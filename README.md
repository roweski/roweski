# Basetune

Compare Intune policies across tenants — securely, offline-capable, and fully under your control.

<p left="center">
  <a href="https://github.com/roweski/basetune">
    <img src="https://img.shields.io/badge/Go%20to-roweski%2Fbasetune-blue?style=for-the-badge&logo=github" alt="Go to basetune">
  </a>
</p>

## What it does

Basetune is a PowerShell-based tool to compare **Intune Settings Catalog** and **Security Baseline** policies across tenants or exported baselines. Common use cases include compliance audits and baseline comparisons.

Policies can be loaded:
- **Online** via Microsoft Graph API
- **Offline** from exported JSON files

Comparison capabilities:
- **Source vs. Target** — Each comparison run compares one source against one target. Source and target can be any combination of online tenants and offline JSON folders.
- **Unlimited tenant configuration** — Configure as many tenants and baselines as you need, then pick which two to compare at runtime (from the UI or via CLI parameters).
