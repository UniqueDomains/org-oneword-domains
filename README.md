# Available .ORG One-Word Domains (38,243)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-10%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-38%2C243%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .org one-word domains from Unique Domains.

> **Important:** this repository is a **public 10,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **38,243 domains** on the canonical page below.

**Public extract:** 10,000 rows · **Live catalog:** 38,243 domains

**Last updated:** 2026-04-12  
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

- `org.csv` — public CSV extract (10,000 rows)
- `org.json` — public JSON extract (10,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/org-oneword-domains/main/org.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain              | status    | ask_price  | renewal_price | attractiveness | demand | length | registrar                                   |
| ------------------- | --------- | ---------- | ------------- | -------------- | ------ | ------ | ------------------------------------------- |
| termdeposit.org     | available | $8.99      | $21.99        | 60             | 72     | 12     | name.com                                    |
| abram.org           | resell    | $4,138.85  | $17.99        | 84             | 84     | 5      | GoDaddy.com, LLC                            |
| icon.org            | premium   | $533,025   | —             | 89             | 43     | 4      | GoDaddy Online Services Cayman Islands Ltd. |
| enameling.org       | available | $8.99      | $21.99        | 56             | 72     | 9      | name.com                                    |
| studies.org         | resell    | $101,200   | $21.99        | —              | 84     | 7      | GoDaddy.com, LLC                            |
| gay.org             | premium   | $1,421,400 | —             | 82             | 43     | 3      | GoDaddy Online Services Cayman Islands Ltd. |
| abdominalcavity.org | available | $7.49      | $21.99        | 54             | 72     | 16     | name.com                                    |
| adorn.org           | resell    | $21,850    | $17.99        | 98             | 80     | 5      | GoDaddy.com, LLC                            |
| gaming.org          | premium   | $236,900   | —             | 76             | 38     | 6      | GoDaddy Online Services Cayman Islands Ltd. |
| finishedgoods.org   | available | $8.99      | $21.99        | 56             | 16     | 14     | name.com                                    |
| renewable.org       | resell    | $920,000   | $21.99        | 84             | 80     | 9      | GoDaddy Online Services Cayman Islands Ltd. |
| drift.org           | premium   | $59,225    | —             | 68             | 38     | 5      | GoDaddy Online Services Cayman Islands Ltd. |
| plotted.org         | available | $7.49      | $21.99        | 72             | 5      | 7      | name.com                                    |
| readiness.org       | resell    | $5,692.50  | $21.99        | 60             | 80     | 9      | GoDaddy.com, LLC                            |
| machine.org         | premium   | $88,837.50 | —             | 72             | 36     | 7      | GoDaddy Online Services Cayman Islands Ltd. |
| justabout.org       | available | $7.49      | $21.99        | 58             | 5      | 10     | name.com                                    |
| abatement.org       | resell    | $11,189.50 | $17.99        | 52             | 80     | 9      | GoDaddy.com, LLC                            |
| wicked.org          | premium   | $34,350.50 | —             | 62             | 30     | 6      | GoDaddy Online Services Cayman Islands Ltd. |
| accustomed.org      | available | $7.49      | $21.99        | 72             | 2      | 10     | name.com                                    |
| suiting.org         | resell    | $1,481.20  | $21.99        | 60             | 72     | 7      | DomainHood LLC                              |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract           | Unique Domains                                   |
| ------------------------ | ------------------------------------------------ |
| 10,000-row public sample | 38,243 live domains                              |
| Static CSV / JSON        | live search and daily refresh                    |
| Basic exported fields    | deeper price, demand, risk, and workflow context |
| No persistence           | Radar, saved search, and alerts                  |
| No founder workflow      | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/org?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_org_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/org?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_org_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_org_oneword_domains&utm_content=related_pricing)

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

> Unique Domains. *Available .ORG One-Word Domains*. Version 2026-04-12. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .ORG page](https://unique.domains/domains/tld/org?utm_source=github&utm_medium=referral&utm_campaign=repo_org_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_org_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_org_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_org_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
