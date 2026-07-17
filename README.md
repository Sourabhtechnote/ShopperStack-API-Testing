# 🛒 ShopperStack API Testing using Postman & Newman

## 📌 Project Overview

This project demonstrates end-to-end REST API testing of the **ShopperStack Swagger APIs** using **Postman**, **Newman CLI**, and the **htmlextra reporter**.

The project includes:
- API request execution through Postman Collection Runner
- Automated test validation using JavaScript
- Newman command-line execution
- HTML report generation using htmlextra
- Exported Postman Collection & Environment files
- Complete execution workflow video

---

# 🛠️ Tech Stack

- Postman
- Newman
- Newman HTML Extra Reporter
- Node.js
- npm
- JavaScript (Postman Test Scripts)
- Git
- GitHub

---

# 📂 Project Structure

```
ShopperStack-API-Testing
│
├── README.md
│
├── Postman Collection
│   └── Postman_Collection.json
│
├── Postman Environment
│   └── Postman_Environment.json
│
├── Reports
│   └── ShopperStack-Newman-APITestingReport.html
│
├── Screenshots
│
└── Video
```

---

# ✅ Test Coverage

The collection contains:

- 7 API folders
- 27 API Requests

The APIs include multiple CRUD operations and user workflow validations.

---

# 🧪 Automated Test Scripts

Several Postman requests include JavaScript test scripts to validate:

- HTTP Status Codes
- Response Time
- Response Body
- JSON Values
- Authentication Token
- Dynamic Variables
- Environment Variables

---

# ▶️ Project Demonstration Video

The project includes a complete screen recording demonstrating the entire workflow.

The video covers:

### 1. Swagger API Overview

- ShopperStack Swagger APIs

### 2. Postman Collection Runner

- Running complete collection
- Executing all 7 folders
- Running all 27 requests

### 3. Postman Test Scripts

Examples of:

- pm.test()
- pm.expect()
- Response validations
- Assertions
- Environment variable usage

### 4. Exporting Project Files

- Postman Collection
- Postman Environment

### 5. Newman Setup

Verification of installed tools:

- Node.js
- npm
- Newman
- Newman HTML Extra Reporter

### 6. Newman Execution

Running collection from Command Prompt using Newman.

### 7. Troubleshooting

The video also demonstrates:

- Errors encountered during Newman execution
- Steps taken to resolve the issues
- Successful rerun after fixing the configuration

### 8. HTML Report Generation

Executing Newman with the **htmlextra** reporter to generate a professional HTML execution report.

---

# 📊 Newman HTML Report

The project includes an HTML report generated using:

```
newman-reporter-htmlextra
```

The report contains:

- Execution Summary
- Passed Tests
- Failed Tests
- Assertions
- Response Details
- Request Information
- Response Time
- Visual Dashboard

---

# 🚀 Running the Project

## Install Newman

```bash
npm install -g newman
```

## Install HTML Extra Reporter

```bash
npm install -g newman-reporter-htmlextra
```

## Verify Installation

```bash
node -v
npm -v
newman -v
```

## Execute Collection

```bash
newman run "Postman Collection/Postman_Collection.json" ^
-e "Postman Environment/Postman_Environment.json"
```

## Generate HTML Report

```bash
newman run "Postman Collection/Postman_Collection.json" ^
-e "Postman Environment/Postman_Environment.json" ^
-r htmlextra ^
--reporter-htmlextra-export "Reports/ShopperStack-Newman-APITestingReport.html"
```

---

# 📷 Screenshots

Repository includes screenshots demonstrating:

- Collection Runner
- Newman CLI Execution
- HTML Report
- API Responses

---

# 🎯 Learning Outcomes

Through this project I learned:

- REST API Testing
- Postman Collection Runner
- JavaScript Test Assertions
- Newman CLI
- HTML Report Generation
- Environment Variables
- Collection Variables
- Command Line Execution
- Git & GitHub Project Management
- Debugging and Troubleshooting API Automation

---

# 📌 Future Improvements

- Add CI/CD integration (GitHub Actions or Jenkins)
- Add data-driven testing
- Add CSV/JSON data files
- Improve HTML report customization
- Add API documentation
- Record voice-over explanation for the demonstration video

---

# 👨‍💻 Author

**Sourabh Kurhade**

QA Automation | API Testing | Postman | Newman | Git | GitHub

---
Thank you for your time, We welcome your suggestions and contributions. :) 
