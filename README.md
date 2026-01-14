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
Git is a distributed version control system used to track code changes locally. GitHub is a cloud-based platform that hosts Git repositories and provides collaboration features such as pull requests, issues, code reviews, and CI/CD integration.

### 2. git clone, git pull, git fetch
`git clone` creates a local copy of a remote repository. `git pull` fetches changes from the remote repository and merges them into the current branch. `git fetch` only downloads updates without merging, allowing review before integration.

### 3. Merge conflict and resolution
A merge conflict occurs when Git cannot automatically merge changes from different branches. It is resolved by manually editing conflicting files, selecting the correct code, removing conflict markers, testing changes, and committing the resolved version.

### 4. git merge vs git rebase
`git merge` combines branches and preserves commit history by creating a merge commit. `git rebase` rewrites commit history by applying commits sequentially on another branch, resulting in a cleaner and linear history.

### 5. .gitignore importance
`.gitignore` specifies files and directories Git should not track, such as node_modules, environment files, and logs. It keeps repositories clean, improves security, and avoids committing unnecessary or sensitive files.

### 6. GitHub Repository Link
*(Paste your assessment repository link here)*

---

## Section 2: MySQL & PostgreSQL

### 1. MySQL vs PostgreSQL
MySQL is commonly used for simple, read-heavy applications. PostgreSQL supports advanced features such as complex queries, JSON data types, and strict SQL standards, making it suitable for enterprise-level applications.

### 2. Primary key and foreign key
A primary key uniquely identifies each record in a table and cannot be null. A foreign key references a primary key from another table, maintaining relationships and referential integrity.

### 3. WHERE vs HAVING
`WHERE` filters rows before grouping and cannot use aggregate functions. `HAVING` filters grouped results after aggregation and works with functions like COUNT and SUM.

### 4. DELETE vs TRUNCATE
`DELETE` removes selected rows and can be rolled back. `TRUNCATE` deletes all rows quickly, resets identity counters, and cannot be rolled back.

### 5. Database normalization
Database normalization organizes data to reduce redundancy and improve data integrity by following normal forms such as 1NF, 2NF, and 3NF.

### 6. INNER, LEFT, RIGHT JOIN
INNER JOIN returns matching rows from both tables. LEFT JOIN returns all rows from the left table. RIGHT JOIN returns all rows from the right table.

### 7. SQL Queries
INSERT adds new records, SELECT retrieves data, UPDATE modifies existing records, DELETE removes records, and JOIN combines data from multiple tables.

---

## Section 3: React Fundamentals

### 1. What is React and why used
React is a JavaScript library used to build reusable UI components. It uses a virtual DOM to improve performance and is widely used for scalable single-page applications.

### 2. State vs Props
State is mutable data managed within a component. Props are immutable values passed from parent to child components.

### 3. React hooks
React hooks like `useState`, `useEffect`, and `useContext` allow functional components to manage state and lifecycle features.

### 4. useEffect explanation
`useEffect` handles side effects such as API calls and DOM updates. It runs after render and depends on a dependency array.

### 5. Lifting state up
Lifting state up moves shared state to a common parent component so child components can access the same data.

### 6. React Practical GitHub Link
*(Paste your React project link here)*

---

## Section 4: TypeScript Basics

### 1. What is TypeScript
TypeScript is a superset of JavaScript that adds static typing and compile-time error checking for better scalability.

### 2. any vs unknown
`any` disables type safety, while `unknown` requires type checking before use.

### 3. Interfaces in TypeScript
Interfaces define the structure of objects and enforce consistent data types.

### 4. Type inference
Type inference allows TypeScript to automatically detect variable types based on assigned values.

### 5. Optional and readonly properties
Optional properties may or may not exist. Readonly properties cannot be modified after initialization.

### 6. TypeScript Code / GitHub Link
*(Paste your TypeScript project link here)*

---

## Section 5: General Web Development

### 1. REST API
A REST API enables communication between client and server using HTTP methods like GET and POST.

### 2. PUT vs PATCH
PUT replaces an entire resource, while PATCH updates specific fields.

### 3. CORS
CORS controls cross-origin requests to protect web applications.

### 4. SQL vs NoSQL
SQL databases use structured schemas, while NoSQL databases are schema-less and scalable.

### 5. MVC Architecture
MVC separates applications into Model, View, and Controller layers for better organization.
