<p align="center">
  <img src="https://raw.githubusercontent.com/Abdalkaderdev/Abdalkaderdev/main/banner.svg" alt="Abdalkader Alhamoud — full-stack and AI engineer, Erbil, Kurdistan Region" width="100%" />
</p>

<p align="center">
  <a href="https://abdalkader.dev"><b>abdalkader.dev</b></a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/abdalkaderdev">LinkedIn</a> &nbsp;·&nbsp;
  <a href="mailto:hello@abdalkader.dev">hello@abdalkader.dev</a> &nbsp;·&nbsp;
  <a href="https://instagram.com/abdalkader.dev">Instagram</a>
</p>

---

Most people building with LLMs call an API. I train the model, serve it, and build the product
around it — the retrieval layer, the backend, the web app, and the mobile app that ships to the
App Store.

Lead engineer at **Why Live Today LLC**, building **[GodFocus](https://platform.godfocus.io)**.
Also with **Mount Seir Tech**, **Disciple One**, **Natuzzi Erbil** and **Real House**, out of Erbil.

<br />

## What I'm building

<table>
<tr><td width="50%" valign="top">

### [GodFocus](https://platform.godfocus.io)
**Bible search + RAG as a service**

The models are mine, not rented. A **QLoRA** fine-tune, preference-aligned with **DPO**, adapters
merged and scored through a dedicated eval harness. Alongside it a custom **cross-encoder reranker**
trained with sentence-transformers and PyTorch, then exported to **ONNX** so it runs inline in the
request path instead of adding a network hop. All over a **pgvector** retrieval layer.

`PyTorch` `QLoRA` `DPO` `ONNX` `pgvector` `Ollama`

</td><td width="50%" valign="top">

### [ParsaLink](https://parsalink.io)
**AI CRM · Mount Seir Tech**

**OpenAI, Anthropic and Google Gemini SDKs running side by side** in one Django 5 + DRF backend,
with an **MCP server** so agents can drive the CRM directly. Infrastructure is code: **Terraform**
across Cloudflare and Hostinger, managing DNS and preview environments. Plus a SvelteKit site and
an Expo mobile CRM with biometric auth.

`Django` `DRF` `PostgreSQL` `Terraform` `MCP` `Expo`

</td></tr>
<tr><td width="50%" valign="top">

### [VIA](https://viaapp.life) + [Disciple One](https://discipleone.life)
**Live on the App Store**

Eight repos — API, web, admin, church dashboard, mobile, SDK, types, docs — **1,114 commits**. The
app is React Native, but the interesting part is native: I wrote the **Live Activity and Dynamic
Island** widget in Swift with ActivityKit and WidgetKit, plus two Expo native modules to bridge it
to JS. Live Activities render as snapshots, so the animation has to be update-driven rather than a
loop — that constraint shapes the whole widget.

`React Native` `Swift` `SwiftUI` `ActivityKit` `WidgetKit` `EAS`

</td><td width="50%" valign="top">

### [SoapBox](https://soapboxsuperapp.com)
**Platform engineering**

SDK, [developer portal](https://builder.soapboxsuperapp.com) and cloud console — the surfaces
*other* engineers build against. Fine-tuned LLMs for product-specific use cases.

`React` `Node.js` `TypeScript` `LLM fine-tuning`

</td></tr>
</table>

<br />

## Shipped and live

| | What it is | For |
|---|---|---|
| **[platform.godfocus.io](https://platform.godfocus.io)** | Bible search + RAG, on models I trained | Why Live Today |
| **[parsalink.io](https://parsalink.io)** | AI CRM — three LLM SDKs + MCP server | Mount Seir Tech |
| **[viaapp.life](https://viaapp.life)** | Devotional app — iOS, Android, web | Disciple One |
| **[discipleone.life](https://discipleone.life)** | Nonprofit platform + church dashboards | Disciple One |
| **[soapboxsuperapp.com](https://soapboxsuperapp.com)** | Faith community platform + SDK | SoapBox |
| **[phoenixerbil.com](https://phoenixerbil.com)** | Multilingual site + Odoo ERP work | Phoenix Tower |
| **[realhouseiq.com](https://realhouseiq.com)** · **[map](https://map.realhouseiq.com)** | Real estate site + property map | Real House |
| **[tunica.vercel.app](https://tunica.vercel.app/en)** | Multilingual brand site | client |
| **[familydentalcard.vip](https://familydentalcard.vip)** | Clinic site | client |
| **[hamiltoniq.com](https://hamiltoniq.com)** | Real estate platform | client |
| **[abdalkader.dev](https://abdalkader.dev)** | Portfolio | me |

<br />

## Stack

**AI/ML** — LLM fine-tuning (QLoRA, DPO) · custom reranker training · RAG architecture · pgvector ·
embeddings and semantic search · ONNX inference optimisation · MCP servers · OpenAI, Anthropic and
Google Gemini SDKs in production

**Languages** — Python · TypeScript · JavaScript · Swift · SQL

**Frontend** — React · Next.js · Svelte/SvelteKit · Astro · GSAP · Three.js · SCSS

**Mobile** — React Native (Expo) · expo-router · SwiftUI · WidgetKit · ActivityKit · EAS Build & Submit ·
in-app purchases · biometric auth · push notifications · offline-first sync

**Backend** — Node.js · Express · Django · DRF · FastAPI · REST · GraphQL · Prisma · WebSockets

**Infra** — Terraform (Cloudflare, Hostinger) · Docker · GitHub Actions · Caddy · Nginx · VPS ·
Cloudflare · AWS (boto3) · Vercel

**Data** — PostgreSQL · pgvector · MongoDB · Redis

<br />

## The numbers

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Abdalkaderdev&show_icons=true&include_all_commits=true&hide_border=true&bg_color=0a0908&title_color=f44e00&icon_color=fa7300&text_color=a8a8a8" alt="GitHub stats" />
  <img height="165" src="https://streak-stats.demolab.com/?user=Abdalkaderdev&hide_border=true&background=0a0908&ring=f44e00&fire=fa7300&currStreakLabel=f44e00&sideLabels=a8a8a8&dates=787878&currStreakNum=f8f8f8&sideNums=f8f8f8&stroke=252525" alt="Streak" />
</p>
<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Abdalkaderdev&layout=compact&langs_count=8&hide_border=true&bg_color=0a0908&title_color=f44e00&text_color=a8a8a8" alt="Top languages" />
</p>

**6,300+** contributions in the last year · **41** repositories with my commits ·
**176** repositories · **6** organisations · **28** repos as an outside collaborator

Heaviest: Disciple One **1,114** · ParsaLink **495** · godfocus **377** · via-mobile **369** ·
Godfocus-api **189** · godfocus-mobile **159**

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Abdalkaderdev/Abdalkaderdev/output/snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Abdalkaderdev/Abdalkaderdev/output/snake-light.svg" />
  <img alt="Contribution graph being eaten by a snake" src="https://raw.githubusercontent.com/Abdalkaderdev/Abdalkaderdev/output/snake-dark.svg" width="100%" />
</picture>

<br />

## Before software

Cell site technician for **MTN Syria** in Aleppo and **Zain Sudan** in Khartoum, 2015–2018,
installing and maintaining telecom infrastructure. I came to software properly in November 2023.
The telecom years are why I think about uptime before features.

<br />

---

<p align="center">
  <a href="https://abdalkader.dev">abdalkader.dev</a> &nbsp;·&nbsp;
  <a href="https://instagram.com/abdalkader.dev">Instagram</a> &nbsp;·&nbsp;
  <a href="https://tiktok.com/@Abdalkader.dev">TikTok</a> &nbsp;·&nbsp;
  <a href="https://buymeacoffee.com/abdalkader.dev">Buy me a coffee</a>
</p>
