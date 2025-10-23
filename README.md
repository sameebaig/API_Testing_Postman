# Postman API Project – ReqRes API

This project contains automated API tests built in **Postman** using the **ReqRes public API**.

## Overview
- Demonstrates CRUD operations (Create, Read, Update, Delete).
- Includes request chaining.
- Contains assertions for validation.
- Uses environment variables
- Integrated with Postman Monitors for scheduled runs

## Tech Stack
- Postman
- JavaScript (for pre-request and test scripts)
- ReqRes Public API (https://reqres.in)

## 🧰 Collection Includes
1. Register User (POST)
2. Login User 
3. List Users  
4. Create User  (GET)
5. Get Created User  (GET)
6. Update User (PUT)  
7. Partial Update (PATCH)  
8. Delete User  
9. Delayed Response  
10. Negative Scenario

## How to Run
1. Import both files into Postman:
   - `ReqRes_API_Testing.postman_collection.json`
   - `ReqRes_Environment.postman_environment.json`
2. Select the environment in the top-right dropdown.
3. Run the full collection via **Collection Runner**.
4. If you want add a monitor for daily automated runs.
