# Technologie (Technology)

11 datasets — 2,266 records

> Browse at [listbase.org/de/tech/](https://listbase.org/de/tech/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Emoji — Namen auf Deutsch (CLDR)](de-emoji-namen.json) | 1,966 | 324 KB | [CSV](de-emoji-namen_DE.csv) | [Excel](de-emoji-namen_DE.xlsx) | [View](https://listbase.org/de/tech/de-emoji-namen/) |
| [Zeitzonen der Welt (IANA / CLDR deutsch)](de-zeitzonen.json) | 150 | 26 KB | [CSV](de-zeitzonen_DE.csv) | [Excel](de-zeitzonen_DE.xlsx) | [View](https://listbase.org/de/tech/de-zeitzonen/) |
| [Zeitzonen — America (45)](de-zeitzonen-america.json) | 45 | 9 KB | [CSV](de-zeitzonen-america_DE.csv) | [Excel](de-zeitzonen-america_DE.xlsx) | [View](https://listbase.org/de/tech/de-zeitzonen-america/) |
| [Zeitzonen — Asia (40)](de-zeitzonen-asia.json) | 40 | 8 KB | [CSV](de-zeitzonen-asia_DE.csv) | [Excel](de-zeitzonen-asia_DE.xlsx) | [View](https://listbase.org/de/tech/de-zeitzonen-asia/) |
| [Zeitzonen — Europe (25)](de-zeitzonen-europe.json) | 25 | 5 KB | [CSV](de-zeitzonen-europe_DE.csv) | [Excel](de-zeitzonen-europe_DE.xlsx) | [View](https://listbase.org/de/tech/de-zeitzonen-europe/) |
| [Zeitzonen — Africa (14)](de-zeitzonen-africa.json) | 14 | 4 KB | [CSV](de-zeitzonen-africa_DE.csv) | [Excel](de-zeitzonen-africa_DE.xlsx) | [View](https://listbase.org/de/tech/de-zeitzonen-africa/) |
| [Zeitzonen — Pacific (9)](de-zeitzonen-pacific.json) | 9 | 3 KB | [CSV](de-zeitzonen-pacific_DE.csv) | [Excel](de-zeitzonen-pacific_DE.xlsx) | [View](https://listbase.org/de/tech/de-zeitzonen-pacific/) |
| [Zeitzonen — Atlantic (7)](de-zeitzonen-atlantic.json) | 7 | 3 KB | [CSV](de-zeitzonen-atlantic_DE.csv) | [Excel](de-zeitzonen-atlantic_DE.xlsx) | [View](https://listbase.org/de/tech/de-zeitzonen-atlantic/) |
| [Zeitzonen — Indian (5)](de-zeitzonen-indian.json) | 5 | 2 KB | [CSV](de-zeitzonen-indian_DE.csv) | [Excel](de-zeitzonen-indian_DE.xlsx) | [View](https://listbase.org/de/tech/de-zeitzonen-indian/) |
| [Zeitzonen — Antarctica (3)](de-zeitzonen-antarctica.json) | 3 | 2 KB | [CSV](de-zeitzonen-antarctica_DE.csv) | [Excel](de-zeitzonen-antarctica_DE.xlsx) | [View](https://listbase.org/de/tech/de-zeitzonen-antarctica/) |
| [Zeitzonen — Etc (2)](de-zeitzonen-etc.json) | 2 | 2 KB | [CSV](de-zeitzonen-etc_DE.csv) | [Excel](de-zeitzonen-etc_DE.xlsx) | [View](https://listbase.org/de/tech/de-zeitzonen-etc/) |

## Quick Start

```bash
# List all technology datasets
curl https://cdn.de.listbase.org/index.json | jq '.datasets[] | select(.category=="tech") | .id'

# Fetch a dataset
curl https://cdn.de.listbase.org/tech/de-emoji-namen.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/de/tech/)
