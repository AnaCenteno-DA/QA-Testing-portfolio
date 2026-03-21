

### 🧪 Test Cases – Login Functionality
---
## 📋 Test Cases – File Upload Feature

This section contains test cases designed to validate the file upload functionality.  
The scenarios include positive, negative, and edge cases to ensure system reliability, usability, and error handling.

### 🎯 Objective
To verify that users can upload files correctly under different conditions, including file size limits, unsupported formats, and network interruptions.
---


| ID | Title | Type | Steps | Expected Result |
|----|------|------|------|----------------|
| TC-001 | Valid login | Positive | Enter valid credentials | User logs in successfully |
| TC-002 | Invalid password | Negative | Enter wrong password | Error message displayed |
| TC-003 | Invalid email format | Negative | Enter "user@com" | Validation error shown |
| TC-004 | Empty fields | Edge | Click login without input | Required field message |
| TC-005 | SQL Injection attempt | Security | Enter `' OR 1=1 --` | Access denied |
| TC-006 | XSS attempt | Security | Enter `<script>alert(1)</script>` | Input sanitized |
| TC-007 | Remember me checkbox | Functional | Select checkbox and login | Session persists |
| TC-008 | Forgot password link | Functional | Click link | Redirects to reset page |
| TC-009 | Case sensitivity check | Edge | Enter uppercase email | System handles correctly |
| TC-010 | Multiple failed attempts | Security | Enter wrong password 5 times | Account locked or captcha shown |
