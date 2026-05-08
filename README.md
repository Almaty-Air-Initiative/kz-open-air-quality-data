# Air Quality Datasets (Kazakhstan / Almaty)

Open repository of air quality datasets collected from various sources, including:
- [Kazhydromet](https://www.kazhydromet.kz/en/ecology/ezhemesyachnyy-informacionnyy-byulleten-o-sostoyanii-okruzhayuschey-sredy) (Kazakhstan national monitoring network)
- Other public, open-data, and research datasets

Data is updated periodically as new information becomes available.

## 📊 Data

Datasets are provided in CSV format and include:
- **PM2.5** *(primary pollutant)*
- PM10
- NO2
- SO2
- CO
- O3


## 🗂 Structure
```bash
kz-open-air-quality-data/
│
├── Kazhydromet/
│   ├── kgm_{year}/ 
│   │   ├── kgm_{year}_{month}.csv
│   │   ├── ...
│   │   └── stations.csv
│   └── README.md
│
├── open_sensors/
│   ├── {year}_data/ 
│   │   ├── AAI_{year}_{month}.csv
│   │   ├── ...
│   │   └── README.md
│   └── README.md
```


## 🌍 Almaty Air Initiative 

Explore more:

- 🌐 [Visit Website](https://air.org.kz/en/)  
- 📊 [Explore Air Quality Data](https://dashboard.air.org.kz/)
