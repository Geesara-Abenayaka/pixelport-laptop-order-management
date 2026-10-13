# PixelPort - Laptop Order Management System

PixelPort is a hybrid order and inventory management solution tailored for laptop retail and distribution. The system provides a unified ecosystem featuring a modern web application for customer interactions and orders, complemented by a dedicated C# .NET desktop client for high-efficiency management and administrative operations.

---

## 🚀 Features

### Desktop Application (`PixelPort`)
- Built with C# and .NET (`.sln`).
- Fast offline-first/local administrative control for inventory and order dispatch.
- Detailed laptop specification management (brand, CPU, GPU, RAM, storage, pricing).
- Order processing, billing, and receipt generation.

### Web Application (`myproject` / `Backend`)
- Responsive customer-facing storefront to browse, filter, and order laptops.
- Robust API layer powered by Prisma ORM for structured database interactions.
- Order status tracking and real-time inventory synchronization.

---

## 🛠️ Tech Stack & Architecture

- **Desktop Client:** C# / .NET Framework / WPF or Windows Forms
- **Backend API:** Node.js / Express.js / Prisma ORM
- **Frontend Web:** Modern JavaScript (React / HTML / CSS)
- **Database:** SQLite / PostgreSQL / MySQL (managed via Prisma)

---

## 📁 Repository Structure

```text
├── Backend/
│   └── PRISMA/         # Prisma schema, migrations, and database configuration
├── PixelPort/          # C# .NET desktop application source code
├── PixelPort.sln       # Visual Studio solution file
├── myproject/          # Web frontend / client-side application
└── README.md
