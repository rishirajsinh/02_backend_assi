# Student API 🚀

## 📌 Project Title
Student REST API using Node.js and Express.js

---

## 📌 Objective

The objective of this project is to build a REST API using Express.js to manage student data. This API allows users to retrieve student records, calculate average CGPA, find toppers, count students, and filter students by branch or ID.

---

## 📌 Technologies Used

- Node.js
- Express.js
- Postman
- GitHub

---

## 📌 Implemented Routes

| Method | Route | Description |
|-------|------|-------------|
| GET | / | Home Route |
| GET | /students | Get all students |
| GET | /students/:id | Get student by ID |
| GET | /students/topper | Get Topper Student |
| GET | /students/average | Get Average CGPA |
| GET | /students/count | Get Total Students |
| GET | /students/branch/:branchName | Get Students by Branch |

---

## 📌 Sample API URLs

### Home Route
http://localhost:3000/

### Get All Students
http://localhost:3000/students

### Get Student by ID
http://localhost:3000/students/1

### Get Topper Student
http://localhost:3000/students/topper

### Get Average CGPA
http://localhost:3000/students/average

### Get Total Students
http://localhost:3000/students/count

### Get Students by Branch
http://localhost:3000/students/branch/cse

---

## 📌 Steps to Run Locally

### Step 1 - Clone Repository


git clone https://github.com/yourusername/student-api.git


### Step 2 - Open Project Folder


cd student-api


### Step 3 - Install Dependencies


npm install


### Step 4 - Run Server


node index.js


OR


npm run dev


### Step 5 - Open Browser


http://localhost:3000


---

## 📌 Postman Documentation Link

https://documenter.getpostman.com/view/50840970/2sBXcGCzAc

---

## 📌 Deployed API Link

https://student-cgpa-api-zcgm.onrender.com/

Example:

https://student-api.onrender.com

---

## 📌 Project Structure


student-api/
│
├── index.js
├── package.json
├── package-lock.json
├── .gitignore
├── README.md
└── node_modules/


---

## 📌 Author

Rishirajsingh Rathore

---

## 📌 Project Status

Completed ✅
