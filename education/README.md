# Образование (Education)

1 datasets — 309 records

> Browse at [listbase.org/ru/education/](https://listbase.org/ru/education/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Россия — Университеты и высшие учебные заведения](ru-universitety.json) | 309 | 97 KB | [CSV](ru-universitety_RU.csv) | [Excel](ru-universitety_RU.xlsx) | [View](https://listbase.org/ru/education/ru-universitety/) |

## Quick Start

```bash
# List all education datasets
curl https://cdn.ru.listbase.org/index.json | jq '.datasets[] | select(.category=="education") | .id'

# Fetch a dataset
curl https://cdn.ru.listbase.org/education/ru-universitety.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ru/education/)
