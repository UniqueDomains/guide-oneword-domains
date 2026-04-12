# Available .GUIDE One-Word Domains (8,325)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-8%2C325%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-8%2C325%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated dataset of available and resale .guide one-word domains from Unique Domains.

> **Note:** this repository currently mirrors the full live catalog for this exact search.
> Unique Domains counts can still change as the search refreshes.

**Public extract:** 8,325 rows · **Live catalog:** 8,325 domains

**Last updated:** 2026-04-12  
**Canonical page:** `https://unique.domains/domains/tld/guide`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/guide?utm_source=github&utm_medium=referral&utm_campaign=repo_guide_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./guide.csv">CSV</a> / <a href="./guide.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_guide_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_guide_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .GUIDE search](https://unique.domains/domains/tld/guide?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_guide_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .GUIDE search](https://unique.domains/domains/tld/guide?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_guide_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_guide_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .GUIDE one-word domain catalog.

### Files

- `guide.csv` — public CSV extract (8,325 rows)
- `guide.json` — public JSON extract (8,325 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/guide-oneword-domains/main/guide.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain             | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                                 |
| ------------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------------- |
| snap.guide         | available | $10.99    | $57.99        | 90             | 46     | 4      | name.com                                                  |
| artificial.guide   | resell    | —         | —             | 68             | 98     | 10     | Dynadot Inc                                               |
| sex.guide          | premium   | $500      | —             | 80             | 59     | 3      | name.com                                                  |
| swap.guide         | available | $10.99    | —             | 80             | 39     | 4      | name.com                                                  |
| entrepreneur.guide | resell    | —         | —             | 78             | 80     | 12     | Porkbun LLC                                               |
| ace.guide          | premium   | $42.90    | $42.90        | 88             | 57     | 3      | namecheap                                                 |
| conscious.guide    | available | $10.99    | $57.99        | 89             | 38     | 9      | name.com                                                  |
| office.guide       | resell    | —         | —             | 100            | 58     | 6      | DomainSite, Inc.                                          |
| true.guide         | premium   | $500      | $500          | 86             | 52     | 4      | name.com                                                  |
| unify.guide        | available | $10.99    | $57.99        | 72             | 38     | 5      | name.com                                                  |
| the.guide          | resell    | —         | —             | 98             | 58     | 3      | 1API GmbH                                                 |
| all.guide          | premium   | $42.90    | $42.90        | 88             | 48     | 3      | namecheap                                                 |
| sharp.guide        | available | $10.99    | $57.99        | 84             | 36     | 5      | name.com                                                  |
| data.guide         | resell    | —         | —             | 70             | 56     | 4      | Global Domains International, Inc. DBA DomainCostClub.com |
| green.guide        | premium   | $128.70   | $128.70       | 108            | 45     | 5      | namecheap                                                 |
| aaron.guide        | available | $54.48    | —             | 88             | 35     | 5      | namecheap                                                 |
| email.guide        | resell    | —         | —             | 106            | 54     | 6      | GoDaddy.com, LLC                                          |
| food.guide         | premium   | $11,700   | $11,700       | 94             | 44     | 4      | namecheap                                                 |
| goon.guide         | available | $10.99    | $57.99        | 80             | 35     | 5      | name.com                                                  |
| alpha.guide        | resell    | —         | —             | 90             | 54     | 5      | Spaceship, Inc.                                           |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 8,325-row public sample | 8,325 live domains                               |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/guide?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_guide_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/guide?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_guide_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_guide_oneword_domains&utm_content=related_pricing)

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

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .GUIDE One-Word Domains*. Version 2026-04-12. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .GUIDE page](https://unique.domains/domains/tld/guide?utm_source=github&utm_medium=referral&utm_campaign=repo_guide_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_guide_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_guide_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_guide_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
