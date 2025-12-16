<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />
</div>

# Run and deploy your AI Studio app

This contains everything you need to run your app locally.

View your app in AI Studio: https://ai.studio/apps/drive/1rcKDHocMJydMCBea0k6wPv5UHuv3yOkt

## Run Locally

**Prerequisites:**  Node.js

1. Install dependencies:
   ```bash
   npm install
   ```
2. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key (if applicable)
3. Run the app:
   ```bash
   npm run dev
   ```

## Build for Production

To create a production build:
```bash
npm run build
```
 
## Deployment

This project is configured to automatically deploy to GitHub Pages when pushing to the `main` branch.

1. Go to your repository **Settings** -> **Pages**.
2. Under "Build and deployment", set **Source** to **GitHub Actions**.
3. Push your code to the `main` branch.
4. The deployment workflow will trigger automatically.
