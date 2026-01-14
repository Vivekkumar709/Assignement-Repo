# MERN Stack Developer Internship – Assessment

## Section 0: Candidate Details

- **Full Name:** Vivek Kumar  
- **Email Address:** vivekkumar16jun04@gmail.com  
- **College / Company Name:** Dewan VS Institute of Engineering and Technology  
- **GitHub Profile URL:** https://github.com/Vivekkumar709  
- **Internship Batch / Group Name:** MERN Stack Developer / MERN & PERN Full Stack Internship  

---
## Section 1: Git & GitHub

### 1. Difference between Git and GitHub
Git is a version control system that runs on our local machine and helps us track changes in source code. GitHub is an online platform where Git repositories are stored and shared. Git is the tool, while GitHub is the service that provides collaboration, backup, and project management features.

### 2. git clone, git pull, git fetch
`git clone` is used to copy an entire remote repository to the local system for the first time.  
`git fetch` is used to download the latest changes from the remote repository without merging them into the current branch.  
`git pull` fetches the latest changes and immediately merges them into the current working branch.

### 3. Merge conflict and resolution
A merge conflict occurs when Git cannot automatically combine changes from different branches. To resolve it, we manually edit the conflicting files, remove conflict markers, keep the correct code, test the changes, and then commit the final version.

### 4. git merge vs git rebase
`git merge` joins two branches together and keeps the full commit history by creating a merge commit.  
`git rebase` moves commits from one branch onto another and creates a clean, linear commit history.

### 5. Importance of .gitignore
`.gitignore` is used to tell Git which files or folders should not be tracked, such as node_modules, environment files, and logs. It helps keep the repository clean and prevents sensitive or unnecessary files from being committed.

### 6. GitHub Repository Link
https://github.com/Vivekkumar709/Assignement-Repo

---

## Section 2: MySQL & PostgreSQL

### 1. MySQL vs PostgreSQL
MySQL is mostly used for simple and read-heavy applications. PostgreSQL supports advanced features like complex queries, JSON data, and strict SQL standards, making it suitable for large and enterprise-level applications.

### 2. Primary key and foreign key
A primary key uniquely identifies each row in a table and cannot contain null values.  
A foreign key is used to link one table to another by referencing the primary key of another table.

### 3. WHERE vs HAVING
`WHERE` is used to filter rows before grouping the data and cannot use aggregate functions.  
`HAVING` is used to filter grouped data after aggregation and works with functions like COUNT and SUM.

### 4. DELETE vs TRUNCATE
`DELETE` removes selected rows from a table and can be rolled back.  
`TRUNCATE` removes all rows at once, resets auto-increment values, and cannot be rolled back.

### 5. Database normalization
Normalization is the process of organizing data to reduce redundancy and improve data consistency by following normal forms like 1NF, 2NF, and 3NF.

### 6. INNER, LEFT, RIGHT JOIN
INNER JOIN returns only matching records from both tables.  
LEFT JOIN returns all records from the left table and matching records from the right table.  
RIGHT JOIN returns all records from the right table and matching records from the left table.

### 7. SQL Queries
INSERT is used to add new data.  
SELECT is used to fetch data.  
UPDATE is used to modify existing data.  
DELETE is used to remove data.  
JOIN is used to combine data from multiple tables.

---

## Section 3: React Fundamentals

### 1. What is React and why it is used
React is a JavaScript library used to build fast and reusable user interface components. It uses a virtual DOM to improve performance and is commonly used to develop single-page applications.

### 2. State vs Props
State is data that is managed inside a component and can change over time.  
Props are values passed from parent components to child components and cannot be modified by the child.

### 3. React Hooks
React Hooks like `useState`, `useEffect`, and `useContext` allow functional components to use state, lifecycle methods, and shared data.

### 4. useEffect explanation
`useEffect` is used to handle side effects such as API calls, event listeners, and DOM updates. It runs after rendering and depends on the dependency array.

### 5. Lifting state up
Lifting state up means moving shared data to a common parent component so multiple child components can access and use the same state.

### 6. React Practical GitHub Link
https://github.com/Vivekkumar709/react-practice

---

## Section 4: TypeScript Basics

### 1. What is TypeScript
TypeScript is an extension of JavaScript that adds static typing, which helps catch errors at compile time and improves code quality.

### 2. any vs unknown
`any` allows any type of value and removes type safety.  
`unknown` is safer because it requires type checking before using the value.

### 3. Interfaces in TypeScript
Interfaces define the structure of an object and ensure that the correct data types are used.

### 4. Type inference
Type inference allows TypeScript to automatically determine the type of a variable based on its assigned value.

### 5. Optional and readonly properties
Optional properties may or may not be present in an object.  
Readonly properties cannot be changed once they are assigned.

### 6. TypeScript Code / GitHub Link
https://github.com/Vivekkumar709/typescript-practice

---

## Section 5: General Web Development

### 1. REST API
A REST API allows communication between client and server using HTTP methods like GET, POST, PUT, and DELETE.

### 2. PUT vs PATCH
PUT replaces the entire resource with new data.  
PATCH updates only specific fields of a resource.

### 3. CORS
CORS (Cross-Origin Resource Sharing) is a security feature that controls which domains are allowed to access server resources.

### 4. SQL vs NoSQL
SQL databases use structured tables and fixed schemas.  
NoSQL databases are flexible, schema-less, and designed for scalability.

### 5. MVC Architecture
MVC stands for Model, View, and Controller. It separates application logic, user interface, and data handling to make applications easier to manage and maintain.
