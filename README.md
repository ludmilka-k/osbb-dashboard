# Acme Dashboard
> A powerful tool for viewing, organizing and analyzing your bank records.

###  Try it out (Demo)
* Email: user@nextmail.com
* Password: 123456

<code><img src="/public/hero-desktop.png" /></code>
The app use the starter template for the Next.js App Router [Course](https://nextjs.org/learn). 

## Features

- [x] Authentication using NextAuth
- [x] Route protection with Next.js Middleware
- [x] Fetch live data from Neon database using SQL
- [x] Invoice's CRUD operations via React Server Actions
- [x] Implement streaming with Suspense and loading skeletons
- [x] Search and pagination
- [x] Improve accessibility with Server-side validation of form
- [x] Adding Metadata
- [x] User-Friendly: Custom 404 page, Loading spinners
- [x] Responsive Design (Tailwind)

## Technologies Steak
- [Next.js](https://nextjs.org/)
- [React](https://reactjs.org/)
- [Typescript](https://www.typescriptlang.org)
- [Tailwind CSS](https://tailwindcss.com/)
- [NextAuth.js](https://next-auth.js.org/)
- [Neon](https://neon.tech/)
- [Vercel](https://vercel.com/)

## Getting Started

### Prerequisites
Get or Sign up at:
1. Node.js (v18 or higher).
2. Neon account.
3. Vercel account.

### `.env` file
Set up the environment variables:
* POSTGRES_URL=
* POSTGRES_PRISMA_URL=
* POSTGRES_URL_NON_POOLING=
* POSTGRES_USER=
* POSTGRES_HOST=
* POSTGRES_PASSWORD=
* POSTGRES_DATABASE=

[//]: # (`openssl rand -base64 32`)
* AUTH_SECRET=
* AUTH_URL=http://localhost:3000/api/auth

### Install dependencies

```bash
npm install
```

### Run the development server

```bash
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.