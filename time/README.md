# Время и календарь (Time & Calendar)

1 datasets — 660 records

> Browse at [listbase.org/ru/time/](https://listbase.org/ru/time/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Государственные праздники России — полный каталог (1991–2030)](ru-prazdniki-completos.json) | 660 | 360 KB | [CSV](ru-prazdniki-completos_RU.csv) | [Excel](ru-prazdniki-completos_RU.xlsx) | [View](https://listbase.org/ru/time/ru-prazdniki-completos/) |

## Quick Start

```bash
# List all time & calendar datasets
curl https://cdn.ru.listbase.org/index.json | jq '.datasets[] | select(.category=="time") | .id'

# Fetch a dataset
curl https://cdn.ru.listbase.org/time/ru-prazdniki-completos.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ru/time/)
