# Finanse i Handel (Finance & Trade)

6 datasets — 350 records

> Browse at [listbase.org/pl/finance/](https://listbase.org/pl/finance/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Zbiór Danych Rejestru Prefiksów Kodów Kreskowych i Krajów GS1](finance-gs1-codes.json) | 126 | 19 KB | [CSV](finance-gs1-codes_PL.csv) | [Excel](finance-gs1-codes_PL.xlsx) | [View](https://listbase.org/pl/finance/finance-gs1-codes/) |
| [Zbiór Danych Rozdziałów Kodów HS (System Zharmonizowany)](finance-hs-codes.json) | 98 | 22 KB | [CSV](finance-hs-codes_PL.csv) | [Excel](finance-hs-codes_PL.xlsx) | [View](https://listbase.org/pl/finance/finance-hs-codes/) |
| [Kompleksowy Zestaw Danych Stawek VAT/GST według Krajów](finance-vat-rates.json) | 75 | 18 KB | [CSV](finance-vat-rates_PL.csv) | [Excel](finance-vat-rates_PL.xlsx) | [View](https://listbase.org/pl/finance/finance-vat-rates/) |
| [Elektrownie gazowe w Polsce](pl-gazowe-elektrownie.json) | 26 | 16 KB | [CSV](pl-gazowe-elektrownie_PL.csv) | [Excel](pl-gazowe-elektrownie_PL.xlsx) | [View](https://listbase.org/pl/finance/pl-gazowe-elektrownie/) |
| [Zestaw Danych Kodów i Specyfikacji Kontenerów Wysyłkowych ISO 6346](finance-container-codes.json) | 14 | 8 KB | [CSV](finance-container-codes_PL.csv) | [Excel](finance-container-codes_PL.xlsx) | [View](https://listbase.org/pl/finance/finance-container-codes/) |
| [Zbiór Danych Reguł i Definicji Incoterms 2020](finance-incoterms.json) | 11 | 8 KB | [CSV](finance-incoterms_PL.csv) | [Excel](finance-incoterms_PL.xlsx) | [View](https://listbase.org/pl/finance/finance-incoterms/) |

## Quick Start

```bash
# List all finance & trade datasets
curl https://cdn.pl.listbase.org/index.json | jq '.datasets[] | select(.category=="finance") | .id'

# Fetch a dataset
curl https://cdn.pl.listbase.org/finance/finance-gs1-codes.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/pl/finance/)
