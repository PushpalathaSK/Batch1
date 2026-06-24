# Assignment 05 – Customer Feedback Processing System

## Topics Covered

- Reading Files (txt, csv)
- Writing Files (txt, csv)
- Exception Handling
  - try
  - except
  - finally
- Handling Real-World Data Errors

---

## Business Scenario

You are working as a Junior Data Analyst for a Customer Support Company.

Every day, customer feedback is received and stored in files. The management team wants an automated system that can read customer feedback data, handle invalid records, generate summary reports, and save the results for future analysis.

Your task is to develop a Customer Feedback Processing System using Python.

---

## Dataset

### feedback.csv

```csv
Customer_ID,Customer_Name,Rating
C101,John,5
C102,Mary,4
C103,David,
C104,Alex,abc
C105,Sarah,3
```

---

## Part A – Reading Files

### Task 1

Read the contents of a text file:

```text
company_notice.txt
```

Display the contents on the screen.

---

### Task 2

Read the customer feedback data from:

```text
feedback.csv
```

Display all records.

---

## Part B – Writing Files

Generate a report file:

```text
feedback_summary.txt
```

The report should contain:

- Total Customers
- Valid Ratings
- Invalid Ratings
- Average Rating

---

### Sample Output

```text
Customer Feedback Summary

Total Customers : 5

Valid Ratings : 3

Invalid Ratings : 2

Average Rating : 4.0
```

---

## Part C – Exception Handling

Implement proper exception handling for the following situations.

### Scenario 1 – Missing File

If the feedback file is not available:

```python
FileNotFoundError
```

Display:

```text
Feedback file not found.
```

---

### Scenario 2 – Invalid Rating

Example:

```text
abc
```

Use:

```python
ValueError
```

Display:

```text
Invalid rating found.
```

---

### Scenario 3 – Empty Rating

Example:

```text
(blank value)
```

Handle the record appropriately and continue processing.

---

## Part D – Using finally

Display a completion message irrespective of success or failure.

Example:

```text
Processing Completed
```

---

## Part E – Real-World Data Cleaning

Before calculating statistics:

### Validate Ratings

Accept only:

```text
1 to 5
```

Ignore:

- Blank values
- Text values
- Negative values
- Values greater than 5

---

### Calculate

1. Total Customers
2. Total Valid Ratings
3. Total Invalid Ratings
4. Average Rating
5. Highest Rating
6. Lowest Rating

---

## Part F – Save Processed Data

Create:

```text
clean_feedback.csv
```

Store only valid records.

Example:

```csv
Customer_ID,Customer_Name,Rating
C101,John,5
C102,Mary,4
C105,Sarah,3
```

---

## Business Analysis Questions

Answer the following:

1. How many customer records were received?
2. How many valid ratings were available?
3. How many records contained errors?
4. What is the average customer satisfaction rating?
5. What recommendations would you provide to improve data quality?

---

## Sample Report

```text
Customer Feedback Processing Report

Total Records : 5

Valid Records : 3

Invalid Records : 2

Average Rating : 4.0

Highest Rating : 5

Lowest Rating : 3

Processing Completed Successfully
```

---

## Deliverables

### Files Required

1. feedback_processor.py
2. feedback.csv
3. clean_feedback.csv
4. feedback_summary.txt
5. README.md

---

## GitHub Repository Structure

```text
assignment_05_customer_feedback_processing/
│
├── feedback.csv
├── feedback_processor.py
├── clean_feedback.csv
├── feedback_summary.txt
└── README.md
```

---

## Bonus Task

Generate a separate file:

```text
error_log.txt
```

Store all invalid records along with the reason.

Example:

```text
C103 - Missing Rating

C104 - Invalid Rating Format
```

---

## Learning Outcomes

After completing this assignment, you should be able to:

- Read data from text and CSV files.
- Write processed results to files.
- Handle runtime errors using try-except.
- Use finally for cleanup activities.
- Validate and clean real-world business data.
- Generate automated reports for business users.
- Build reliable data-processing programs.