# Sprache (Language)

2 datasets — 760 records

> Browse at [listbase.org/de/language/](https://listbase.org/de/language/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Sprachen der Welt (591)](de-sprachen.json) | 591 | 55 KB | [CSV](de-sprachen_DE.csv) | [Excel](de-sprachen_DE.xlsx) | [View](https://listbase.org/de/language/de-sprachen/) |
| [Schriftsysteme der Welt (ISO 15924 / CLDR deutsch)](de-schriftsysteme.json) | 169 | 14 KB | [CSV](de-schriftsysteme_DE.csv) | [Excel](de-schriftsysteme_DE.xlsx) | [View](https://listbase.org/de/language/de-schriftsysteme/) |

## Quick Start

```bash
# List all language datasets
curl https://cdn.de.listbase.org/index.json | jq '.datasets[] | select(.category=="language") | .id'

# Fetch a dataset
curl https://cdn.de.listbase.org/language/de-sprachen.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/de/language/)
