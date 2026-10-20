# Zdrowie (Health)

1 datasets — 11,435 records

> Browse at [listbase.org/pl/health/](https://listbase.org/pl/health/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Apteki w Polsce (Pharmacies in Poland, OSM)](pl-apteki.json) | 11,435 | 1129 KB | [CSV](pl-apteki_PL.csv) | [Excel](pl-apteki_PL.xlsx) | [View](https://listbase.org/pl/health/pl-apteki/) |

## Quick Start

```bash
# List all health datasets
curl https://cdn.pl.listbase.org/index.json | jq '.datasets[] | select(.category=="health") | .id'

# Fetch a dataset
curl https://cdn.pl.listbase.org/health/pl-apteki.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/pl/health/)
