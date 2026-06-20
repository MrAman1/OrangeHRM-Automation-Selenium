# OrangeHRM-Automation-Selenium
 Designed and developed a scalable test automation framework for OrangeHRM using Selenium WebDriver, Java, and TestNG. Implemented Page Object Model (POM), Data-Driven Testing, Extent Reports, reusable utilities, and automated end-to-end HR workflows including Login, Employee Management, Leave Management, and User Administration. 
# OrangeHRM Automation Framework

## Project Overview

This project is a Selenium-based Automation Testing Framework developed for the OrangeHRM application. The framework automates various HR management functionalities and follows industry-standard automation practices using Java, Selenium WebDriver, TestNG, and Page Object Model (POM).

## Tech Stack

- Java
- Selenium WebDriver
- TestNG
- Maven
- Page Object Model (POM)
- Extent Reports
- Apache POI (Excel)
- Git & GitHub

---

## Features

### Automated Modules

- Login Module
- Dashboard Validation
- Employee Management (PIM)
- Leave Management
- Recruitment Module
- Admin/User Management
- Logout Functionality

### Framework Features

- Page Object Model Design Pattern
- Data-Driven Testing
- Cross Browser Support
- Screenshot Capture on Failure
- Configurable Test Data
- Reusable Utility Classes
- Extent Reporting
- Maven Build Management

---

## Framework Structure
OrangeHRM-Automation
│
├── src/main/java
│ ├── pages
│ ├── utilities
│ └── base
│
├── src/test/java
│ ├── tests
│ └── dataProviders
│
├── testData
│ └── Excel Files
│
├── reports
│
├── screenshots
│
├── pom.xml
│
└── testng.xml

---

## Design Pattern

This framework follows the Page Object Model (POM) design pattern:

- Separation of Page Objects and Test Scripts
- Better Code Reusability
- Easy Maintenance
- Improved Readability

---

## Test Scenarios Covered

### Login Module

- Valid Login
- Invalid Login
- Empty Credentials
- Password Validation

### Employee Management

- Add Employee
- Search Employee
- Update Employee Details
- Delete Employee

### Leave Management

- Apply Leave
- Approve Leave
- Reject Leave

### Admin Module

- Create User
- Search User
- Update User
- Delete User

---

## Reporting

The framework generates:

- TestNG Reports
- Extent Reports
- Failure Screenshots

---

## How to Run

### Clone Repository

```bash
git clone <repository-url>
