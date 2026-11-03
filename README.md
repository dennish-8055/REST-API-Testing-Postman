# REST API Testing Using Postman

## Project Overview

This project demonstrates manual and automated REST API testing using **Postman** and the public **Reqres API**.

The objective was to test different HTTP methods, validate API responses, verify status codes, and write automated test scripts using Postman's JavaScript-based testing features.

The project covers CRUD-related API operations: GET, POST, PUT, PATCH, and DELETE.

## Tools & Technologies

* **Postman** – API testing and automation
* **Reqres API** – Public REST API for testing
* **JavaScript** – Writing automated test scripts
* **JSON** – Request and response data
* **HTTP Methods** – GET, POST, PUT, PATCH, DELETE

## API Base URL

`https://reqres.in/api`

## API Requests Tested

| Test Case             | HTTP Method | Endpoint        | Expected Status |
| --------------------- | ----------- | --------------- | --------------- |
| Get Single User       | GET         | `/users/2`      | 200 OK          |
| Get All Users         | GET         | `/users?page=2` | 200 OK          |
| Create User           | POST        | `/users`        | 201 Created     |
| Update User           | PUT         | `/users/2`      | 200 OK          |
| Partially Update User | PATCH       | `/users/2`      | 200 OK          |
| Delete User           | DELETE      | `/users/2`      | 204 No Content  |

## Test Execution Summary

The following automated checks were executed in Postman.

| API Request          | Total Checks | Passed | Failed |
| -------------------- | -----------: | -----: | -----: |
| GET – Single User    |            5 |      5 |      0 |
| POST – Create User   |            6 |      6 |      0 |
| PUT – Update User    |            4 |      4 |      0 |
| PATCH – Update User  |            4 |      4 |      0 |
| DELETE – Delete User |            2 |      2 |      0 |
| **Total**            |       **21** | **21** |  **0** |

**GET – All Users:** The request returned `200 OK`. The response showed page 2 of 2, six users on that page, and 12 users in total. Its automated test count is not included in the table above.

## Automated Test Validations

Automated Postman scripts were used to validate:

* HTTP response status codes
* API response time (below 3000 milliseconds)
* User ID
* User name and email
* Created user details
* Updated user information
* Presence of created and updated timestamps
* Successful delete response

## Key Results

* Successfully retrieved user details using GET.
* Retrieved paginated user data using GET.
* Created a user using POST and received `201 Created`.
* Updated user information using PUT.
* Partially updated user information using PATCH.
* Deleted a user using DELETE and received `204 No Content`.
* Executed 21 automated checks, all of which passed.

## Project Structure

```text
API-Testing-Postman/
│
├── Screenshots/
│   ├── GET-Single-User.png
│   ├── GET-All-Users.png
│   ├── POST-Create-User.png
│   ├── PUT-Update-User.png
│   ├── PATCH-Update-User.png
│   └── DELETE-Delete-User.png
│
└── README.md
```

*Update the screenshot filenames above to match the actual filenames in your Screenshots folder.*

## What I Learned

Through this project, I gained practical experience in:

* Understanding REST API concepts.
* Working with different HTTP methods.
* Sending API requests through Postman.
* Understanding HTTP status codes.
* Reading and validating JSON responses.
* Writing automated test scripts in Postman.
* Checking API response times.
* Organizing API requests into a Postman collection.
* Identifying successful and unsuccessful API responses.

## Conclusion

This project helped me develop practical knowledge of REST API testing and Postman automation. It provided hands-on experience in validating API responses, checking status codes, and writing reusable automated test scripts.

**Project Type:** API Testing
**Tool:** Postman
**API:** Reqres
**Testing:** Manual and Automated API Testing

---
