# Basetune

Compare Intune policies across tenants — securely, offline-capable, and fully under your control.

<p align="center">
  <a href="https://github.com/roweski/basetune">
    <img src="https://img.shields.io/badge/Go%20to-roweski%2Fbasetune-blue?style=for-the-badge&logo=github" alt="Go to basetune">
  </a>
</p>

## What it does

Basetune is a PowerShell-based tool for comparing **Intune Settings Catalog** and **Security Baseline** policies across tenants or exported baselines.

Policies can be loaded online through the Microsoft Graph API or offline from exported JSON files — whichever fits your workflow.

## Comparing policies

Each run compares one source against one target, using any combination of online and offline data sources.

Configure as many tenants and baselines as needed, then choose which two to compare at runtime — either through the UI or via CLI parameters.
