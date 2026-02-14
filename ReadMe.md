# Paid Advertising Suite — Claude Cowork Plugin

**13 AI-powered skills + 7 slash commands** for managing Google Ads, Meta Ads & LinkedIn Ads campaigns — all inside Claude Cowork.

Built by [@RananjayRaj](https://youtube.com/@RananjayRaj) | [LinkedIn](https://linkedin.com/in/rananjayraj/) | [Newsletter](https://theaidrivenmarketer.beehiiv.com/)

<!-- ![Plugin Demo](assets/demo.gif) -->
<!-- Add a demo GIF/screenshot here later -->

---

## What Is This?

A free Claude Cowork plugin that turns Claude into your **paid advertising co-pilot**. Upload your campaign data (CSV/Excel) or connect live APIs — and get instant audits, audience strategies, creative briefs, and optimization recommendations.

No code. No dashboards. Just talk to Claude.

---

## Quick Install

1. Download this repo as ZIP → [Download ZIP](../../archive/refs/heads/main.zip)
2. Open **Claude Desktop** → go to **Cowork**
3. Click **Plugins** (bottom-left) → **Upload Plugin**
4. Select the downloaded ZIP
5. Done! Try `/audit` to run your first campaign audit

> **Requirements:** Claude Pro, Max, Team, or Enterprise subscription + macOS Desktop App with Cowork enabled.

---

## 13 Skills

| # | Skill | What It Does |
|---|-------|--------------|
| 1 | **Ad Performance Diagnostic** | Full campaign analysis with benchmarks, root cause diagnosis & prioritized fixes |
| 2 | **Google Ads Copy Generator** | Policy-compliant headlines, descriptions & extensions with character optimization |
| 3 | **Negative Keyword Miner** | Extract negatives from search term reports with savings estimates |
| 4 | **Meta Ads Creative Brief** | Designer-ready briefs with audience insights, visual direction & format specs |
| 5 | **Creative Testing Framework** | A/B test matrices with hypotheses, sample sizes & success criteria |
| 6 | **Creative Testing Insights Reporter** | Translate test results into actionable design principles |
| 7 | **Ad Creative Performance Predictor** | Score creative concepts (0-100) before you spend a single dollar |
| 8 | **Performance Max Auditor** | Google PMax campaign audit for wastage & missed opportunities |
| 9 | **Search Terms Analyzer** | Identify high-intent winners, wasted spend & new keyword opportunities |
| 10 | **Meta Ads Andromeda Auditor** | Deep Meta audit using Andromeda delivery system insights |
| 11 | **Meta Ads Audience Builder** | Build prospecting, lookalike & retargeting audiences for Meta |
| 12 | **LinkedIn Ads Audience Builder** | B2B audience segments with ABM, title stacking & matched audiences |
| 13 | **Competitive Ads Extractor** | Extract & analyze competitor ads from ad libraries |

---

## 7 Slash Commands

| Command | What It Does |
|---------|-------------|
| `/audit` | Run a full campaign audit (Google, Meta, LinkedIn, or PMax) |
| `/optimize` | Get quick-fire optimization recommendations from campaign data |
| `/creative` | Generate ad copy, creative briefs, test plans, or predict performance |
| `/audience` | Build or refine audiences for Meta or LinkedIn |
| `/spy` | Extract and analyze competitor advertising strategies |
| `/search-terms` | Analyze search term reports and mine negative keywords |
| `/predict` | Score creative concepts before they go live |

---

## Example Workflows

**Campaign Audit**
```
/audit → Select "Google Ads" → Upload 30-day CSV → Get full audit report
```

**Competitive Intelligence**
```
/spy → Enter competitor "HubSpot" → Get messaging themes, creative patterns & gaps
```

**Audience Building**
```
/audience → Select "LinkedIn" → Describe your ICP → Get segmented audiences with overlap management
```

**Full Creative Pipeline**
```
/spy → Find competitor gaps
  → /creative → Write ad copy based on gaps
    → /predict → Score concepts before launch
      → /creative → Set up A/B test plan
        → /creative → Analyze results → Get design principles
```

---

## Optional Connectors (MCPs)

For live data access, connect these optional integrations inside Cowork:

- **Google Ads** — Pull campaign data directly
- **Meta Ads** — Access campaign metrics and Ad Library
- **Google Sheets** — Export reports and audit results

> These are optional. The plugin works fully with uploaded CSV/Excel files.

---

## Plugin Structure

```
paid-advertising-suite/
├── .claude-plugin/plugin.json    # Plugin manifest
├── .mcp.json                     # Optional MCP connector configs
├── README.md                     # This file
├── commands/                     # 7 slash commands
│   ├── audit.md
│   ├── optimize.md
│   ├── creative.md
│   ├── audience.md
│   ├── spy.md
│   ├── search-terms.md
│   └── predict.md
└── skills/                       # 13 skill modules
    ├── ad-performance-diagnostic/
    ├── google-ads-copy-generator/
    ├── negative-keyword-miner/
    ├── meta-ads-creative-brief/
    ├── creative-testing-framework/
    ├── creative-testing-insights-reporter/
    ├── ad-creative-performance-predictor/
    ├── performance-max-auditor/
    ├── search-terms-analyzer/
    ├── meta-ads-andromeda-auditor/
    ├── meta-ads-audience-builder/
    ├── linkedin-ads-audience-builder/
    └── competitive-ads-extractor/
```

---

## Get the Newsletter

Every week I share AI-powered marketing workflows, tools, and automation tips.

**[Subscribe to The AI Driven Marketer](https://theaidrivenmarketer.beehiiv.com/)**

---

## Connect

- **YouTube:** [@RananjayRaj](https://youtube.com/@RananjayRaj) — Tutorials on Claude Code, Cowork & vibe coding
- **LinkedIn:** [/in/rananjayraj](https://linkedin.com/in/rananjayraj/)
- **Newsletter:** [The AI Driven Marketer](https://theaidrivenmarketer.beehiiv.com/)

---

## License

MIT — free to use, modify, and distribute.

---

## Version History

| Version | Date | Changes |
|---------|------|---------|
| 1.0.0 | Feb 2026 | Initial release — 13 skills, 7 commands |
