# Yacob Tech | Startup

**Building Tomorrow, Today.**

A modern corporate technology website built from the open-source Startup Next.js template.

## Project goals

- Responsive company website with a modern technology aesthetic
- Service and business-sector pages
- English, Afaan Oromo, and Amharic language support
- Blog and company news
- Secure administrator dashboard
- Supabase database and authentication with server-side authorization and Row Level Security
- Contact form with server-side email delivery
- Deployment through Vercel

## Current status

The initial branding pass is in progress on the `feature/corporate-platform` branch. Backend integrations, multilingual content, admin features, automated tests, and deployment still need to be implemented and verified. Do not treat these planned features as operational until tested.

## Development

Requirements: Node.js 20 or later and npm.

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

Before production, run the available checks, verify all environment variables, configure Supabase RLS policies, and test admin access and contact-form delivery.

## Environment variables

Use a local `.env.local` file and configure production values in Vercel. Never commit secrets. The exact required variables will be documented when the integrations are implemented.

## Original template and license

This project is based on [NextJSTemplates/startup-nextjs](https://github.com/NextJSTemplates/startup-nextjs). The upstream project is licensed under the MIT License. Keep the original copyright and license notice in `LICENSE` and preserve applicable attribution.

Original template copyright: Next.js Templates (2023).
