import pypandoc

# README content in markdown
readme_content = """
# 📝 Test Scenarios for Web Application

## 📌 Project Overview
This project contains a set of **functional test scenarios** derived from the Functional Requirements Specification (FRS). The goal of these scenarios is to validate different modules and functionalities of the application, ensuring that the system works as expected across various user interactions.

---

## 📂 Contents
The project covers the following key functionalities:

1. **User Account Management**
   - Register Account
   - Login / Logout
   - Forgot Password
   - My Account (Information, Change Password, Address Book, Order History, Downloads, Reward Points, Recurring Payments, Affiliate, Newsletter)

2. **Product & Cart Features**
   - Search Functionality
   - Product Display Page
   - Add to Cart
   - Wishlist
   - Shopping Cart
   - Product Compare
   - Checkout
   - Product Returns

3. **Order & Transactions**
   - Order Information
   - Transactions
   - Returned Requests

4. **Other Functionalities**
   - Home Page
   - Contact Us Page
   - Gift Certificate Page
   - Header, Menu & Footer Options
   - Multi-currency Functionality

---

## ⚡ Priority Levels
The test scenarios are categorized into different priority levels:

- **P0 (Critical):** Must test immediately, core user flows (e.g., Register, Login, Logout).  
- **P1 (High):** Important business functionalities (e.g., Search, Product Display, Add to Cart, Shopping Cart).  
- **P2 (Medium):** Secondary flows (e.g., Forgot Password).  
- **P3 (Normal):** General features and supporting modules (e.g., My Account options, Newsletter, Orders, Contact Us).  
- **P4 (Low):** Optional features (e.g., Wishlist, Product Compare).

---

## 📊 Summary of Test Cases
| Priority | No. of Scenarios | Total Test Cases |
|----------|------------------|------------------|
| **P0**   | 3                | 61               |
| **P1**   | 4                | 182              |
| **P2**   | 1                | 25               |
| **P3**   | 20               | 713              |
| **P4**   | 2                | 45               |
| **Total**| 30               | **1026**         |

---

## 🚀 How to Use
1. Review the **Test Scenario ID** and its description.  
2. Identify the **priority** to determine the execution order.  
3. Execute the **test cases** associated with each scenario.  
4. Log defects in the bug-tracking tool (e.g., JIRA) with references to scenario IDs.  

---

## ✅ Best Practices
- Start execution with **P0 & P1** scenarios.  
- Validate **end-to-end workflows** before moving to P3/P4 scenarios.  
- Ensure **cross-browser and multi-currency** validations.  
- Perform **regression testing** after fixes.  

---

## 📌 References
- **FRS (Functional Requirement Specification)** document.  
- Test design techniques: Equivalence Partitioning, Boundary Value Analysis, Positive & Negative Testing.  
