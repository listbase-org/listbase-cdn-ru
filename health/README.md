# Здоровье (Health)

1 datasets — 205 records

> Browse at [listbase.org/ru/health/](https://listbase.org/ru/health/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Hospitals in Russia](ru-bolnitsy.json) | 205 | 88 KB | [CSV](ru-bolnitsy_RU.csv) | [Excel](ru-bolnitsy_RU.xlsx) | [View](https://listbase.org/ru/health/ru-bolnitsy/) |

## Quick Start

```bash
# List all health datasets
curl https://cdn.ru.listbase.org/index.json | jq '.datasets[] | select(.category=="health") | .id'

# Fetch a dataset
curl https://cdn.ru.listbase.org/health/ru-bolnitsy.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ru/health/)
