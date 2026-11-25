<!-- styled:v2 -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1d1726,50:167dfe,100:9533fa&height=180&section=header&text=LeadLens%3A%20Legal%20Marketing%20ROI%20Dashboard&fontSize=31&fontColor=ffffff&fontAlignY=36&desc=Case%20study%20%E2%80%A2%20Legal%20%E2%80%A2%20Marketing%20analytics%20dashboard&descAlignY=58&descSize=16&animation=fadeIn" width="100%" alt="LeadLens: Legal Marketing ROI Dashboard" />

**A marketing dashboard for a law firm that joins ad data with intake and case data to show cost per lead and cost per signed case for every channel.**

<p>
  <img src="https://img.shields.io/badge/Legal-167dfe?style=flat-square" alt="Legal" />
  <img src="https://img.shields.io/badge/Marketing%20analytics%20dashboard-9533fa?style=flat-square" alt="Marketing analytics dashboard" />
  <img src="https://img.shields.io/badge/React-231f20?style=flat-square" alt="React" />
  <img src="https://img.shields.io/badge/Python-231f20?style=flat-square" alt="Python" />
  <img src="https://img.shields.io/badge/Google%20Ads%20API-231f20?style=flat-square" alt="Google Ads API" />
  <img src="https://img.shields.io/badge/n8n-231f20?style=flat-square" alt="n8n" />
  <img src="https://img.shields.io/badge/Google%20Sheets-231f20?style=flat-square" alt="Google Sheets" />
  <img src="https://img.shields.io/badge/Looker-231f20?style=flat-square" alt="Looker" />
</p>

<p>
  <a href="#overview">Overview</a> ·
  <a href="#key-features">Key features</a> ·
  <a href="#results">Results</a> ·
  <a href="#tech-stack">Tech stack</a>
</p>

</div>

---

![LeadLens legal marketing ROI dashboard: ad spend, leads, cost per lead, signed cases, lead funnel and performance by channel.](assets/cover.webp)

## Overview

The firm could see ad spend and clicks, but not which channels produced signed cases. Lexvaxa built LeadLens, a custom dashboard that joins ad platform data with intake and case data. Partners see spend, leads, cost per lead and cost per signed case, a lead funnel from first contact to signed, weekly leads and signed cases, signed cases by practice area and a performance table for every channel. Screens shown use sample data, so no client records are exposed.

## The challenge

Marketing reports stopped at clicks and leads, so budget decisions could not be tied to the cases the firm actually signed.

## The solution

n8n pipelines pull ad spend from the ad platforms and match it with intake and case records, feeding a React dashboard and a channel ROI table.

## Key features

- Ad spend, leads, cost per lead and cost per signed case
- Lead funnel from lead to signed case
- Weekly leads and signed cases
- Signed cases by practice area
- Spend and ROI by channel
- Campaign performance table

## Results

- Budget decisions are based on signed cases, not just clicks

## Tech stack

![React](https://img.shields.io/badge/React-1d1726?style=for-the-badge) ![Python](https://img.shields.io/badge/Python-1d1726?style=for-the-badge) ![Google Ads API](https://img.shields.io/badge/Google%20Ads%20API-1d1726?style=for-the-badge) ![n8n](https://img.shields.io/badge/n8n-1d1726?style=for-the-badge) ![Google Sheets](https://img.shields.io/badge/Google%20Sheets-1d1726?style=for-the-badge) ![Looker](https://img.shields.io/badge/Looker-1d1726?style=for-the-badge) ![CRM data](https://img.shields.io/badge/CRM%20data-1d1726?style=for-the-badge)

## Demo

A working version of the dashboard UI with **sample data** is in [`demo/index.html`](demo/index.html). Download it and open it in a browser; it has no build step.

## Privacy

Client names and records are confidential. Every screen in this repository uses sample data, and source code that belongs to the client is not published.

## Links

- Case study on Lexvaxa: https://lexvaxa.com/work/legal-marketing-roi-dashboard

---

<div align="center">

**Built by [Ch Muhammad Samiullah](https://github.com/samiullah156-creator)** · AI Automation Engineer and Full-Stack Developer at [Lexvaxa](https://lexvaxa.com)

<a href="https://github.com/samiullah156-creator"><img src="https://img.shields.io/badge/More%20projects-181717?style=for-the-badge&logo=github&logoColor=white" alt="More projects" /></a>
<a href="https://lexvaxa.com/contact"><img src="https://img.shields.io/badge/Work%20with%20me-167dfe?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Work with me" /></a>
<a href="https://www.linkedin.com/in/sami-lexvaxa/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>

<sub>⭐ Star this repo if you found it useful</sub>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:9533fa,50:167dfe,100:1d1726&height=110&section=footer" width="100%" alt="" />
