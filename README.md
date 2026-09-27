# GW Residence Unit Calculator

This is a static HTML site ready to deploy on Vercel. The site entry point is `index.html`.

## Deploy with Vercel CLI

1. Install Node.js if it is not already installed.
2. Open a terminal in this folder and run `npx vercel`.
3. Follow the prompts to sign in and create/link the Vercel project. Keep the project root as this folder; no framework, build command, or output directory is required.
4. To publish the production deployment, run `npx vercel --prod`.

No environment variables or build step are needed for this static page.

## Google Sheet access

The calculator reads the sheet directly in the visitor's browser. Keep the sheet published/shared for link access, and verify the selected tab's `gid` in the URL. The sheet ID and its contents are visible to site visitors, so do not use this approach for private data. If the browser blocks the request or the sheet is not publicly readable, the calculator falls back to its sample data.
