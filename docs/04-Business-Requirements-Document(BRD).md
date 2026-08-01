# Business Requirements Document (BRD)

## Project Information

| Item | Details |
|------|---------|
| Project Name | Resort Booking Management System |
| Business | Oluhle Resort |
| Document | Business Requirements Document (BRD) |
| Version | 1.0 |
| Author | Bonolo Lekalakala |
| Date | 01 August 2026 |
| Status | Draft |

---

# Table of Contents

1. Executive Summary
2. Project Background
3. Business Need
4. Project Objectives
5. Project Scope
6. Stakeholders
7. Business Requirements
8. Functional Requirements
9. Non-Functional Requirements
10. Assumptions
11. Constraints
12. Risks
13. Success Criteria
14. Business Rules
15. High-Level Business Process
16. Deliverables
17. Approval

---

# 1. Executive Summary

Oluhle Resort currently manages reservations manually using WhatsApp, phone calls, email, and a paper booking register. As business has grown, this manual process has become inefficient and difficult to manage.

The Resort Booking Management System will replace manual booking processes with a centralized web-based application that enables customers to view available rooms, submit booking requests, make enquiries, and receive communication through their preferred method (WhatsApp or Email).

The solution will improve operational efficiency, reduce booking conflicts, and enhance customer satisfaction.

---

# 2. Project Background

Oluhle Resort is a small-to-medium hospitality business offering accommodation to local and international guests.

The existing booking process depends heavily on manual administration, making it difficult to manage bookings accurately.

Current booking methods include:

- WhatsApp
- Phone calls
- Email
- Paper booking register

The increasing number of guests has resulted in booking conflicts, slower customer responses, and inefficient reporting.

---

# 3. Business Need

The resort requires a centralized digital booking system to:

- Replace paper booking records
- Prevent double bookings
- Improve customer communication
- Improve operational efficiency
- Generate business reports
- Improve customer satisfaction
- Support future business growth

---

# 4. Business Objectives

The project aims to:

- Digitize all booking processes.
- Reduce double bookings by at least 95%.
- Improve booking response times.
- Provide real-time room availability.
- Centralize customer information.
- Improve communication through WhatsApp and Email.
- Improve reporting capabilities.
- Reduce manual administration.

---

# 5. Project Scope

## In Scope

The system will provide:

- Customer registration
- Customer login
- Room management
- Room availability
- Booking management
- Customer management
- Payment recording
- Check-in
- Check-out
- Customer enquiries
- WhatsApp communication
- Email communication
- Reports
- Staff login
- User management

---

## Out of Scope

The following are excluded from this phase:

- Online payment gateway
- Mobile application
- Loyalty programme
- Integration with travel websites
- SMS notifications

These will be considered in future versions.

---

# 6. Stakeholders

| Stakeholder | Role |
|-------------|------|
| Resort Owner | Project Sponsor |
| Reception Staff | System Users |
| Customers | End Users |
| Housekeeping | Operational Support |
| Accountant | Financial Reporting |
| System Administrator | System Maintenance |
| Business Analyst | Requirements Analysis |
| Software Developer | System Development |

---

# 7. Business Requirements

The business requires the system to:

BR-001
Manage all bookings electronically.

BR-002
Maintain customer records.

BR-003
Display room availability.

BR-004
Prevent double bookings.

BR-005
Record payments.

BR-006
Generate management reports.

BR-007
Manage customer enquiries.

BR-008
Allow customers to select WhatsApp or Email as their preferred communication method.

BR-009
Improve operational efficiency.

BR-010
Reduce paper usage.

---

# 8. Functional Requirements

### Customer

FR-001
The system shall allow customers to register.

FR-002
The system shall allow customers to log in.

FR-003
The system shall display available rooms.

FR-004
The system shall allow customers to submit booking requests.

FR-005
The system shall allow customers to submit enquiries.

FR-006
The system shall allow customers to choose WhatsApp or Email.

---

### Reception Staff

FR-007
Manage bookings.

FR-008
Approve bookings.

FR-009
Cancel bookings.

FR-010
Update booking information.

FR-011
Manage customers.

FR-012
Record payments.

FR-013
Check guests in.

FR-014
Check guests out.

---

### Administration

FR-015
Generate reports.

FR-016
Manage rooms.

FR-017
Manage room availability.

FR-018
Manage users.

FR-019
Manage customer enquiries.

---

# 9. Non-Functional Requirements

## Performance

- Pages should load within 3 seconds.
- Reports should generate within 10 seconds.

---

## Security

- Passwords must be encrypted.
- Users must authenticate before accessing the system.
- User rolesmust be enforced.

---

## Availability

The system should be available 99% of business hours.

---

## Usability

The application must:

- Be easy to learn.
- Use simple navigation.
- Work on desktop and mobile browsers.

---

## Reliability

The system shall:

- Automatically save booking information.
- Prevent data loss.
- Maintain database integrity.

---

# 10. Assumptions

It is assumed that:

- Staff have internet access.
- Staff possess basic computer skills.
- Customers have WhatsApp or Email.
- The resort has stable internet connectivity.

---

# 11. Constraints

Project constraints include:

- Limited budget.
- Limited development time.
- Existing manual business processes.
- Small development team.

---

# 12. Risks

| Risk | Impact | Mitigation |
|------|--------|------------|
| Internet downtime | High | Offline procedures |
| Staff resistance | Medium | User training |
| Data loss | High | Regular backups |
| Security breaches | High | Authentication and encryption |
| Requirement changes | Medium | Change management |

---

# 13. Success Criteria

The project will be considered successful if:

- All bookings are digital.
- Double bookings are eliminated.
- Customer response times improve.
- Reports are automated.
- Staff successfully adopt the system.
- Customers receive confirmations through their preferred communication method.

---

# 14. Business Rules

BR-Rule-001

Every booking must belong to one customer.

BR-Rule-002

A room cannot have more than one active booking for the same dates.

BR-Rule-003

Only authenticated staff may approve bookings.

BR-Rule-004

Every payment must be linked to a booking.

BR-Rule-005

Every booking must have a status.

Possible statuses:

- Pending
- Confirmed
- Checked-In
- Checked-Out
- Cancelled

BR-Rule-006

Customers must select a preferred communication method.

---

# 15. High-Level Business Process

1. Customer searches available rooms.

2. Customer submits booking request.

3. Customer selects preferred communication method.

4. Reception reviews booking.

5. Booking is approved or rejected.

6. Confirmation is sent.

7. Customer checks in.

8. Customer checks out.

9. Payment is recorded.

10. Reports are generated.

---

# 16. Deliverables

The project will deliver:

- Business Analysis documentation
- Web application
- MySQL database
- Administrator dashboard
- Customer portal
- Reporting dashboard
- User documentation
- Testing documentation

---

# 17. Approval

| Role | Name | Signature | Date |
|------|------|-----------|------|
| Resort Owner | | | |
| Business Analyst | Bonolo Lekalakala | | |
| Project Supervisor | | | |

---

# Conclusion

The Business Requirements Document defines the business needs and high-level requirements for the Oluhle Resort Booking Management System.

The proposed solution will modernize the resort's operations by replacing manual booking processes with a secure, centralized web application that improves efficiency, customer service, reporting, and communication through WhatsApp and Email.

The BRD serves as the foundation for the Software Requirements Specification (SRS), system design, development, testing, and implementation.
