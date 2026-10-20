# Muzyka (Music)

2 datasets — 162 records

> Browse at [listbase.org/pl/music/](https://listbase.org/pl/music/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Zestaw Danych Referencyjnych Tabela Akordów Pianino](music-piano-chords.json) | 84 | 22 KB | [CSV](music-piano-chords_PL.csv) | [Excel](music-piano-chords_PL.xlsx) | [View](https://listbase.org/pl/music/music-piano-chords/) |
| [Kompleksowy Zbiór Danych Akordów Gitarowych](music-guitar-chords.json) | 78 | 24 KB | [CSV](music-guitar-chords_PL.csv) | [Excel](music-guitar-chords_PL.xlsx) | [View](https://listbase.org/pl/music/music-guitar-chords/) |

## Quick Start

```bash
# List all music datasets
curl https://cdn.pl.listbase.org/index.json | jq '.datasets[] | select(.category=="music") | .id'

# Fetch a dataset
curl https://cdn.pl.listbase.org/music/music-piano-chords.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/pl/music/)
