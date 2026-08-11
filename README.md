# Available .CONDOS One-Word Domains (13,745)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-13%2C745%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .condos one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **13,745 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 13,745 domains · **Median ask:** $69.25 · **High-demand under $2,500:** 3

**Last updated:** 2026-08-11
**Canonical page:** `https://unique.domains/domains/tld/condos`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/condos?utm_source=github&utm_medium=referral&utm_campaign=repo_condos_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./condos.csv">CSV</a> / <a href="./condos.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_condos_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_condos_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .CONDOS search](https://unique.domains/domains/tld/condos?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_condos_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .CONDOS search](https://unique.domains/domains/tld/condos?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_condos_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_condos_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .CONDOS one-word domain catalog.

### Files

- `condos.csv`, public CSV extract (1,000 rows)
- `condos.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/condos-oneword-domains/main/condos.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| christmas.condos | premium   | $854      | $854          | high           | low    | 9      | namesilo         |
| come.condos      | available | $58.99    | $58.99        | high           | low    | 4      | namesilo         |
| action.condos    | available | $58.99    | $58.99        | high           | medium | 6      | namesilo         |
| abo.condos       | available | $58.99    | $58.99        | low            | low    | 3      | namesilo         |
| have.condos      | resell    | —         | —             | high           | low    | 4      | Sav.com, LLC     |
| boo.condos       | premium   | $82.50    | —             | high           | low    | 3      | name.com         |
| ape.condos       | available | $58.99    | $58.99        | medium         | low    | 3      | namesilo         |
| alaska.condos    | resell    | —         | —             | high           | low    | 6      | GoDaddy.com, LLC |
| eat.condos       | premium   | $78.54    | $78.54        | high           | low    | 3      | namesilo         |
| aug.condos       | available | $58.99    | $58.99        | low            | low    | 3      | namesilo         |
| fan.condos       | premium   | $118.80   | $118.80       | high           | low    | 3      | namesilo         |
| azo.condos       | available | $58.99    | $58.99        | low            | low    | 3      | namesilo         |
| fee.condos       | premium   | $118.80   | $118.80       | high           | low    | 3      | namesilo         |
| bag.condos       | available | $58.99    | $58.99        | high           | low    | 3      | namesilo         |
| fix.condos       | premium   | $118.80   | $118.80       | medium         | low    | 3      | namesilo         |
| but.condos       | available | $58.99    | $58.99        | high           | low    | 3      | namesilo         |
| gas.condos       | premium   | $260      | $260          | high           | low    | 3      | namecheap        |
| CNN.condos       | available | $58.99    | $58.99        | high           | low    | 3      | namesilo         |
| His.condos       | premium   | $118.80   | $118.80       | high           | low    | 3      | namesilo         |
| cry.condos       | available | $71.99    | —             | high           | low    | 3      | name.com         |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 13,745 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 3 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/condos?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_condos_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/condos?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_condos_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_condos_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This list gathers one-word .condos domain names such as watches.condos, gearup.condos, and forces.condos. Each name pairs a single, memorable word with the .condos extension, making them well suited for real estate, home services, and lifestyle-focused brands. With a median ask near $72, most of these domains sit within reach of a small business budget, and renewal costs should be checked before purchase. Updated daily, this selection makes it straightforward to shortlist a distinctive name in a niche where availability is often limited.

- 12,809 one-word .condos domain names in this selection
- Median asking price near $72
- Names built for real estate, lifestyle, and home brands
- Updated daily — compare pricing and renewal before buying

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .CONDOS One-Word Domains*. Version 2026-08-11. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .CONDOS page](https://unique.domains/domains/tld/condos?utm_source=github&utm_medium=referral&utm_campaign=repo_condos_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_condos_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_condos_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_condos_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
