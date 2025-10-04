# Natural_Stupidity
odoo X IIT Gandhinagar Hackathon
# 🧩 Company Auth & Management System (Simulation)

A *fully simulated company authentication and management dashboard* built using *Tailwind CSS* and *Vanilla JavaScript (ES Modules)* — powered by *Firebase (mock mode)* for company administration, user roles, and expense management workflows.

This project demonstrates a multi-role environment with *Admin, **Manager, and **Employee* views — all running client-side in simulation mode (no live backend required).

---

## 🚀 Features

### 🔐 Authentication (Simulated)
- Admin Sign Up and Sign In forms.
- Email and password validation.
- Firebase Auth placeholders (simulation mode active by default).
- Role-based dashboard switching: Admin / Manager / Employee.

### 🧭 Admin Dashboard
- Create new company users (Employee or Manager roles).
- Manage company user list dynamically.
- Define complex multi-approver rules for expense approvals:
  - Sequential vs parallel approvals.
  - Manager involvement toggle.
  - Minimum approval percentage logic.
- Real-time UI updates with live DOM rendering.

### 💼 Employee Dashboard
- Create, edit, and submit expense requests.
- Save drafts before submission.
- Simulated OCR receipt upload:
  - Auto-fills date, amount, and description.
  - Mock currency extraction and conversion.
- View expense history with status tracking:
  - Draft → Pending → Approved / Rejected.
- Auto conversion into company base currency (mocked).

### 🧾 Manager Dashboard
- View pending approvals assigned to the manager.
- Approve or reject expense requests.
- See real-time status updates.

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|-------------|
| Frontend | *HTML5, **Tailwind CSS, **JavaScript (ES Modules)* |
| UI Framework | *Tailwind CSS* (CDN) |
| Fonts | *Google Fonts – Inter* |
| Auth & Database (Simulated) | *Firebase Auth* & *Firestore (Mock)* |
| State Management | Vanilla JS Objects & Local State |


