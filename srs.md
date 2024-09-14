# Software Requirements Specification

## Employee Management System with Payment Tracking

  

### 1. Introduction

#### 1.1 Purpose

This document outlines the software requirements for an Employee Management System with integrated payment tracking features for CareerShapers.in.

  

#### 1.2 Scope

The system will manage employees, track payments, provide analytics, and offer role-based access control for super admins and regular employees.

  

#### 1.3 Definitions, Acronyms, and Abbreviations

- EMS: Employee Management System

- CRUD: Create, Read, Update, Delete

- UG: Undergraduate

- PG: Postgraduate

  

### 2. Overall Description

#### 2.1 Product Perspective

The EMS will be a web-based application accessible to super admins and employees of CareerShapers.in.

  

#### 2.2 User Classes and Characteristics

1. Super Admin: Has full access to all system features

2. Employee: Has limited access to system features

  

#### 2.3 Operating Environment

- Web-based application

- Compatible with modern web browsers

- Responsive design for desktop and mobile devices

  

#### 2.4 Design and Implementation Constraints

- Email domain restricted to careershapers.in

- Secure storage of passwords and sensitive information

- Compliance with data protection regulations

  

### 3. Specific Requirements

#### 3.1 User Authentication and Management

1. Super Admin Capabilities:

- Create and delete employee accounts

- Super Admin can view and share forgotten employee passwords.
- View all employee information

- Perform CRUD operations on employee data


  

2. Employee Capabilities:

- Login using email and password

- Request password reset from Super Admin

- Create user accounts (clients/leads)


  

3. Password Management:

- Secure storage of passwords (hashed and salted)

- Password reset functionality for employees via Super Admin

- Super Admin can view and communicate passwords securely

  

#### 3.2 Payment Management

1. Super Admin Capabilities:

-    Record payments

- View all payments (online and offline)

- Filter payments based on various criteria

- Export payment data to Excel

- View payment analytics and graphs

  

2. Employee Capabilities:

- Record payments

- View payments made by them

- Cannot delete payments

- Receive verification code for each payment

  

3. Payment Analytics:

- Graphs for UG and PG sales

- Payment status analytics (completed, pending, cancelled)

- Recent payment view

  

#### 3.3 Mentor Allocation

- Super Admin can view mentor allocation for each lead

  

#### 3.4 Email System

- Predefined email templates

- Automatic template generation for common scenarios

- Super Admin can send employee credentials through emails

  

#### 3.5 Activity Tracking

- Admin can view all employee activities

- Logging of user actions for auditing purposes

  

#### 3.6 Graphical Reporting

- Sales graphs for UG and PG

- Payment status graphs

- Custom graphs for various metrics

  

#### 3.7 Help and Support

- Help section for both employees and admin

- Support ticket system for reporting issues

- API documentation for technical support

  

#### 3.8 Notification System

- In-app notifications for important events

- Email notifications for critical updates

- Customizable notification preferences

  

#### 3.9 Data Export

- Export functionality for payment data (Excel format)

- Ability to export other relevant data as needed

  

### 4. Additional Features

#### 4.1 Dashboard

- Personalized dashboards for Super Admin and Employees

- Quick access to frequently used features

- Summary of key metrics and recent activities

  

#### 4.2 Reporting

- Customizable report generation

- Scheduled automated reports

- Export reports in various formats (PDF, CSV, Excel)

  

#### 4.3 API Integration

- RESTful API for potential integration with other systems

- Secure API authentication and rate limiting

  

#### 4.4 Audit Trail

- Comprehensive logging of all system actions

- Ability to review and export audit logs

  

#### 4.5 Multi-factor Authentication

- Optional two-factor authentication for enhanced security

  

#### 4.6 Performance Analytics

- Employee performance metrics and comparisons

- Goal setting and tracking features

  

### 5. Non-functional Requirements

#### 5.1 Performance

- Page load times under 2 seconds

- Support for concurrent users (specify expected number)

  

#### 5.2 Security

- HTTPS encryption for all communications

- Regular security audits and penetration testing

- Compliance with relevant data protection regulations

  

#### 5.3 Reliability

- 99.9% uptime guarantee

- Regular data backups and disaster recovery plan

  

#### 5.4 Usability

- Intuitive user interface with minimal training required

- Accessibility compliance (WCAG 2.1 AA)

  

#### 5.5 Scalability

- Ability to handle growing number of users and data volume

- Modular design for easy feature additions

  

### 6. Future Enhancements

- Mobile application for on-the-go access

- Integration with third-party HR and payroll systems

- Advanced analytics with machine learning capabilities

- Integrate multiple third-party sites into a single, unified web platform.
- Eliminate use of LeadSquare.
