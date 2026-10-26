# KNOWRISE website starter

Premium navy-and-gold Next.js website for KNOWRISE.

## Included
- Responsive homepage
- Opportunity categories and clearly labelled placeholder listing cards
- Learning Centre introduction
- About and founder section using the supplied image assets
- Admin dashboard UI preview at `/admin`
- Tailwind CSS and TypeScript setup

## Important status
The `/admin` route is **only a UI preview**. It is not authenticated and must not be treated as a secure admin system. Before production, connect Supabase, implement authentication and server-side authorization, and connect real opportunity/resource CRUD operations. Do not publish private data on the current admin preview.

Opportunity cards are demonstration placeholders, not real open opportunities. Replace them with verified listings before launch.

## Assets
- `public/images/knowrise-logo.png`: supplied official KR logo
- `public/images/founder-yahaya.jpg`: supplied founder photograph

## Run locally
Install Node.js, then run:
1. `npm install`
2. `npm run dev`

## Deploy
Push the project to GitHub and import the repository into Vercel. Use the default Next.js framework preset. Add Supabase environment variables only after the database/authentication integration has been implemented.
