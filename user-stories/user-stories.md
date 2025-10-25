# Airbnb Clone – User Stories

## Objective
This document translates the main use cases from the Airbnb Clone system into user stories following Agile methodology. Each user story represents a key system interaction from the perspective of different actors such as Guests, Hosts, and Admins.

---

## 🧍‍♂️ 1. User Registration and Login

**As a user (Guest or Host),**  
I want to be able to register for an account  
**so that** I can securely log in and access the platform to book or list properties.

**Acceptance Criteria:**
- The user must provide a valid email and password.
- The system must validate email uniqueness.
- Upon registration, the user should receive a confirmation message or email.
- Login should be available only to verified users.

---

## 🏡 2. Property Listing and Management

**As a Host,**  
I want to list my property with details such as name, location, description, and price per night  
**so that** guests can view and book my property.

**Acceptance Criteria:**
- The host must be a registered user.
- The listing must include mandatory information (name, price, location, and description).
- Hosts can edit, update, or remove their listings.

---

## 🔍 3. Property Search and Booking

**As a Guest,**  
I want to search for properties by location, price, and availability  
**so that** I can easily find and book a property that fits my needs.

**Acceptance Criteria:**
- Guests can apply filters like location, date, and price.
- The system must display available properties.
- Guests can view property details before booking.

---

## 💳 4. Payment Processing

**As a Guest,**  
I want to make secure payments through multiple payment methods  
**so that** I can confirm my booking instantly.

**Acceptance Criteria:**
- Supported payment methods include credit card, PayPal, and Stripe.
- Payment must be linked to a valid booking.
- A confirmation receipt should be generated after successful payment.

---

## 📝 5. Leave a Review

**As a Guest,**  
I want to leave a rating and review after my stay  
**so that** other users can learn about the property’s quality and host experience.

**Acceptance Criteria:**
- Reviews can only be submitted after a confirmed stay.
- Ratings should be on a scale of 1 to 5.
- Comments must be text-based and stored with timestamps.

---

## 🧰 6. Admin Management

**As an Admin,**  
I want to review, approve, or reject property listings  
**so that** only verified and high-quality listings are available on the platform.

**Acceptance Criteria:**
- Admin can view all pending property listings.
- Admin can approve, reject, or deactivate listings.
- Admin actions should be logged for auditing.

---

## 💬 7. Messaging Between Users

**As a Guest or Host,**  
I want to send and receive messages within the platform  
**so that** I can communicate about bookings or property details.

**Acceptance Criteria:**
- Messages must include sender, recipient, and message body.
- The system must display message history.
- Notifications should be sent for new messages.

---

## Summary
These user stories describe the essential features and interactions required in the Airbnb Clone project. They ensure that all system functionalities align with user needs and project goals.

