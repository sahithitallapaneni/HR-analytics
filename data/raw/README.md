# Raw Data Folder

This folder contains the **raw HR datasets** used as input for the HR analytics capstone project.  
All files here are unmodified, representing typical outputs from HRIS, ATS, and other HR systems.

## Folder Structure

### 1. ATS Dataset
Datasets available in kaggle extracted from the Applicant Tracking System and HR development tools. Includes:

- `recruitment_data`  
  Candidate applications, interviews, offers, hires, and source of hire metrics.

- `training_and_development_data`  
  Employee training programs, participation, completion, and outcomes.

- `employee_engagement_survey_data`  
  Survey responses related to employee engagement, satisfaction, and workplace sentiment.

- `employee_data`  
  Basic employee information from the HRIS, including demographics, job details, hire and termination dates.

### 2. Attrition Dataset
- `HR-Employee-Attrition`  
  Historical attrition data including employee tenure, termination type, reasons for leaving, and other relevant metrics.

## Data Characteristics
- May contain missing or inconsistent values
- Mixed formats for dates, text, and numeric fields
- Naming inconsistencies or duplicate entries reflecting real-world HR systems

## Workflow
All data cleaning, transformation, and feature engineering is performed in `notebooks/data_cleaning.ipynb`.  
Cleaned datasets are saved to `data/cleaned/` for analysis and dashboard development.
