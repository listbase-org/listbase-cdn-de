# Umwelt (Environment)

11 datasets — 281,532 records

> Browse at [listbase.org/de/environment/](https://listbase.org/de/environment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Kraftwerke in Deutschland (Stromerzeugungsanlagen)](de-kraftwerke.json) | 141,420 | 71671 KB | [CSV](de-kraftwerke_DE.csv) | [Excel](de-kraftwerke_DE.xlsx) | [View](https://listbase.org/de/environment/de-kraftwerke/) |
| [Solaranlagen (Photovoltaik) in Deutschland](de-solaranlagen.json) | 70,901 | 35629 KB | [CSV](de-solaranlagen_DE.csv) | [Excel](de-solaranlagen_DE.xlsx) | [View](https://listbase.org/de/environment/de-solaranlagen/) |
| [Windkraftanlagen in Deutschland](de-windkraftanlagen.json) | 36,621 | 18495 KB | [CSV](de-windkraftanlagen_DE.csv) | [Excel](de-windkraftanlagen_DE.xlsx) | [View](https://listbase.org/de/environment/de-windkraftanlagen/) |
| [Biogasanlagen in Deutschland](de-biogasanlagen.json) | 18,039 | 9260 KB | [CSV](de-biogasanlagen_DE.csv) | [Excel](de-biogasanlagen_DE.xlsx) | [View](https://listbase.org/de/environment/de-biogasanlagen/) |
| [Gaskraftwerke in Deutschland](de-gaskraftwerke.json) | 6,984 | 3666 KB | [CSV](de-gaskraftwerke_DE.csv) | [Excel](de-gaskraftwerke_DE.xlsx) | [View](https://listbase.org/de/environment/de-gaskraftwerke/) |
| [Ölkraftwerke in Deutschland](de-oelkraftwerke.json) | 4,058 | 2116 KB | [CSV](de-oelkraftwerke_DE.csv) | [Excel](de-oelkraftwerke_DE.xlsx) | [View](https://listbase.org/de/environment/de-oelkraftwerke/) |
| [Wasserkraftwerke in Deutschland](de-wasserkraftwerke.json) | 2,286 | 1191 KB | [CSV](de-wasserkraftwerke_DE.csv) | [Excel](de-wasserkraftwerke_DE.xlsx) | [View](https://listbase.org/de/environment/de-wasserkraftwerke/) |
| [Batteriespeicher in Deutschland](de-batteriespeicher.json) | 1,167 | 616 KB | [CSV](de-batteriespeicher_DE.csv) | [Excel](de-batteriespeicher_DE.xlsx) | [View](https://listbase.org/de/environment/de-batteriespeicher/) |
| [Kernkraftwerke in Deutschland](de-kernkraftwerke.json) | 37 | 17 KB | [CSV](de-kernkraftwerke_DE.csv) | [Excel](de-kernkraftwerke_DE.xlsx) | [View](https://listbase.org/de/environment/de-kernkraftwerke/) |
| [Maßeinheiten — Kategorie 'energy' (14)](de-masseinheiten-energy.json) | 14 | 5 KB | [CSV](de-masseinheiten-energy_DE.csv) | [Excel](de-masseinheiten-energy_DE.xlsx) | [View](https://listbase.org/de/environment/de-masseinheiten-energy/) |
| [Maßeinheiten — Kategorie 'temperature' (5)](de-masseinheiten-temperature.json) | 5 | 3 KB | [CSV](de-masseinheiten-temperature_DE.csv) | [Excel](de-masseinheiten-temperature_DE.xlsx) | [View](https://listbase.org/de/environment/de-masseinheiten-temperature/) |

## Quick Start

```bash
# List all environment datasets
curl https://cdn.de.listbase.org/index.json | jq '.datasets[] | select(.category=="environment") | .id'

# Fetch a dataset
curl https://cdn.de.listbase.org/environment/de-kraftwerke.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/de/environment/)
