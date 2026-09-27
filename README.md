# 🚀 Smart API Generator
**Visual No-Code REST API & Database Schema Builder using React, TypeScript & Supabase**

---

## 🌐 Overview

**Smart API Generator** is a developer productivity platform that enables users to visually design relational database schemas and automatically generate production-ready REST APIs. It streamlines backend engineering by combining visual schema modeling, CRUD endpoint generation, role-based access control, and live Swagger/OpenAPI testing in one unified interface.

---

## ✨ Key Features

- 🖱️ **Visual Schema Builder:** Intuitive interface to define tables, columns, data types, and relationships.
- 🔁 **Auto-Generated CRUD Endpoints:** Instantly generates `GET`, `POST`, `PUT`, and `DELETE` endpoints for every table.
- 🔐 **Authentication & Security:** Built-in Email/Password & OAuth authentication powered by Supabase Auth.
- 📄 **One-Click Code & Spec Export:**
  - **OpenAPI 3.0 (Swagger)** specification
  - **PostgreSQL / Supabase SQL** migration scripts
  - **Express.js** backend boilerplate code
- 🧪 **Live API Playground:** Test endpoints and inspect responses directly inside the dashboard.
- 🔒 **RBAC & Table Permissions:** Fine-grained access control and built-in CORS configuration.

---

## 🧱 Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Frontend** | React 18, TypeScript, Vite |
| **UI & Styling** | Tailwind CSS, shadcn/ui, Radix UI, Lucide Icons |
| **Backend & DB** | Supabase (PostgreSQL, Auth, Realtime) |
| **State & Forms** | TanStack React Query, React Hook Form, Zod |

---

## 📁 Project Structure

```text
Smart-API/
├── src/
│   ├── components/       # Reusable UI & schema builder components
│   ├── pages/            # Application views & API playground
│   ├── hooks/            # Custom React hooks
│   ├── integrations/     # Supabase client & types
│   └── App.tsx
├── index.html
├── tailwind.config.ts
├── tsconfig.json
├── package.json
└── README.md
```

## ⚙️ Getting Started
### 1. Clone the repository
```bash


git clone https://github.com/UtkarshDashora/Smart-API.git
cd Smart-API
```
### 2. Install dependencies
```bash

npm install
```
### 3. Configure Environment Variables
Create a .env file in the root directory:

```env


VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```
4. Start the development server
```bash

npm run dev
```
Open http://localhost:5173 in your browser.
