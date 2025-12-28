## 🧾 ExpenseTracker AI

ExpenseTracker AI is a modern AI-powered expense tracking web application built with Next.js 15. It helps users efficiently manage their expenses, analyze spending habits, and gain actionable insights using AI.

## 🚀 Features

Expense Management: Add, edit, and delete expenses with ease

AI-Powered Categorization: Automatic category suggestions based on descriptions

Visual Analytics: Interactive charts to track daily, weekly, and monthly spending

Insights Dashboard: Personalized recommendations and insights

Transaction History: Complete history with search and filtering options

## 🖥️ User Interface

Light & Dark Mode: Seamless theme switching

Responsive Design: Optimized for mobile, tablet, and desktop

Smooth Animations: Clean, modern interactions for better user experience

## 🔐 Authentication & Security

Multiple Login Options: Google, GitHub, Facebook, or email/password

Secure Sessions: Managed via Clerk

User Profiles: Personalized dashboards and data management

## ⚙️ Technology Stack

Frontend: Next.js 15, React 19, TypeScript, Tailwind CSS

Data Visualization: Chart.js

Backend & Database: Neon PostgreSQL, Prisma ORM

AI Integration: OpenRouter AI


## ▶️ Getting Started
1. Clone the Repository
git clone https://github.com/ShivaniSNair/ExpenseTrackerAI.git
cd next-expense-tracker-ai

2. Install Dependencies
npm install

3. Setup Environment Variables

Create a .env file in the project root:

* DATABASE_URL=
* NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
* CLERK_SECRET_KEY=
* OPENROUTER_API_KEY=

4. Run the Development Server
npm run dev


Open http://localhost:3000
 in your browser.

## 📁 Database Schema

User: Stores authenticated user information

Record: Stores expense transactions including category, amount, and date

## 📊 Highlights

Easy expense management with AI suggestions

Interactive charts for data visualization

Comprehensive expense history with search and filtering

One-click deletion of entries
