# <img width="40" alt="SaveSphere Logo" src="https://github.com/user-attachments/assets/4b2c3aaa-aca0-467a-a646-68a32435ab56" /> SaveSphere — AI-Powered Personal Finance & Investment Manager

[![Live Site](https://img.shields.io/badge/Live%20App-SaveSphere-0f172a?style=flat&logo=vercel&logoColor=white)](https://save-sphere-a-personal-finance.vercel.app)
[![Next.js](https://img.shields.io/badge/Built%20With-Next.js-blue.svg?style=flat&logo=nextdotjs)](https://nextjs.org/)
[![TailwindCSS](https://img.shields.io/badge/Styled%20With-TailwindCSS-06b6d4?style=flat&logo=tailwindcss)](https://tailwindcss.com/)
[![Prisma](https://img.shields.io/badge/ORM-Prisma-2d3748?logo=prisma&logoColor=white)](https://www.prisma.io/)
[![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL-blue?logo=postgresql)](https://www.postgresql.org/)
[![Clerk](https://img.shields.io/badge/Auth-Clerk-3b82f6?logo=clerk)](https://clerk.dev)

> A sleek, intelligent, and secure personal finance platform to **track, manage, and grow your investments and expenses** — powered by AI.

## 🚀 Live Demo

🔗 [https://save-sphere-a-personal-finance.vercel.app](https://save-sphere-a-personal-finance.vercel.app)

---
## ✨ Key Highlights

- 🔁 **Unified Finance Hub**: Track all your financial data (expenses, income, investments, FDs, SIPs, mutual funds) in one place.
- 🤖 **AI-Powered Insights**: Gemini AI scans receipts.
- 📊 **Live Investment Tracking**: Get real-time prices, maturity values, and portfolio P&L.
- 📈 **Automated Budgeting & Alerts**: Set budgets, receive alerts via Inngest + React Email.
- 🔐 **Enterprise-Grade Security**: Auth via Clerk, protection via Arcjet.

---

## 🖼️ Screenshots

**SaveSphere Hero Page**  
<img width="1912" alt="Start Page" src="https://github.com/user-attachments/assets/bf0bec37-92ae-4a69-b9e0-e81f8b0bc6c9" />

| 📊 Dashboard | 💼 AccountWise Analysis | ➕ Add Transaction | 💹 Investment Dashboard |
|-------------|--------------------------|--------------------|--------------------------|
| <img width="1270" alt="Dashboard" src="https://github.com/user-attachments/assets/4e396729-2702-4274-b70c-38e3129bf627" /> | <img width="1310" alt="AccountWise" src="https://github.com/user-attachments/assets/f3a194d8-4437-4acb-8c7b-a022ddb4f332" /> | <img width="669" alt="Add Transaction" src="https://github.com/user-attachments/assets/14443274-6082-4885-b03b-c7f177bc2c69" /> | <img width="1367" alt="Investment" src="https://github.com/user-attachments/assets/2e2ce695-ced7-4213-a8b8-0c091c2e429d" /> |

---

## 🧠 Tech Stack

| Layer         | Tech                                      |
|---------------|-------------------------------------------|
| **Frontend**  | Next.js App Router, React, Tailwind CSS   |
| **UI/UX**     | `shadcn/ui`, Lucide Icons                 |
| **Backend**   | Next.js API Routes (Server Actions)       |
| **Database**  | PostgreSQL + Prisma ORM                   |
| **Auth**      | Clerk                                     |
| **AI**        | Gemini AI (receipt auto-fill)             |
| **Finance API**| Yahoo Finance2(Node Js)                      |
| **Emails**    | Inngest + React Email + Resend            |
| **Security**  | Arcjet                                     |

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```sh
git clone https://github.com/RajBorad1729/SaveSphere---A-Personal-Finance.git
cd SaveSphere---A-Personal-Finance
```

### 2️⃣ Install Dependencies
```sh
npm install
```
### 3️⃣ Configure Environment Variables

make .env filr
Fill in the following variables inside .env:
```sh
DATABASE_URL=
DIRECT_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=

RESEND_API_KEY=

ARCJET_KEY=

```
### 4️⃣ Set Up Database
```sh
npx prisma db push
```
5️⃣ Start Development Server
```sh
npm run dev
```

### ➡️ Visit: http://localhost:3000
---
## 🔄 User Flow Diagram
<img width="4552" height="1800" alt="image" src="https://github.com/user-attachments/assets/8d3f5a60-b629-4b10-a98d-27da150d0785" />

---
## 🔍 Core Functionalities

### 💼 Investment Management
- Track **Fixed Deposits (FDs)**, **SIPs**, **Stocks**, **Mutual Funds**
- Maturity calculations, P&L.

### 🧾 Transaction Management
- Categorized & recurring entries
- **Gemini AI** powered receipt scanning
- Customizable frequency rules for recurring transactions

### 📈 Budgets & Reports
- Set monthly budgets by category
- Visual insights and summaries
- **Email alerts** via React Email

### 🔐 Security & Auth
- **Clerk-based** Auth (JWT)
- RBAC route protection
- **Arcjet** for bot protection & rate limiting

---

## 🌍 Use Cases

✅ **Working Professionals** — salary, SIPs & investment tracking  
✅ **Frequent Travelers** — multi-currency transactions  
✅ **Finance Enthusiasts** — deep portfolio insights  
✅ **SMB Owners** — recurring expenses & smart analytics  

---

## 🎯 Impact

📦 Centralizes financial life into one dashboard  
🤖 Automates tedious tasks (e.g., receipt entry)  
📉 Provides smarter insights for better financial planning  
📈 Helps users grow savings and optimize investments  

---

## 🧪 Testing

```sh
# Lint the code
npm run lint

# Run unit/integration tests
npm run test

# Build for production
npm run build
```
---
## 🙌 Contributions Welcome
I ❤️ community input. Feel free to:

- 🐛 Report bugs

- ✨ Suggest new features

---
## 📬 Contact
Maintainer: @RajBorad1729
