Smart Incubation — Redirect Service

🔁 Permanent Redirect for Legacy Vercel URL

This repository exists only to preserve backward compatibility for users accessing the old Vercel URL and to redirect them to the new canonical domain.

🔗 What This Repo Does

All traffic to:

https://incubation-platform.vercel.app

is permanently redirected (HTTP 308) to:

https://smartincubation.co.za

This ensures:

No broken links for existing users

SEO-safe migration

Deep-link preservation (/login, /dashboard, etc.)

Zero downtime during domain transition

🧠 Why This Exists

The main application repository was moved to a Vercel Organization and deployed under a custom domain.

However, the original Vercel project (incubation-platform.vercel.app) lives under a personal Vercel account and cannot directly redirect to a project owned by another account.

👉 This lightweight redirect project is the official and recommended Vercel pattern for handling that scenario.
