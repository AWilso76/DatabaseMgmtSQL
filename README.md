# 💾 Database Management Using SQL**

# Overview
This project demonstrates how to use **SQL queries** to retrieve and analyze data efficiently from relational databases.  
The queries are designed to simulate real-world scenarios such as reviewing login attempts, analyzing department data, 
and filtering based on time or region.

# Objectives
- Retrieve specific data based on logical conditions  
- Use filtering, grouping, and sorting clauses  
- Analyze and interpret the results for business insights  

# Tools & Technologies
- **Language:** SQL  
- **Environment:** MySQL 
- **Files:** `.SQL` scripts for each scenario  

# Relevance to IT Support / Applications Analyst Role
Database query skills are essential for supporting enterprise applications and resolving user issues.  
This project demonstrates:
- Ability to navigate and extract information from complex datasets  
- Familiarity with query optimization and data analysis  
- Translating business questions into technical SQL statements  

# Example Queries

-- Retrieve login attempts after 6 PM
SELECT * FROM LoginAttempts
WHERE LoginTime > '18:00:00';

-- List employees not in the IT Department
SELECT EmployeeName, Department
FROM Employees
WHERE Department <> 'Information Technology';

# Example Results

| EmployeeName | Department | LoginTime |
| ------------ | ---------- | --------- |
| John Doe     | Radiology  | 18:32:15  |
| Maria Lee    | Nursing    | 20:04:27  |


# Future Enhancements

- Create stored procedures and views for repeated queries

- Implement role-based access and security filters

- Build a dashboard in Power BI or Excel for visual reporting


# Screenshots

---

## Login Attempts After 6 PM:
This query retrieves all login attempts made after 6 PM, demonstrating the ability to filter data based on time conditions.

<img width="1000" alt="image" src="https://i.imgur.com/9WjIyqe.png">
---

## Login Attempts on Two Specific Dates:
A query designed to extract all login attempts made on two different dates. This highlights my capability to handle multiple condition-based filtering.

<img width="1000" alt="image" src="https://i.imgur.com/gmYl3tB.png">
---

## Login Attempts Excluding a Specific Country (Mexico):
The query retrieves login attempts from all countries except Mexico, showcasing the use of exclusion conditions.

<img width="1000" alt="image" src="https://i.imgur.com/g7jNU9i.png">
---

## Employees in the Finance and Sales Departments Only:
This query focuses on retrieving records for employees belonging to the Finance and Sales departments, illustrating department-specific filtering.

<img width="1000" alt="image" src="https://i.imgur.com/HNCnf2F.png">
---

## Employees Excluding the Information Technology Department:
The query excludes employees from the Information Technology department, demonstrating how SQL can be used to manage exclusions at a department level.

<img width="51000" alt="image" src="https://i.imgur.com/v6sE7lD.png">


