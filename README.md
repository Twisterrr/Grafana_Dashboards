# Grafana Dashboards Repository
Personnal Project, Grafana Dashboards

![visitor badge](https://visitor-badge.glitch.me/badge?page_id=twisterrr.mul_my_rpg_2029&left_color=purple&right_color=grey)

![grafana-logo](https://github.com/Twisterrr/Grafana_Dashboards/assets/60510584/ac00402c-b10d-474a-b297-b0348923c1d1)

## Overview

This repository is dedicated to Grafana dashboards for monitoring various software, systems, equipment... It is organized with separate folders for different categories, each containing JSON files for dashboards and scripts for data ingestion. The dashboards leverage main data sources such as InfluxDB, Prometheus, etc.

## Folder Structure
```
.
├── software/
│ ├── web-app/
│ │ ├── dashboard.json
│ │ ├── data-scripts/
│ │ │ ├── ingest-web-app-data.sh
│ ├── microservices/
│ │ ├── dashboard.json
│ │ ├── data-scripts/
│ │ │ ├── ingest-microservices-data.py
├── systems/
│ ├── linux-servers/
│ │ ├── dashboard.json
│ │ ├── data-scripts/
│ │ │ ├── ingest-linux-servers-data.sh
│ ├── windows-servers/
│ │ ├── dashboard.json
│ │ ├── data-scripts/
│ │ │ ├── ingest-windows-servers-data.ps1
├── devices/
│ ├── iot-devices/
│ │ ├── dashboard.json
│ │ ├── data-scripts/
│ │ │ ├── ingest-iot-devices-data.js
│ ├── network-equipment/
│ │ ├── dashboard.json
│ │ ├── data-scripts/
│ │ │ ├── ingest-network-equipment-data.py
├── ...
├── README.md
```

- `software/`: Dashboards and data scripts related to software monitoring.
- `systems/`: Dashboards and data scripts related to system monitoring.
- `devices/`: Dashboards and data scripts related to equipment and devices monitoring.

Each subfolder contains dashboards in JSON format and data scripts for data ingestion specific to the category.

## Getting Started

1. Clone this repository:

    ```bash
    git clone <repository_url>
    cd <repository_directory>
    ```

2. Explore the folders for the category and type of dashboard you are interested in.

3. Use Grafana to import the JSON files for dashboards into your Grafana instance.

4. Refer to the data scripts for guidelines on ingesting data into your chosen data source.

## Main Data Sources

- [InfluxDB](https://www.influxdata.com/): A time-series database commonly used for storing monitoring data.
- [Prometheus](https://prometheus.io/): An open-source monitoring and alerting toolkit.
- [Grafana Cloud](https://grafana.com/cloud/): A fully managed observability platform.
