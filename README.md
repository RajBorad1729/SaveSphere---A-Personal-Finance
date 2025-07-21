# 💰 SaveSphere — AI-Powered Personal Finance & Investment Manager

<img width="600" alt="SaveSphere Logo" src="https://github.com/user-attachments/assets/4b2c3aaa-aca0-467a-a646-68a32435ab56" />

[![Next.js](https://img.shields.io/badge/Built%20With-Next.js-blue.svg?style=flat&logo=nextdotjs)](https://nextjs.org/)
[![TailwindCSS](https://img.shields.io/badge/Styled%20With-TailwindCSS-06b6d4?style=flat&logo=tailwindcss)](https://tailwindcss.com/)
[![Prisma](https://img.shields.io/badge/ORM-Prisma-2d3748?logo=prisma&logoColor=white)](https://www.prisma.io/)
[![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL-blue?logo=postgresql)](https://www.postgresql.org/)
[![Clerk](https://img.shields.io/badge/Auth-Clerk-3b82f6?logo=clerk)](https://clerk.dev)
[![License](https://img.shields.io/github/license/your-username/savesphere)](./LICENSE)

> A sleek, intelligent, and secure personal finance platform to **track, manage, and grow your investments and expenses** — powered by AI.

---

## ✨ Key Highlights

- 🔁 **Unified Finance Hub**: Track all your financial data (expenses, income, investments, FDs, SIPs, mutual funds) in one place.
- 🤖 **AI-Powered Insights**: Gemini AI scans receipts and offers smart financial advice.
- 📊 **Live Investment Tracking**: Get real-time prices, maturity values, and portfolio P&L.
- 📈 **Automated Budgeting & Alerts**: Set budgets, receive alerts via Inngest + React Email.
- 🔐 **Enterprise-Grade Security**: Auth via Clerk, protection via Arcjet.

---

## 🖼️ Screenshots

**Start Page**  
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
| **Finance API**| Yahoo Finance API                        |
| **Emails**    | Inngest + React Email + Resend            |
| **Security**  | Arcjet                                     |

---

## 📂 Project Structure

```bash
.
├── app/                      # Next.js App Router files
│   ├── dashboard/            # Main dashboard
│   ├── investments/          # Investment CRUD views
│   ├── api/                  # API Routes (server actions)
├── components/               # Shared UI components
├── lib/                      # Prisma, auth, utils
├── public/                   # Static assets and logos
├── prisma/                   # Prisma schema
├── styles/                   # Tailwind styles
└── .env.local                # Your environment variables

