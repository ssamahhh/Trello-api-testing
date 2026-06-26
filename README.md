# Trello API Testing with Postman

## Overview

This project is a **Postman API Testing Collection** developed for the **Trello REST API**.

The collection automates the complete lifecycle of Trello resources, including creating, retrieving, updating, and deleting Boards, Lists, Cards, and Checklists.

The project follows API testing best practices by organizing requests into reusable workflows, using variables for dynamic values, and validating responses through automated Postman test scripts.

---

## Project Objectives

* Practice REST API testing using Postman.
* Validate CRUD (Create, Read, Update, Delete) operations.
* Automate API response validation.
* Learn variable management and request chaining.
* Build a professional API testing portfolio project.

---

## Technologies Used

* Postman
* Trello REST API
* JavaScript (Postman Tests)
* JSON

---

## API Under Test

**Base URL**

```
https://api.trello.com/1
```

---

## Features

* Create Board

* Retrieve Board Information

* Update Board

* Delete Board

* Create List

* Retrieve List

* Update List

* Archive / Unarchive List

* Create Card

* Retrieve Card

* Update Card

* Delete Card

* Create Checklist

* Retrieve Checklist

* Update Checklist

* Delete Checklist

---

## Variables Used

The collection uses variables to avoid hardcoding values.

| Variable    | Description          |
| ----------- | -------------------- |
| key         | Trello API Key       |
| token       | Trello API Token     |
| boardId     | Created Board ID     |
| listId      | Created List ID      |
| cardId      | Created Card ID      |
| checklistId | Created Checklist ID |

Dynamic IDs are captured from API responses and reused in subsequent requests.

---

## Test Coverage

The collection validates:

* HTTP Status Codes
* Response Body
* Required Fields
* Returned IDs
* Response Time
* Data Integrity
* CRUD Operations

---

## Request Flow

```
Create Board
        │
        ▼
Create List
        │
        ▼
Create Card
        │
        ▼
Create Checklist
        │
        ▼
Get Resources
        │
        ▼
Update Resources
        │
        ▼
Delete Resources
```

---

## Running the Collection

1. Import the Postman Collection.
2. Set your Trello API **Key** and **Token**.
3. Run the requests sequentially or use the Collection Runner.
4. Verify that all tests pass successfully.

---

## Author

**Samah Sameh**
