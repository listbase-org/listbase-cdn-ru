# Технологии (Technology)

2 datasets — 363 records

> Browse at [listbase.org/ru/tech/](https://listbase.org/ru/tech/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Эмодзи-флаги стран мира](ru-strany-emoji-flagi.json) | 249 | 42 KB | [CSV](ru-strany-emoji-flagi_RU.csv) | [Excel](ru-strany-emoji-flagi_RU.xlsx) | [View](https://listbase.org/ru/tech/ru-strany-emoji-flagi/) |
| [Библиотеки России](ru-biblioteki.json) | 114 | 59 KB | [CSV](ru-biblioteki_RU.csv) | [Excel](ru-biblioteki_RU.xlsx) | [View](https://listbase.org/ru/tech/ru-biblioteki/) |

## Quick Start

```bash
# List all technology datasets
curl https://cdn.ru.listbase.org/index.json | jq '.datasets[] | select(.category=="tech") | .id'

# Fetch a dataset
curl https://cdn.ru.listbase.org/tech/ru-strany-emoji-flagi.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ru/tech/)
