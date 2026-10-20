# Sport (Sports)

1 datasets — 1,115 records

> Browse at [listbase.org/pl/sports/](https://listbase.org/pl/sports/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Polska — sklepy sportowe](pl-sklepy-sportowe.json) | 1,115 | 109 KB | [CSV](pl-sklepy-sportowe_PL.csv) | [Excel](pl-sklepy-sportowe_PL.xlsx) | [View](https://listbase.org/pl/sports/pl-sklepy-sportowe/) |

## Quick Start

```bash
# List all sports datasets
curl https://cdn.pl.listbase.org/index.json | jq '.datasets[] | select(.category=="sports") | .id'

# Fetch a dataset
curl https://cdn.pl.listbase.org/sports/pl-sklepy-sportowe.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/pl/sports/)
