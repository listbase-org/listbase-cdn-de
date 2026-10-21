# Gesundheit (Health)

1 datasets — 1,218 records

> Browse at [listbase.org/de/health/](https://listbase.org/de/health/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Krankenhäuser in Deutschland / Hospitals in Germany](de-krankenhaeuser.json) | 1,218 | 337 KB | [CSV](de-krankenhaeuser_DE.csv) | [Excel](de-krankenhaeuser_DE.xlsx) | [View](https://listbase.org/de/health/de-krankenhaeuser/) |

## Quick Start

```bash
# List all health datasets
curl https://cdn.de.listbase.org/index.json | jq '.datasets[] | select(.category=="health") | .id'

# Fetch a dataset
curl https://cdn.de.listbase.org/health/de-krankenhaeuser.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/de/health/)
