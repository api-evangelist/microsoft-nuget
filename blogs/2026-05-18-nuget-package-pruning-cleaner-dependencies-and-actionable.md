---
title: "NuGet Package Pruning: Cleaner Dependencies and Actionable Vulnerability Reports"
url: "https://devblogs.microsoft.com/dotnet/nuget-package-pruning-in-dotnet-10/"
date: "2026-05-18"
author: "Nikolche Kolev"
feed_url: "https://devblogs.microsoft.com/dotnet/category/nuget/feed/"
---
If you’ve run NuGet Audit or a vulnerability scanner on a .NET project, you’ve likely seen warnings for transitive packages you never explicitly installed. In many cases, those packages — such as System.Text.Json or System.Text.Encodings.Web — are already provided at a newer version by the .NET Runtime Libraries, so the package vulnerability warning is a false positive. In .NET 10,
