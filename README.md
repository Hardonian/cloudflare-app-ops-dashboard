# cloudflare-app-ops-dashboard

Operational status dashboard for Cloudflare-native projects.  
Live at https://cloudflare-app-ops-dashboard.pages.dev

## What It Shows

A single-page status board tracking deployed Worker/Pages apps across the Hardonian portfolio. Each app is listed with its actual stage (scaffold, experimental, phase 2, or deployed), working features, and known gaps.

## Apps Tracked

| App | Stage | Worker | Frontend | Landing |
|-----|-------|--------|----------|---------|
| Webhook Witness | Phase 2 / Deployed | ✅ | ✅ | ✅ |
| API Changelog Radar | Scaffold / Deployed | ✅* | ✅* | ✅* |
| tfstate Drift Inspector | Experimental / Deployed | ✅* | ✅* | ✅* |
| cloudflare-launch-portfolio | Deployed | — | ✅ | — |

*Worker and pages deployed but backed by scaffold/experimental code. See each repo's README for actual capabilities.

## Repos

- [webhook-witness](https://github.com/Hardonian/webhook-witness)
- [api-changelog-radar](https://github.com/Hardonian/api-changelog-radar)
- [tfstate-drift-inspector](https://github.com/Hardonian/tfstate-drift-inspector)

## Stack

- Cloudflare Pages (static HTML/CSS)
- Deployed via GitHub Actions to Pages
