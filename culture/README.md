# Kultur und Religion (Culture & Religion)

15 datasets — 22,685 records

> Browse at [listbase.org/de/culture/](https://listbase.org/de/culture/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Museen im deutschsprachigen Raum (Museums in German-speaking countries)](de-museen.json) | 5,054 | 1090 KB | [CSV](de-museen_DE.csv) | [Excel](de-museen_DE.xlsx) | [View](https://listbase.org/de/culture/de-museen/) |
| [Klöster in Deutschland / Monasteries in Germany](de-kloester.json) | 4,509 | 1225 KB | [CSV](de-kloester_DE.csv) | [Excel](de-kloester_DE.xlsx) | [View](https://listbase.org/de/culture/de-kloester/) |
| [Burgen in Deutschland / Castles in Germany](de-burgen.json) | 4,393 | 1134 KB | [CSV](de-burgen_DE.csv) | [Excel](de-burgen_DE.xlsx) | [View](https://listbase.org/de/culture/de-burgen/) |
| [Bibliotheken in Deutschland / Libraries in Germany](de-bibliotheken.json) | 2,312 | 658 KB | [CSV](de-bibliotheken_DE.csv) | [Excel](de-bibliotheken_DE.xlsx) | [View](https://listbase.org/de/culture/de-bibliotheken/) |
| [Kinos in Deutschland / Cinemas in Germany](de-kinos.json) | 2,180 | 554 KB | [CSV](de-kinos_DE.csv) | [Excel](de-kinos_DE.xlsx) | [View](https://listbase.org/de/culture/de-kinos/) |
| [Statuen in Deutschland / Statues in Germany](de-statuen.json) | 1,276 | 335 KB | [CSV](de-statuen_DE.csv) | [Excel](de-statuen_DE.xlsx) | [View](https://listbase.org/de/culture/de-statuen/) |
| [Theater in Deutschland / Theatres in Germany](de-theater.json) | 973 | 252 KB | [CSV](de-theater_DE.csv) | [Excel](de-theater_DE.xlsx) | [View](https://listbase.org/de/culture/de-theater/) |
| [Synagogen in Deutschland / Synagogues in Germany](de-synagogen.json) | 830 | 216 KB | [CSV](de-synagogen_DE.csv) | [Excel](de-synagogen_DE.xlsx) | [View](https://listbase.org/de/culture/de-synagogen/) |
| [Windmühlen in Deutschland / Windmills in Germany](de-windmuehlen.json) | 467 | 122 KB | [CSV](de-windmuehlen_DE.csv) | [Excel](de-windmuehlen_DE.xlsx) | [View](https://listbase.org/de/culture/de-windmuehlen/) |
| [Leuchttürme in Deutschland / Lighthouses in Germany](de-leuchttuerme.json) | 208 | 57 KB | [CSV](de-leuchttuerme_DE.csv) | [Excel](de-leuchttuerme_DE.xlsx) | [View](https://listbase.org/de/culture/de-leuchttuerme/) |
| [Paläste in Deutschland / Palaces in Germany](de-palaeste.json) | 148 | 40 KB | [CSV](de-palaeste_DE.csv) | [Excel](de-palaeste_DE.xlsx) | [View](https://listbase.org/de/culture/de-palaeste/) |
| [Abteien in Deutschland / Abbeys in Germany](de-abteien.json) | 132 | 36 KB | [CSV](de-abteien_DE.csv) | [Excel](de-abteien_DE.xlsx) | [View](https://listbase.org/de/culture/de-abteien/) |
| [Moscheen in Deutschland / Mosques in Germany](de-moscheen.json) | 98 | 27 KB | [CSV](de-moscheen_DE.csv) | [Excel](de-moscheen_DE.xlsx) | [View](https://listbase.org/de/culture/de-moscheen/) |
| [Festungen in Deutschland / Fortresses in Germany](de-festungen.json) | 59 | 17 KB | [CSV](de-festungen_DE.csv) | [Excel](de-festungen_DE.xlsx) | [View](https://listbase.org/de/culture/de-festungen/) |
| [UNESCO-Welterbestätten in Deutschland](de-unesco-welterbe.json) | 46 | 48 KB | [CSV](de-unesco-welterbe_DE.csv) | [Excel](de-unesco-welterbe_DE.xlsx) | [View](https://listbase.org/de/culture/de-unesco-welterbe/) |

## Quick Start

```bash
# List all culture & religion datasets
curl https://cdn.de.listbase.org/index.json | jq '.datasets[] | select(.category=="culture") | .id'

# Fetch a dataset
curl https://cdn.de.listbase.org/culture/de-museen.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/de/culture/)
