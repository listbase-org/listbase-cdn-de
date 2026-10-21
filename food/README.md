# Essen (Food & Nutrition)

1 datasets — 1,254 records

> Browse at [listbase.org/de/food/](https://listbase.org/de/food/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Michelin-Restaurants in Deutschland](de-michelin-restaurants.json) | 1,254 | 1531 KB | [CSV](de-michelin-restaurants_DE.csv) | [Excel](de-michelin-restaurants_DE.xlsx) | [View](https://listbase.org/de/food/de-michelin-restaurants/) |

## Quick Start

```bash
# List all food & nutrition datasets
curl https://cdn.de.listbase.org/index.json | jq '.datasets[] | select(.category=="food") | .id'

# Fetch a dataset
curl https://cdn.de.listbase.org/food/de-michelin-restaurants.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/de/food/)
