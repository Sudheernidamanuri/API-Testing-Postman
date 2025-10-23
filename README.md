# 🚀 API Testing with Postman - Professional Collection Suite

[![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)](https://www.postman.com/)
[![API Testing](https://img.shields.io/badge/API_Testing-4CAF50?style=for-the-badge&logo=checkmarx&logoColor=white)]()
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)]()
[![GitHub Stars](https://img.shields.io/github/stars/Sudheernidamanuri/API-Testing-Postman?style=for-the-badge)](https://github.com/Sudheernidamanuri/API-Testing-Postman/stargazers)

## 📋 Overview

This repository contains a **comprehensive suite of professional Postman API test collections** designed for various applications and services. These collections demonstrate industry-standard API testing practices including **authentication workflows**, **CRUD operations**, **data validation**, **error handling**, and **advanced filtering techniques**.

Perfect for **QA Engineers**, **Developers**, and **API Testers** looking to implement robust testing strategies and learn best practices in API automation.

## 🎯 Key Features

- ✅ **Production-Ready Test Scripts** with comprehensive validation
- 🔐 **JWT & Token-Based Authentication** implementations
- 🔄 **Complete CRUD Operation** coverage
- 📊 **Advanced Data Filtering** and search capabilities
- 🛡️ **Error Handling** and edge case testing
- 📝 **Detailed Documentation** with usage examples
- 🏗️ **Modular Collection Structure** for easy maintenance
- 🎨 **Professional Test Reporting** with custom assertions

## 📚 Collections Included

### 1. 📞 Contact Management API
**File:** `ContactListAPI.postman_collection.json`

A complete test suite for Contact Management system featuring:
- 🔑 **JWT Token-based Authentication** (Login/Logout)
- 👤 **Create New Contacts** with validation
- 📋 **Retrieve Contact Lists** with pagination
- ✏️ **Update Contact Information** (PATCH/PUT operations)
- 🗑️ **Delete Contacts** with confirmation
- 🔍 **Search & Filter Contacts** by various criteria

### 2. 👥 Employee Management API
**File:** `EmployeeManagement_API.postman_collection.json`

Comprehensive employee data management with advanced filtering:
- 👥 **Retrieve All Employees** with pagination
- ➕ **Add New Employee Records** with validation
- 🚻 **Filter Employees by Gender** (Male/Female)
- 📊 **Department-wise Employee Management**
- 📈 **Employee Performance Metrics**
- 🔧 **Bulk Operations** for data management

### 3. 🗄️ H2 Database API Testing
**File:** `H2_db_API.postman_collection.json`

Specialized collection for H2 Database operations:
- 💾 **Database Connection Testing**
- 📋 **Table CRUD Operations**
- 🔍 **Complex Query Testing**
- 🔗 **Join Operations Validation**
- 📊 **Performance Testing** for database operations
- 🛠️ **Schema Management** operations

### 4. 🎬 Movie Ticket Booking System
**File:** `MovieTicketBookingSystem.postman_collection.json`

E-commerce style booking system testing:
- 🎭 **Movie Catalog Management**
- 🎫 **Ticket Booking Workflow**
- 💳 **Payment Processing** simulation
- 🪑 **Seat Selection** and availability
- 📧 **Booking Confirmation** system
- 🎟️ **Ticket Cancellation** process

### 5. 🌐 Selenium WebDriver APIs
**File:** `Selenium_WD_APIs.postman_collection.json`

Selenium Grid and WebDriver API testing:
- 🚗 **WebDriver Session Management**
- 🌐 **Browser Automation** endpoints
- 📱 **Multi-browser Testing** scenarios
- 🔧 **Grid Configuration** validation
- 📊 **Session Monitoring** and reporting

### 6. 🔄 GoREST API Workflow *(NEW)*
**File:** `GoRESTAPI_Workflow.postman_collection.json`

**Latest Addition:** Advanced workflow automation for GoREST API:
- 👤 **User Management** (Create, Read, Update, Delete)
- 📝 **Posts & Comments** complete workflow
- ✅ **Todo Management** system
- 🔐 **Authentication Token** management
- 🔗 **Workflow Chaining** with dependencies
- 📊 **Advanced Filtering** and search
- 🛡️ **Comprehensive Error Handling**
- 📈 **Performance Benchmarking**

## 🛠️ Getting Started

### Prerequisites
- [Postman](https://www.postman.com/downloads/) (Desktop or Web)
- Basic understanding of REST APIs
- Knowledge of HTTP methods and status codes

### Installation & Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Sudheernidamanuri/API-Testing-Postman.git
   cd API-Testing-Postman
   ```

2. **Import Collections to Postman**
   - Open Postman
   - Click **Import** button
   - Select **Upload Files**
   - Choose the `.postman_collection.json` files
   - Click **Import**

3. **Set Up Environment Variables** (if required)
   - Create a new Environment in Postman
   - Add necessary variables (base_url, api_key, etc.)
   - Select the environment before running tests

### Quick Start Guide

1. **Choose Your Collection** based on your testing needs
2. **Review Pre-request Scripts** for setup requirements
3. **Execute Tests** individually or run complete collection
4. **Analyze Results** using Postman's test runner
5. **Customize Tests** according to your specific requirements

## 📊 Test Execution

### Running Individual Collections
```bash
# Using Newman (Postman CLI)
newman run ContactListAPI.postman_collection.json
newman run GoRESTAPI_Workflow.postman_collection.json
```

### Batch Testing
```bash
# Run all collections
for file in *.postman_collection.json; do
    newman run "$file" --reporters cli,json
done
```

## 🎯 Best Practices Implemented

- **Parameterized Requests** for reusability
- **Environment Variables** for different testing stages
- **Pre-request Scripts** for setup automation
- **Test Scripts** with comprehensive assertions
- **Error Handling** for robust testing
- **Data-Driven Testing** capabilities
- **Continuous Integration** ready

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Postman Team** for the excellent API testing platform
- **Open Source Community** for continuous inspiration
- **Contributors** who help improve this collection

## 📞 Support & Contact

- **GitHub Issues**: [Report bugs or request features](https://github.com/Sudheernidamanuri/API-Testing-Postman/issues)
- **Discussions**: [Join community discussions](https://github.com/Sudheernidamanuri/API-Testing-Postman/discussions)

---

⭐ **Star this repository** if you find it helpful!

**Happy Testing!** 🚀
