# Integrate Labs App Store

Private Umbrel community app store for Integrate Labs client boxes.

White-labeled AI agents + a curated toolkit for real-estate teams. Apps here are
version-pinned and only update when Integrate Labs publishes a new version, so
client branding and configuration are never clobbered by upstream releases.

## Apps
- **RYSE AI** — white-labeled Hermes agent (RYSE Platinum Partners)
- **DocuSeal** — self-hosted e-signatures (contracts, listing agreements, disclosures)
- **NocoDB** — no-code database/CRM (leads, deals, transaction pipelines)
- **Metabase** — dashboards & reporting (deal flow, marketing KPIs)

## Add this store to a box
Umbrel dashboard → App Store → ··· → Community App Stores → add:
`https://github.com/fordboy135/integrate-labs-app-store`

## Updating an app
Bump `version` in the app's `umbrel-app.yml` and the pinned image digest in
`docker-compose.yml`, commit, push. Boxes show the update in their dashboard.
