# Język (Language)

6 datasets — 734 records

> Browse at [listbase.org/pl/language/](https://listbase.org/pl/language/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Kompleksowa Tabela Sylab Pinyin Chińskich i Przewodnik Wymowy](lang-pinyin-table.json) | 408 | 101 KB | [CSV](lang-pinyin-table_PL.csv) | [Excel](lang-pinyin-table_PL.xlsx) | [View](https://listbase.org/pl/language/lang-pinyin-table/) |
| [Systemy pisma świata (ISO 15924 / CLDR polski)](pl-systemy-pisma.json) | 141 | 12 KB | [CSV](pl-systemy-pisma_PL.csv) | [Excel](pl-systemy-pisma_PL.xlsx) | [View](https://listbase.org/pl/language/pl-systemy-pisma/) |
| [Zbiór Danych: Tabela Klasyfikacji Zaimków Angielskich](lang-english-pronouns.json) | 69 | 21 KB | [CSV](lang-english-pronouns_PL.csv) | [Excel](lang-english-pronouns_PL.xlsx) | [View](https://listbase.org/pl/language/lang-english-pronouns/) |
| [Zbiór Danych Japońskiej Tabeli Hiragany i Mapowania Romaji](lang-hiragana-table.json) | 46 | 11 KB | [CSV](lang-hiragana-table_PL.csv) | [Excel](lang-hiragana-table_PL.xlsx) | [View](https://listbase.org/pl/language/lang-hiragana-table/) |
| [Kompletny Zestaw Danych Tabeli Znaków Katakany Japońskiej](lang-katakana-table.json) | 46 | 11 KB | [CSV](lang-katakana-table_PL.csv) | [Excel](lang-katakana-table_PL.xlsx) | [View](https://listbase.org/pl/language/lang-katakana-table/) |
| [Kompletny Zbiór Danych Znaków Alfabetu Greckiego](lang-greek-alphabet.json) | 24 | 9 KB | [CSV](lang-greek-alphabet_PL.csv) | [Excel](lang-greek-alphabet_PL.xlsx) | [View](https://listbase.org/pl/language/lang-greek-alphabet/) |

## Quick Start

```bash
# List all language datasets
curl https://cdn.pl.listbase.org/index.json | jq '.datasets[] | select(.category=="language") | .id'

# Fetch a dataset
curl https://cdn.pl.listbase.org/language/lang-pinyin-table.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/pl/language/)
