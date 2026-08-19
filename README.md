# Available .ORG One-Word Domains (41,040)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-41%2C040%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .org one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **41,040 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 41,040 domains · **Median ask:** $5,085.46 · **High-demand under $2,500:** 31

**Last updated:** 2026-08-19
**Canonical page:** `https://unique.domains/domains/tld/org`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/org?utm_source=github&utm_medium=referral&utm_campaign=repo_org_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./org.csv">CSV</a> / <a href="./org.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_org_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_org_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .ORG search](https://unique.domains/domains/tld/org?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_org_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .ORG search](https://unique.domains/domains/tld/org?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_org_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_org_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .ORG one-word domain catalog.

### Files

- `org.csv`, public CSV extract (1,000 rows)
- `org.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/org-oneword-domains/main/org.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status    | ask_price  | renewal_price | attractiveness | demand | length | registrar                                   |
| -------------- | --------- | ---------- | ------------- | -------------- | ------ | ------ | ------------------------------------------- |
| ilxx.org       | available | $8.48      | $18.98        | low            | low    | 4      | namecheap                                   |
| feb.org        | resell    | $23,688.82 | —             | high           | low    | 3      | Dynadot Inc                                 |
| icon.org       | premium   | $533,025   | —             | high           | medium | 4      | GoDaddy Online Services Cayman Islands Ltd. |
| agnate.org     | available | $8.48      | $18.98        | low            | low    | 6      | namecheap                                   |
| rompers.org    | resell    | $9,526.60  | $21.99        | medium         | low    | 7      | 1API GmbH                                   |
| unlike.org     | premium   | $2,286.20  | $2,286.20     | high           | low    | 6      | Azdomainz, LLC                              |
| anodic.org     | available | $8.48      | $18.98        | medium         | low    | 6      | namecheap                                   |
| abatement.org  | resell    | $11,189.50 | $17.99        | medium         | high   | 9      | GoDaddy.com, LLC                            |
| worker.org     | premium   | $33,166    | —             | high           | low    | 6      | GoDaddy Online Services Cayman Islands Ltd. |
| jelled.org     | available | $8.48      | $18.98        | low            | low    | 6      | namecheap                                   |
| aboriginal.org | resell    | $11,371.20 | $17.99        | low            | low    | 10     | GoDaddy Online Services Cayman Islands Ltd. |
| landing.org    | premium   | $34,350.50 | —             | high           | low    | 7      | GoDaddy Online Services Cayman Islands Ltd. |
| pimply.org     | available | $8.48      | $18.98        | low            | low    | 6      | namecheap                                   |
| CME.org        | resell    | —          | —             | high           | high   | 3      | Dynadot Inc                                 |
| altissimo.org  | premium   | $2,236.34  | $19.99        | low            | low    | 9      | Annulet LLC                                 |
| adenoid.org    | available | $8.48      | $18.98        | low            | low    | 7      | namecheap                                   |
| eve.org        | resell    | —          | —             | high           | medium | 3      | PDR Ltd. d/b/a PublicDomainRegistry.com     |
| diplomatic.org | premium   | $24,874.50 | —             | high           | low    | 10     | GoDaddy Online Services Cayman Islands Ltd. |
| albinal.org    | available | $8.48      | $18.98        | low            | low    | 7      | namecheap                                   |
| fmt.org        | resell    | —          | —             | high           | high   | 3      | Dynadot Inc                                 |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 41,040 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 31 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/org?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_org_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/org?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_org_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_org_oneword_domains&utm_content=related_pricing)

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

This selection includes 38,856 one-word .ORG domain names covering everyday vocabulary — from concrete nouns like destination.org and spray.org to descriptive terms like vegetarian.org and arabic.org. With a median ask near $10,492, pricing spans a wide range, giving investors room to scan for spread and founders room to find a brandable, ownable name.

- 38,856 one-word .ORG domains in this selection
- Median ask near $10,492 across the set
- Mix of nouns, verbs & adjectives — high brandability
- Compare pricing & renewal before deciding

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .ORG One-Word Domains*. Version 2026-08-19. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .ORG page](https://unique.domains/domains/tld/org?utm_source=github&utm_medium=referral&utm_campaign=repo_org_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_org_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_org_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_org_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
