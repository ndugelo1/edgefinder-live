# EdgeFinder LIVE - Free API Version (Option A)

Live macro & sentiment scanner clone of A1 Trading's EdgeFinder.
- No API keys needed
- Data: Frankfurter (ECB), CoinGecko, CFTC Socrata
- Auto-refreshes every 60s
- Scoring: Trend + COT + Retail + Econ + Rates + Seasonal = Total Score

## Live Data Sources
- Forex: https://api.frankfurter.app/latest?from=EUR
- Metals: https://api.coingecko.com/api/v3/simple/price?ids=pax-gold
- COT: https://publicreporting.cftc.gov/resource/6dca-aqww.json

## Deploy to Vercel (30 sec)
1. Push this repo to GitHub
2. Import in Vercel - it auto-detects as static site
3. Deploy

## Local Dev
Just open index.html, or `npx serve .`

Built for Ndugelo - Roodepoort, SA
