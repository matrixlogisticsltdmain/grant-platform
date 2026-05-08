# Grant Platform MVP

A micro-grant application platform for African small businesses. Businesses can apply for $100-3000 grants, pay a $2 verification fee via mobile money, and receive funding after admin approval.

## Features

- ✅ Business application form with proposal upload
- ✅ Mobile money payments via Flutterwave (MTN, Airtel, Orange)
- ✅ Admin review panel
- ✅ Automated user account creation after funding
- ✅ Magic link email login
- ✅ Business owner dashboard

## Tech Stack

- **Backend:** Node.js + Express
- **Database:** Supabase (PostgreSQL)
- **Auth:** Firebase Auth
- **Payments:** Flutterwave
- **Hosting:** Render
- **Frontend:** React Native + React Web

## Quick Start

### Prerequisites
- Node.js 18+
- Supabase account (free)
- Firebase project (free)
- Flutterwave account

### Environment Variables

Create a `.env` file in the backend directory:

```env
SUPABASE_URL=your_supabase_url
SUPABASE_ANON_KEY=your_supabase_anon_key
FLW_PUBLIC_KEY=your_flutterwave_public_key
FLW_SECRET_KEY=your_flutterwave_secret_key
FIREBASE_PROJECT_ID=your_firebase_project_id
FIREBASE_CLIENT_EMAIL=your_firebase_client_email
FIREBASE_PRIVATE_KEY="your_private_key"
