# Security Policy

## Supported Versions

This project is currently under development. Security fixes will be applied to the current development version.

| Version | Supported          |
| ------- | ------------------ |
| 1.x.x   | :white_check_mark: |
| < 1.0   | :x:                |

## Reporting a Vulnerability

If you discover a security vulnerability in this Inventory Management System, please report it privately to the project maintainers.

### When Reporting

Please include:

* A description of the vulnerability
* Steps to reproduce the issue
* The affected feature or component
* Any relevant screenshots or error messages
* A possible solution, if known

### Response

The project maintainers will review the reported vulnerability and take appropriate action.

Please do not publicly disclose security vulnerabilities before they have been reviewed and addressed.

## Security Measures

This project is designed to use the following security practices:

* Password hashing instead of storing plain-text passwords
* Prepared statements for database queries
* Input validation
* Session-based authentication
* Role-based access control
* Protection against SQL injection
* Secure database configuration
* Proper error handling without exposing sensitive information
