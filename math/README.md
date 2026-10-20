# Matematyka (Mathematics)

3 datasets — 152 records

> Browse at [listbase.org/pl/math/](https://listbase.org/pl/math/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Zbiór Danych Wzorów na Pochodne i Reguł Różniczkowania](math-derivative-formulas.json) | 57 | 13 KB | [CSV](math-derivative-formulas_PL.csv) | [Excel](math-derivative-formulas_PL.xlsx) | [View](https://listbase.org/pl/math/math-derivative-formulas/) |
| [Zbiór danych Powszechnych Wzorów Całkowych](math-integral-formulas.json) | 56 | 13 KB | [CSV](math-integral-formulas_PL.csv) | [Excel](math-integral-formulas_PL.xlsx) | [View](https://listbase.org/pl/math/math-integral-formulas/) |
| [Kompleksowy Zbiór Danych Tabeli Transformacji Laplace'a](math-laplace-transform.json) | 39 | 9 KB | [CSV](math-laplace-transform_PL.csv) | [Excel](math-laplace-transform_PL.xlsx) | [View](https://listbase.org/pl/math/math-laplace-transform/) |

## Quick Start

```bash
# List all mathematics datasets
curl https://cdn.pl.listbase.org/index.json | jq '.datasets[] | select(.category=="math") | .id'

# Fetch a dataset
curl https://cdn.pl.listbase.org/math/math-derivative-formulas.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/pl/math/)
