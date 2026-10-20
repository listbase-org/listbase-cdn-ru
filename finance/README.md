# Финансы и торговля (Finance & Trade)

1 datasets — 39 records

> Browse at [listbase.org/ru/finance/](https://listbase.org/ru/finance/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Marketplaces in Russia](ru-rynki.json) | 39 | 16 KB | [CSV](ru-rynki_RU.csv) | [Excel](ru-rynki_RU.xlsx) | [View](https://listbase.org/ru/finance/ru-rynki/) |

## Quick Start

```bash
# List all finance & trade datasets
curl https://cdn.ru.listbase.org/index.json | jq '.datasets[] | select(.category=="finance") | .id'

# Fetch a dataset
curl https://cdn.ru.listbase.org/finance/ru-rynki.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ru/finance/)
