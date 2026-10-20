# Żywność i Odżywianie (Food & Nutrition)

5 datasets — 38,481 records

> Browse at [listbase.org/pl/food/](https://listbase.org/pl/food/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Restauracje w Polsce (Restaurants in Poland, OSM)](pl-restauracje.json) | 20,800 | 2075 KB | [CSV](pl-restauracje_PL.csv) | [Excel](pl-restauracje_PL.xlsx) | [View](https://listbase.org/pl/food/pl-restauracje/) |
| [Bary szybkiej obsługi (fast food) w Polsce (Fast food, OSM)](pl-bary-szybkiej-obslugi.json) | 11,093 | 1091 KB | [CSV](pl-bary-szybkiej-obslugi_PL.csv) | [Excel](pl-bary-szybkiej-obslugi_PL.xlsx) | [View](https://listbase.org/pl/food/pl-bary-szybkiej-obslugi/) |
| [Piekarnie w Polsce (Bakeries in Poland, OSM)](pl-piekarnie.json) | 6,057 | 604 KB | [CSV](pl-piekarnie_PL.csv) | [Excel](pl-piekarnie_PL.xlsx) | [View](https://listbase.org/pl/food/pl-piekarnie/) |
| [Polska — sklepy z winem](pl-sklepy-z-winem.json) | 335 | 34 KB | [CSV](pl-sklepy-z-winem_PL.csv) | [Excel](pl-sklepy-z-winem_PL.xlsx) | [View](https://listbase.org/pl/food/pl-sklepy-z-winem/) |
| [Restauracje Michelin w Polsce](pl-restauracje-michelin.json) | 196 | 205 KB | [CSV](pl-restauracje-michelin_PL.csv) | [Excel](pl-restauracje-michelin_PL.xlsx) | [View](https://listbase.org/pl/food/pl-restauracje-michelin/) |

## Quick Start

```bash
# List all food & nutrition datasets
curl https://cdn.pl.listbase.org/index.json | jq '.datasets[] | select(.category=="food") | .id'

# Fetch a dataset
curl https://cdn.pl.listbase.org/food/pl-restauracje.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/pl/food/)
