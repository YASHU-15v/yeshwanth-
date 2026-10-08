# Yeshwanth Gowda V – website
3 pages (Home, About & nammaweb, Book a call) + Vercel serverless backend (`api/book.js`).

## Deploy
1. `git init && git add . && git commit -m "Initial site"`, create a GitHub repo, push.
2. In Vercel: Add New Project, import the repo (no build settings needed).
3. Settings > Environment Variables: `GMAIL_USER`, `GMAIL_APP_PASSWORD`, `OWNER_EMAIL` (see `.env.example`).
   Create the app password at myaccount.google.com/apppasswords (2-step verification must be on).
4. Redeploy, then test the booking form.
