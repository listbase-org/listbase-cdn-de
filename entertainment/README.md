# Unterhaltung (Entertainment)

19 datasets — 2,307 records

> Browse at [listbase.org/de/entertainment/](https://listbase.org/de/entertainment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Sendefeeds deutscher Fernsehsender (German TV channel feeds)](de-tv-sender-feeds.json) | 982 | 271 KB | [CSV](de-tv-sender-feeds_DE.csv) | [Excel](de-tv-sender-feeds_DE.xlsx) | [View](https://listbase.org/de/entertainment/de-tv-sender-feeds/) |
| [Deutsche Fernsehsender (German TV channels)](de-tv-sender.json) | 733 | 293 KB | [CSV](de-tv-sender_DE.csv) | [Excel](de-tv-sender_DE.xlsx) | [View](https://listbase.org/de/entertainment/de-tv-sender/) |
| [Allgemeine Fernsehsender (General TV channels)](de-tv-sender-allgemein.json) | 99 | 38 KB | [CSV](de-tv-sender-allgemein_DE.csv) | [Excel](de-tv-sender-allgemein_DE.xlsx) | [View](https://listbase.org/de/entertainment/de-tv-sender-allgemein/) |
| [Spielfilmsender (Movies TV channels)](de-tv-sender-spielfilm.json) | 99 | 46 KB | [CSV](de-tv-sender-spielfilm_DE.csv) | [Excel](de-tv-sender-spielfilm_DE.xlsx) | [View](https://listbase.org/de/entertainment/de-tv-sender-spielfilm/) |
| [Seriensender (Series TV channels)](de-tv-sender-serien.json) | 73 | 35 KB | [CSV](de-tv-sender-serien_DE.csv) | [Excel](de-tv-sender-serien_DE.xlsx) | [View](https://listbase.org/de/entertainment/de-tv-sender-serien/) |
| [Unterhaltungssender (Entertainment TV channels)](de-tv-sender-unterhaltung.json) | 63 | 29 KB | [CSV](de-tv-sender-unterhaltung_DE.csv) | [Excel](de-tv-sender-unterhaltung_DE.xlsx) | [View](https://listbase.org/de/entertainment/de-tv-sender-unterhaltung/) |
| [Comedysender (Comedy TV channels)](de-tv-sender-comedy.json) | 42 | 23 KB | [CSV](de-tv-sender-comedy_DE.csv) | [Excel](de-tv-sender-comedy_DE.xlsx) | [View](https://listbase.org/de/entertainment/de-tv-sender-comedy/) |
| [Dokumentationssender (Documentary TV channels)](de-tv-sender-dokumentation.json) | 41 | 20 KB | [CSV](de-tv-sender-dokumentation_DE.csv) | [Excel](de-tv-sender-dokumentation_DE.xlsx) | [View](https://listbase.org/de/entertainment/de-tv-sender-dokumentation/) |
| [Kindersender (Kids TV channels)](de-tv-sender-kinder.json) | 35 | 18 KB | [CSV](de-tv-sender-kinder_DE.csv) | [Excel](de-tv-sender-kinder_DE.xlsx) | [View](https://listbase.org/de/entertainment/de-tv-sender-kinder/) |
| [Musiksender (Music TV channels)](de-tv-sender-musik.json) | 28 | 12 KB | [CSV](de-tv-sender-musik_DE.csv) | [Excel](de-tv-sender-musik_DE.xlsx) | [View](https://listbase.org/de/entertainment/de-tv-sender-musik/) |
| [Animationssender (Animation TV channels)](de-tv-sender-animation.json) | 22 | 13 KB | [CSV](de-tv-sender-animation_DE.csv) | [Excel](de-tv-sender-animation_DE.xlsx) | [View](https://listbase.org/de/entertainment/de-tv-sender-animation/) |
| [Teleshopping-Sender (Shop TV channels)](de-tv-sender-shopping.json) | 20 | 9 KB | [CSV](de-tv-sender-shopping_DE.csv) | [Excel](de-tv-sender-shopping_DE.xlsx) | [View](https://listbase.org/de/entertainment/de-tv-sender-shopping/) |
| [Lifestyle-Sender (Lifestyle TV channels)](de-tv-sender-lifestyle.json) | 15 | 8 KB | [CSV](de-tv-sender-lifestyle_DE.csv) | [Excel](de-tv-sender-lifestyle_DE.xlsx) | [View](https://listbase.org/de/entertainment/de-tv-sender-lifestyle/) |
| [Religiöse Sender (Religious TV channels)](de-tv-sender-religion.json) | 14 | 7 KB | [CSV](de-tv-sender-religion_DE.csv) | [Excel](de-tv-sender-religion_DE.xlsx) | [View](https://listbase.org/de/entertainment/de-tv-sender-religion/) |
| [Nachrichtensender (News TV channels)](de-tv-sender-nachrichten.json) | 13 | 7 KB | [CSV](de-tv-sender-nachrichten_DE.csv) | [Excel](de-tv-sender-nachrichten_DE.xlsx) | [View](https://listbase.org/de/entertainment/de-tv-sender-nachrichten/) |
| [Kultursender (Culture TV channels)](de-tv-sender-kultur.json) | 10 | 6 KB | [CSV](de-tv-sender-kultur_DE.csv) | [Excel](de-tv-sender-kultur_DE.xlsx) | [View](https://listbase.org/de/entertainment/de-tv-sender-kultur/) |
| [Bildungssender (Education TV channels)](de-tv-sender-bildung.json) | 8 | 5 KB | [CSV](de-tv-sender-bildung_DE.csv) | [Excel](de-tv-sender-bildung_DE.xlsx) | [View](https://listbase.org/de/entertainment/de-tv-sender-bildung/) |
| [Klassiker-Sender (Classic TV channels)](de-tv-sender-klassiker.json) | 5 | 5 KB | [CSV](de-tv-sender-klassiker_DE.csv) | [Excel](de-tv-sender-klassiker_DE.xlsx) | [View](https://listbase.org/de/entertainment/de-tv-sender-klassiker/) |
| [Parlamentssender (Legislative TV channels)](de-tv-sender-parlament.json) | 5 | 4 KB | [CSV](de-tv-sender-parlament_DE.csv) | [Excel](de-tv-sender-parlament_DE.xlsx) | [View](https://listbase.org/de/entertainment/de-tv-sender-parlament/) |

## Quick Start

```bash
# List all entertainment datasets
curl https://cdn.de.listbase.org/index.json | jq '.datasets[] | select(.category=="entertainment") | .id'

# Fetch a dataset
curl https://cdn.de.listbase.org/entertainment/de-tv-sender-feeds.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/de/entertainment/)
