# ListBase CDN — Русский (ru)

Open dataset collection for **Русский** (Russian).
439 datasets across 13 categories with 214,253 total records.

> Browse and download at [https://listbase.org/ru/](https://listbase.org/ru/)

## Categories

| Category | Datasets |
|----------|----------|
| [Культура и религия (Culture & Religion)](culture/) | 8 |
| [Образование (Education)](education/) | 1 |
| [Окружающая среда (Environment)](environment/) | 2 |
| [Финансы и торговля (Finance & Trade)](finance/) | 1 |
| [География (Geography)](geography/) | 105 |
| [Здоровье (Health)](health/) | 1 |
| [Язык (Language)](language/) | 1 |
| [Справочник (Reference)](reference/) | 231 |
| [Наука (Science)](science/) | 1 |
| [Технологии (Technology)](tech/) | 2 |
| [Время и календарь (Time & Calendar)](time/) | 1 |
| [Туризм (Tourism)](tourism/) | 1 |
| [Транспорт (Transport)](transport/) | 84 |

## Usage

### Browse on the web
Visit [listbase.org/ru/](https://listbase.org/ru/) to search, preview, and download in Excel, CSV, or PDF.

### Fetch via CDN
```bash
# Dataset index (metadata only)
curl https://cdn.ru.listbase.org/index.json

# Full dataset (JSON)
curl https://cdn.ru.listbase.org/geography/th-central-provinces.json

# Download as Excel or CSV
curl -O https://cdn.ru.listbase.org/geography/th-central-provinces_RU.xlsx
curl -O https://cdn.ru.listbase.org/geography/th-central-provinces_RU.csv

# Build dump (metadata + sample rows, gzipped)
curl https://cdn.ru.listbase.org/dump.json.gz | gunzip
```

### Use in JavaScript
```js
const res = await fetch('https://cdn.ru.listbase.org/geography/th-central-provinces.json');
const data = await res.json();
console.log(data.name);    // "ภาคกลาง — จังหวัดในภาคกลาง"
console.log(data.rows);    // [{ ... }, ...]
```

## File Structure

```
├── index.json              # Dataset index (metadata + file info)
├── dump.json.gz            # Build dump (metadata + 20 sample rows per dataset)
├── {category}/
│   ├── README.md           # Category overview
│   ├── {dataset}.json      # Full dataset with rows
│   ├── {dataset}_RU.csv   # CSV download
│   └── {dataset}_RU.xlsx  # Excel download
```

## Dataset JSON Format

Each `.json` file contains:

| Field | Description |
|-------|-------------|
| `id` | Unique dataset identifier |
| `name` | Dataset name |
| `description` | What this dataset contains |
| `category` | Category (e.g. geography, finance) |
| `source` | Data source attribution |
| `updated` | Last updated date |
| `record_count` | Number of records |
| `columns` | Column definitions (key, label, type) |
| `rows` | Array of data records |

## License

Data is provided under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
See individual dataset `source` fields for original data attribution.

---

Part of [ListBase](https://listbase.org) — Free Reference Tables & Lists
