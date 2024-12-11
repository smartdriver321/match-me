# Match Me App

> A full-stack dating application built with Next.js 14, Prisma, NextAuth, Pusher, and Cloudinary.

## URL

[YouTube App Demo](https://youtu.be/HqlJjX9uIuk)

## Tools

- Next.js 14
- Prisma
- NextAuth (Auth.js)
- Pusher
- Cloudinary
- Vercel
- PostgreSQL
- React Hook Form
- Zod Validation
- Zustand
- TypeScript

## Prerequisites

- Node.js (v18 or higher)
- PostgreSQL database

## Installation

1. Clone the repo
2. Install packages `npm install`
3. Set up environment variables in .env file
4. Set up Prisma database

```bash
npx prisma generate
npx prisma migrate dev
npx prisma db seed

Add to script for seeding
"prisma": {
		"seed": "ts-node --compiler-options {\"module\":\"CommonJS\"} prisma/seed.ts"
	}
```

5. Run the development server `npm run dev`
