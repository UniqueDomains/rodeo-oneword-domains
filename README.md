# Available .RODEO One-Word Domains (17,496)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-17%2C496%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .rodeo one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **17,496 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 17,496 domains · **Median ask:** $20.55 · **High-demand under $2,500:** 18

**Last updated:** 2026-08-20
**Canonical page:** `https://unique.domains/domains/tld/rodeo`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/rodeo?utm_source=github&utm_medium=referral&utm_campaign=repo_rodeo_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./rodeo.csv">CSV</a> / <a href="./rodeo.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_rodeo_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rodeo_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .RODEO search](https://unique.domains/domains/tld/rodeo?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_rodeo_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .RODEO search](https://unique.domains/domains/tld/rodeo?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_rodeo_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rodeo_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .RODEO one-word domain catalog.

### Files

- `rodeo.csv`, public CSV extract (1,000 rows)
- `rodeo.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/rodeo-oneword-domains/main/rodeo.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| bae.rodeo     | available | $12.99    | $12.99        | high           | low    | 3      | namesilo         |
| start.rodeo   | resell    | —         | —             | high           | medium | 5      | GoDaddy.com, LLC |
| abo.rodeo     | premium   | $47.20    | $11.80        | low            | low    | 3      | namesilo         |
| HBO.rodeo     | available | $12.99    | $12.99        | high           | medium | 3      | namesilo         |
| leather.rodeo | resell    | —         | —             | high           | low    | 7      | Dynadot Inc      |
| ana.rodeo     | premium   | $96       | $11.80        | high           | low    | 3      | namesilo         |
| ilx.rodeo     | available | $12.99    | $12.99        | low            | low    | 3      | namesilo         |
| ass.rodeo     | premium   | $96       | $11.80        | low            | low    | 3      | namesilo         |
| sep.rodeo     | available | $12.99    | $12.99        | high           | low    | 3      | namesilo         |
| ate.rodeo     | premium   | $47.20    | $11.80        | high           | low    | 3      | namesilo         |
| suv.rodeo     | available | $12.99    | $12.99        | high           | low    | 3      | namesilo         |
| beg.rodeo     | premium   | $96       | $11.80        | medium         | low    | 3      | namesilo         |
| xxv.rodeo     | available | $12.99    | $12.99        | medium         | low    | 3      | namesilo         |
| bit.rodeo     | premium   | $96       | $11.80        | high           | medium | 3      | namesilo         |
| aery.rodeo    | available | $12.99    | $12.99        | low            | low    | 4      | namesilo         |
| bra.rodeo     | premium   | $96       | $11.80        | medium         | low    | 3      | namesilo         |
| arty.rodeo    | available | $12.99    | $12.99        | low            | low    | 4      | namesilo         |
| con.rodeo     | premium   | $96       | $11.80        | high           | low    | 3      | namesilo         |
| bead.rodeo    | available | $12.99    | $12.99        | high           | low    | 4      | namesilo         |
| dew.rodeo     | premium   | $96       | $11.80        | medium         | low    | 3      | namesilo         |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 17,496 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 18 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/rodeo?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_rodeo_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/rodeo?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_rodeo_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_rodeo_oneword_domains&utm_content=related_pricing)

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

This list covers 12,508 one-word and short-phrase .rodeo domain names, including everyday words like edamame.rodeo and rumcake.rodeo alongside action phrases such as useit.rodeo and lightup.rodeo. The median asking price across the set sits near $25, keeping entry costs low across this niche extension. For founders, the mix includes short, ownable names that are easy to spell and pronounce. For investors, the .rodeo extension offers wide word-availability, though resale liquidity should be checked against .com equivalents before buying. Updated daily.

- 12,508 one-word .rodeo domains tracked, spanning short words to phrases
- Median asking price near $25 across this .rodeo selection
- Includes brandable single words and compound name-style domains
- Updated daily to reflect current .rodeo pricing

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .RODEO One-Word Domains*. Version 2026-08-20. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .RODEO page](https://unique.domains/domains/tld/rodeo?utm_source=github&utm_medium=referral&utm_campaign=repo_rodeo_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_rodeo_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_rodeo_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rodeo_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
