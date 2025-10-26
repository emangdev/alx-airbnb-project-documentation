# 🎯 Objective

Visualize System Interactions Using a Use Case Diagram

---

## 📝 Instructions

Based on the features outlined in **Task 1 (Airbnb Clone Backend Requirements)**, use **Draw.io** (or any UML diagram tool of your choice) to create a **Use Case Diagram** that visualizes how different users interact with the system.

Your diagram should clearly show:
- The **actors** (users or external systems).
- The **system boundary** (the Airbnb Clone application).
- The **use cases** (major functionalities users perform).
- The **relationships** between actors and use cases (associations, includes, extends).

---

## 👥 Key Actors

1. **Guest (User)**
   - Registers or logs in.
   - Searches and filters properties.
   - Books a property.
   - Makes a payment.
   - Leaves reviews and ratings.
   - Cancels bookings.

2. **Host**
   - Registers or logs in.
   - Adds, edits, or deletes property listings.
   - Manages bookings.
   - Responds to reviews.
   - Receives payments.

3. **Admin**
   - Monitors users, properties, and bookings.
   - Manages payments and disputes.
   - Manages system data (CRUD operations for users, listings, etc.).

4. **Payment Gateway (External System)**
   - Handles secure payment transactions between guests and hosts.

5. **Email/Notification Service (External System)**
   - Sends booking confirmations, payment updates, and notifications.

---

## 🧩 Core Use Cases to Include

| Category | Use Cases |
|-----------|------------|
| **User Management** | Register, Login, Update Profile |
| **Property Management** | Add Listing, Edit Listing, Delete Listing |
| **Search and Booking** | Search Properties, Filter Properties, Book Property, Cancel Booking |
| **Payments** | Make Payment, Receive Payment |
| **Reviews and Ratings** | Leave Review, View Reviews |
| **Admin Operations** | Manage Users, Manage Listings, Monitor Bookings, Handle Payments |
| **Notifications** | Send Email Notifications, Send In-App Alerts |

---

## 🧠 Design Tips for Your Diagram

- Place the **system boundary** (Airbnb Clone) as a rectangle in the center.
- Position **actors** (Guest, Host, Admin, Payment Gateway, Email Service) outside the system boundary.
- Connect each actor to its respective **use cases** inside the system.
- Use **“include”** and **“extend”** relationships where appropriate:
  - *Example:* `Make Payment` → includes → `Verify Payment`.
  - *Example:* `Book Property` → extends → `Send Confirmation Email`.

---

## 📎 Deliverable

- A **Use Case Diagram (.drawio or .png format)** clearly showing:
  - All main actors.
  - All primary use cases.
  - Correct use of relationships (association, include, extend).

---

## ✅ Outcome

By completing this task, you’ll:
- Understand the **interactions** between different user roles and system features.
- Gain a clearer picture of how the **backend requirements** connect to **user actions**.
- Have a **visual reference** for future API design and database schema planning.
