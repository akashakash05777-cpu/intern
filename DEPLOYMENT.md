# GitHub Pages Deployment Guide

## Quick Setup

1. **Push your code to GitHub**:
   ```bash
   git add .
   git commit -m "Configure for GitHub Pages deployment"
   git push origin main
   ```

2. **Enable GitHub Pages**:
   - Go to your GitHub repository
   - Click on "Settings" tab
   - Scroll down to "Pages" section
   - Under "Source", select "GitHub Actions"
   - The workflow will automatically deploy your app

3. **Access your app**:
   - Your app will be available at: `https://yourusername.github.io/repositoryname/`
   - Users will be automatically redirected to the login page

## What's Configured

- ✅ Static export enabled for GitHub Pages
- ✅ Client-side redirect from root to login page
- ✅ GitHub Actions workflow for automatic deployment
- ✅ Fallback index.html for immediate redirect
- ✅ .nojekyll file to prevent Jekyll processing

## Files Added/Modified

- `next.config.ts` - Configured for static export
- `src/app/page.tsx` - Client-side redirect to login
- `.github/workflows/deploy.yml` - GitHub Actions deployment
- `public/.nojekyll` - Prevent Jekyll processing
- `public/index.html` - Fallback redirect page

## Troubleshooting

If the deployment fails:
1. Check the Actions tab in your GitHub repository
2. Ensure your repository is public or you have GitHub Pro
3. Make sure the main branch is selected for deployment
