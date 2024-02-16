

## ⚡️ Getting Started

Clone the project

```bash
git clone https://github.com/softwdevel/Temperature-monitoring-system.git
```


Change the environment variables define in `.env` that are used to setup and deploy the stack
```bash
├── .env         <---
├── docker-compose.yml
├── entrypoint.sh
└── ...
```


Start the services
```bash
docker-compose up -d
```
## Docker Images Used (Official & Verified)

[**InfluxDB**](https://hub.docker.com/_/influxdb) / `2.1.1`

[**Grafana-OSS**](https://hub.docker.com/r/grafana/grafana-oss) / `8.4.3`


