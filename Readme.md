# 🍽️ Restaurant POS & Self-Service Kiosk

A complete, modern **Point of Sale (POS)** and **Self-Service Kiosk** system for restaurants, built with a scalable micro-frontend/backend architecture.

This project includes:

- ✅ Full-featured POS system (cashier interface)
- ✅ Self-service kiosk for customers
- ✅ Loyalty and rewards system
- ✅ Ticket/invoice printing
- ✅ Admin dashboard for full business control
- ✅ Hosted **locally via Docker** for fast and isolated deployment

---

## 📦 Monorepo Architecture

```
restaurant-pos/
│
├── api/         → Spring Boot (Java), PostgreSQL, Docker
├── admin/       → React + Vite (Admin Dashboard)
├── ui/          → React + Vite (POS Interface)
└── kiosk-ui/    → React + Vite (Self-Service Kiosk)
```

Each folder is managed as a separate GitHub repository:
- [`restaurant-pos-Kiosk-api`](https://github.com/SmartLogix520/BorneCommandeServer)
- [`restaurant-pos-Kiosk-admin`](https://github.com/SmartLogix520/BorneCommandeAdmin)
- [`restaurant-pos-ui`](https://github.com/SmartLogix520/restaurant-pos-ui)
- [`kiosk-ui`](https://github.com/SmartLogix520/BorneCommandeClient)

---

## 🚀 Tech Stack

| Component     | Technologies Used                              |
|---------------|--------------------------------------------------|
| API           | Spring Boot, Java, PostgreSQL, Docker           |
| Admin         | React, Vite                                     |
| POS UI        | React, Vite                                     |
| Kiosk UI      | React, Vite                                     |
| Deployment    | Docker (local containers)                       |

---

## ⚙️ Features

### POS (Cashier) System
- Order management (add/edit/remove items)
- Bill splitting & discounts
- Ticket/invoice printing
- Loyalty program integration

### Self-Service Kiosk
- Customer-initiated ordering
- Responsive touch UI
- QR or table code support
- Offline-ready setup

### Admin Dashboard
- Menu and category management
- User and role access
- Real-time order tracking
- Reports and analytics

### API Backend
- RESTful API built with Spring Boot
- PostgreSQL relational database
- Dockerized for local setup