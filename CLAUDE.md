# emoa2l.github.io - GitHub Pages Site

## Project Overview
This is a GitHub Pages site that serves as an app listing page for emoa2l's projects. The site is hosted at https://emoa2l.github.io

## Purpose
- List apps and tools created by emoa2l
- Provide links to GitHub repositories
- Include sponsor links for each app

## Design Philosophy
- Clean, minimal GitHub-inspired design
- No gradients or flashy styling
- Straightforward list-based layout
- Mobile responsive

## Current Apps Listed
1. **SimpleStripeApi**
   - Demo: https://emoa2l.github.io/SimpleStripeApi/
   - GitHub: https://github.com/emoa2l/SimpleStripeApi
   - Description: A simple API wrapper for Stripe payment processing

## How to Add New Apps
Edit `index.html` and add a new `<li class="app-item">` entry to the app list (around line 155):

```html
<li class="app-item">
    <div class="app-header">
        <a href="URL_TO_APP" class="app-name">App Name</a>
        <span class="sponsor-badge">Sponsor</span>
    </div>
    <p class="app-description">Brief description of what the app does.</p>
    <div class="app-links">
        <a href="URL_TO_DEMO" class="app-link">Demo →</a>
        <a href="URL_TO_GITHUB" class="app-link">GitHub →</a>
        <a href="URL_TO_SPONSOR" class="app-link">Sponsor →</a>
    </div>
</li>
```

## Deployment
Changes pushed to the `main` branch automatically deploy to GitHub Pages within 1-2 minutes.

## File Structure
- `index.html` - Main page with inline CSS
- `CLAUDE.md` - This file (context for Claude sessions)

## Notes
- This is a static site with no build process
- All styling is contained in `index.html`
- No external dependencies
