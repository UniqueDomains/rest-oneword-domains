# Available .REST One-Word Domains (12,159)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C159%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .rest one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,159 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,159 domains · **Median ask:** $58.23 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-11  
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

- `rest.csv` — public CSV extract (1,000 rows)
- `rest.json` — public JSON extract (1,000 rows)
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

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar       |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------- |
| Acup.rest     | available | $41.98    | —             | 80             | 5      | 5      | namecheap       |
| might.rest    | premium   | —         | —             | 80             | 13     | 5      | —               |
| Skype.rest    | available | $41.98    | —             | 86             | 65     | 5      | namecheap       |
| geton.rest    | available | $19.99    | —             | 82             | 10     | 6      | name.com        |
| edamame.rest  | available | $2.19     | $28.99        | 80             | 9      | 7      | namesilo        |
| playon.rest   | available | $19.99    | —             | 80             | 14     | 7      | name.com        |
| QandA.rest    | available | $41.98    | —             | 80             | 10     | 7      | namecheap       |
| toneup.rest   | available | $19.99    | —             | 80             | 5      | 7      | name.com        |
| hangon.rest   | available | $19.99    | —             | 82             | 6      | 7      | name.com        |
| dogsick.rest  | available | $19.99    | —             | 90             | 1      | 7      | name.com        |
| getlife.rest  | available | $19.99    | —             | 80             | 5      | 8      | name.com        |
| leaveon.rest  | available | $19.99    | —             | 80             | 1      | 8      | name.com        |
| Snickers.rest | available | $41.98    | —             | 80             | 10     | 8      | namecheap       |
| makers.rest   | available | $2.19     | $28.99        | 62             | 67     | 6      | namesilo        |
| iconic.rest   | resell    | —         | —             | 76             | 38     | 6      | Spaceship, Inc. |
| jobs.rest     | premium   | $787.50   | —             | 79             | 42     | 4      | name.com        |
| crystal.rest  | resell    | —         | —             | 70             | 37     | 7      | GoDaddy         |
| matcha.rest   | premium   | $393.75   | —             | 86             | 39     | 6      | name.com        |
| spaces.rest   | available | $19.99    | —             | 54             | 30     | 6      | name.com        |
| cams.rest     | resell    | —         | —             | 52             | 29     | 4      | NAMECHEAP       |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,159 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

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

This selection is entirely made up of one-word .rest domains. The set spans generic terms, action words, plurals, and sharper coined or suggestive names such as Acup.rest, finals.rest, jewels.rest, forces.rest, and useit.rest. Median ask is 58.23, which keeps initial pricing straightforward, but the real decision is fit: whether the word is easy to say, easy to remember, and credible on a .rest ending. Some names look broadly brandable, while others may raise rights concerns because they match well-known terms. A strong pick in this set is simple, distinct, and commercially usable without ambiguity.

- One-word .rest domains only
- 12,158 domains; median ask 58.23
- Check clarity, recall, and commercial fit
- Avoid obvious trademark-heavy terms

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .REST One-Word Domains*. Version 2026-05-11. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .REST page](https://unique.domains/domains/tld/rest?utm_source=github&utm_medium=referral&utm_campaign=repo_rest_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_rest_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_rest_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rest_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
