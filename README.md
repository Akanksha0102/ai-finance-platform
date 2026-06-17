# AI Finance Platform 💰

A full-stack AI-powered personal finance management platform built with Next.js 15, featuring intelligent transaction tracking, automated budget alerts, and AI-generated financial insights powered by Google Gemini.

---

## Features

- **Authentication** — Secure sign-up and sign-in via Clerk, with onboarding flow for new users
- **Account Management** — Create and manage multiple bank accounts; track balances across all of them
- **Transaction Tracking** — Add, edit, and categorize income and expense transactions with receipt scanning
- **AI Receipt Scanner** — Upload a receipt and Gemini AI auto-fills transaction details
- **Dashboard & Analytics** — Visual charts (Recharts) showing spending trends, category breakdowns, and monthly comparisons
- **Budget Management** — Set budgets per category and get real-time progress tracking
- **Automated Email Alerts** — Monthly budget reports and low-balance warnings sent via Resend using React Email templates
- **Background Jobs** — Inngest handles recurring tasks like sending monthly summaries and processing scheduled transactions
- **Rate Limiting & Bot Protection** — Arcjet protects API routes from abuse and brute-force attacks
- **Dark Mode** — Full light/dark theme support via next-themes
- **Recurring Transactions** — Schedule transactions to auto-repeat (daily, weekly, monthly)

---

## Tech Stack

| Layer | Technology |
|---|---|
| Framework | Next.js 15 (App Router) |
| Language | JavaScript |
| Auth | Clerk |
| Database | PostgreSQL via Supabase |
| ORM | Prisma |
| AI | Google Gemini API |
| Background Jobs | Inngest |
| Email | Resend + React Email |
| Rate Limiting | Arcjet |
| UI Components | shadcn/ui + Radix UI |
| Styling | Tailwind CSS |
| Charts | Recharts |
| Forms | React Hook Form + Zod |

---
