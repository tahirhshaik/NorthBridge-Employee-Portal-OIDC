# Project Overview

## NorthBridge Employee Portal 2.0

**Version:** 1.0  
**Project Type:** Microsoft Entra ID (Azure AD) Single Sign-On (SSO) Implementation  
**Authentication Protocol:** OpenID Connect (OIDC)  
**Framework:** ASP.NET Core MVC (.NET 8)

---

# Introduction

The **NorthBridge Employee Portal 2.0** project is a hands-on Identity and Access Management (IAM) implementation that demonstrates how an enterprise web application can be integrated with **Microsoft Entra ID** using **OpenID Connect (OIDC)** for authentication.

Instead of maintaining separate usernames and passwords inside the application, employees authenticate using their Microsoft Entra accounts. Microsoft Entra ID acts as the trusted Identity Provider (IdP), allowing authentication to be centralized while improving security, user experience, and administrative control.

This repository documents the complete implementation process from initial application creation through Microsoft Entra configuration, authentication integration, troubleshooting, and enterprise IAM concepts.

---

# Project Goals

The primary objectives of this project are:

- Learn how Microsoft Entra ID functions as an Identity Provider.
- Implement Single Sign-On (SSO) using OpenID Connect.
- Configure an enterprise application for authentication.
- Understand authentication and authorization workflows.
- Learn how Microsoft Entra communicates with applications using ID Tokens.
- Develop practical troubleshooting skills for Microsoft Entra authentication.
- Document the implementation using enterprise-level standards.

---

# Why This Project?

Modern organizations rarely allow employees to maintain separate credentials for every internal application.

Instead, organizations use a centralized Identity Provider such as Microsoft Entra ID.

Benefits include:

- Single Sign-On (SSO)
- Centralized Identity Management
- Multi-Factor Authentication (MFA)
- Conditional Access
- Improved Security
- Simplified User Experience
- Reduced Password Management

This project demonstrates how those concepts are implemented in practice.

---

# Business Scenario

NorthBridge Technologies has developed an internal Employee Portal that allows employees to access company resources.

The organization wants employees to authenticate using their Microsoft Entra accounts instead of creating separate application accounts.

The IAM team has been assigned to:

- Register the application in Microsoft Entra ID.
- Configure authentication.
- Enable Single Sign-On.
- Test authentication.
- Troubleshoot authentication issues.
- Document the complete implementation.

This repository represents that implementation.

---

# Technologies Used

| Technology | Purpose |
|------------|---------|
| ASP.NET Core MVC (.NET 8) | Web Application |
| Microsoft Entra ID | Identity Provider (IdP) |
| OpenID Connect (OIDC) | Authentication Protocol |
| Microsoft.Identity.Web | Authentication Library |
| Visual Studio Code | Development Environment |
| Git & GitHub | Version Control and Documentation |

---

# IAM Concepts Covered

Throughout this project, the following IAM concepts will be implemented and explained:

- Identity Provider (IdP)
- OpenID Connect (OIDC)
- Single Sign-On (SSO)
- Authentication
- Authorization
- App Registration
- Enterprise Application
- Redirect URI
- ID Tokens
- Claims
- Microsoft Graph
- Delegated Permissions
- Admin Consent
- Conditional Access
- App Roles
- Group-Based Authorization
- Sign-in Logs
- Authentication Troubleshooting

---

# High-Level Architecture

```text
                Employee
                    │
                    ▼
      NorthBridge Employee Portal
                    │
          Authentication Required
                    │
                    ▼
          Microsoft.Identity.Web
                    │
                    ▼
          Microsoft Entra ID
                    │
     Username + Password + MFA
                    │
                    ▼
               ID Token
                    │
                    ▼
      NorthBridge Employee Portal
                    │
                    ▼
          Authenticated Session
```

---

# Current Project Status

## Completed

- Created ASP.NET Core MVC application
- Created Microsoft Entra App Registration
- Configured Enterprise Application
- Configured Microsoft.Identity.Web
- Configured Redirect URI
- Protected the application using authentication
- Successfully redirected users to Microsoft Entra
- Completed the consent flow
- Troubleshot initial authentication issues

---

# Future Enhancements

The project will continue to expand with additional enterprise IAM topics including:

- ID Tokens
- Claims
- Microsoft Graph
- Access Tokens
- Refresh Tokens
- App Roles
- Group Claims
- Conditional Access
- Sign-in Logs
- Enterprise Troubleshooting
- Role-Based Authorization

---

# Learning Outcomes

By completing this project, readers will understand:

- How enterprise applications integrate with Microsoft Entra ID.
- How OpenID Connect authentication works.
- How Single Sign-On is implemented.
- How authentication requests are processed.
- How Microsoft Entra issues ID Tokens.
- How enterprise IAM engineers troubleshoot authentication issues.
- How to implement Microsoft Entra authentication in an ASP.NET Core application.

---

# Repository Roadmap

| Chapter | Topic |
|----------|-------|
| 01 | Project Overview |
| 02 | Business Scenario |
| 03 | Solution Architecture |
| 04 | Lab Prerequisites |
| 05 | Creating the ASP.NET Core MVC Application |
| 06 | Microsoft Entra App Registration |
| 07 | Enterprise Application |
| 08 | Configuring OpenID Connect |
| 09 | Protecting the Application |
| 10 | Authentication Flow |
| 11 | Troubleshooting |
| 12 | ID Tokens |
| 13 | Claims |
| 14 | Microsoft Graph |
| 15 | App Roles |
| 16 | Conditional Access |
| 17 | Sign-in Logs |
| 18 | Lessons Learned |

---

> **Note:** This project is a personal learning and portfolio project created using a fictional company, **NorthBridge Technologies**, to demonstrate enterprise Identity and Access Management concepts. No real organizational or customer data is used.A
