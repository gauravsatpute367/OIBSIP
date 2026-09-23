# Web Development & Designing - Internship Tasks

This repository contains all the web development tasks completed during the internship. The tasks are organized into three levels of increasing complexity.

---

## 📁 Project Structure

```
WEB DEVELOPMENT & DESIGNING/
├── LEVEL 1/           # Beginner - Static HTML/CSS Projects
│   ├── task 1/        # FlowDesk Landing Page
│   ├── task 2/        # Personal Portfolio Page
│   └── task 3/        # Responsive Landing Page
├── LEVEL 2/           # Intermediate - Interactive Frontend
│   ├── task 1/        # Login/Registration Page
│   ├── task 2/        # Dashboard UI
│   ├── task 3/        # Product Listing Page
│   └── task 4/        # Orbit Pizza - Auth & Dashboard (Frontend Only)
└── LEVEL 3/           # Advanced - Full Stack Application
    └── task 1/        # Orbit Pizza - Full Stack MERN-like App
        ├── frontend/  # React + Vite
        └── server.js  # Express.js Backend
```

---

## 🚀 Level 1: Beginner Tasks

### Task 1 - FlowDesk Landing Page
**File:** `LEVEL 1/task 1/index.html`

A modern, responsive landing page for a fictional project management tool "FlowDesk".
- **Tech:** HTML5, CSS3 (Custom Properties, Flexbox, Grid)
- **Features:**
  - Hero section with animated background
  - Feature cards with hover effects
  - Pricing tables
  - Testimonials carousel
  - Footer with newsletter signup
  - Fully responsive (mobile-first)
  - Smooth scroll navigation

### Task 2 - Personal Portfolio Page
**Files:** `LEVEL 1/task 2/index.html`, `LEVEL 1/task 2/gaurav.jpg`

A personal portfolio website showcasing projects, skills, and experience.
- **Tech:** HTML5, CSS3
- **Features:**
  - Hero section with profile image
  - About me section
  - Skills showcase with progress bars
  - Project gallery
  - Contact form
  - Responsive design

### Task 3 - Responsive Landing Page
**File:** `LEVEL 1/task 3/index.html`

A generic responsive landing page template.
- **Tech:** HTML5, CSS3
- **Features:**
  - Navigation bar
  - Hero section
  - Features/Services section
  - Contact section
  - Mobile-responsive layout

---

## 🎯 Level 2: Intermediate Tasks

### Task 1 - Login/Registration Page
**File:** `LEVEL 2/task 1/index.html`

Authentication UI with login and registration forms.
- **Tech:** HTML5, CSS3, Vanilla JS
- **Features:**
  - Toggle between login/register
  - Form validation
  - Password visibility toggle
  - Remember me checkbox
  - Forgot password link
  - Animated transitions

### Task 2 - Dashboard UI
**File:** `LEVEL 2/task 2/index.html`

A dashboard interface with sidebar navigation.
- **Tech:** HTML5, CSS3
- **Features:**
  - Collapsible sidebar
  - Stats cards
  - Data tables
  - Charts placeholder
  - User profile dropdown
  - Responsive layout

### Task 3 - Product Listing Page
**File:** `LEVEL 2/task 3/index.html`

E-commerce style product listing with filters.
- **Tech:** HTML5, CSS3, Vanilla JS
- **Features:**
  - Product grid layout
  - Category filters
  - Price range slider
  - Sort options
  - Add to cart buttons
  - Pagination

### Task 4 - Orbit Pizza Authentication & Dashboard (Frontend)
**Files:** `LEVEL 2/task 4/index.html`, `LEVEL 2/task 4/dashboard.html`

Complete frontend for a pizza ordering application.
- **Tech:** HTML5, CSS3, Vanilla JS (ES6 Modules)
- **Features:**
  - **index.html:** User/Admin login, registration, password reset
  - **dashboard.html:** Menu browsing, cart, order tracking, admin panel
  - LocalStorage for session management
  - Mock API integration ready
  - Dark theme with animated backgrounds

---

## 🏆 Level 3: Advanced Full-Stack Task

### Task 1 - Orbit Pizza Full-Stack Application
**Directory:** `LEVEL 3/task 1/`

A complete pizza ordering system with React frontend and Express.js backend.

#### Backend (`server.js`)
- **Runtime:** Node.js with Express 5
- **Database:** JSON file-based storage (`data/store.json`)
- **Authentication:** JWT with bcryptjs password hashing
- **API Endpoints:**

| Method | Endpoint | Description |
|--------|----------|-------------|
| `GET` | `/api/health` | Health check |
| `GET` | `/api/menu` | Get all pizzas |
| `GET` | `/api/menu/:id/reviews` | Get reviews for a pizza |
| `POST` | `/api/menu/:id/reviews` | Add review (auth required) |
| `GET` | `/api/inventory` | Get inventory |
| `GET` | `/api/offers` | Get active offers |
| `GET` | `/api/deals` | Get active deals |
| `POST` | `/api/auth/register` | User registration |
| `POST` | `/api/auth/login` | User login |
| `POST` | `/api/auth/admin/login` | Admin login |
| `POST` | `/api/auth/forgot-password` | Request password reset |
| `POST` | `/api/auth/reset-password` | Reset password |
| `GET` | `/api/orders/my` | Get user orders (auth) |
| `POST` | `/api/orders` | Place order (auth) |
| `GET` | `/api/admin/orders` | Get all orders (admin) |
| `PATCH` | `/api/admin/orders/:id/status` | Update order status (admin) |
| `PATCH` | `/api/admin/inventory/:id` | Update inventory (admin) |
| `POST` | `/api/admin/menu` | Add product (admin) |
| `PATCH` | `/api/admin/menu/:id` | Update product (admin) |
| `DELETE` | `/api/admin/menu/:id` | Delete product (admin) |
| `PATCH` | `/api/admin/offers/:id` | Update offer (admin) |
| `PATCH` | `/api/admin/deals/:id` | Update deal (admin) |

#### Frontend (`frontend/`)
- **Framework:** React 19 with Vite
- **Styling:** Custom CSS with CSS Variables, Animations
- **State:** React Hooks (useState, useEffect, useMemo)

**User Features:**
- Authentication (login/register/forgot password)
- Browse menu with search, filter, sort
- Product detail page with reviews
- Pizza customization (size, quantity, toppings)
- Shopping cart with quantity controls
- Checkout with address/phone validation
- Order history with status tracking
- Product comparison (up to 3 items)

**Admin Features:**
- Tabbed dashboard (Orders, Products, Offers & Deals, Inventory)
- Order management with full status workflow
- Product CRUD operations
- Offer/Deal activation toggles
- Inventory stock management with low-stock alerts

**UI/UX Highlights:**
- Dark theme with animated gradient backgrounds
- Staggered entrance animations
- Hover/tap micro-interactions
- Toast notifications (auto-dismiss 5s)
- Fully responsive (mobile-first)
- Smooth scroll navigation
- Compare modal with side-by-side specs

---

## 🛠️ Technologies Used

| Category | Technologies |
|----------|--------------|
| **Frontend** | HTML5, CSS3, JavaScript (ES6+), React 19, Vite |
| **Backend** | Node.js, Express 5 |
| **Database** | JSON file storage (file-based) |
| **Authentication** | JWT (jsonwebtoken), bcryptjs |
| **Email** | Nodemailer (Ethereal/SMTP) |
| **Scheduling** | node-cron |
| **Styling** | Custom CSS, CSS Variables, CSS Animations |
| **Build Tool** | Vite |

---

## 🚀 Getting Started

### Level 1 & 2 Tasks
Simply open the `index.html` files in a web browser. No build step required.

```bash
# Example: Open Level 1 Task 1
open "LEVEL 1/task 1/index.html"
```

### Level 3 Task 1 - Full Stack App

#### Prerequisites
- Node.js 18+
- npm 9+

#### Backend Setup
```bash
cd "LEVEL 3/task 1"
npm install
node server.js
# Server runs on http://localhost:5000
```

#### Frontend Setup
```bash
cd "LEVEL 3/task 1/frontend"
npm install
npm run dev
# Frontend runs on http://localhost:5173
```

#### Default Admin Credentials
- **Email:** admin@orbit.com
- **Password:** admin123

---

## 📱 Responsive Breakpoints

| Device | Width |
|--------|-------|
| Mobile | < 560px |
| Tablet | 560px - 880px |
| Desktop | > 880px |

---

## 🎨 Design System

### Color Palette (Level 3)
```css
--primary: #52e0c0 (Mint)
--primary-dark: #189b8a
--accent: #a78bfa (Purple)
--warm: #ff8b67 (Coral)
--gold: #f7bf65
--dark: #081922
--panel: rgba(12, 34, 42, 0.8)
--text: #f8faf8
--muted: #b7d7d4
```

### Animations
- `fadeIn` - Toast notifications, modals
- `slideIn` - Side panels, drawers
- `scaleIn` - Cards, buttons
- `floatLight` - Background orbs
- `nightShift` - Background gradient shift

---

## 📝 License

This project is for educational/internship purposes only.

---

## 👨‍💻 Author

**Gaurav Satpute** - Web Development Intern

---
*Last Updated: September 2026*
