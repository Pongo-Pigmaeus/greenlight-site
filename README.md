# Greenlight Vercel Site

Static support and privacy pages for App Store submission.

## Before Deploying

Replace `REPLACE_WITH_SUPPORT_EMAIL` in:

- `support.html`
- `privacy.html`

Use a real email address that App Review and users can contact.

## Deploy on Vercel

1. Create a new Vercel project.
2. Use this folder as the project root: `AppStoreSubmission/VercelSite`.
3. Framework preset: `Other`.
4. Build command: leave empty.
5. Output directory: leave empty.

After deploy, use these URLs in App Store Connect:

- Support URL: `https://your-vercel-project.vercel.app/support`
- Privacy Policy URL: `https://your-vercel-project.vercel.app/privacy`
- Marketing URL: `https://your-vercel-project.vercel.app`
