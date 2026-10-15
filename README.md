# QPU — The Quantum Computing Launchpad

Static site. No build step.

## Deploy on Vercel
1. Push these files to the root of a GitHub repo.
2. In Vercel: Add New > Project > import the repo.
3. Framework preset: **Other**. Leave build command and output directory empty.
4. Deploy.

## Files
- `index.html` - the whole site (HTML, CSS, JS)
- `logo.webp`, `logo-icon.png`, `qpu-screen.png`, `logo-full.png` - logo assets
- `vercel.json` - clean URLs

## Wallet
Uses `@solana/web3.js` (CDN) with Phantom, Solflare and Backpack. SOL balance uses the public
mainnet RPC (`RPC` constant in `index.html`); swap in a Helius/QuickNode URL for production.
