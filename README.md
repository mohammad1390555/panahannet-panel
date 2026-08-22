# PANAHANNET Panel

Cloudflare Worker-based VPN management panel (v3.5.25).

## Features
- 🌐 Web dashboard with subscription management
- 🤖 Telegram bot integration
- 💳 Wallet, shop & agency system
- 📊 Usage tracking & stats (D1 database)
- 🔐 Master key + API key authentication
- 🛡️ Rate limiting (200 req/min per IP)

## Deploy
```bash
npx wrangler deploy
```

Requires a D1 database bound as `IOT_DB` (see `wrangler.toml`).

## Update
The panel checks this repo's `version` file and `_worker.js` for updates via the built-in update API.
