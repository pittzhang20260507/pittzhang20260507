## Hi, I'm Pitt (Parker)

**AI FDE · AI-Native Infrastructure Engineering**

10+ years of enterprise IT infrastructure — from VMware / AD / Exchange data centers in GLP-regulated pharma and high-security environments, to Linux, cloud, observability and SRE. Today I build multi-agent engineering workflows that turn real business rules into production systems that can be verified and rolled back.

中文：十余年企业基础设施经验，现专注 AI FDE——用多 Agent 协同工程流程，把企业 AI 方案落成可运行、可验证的生产系统。

### Multi-agent workflow · 让多个 AI 按工程规则协作

<p align="center">
  <img src="assets/claude.png" width="96" height="96" alt="Claude" title="Claude">
  &nbsp;&nbsp;&nbsp;
  <img src="assets/codex.png" width="96" height="96" alt="Codex" title="Codex">
  &nbsp;&nbsp;&nbsp;
  <img src="assets/gemini.png" width="96" height="96" alt="Gemini" title="Gemini">
  &nbsp;&nbsp;&nbsp;
  <picture><source media="(prefers-color-scheme: dark)" srcset="assets/grok-dark.png"><img src="assets/grok-light.png" width="96" height="96" alt="Grok" title="Grok"></picture>
  <br>
  <sub>Claude · Codex · Gemini · Grok</sub>
</p>

Plan review first, task breakdown, cross-validation between agents, official-docs lookup and automated gates — each step continues only on logs, tests and a human PASS.

```mermaid
flowchart LR
    A["01 Requirements<br/>& rules"] --> B["02 Architecture<br/>& task cards"]
    B --> C["03 Multi-agent<br/>implementation"]
    C --> D["04 Cross-review<br/>& gates"]
    D --> E["05 Test evidence<br/>& human sign-off"]
```

### Running systems · 运行中的 AI 与基础设施实践

| | System | What it does |
|---|---|---|
| 📚 | **Official-docs knowledge base + MCP** | Curated official sources with cited retrieval and verification, so agents rely less on stale knowledge |
| 🛡️ | **AI hook gate system** | Enforces official-docs lookups and code checks, reducing drift and omissions during automated execution |
| 🌐 | **Multi-node security operations** | 12-node fleet across Asia, Europe and the US: automated access control, linked log-based defense, host-by-host verification, rollback-ready changes |
| ⚙️ | **K3s failover & observability lab** | Multi-ingress failover and monitoring pipeline, turned into reusable deployment and troubleshooting practice |

### Featured project

**[gemini-mcp-docs-agent](https://github.com/pittzhang20260507/gemini-mcp-docs-agent)** — MCP server + agent that answers infra/ops questions only from official upstream docs, with exact source citations. Built on Gemini and Vertex AI Search.

<a href="https://www.youtube.com/watch?v=l67ilza4aGk"><img src="assets/demo-poster.jpg" width="560" alt="gemini-mcp-docs-agent demo video"></a>

More write-ups: [engineering case studies](https://api-cloud.cc/case-studies.html) · [K8s observability](https://api-cloud.cc/k8s-observability.html). Most of my production work lives in private repositories; the case studies describe it.

### Tech I use daily

![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?logo=ubuntu&logoColor=white)
![K3s](https://img.shields.io/badge/K3s-FFC61C?logo=k3s&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?logo=nginx&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?logo=cloudflare&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?logo=googlecloud&logoColor=white)
![DigitalOcean](https://img.shields.io/badge/DigitalOcean-0080FF?logo=digitalocean&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white)
![Vue](https://img.shields.io/badge/Vue-4FC08D?logo=vuedotjs&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus&logoColor=white)
![OpenWrt](https://img.shields.io/badge/OpenWrt-00B5E2?logo=openwrt&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-88171A?logo=wireguard&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)

### Find me

[Blog · api-cloud.cc](https://api-cloud.cc) · [About](https://api-cloud.cc/about.html) · [Contact](https://api-cloud.cc/contact.html)
