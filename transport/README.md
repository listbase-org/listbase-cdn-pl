# Transport (Transport)

3 datasets — 2,106 records

> Browse at [listbase.org/pl/transport/](https://listbase.org/pl/transport/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Kody lokalizacji UN/LOCODE — Polska (porty, lotniska, terminale)](pl-unlocode.json) | 1,952 | 1306 KB | [CSV](pl-unlocode_PL.csv) | [Excel](pl-unlocode_PL.xlsx) | [View](https://listbase.org/pl/transport/pl-unlocode/) |
| [Lotniska w Polsce (Airports of Poland)](pl-lotniska.json) | 149 | 72 KB | [CSV](pl-lotniska_PL.csv) | [Excel](pl-lotniska_PL.xlsx) | [View](https://listbase.org/pl/transport/pl-lotniska/) |
| [Międzynarodowe lotniska w Polsce (International Airports of Poland)](pl-lotniska-miedzynarodowe.json) | 5 | 5 KB | [CSV](pl-lotniska-miedzynarodowe_PL.csv) | [Excel](pl-lotniska-miedzynarodowe_PL.xlsx) | [View](https://listbase.org/pl/transport/pl-lotniska-miedzynarodowe/) |

## Quick Start

```bash
# List all transport datasets
curl https://cdn.pl.listbase.org/index.json | jq '.datasets[] | select(.category=="transport") | .id'

# Fetch a dataset
curl https://cdn.pl.listbase.org/transport/pl-unlocode.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/pl/transport/)
