# Project Testing Phase

## Project Title
Import Data Using Transform Maps

## 1. Testing Overview

The testing phase is performed to verify that the data is imported, transformed, and stored correctly in the ServiceNow target table.

## 2. Test Cases

| Test Case | Test Description | Expected Result | Status |
|---|---|---|---|
| TC01 | Upload the source data file | File should be uploaded successfully | Pass |
<img width="1366" height="768" alt="Screenshot 2026-09-23 202011" src="https://github.com/user-attachments/assets/781c36a9-d50e-41fc-9690-221c7bac0690" />

| TC02 | Create Import Set | Import Set should be created successfully | Pass |
<img width="1366" height="768" alt="Screenshot 2026-09-23 203423" src="https://github.com/user-attachments/assets/389b1091-34aa-493a-9d19-d653b5109e81" />

| TC03 | Import source records | Records should be imported into the Import Set table | Pass |
<img width="1366" height="768" alt="Screenshot 2026-09-23 203935" src="https://github.com/user-attachments/assets/6cae65b3-d282-40a5-abd5-8f82d42c8b37" />

| TC04 | Create Transform Map | Transform Map should be created successfully | Pass |
<img width="1366" height="768" alt="Screenshot 2026-09-23 203610" src="https://github.com/user-attachments/assets/8aca2648-7ccd-4fc1-8f82-f0c23a3d461f" />

| TC05 | Configure field mapping | Source fields should map to target fields correctly | Pass |
<img width="1366" height="768" alt="Screenshot 2026-09-23 204238" src="https://github.com/user-attachments/assets/020e577d-d19d-4195-8070-ee8fefa20e7b" />

| TC06 | Run transformation | Records should be transferred to the target table | Pass |
<img width="1366" height="768" alt="Screenshot 2026-09-23 205357" src="https://github.com/user-attachments/assets/873376f4-2607-4b98-a503-f9a0bb7fb706" />

| TC07 | Verify target records | Imported records should contain correct values | Pass |

![Uploading Screenshot 2026-09-26 123732.png…]()


## 3. Testing Process

1. Prepare the source data.
2. Upload the data into ServiceNow.
3. Verify the Import Set records.
4. Check the Transform Map configuration.
5. Verify all field mappings.
6. Run the transformation.
7. Open the target table.
8. Compare the target records with the source data.
9. Check for any transformation errors.

## 4. Expected Test Results

The source records should be successfully imported and transformed into the target table. The mapped fields should contain the correct values and the transformation should complete without unexpected errors.

## 5. Error Handling

If an error occurs during transformation:

- Check the source data.
- Verify the field mappings.
- Check the Transform Map configuration.
- Review the import and transformation logs.
- Correct the issue and run the transformation again.

## 6. Conclusion

Testing confirms that the Import Data Using Transform Maps process works as expected and that the imported records are correctly available in the ServiceNow target table.
