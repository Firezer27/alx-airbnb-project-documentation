# Airbnb Clone Backend - Requirements Specification

## 📘 Overview
This document defines the **functional** and **technical requirements** for the core backend features of the Airbnb Clone system.  
It describes how the backend supports user management, property listings, and booking processes through secure RESTful APIs.

---

## 🧩 Key Backend Features
The following features are covered in this document:
1. **User Authentication and Authorization**
2. **Property Management**
3. **Booking Management System**

---

## 1️⃣ User Authentication and Authorization

### 🎯 Objective
Allow users (guests and hosts) to securely register, log in, and manage their accounts.

### 🧠 Functional Requirements
- Users must be able to register with an email and password.
- Passwords must be stored securely (hashed).
- Authentication tokens (JWT) should be used for session management.
- Users can update profile information.
- Only authenticated users can access protected routes.

### ⚙️ API Endpoints

| Method | Endpoint | Description | Auth Required |
|:-------|:----------|:-------------|:---------------|
| POST | `/api/v1/auth/register` | Register a new user | ❌ |
| POST | `/api/v1/auth/login` | Log in and receive a JWT token | ❌ |
| GET | `/api/v1/users/profile` | Retrieve logged-in user info | ✅ |
| PUT | `/api/v1/users/profile` | Update user profile | ✅ |

### 🧾 Input/Output Specifications

**Register (POST /api/v1/auth/register)**  
**Input:**
```json
{
  "name": "John Doe",
  "email": "john@example.com",
  "password": "strongPassword123"
}

