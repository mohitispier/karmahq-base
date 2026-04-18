# KarmaHQ Website - Source Code

## Setup Instructions

1. Install dependencies:
   ```
   npm install
   ```

2. Create `.env.local` file:
   ```
   VITE_BASE44_APP_ID=your_app_id
   VITE_BASE44_APP_BASE_URL=your_backend_url
   ```

3. Run locally:
   ```
   npm run dev
   ```

4. Build for production:
   ```
   npm run build
   ```

## Tech Stack
- React 18 + Vite
- Tailwind CSS + shadcn/ui
- Framer Motion
- TanStack React Query
- React Router v6
- Base44 SDK (auth, database, integrations)

## Deploy to GitHub Pages / cPanel
- Run `npm run build`
- Upload the `dist/` folder contents to your hosting
