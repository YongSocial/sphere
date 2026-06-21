# Yong Social — Company Dashboard

> **Finance · Crypto · Wealth Building**

A public-facing dashboard for [Yong Social](https://www.yongsocial.com/) that lets the community track company growth in real time, engage with live polls, and connect with the brand.

---

## Features

- **Growth Analytics** — Live website traffic (24h hourly chart), total social followers across all platforms, and company net worth (cash + crypto).
- **Crypto Holdings** — Real-time asset values powered by CoinGecko, refreshed every 60 seconds.
- **Latest Content** — Auto-pulls the most recent article from yongsocial.com via RSS.
- **Yong Pool** — Community voting on live polls. One vote per user. Results reveal after voting or when the poll ends. Countdown timers for active polls.
- **Profile** — Personalized user view via Telegram Web App authentication.

---

## Tech Stack

| Layer | Technology |
|---|---|
| UI | HTML5, Tailwind CSS (CDN), Chart.js |
| Auth | Telegram Web App SDK |
| Database | Firebase Firestore (polls + voting) |
| Crypto Data | CoinGecko API |
| Content | RSS feed (yongsocial.com) |

---

## Hosting

This is a static single-file app (`index.html`) — deployable directly via **GitHub Pages**.

1. Push `index.html` to your repo's `main` branch.
2. Go to **Settings → Pages → Source → main / root**.
3. Your dashboard will be live at `https://<your-username>.github.io/<repo-name>/`.

---

## License

© 2026 Yong Social. All rights reserved. See [LICENSE](./LICENSE).
