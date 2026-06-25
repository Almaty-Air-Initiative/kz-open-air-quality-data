# Air Quality Datasets (Kazakhstan / Almaty)

Open repository of historical air quality datasets collected from multiple monitoring networks across Kazakhstan.

The repository currently includes:
- [Kazhydromet](https://www.kazhydromet.kz/en/ecology/ezhemesyachnyy-informacionnyy-byulleten-o-sostoyanii-okruzhayuschey-sredy) - the national environmental monitoring network of Kazakhstan.
- Open sensors - crowdsourced low-cost sensor measurements from the Almaty Air Initiative network.

All datasets are distributed in CSV format and are periodically updated as new data becomes available.

## 📊 Data

Datasets are provided in CSV format and include:
* PM2.5
* PM10
* NO₂
* SO₂
* CO
* O₃

## 🗂 Structure

```
kz-open-air-quality-data/
│
├── Kazhydromet/
│   ├── README.md
│   ├── kgm_2024/
│   │   ├── kgm_2024_01.csv
│   │   ├── ...
│   │   └── stations.csv
│   └── kgm_2025/
│       ├── kgm_2025_01.csv
│       ├── ...
│       └── stations.csv
│
├── open_sensors/
│   ├── README.md
│   ├── 2019.csv
│   ├── 2020.csv
│   ├── 2021.csv
│   ├── 2022.csv
│   ├── 2023_data/
│   │   ├── AAI_2023_01.csv
│   │   ├── ...
│   │   └── AAI_2023_12.csv
│   ├── 2024_data/
│   │   ├── AAI_2024_01.csv
│   │   ├── ...
│   │   └── AAI_2024_12.csv
│   └── 2025_data/
│       ├── AAI_2025_01.csv
│       ├── ...
│       ├── AAI_2025_12.csv
│       └── README.md
│
└── README.md
```


## 🌍 Almaty Air Initiative 

Explore more:

- 🌐 [Visit Website](https://air.org.kz/en/)  
- 📊 [Explore Air Quality Data](https://dashboard.air.org.kz/)
