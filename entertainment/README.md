# Rozrywka (Entertainment)

1 datasets — 1,349 records

> Browse at [listbase.org/pl/entertainment/](https://listbase.org/pl/entertainment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Polska — księgarnie](pl-ksiegarnie.json) | 1,349 | 134 KB | [CSV](pl-ksiegarnie_PL.csv) | [Excel](pl-ksiegarnie_PL.xlsx) | [View](https://listbase.org/pl/entertainment/pl-ksiegarnie/) |

## Quick Start

```bash
# List all entertainment datasets
curl https://cdn.pl.listbase.org/index.json | jq '.datasets[] | select(.category=="entertainment") | .id'

# Fetch a dataset
curl https://cdn.pl.listbase.org/entertainment/pl-ksiegarnie.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/pl/entertainment/)
