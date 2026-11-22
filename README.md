# AIRevenueBridge

**From AI products to paying customers.**

AIRevenueBridge is an India-first B2B discovery and pilot-planning marketplace concept. It helps businesses describe operational problems, AI builders publish solutions, and both sides outline measurable pilot engagements.

## MVP features
- AI solution directory with search and category filters
- Buyer demand board with requirement submission
- Pilot brief builder with scope, price, duration and success metric
- Workspace snapshot for listings, requirements and pilot briefs
- Responsive desktop and mobile interface

## Run locally
```bash
npm install
npm run dev
```

## Production build
```bash
npm run build
```

## MVP limitations
- This version is a **browser-local demo**. User-created entries are stored in the current browser's localStorage.
- Authentication, shared database, email notifications, payments, contracts and verified buyer/seller accounts are not connected yet.
- Initial marketplace and demand-board entries are illustrative sample data, not verified customers or live commercial opportunities.
- Do not present sample entries as evidence of traction.

## Production roadmap
1. Connect Supabase Auth and PostgreSQL with row-level security.
2. Add verified buyer/provider profiles, moderation and abuse reporting.
3. Add server-side matching and notification workflows.
4. Add secure paid-pilot checkout after legal, tax and payment flows are defined.
5. Add admin tools, analytics and audit logs.

## Stack
React, Vite, CSS and lucide-react.
