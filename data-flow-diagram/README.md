# Airbnb Clone – Data Flow Diagram (DFD)

## 🎯 Objective
This document presents the **Data Flow Diagram (DFD)** for the Airbnb Clone backend system.  
The goal is to visualize how data moves between different entities (Users, Properties, Bookings, and Payments) and system processes.  

The DFD shows the interaction between **external entities**, **internal processes**, **data stores**, and **data flows**, providing a clear view of the backend architecture.

---

## 🧩 DFD Overview

### 📘 Level 0 (Context Diagram)
At the highest level, the Airbnb system interacts with:
- **Guest (User)** – Registers, searches, and books properties.
- **Host** – Lists and manages properties.
- **Admin** – Manages the overall system.
- **Payment Gateway** – Processes payments securely.

All interactions are processed through the **Airbnb Backend System** which communicates with a central database.

---

### 📗 Level 1 (Detailed Data Flow)
Below are the main processes and data flows represented in the DFD:

| Process | Description | Inputs | Outputs |
|----------|--------------|--------|----------|
| **1.0 User Management** | Handles registration, login, and authentication. | User credentials | Authenticated user session |
| **2.0 Property Management** | Hosts create, update, or delete property listings. | Property details | Listing stored in database |
| **3.0 Booking Management** | Manages property bookings by guests. | Booking requests | Booking confirmation |
| **4.0 Payment Processing** | Handles payment validation and transactions. | Payment info | Payment receipt |
| **5.0 Reviews & Ratings** | Allows guests to post reviews for completed bookings. | Review data | Review stored in database |

---

## 📊 DFD Components

### 🧍 External Entities
- **Guest**
- **Host**
- **Admin**
- **Payment Gateway**

### ⚙️ Processes
- 1.0 User Management  
- 2.0 Property Management  
- 3.0 Booking Management  
- 4.0 Payment Processing  
- 5.0 Review Management

### 🗃️ Data Stores
- D1: User Database  
- D2: Property Database  
- D3: Booking Database  
- D4: Payment Database  
- D5: Review Database  

### 🔄 Data Flow Examples
- Guest → Register/Login → User Management → D1: User Database  
- Host → Create Property → Property Management → D2: Property Database  
- Guest → Book Property → Booking Management → D3: Booking Database  
- Booking Management → Payment Processing → D4: Payment Database  
- Guest → Submit Review → Review Management → D5: Review Database  

---

## 🧠 Insights
The DFD ensures:
- Clear visualization of how data travels across components.
- Identification of key processes for implementation.
- Understanding of data input/output relationships.

---

## 🖼️ Exported Diagram
The visual Data Flow Diagram is saved as:

