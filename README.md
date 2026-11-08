# Brandable One-Word Domains (~246,000)

~246,000 names in this list today, refreshed every night.

Live page: [unique.domains/domains/brandable](https://unique.domains/domains/brandable?utm_source=github&utm_medium=referral&utm_campaign=repo_brandable_oneword_domains&utm_content=top_page)

<img alt="updated: daily" src="https://img.shields.io/badge/updated-daily-0969da"> <img alt="extract: 1,000 rows" src="https://img.shields.io/badge/extract-1%2C000%20rows-8250df"> <img alt="formats: CSV | JSON" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b"> <img alt="licence: CC BY 4.0" src="https://img.shields.io/badge/licence-CC%20BY%204.0-2ea44f">

## Download

- [brandable.csv](https://github.com/UniqueDomains/brandable-oneword-domains/raw/main/brandable.csv), 1,000 rows
- [brandable.json](https://github.com/UniqueDomains/brandable-oneword-domains/raw/main/brandable.json), 1,000 rows

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/brandable-oneword-domains/main/brandable.csv")
print(df.head())
```

## Sample rows

The first 20 rows of the file, in the file's order.

| domain                 | status    | purchase_price | renewal_price | attractiveness | demand | length |
| ---------------------- | --------- | -------------- | ------------- | -------------- | ------ | ------ |
| transformers.vacations | available | $30.20         | $30.20        | high           | low    | 12     |
| built.institute        | available | $5.38          | $21.94        | high           | medium | 5      |
| accurate.gg            | resell    | —              | —             | high           | low    | 8      |
| agreed.viajes          | available | $94.98         | $124.48       | high           | low    | 6      |
| goal.insure            | available | $72.99         | $72.99        | high           | low    | 4      |
| modem.attorney         | available | $62.99         | $62.99        | high           | low    | 5      |
| microphone.protection  | available | $1,999.99      | $2,049.99     | high           | low    | 10     |
| instant.accountant     | premium   | $650           | $84.50        | high           | medium | 7      |
| spiderman.memorial     | available | $41.60         | $41.60        | high           | low    | 9      |
| superstar.place        | available | $25.48         | $34.48        | high           | low    | 9      |
| bicycle.locker         | premium   | $1,100         | $32.32        | high           | medium | 7      |
| original.sucks         | available | $218.99        | $218.99       | high           | low    | 8      |
| sexy.tennis            | premium   | $85.80         | $85.80        | high           | low    | 4      |
| belt.computer          | available | $17.80         | $31.25        | high           | low    | 4      |
| young.fishing          | premium   | $41.60         | $26.08        | high           | medium | 5      |
| eight.menu             | available | $27.99         | $27.99        | high           | medium | 5      |
| fashions.direct        | available | $17            | —             | high           | low    | 8      |
| hardly.melbourne       | available | $42.60         | $42.60        | high           | low    | 6      |
| careful.wtf            | available | $7.49          | $36.49        | high           | low    | 7      |
| bizarre.homes          | available | $1.80          | $21.98        | high           | low    | 7      |

## What is in the data

- `domain`: Fully qualified domain name.
- `status`: Current acquisition state for the domain in the public extract.
- `purchase_price`: Visible purchase price when available.
- `renewal_price`: Visible renewal price when available.
- `attractiveness`: Public composite naming band used as a decision-support signal.
- `demand`: Public buyer-pressure band when available.
- `length`: Character count without the TLD.
- `registrar`: Registrar name when known.
- `created_at`: Creation timestamp when known.
- `expires_at`: Expiry timestamp when known.

Types and formats: [DATA_DICTIONARY.md](./DATA_DICTIONARY.md).

## Methodology

- The files hold 1,000 rows of the ~246,000 names in the live list today.
- Every row is a one-word domain name.
- Status and prices are the last ones Unique Domains stored for each name, not a reading taken on the day of the rebuild.
- The live count marked with a tilde is estimated from a 2 percent page sample of the catalog and rounded to three significant digits; it moves between nights. The rows in the files are real rows.

More in [METHODOLOGY.md](./METHODOLOGY.md).

## Update policy

- The files are rebuilt every night from the same export.
- The snapshot is the day of the rebuild; each row's status is the last one stored, not a reading of that day.
- The files hold the public extract, not the whole live list.

## How to cite

> Unique Domains, Brandable One-Word Domains, https://unique.domains/domains/brandable, CC BY 4.0

Citation metadata: [CITATION.cff](./CITATION.cff). A DOI follows once Zenodo mints one.

## Related datasets

- [Every one-word domain](https://github.com/UniqueDomains/oneword-domains) (the hub)

One-word domains by ending:

- [.com](https://github.com/UniqueDomains/com-oneword-domains), [page](https://unique.domains/tld/com?utm_source=github&utm_medium=referral&utm_campaign=repo_brandable_oneword_domains&utm_content=related_tld_page)
- [.ai](https://github.com/UniqueDomains/ai-oneword-domains), [page](https://unique.domains/tld/ai?utm_source=github&utm_medium=referral&utm_campaign=repo_brandable_oneword_domains&utm_content=related_tld_page)
- [.io](https://github.com/UniqueDomains/io-oneword-domains), [page](https://unique.domains/tld/io?utm_source=github&utm_medium=referral&utm_campaign=repo_brandable_oneword_domains&utm_content=related_tld_page)
- [.app](https://github.com/UniqueDomains/app-oneword-domains), [page](https://unique.domains/tld/app?utm_source=github&utm_medium=referral&utm_campaign=repo_brandable_oneword_domains&utm_content=related_tld_page)
- [.co](https://github.com/UniqueDomains/co-oneword-domains), [page](https://unique.domains/tld/co?utm_source=github&utm_medium=referral&utm_campaign=repo_brandable_oneword_domains&utm_content=related_tld_page)
- [.xyz](https://github.com/UniqueDomains/xyz-oneword-domains), [page](https://unique.domains/tld/xyz?utm_source=github&utm_medium=referral&utm_campaign=repo_brandable_oneword_domains&utm_content=related_tld_page)

Lists:

- [Expired](https://github.com/UniqueDomains/expired-oneword-domains)
- [Expiring](https://github.com/UniqueDomains/expiring-oneword-domains)
- [Short](https://github.com/UniqueDomains/short-oneword-domains)

Every ending Unique Domains tracks: [unique.domains/tld](https://unique.domains/tld?utm_source=github&utm_medium=referral&utm_campaign=repo_brandable_oneword_domains&utm_content=related_hub).

## About Unique Domains

[Unique Domains](https://unique.domains/?utm_source=github&utm_medium=referral&utm_campaign=repo_brandable_oneword_domains&utm_content=about) tracks one-word domain names across the endings people build on: which are free to register, what they cost to hold and what names of each ending sell for. The datasets in this organization are its public extracts, refreshed every night.

Questions and corrections: `kai@unique.domains`
