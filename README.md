# Available .REST One-Word Domains (12,162)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C162%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .rest one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,162 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,162 domains · **Median ask:** $77.18 · **High-demand under $2,500:** 0

**Last updated:** 2026-07-07
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

- `rest.csv`, public CSV extract (1,000 rows)
- `rest.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/rest-oneword-domains/main/rest.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain       | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                           |
| ------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------------------------- |
| HBO.rest     | available | $2.19     | $28.99        | high           | medium | 3      | namesilo                            |
| lawyer.rest  | resell    | $19.99    | —             | medium         | low    | 6      | NAMECHEAP                           |
| ADS.rest     | premium   | $787.50   | —             | high           | medium | 3      | name.com                            |
| led.rest     | available | $2.19     | $28.99        | high           | low    | 3      | namesilo                            |
| ball.rest    | resell    | —         | —             | medium         | low    | 4      | Spaceship, Inc.                     |
| arm.rest     | premium   | $3,937.50 | —             | high           | medium | 3      | name.com                            |
| RGB.rest     | available | $2.19     | $28.99        | medium         | low    | 3      | namesilo                            |
| rich.rest    | resell    | —         | —             | high           | low    | 4      | Spaceship, Inc.                     |
| boy.rest     | premium   | $393.75   | —             | medium         | low    | 3      | name.com                            |
| sue.rest     | available | $2.19     | $28.99        | high           | low    | 3      | namesilo                            |
| rose.rest    | resell    | —         | —             | high           | medium | 4      | GMO Internet, Inc. d/b/a Onamae.com |
| egg.rest     | premium   | $1,968.75 | —             | high           | low    | 3      | name.com                            |
| tub.rest     | available | $2.19     | $28.99        | high           | low    | 3      | namesilo                            |
| shell.rest   | resell    | —         | —             | medium         | low    | 5      | Spaceship, Inc.                     |
| end.rest     | premium   | $1,968.75 | —             | high           | low    | 3      | name.com                            |
| xvi.rest     | available | $2.19     | $28.99        | medium         | low    | 3      | namesilo                            |
| moment.rest  | resell    | —         | —             | high           | low    | 6      | GMO Internet, Inc. d/b/a Onamae.com |
| gay.rest     | premium   | $787.50   | —             | high           | medium | 3      | name.com                            |
| bare.rest    | available | $2.19     | $28.99        | medium         | low    | 4      | namesilo                            |
| freedom.rest | resell    | —         | —             | high           | medium | 7      | Spaceship, Inc.                     |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,162 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/rest?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_rest_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/rest?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_rest_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_rest_oneword_domains&utm_content=related_pricing)

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

This list of .rest domain names spans single words, compound phrases, and niche terms like jetblack.rest, getmoving.rest, and pierogi.rest. With 12,162 domains and a median ask around $77, pricing stays approachable for most budgets. A handful of entries, such as WiFi.rest and Chanel.rest, carry trademark or generic-term risk worth checking before you commit.

- 12,162 one-word .rest domains available now
- Median ask near $77 across the full set
- Mix of brandable, compound, and dictionary-style names
- Some names carry trademark or generic-term risk — vet first

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .REST One-Word Domains*. Version 2026-07-07. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .REST page](https://unique.domains/domains/tld/rest?utm_source=github&utm_medium=referral&utm_campaign=repo_rest_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_rest_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_rest_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rest_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
