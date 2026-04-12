# Available .REST One-Word Domains (9,240)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-9%2C246%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-9%2C240%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated dataset of available and resale .rest one-word domains from Unique Domains.

> **Note:** this repository currently mirrors the full live catalog for this exact search.
> Unique Domains counts can still change as the search refreshes.

**Public extract:** 9,246 rows · **Live catalog:** 9,240 domains

**Last updated:** 2026-04-12  
**Canonical page:** `https://unique.domains/domains/tld/rest`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/rest?utm_source=github&utm_medium=referral&utm_campaign=repo_rest_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./rest.csv">CSV</a> / <a href="./rest.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_rest_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rest_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .REST search](https://unique.domains/domains/tld/rest?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_rest_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .REST search](https://unique.domains/domains/tld/rest?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_rest_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rest_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .REST one-word domain catalog.

### Files

- `rest.csv` — public CSV extract (9,246 rows)
- `rest.json` — public JSON extract (9,246 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/rest-oneword-domains/main/rest.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar       |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------- |
| nationwide.rest | available | $41.98    | —             | 76             | 66     | 10     | namecheap       |
| elderly.rest    | resell    | $41.98    | —             | 94             | 12     | 7      | GoDaddy         |
| apple.rest      | premium   | $177.68   | —             | 88             | 88     | 5      | name.com        |
| seventeen.rest  | available | $41.98    | —             | 84             | 62     | 9      | namecheap       |
| checkout.rest   | resell    | —         | —             | 68             | 79     | 9      | Dynadot, LLC    |
| easy.rest       | premium   | $819      | $1,170        | 128            | 62     | 4      | namecheap       |
| athletics.rest  | available | $41.98    | —             | 69             | 52     | 9      | namecheap       |
| prompt.rest     | resell    | —         | —             | 114            | 68     | 6      | Porkbun LLC     |
| power.rest      | premium   | $585      | $1,170        | 98             | 62     | 5      | namecheap       |
| unify.rest      | available | $41.98    | —             | 72             | 38     | 5      | namecheap       |
| line.rest       | resell    | —         | —             | 74             | 68     | 4      | Spaceship, Inc. |
| ace.rest        | premium   | $819      | $1,170        | 88             | 57     | 3      | namecheap       |
| conscious.rest  | available | $41.98    | —             | 89             | 37     | 9      | namecheap       |
| jesus.rest      | resell    | —         | —             | 126            | 52     | 5      | Dynadot, LLC    |
| live.rest       | premium   | $4,095    | $5,850        | 108            | 56     | 4      | namecheap       |
| rank.rest       | available | $41.98    | —             | 70             | 35     | 4      | namecheap       |
| air.rest        | resell    | —         | —             | 84             | 49     | 3      | Spaceship, Inc. |
| data.rest       | premium   | $1,462.50 | $2,925        | 70             | 56     | 4      | namecheap       |
| progress.rest   | available | $41.98    | —             | 82             | 34     | 8      | namecheap       |
| root.rest       | resell    | —         | —             | 64             | 49     | 4      | Spaceship, Inc. |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 9,246-row public sample | 9,240 live domains                               |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/rest?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_rest_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/rest?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_rest_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_rest_oneword_domains&utm_content=related_pricing)

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

> Unique Domains. *Available .REST One-Word Domains*. Version 2026-04-12. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .REST page](https://unique.domains/domains/tld/rest?utm_source=github&utm_medium=referral&utm_campaign=repo_rest_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_rest_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_rest_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rest_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
