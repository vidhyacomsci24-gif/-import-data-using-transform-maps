# Project Development Phase

## Project Title
Import Data Using Transform Maps

## 1. Development Overview

The project is developed using ServiceNow Import Sets and Transform Maps to import external data and transfer it into the required target table.

## 2. Development Steps

### Step 1: Prepare Source Data
Prepare the required data in a CSV or Excel file with the necessary fields.
<img width="1366" height="768" alt="Screenshot 2026-09-23 202011" src="https://github.com/user-attachments/assets/8747d4dc-a4b7-4ffd-a199-a3f341c8e614" />


### Step 2: Create Data Source
Create a Data Source in ServiceNow and configure the source file for importing the data.

![Uploading Screenshot 2026-09-23 202140.png…]()


### Step 3: Import the Data
Upload the source file and run the import process.

<img width="1366" height="768" alt="Screenshot 2026-09-23 203935" src="https://github.com/user-attachments/assets/13048f37-1d1c-4596-9987-573bddb61580" />



### Step 4: Create Import Set
Create an Import Set to store the imported source data temporarily.

<img width="1366" height="768" alt="Screenshot 2026-09-23 203242" src="https://github.com/user-attachments/assets/0e0b923c-6733-4eb1-9e28-7ecc75edfb2e" />

### Step 5: Create Transform Map
Create a Transform Map and select the required source table and target table.

<img width="1366" height="768" alt="Screenshot 2026-09-23 204238" src="https://github.com/user-attachments/assets/f47eacf2-21ab-47f1-b003-6fe2f1241c45" />


### Step 6: Configure Field Mapping
Map the source fields to their corresponding target fields.

<img width="1366" height="768" alt="Screenshot 2026-09-23 204305" src="https://github.com/user-attachments/assets/faeb4c4e-143d-4e6c-a9d1-d787114e496b" />


Example:

| Source Field | Target Field |
|---|---|
| Name | Name |
| Email | Email |
| Department | Department |
| Location | Location |

### Step 7: Run Transformation
Run the Transform Map to transfer the data from the Import Set table to the target table.




### Step 8: Verify Records
Check the target table and verify that the records have been imported correctly.

<img width="1366" height="545" alt="Screenshot 2026-09-26 123732" src="https://github.com/user-attachments/assets/b89d3779-8067-4ffa-ae04-29dcbf917950" />


## 3. Development Components

- Data Source
- Import Set
- Import Set Table
- Transform Map
- Field Maps
- Target Table

## 4. Expected Development Output

The source data should be successfully imported, transformed, and stored in the selected ServiceNow target table.

## 5. Development Verification

The imported records should be checked to ensure that:

- All required records are available.
- Source fields are mapped correctly.
- Target fields contain the expected values.
- No major transformation errors are present.

## 6. Conclusion

The development phase implements the complete data import process using ServiceNow Import Sets and Transform Maps. The developed process provides a structured way to import and transform external data into ServiceNow.
