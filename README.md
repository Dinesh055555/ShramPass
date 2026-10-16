# ShramPass

One rider, one ledger: protection that follows India's delivery riders across every app and every state.

A phone-first prototype built for the case competition "Securing India's Platform Workforce". It is one static page (`index.html`) with no build step and no server.

## What is inside

| Screen | What it does |
|---|---|
| Home | One-page dashboard: alerts, ShramPass card and tier progress, this week's earnings, money paid by ShramPass, savings, last 8 weeks, cover, things to do, one-tap help, request tracker, community highlights |
| Money | Earnings from every app added together, why earnings count instead of days, savings switch (APY or NPS), weekly statement |
| Cover | Bronze, Silver and Gold benefits, cash without forms, money received, requests |
| Community | Riders post tips and problems by topic, mark posts helpful, reply and report |
| Me | QR card any app can scan, details and nominee, work passport, consent-based work certificate, language |

The top bar has a Hindi switch, read-aloud and a Demo button that sends payouts, heat or rain alerts and accident records. "How ShramPass works" (beside the app on a laptop, under Me on a phone) covers the problem, stakeholders, theory of change, platforms, board ledger, cost model and roadmap.

Riders, platforms (TiffinGo, BasketNow, ParcelPe) and pilot figures are illustrative. Community posts are saved in each visitor's own browser.

## Deploy on Render

1. Push these files to the root of a GitHub repository.
2. On render.com choose **New > Static Site** and connect the repository.
3. Settings: Branch `main`, Root Directory empty, Build Command `echo "No build step needed"`, Publish Directory `.`
4. Click **Create Static Site**. The link looks like `https://shrampass.onrender.com`.

Or choose **New > Blueprint** and Render reads `render.yaml` for you.

## Run locally

Open `index.html` in any browser.
