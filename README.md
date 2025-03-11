This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First clone or download the repository to your local machine.
Cd into directory and enter following command:
```
npm install
```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```



Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## NOTE
### You will need to create .env file with following :
```
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL =
NEXT_PUBLIC_CLERK_SIGN_UP_URL =    
ARCJET_KEY=
# Connect to Supabase via connection pooling with Supavisor.
DATABASE_URL=
# Direct connection to the database. Used for migrations.
DIRECT_URL=
```        
