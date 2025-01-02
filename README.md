# Healthcare Patient Waiting List Analysis

## Project Description
This project is based on the analysis of healthcare data for both inpatient and outpatient waiting lists of patients from 2018 to 2021. Emphasis will be put on mastering Power BI by creating an interactive dashboard with advanced visuals, DAX measures, and dynamic filtering.

---

## Data Overview
- **Categories**: Inpatient and Outpatient
- **Time Period**: 2018–2021
- **Data Source**: Publicly available healthcare datasets
- **Folder Structure**:
  - **Inpatient Folder**: This folder contains annual data files for inpatient waiting lists from 2018 to 2021.
  - **Outpatient Folder**: This folder contains annual data files for outpatient waiting lists, 2018–2021.
  - **Mapping_Speciality File**: This enables the mapping of specialties and their categorized groups for better analysis.

The data files are available in this repository.

---

## Objectives
1. Design an interactive Power BI dashboard that demonstrates comprehensive data visualization and analysis skills.
2. Highlight the trends in the waiting lists for both inpatient and outpatient categories.
3. Provide filters and tools that will allow users to explore the data on their own.

---

## Data Preparation
### Steps Taken
1. **Import and Organize**:
   - Data was then organized into different folders for inpatient and outpatient datasets.
   - Ensured column headers were the same throughout all files for seamless integration.

2. **Data Cleaning**:
   - Standardized data types and removed irrelevant or redundant columns.
   - Renamed the `Speciality` column in outpatient datasets to `Specialty_Name` for consistency with naming convention used for inpatient datasets.
   - Added a `Case_Type` column in the outpatient dataset with the value "Outpatient."
   - Standardized the values in the `Time_Bands` column for proper analysis.

3. **Merging of Data**:
   - Combined inpatient and outpatient datasets into a single table called `AllData` while preserving the original datasets for validation.

---

## Data Modeling
- Established relationships between `AllData` and the `Mapping_Speciality` file using the column `Specialty_Name`.
- Created calculated measures using DAX language to derive insights dynamically.

---

## How to Access the Dashboard

The Power BI Dashboard file (`Healthcare_Waiting_List_Dashboard.pbix`) is included in this repository. Follow these steps to access and use the dashboard:

### 1. **Download Power BI Desktop**
   - If you don't already have Power BI Desktop installed, you can download it for free from the official [Power BI website](https://powerbi.microsoft.com/desktop/).

### 2. **Download the `.pbix` File**
   - Go to the repository and find the file: `Healthcare_Waiting_List_Dashboard.pbix`.
   - Download the file to your local computer.

### 3. **Open the File in Power BI Desktop**
   - Launch Power BI Desktop.
   - Open the `.pbix` file downloaded using **File > Open**.

---

## Tools and Technologies
- **Power BI**: Data integration, DAX calculations, and developing interactive dashboards.
- **CSV Files**: Used for storing and mapping specialty data.
