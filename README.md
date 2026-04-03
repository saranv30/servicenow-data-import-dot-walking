# Automating Data Import and Relationship Mapping Using Import Sets & Dot Walking

## Project Overview

This project demonstrates how to automate employee data import into ServiceNow and establish relationships between records using **Import Sets, Transform Maps, and Dot Walking**.

The goal is to eliminate manual data entry, reduce errors, and improve data accessibility in enterprise systems.

---

## Objectives

* Automate employee data import process
* Ensure accurate relationship mapping
* Reduce manual effort and errors
* Improve data accessibility using Dot Walking

---

## Tools & Technologies

* ServiceNow
* Google Sheets
* CSV File Format
* Import Sets
* Transform Maps
* Dot Walking

---

## Dataset

The dataset was created using Google Sheets with the following fields:

* Name
* Email
* Department
* Manager
* Phone Number

---

## Project Workflow

### 1. Data Preparation

* Created employee dataset in Google Sheets
* Exported data as CSV file

### 2. Import Set Creation

* Uploaded CSV into ServiceNow
* Created staging table (`import_employee`)

### 3. Transform Map Configuration

* Mapped source table to target table (`sys_user`)
* Used Auto Map and Mapping Assist

### 4. Field Mapping

* Mapped fields like name, email, department
* Handled reference fields (manager, department)

### 5. Data Transformation

* Executed transform
* Verified records in target table

### 6. Dot Walking Implementation

* Configured Incident form
* Accessed fields like:

  * Assigned to.department
  * Assigned to.email
  * Assigned to.manager

---

## Screenshots

### Import Set Creation

![Import Set](images/import_set.png)

### Transform Map

![Transform Map](images/transform_map.png)

### Field Mapping

![Mapping Assist](images/mapping.png)

### Dot Walking

![Dot Walking](images/dot_walking.png)

---

## Results

* Successfully automated data import process
* Reduced manual errors
* Improved data consistency
* Enabled dynamic data retrieval using Dot Walking

---

## Challenges

* Handling reference fields correctly
* Avoiding duplicate records
* Ensuring accurate field mapping

---

## Future Enhancements

* Schedule automated imports
* Integrate with external systems
* Add validation rules for better data quality

---

## Conclusion

This project highlights the importance of automation in data management. Using ServiceNow features like Import Sets and Dot Walking improves efficiency, accuracy, and scalability.

---

## 👤 Author

**Your Name**

---
