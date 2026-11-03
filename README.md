# 🚀 Reqres API Testing Project | Postman

![Postman](https://img.shields.io/badge/Tool-Postman-orange?logo=postman\&logoColor=white)
![API Testing](https://img.shields.io/badge/Testing-API%20Testing-blue)
![HTTP](https://img.shields.io/badge/Protocol-HTTP-green)
![Status](https://img.shields.io/badge/Project-Completed-success)

## 📌 Project Overview

This project demonstrates **REST API testing using Postman** with the Reqres API.

The project covers the execution and validation of different HTTP methods, response status codes, response times, JSON response data, and automated test scripts.

The objective is to understand API testing fundamentals and demonstrate practical testing skills.

## 🎯 Project Objectives

* Understand REST API concepts.
* Test APIs using different HTTP methods.
* Validate HTTP response status codes.
* Verify JSON response data.
* Validate API response time.
* Write automated test scripts using Postman.
* Understand CRUD operations.
* Document API testing results with screenshots.

## 🛠️ Tools & Technologies

| Tool       | Purpose                             |
| ---------- | ----------------------------------- |
| Postman    | API testing and automation          |
| Reqres API | Sample REST API                     |
| JavaScript | Writing API test scripts            |
| JSON       | Request and response data           |
| GitHub     | Project documentation and portfolio |

## 🌐 API Information

**Base URL:** `https://reqres.in/api`

**API Endpoints Tested:**

| HTTP Method | Endpoint        | Description                  |
| ----------- | --------------- | ---------------------------- |
| GET         | `/users?page=2` | Retrieve all users on page 2 |
| GET         | `/users/2`      | Retrieve a single user       |
| POST        | `/users`        | Create a new user            |
| PUT         | `/users/2`      | Update an existing user      |
| PATCH       | `/users/2`      | Partially update a user      |
| DELETE      | `/users/2`      | Delete a user                |

## 🧪 API Testing Details

### 1️⃣ GET – Retrieve Single User

* Verified HTTP status code: `200 OK`
* Validated response time.
* Verified user ID.
* Verified first name.
* Verified email presence.

**Test Results: 5/5 Passed**

### 2️⃣ POST – Create User

* Verified HTTP status code: `201 Created`
* Validated response time.
* Verified user name.
* Verified job information.
* Verified generated user ID.
* Verified created date.

**Test Results: 6/6 Passed**

### 3️⃣ PUT – Update User

* Verified HTTP status code: `200 OK`
* Validated response time.
* Verified updated user name.
* Verified updated job information.

**Test Results: 4/4 Passed**

### 4️⃣ PATCH – Partially Update User

* Verified HTTP status code: `200 OK`
* Validated response time.
* Verified updated job information.
* Verified updated date.

**Test Results: 4/4 Passed**

### 5️⃣ DELETE – Delete User

* Verified HTTP status code: `204 No Content`
* Validated response time.

**Test Results: 2/2 Passed**

### 6️⃣ GET – Retrieve All Users

* Executed GET request to retrieve users.
* Verified successful response: `200 OK`.
* Observed page 2 containing 6 users.
* API response indicated 12 users in total.

## 📊 Automated Test Execution Summary

| API Request                    |     Test Results |
| ------------------------------ | ---------------: |
| GET – Single User              |       5/5 Passed |
| POST – Create User             |       6/6 Passed |
| PUT – Update User              |       4/4 Passed |
| PATCH – Update User            |       4/4 Passed |
| DELETE – Delete User           |       2/2 Passed |
| **Total automated assertions** | **21/21 Passed** |

*Note: The 21 assertions are from the five requests with visible Postman test results. The GET All Users request was also executed successfully, but its assertion count is not included.*

## 📸 Screenshots & Test Evidence

The following screenshots demonstrate the API requests, responses, and automated test results.

### 1. GET – Retrieve All Users

![GET All Users](Screenshots/GET-All-Users.png)

### 2. GET – Retrieve Single User

![GET Single User](Screenshots/GET-Single-User.png)

### 3. POST – Create User

![POST Create User](Screenshots/POST-Create-User.png)

### 4. PUT – Update User

![PUT Update User](Screenshots/PUT-Update-User.png)

### 5. PATCH – Partially Update User

![PATCH Update User](Screenshots/PATCH-Update-User.png)

### 6. DELETE – Delete User

![DELETE User](Screenshots/DELETE-User.png)

## 📂 Project Structure

```text
Reqres-API-Testing/
│
├── Screenshots/
│   ├── GET-All-Users.png
│   ├── GET-Single-User.png
│   ├── POST-Create-User.png
│   ├── PUT-Update-User.png
│   ├── PATCH-Update-User.png
│   └── DELETE-User.png
│
├── Reqres-API-Testing.postman_collection.json
│
└── README.md
```

## 💡 Key Learnings

Through this project, I gained practical experience in:

* Understanding REST API architecture.
* Working with GET, POST, PUT, PATCH, and DELETE methods.
* Sending API requests through Postman.
* Validating HTTP status codes.
* Writing JavaScript-based automated test scripts.
* Verifying JSON response attributes.
* Checking API response time.
* Organizing API requests into Postman collections.
* Documenting testing activities and results.

## 🔮 Future Enhancements

* Add negative test scenarios.
* Perform API testing with different test data.
* Add JSON schema validation.
* Explore Postman Collection Runner.
* Integrate API tests with Newman and CI/CD pipelines.

## 👨‍💻 Author

**Dennish Yadav**

MCA Graduate | Aspiring Software Tester | API Testing Enthusiast

📌 Skills: Manual Testing | API Testing | Postman | REST API | SQL | JavaScript Basics

---

⭐ **Thank you for visiting my project!**
