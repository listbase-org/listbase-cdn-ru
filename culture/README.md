# Культура и религия (Culture & Religion)

8 datasets — 14,449 records

> Browse at [listbase.org/ru/culture/](https://listbase.org/ru/culture/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Churches in Russia](ru-tserkvi.json) | 9,259 | 3615 KB | [CSV](ru-tserkvi_RU.csv) | [Excel](ru-tserkvi_RU.xlsx) | [View](https://listbase.org/ru/culture/ru-tserkvi/) |
| [Monuments and memorials in Russia](ru-pamyatniki.json) | 2,840 | 1112 KB | [CSV](ru-pamyatniki_RU.csv) | [Excel](ru-pamyatniki_RU.xlsx) | [View](https://listbase.org/ru/culture/ru-pamyatniki/) |
| [Музеи России (Museums in Russia)](ru-muzei.json) | 1,653 | 411 KB | [CSV](ru-muzei_RU.csv) | [Excel](ru-muzei_RU.xlsx) | [View](https://listbase.org/ru/culture/ru-muzei/) |
| [Cinemas in Russia](ru-kinoteatry.json) | 293 | 106 KB | [CSV](ru-kinoteatry_RU.csv) | [Excel](ru-kinoteatry_RU.xlsx) | [View](https://listbase.org/ru/culture/ru-kinoteatry/) |
| [Mosques in Russia](ru-mecheti.json) | 217 | 78 KB | [CSV](ru-mecheti_RU.csv) | [Excel](ru-mecheti_RU.xlsx) | [View](https://listbase.org/ru/culture/ru-mecheti/) |
| [Statues in Russia](ru-statui.json) | 127 | 50 KB | [CSV](ru-statui_RU.csv) | [Excel](ru-statui_RU.xlsx) | [View](https://listbase.org/ru/culture/ru-statui/) |
| [Synagogues in Russia](ru-sinagogi.json) | 31 | 13 KB | [CSV](ru-sinagogi_RU.csv) | [Excel](ru-sinagogi_RU.xlsx) | [View](https://listbase.org/ru/culture/ru-sinagogi/) |
| [Всемирное наследие ЮНЕСКО в России](ru-vsemirnoe-nasledie-unesco.json) | 29 | 32 KB | [CSV](ru-vsemirnoe-nasledie-unesco_RU.csv) | [Excel](ru-vsemirnoe-nasledie-unesco_RU.xlsx) | [View](https://listbase.org/ru/culture/ru-vsemirnoe-nasledie-unesco/) |

## Quick Start

```bash
# List all culture & religion datasets
curl https://cdn.ru.listbase.org/index.json | jq '.datasets[] | select(.category=="culture") | .id'

# Fetch a dataset
curl https://cdn.ru.listbase.org/culture/ru-tserkvi.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ru/culture/)
