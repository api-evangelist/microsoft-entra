# Programmatic API Onboarding — Microsoft Entra ID

A single-file, zero-dependency Node.js (18+) CLI that reproduces SoundCloud's
`sc-api-auth.mjs` pattern for Microsoft Entra ID: register an application / obtain credentials
programmatically instead of clicking through a dashboard, so agents and developers
can onboard at the command line.

- Script: [`microsoft-entra-api-auth.mjs`](microsoft-entra-api-auth.mjs)
- Run `node microsoft-entra-api-auth.mjs --help` for usage and the required environment variables.
- Story / rationale: https://apievangelist.com/2026/07/28/microsoft-entra-programmatic-onboarding/

Part of the API Evangelist "Programmatic API Onboarding for the Agentic Moment" series.
