# Gemma Serenity — Living Affirmations

**Internal use only. Not a public project.**

This is Gemma Serenity Gorokhoff's personal bilingual affirmation stack — English and French — deployed as a Progressive Web App (PWA).

## Live URL

🔗 https://affirmations.gemmaserenity.com

## What it is

A single-file static PWA (`index.html`) containing Gemma's full affirmation stack across both languages. Features include:

- English / Français language toggle
- Pinch-to-zoom text resizing (mobile-friendly, reflows without horizontal scroll)
- Installable on iPhone or Android home screen as a native-feeling app
- Works offline via service worker
- No backend, no database, no login required

## How it was built

Created in Claude Chat (claude.ai) under Sascha Gorokhoff's account. All affirmation content, design, and logic were developed and iterated directly in conversation with Claude.

## Repository

**GitHub repo name:** `affirmations`  
**Owner:** gorokhoff.gemma@gmail.com  
Cloudflare Pages is connected directly to this GitHub repository. Every push to the `main` branch triggers an automatic redeploy — no build step, no CLI required.

## How to update content

To add, change, or remove an affirmation: open Claude Chat, share the instruction, and Claude will return an updated `index.html`. Replace the file in this repo and Cloudflare deploys it within ~30 seconds.

## Files

| File | Purpose |
|---|---|
| `index.html` | The entire app |
| `manifest.json` | PWA install manifest |
| `favicon.svg` | Browser tab icon |
| `icon-192.png` | App icon (home screen) |
| `icon-512.png` | App icon (splash screen) |
| `_headers` | Cloudflare Pages security headers |
| `_redirects` | Cloudflare Pages routing rules |

## Owner

**Gemma Serenity Gorokhoff**  
Phoenix, AZ, USA  
gorokhoff.gemma@gmail.com  
gemma@gemmaserenity.com

*All content © Gemma Serenity Gorokhoff. All rights reserved.*