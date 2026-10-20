# Nauka (Science)

9 datasets — 405 records

> Browse at [listbase.org/pl/science/](https://listbase.org/pl/science/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Kompleksowy Zbiór Danych Tabeli Okresowej Pierwiastków](science-periodic-table.json) | 118 | 39 KB | [CSV](science-periodic-table_PL.csv) | [Excel](science-periodic-table_PL.xlsx) | [View](https://listbase.org/pl/science/science-periodic-table/) |
| [Kompletny Zbiór Danych Tabela Kodonów RNA](science-codon-table.json) | 64 | 13 KB | [CSV](science-codon-table_PL.csv) | [Excel](science-codon-table_PL.xlsx) | [View](https://listbase.org/pl/science/science-codon-table/) |
| [Zbiór Danych Tabela Elektroujemności (Skala Paulinga)](science-electronegativity.json) | 62 | 17 KB | [CSV](science-electronegativity_PL.csv) | [Excel](science-electronegativity_PL.xlsx) | [View](https://listbase.org/pl/science/science-electronegativity/) |
| [Zbiór danych Międzynarodowego Układu Jednostek Miar (Jednostki SI)](science-si-units.json) | 53 | 13 KB | [CSV](science-si-units_PL.csv) | [Excel](science-si-units_PL.xlsx) | [View](https://listbase.org/pl/science/science-si-units/) |
| [Zbiór Danych Referencyjnych Skali pH i Właściwości Chemicznych](science-ph-scale.json) | 33 | 8 KB | [CSV](science-ph-scale_PL.csv) | [Excel](science-ph-scale_PL.xlsx) | [View](https://listbase.org/pl/science/science-ph-scale/) |
| [Kompleksowy Zestaw Danych Tabela Zasad Rozpuszczalności](science-solubility-rules.json) | 31 | 12 KB | [CSV](science-solubility-rules_PL.csv) | [Excel](science-solubility-rules_PL.xlsx) | [View](https://listbase.org/pl/science/science-solubility-rules/) |
| [Kompleksowy Zbiór Danych o Właściwościach Aminokwasów](science-amino-acids.json) | 22 | 10 KB | [CSV](science-amino-acids_PL.csv) | [Excel](science-amino-acids_PL.xlsx) | [View](https://listbase.org/pl/science/science-amino-acids/) |
| [Kompleksowy Zestaw Danych Tabela Zgodności Grup Krwi](science-blood-types.json) | 11 | 6 KB | [CSV](science-blood-types_PL.csv) | [Excel](science-blood-types_PL.xlsx) | [View](https://listbase.org/pl/science/science-blood-types/) |
| [Zestaw Danych Planet i Ciał Niebieskich Układu Słonecznego](science-planet-data.json) | 11 | 10 KB | [CSV](science-planet-data_PL.csv) | [Excel](science-planet-data_PL.xlsx) | [View](https://listbase.org/pl/science/science-planet-data/) |

## Quick Start

```bash
# List all science datasets
curl https://cdn.pl.listbase.org/index.json | jq '.datasets[] | select(.category=="science") | .id'

# Fetch a dataset
curl https://cdn.pl.listbase.org/science/science-periodic-table.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/pl/science/)
