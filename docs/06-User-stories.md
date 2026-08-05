# User Stories

## Document Information

| Item | Details |
|------|---------|
| **Project** | Resort Booking Management System |
| **Client** | Oluhle Resort |
| **Document** | User Stories |
| **Version** | 1.0 |
| **Author** | Bonolo Lekalakala |
| **Date** | 05 August 2026 |
| **Status** | Draft |

---

# Epic 1 – Employee Authentication

## US-001

**As an** employee

**I want** to log into the system

**So that** I can access the resort management system according to my role.

**Priority:** High

### Acceptance Criteria

- Employee enters a valid username and password.
- Only active employees can log in.
- Invalid login credentials display an error message.
- Employee is redirected to the correct dashboard after login.

---

## US-002

**As an** employee

**I want** to reset my password

**So that** I can regain access to my account.

**Priority:** Medium

### Acceptance Criteria

- Employee can request a password reset.
- Employee creates a new secure password.
- Employee can log in using the new password.

---

# Epic 2 – Chalet Management

## US-003

**As a** receptionist

**I want** to view available chalets

**So that** I can assign accommodation to customers.

**Priority:** High

### Acceptance Criteria

- Only available chalets are displayed.
- Booked chalets are excluded.
- Chalets under maintenance are excluded.

---

## US-004

**As an** administrator

**I want** to add chalets

**So that** customers have accommodation available for booking.

**Priority:** High

### Acceptance Criteria

- Administrator can add a chalet number.
- Capacity can be specified.
- Price per night is recorded.
- Chalet status is saved.

---

## US-005

**As an** administrator

**I want** to edit chalet details

**So that** accommodation information remains accurate.

**Priority:** High

### Acceptance Criteria

- Administrator can update chalet information.
- Changes are saved successfully.

---

## US-006

**As an** administrator

**I want** to update chalet availability

**So that** unavailable chalets cannot be assigned.

**Priority:** Medium

### Acceptance Criteria

- Chalet status can be changed to Available.
- Chalet status can be changed to Booked.
- Chalet status can be changed to Maintenance.

---

# Epic 3 – Booking Management

## US-007

**As a** customer

**I want** to submit a booking request

**So that** I can request accommodation online.

**Priority:** High

### Acceptance Criteria

- Customer completes the booking request form.
- Booking request is submitted successfully.
- Customer receives a confirmation message.

---

## US-008

**As a** receptionist

**I want** to assign an available chalet

**So that** customers are allocated accommodation.

**Priority:** High

### Acceptance Criteria

- Only available chalets appear in the dropdown list.
- Selected chalet is linked to the booking.
- Assigned chalet appears on the booking details page.

---

## US-009

**As a** receptionist

**I want** to confirm bookings

**So that** customer reservations become confirmed.

**Priority:** High

### Acceptance Criteria

- Booking status changes to Confirmed.
- Assigned chalet status changes to Booked.
- Total booking price is calculated automatically.

---

## US-010

**As the** system

**I want** to calculate the booking total automatically

**So that** staff do not calculate accommodation costs manually.

**Priority:** High

### Acceptance Criteria

- Number of nights is calculated.
- Chalet price per night is retrieved.
- Total price is saved to the booking.

---

## US-011

**As a** receptionist

**I want** to decline bookings

**So that** unavailable bookings are rejected.

**Priority:** Medium

### Acceptance Criteria

- Booking status changes to Cancelled.
- Customer is notified of the decision.

---

## US-012

**As a** receptionist

**I want** to cancel bookings

**So that** incorrect reservations can be removed.

**Priority:** Medium

### Acceptance Criteria

- Booking status changes to Cancelled.
- Chalet becomes available if previously assigned.

---

## US-013

**As a** receptionist

**I want** to update booking details

**So that** customer information remains accurate.

**Priority:** High

### Acceptance Criteria

- Receptionist can edit booking information.
- Updated information is saved successfully.

---

## US-014

**As a** receptionist

**I want** to check guests in

**So that** occupancy records are updated.

**Priority:** High

### Acceptance Criteria

- Booking status changes to Checked In.
- Check-in date is recorded.

---

## US-015

**As a** receptionist

**I want** to check guests out

**So that** the chalet becomes available for future bookings.

**Priority:** High

### Acceptance Criteria

- Booking status changes to Checked Out.
- Chalet status changes to Available.

---

# Epic 4 – Customer Management

## US-016

**As a** receptionist

**I want** to view customer information

**So that** I can assist customers quickly.

**Priority:** High

### Acceptance Criteria

- Customer details are displayed.
- Booking history is accessible.

---

## US-017

**As a** receptionist

**I want** to update customer information

**So that** customer records remain accurate.

**Priority:** High

### Acceptance Criteria

- Receptionist can edit customer details.
- Changes are saved successfully.

---

## US-018

**As an** administrator

**I want** to search for customers

**So that** I can locate customer records quickly.

**Priority:** Medium

### Acceptance Criteria

- Customers can be searched by name.
- Customers can be searched by email.
- Matching records are displayed.

---

# Epic 5 – Payments

## US-019

**As the** system

**I want** to generate an invoice after booking confirmation

**So that** customers know the amount payable.

**Priority:** High

### Acceptance Criteria

- Invoice contains customer details.
- Invoice contains booking details.
- Invoice contains total booking amount.

---

## US-020

**As a** receptionist

**I want** to record customer payments

**So that** confirmed bookings are marked as paid.

**Priority:** High

### Acceptance Criteria

- Payment amount is captured.
- Payment date is stored.
- Booking payment status is updated.

---

## US-021

**As an** accountant

**I want** to view payment history

**So that** I can reconcile financial transactions.

**Priority:** High

### Acceptance Criteria

- Previous payments are displayed.
- Payments can be searched by booking.

---

## US-022

**As an** accountant

**I want** to generate payment reports

**So that** financial records can be prepared.

**Priority:** High

### Acceptance Criteria

- Payment reports can be generated.
- Reports display payment totals.

---

# Epic 6 – Customer Enquiries

## US-023

**As a** customer

**I want** to submit an enquiry

**So that** I can request assistance.

**Priority:** High

### Acceptance Criteria

- Customer submits an enquiry.
- Enquiry is saved successfully.

---

## US-024

**As a** receptionist

**I want** to respond to customer enquiries

**So that** customers receive timely feedback.

**Priority:** High

### Acceptance Criteria

- Receptionist views enquiries.
- Response is recorded.
- Customer is notified.

---

# Epic 7 – Communication

## US-025

**As a** customer

**I want** to choose WhatsApp

**So that** I receive booking updates through WhatsApp.

**Priority:** High

### Acceptance Criteria

- WhatsApp can be selected as the preferred communication method.

---

## US-026

**As a** customer

**I want** to choose Email

**So that** I receive booking updates through email.

**Priority:** High

### Acceptance Criteria

- Email can be selected as the preferred communication method.

---

## US-027

**As the** system

**I want** to send booking confirmation notifications

**So that** customers know their booking has been confirmed.

**Priority:** High

### Acceptance Criteria

- Notification is sent after confirmation.
- Booking details are included.

---

## US-028

**As the** system

**I want** to send booking reminders

**So that** customers remember their upcoming stay.

**Priority:** Medium

### Acceptance Criteria

- Reminder is sent before check-in.
- Reminder includes booking information.

---

# Epic 8 – Reports

## US-029

**As a** manager

**I want** to view booking reports

**So that** I can monitor booking activity.

**Priority:** High

### Acceptance Criteria

- Report displays booking statistics.
- Report can be filtered by date.

---

## US-030

**As a** manager

**I want** to view chalet occupancy reports

**So that** I can monitor accommodation utilisation.

**Priority:** High

### Acceptance Criteria

- Occupancy percentage is displayed.
- Occupied and available chalets are shown.

---

## US-031

**As a** manager

**I want** to view revenue reports

**So that** I can evaluate business performance.

**Priority:** High

### Acceptance Criteria

- Revenue totals are displayed.
- Revenue can be filtered by date.

---

## US-032

**As a** manager

**I want** to view enquiry reports

**So that** I can monitor customer service performance.

**Priority:** Medium

### Acceptance Criteria

- Number of enquiries is displayed.
- Response status is shown.

---

# Summary

| Epic | Number of Stories |
|------|------------------:|
| Employee Authentication | 2 |
| Chalet Management | 4 |
| Booking Management | 9 |
| Customer Management | 3 |
| Payments | 4 |
| Customer Enquiries | 2 |
| Communication | 4 |
| Reports | 4 |

**Total User Stories:** **32**