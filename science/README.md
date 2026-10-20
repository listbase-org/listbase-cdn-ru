# Наука (Science)

1 datasets — 83 records

> Browse at [listbase.org/ru/science/](https://listbase.org/ru/science/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Ледники России](ru-ledniki.json) | 83 | 25 KB | [CSV](ru-ledniki_RU.csv) | [Excel](ru-ledniki_RU.xlsx) | [View](https://listbase.org/ru/science/ru-ledniki/) |

## Quick Start

```bash
# List all science datasets
curl https://cdn.ru.listbase.org/index.json | jq '.datasets[] | select(.category=="science") | .id'

# Fetch a dataset
curl https://cdn.ru.listbase.org/science/ru-ledniki.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ru/science/)
