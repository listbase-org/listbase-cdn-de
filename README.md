# ListBase CDN — Deutsch (de)

Open dataset collection for **Deutsch** (German).
465 datasets across 15 categories with 1,865,250 total records.

> Browse and download at [https://listbase.org/de/](https://listbase.org/de/)

## Categories

| Category | Datasets |
|----------|----------|
| [Kultur und Religion (Culture & Religion)](culture/) | 15 |
| [Bildung (Education)](education/) | 18 |
| [Unterhaltung (Entertainment)](entertainment/) | 19 |
| [Umwelt (Environment)](environment/) | 11 |
| [Finanzen und Handel (Finance & Trade)](finance/) | 26 |
| [Essen (Food & Nutrition)](food/) | 1 |
| [Geographie (Geography)](geography/) | 48 |
| [Gesundheit (Health)](health/) | 1 |
| [Sprache (Language)](language/) | 2 |
| [Referenz (Reference)](reference/) | 206 |
| [Sport (Sports)](sports/) | 32 |
| [Technologie (Technology)](tech/) | 11 |
| [Zeit und Kalender (Time & Calendar)](time/) | 31 |
| [Transport](transport/) | 23 |
| [Einheiten und Maße (Units & Measurements)](units/) | 21 |

## Usage

### Browse on the web
Visit [listbase.org/de/](https://listbase.org/de/) to search, preview, and download in Excel, CSV, or PDF.

### Fetch via CDN
```bash
# Dataset index (metadata only)
curl https://cdn.de.listbase.org/index.json

# Full dataset (JSON)
curl https://cdn.de.listbase.org/geography/th-central-provinces.json

# Download as Excel or CSV
curl -O https://cdn.de.listbase.org/geography/th-central-provinces_DE.xlsx
curl -O https://cdn.de.listbase.org/geography/th-central-provinces_DE.csv

# Build dump (metadata + sample rows, gzipped)
curl https://cdn.de.listbase.org/dump.json.gz | gunzip
```

### Use in JavaScript
```js
const res = await fetch('https://cdn.de.listbase.org/geography/th-central-provinces.json');
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
│   ├── {dataset}_DE.csv   # CSV download
│   └── {dataset}_DE.xlsx  # Excel download
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
