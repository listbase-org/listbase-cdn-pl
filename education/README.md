# Edukacja (Education)

3 datasets — 24,836 records

> Browse at [listbase.org/pl/education/](https://listbase.org/pl/education/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Szkoły w Polsce (Schools in Poland, OSM)](pl-szkoly.json) | 15,682 | 2048 KB | [CSV](pl-szkoly_PL.csv) | [Excel](pl-szkoly_PL.xlsx) | [View](https://listbase.org/pl/education/pl-szkoly/) |
| [Przedszkola w Polsce (Kindergartens in Poland, OSM)](pl-przedszkola.json) | 9,017 | 1056 KB | [CSV](pl-przedszkola_PL.csv) | [Excel](pl-przedszkola_PL.xlsx) | [View](https://listbase.org/pl/education/pl-przedszkola/) |
| [Polska — Uniwersytety i uczelnie wyższe](pl-uniwersytety.json) | 137 | 44 KB | [CSV](pl-uniwersytety_PL.csv) | [Excel](pl-uniwersytety_PL.xlsx) | [View](https://listbase.org/pl/education/pl-uniwersytety/) |

## Quick Start

```bash
# List all education datasets
curl https://cdn.pl.listbase.org/index.json | jq '.datasets[] | select(.category=="education") | .id'

# Fetch a dataset
curl https://cdn.pl.listbase.org/education/pl-szkoly.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/pl/education/)
