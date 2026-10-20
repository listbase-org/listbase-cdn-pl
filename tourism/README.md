# Turystyka (Tourism)

3 datasets — 32,703 records

> Browse at [listbase.org/pl/tourism/](https://listbase.org/pl/tourism/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Punkty informacji turystycznej w Polsce (Tourist information, OSM)](pl-punkty-informacji-turystycznej.json) | 20,418 | 2260 KB | [CSV](pl-punkty-informacji-turystycznej_PL.csv) | [Excel](pl-punkty-informacji-turystycznej_PL.xlsx) | [View](https://listbase.org/pl/tourism/pl-punkty-informacji-turystycznej/) |
| [Pensjonaty i kwatery w Polsce (Guest houses in Poland, OSM)](pl-pensjonaty.json) | 6,832 | 706 KB | [CSV](pl-pensjonaty_PL.csv) | [Excel](pl-pensjonaty_PL.xlsx) | [View](https://listbase.org/pl/tourism/pl-pensjonaty/) |
| [Hotele w Polsce (Hotels in Poland, OSM)](pl-hotele.json) | 5,453 | 556 KB | [CSV](pl-hotele_PL.csv) | [Excel](pl-hotele_PL.xlsx) | [View](https://listbase.org/pl/tourism/pl-hotele/) |

## Quick Start

```bash
# List all tourism datasets
curl https://cdn.pl.listbase.org/index.json | jq '.datasets[] | select(.category=="tourism") | .id'

# Fetch a dataset
curl https://cdn.pl.listbase.org/tourism/pl-punkty-informacji-turystycznej.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/pl/tourism/)
