---
title: "New Trusted Publishing enhances security on NuGet.org"
url: "https://devblogs.microsoft.com/dotnet/enhanced-security-is-here-with-the-new-trust-publishing-on-nuget-org/"
date: "2025-09-22"
author: "Evgeny Tvorun, Sean"
feed_url: "https://devblogs.microsoft.com/dotnet/category/nuget/feed/"
---
We’re excited to announce Trusted Publishing on nuget.org — a simpler, safer way to publish NuGet packages from GitHub Actions. Rather than relying on long‑lived API keys, your workflow can use a short‑lived GitHub OIDC token to request a temporary, single‑use NuGet API key. These keys expire quickly (≈ 1 hour), eliminating long‑lived secrets that need to be stored, rotated,
