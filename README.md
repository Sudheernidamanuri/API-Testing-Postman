# API Testing with Postman

## 📋 Overview

This repository contains a comprehensive collection of Postman API test suites for various applications and services. The collections demonstrate professional API testing practices including authentication, CRUD operations, and data validation across different domains.

## 🗂️ Collections Included

### 1. Contact List API
**File:** `ContactListAPI.postman_collection.json`

A complete test suite for a Contact Management system featuring:
- 🔐 JWT Token-based authentication (Login/Logout)
- 📝 Create new contacts
- 📖 Retrieve all contacts
- ✏️ Update contact information
- 🗑️ Delete contacts

### 2. Employee Management API
**File:** `EmployeeManagement API.postman_collection.json`

Comprehensive employee data management with advanced filtering:
- 👥 Retrieve all employees
- ➕ Add new employee records
- 🚹 Filter employees by gender (Male/Female)
- 🏢 Filter employees by department (HR)
- ❌ Delete employee records

### 3. H2 Database API
**File:** `H2 db API.postman_collection.json`

Direct database interaction tests for H2 in-memory database operations.

### 4. Movie Ticket Booking System
**File:** `MovieTicketBookingSystem.postman_collection.json`

End-to-end testing for a movie ticket booking platform covering the complete booking workflow.

### 5. Selenium WebDriver APIs
**File:** `Selenium WD APIs.postman_collection.json`

API tests for Selenium WebDriver remote server interactions and browser automation endpoints.

## 🚀 Getting Started

### Prerequisites
- [Postman](https://www.postman.com/downloads/) (Desktop app or Web version)
- Basic understanding of REST APIs and HTTP methods

### Installation & Usage

1. **Clone this repository:**
   ```bash
   git clone https://github.com/Sudheernidamanuri/API-Testing-Postman.git
   ```

2. **Import collections into Postman:**
   - Open Postman
   - Click on **Import** button (top left)
   - Select **File** tab
   - Navigate to the cloned repository folder
   - Select the desired `.postman_collection.json` file(s)
   - Click **Import**

3. **Configure Environment Variables (if required):**
   - Some collections may require base URLs or authentication tokens
   - Set these as environment variables in Postman
   - Common variables:
     - `base_url` - API endpoint base URL
     - `token` - Authentication token (where applicable)

4. **Run Tests:**
   - Select the imported collection
   - Click **Run** to open the Collection Runner
   - Configure iterations and data files if needed
   - Click **Start Run**

## 📊 Test Features

✅ **Authentication Testing** - JWT tokens, session management  
✅ **CRUD Operations** - Create, Read, Update, Delete  
✅ **Data Validation** - Response verification and schema validation  
✅ **Status Code Verification** - Proper HTTP status code assertions  
✅ **Filtering & Querying** - Advanced data retrieval patterns  
✅ **Error Handling** - Negative test scenarios  

## 🛠️ Best Practices Implemented

- **Organized Structure** - Logical grouping of related API requests
- **Environment Variables** - Flexible configuration management
- **Test Scripts** - Automated assertions in response validation
- **Pre-request Scripts** - Dynamic data generation and token management
- **Descriptive Naming** - Clear request and test case descriptions

## 📝 Collection Structure

Each collection follows a standard structure:
```
Collection Name
├── Authentication (if applicable)
│   ├── Login/Token generation
│   └── Logout
├── GET Requests
│   ├── Get all resources
│   └── Get with filters
├── POST Requests
│   └── Create new resource
├── PUT/PATCH Requests
│   └── Update existing resource
└── DELETE Requests
    └── Remove resource
```

## 🤝 Contributing

Contributions are welcome! If you'd like to add more test collections or improve existing ones:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/NewAPITests`)
3. Commit your changes (`git commit -m 'Add new API test collection'`)
4. Push to the branch (`git push origin feature/NewAPITests`)
5. Open a Pull Request

## 📧 Contact

**Sudheer Nidamanuri**  
GitHub: [@Sudheernidamanuri](https://github.com/Sudheernidamanuri)

## ⭐ Show Your Support

If you find these API test collections helpful, please consider giving this repository a star!

---

*Last Updated: October 2025*
