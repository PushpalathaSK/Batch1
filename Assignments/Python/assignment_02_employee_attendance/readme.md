# Assignment 02 – Employee Attendance Monitoring System

## Topics Covered

- Conditional Statements (if, elif, else)
- Loops (for, while)
- break
- continue
- pass

---

## Business Scenario

You are working as a Junior Data Analyst in an organization.

The HR department wants a simple Attendance Monitoring System to classify employees based on their attendance percentage and generate a summary report.

---

## Requirements

### Part A – Attendance Classification

Accept attendance percentage for 10 employees.

Classify each employee using the following criteria:

| Attendance % | Category |
|-------------|----------|
| 90 and above | Excellent |
| 75 – 89 | Good |
| Below 75 | Improvement Required |

Display the category for each employee.

---

### Part B – Attendance Summary

Calculate and display:

- Total Employees Processed
- Number of Excellent Employees
- Number of Good Employees
- Number of Employees Requiring Improvement

---

### Part C – Using break

Allow the user to stop data entry at any time.

If the attendance entered is:

```python
-1
```

Stop processing further records using `break`.

---

### Part D – Using continue

If attendance entered is:

```python
0
```

Skip the current record and continue processing the next employee using `continue`.

---

### Part E – Using pass

Create a placeholder block for future functionality.

Example:

```python
if attendance > 100:
    pass
```

Add a comment explaining what validation could be added in the future.

---

## Sample Input

```text
Employee 1 Attendance: 95
Employee 2 Attendance: 82
Employee 3 Attendance: 65
Employee 4 Attendance: 0
Employee 5 Attendance: 91
Employee 6 Attendance: -1
```

---

## Sample Output

```text
Employee 1 : Excellent
Employee 2 : Good
Employee 3 : Improvement Required

Attendance Summary

Total Employees Processed : 4
Excellent : 2
Good : 1
Improvement Required : 1
```

---

## Deliverables

1. Python Program
2. Screenshot of Output
3. README.md explaining the approach
4. Upload to Personal GitHub Repository

---

## Bonus Task

Generate additional insights:

- Highest Attendance Percentage
- Lowest Attendance Percentage
- Average Attendance Percentage
- Percentage of Employees in Each Category

---

## Learning Outcomes

After completing this assignment, you should be able to:

- Use if, elif, else for decision making
- Use for loops for repeated processing
- Use while loops for user-controlled execution
- Apply break to terminate loops
- Apply continue to skip iterations
- Understand the purpose of pass
- Build simple business logic using Python