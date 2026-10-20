# ListBase CDN — Polski (pl)

Open dataset collection for **Polski** (Polish).
476 datasets across 20 categories with 1,089,440 total records.

> Browse and download at [https://listbase.org/pl/](https://listbase.org/pl/)

## Categories

| Category | Datasets |
|----------|----------|
| [Kultura i Religia (Culture & Religion)](culture/) | 4 |
| [Edukacja (Education)](education/) | 3 |
| [Rozrywka (Entertainment)](entertainment/) | 1 |
| [Środowisko (Environment)](environment/) | 9 |
| [Finanse i Handel (Finance & Trade)](finance/) | 6 |
| [Żywność i Odżywianie (Food & Nutrition)](food/) | 5 |
| [Geografia (Geography)](geography/) | 73 |
| [Zdrowie (Health)](health/) | 1 |
| [Język (Language)](language/) | 6 |
| [Matematyka (Mathematics)](math/) | 3 |
| [Muzyka (Music)](music/) | 2 |
| [Referencje (Reference)](reference/) | 293 |
| [Nauka (Science)](science/) | 9 |
| [Społeczeństwo (Society)](society/) | 1 |
| [Sport (Sports)](sports/) | 1 |
| [Technologia (Technology)](tech/) | 24 |
| [Czas i Kalendarz (Time & Calendar)](time/) | 4 |
| [Turystyka (Tourism)](tourism/) | 3 |
| [Transport](transport/) | 3 |
| [Jednostki i Miary (Units & Measurements)](units/) | 25 |

## Usage

### Browse on the web
Visit [listbase.org/pl/](https://listbase.org/pl/) to search, preview, and download in Excel, CSV, or PDF.

### Fetch via CDN
```bash
# Dataset index (metadata only)
curl https://cdn.pl.listbase.org/index.json

# Full dataset (JSON)
curl https://cdn.pl.listbase.org/geography/th-central-provinces.json

# Download as Excel or CSV
curl -O https://cdn.pl.listbase.org/geography/th-central-provinces_PL.xlsx
curl -O https://cdn.pl.listbase.org/geography/th-central-provinces_PL.csv

# Build dump (metadata + sample rows, gzipped)
curl https://cdn.pl.listbase.org/dump.json.gz | gunzip
```

### Use in JavaScript
```js
const res = await fetch('https://cdn.pl.listbase.org/geography/th-central-provinces.json');
const data = await res.json();
console.log(data.name);    // "ภาคกลาง — จังหวัดในภาคกลาง"
console.log(data.rows);    // [{ ... }, ...]
```

## File Structure

```
├── index.json              # Dataset index (metadata + file info)
├── dump.json.gz            # Build dump (metadata + 20 sample rows per dataset)
├── {category}/
│   ├── README.md           # Category overview
│   ├── {dataset}.json      # Full dataset with rows
│   ├── {dataset}_PL.csv   # CSV download
│   └── {dataset}_PL.xlsx  # Excel download
```

## Dataset JSON Format

Each `.json` file contains:

| Field | Description |
|-------|-------------|
| `id` | Unique dataset identifier |
| `name` | Dataset name |
| `description` | What this dataset contains |
| `category` | Category (e.g. geography, finance) |
| `source` | Data source attribution |
| `updated` | Last updated date |
| `record_count` | Number of records |
| `columns` | Column definitions (key, label, type) |
| `rows` | Array of data records |

## License

Data is provided under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
See individual dataset `source` fields for original data attribution.

---

Part of [ListBase](https://listbase.org) — Free Reference Tables & Lists
