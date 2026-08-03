# Software Requirements Specification (SRS)

## Project Information

| Item | Details |
|------|---------|
| Project Name | Resort Booking Management System |
| Client | Oluhle Resort |
| Document | Software Requirements Specification |
| Version | 1.0 |
| Author | Bonolo Lekalakala |
| Date |  03 August 2026 |
| Status | Draft |

---

# Table of Contents

1. Introduction
2. Purpose
3. Scope
4. System Overview
5. User Roles
6. Functional Requirements
7. Non-Functional Requirements
8. External Interface Requirements
9. Database Requirements
10. Business Rules
11. System Constraints
12. Assumptions
13. Acceptance Criteria
14. Future Enhancements

---

# 1. Introduction

This document specifies the software requirements for the Oluhle Resort Booking Management System.

The application will replace the current manual booking process with a secure web-based system that allows staff to manage bookings while enabling customers to make booking requests and enquiries online.

---

# 2. Purpose

The purpose of this document is to define the software requirements needed to design, develop, test, and deploy the Resort Booking Management System.

---

# 3. Scope

The system will provide:

- Customer registration
- Secure login
- Room management
- Online booking requests
- Booking approval
- Payment recording
- Customer enquiries
- Reporting
- WhatsApp communication
- Email communication

---

# 4. System Overview

The application will consist of the following modules:

- Authentication
- Customer Management
- Room Management
- Booking Management
- Payment Management
- Enquiry Management
- Reporting
- Administration

---

# 5. User Roles

## Administrator

Can:

- Manage users
- Manage rooms
- View reports
- Manage bookings
- Manage customers

---

## Reception Staff

Can:

- Create bookings
- Approve bookings
- Update bookings
- Check guests in
- Check guests out
- Record payments

---

## Customer

Can:

- Register
- Login
- Search rooms
- Submit booking requests
- Submit enquiries
- Choose WhatsApp or Email
- View booking history

---

# 6. Functional Requirements

## Authentication

FR-001

The system shall allow users to register.

Priority: High

---

FR-002

The system shall authenticate users before allowing access.

Priority: High

---

FR-003

The system shall encrypt user passwords.

Priority: High

---

## Customer Module

FR-004

The system shall store customer information.

---

FR-005

The system shall update customer profiles.

---

FR-006

The system shall record customer communication preferences.

---

## Room Module

FR-007

The system shall manage room information.

---

FR-008

The system shall display room availability.

---

FR-009

The system shall prevent double bookings.

---

## Booking Module

FR-010

The system shall allow booking requests.

---

FR-011

The system shall approve bookings.

---

FR-012

The system shall cancel bookings.

---

FR-013

The system shall update booking details.

---

## Payment Module

FR-014

The system shall record payments.

---

FR-015

The system shall display payment history.

---

## Enquiry Module

FR-016

The system shall record customer enquiries.

---

FR-017

The system shall track enquiry status.

---

## Communication Module

FR-018

The system shall send booking confirmations by Email.

---

FR-019

The system shall support WhatsApp communication.

---

FR-020

The system shall send booking updates using the customer's preferred communication method.

---

## Reporting Module

FR-021

The system shall generate booking reports.

---

FR-022

The system shall generate occupancy reports.

---

FR-023

The system shall generate payment reports.

---

FR-024

The system shall generate customer reports.

---

# 7. Non-Functional Requirements

## Performance

- Page load time must not exceed 3 seconds.
- Reports should generate within 10 seconds.

---

## Reliability

- Automatic database backups.
- Data validation.
- Error logging.

---

## Security

- Password encryption.
- Role-based access control.
- Secure authentication.
- Session timeout.

---

## Availability

The system shall be available during business hours.

---

## Maintainability

The application shall use modular code.

---

## Usability

The interface shall:

- Be easy to navigate.
- Be responsive.
- Support desktop and mobile browsers.

---

# 8. External Interface Requirements

## User Interface

The application shall include:

- Login Page
- Registration Page
- Customer Dashboard
- Staff Dashboard
- Booking Page
- Room Management
- Reports Dashboard

---

## Hardware

The system requires:

- Computer
- Internet connection
- Modern web browser

---

## Software

- Python
- Flask
- MySQL
- HTML
- CSS
- JavaScript

---

# 9. Database Requirements

The database shall include:

- Users
- Customers
- Rooms
- Bookings
- Payments
- Enquiries
- Reports

Primary keys shall uniquely identify every record.

Foreign keys shall maintain relationships.

---

# 10. Business Rules

- Every booking belongs to one customer.
- Rooms cannot be double booked.
- Payments must belong to bookings.
- Only staff may approve bookings.
- Every booking has a status.
- Communication preference is mandatory.

---

# 11. System Constraints

- Internet required.
- Limited development budget.
- Small development team.
- WhatsApp Business account required.

---

# 12. Assumptions

- Users have internet access.
- Customers possess Email or WhatsApp.
- Staff receive training before implementation.

---

# 13. Acceptance Criteria

The system shall be accepted if:

- Users successfully register.
- Bookings are managed digitally.
- Double bookings are prevented.
- Reports generate successfully.
- Payments are recorded.
- Customer communication preferences are honoured.
- Staff successfully manage bookings.

---

# 14. Future Enhancements

Future versions may include:

- Online payments
- Mobile application
- SMS notifications
- Loyalty programme
- Third-party booking integrations
- AI chatbot
- QR code check-in
- Customer reviews

---

# Conclusion

The Software Requirements Specification defines the detailed software requirements for developing the Oluhle Resort Booking Management System.

The document provides the foundation for system design, database development, coding, testing, and deployment.
