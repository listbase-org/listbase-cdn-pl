# Środowisko (Environment)

9 datasets — 5,478 records

> Browse at [listbase.org/pl/environment/](https://listbase.org/pl/environment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Elektrownie w Polsce](pl-elektrownie.json) | 2,745 | 1403 KB | [CSV](pl-elektrownie_PL.csv) | [Excel](pl-elektrownie_PL.xlsx) | [View](https://listbase.org/pl/environment/pl-elektrownie/) |
| [Elektrownie słoneczne w Polsce](pl-sloneczne-elektrownie.json) | 2,386 | 1214 KB | [CSV](pl-sloneczne-elektrownie_PL.csv) | [Excel](pl-sloneczne-elektrownie_PL.xlsx) | [View](https://listbase.org/pl/environment/pl-sloneczne-elektrownie/) |
| [Elektrownie wiatrowe w Polsce](pl-wiatrowe-elektrownie.json) | 229 | 117 KB | [CSV](pl-wiatrowe-elektrownie_PL.csv) | [Excel](pl-wiatrowe-elektrownie_PL.xlsx) | [View](https://listbase.org/pl/environment/pl-wiatrowe-elektrownie/) |
| [Elektrownie na węgiel kamienny w Polsce](pl-kamiennoweglowe-elektrownie.json) | 49 | 34 KB | [CSV](pl-kamiennoweglowe-elektrownie_PL.csv) | [Excel](pl-kamiennoweglowe-elektrownie_PL.xlsx) | [View](https://listbase.org/pl/environment/pl-kamiennoweglowe-elektrownie/) |
| [Elektrownie wodne w Polsce](pl-wodne-elektrownie.json) | 34 | 21 KB | [CSV](pl-wodne-elektrownie_PL.csv) | [Excel](pl-wodne-elektrownie_PL.xlsx) | [View](https://listbase.org/pl/environment/pl-wodne-elektrownie/) |
| [Jednostki miary — kategoria 'energy' (14)](pl-jednostki-miary-energy.json) | 14 | 5 KB | [CSV](pl-jednostki-miary-energy_PL.csv) | [Excel](pl-jednostki-miary-energy_PL.xlsx) | [View](https://listbase.org/pl/environment/pl-jednostki-miary-energy/) |
| [Elektrownie na biomasę w Polsce](pl-biomasowe-elektrownie.json) | 9 | 8 KB | [CSV](pl-biomasowe-elektrownie_PL.csv) | [Excel](pl-biomasowe-elektrownie_PL.xlsx) | [View](https://listbase.org/pl/environment/pl-biomasowe-elektrownie/) |
| [Elektrownie na węgiel brunatny w Polsce](pl-brunatnoweglowe-elektrownie.json) | 7 | 8 KB | [CSV](pl-brunatnoweglowe-elektrownie_PL.csv) | [Excel](pl-brunatnoweglowe-elektrownie_PL.xlsx) | [View](https://listbase.org/pl/environment/pl-brunatnoweglowe-elektrownie/) |
| [Jednostki miary — kategoria 'temperature' (5)](pl-jednostki-miary-temperature.json) | 5 | 3 KB | [CSV](pl-jednostki-miary-temperature_PL.csv) | [Excel](pl-jednostki-miary-temperature_PL.xlsx) | [View](https://listbase.org/pl/environment/pl-jednostki-miary-temperature/) |

## Quick Start

```bash
# List all environment datasets
curl https://cdn.pl.listbase.org/index.json | jq '.datasets[] | select(.category=="environment") | .id'

# Fetch a dataset
curl https://cdn.pl.listbase.org/environment/pl-elektrownie.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/pl/environment/)
