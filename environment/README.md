# Окружающая среда (Environment)

2 datasets — 601 records

> Browse at [listbase.org/ru/environment/](https://listbase.org/ru/environment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Электростанции России](ru-elektrostantsii.json) | 545 | 213 KB | [CSV](ru-elektrostantsii_RU.csv) | [Excel](ru-elektrostantsii_RU.xlsx) | [View](https://listbase.org/ru/environment/ru-elektrostantsii/) |
| [Атомные электростанции России](ru-atomnye-elektrostantsii.json) | 56 | 24 KB | [CSV](ru-atomnye-elektrostantsii_RU.csv) | [Excel](ru-atomnye-elektrostantsii_RU.xlsx) | [View](https://listbase.org/ru/environment/ru-atomnye-elektrostantsii/) |

## Quick Start

```bash
# List all environment datasets
curl https://cdn.ru.listbase.org/index.json | jq '.datasets[] | select(.category=="environment") | .id'

# Fetch a dataset
curl https://cdn.ru.listbase.org/environment/ru-elektrostantsii.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ru/environment/)
