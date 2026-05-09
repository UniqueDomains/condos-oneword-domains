# Available .CONDOS One-Word Domains (12,809)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C809%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .condos one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,809 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,809 domains · **Median ask:** $75.56 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-09  
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

- `condos.csv` — public CSV extract (1,000 rows)
- `condos.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/condos-oneword-domains/main/condos.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain              | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| skills.condos       | available | $71.99    | —             | 58             | 47     | 6      | name.com  |
| tickets.condos      | premium   | $118.80   | $118.80       | 64             | 34     | 7      | namesilo  |
| whynot.condos       | available | $71.99    | —             | 74             | 39     | 7      | name.com  |
| solutions.condos    | premium   | $123.75   | —             | 56             | 31     | 9      | name.com  |
| tokens.condos       | available | $58.99    | $58.99        | 51             | 36     | 6      | namesilo  |
| photos.condos       | premium   | $123.75   | —             | 54             | 28     | 6      | name.com  |
| Cats.condos         | available | $72.98    | —             | 59             | 33     | 4      | namecheap |
| loans.condos        | premium   | $118.80   | $118.80       | 58             | 24     | 5      | namesilo  |
| teams.condos        | available | $71.99    | —             | 62             | 32     | 5      | name.com  |
| flights.condos      | premium   | $118.80   | $118.80       | 61             | 22     | 7      | namesilo  |
| trends.condos       | available | $71.99    | —             | 60             | 32     | 6      | name.com  |
| reservation.condos  | premium   | $250      | —             | 65             | 19     | 11     | name.com  |
| heroes.condos       | available | $71.99    | —             | 68             | 29     | 6      | name.com  |
| vacations.condos    | premium   | $854      | $854          | 56             | 19     | 9      | namesilo  |
| cams.condos         | available | $58.99    | $58.99        | 52             | 29     | 4      | namesilo  |
| highend.condos      | premium   | $82.50    | —             | 72             | 17     | 8      | name.com  |
| dogs.condos         | available | $71.99    | —             | 76             | 28     | 4      | name.com  |
| LongBeach.condos    | premium   | $92.40    | $92.40        | 62             | 11     | 10     | namecheap |
| commonground.condos | available | $71.99    | —             | 74             | 28     | 13     | name.com  |
| gems.condos         | available | $58.99    | $58.99        | 70             | 28     | 4      | namesilo  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,809 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/condos?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_condos_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/condos?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_condos_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_condos_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This selection is entirely made up of one-word .condos domains. That makes the extension itself the main signal: every name is explicitly tied to condo use, so the word before the dot has to carry the branding quality. Short, concrete words such as call.condos, action.condos, play.condos, bag.condos, and zest.condos feel very different in marketability, even if pricing looks similar. For founders, the key question is whether the word sounds credible and memorable for a condo-related brand. For investors, the key question is whether the term is commercially intuitive enough to support resale interest relative to ask and renewal economics.

- All names in this selection use the .condos extension
- Median ask across the set is 75.56
- Favor words with clear condo or property relevance
- Avoid names that feel random, awkward, or hard to justify

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .CONDOS One-Word Domains*. Version 2026-05-09. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .CONDOS page](https://unique.domains/domains/tld/condos?utm_source=github&utm_medium=referral&utm_campaign=repo_condos_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_condos_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_condos_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_condos_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
