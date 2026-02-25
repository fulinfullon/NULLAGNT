# NullAgent

Autonomous trading agents on Base · Zero Trace Execution · x402 Native

## Files

```
nullagent/
├── index.html    ← Main website (landing + deploy wizard + dashboard)
├── docs.html     ← Documentation page
└── README.md
```

## Deploy

Upload both HTML files to any static host:

**Option A — GitHub Pages (free)**
1. Push this repo to GitHub
2. Settings → Pages → Deploy from branch: main
3. Site live at `https://yourusername.github.io/nullagent`

**Option B — Your own domain (GoDaddy + any host)**
1. Upload `index.html` and `docs.html` to your hosting root
2. Point domain DNS to hosting provider

**Option C — Netlify or Vercel (free, instant)**
1. Drag & drop folder at netlify.com or vercel.com
2. Get instant SSL domain

## What works

- ✅ MetaMask connect (real window.ethereum + personal_sign)
- ✅ Base mainnet chain switch (chainId 8453)
- ✅ Deploy wizard — 4 steps with live terminal animation
- ✅ Dashboard — stealth wallet table, trades, vault, privacy panel
- ✅ Live terminal log simulation
- ✅ Generate wallet button adds rows to the table
- ✅ Vault split preview (real-time calculation)
- ✅ Full documentation page with sidebar navigation
- ✅ All external links (Conway, x402, Railgun, Base, GitHub)
- ✅ Sections marked [FILL] for easy completion

## Stack

- Pure HTML + CSS + JS — zero dependencies, zero build step
- Fonts: Unbounded (display) + Azeret Mono (monospace) via Google Fonts
- Chain: Base mainnet (8453)
- Auth: MetaMask personal_sign
