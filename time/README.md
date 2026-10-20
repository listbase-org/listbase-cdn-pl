# Czas i Kalendarz (Time & Calendar)

4 datasets — 122 records

> Browse at [listbase.org/pl/time/](https://listbase.org/pl/time/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Nazwy miesięcy według kalendarza (CLDR polski)](pl-miesiace-kalendarze.json) | 74 | 13 KB | [CSV](pl-miesiace-kalendarze_PL.csv) | [Excel](pl-miesiace-kalendarze_PL.xlsx) | [View](https://listbase.org/pl/time/pl-miesiace-kalendarze/) |
| [Dni, kwartały, pory dnia i ery — nazwy po polsku (CLDR)](pl-dni-kwartaly-ery.json) | 24 | 4 KB | [CSV](pl-dni-kwartaly-ery_PL.csv) | [Excel](pl-dni-kwartaly-ery_PL.xlsx) | [View](https://listbase.org/pl/time/pl-dni-kwartaly-ery/) |
| [Kompleksowy Zbiór Danych Zwierząt Chińskiego Zodiaku (12 Znaków)](time-chinese-zodiac.json) | 12 | 11 KB | [CSV](time-chinese-zodiac_PL.csv) | [Excel](time-chinese-zodiac_PL.xlsx) | [View](https://listbase.org/pl/time/time-chinese-zodiac/) |
| [Kompletny Zestaw Danych Zachodnich Znaków Zodiaku](time-zodiac-signs.json) | 12 | 9 KB | [CSV](time-zodiac-signs_PL.csv) | [Excel](time-zodiac-signs_PL.xlsx) | [View](https://listbase.org/pl/time/time-zodiac-signs/) |

## Quick Start

```bash
# List all time & calendar datasets
curl https://cdn.pl.listbase.org/index.json | jq '.datasets[] | select(.category=="time") | .id'

# Fetch a dataset
curl https://cdn.pl.listbase.org/time/pl-miesiace-kalendarze.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/pl/time/)
