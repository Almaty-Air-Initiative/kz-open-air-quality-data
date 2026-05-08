# Almaty Community Air Sensor Dataset

This dataset contains processed **hourly air quality observations** from community and distributed sensor networks in Almaty for **2025**.

The dataset combines measurements from multiple public and community-based monitoring sources and is organized into monthly files.

---

## Repository Structure
```bash
2025_data/
│
├── kgm_2025_{month}.csv
├── ...
└── README.md
```

---

## Temporal Resolution

| Metric | Value |
|---------|--------|
| Frequency | Hourly |
| Time format | `YYYY-MM-DD HH:00:00` |
| Coverage | January–December 2025 |

Example timestamps:
- `2025-01-01 00:00:00`
- `2025-01-01 01:00:00`
- `2025-01-01 02:00:00`

---
## Variables

| Column | Description |
|----------|-------------|
| `datetime` | Timestamp (`YYYY-MM-DD HH:MM:SS`, UTC+5) |
| `id` | Sensor ID |
| `name` | Sensor name |
| `pm25` | PM2.5 concentration (µg/m³) |
| `pm10` | PM10 concentration (µg/m³) |
| `no2` | NO₂ concentration (µg/m³) |
| `so2` | SO₂ concentration (µg/m³) |
| `co` | CO concentration (µg/m³) |
| `aqi_pm25` | PM2.5 AQI |
| `district` | District name (Kazakh) |
| `district_ru` | District name (Russian) |
| `lat` | Latitude |
| `lon` | Longitude |
| `source` | Sensor network source |
| `origin` | Original platform/provider |

---
### January–September 2025

Data includes sensors from existing community monitoring networks.

### October–December 2025

Beginning in **October 2025**, the dataset also includes additional sensors deployed by **Almaty Air Initiative**, expanding monitoring coverage across the city.

---
## Missing Values

Missing values are represented as:

```python
NaN
```

Possible reasons:
- temporary sensor downtime  
- maintenance  
- unavailable pollutant measurements  
- incomplete source records  

---

## License

Open for research and educational use.
