# BidCalc — Rough Estimate (Free) · PWA

A lightweight, client-side web app that helps quickly build **rough construction estimates** (Canada-oriented).  
No backend. Works offline. Installable to phones as a **Progressive Web App**.

> ⚠️ Budgetary estimate only — not a formal quote. Rates are placeholders; adjust under **Settings**.

---

## Demo
- Live: **https://vladk73864.github.io/bidcalc-rough/**
- Works best over HTTPS (required for PWA/service worker).

## Features
- Job builder: **Drywall, Framing, Insulation, Taping, ACT Ceilings, Extras**, plus **Custom item**.
- Editable **unit rates**, openings adders, **regional multiplier**, optional **GST/PST**.
- **CSV export**, **Print / Save as PDF**, and **Share link** (encodes state in the URL).
- **Local draft save** (localStorage).
- **PWA**: Add to Home Screen (Android/iOS), offline cache via Service Worker.

## Quick start (local)
> Service workers require HTTPS or localhost.
```bash
# Option A: Python static server
python -m http.server 8080

# Option B: Node serve
npx serve -p 8080
