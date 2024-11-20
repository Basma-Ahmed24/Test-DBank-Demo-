# Test-DBank-Demo  
This repository contains the test documentation and scripts for manually testing the **DBank Demo** application. The DBank Demo is a simple web application designed to simulate banking operations, such as creating an account, depositing, withdrawing, and viewing transaction history.  

---

## **Table of Contents**  
- [Introduction](#introduction)  
- [Test Objectives](#test-objectives)  
- [Pre-requisites](#pre-requisites)  
- [Test Scope](#test-scope)  
- [Test Scenarios](#test-scenarios)  
- [Test Execution](#test-execution)  
- [Reporting Issues](#reporting-issues)  
- [Future Enhancements](#future-enhancements)  

---

## **Introduction**  
The **DBank Demo** application is a prototype for simulating banking functionalities in a controlled environment. This README provides details on the manual testing procedures for validating the application's functionality, usability, and reliability.  

---

## **Test Objectives**  
The primary objectives of manual testing are to:  
- Ensure the functionality of core features (e.g., account creation, deposits, withdrawals).  
- Validate the user interface for usability and responsiveness.  
- Identify defects or bugs in the application.  
- Confirm compatibility across different browsers and devices.  

---

## **Pre-requisites**  
Before starting the tests, ensure the following:  
1. **Environment Setup**:  
   - Access to the DBank Demo application URL.  
   - Test environment configured with supported browsers (e.g., Chrome, Firefox).  

2. **Test Data**:  
   - Test account credentials.  
   - Example scenarios for deposits and withdrawals.  

3. **Tools**:  
   - Issue tracking tool for reporting defects (e.g., Jira, GitHub Issues).  
   - Browser Developer Tools for debugging.  

---

## **Test Scope**  
The manual testing process will focus on:  
- **Core Banking Features**:  
  - Account creation.  
  - Logging in and out.  
  - Deposit and withdrawal functionalities.  
  - Viewing transaction history.  

- **UI/UX**:  
  - Layout and design validation.  
  - Accessibility checks.  

- **Performance**:  
  - Response times for key actions.  

- **Compatibility**:  
  - Browser and device testing.  

---

## **Test Scenarios**  
Below is a list of key test scenarios:  

### 1. **Account Creation**  
   - Verify users can create accounts with valid inputs.  
   - Validate error messages for invalid inputs (e.g., missing fields, incorrect formats).  

### 2. **Login and Logout**  
   - Test successful login with valid credentials.  
   - Verify error handling for invalid credentials.  
   - Confirm users can log out successfully.  

### 3. **Deposit Funds**  
   - Ensure users can deposit valid amounts.  
   - Verify error messages for invalid deposit inputs (e.g., negative amounts).  

### 4. **Withdraw Funds**  
   - Confirm withdrawals process correctly with sufficient balance.  
   - Verify error messages for insufficient balance.  

### 5. **Transaction History**  
   - Ensure the transaction history displays correct details (date, type, amount).  
   - Verify pagination or scrolling for large histories.  

### 6. **UI/UX Validation**  
   - Check alignment, font consistency, and responsiveness of the UI.  
   - Validate accessibility features (e.g., alt text for images, keyboard navigation).  

---

## **Test Execution**  
1. Follow the **Test Scenarios** section for step-by-step validation.  
2. Record observations and defects in the test log.  
3. Retest resolved issues to confirm fixes.  

---

## **Reporting Issues**  
Report any identified bugs or issues with the following details:  
- **Issue Title**: Brief summary of the defect.  
- **Steps to Reproduce**: Detailed steps to replicate the issue.  
- **Expected Result**: What should happen.  
- **Actual Result**: What actually happened.  
- **Environment**: Browser, OS, version details.  
- **Attachments**: Screenshots, videos, or logs (if applicable).  

---

## **Future Enhancements**  
- Automate repetitive test scenarios.  
- Add detailed test cases for edge cases and boundary value analysis.  
- Expand compatibility testing for additional browsers and devices.  

---  

Happy Testing!  
