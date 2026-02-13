# 📚 Postman Library API Practice

## 📌 Overview

This repository contains a **Postman practice project** created to learn and implement core API testing concepts.

The project validates a simple **Library Management API** by performing an end-to-end workflow:

* Add a Book
* Retrieve the Book Details
* Delete the Book

This demonstrates how APIs interact with each other using dynamic data and validations.

---

## 🛠 Tools & Technologies Used

* **Postman** – API Testing Tool
* **JavaScript (Postman Scripts)** – Assertions & Data Handling
* **Environment Variables** – Configuration Management
* **JSON Schema Validation** – Response Structure Validation

---

## 🔄 Workflow Covered

### 1️⃣ Add Book (POST)

* Sends request to create a new book.
* Generates dynamic values to avoid duplication.
* Captures the generated `Book ID` from response.

### 2️⃣ Search Book (GET)

* Uses captured `Book ID` to fetch book details.
* Validates:

  * Author
  * ISBN
  * Response Schema
  * Status Code

### 3️⃣ Remove Book (POST)

* Deletes the created book using the same ID.
* Ensures test data cleanup.

---

## ✅ Concepts Practiced

* API Request Chaining
* Dynamic Data Generation
* Environment & Collection Variables
* Response Assertions
* Schema Validation
* Status Code Validation
* Response Time Checks
* Test Data Cleanup Strategy

---

## 📂 Files Included

| File                                    | Description                                      |
| --------------------------------------- | ------------------------------------------------ |
| Library.postman_collection.json         | Contains API requests and test scripts           |
| QA_Environment.postman_environment.json | Contains environment configuration like Base URL |

---

## ▶️ How to Run This Project

1. Download this repository.
2. Open **Postman**.
3. Import:

   * `Library.postman_collection.json`
   * `QA_Environment.postman_environment.json`
4. Select **QA_Environment** from environment dropdown.
5. Run the collection using **Collection Runner**.

---

## 🎯 Learning Purpose

This project was built as a **hands-on learning exercise** to understand real-world API testing workflows before implementing automation using tools like RestAssured.

---

## 👤 Author

**Karan Sagale**
Senior Software Test Engineer
API Testing | Manual Testing | Automation Learner