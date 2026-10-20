# Туризм (Tourism)

1 datasets — 1,047 records

> Browse at [listbase.org/ru/tourism/](https://listbase.org/ru/tourism/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Hotels in Russia](ru-gostinitsy.json) | 1,047 | 322 KB | [CSV](ru-gostinitsy_RU.csv) | [Excel](ru-gostinitsy_RU.xlsx) | [View](https://listbase.org/ru/tourism/ru-gostinitsy/) |

## Quick Start

```bash
# List all tourism datasets
curl https://cdn.ru.listbase.org/index.json | jq '.datasets[] | select(.category=="tourism") | .id'

# Fetch a dataset
curl https://cdn.ru.listbase.org/tourism/ru-gostinitsy.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ru/tourism/)
