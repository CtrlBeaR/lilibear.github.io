# LiliBeaR Website

One-page React/Vite website for LiliBeaR and PaymentManager.

## Run Locally

Install Node.js first, then run:

```powershell
npm install
npm run dev:api
npm run dev
```

## Build

```powershell
npm run build
```

## Notes

- The site is built from the roadmap in `Roadmaps/Website_Roadmap.md`.
- Product screenshots are loaded from `Assets/Screenshots`.
- The installer link uses `Downloads/PaymentManager-Setup.exe`.
- API routes live in `backend/server.js`.
- Submissions are stored in `backend/data/submissions.json`.
- Copy `.env.example` to `.env` and fill in your SMTP settings to enable email delivery.
