# Airbnb Clone – Flowchart for System Process

## 🎯 Objective
This document provides a **flowchart** illustrating one of the key backend processes in the Airbnb Clone system — **User Registration**.  
The goal of this flowchart is to show how data moves step-by-step through the backend system, from the user submitting input to data validation, storage, and confirmation.

---

## 🧩 Process Overview: User Registration

### 🧠 Description
The **User Registration** process allows new users (guests or hosts) to create accounts on the platform.  
The backend validates input, ensures email uniqueness, hashes passwords securely, and stores user data in the database.

---

## 🔄 Flow Steps

| Step | Description |
|------|--------------|
| **1. Start** | The user initiates registration by submitting the registration form. |
| **2. Input Validation** | Backend validates all required fields — name, email, and password. |
| **3. Check Email Uniqueness** | System checks whether the email is already registered. |
| **4. Hash Password** | If valid, the password is hashed using bcrypt before storage. |
| **5. Store in Database** | User details are saved into the database. |
| **6. Send Confirmation Email** | System sends a welcome or verification email to the user. |
| **7. Registration Success** | The system returns a success message to the frontend. |
| **8. End** | The registration process is completed. |

---

## 🖼️ Flowchart Diagram
The flowchart below visually represents the process described above.

