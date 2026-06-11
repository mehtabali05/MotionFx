# MotionFx

A tier-based learning platform designed to deliver structured trading education, referral-based onboarding, affiliate access, and subscription-gated learning experiences.

MotionFx allows users to join through a direct sign-up or referral link, start with limited free access, and unlock additional content and features through higher subscription tiers. The platform also includes an affiliate workflow where users can request referral access and receive approval before sharing referral links.

## Live Preview

> https://fxsystems.ca
> https://motionfx-fe-production.up.railway.app

## Screenshots

<img width="300" height="250" alt="auth" src="https://github.com/user-attachments/assets/84c7d1bb-74e4-4196-aeb8-623d493ed2a3" />
<img width="300" height="250" alt="landing" src="https://github.com/user-attachments/assets/7b23e11f-2ec2-40b2-805f-6423fb2863ad" />

<img width="300" height="250" alt="new user" src="https://github.com/user-attachments/assets/c890098c-ce5f-4738-946d-05be00b074d4" />
<img width="300" height="250" alt="user" src="https://github.com/user-attachments/assets/dfa2b01a-fb58-4a66-ba6c-4b7ac642663b" />

<img width="300" height="250" alt="admin" src="https://github.com/user-attachments/assets/6762d4d8-9c93-413a-b96d-6e405667b366" />





## Key Features

### User Access & Onboarding

* Sign up using direct registration or referral link
* Limited access for free users
* Subscription-based content unlocking
* Affiliate request and approval workflow
* Referral link generation after affiliate approval

### Free Tier Access

Free users can view:

* Basic Lessons
* Roadmap
* Settings
* Packages

### Subscription Access

After purchasing a subscription, users can access:

* Advanced Lessons
* Live Sessions
* Partner Portal
* Affiliate referral data and referral performance views

### Master Subscription Access

After upgrading to master subscription, users can access:

* Master Classes
* Master Sessions
* Builder Section
* Advanced affiliate-related features

### Admin Features

* Create and manage courses
* Create and manage tiers
* Create and manage lessons under courses
* Create and manage builders
* Create and manage sessions
* Manage users
* Approve or manage affiliate onboarding requests


## Core Modules

* Authentication & Registration
* Referral Onboarding
* Affiliate Approval
* Subscription Management
* Course Management
* Tier Management
* Lesson Management
* Live Sessions
* Master Classes
* Partner Portal
* Builder Section
* User Management
* Settings

## Project Purpose

MotionFx was built to combine education, subscription monetization, and referral-based growth into one scalable learning platform. It is designed to support both user progression and business growth through tiered access, affiliate workflows, and structured content delivery.

## My Contributions

* Designed and built the platform from scratch
* Implemented referral-based and direct onboarding flows
* Developed subscription-gated access for multiple user tiers
* Built affiliate request and approval workflows
* Created role-based access to learning sections and platform features
* Developed admin tools for managing courses, tiers, lessons, builders, sessions, and users
* Structured the application for scalable content delivery and user progression
* Built the foundation for manager onboarding and platform operations

## Tech Stack

* **Frontend:** React.js, TypeScript
* **Backend:** NestJS, Node.js
* **Database:** PostgreSQL
* **ORM:** Drizzle ORM
* **Data Fetching:** TanStack Query
* **Authentication:** Better Auth
* **Real-Time:** Socket.io
* **Media Storage:** Cloudinary
* **Email Services:** SendGrid
* **Deployment:** Railway
* **Payments:** Stripe

## Best Practices Followed

* Tier-based access control
* Referral and affiliate workflow separation
* Modular content management structure
* Clean and reusable UI components
* Scalable backend architecture
* Secure authentication and permission-based navigation
* Maintainable data relationships for courses, lessons, and subscriptions

## Setup

```bash
git clone https://github.com/mehtabali05/motionfx.git
cd motionfx
npm install
npm run dev
```

## Environment Variables

Create a `.env` file and configure the required values for your setup.

```bash
VITE_API_URL=
VITE_APP_URL=


DATABASE_URL=""
BETTER_AUTH_SECRET=""
BETTER_AUTH_URL=""
FRONTEND_URL=
CORS_ORIGIN=""
STRIPE_SECRET_KEY=""
STRIPE_WEBHOOK_SECRET=""
SENDGRID_API_KEY=""
SENDGRID_FROM_EMAIL=""
PORT=3000
STRIPE_API_VERSION="2022-11-15"
CLOUDINARY_CLOUD_NAME=""
CLOUDINARY_API_KEY=""
CLOUDINARY_API_SECRET=""

```

## Folder Structure

```bash
src/
├── app/
├── components/
├── features/
├── hooks/
├── lib/
├── pages/
├── services/
├── stores/
└── utils/
```

## Future Improvements

* Referral analytics dashboard
* Affiliate performance tracking
* Certificate generation for completed lessons
* Session replay or recordings
* Email automation for course progress
* Advanced masterclass management

## License

This repository is intended for portfolio and demonstration purposes.

## Contact

**Mehtab Ali**
Full Stack Developer
LinkedIn: [https://www.linkedin.com/in/mehtab-ali-280b2631b/](https://www.linkedin.com/in/mehtab-ali-280b2631b/)
