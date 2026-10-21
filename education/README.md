# Bildung (Education)

18 datasets — 1,173 records

> Browse at [listbase.org/de/education/](https://listbase.org/de/education/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Deutschland — Universitäten und Hochschulen (Typ, Träger, Promotionsrecht, Studierendenzahlen)](de-universitaeten.json) | 427 | 218 KB | [CSV](de-universitaeten_DE.csv) | [Excel](de-universitaeten_DE.xlsx) | [View](https://listbase.org/de/education/de-universitaeten/) |
| [Deutschland — Hochschulen und Universitäten](de-hochschulen.json) | 319 | 104 KB | [CSV](de-hochschulen_DE.csv) | [Excel](de-hochschulen_DE.xlsx) | [View](https://listbase.org/de/education/de-hochschulen/) |
| [Baden-Württemberg — Universitäten und Hochschulen](de-baden-wuerttemberg-universitaeten.json) | 76 | 42 KB | [CSV](de-baden-wuerttemberg-universitaeten_DE.csv) | [Excel](de-baden-wuerttemberg-universitaeten_DE.xlsx) | [View](https://listbase.org/de/education/de-baden-wuerttemberg-universitaeten/) |
| [Nordrhein-Westfalen — Universitäten und Hochschulen](de-nordrhein-westfalen-universitaeten.json) | 69 | 39 KB | [CSV](de-nordrhein-westfalen-universitaeten_DE.csv) | [Excel](de-nordrhein-westfalen-universitaeten_DE.xlsx) | [View](https://listbase.org/de/education/de-nordrhein-westfalen-universitaeten/) |
| [Bayern — Universitäten und Hochschulen](de-bayern-universitaeten.json) | 48 | 26 KB | [CSV](de-bayern-universitaeten_DE.csv) | [Excel](de-bayern-universitaeten_DE.xlsx) | [View](https://listbase.org/de/education/de-bayern-universitaeten/) |
| [Berlin — Universitäten und Hochschulen](de-berlin-universitaeten.json) | 38 | 21 KB | [CSV](de-berlin-universitaeten_DE.csv) | [Excel](de-berlin-universitaeten_DE.xlsx) | [View](https://listbase.org/de/education/de-berlin-universitaeten/) |
| [Hessen — Universitäten und Hochschulen](de-hessen-universitaeten.json) | 34 | 19 KB | [CSV](de-hessen-universitaeten_DE.csv) | [Excel](de-hessen-universitaeten_DE.xlsx) | [View](https://listbase.org/de/education/de-hessen-universitaeten/) |
| [Niedersachsen — Universitäten und Hochschulen](de-niedersachsen-universitaeten.json) | 29 | 17 KB | [CSV](de-niedersachsen-universitaeten_DE.csv) | [Excel](de-niedersachsen-universitaeten_DE.xlsx) | [View](https://listbase.org/de/education/de-niedersachsen-universitaeten/) |
| [Sachsen — Universitäten und Hochschulen](de-sachsen-universitaeten.json) | 24 | 14 KB | [CSV](de-sachsen-universitaeten_DE.csv) | [Excel](de-sachsen-universitaeten_DE.xlsx) | [View](https://listbase.org/de/education/de-sachsen-universitaeten/) |
| [Hamburg — Universitäten und Hochschulen](de-hamburg-universitaeten.json) | 21 | 13 KB | [CSV](de-hamburg-universitaeten_DE.csv) | [Excel](de-hamburg-universitaeten_DE.xlsx) | [View](https://listbase.org/de/education/de-hamburg-universitaeten/) |
| [Rheinland-Pfalz — Universitäten und Hochschulen](de-rheinland-pfalz-universitaeten.json) | 19 | 12 KB | [CSV](de-rheinland-pfalz-universitaeten_DE.csv) | [Excel](de-rheinland-pfalz-universitaeten_DE.xlsx) | [View](https://listbase.org/de/education/de-rheinland-pfalz-universitaeten/) |
| [Brandenburg — Universitäten und Hochschulen](de-brandenburg-universitaeten.json) | 13 | 9 KB | [CSV](de-brandenburg-universitaeten_DE.csv) | [Excel](de-brandenburg-universitaeten_DE.xlsx) | [View](https://listbase.org/de/education/de-brandenburg-universitaeten/) |
| [Thüringen — Universitäten und Hochschulen](de-thueringen-universitaeten.json) | 13 | 9 KB | [CSV](de-thueringen-universitaeten_DE.csv) | [Excel](de-thueringen-universitaeten_DE.xlsx) | [View](https://listbase.org/de/education/de-thueringen-universitaeten/) |
| [Schleswig-Holstein — Universitäten und Hochschulen](de-schleswig-holstein-universitaeten.json) | 12 | 9 KB | [CSV](de-schleswig-holstein-universitaeten_DE.csv) | [Excel](de-schleswig-holstein-universitaeten_DE.xlsx) | [View](https://listbase.org/de/education/de-schleswig-holstein-universitaeten/) |
| [Sachsen-Anhalt — Universitäten und Hochschulen](de-sachsen-anhalt-universitaeten.json) | 10 | 8 KB | [CSV](de-sachsen-anhalt-universitaeten_DE.csv) | [Excel](de-sachsen-anhalt-universitaeten_DE.xlsx) | [View](https://listbase.org/de/education/de-sachsen-anhalt-universitaeten/) |
| [Bremen — Universitäten und Hochschulen](de-bremen-universitaeten.json) | 8 | 6 KB | [CSV](de-bremen-universitaeten_DE.csv) | [Excel](de-bremen-universitaeten_DE.xlsx) | [View](https://listbase.org/de/education/de-bremen-universitaeten/) |
| [Mecklenburg-Vorpommern — Universitäten und Hochschulen](de-mecklenburg-vorpommern-universitaeten.json) | 7 | 6 KB | [CSV](de-mecklenburg-vorpommern-universitaeten_DE.csv) | [Excel](de-mecklenburg-vorpommern-universitaeten_DE.xlsx) | [View](https://listbase.org/de/education/de-mecklenburg-vorpommern-universitaeten/) |
| [Saarland — Universitäten und Hochschulen](de-saarland-universitaeten.json) | 6 | 6 KB | [CSV](de-saarland-universitaeten_DE.csv) | [Excel](de-saarland-universitaeten_DE.xlsx) | [View](https://listbase.org/de/education/de-saarland-universitaeten/) |

## Quick Start

```bash
# List all education datasets
curl https://cdn.de.listbase.org/index.json | jq '.datasets[] | select(.category=="education") | .id'

# Fetch a dataset
curl https://cdn.de.listbase.org/education/de-universitaeten.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/de/education/)
