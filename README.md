# SaaSFlow

Modern SaaS subscription and billing management platform built with Next.js, Prisma, PostgreSQL, and Stripe.

> Inspired by SaaSLens by Wondermove-Inc.

---

## Features

- Subscription plan management
- Stripe billing integration
- Usage analytics dashboard
- Automated invoices
- Role-based admin panel
- Revenue tracking
- Secure authentication
- Modern responsive dashboard UI

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | Next.js 15 + React 19 + TypeScript |
| Styling | Tailwind CSS + Shadcn UI |
| Database | PostgreSQL + Prisma |
| Authentication | NextAuth |
| Billing | Stripe |
| Charts | Recharts |

---

## Screenshots

Add screenshots here later.

---

## Quick Start

### Clone Repository

```bash
git clone https://github.com/aadarshantony/proj1.git
cd saasflow
```

### Install Dependencies

```bash
npm install
```

### Environment Variables

Create `.env.local`

```env
DATABASE_URL=""

NEXTAUTH_SECRET=""
NEXTAUTH_URL="http://localhost:3000"

GOOGLE_CLIENT_ID=""
GOOGLE_CLIENT_SECRET=""

GITHUB_CLIENT_ID=""
GITHUB_CLIENT_SECRET=""

STRIPE_SECRET_KEY=""
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=""
STRIPE_WEBHOOK_SECRET=""
```

### Database Setup

```bash
npx prisma migrate dev
npx prisma generate
```

### Run Development Server

```bash
npm run dev
```

Open:

```txt
http://localhost:3000
```

---

## Project Structure

```txt
src/
├── app/
├── components/
├── lib/
├── hooks/
├── types/
└── prisma/
```

---

## Core Modules

### Authentication
- Google OAuth
- GitHub OAuth
- Session management

### Billing
- Stripe subscriptions
- Plan upgrades
- Invoice history
- Usage metering

### Dashboard
- Revenue analytics
- Subscription tracking
- Usage statistics
- Admin controls

---

## Roadmap

- [ ] Team organizations
- [ ] API keys
- [ ] Email notifications
- [ ] Advanced RBAC
- [ ] Multi-tenant support
- [ ] AI analytics insights

---

## License

MIT License

Inspired by SaaSLens by Wondermove-Inc.