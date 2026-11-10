# AERO COMMAND — EGYPTAIR Operations Dashboard

A lightweight, single-page operations workspace connected to Supabase and deployed on Vercel.

## Live application

- Production: https://egyptair-operations-dashboard.vercel.app
- GitHub: https://github.com/wessammohamedhassan/egyptair-operations-dashboard.

## Features

- Supabase email/password authentication
- Owner-scoped data access through PostgreSQL row-level security
- Executive overview for departments, work-order summaries, safety risks and management decisions
- Department performance and budget overview
- Add safety-risk and management-decision records
- Update management-decision status
- Load clearly labelled sample/demo records

## Technology

- HTML, CSS and browser JavaScript
- Supabase JavaScript client v2 (CDN)
- Supabase Auth and PostgreSQL
- Vercel static hosting with Git-based production deployment

## Supabase configuration

The frontend uses the project's public publishable key only. It does not contain a service-role key or server secret.

- Supabase project ref: `xuvkbyniszzetkebqfmo`
- Region: Frankfurt (`eu-central-1`)
- API URL: `https://xuvkbyniszzetkebqfmo.supabase.co`

Set the Supabase Auth Site URL and allowed redirect URLs to the production domain above. Create an account with an email address you can verify; if email confirmation is enabled, confirm it before signing in.

## Run locally

Serve the repository root with a local web server, for example:

```bash
python -m http.server 8000
```

Then open http://localhost:8000.

## Important limitations

- Dashboard numbers and sample records are illustrative/demo data, not verified EGYPTAIR operational information.
- No live airline systems have been integrated. Maintenance, HR, inventory, safety and finance data are not being imported from operational source systems.
- The dashboard is an operational prototype, not a certified airline operations, safety or maintenance system. Complete security, access-control, data-governance and operational acceptance reviews before any real-world deployment.
