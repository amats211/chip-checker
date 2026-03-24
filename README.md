# Chip Grade ID

**eMMC / UFS Chip Grade Checker with Philippine Pricing**

A mobile-first web app for identifying eMMC/UFS chip quality grades and current market prices.

## Features
- 📷 **Camera capture** — take a photo directly from your phone
- 🤖 **AI auto-detection** — reads chip model from photo automatically
- ✅ **Grade lookup** — A-, A+, A++, A+++, A++++
- 💰 **PH pricing** — editable prices per grade (₱)
- 🕘 **History** — last 20 checks saved locally
- 📱 **PWA** — installable on Android/iOS home screen

## Grades Covered
| Grade | Tier | Description |
|-------|------|-------------|
| A++++ | A5 | UFS 3.1 — Highest quality |
| A+++ | A4 | UFS 2.1/2.2 — High end |
| A++ | A3 | eMMC 5.1 — Premium |
| A+ | A2 | eMMC 5.1 — Standard |
| A- | A1 | eMMC 4.5 — Older gen |

## Live App
👉 **https://amats211.github.io/chip-checker/**

## Setup

### Option 1: GitHub Pages (recommended)
1. Fork or push this repo to your GitHub account as `chip-checker`
2. Go to **Settings → Pages → Source: GitHub Actions**
3. Push to `main` — auto-deploys via the workflow

### Option 2: Local
Just open `index.html` in any browser.

## Updating Prices
Open the app → tap **PRICES** tab → edit any value → tap **Save Prices**.
Prices are saved locally on your device.

## Tech Stack
- Vanilla HTML/CSS/JS — no frameworks, no dependencies
- Claude AI API for image OCR
- PWA ready (manifest + icons)

---
Built for PH phone repair market
