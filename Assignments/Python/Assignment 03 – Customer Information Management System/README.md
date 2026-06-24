# Assignment 03 – Customer Information Management System

## Topics Covered

- Strings and String Methods
- Lists and List Methods
- Tuples
- Sets
- Dictionaries

---

## Business Scenario

You are working as a Junior Data Analyst for a Customer Support Company.

The management team wants a simple system to store and analyze customer information. The objective is to organize customer data, identify unique customers, and generate basic business insights using Python data structures.

---

## Requirements

### Part A – Customer Name Processing (Strings)

Create a program that accepts a customer name and performs the following operations:

1. Convert the name to uppercase.
2. Convert the name to lowercase.
3. Remove leading and trailing spaces.
4. Count the number of characters.
5. Check whether a specific word exists in the customer name.

Example:

```text
Input:
"  John Smith  "

Output:
JOHN SMITH
john smith
John Smith
Length: 10
```

---

### Part B – Customer List Management (Lists)

Create a list containing customer names.

Perform the following operations:

1. Add a new customer.
2. Remove a customer.
3. Sort customers alphabetically.
4. Display total number of customers.
5. Display the first and last customer.

Example:

```python
customers = ["John", "Mary", "David"]
```

---

### Part C – Company Information (Tuples)

Store company information using a tuple.

Information:

- Company Name
- Location
- Establishment Year

Example:

```python
company = ("ABC Support Services", "Coimbatore", 2015)
```

Tasks:

1. Display all values.
2. Access individual elements.
3. Display company age.

---

### Part D – Unique Customer Cities (Sets)

The company receives customers from multiple cities.

Store city names in a set.

Example:

```python
cities = {"Chennai", "Coimbatore", "Madurai", "Chennai"}
```

Tasks:

1. Display all unique cities.
2. Count unique cities.
3. Add a new city.
4. Remove a city.
5. Check whether a city exists.

---

### Part E – Customer Details (Dictionaries)

Store customer information using a dictionary.

Example:

```python
customer = {
    "Customer_ID": "C101",
    "Name": "John",
    "City": "Chennai",
    "Satisfaction_Rating": 4.5
}
```

Tasks:

1. Display all customer details.
2. Update satisfaction rating.
3. Add a new field:
   - Membership Type
4. Remove a field.
5. Display all keys and values separately.

---

## Business Analysis Tasks

Using the above data structures, answer the following questions:

1. How many customers are stored in the system?
2. How many unique cities are represented?
3. Which customer has the highest satisfaction rating?
4. Generate a simple customer summary report.
5. Identify duplicate customer cities and store only unique cities.

---

## Sample Output

```text
Customer Summary Report

Total Customers : 5
Unique Cities : 3

Cities:
Chennai
Coimbatore
Madurai

Highest Satisfaction Rating:
Mary - 4.8

Company:
ABC Support Services
Coimbatore
Established: 2015
```

---

## Deliverables

1. Python Program
2. Screenshot of Output
3. README.md explaining the approach
4. Upload to Personal GitHub Repository

---

## Bonus Task

Create a customer search feature:

- User enters Customer ID.
- Display corresponding customer details.
- If customer not found, display an appropriate message.

---

## Learning Outcomes

After completing this assignment, you should be able to:

- Manipulate strings using built-in methods.
- Store and manage collections using lists.
- Use tuples for fixed information.
- Use sets to maintain unique values.
- Use dictionaries to store structured business data.
- Solve simple business problems using Python data structures.