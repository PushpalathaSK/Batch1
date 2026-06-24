# Assignment 04 – Sales Performance Analysis Utility

## Topics Covered

- Functions
- Function Arguments
- Return Values
- Lambda Functions
- Recursion (Basic)
- Built-in Modules
- Creating Custom Modules

---

## Business Scenario

You are working as a Junior Data Analyst for a retail company.

The Sales Manager wants a Python utility that can perform basic sales analysis and generate business metrics automatically.

Instead of writing repetitive code, the company wants reusable functions and modules that can be used across multiple reports.

---

## Requirements

### Dataset

Use the following sample sales data:

```python
sales = [12000, 15000, 18000, 9000, 21000, 17000]
```

---

## Part A – Functions

Create the following functions:

### 1. Calculate Total Sales

Function Name:

```python
calculate_total_sales()
```

Output:

```text
92000
```

---

### 2. Calculate Average Sales

Function Name:

```python
calculate_average_sales()
```

Output:

```text
15333.33
```

---

### 3. Find Highest Sale

Function Name:

```python
find_highest_sale()
```

Output:

```text
21000
```

---

### 4. Find Lowest Sale

Function Name:

```python
find_lowest_sale()
```

Output:

```text
9000
```

---

## Part B – Function Arguments & Return Values

Create a function:

```python
sales_growth(current_month, previous_month)
```

Return growth percentage.

Example:

```python
sales_growth(25000, 20000)
```

Output:

```text
25%
```

---

## Part C – Lambda Functions

Create Lambda Functions for:

### 1. Calculate Discounted Price

```python
discount = lambda amount: amount * 0.9
```

---

### 2. Convert Customer Names to Uppercase

Example:

```python
customers = ["john", "mary", "david"]
```

Expected Output:

```python
['JOHN', 'MARY', 'DAVID']
```

---

### 3. Sort Products by Price

Use Lambda inside:

```python
sorted()
```

---

## Part D – Recursion (Basic)

The Finance Team wants to calculate factorial values for forecasting scenarios.

Create a recursive function:

```python
factorial(n)
```

Example:

```python
factorial(5)
```

Output:

```text
120
```

---

### Additional Task

Create a recursive countdown:

```python
countdown(10)
```

Output:

```text
10
9
8
7
...
1
```

---

## Part E – Built-in Modules

Use the following modules:

### Math Module

Calculate:

- Square Root of 144
- Power of 5²

---

### Statistics Module

Using sales data:

Calculate:

- Mean
- Median

---

### Datetime Module

Display:

- Current Date
- Current Time

---

### Random Module

Generate:

- Random Customer ID
- Random Discount Percentage

---

## Part F – Creating Custom Modules

Create a custom module named:

```text
sales_utils.py
```

Include:

```python
calculate_total_sales()

calculate_average_sales()

find_highest_sale()

find_lowest_sale()
```

---

Create another file:

```text
main.py
```

Import the module and generate a Sales Performance Report.

---

## Business Analysis Questions

Generate answers for the following:

1. What is the total sales revenue?
2. What is the average sales value?
3. What is the highest sale recorded?
4. What is the lowest sale recorded?
5. What is the sales growth percentage compared to the previous month?
6. What business actions would you recommend based on the sales performance?

---

## Sample Output

```text
Sales Performance Report

Total Sales: ₹92,000

Average Sales: ₹15,333.33

Highest Sale: ₹21,000

Lowest Sale: ₹9,000

Current Date: 24-06-2026

Sales Growth: 25%
```

---

## Deliverables

1. sales_utils.py
2. main.py
3. Screenshot of Output
4. README.md explaining the solution
5. Upload to Personal GitHub Repository

---

## Bonus Task

Create a menu-driven application:

1. Total Sales
2. Average Sales
3. Highest Sale
4. Lowest Sale
5. Sales Growth
6. Exit

The user should be able to select options and view the corresponding analysis.

---

## Learning Outcomes

After completing this assignment, you should be able to:

- Create reusable functions.
- Work with arguments and return values.
- Use lambda functions for quick transformations.
- Understand basic recursion.
- Use built-in Python modules.
- Create and import custom modules.
- Build reusable business analysis utilities.