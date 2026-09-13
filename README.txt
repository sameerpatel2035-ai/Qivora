QIVORA V4 — REAL SHARED ADMIN
1. Create a Supabase project.
2. Create the owner email/password in Authentication > Users.
3. In supabase.sql replace OWNER_EMAIL with that exact email and run it in SQL Editor.
4. Put your Supabase Project URL, Publishable key and OWNER_EMAIL into index.html.
5. Upload index.html to the Qivora GitHub repository. GitHub Pages will redeploy.
6. Never put a Supabase service_role/secret key in browser code.

This version uses Supabase Auth + Postgres + Storage. Public visitors read products; only the configured owner can add/delete products.
