# 💰 SaveSphere — AI-Powered Personal Finance & Investment Manager

![SaveSphere Logo](./public/savesphere-logo.png)

[![Next.js](https://img.shields.io/badge/Built%20With-Next.js-blue.svg?style=flat&logo=nextdotjs)](https://nextjs.org/)
[![TailwindCSS](https://img.shields.io/badge/Styled%20With-TailwindCSS-06b6d4?style=flat&logo=tailwindcss)](https://tailwindcss.com/)
[![Prisma](https://img.shields.io/badge/ORM-Prisma-2d3748?logo=prisma&logoColor=white)](https://www.prisma.io/)
[![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL-blue?logo=postgresql)](https://www.postgresql.org/)
[![Clerk](https://img.shields.io/badge/Auth-Clerk-3b82f6?logo=clerk)](https://clerk.dev)
[![License](https://img.shields.io/github/license/your-username/savesphere)](./LICENSE)

> A sleek, intelligent, and secure personal finance platform to **track, manage, and grow your investments and expenses** — powered by AI.

---

## ✨ Key Highlights

### 🔁 Unified Finance Hub
Track all your financial data: expenses, income, investments, FDs, SIPs, and mutual funds — **in one place**.

### 🤖 AI-Powered Insights
Gemini AI extracts data from receipts, generates spending reports, and offers personalized financial advice.

### 📊 Real-Time Investment Tracking
Get live market prices (via Yahoo Finance), maturity values, and P&L insights.

### 📈 Automated Budgeting & Alerts
Set budgets, monitor goals, and receive alerts via **Inngest** and **React Email**.

### 🔐 Enterprise-Grade Security
Secured with **Clerk Auth** and **Arcjet** (edge & bot protection).

---

## 🖼️ Screenshots

| 📊 Dashboard | 💼 Investment Cards | ➕ Add Investment Modal |
|-------------|---------------------|-------------------------|
| ![](./public/screens/dashboard.png) | ![](./public/screens/cards.png) | ![](./public/screens/modal.png) |

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
⚙️ Setup Instructions
bash
Copy
Edit
# 1. Clone the repo
git clone https://github.com/your-username/savesphere.git
cd savesphere

# 2. Install dependencies
npm install

# 3. Configure environment variables
cp .env.example .env.local
# Fill in:
# - DATABASE_URL
# - CLERK_SECRET_KEY, CLERK_PUBLISHABLE_KEY
# - YAHOO_FINANCE_API_KEY
# - GEMINI_API_KEY
# - ARCJET_SECRET
# - INNGEST_API_KEY

# 4. Set up your database
npx prisma db push

# 5. Start the development server
npm run dev
🔄 User Flow
mermaid
Copy
Edit
graph TD;
  A[User Signup/Login via Clerk] --> B[Dashboard]
  B --> C[Add/View Investments]
  B --> D[Add/View Transactions]
  D --> E[Auto Scan Receipt w/ Gemini AI]
  B --> F[Live Market Data (Yahoo API)]
  B --> G[Monthly Reports + Alerts via Email]
  G --> H[Inngest Schedules Emails]
🧩 Core Features
💼 Investment Management
💹 Add FDs, SIPs, Stocks, Mutual Funds

📌 View maturity values, total invested, and P&L

♻️ Bulk delete & edit functionality

📥 CSV import/export

🧾 Transaction Management
📅 Categorized & recurring transactions

🧠 AI-powered receipt reading (Gemini)

🕒 Smart cron-based scheduling via Inngest

📊 Budget & Reports
🧮 Set monthly budgets per account

📧 Email alerts when budgets are breached

📉 Visual insights via interactive graphs

🔐 Secure & Scalable
🔑 Auth by Clerk

🛡️ Rate-limiting, bot detection via Arcjet

📁 Role-based route protection middleware

🌍 Use Cases
✅ Working Professionals – Manage monthly investments, SIPs, and salary budgeting
✅ Frequent Travelers – Multi-currency support, track expenses in real-time
✅ Finance Enthusiasts – Visualize stock growth, monitor portfolio performance
✅ Small Businesses – Track recurring expenses, automate financial insights

🎯 Impact
🔹 Consolidates all financial data in one platform
🔹 Automates repetitive tasks like receipt scanning and investment logging
🔹 Improves financial literacy with smart, AI-generated insights
🔹 Empowers users to make better saving and investing decisions

🧪 Testing
bash
Copy
Edit
# Lint the code
npm run lint

# Run unit & integration tests
npm run test

# Build the app for production
npm run build
📢 Contributions
We welcome community contributions! Feel free to:

🐛 Report issues

✨ Suggest features

🛠️ Submit pull requests

Before contributing, check our CONTRIBUTING.md file.

📜 License
This project is licensed under the MIT License.

📬 Contact
💻 Project Maintainer: @your-username

🌐 Website: savesphere.io (if available)

📹 Related Tutorials
Check out the Wealth AI Tutorial for the base version of this app focused on expense tracking. SaveSphere builds on top of it with full investment management capabilities.

⭐ Support
If you find this project helpful, please give it a ⭐ on GitHub!

markdown
Copy
Edit

---

✅ **Next Steps**:
- Replace all placeholder links (`your-username`, `.env.example`, image paths, etc.).
- Add `CONTRIBUTING.md`, `.env.example`, and `LICENSE` files if you haven’t yet.
- Consider embedding badges for deployment (e.g., Vercel), CI/CD (e.g., GitHub Actions), or coverage (e.g., Coveralls).

Let me know if you want this exported as a file or converted into a live GitHub Page-style layout.
