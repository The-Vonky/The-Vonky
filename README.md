<div align="center">

# Deywid Braga · `The-Vonky`

### Systems Analyst · Full-stack Developer · Business Automation

**I turn operational complexity, spreadsheets and repetitive workflows into reliable software.**

[![GitHub](https://img.shields.io/badge/GitHub-The--Vonky-181717?style=flat-square&logo=github)](https://github.com/The-Vonky)
[![Location](https://img.shields.io/badge/Patos_de_Minas-MG%2C_Brazil-00A86B?style=flat-square)](#)
[![Focus](https://img.shields.io/badge/Focus-Business_Software_%26_Automation-3178C6?style=flat-square)](#)
[![Email](https://img.shields.io/badge/Email-deywidbraga.dev%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:deywidbraga.dev@gmail.com)

</div>

---

## About me

I'm a **Systems Analyst and Full-stack Developer** focused on software that solves real operational problems.

A large part of my work starts with processes that depend on spreadsheets, repetitive validation, manual controls or fragmented business rules.

I work across the full lifecycle:

```text
Business problem
      ↓
Process discovery
      ↓
Business rules
      ↓
Data modeling
      ↓
Application / API
      ↓
Tests & validation
      ↓
Deployment
      ↓
Real-world feedback
      ↓
Improvement
```

My main interests are:

- business software;
- process automation;
- spreadsheet-to-software migration;
- data reconciliation and traceability;
- internal tools;
- local-first applications;
- reliable deployment;
- testing and CI;
- data integrity and safe migrations.

I currently study **Information Systems at UNIPAM** in Patos de Minas, Minas Gerais, Brazil.

---

# Featured Engineering

## `01` Planejado × Realizado

**Operational reconciliation system for comparing planned and actual business data imported from spreadsheets.**

The system replaces part of a spreadsheet-driven workflow with structured validation, financial reconciliation, historical records and safer confirmation flows.

```text
Excel import
     ↓
Structural validation
     ↓
Business-rule validation
     ↓
Financial reconciliation
     ↓
Immutable confirmation
     ↓
History / comparison / export
     ↓
Backup / restore / migration
```

### Engineering concerns

- preservation of original imported files;
- rejection of invalid or unsafe inputs;
- business-rule validation;
- financial calculations using decimal-safe logic;
- immutable historical snapshots;
- traceable corrections;
- versioned database migrations;
- backup and restore protection;
- data continuity across application updates;
- automated tests and CI.

**Stack**

`Python` · `FastAPI` · `React` · `TypeScript` · `SQLite` · `Excel / OOXML` · `Pytest` · `Vitest` · `GitHub Actions`

---

## `02` Contract Management System

**Internal software for managing contracts, deadlines, reports, dashboards and operational access.**

The project has been explored in both **desktop/local** and **intranet** architectures.

### Areas involved

- contract lifecycle management;
- alerts and expiration monitoring;
- dashboards and KPIs;
- reporting;
- role-oriented operation;
- backup and restore;
- local-network deployment;
- TLS/certificate configuration;
- database persistence;
- startup and deployment automation.

**Stack**

`React` · `TypeScript` · `Tauri` · `Rust` · `PostgreSQL` · `Docker` · `PowerShell`

---

## `03` ISO Proposal Registry

**Migration of an operational Excel workflow into a structured web application.**

### Features

- spreadsheet import;
- customer and proposal management;
- search and filtering;
- document organization;
- historical records;
- reporting;
- structured persistence.

**Stack**

`FastAPI` · `React` · `Vite` · `TypeScript` · `SQLite`

---

## `04` Operational Data & Dashboards

I also build analytical tools around operational datasets.

Recent work includes:

- ABC / Pareto analysis;
- satisfaction survey consolidation;
- cost and consumption analysis;
- multi-spreadsheet consolidation;
- automated reports;
- transformation of raw operational data into actionable views.

---

# Public Projects

<table>
<tr>
<td width="33%" valign="top">

### 🧬 [OmniFit](https://github.com/The-Vonky/OmniFit)

Mobile health and fitness application focused on workouts, diet, physical progress and user experience.

**React Native · Expo · TypeScript · Supabase**

</td>
<td width="33%" valign="top">

### 👨‍👩‍👧 [MisParent](https://github.com/The-Vonky/MisParent)

Academic mobile project for parental activity management and monitoring.

**React Native · Expo · Firebase**

</td>
<td width="33%" valign="top">

### 🐄 [Fazenda Magalhães](https://github.com/The-Vonky/Fazenda-Magalhaes)

Academic system designed around a real dairy-farm management scenario.

**Web · Authentication · Dashboard · Management**

</td>
</tr>
</table>

> Most of my recent professional systems are private because they handle internal company processes, operational data and business rules.

---

# Engineering Principles

The more responsibility a system has, the less I treat software as **just code**.

```text
┌──────────────────────────────────────────────┐
│              ENGINEERING PRINCIPLES          │
├──────────────────────────────────────────────┤
│ Understand the process before coding         │
│ Preserve original data                       │
│ Prefer versioning over destructive overwrite │
│ Test business rules                          │
│ Make failures visible                        │
│ Back up before destructive changes           │
│ Keep migrations auditable                    │
│ Use PRs instead of pushing directly to main  │
│ Keep secrets and real data out of Git        │
│ Design for the actual end user               │
└──────────────────────────────────────────────┘
```

### Data integrity

If software handles company data, losing or silently altering that data is not acceptable.

### Traceability

Important changes should leave a record. A new version should not silently erase the previous state.

### Safe changes

Imports, schema migrations, restores and application updates deserve explicit validation and recovery strategies.

### Tests

Tests are part of implementation, especially around business rules, calculations and failure paths.

### CI

A working interface is not enough. Automated verification should prevent broken code from being accepted.

### User operation

Architecture only matters when the people using the system can understand what happened and what they should do next.

---

# Tech Stack

### Main languages

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![C%23](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)

</div>

### Web & APIs

<div align="center">

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

</div>

### Data, desktop, mobile & infrastructure

<div align="center">

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-24C8DB?style=for-the-badge&logo=tauri&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)

</div>

### Engineering workflow

<div align="center">

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![Ruff](https://img.shields.io/badge/Ruff-D7FF64?style=for-the-badge&logo=ruff&logoColor=black)
![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)

</div>

`REST APIs` · `JSON` · `Excel / OOXML` · `WSL2` · `Windows deployment` · `local networks` · `TLS` · `Git flow` · `PR review` · `data migration`

---

# What I Optimize For

```text
Correct business rules
        +
Reliable data
        +
Understandable UX
        +
Safe deployment
        +
Maintainable code
        =
Software people can actually depend on
```

I don't want to automate a process simply because it *can* be automated.

I want to understand:

- why the process exists;
- which rules actually matter;
- what can go wrong;
- which data must never be lost;
- how changes should be tracked;
- and what makes the user's work safer or easier.

Then I build around that.

---

# GitHub Activity

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=The-Vonky&show_icons=true&theme=github_dark&hide_border=true&rank_icon=github" alt="Deywid Braga GitHub stats" />

<img height="170" src="https://streak-stats.demolab.com?user=The-Vonky&theme=github-dark-blue&hide_border=true&short_numbers=true" alt="Deywid Braga GitHub streak" />

</div>

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=The-Vonky&layout=compact&theme=github_dark&hide_border=true&langs_count=8" alt="Most used public languages" />

</div>

> Public GitHub statistics reflect only public activity and do not represent the full scope of private professional repositories.

---

# Current Direction

I'm currently strengthening the bridge between **software engineering and real business operations**.

My focus is on:

- stronger architecture;
- safer data flows;
- better automated testing;
- reliable local and intranet deployments;
- cleaner update and migration strategies;
- reusable internal tooling;
- open-source projects that demonstrate production-oriented engineering.

---

<div align="center">

## Build software that survives real use.

```js
while (true) {
  understandProblem();
  modelBusinessRules();
  build();
  test();
  ship();
  observe();
  improve();
}
```

**From spreadsheets to software. From manual work to reliable systems.**

[![GitHub](https://img.shields.io/badge/GitHub-The--Vonky-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/The-Vonky)
[![Email](https://img.shields.io/badge/Email-deywidbraga.dev%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:deywidbraga.dev@gmail.com)

![Profile Views](https://komarev.com/ghpvc/?username=The-Vonky&style=flat-square&label=VISITORS)

</div>
