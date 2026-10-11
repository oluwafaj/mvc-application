# 🚀 ASP.NET Core MVC CI/CD Pipeline Setup

This repository contains an **ASP.NET Core MVC** application (`gitmvc-app`) integrated with dual **Continuous Integration (CI)** automation using both **GitHub Actions** and **Azure DevOps Pipelines**.

---

## 🛠️ Architecture & Tech Stack

* **Framework:** .NET 8.0 (ASP.NET Core MVC)
* **Language:** C#
* **Source Control:** Git / GitHub (`development` branch workflow)
* **CI/CD Platforms:** GitHub Actions & Azure DevOps Pipelines
* **OS Environment:** macOS (Apple Silicon development environment)

---

## 📁 Repository Structure

```text
mvc-application/                     <-- Repository Root
├── .github/
│   └── workflows/
│       └── dotnet-ci-development.yml <-- GitHub Actions Workflow
├── gitmvc-app/                      <-- ASP.NET Core MVC Application
│   ├── Controllers/
│   ├── Views/
│   ├── Program.cs
│   └── gitmvc-app.csproj
├── azure-pipelines.yml              <-- Azure DevOps Pipeline Configuration
└── README.md
