# Kazhydromet Dataset (Almaty, Kazakhstan - 2025)

This repository contains air quality monitoring data from **Kazhydromet automatic monitoring stations** in Almaty, Kazakhstan for the year **2025**.

The dataset includes **20-minute observations** of major air pollutants collected across multiple stations in Almaty.

---

## Dataset Structure

```bash
kgm_2025/
│
├── kgm_2025_01.csv
├── kgm_2025_02.csv
├── ...
├── kgm_2025_12.csv
├── stations.csv
└── README.md
```

---

## Files Description

### `kgm_2025_{month}.csv`

Monthly dataset containing air quality observations.

| column | description |
|---------|-------------|
| datetime | measurement datetime (`YYYY-MM-DD HH:MM:SS`, UTC+5)|
| PM2_5 | PM2.5 concentration (mg/m³) |
| PM10 | PM10 concentration (mg/m³) |
| SO2 | sulfur dioxide concentration (mg/m³) |
| CO | carbon monoxide concentration (mg/m³) |
| NO2 | nitrogen dioxide concentration (mg/m³) |
| NO | nitric oxide concentration (mg/m³) |
| O3 | ozone concentration (mg/m³) |
| station | monitoring station ID |
| year | year (Almaty local)|
| month | month (Almaty local) |
| day | day (Almaty local) |
| hour | hour (Almaty local) |

---

### `stations.csv`

Station metadata file.

| column | description |
|---------|-------------|
| station | station ID |
| district | district name (Russian) |
| district_en | district name (English) |
| lat | latitude |
| lon | longitude |

---

## Monitoring Stations

The dataset includes measurements from the following stations:

- 27  
- 28  
- 29  
- 30  
- 31  
- Скат-1  
- Скат-2  
- Скат-3  
- Скат-4  
- Скат-5  
- Скат-6  
- AQM 1  

---

## District Coverage

| Russian | English |
|----------|-----------|
| Алатауский | Alatau |
| Турксибский | Turksib |
| Бостандыкский | Bostandyk |
| Медеуский | Medeu |
| Жетысуский | Zhetysu |
| Бурундайское автохозяйство | Burundai |

---

## Temporal Resolution

Raw measurements are recorded every **20 minutes**.

Example timestamps:

- `2025-01-01 00:00:00`
- `2025-01-01 00:20:00`
- `2025-01-01 00:40:00`

---

## Pollutants Included

- PM2.5
- PM10
- SO2
- CO
- NO2
- NO
- O3
---

## Data Source

Source: **Kazhydromet**  
Official environmental monitoring agency of Kazakhstan:

https://www.kazhydromet.kz/

---

## Data Processing

The original raw monthly Excel files.

---

## Missing Values

Missing observations are represented as:

```python
NaN
```

Possible reasons:

- sensor downtime  
- maintenance periods  
- missing source records  
- unavailable pollutant measurements at specific stations

---

## License

Open for research and educational use.

Please cite the original source:

**Kazhydromet**
