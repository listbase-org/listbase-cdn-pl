# Kultura i Religia (Culture & Religion)

4 datasets — 19,098 records

> Browse at [listbase.org/pl/culture/](https://listbase.org/pl/culture/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Miejsca kultu religijnego w Polsce (Places of worship, OSM)](pl-miejsca-kultu.json) | 18,104 | 2264 KB | [CSV](pl-miejsca-kultu_PL.csv) | [Excel](pl-miejsca-kultu_PL.xlsx) | [View](https://listbase.org/pl/culture/pl-miejsca-kultu/) |
| [Muzea w Polsce (Museums in Poland)](pl-muzea.json) | 710 | 156 KB | [CSV](pl-muzea_PL.csv) | [Excel](pl-muzea_PL.xlsx) | [View](https://listbase.org/pl/culture/pl-muzea/) |
| [Polska — sklepy z artykułami plastycznymi](pl-sklepy-z-artykulami-plastycznymi.json) | 268 | 29 KB | [CSV](pl-sklepy-z-artykulami-plastycznymi_PL.csv) | [Excel](pl-sklepy-z-artykulami-plastycznymi_PL.xlsx) | [View](https://listbase.org/pl/culture/pl-sklepy-z-artykulami-plastycznymi/) |
| [Obiekty światowego dziedzictwa UNESCO w Polsce](pl-obiekty-swiatowego-dziedzictwa-unesco.json) | 16 | 18 KB | [CSV](pl-obiekty-swiatowego-dziedzictwa-unesco_PL.csv) | [Excel](pl-obiekty-swiatowego-dziedzictwa-unesco_PL.xlsx) | [View](https://listbase.org/pl/culture/pl-obiekty-swiatowego-dziedzictwa-unesco/) |

## Quick Start

```bash
# List all culture & religion datasets
curl https://cdn.pl.listbase.org/index.json | jq '.datasets[] | select(.category=="culture") | .id'

# Fetch a dataset
curl https://cdn.pl.listbase.org/culture/pl-miejsca-kultu.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/pl/culture/)
