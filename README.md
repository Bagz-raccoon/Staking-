# $BAGZ Staking Page (Static)

This zip includes TWO drop-in options so the page renders as an actual webpage (not plain text):

## Option A — Pure Static Site (Vercel "Other"/No Build)
Use: `static-root/`
- Put the contents of `static-root` in your repo root:
  - `index.html`
  - `assets/styles.css`
- In Vercel project settings:
  - Framework Preset: **Other**
  - Build Command: *(leave empty)*
  - Output Directory: *(leave empty)*

## Option B — If your repo is Next.js / React (recommended)
Use: `nextjs-public/`
- Copy `nextjs-public/public/staking/` into your repo at:
  - `public/staking/index.html`
  - `public/staking/assets/styles.css`
- Then your staking page is available at:
  - `/staking/`

## Official staking link
https://app.streamflow.finance/staking/solana/mainnet/9VyNXKPziqdra4XKyvfsdH37DwPLycwybUMyXsCLC9jw
