# Agentic Advisors — Website

## What's in this folder
- `index.html` — the full site (everything is in this one file)
- `assets/` — your logo, icon, and headshots

## Before you deploy: two tiny things to swap

Open `index.html` in any text editor and find/replace these:

1. **Your Calendly link.** Search for `YOUR-CALENDLY-URL` and replace with your real Calendly event URL. If your event is at `calendly.com/benwalch/discovery-call`, the full line should become:
   ```
   data-url="https://calendly.com/benwalch/discovery-call?hide_gdpr_banner=1"
   ```

2. **Your Loom video (optional, when ready).** Search for `onclick="alert(` in the hero section. Replace that whole `<div class="hero-video">` block with a Loom embed — Loom gives you an iframe snippet when you click Share → Embed.

## How to deploy (free, 5 minutes)

**Easiest path: Netlify Drop**

1. Go to https://app.netlify.com/drop
2. Drag this entire `agentic-advisors` folder onto the page
3. You get a live URL immediately (something like `lucky-cat-123.netlify.app`)
4. In Netlify settings → Domain management, connect your real domain (agenticadvisors.ca or whatever you buy)
5. Netlify walks you through the DNS settings to copy over to your domain registrar

**Done.** Total cost: $0/month for hosting. You just pay for the domain (~$15/year).

## To update the site later
1. Edit `index.html` locally (or ask me)
2. Go back to Netlify Drop, drag the folder in again
3. Your live site updates in seconds

## File structure
```
agentic-advisors/
├── index.html
└── assets/
    ├── logo.svg
    ├── icon.png
    ├── ben-fullbody.jpg
    └── ben-headshot.png
```
