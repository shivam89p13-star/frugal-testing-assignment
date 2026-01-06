# 🚀 Intelligent Registration System

A modern, responsive registration form with client-side validations and complete Selenium automation testing.

![Registration Form](success-state.png)

## 📋 Features

###  Form Features
- **Complete Registration Form**: 12+ fields including First Name, Last Name, Email, Phone, Age, Gender, Address, Country/State/City, Password, Confirm Password, and Terms & Conditions
- **Real-time Client-side Validation**: Instant feedback as you type with green (valid) and red (invalid) indicators
- **Disposable Email Blocking**: Prevents registration with temporary email domains (@tempmail.com, mailinator.com)
- **Phone Number Validation**: Automatically validates country codes and format based on selected country
- **Password Strength Meter**: Visual indicator showing password strength as Weak, Medium, or Strong
- **Dynamic Dropdown Cascading**: Country selection automatically updates State options; State selection updates City options
- **Show/Hide Password Toggle**: Eye icons to toggle password visibility for better user experience
- **Success Modal with Animation**: Professional popup modal with checkmark animation upon successful submission
- **Automatic Form Reset**: Form clears all fields and validation states after successful submission
- **Responsive Design**: Fully responsive layout that works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Dark theme with gradient accents, smooth animations, and intuitive form flow
- **Accessibility Features**: Proper ARIA labels, keyboard navigation, and screen reader support

###  Automation Testing Features
- **Three Comprehensive Test Scenarios**: 
  - Flow A: Negative testing with missing required fields
  - Flow B: Positive testing with valid form submission  
  - Flow C: Form logic testing (dropdown cascading, password validation)
- **Selenium WebDriver Integration**: Automated browser testing with Chrome WebDriver
- **Automatic Screenshot Capture**: Takes screenshots at key test steps (error states, success states)
- **Detailed Test Logging**: Generates timestamped logs of all test execution steps
- **Form Reset Verification**: Automatically verifies form clears after successful submission
- **Dynamic Element Handling**: Robust handling of dynamic dropdowns and validation states
- **Cross-browser Ready**: Easily configurable for Chrome, Firefox, or Edge browsers
- **Error Handling**: Comprehensive exception handling with detailed error messages
- **Headless Mode Support**: Can run tests in background without opening browser window

## 📸 Screenshots
| Error State | Success State | Full Page |
|-------------|---------------|-----------|
| ![Error](error-state.png) | ![Success](success-state.png) | ![Full](full-page-error.png) |
