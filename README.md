# AERO COMMAND — Supabase-backed executive dashboard

This is an English-language, single-page starter application adapted from the supplied EGYPTAIR dashboard prototype.

## Supabase project
- Project: `EGYPTAIR-Operations-Dashboard`
- Project ref: `xuvkbyniszzetkebqfmo`
- Region: Frankfurt (`eu-central-1`)
- URL: `https://xuvkbyniszzetkebqfmo.supabase.co`
- Browser configuration uses a Supabase publishable key. No service-role or secret key is included.

## Included
- Email/password sign-up and sign-in via Supabase Auth
- Owner-scoped PostgreSQL tables protected by row-level security
- Department directory, work-order summary, risk register, decisions and budget rollups
- Add risk and decision records; update decision status
- CSV export for department financial/headcount summary
- Clearly labelled prototype sample-data loader

## Run locally
1. Serve this folder from a local web server, for example `python -m http.server 8000`.
2. Open `http://localhost:8000`.
3. Create an account using an email address you can verify.
4. If email confirmation is enabled, confirm the message and sign in.
5. Select **Load prototype sample data** to explore the dashboard with illustrative records.

The Supabase database migration has already been applied to the project. The application uses the Supabase JavaScript v2 CDN and the project's publishable key.

## Important limitations
- Dashboard figures and sample records are simulated/illustrative, not actual EGYPTAIR operational data.
- Maintenance, HR, inventory, safety, finance and other operational source systems have not been connected. No live airline records have been imported.
- This repository does not constitute a live hosted website. Deploy the folder to a static host and configure Supabase Auth site and redirect URLs for that host.
- Before production use, define organization roles and permissions, review data governance, connect approved source systems, configure backups/monitoring, and complete security and operational acceptance testing.
