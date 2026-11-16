# Outlet performance dashboard

Single-page dashboard (`index.html`, no build step) backed by Supabase.

- Sales vs target KPIs, outlet filter, per-outlet-week bars, "Needs attention" list
- Username/password sign-in via Supabase Auth; admins can add users from the Users page
- Data: `public.outlet_weekly`; profiles/roles: `public.profiles`

## Deploy on Vercel
1. Import this repo in Vercel (Framework Preset: **Other**).
2. Leave Build Command and Output Directory empty/default. Deploy.

Supabase URL and the publishable key are in `index.html` (they are designed to be public; access is enforced by Row Level Security).
