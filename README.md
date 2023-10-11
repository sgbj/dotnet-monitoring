# .NET 8 Monitoring with OpenTelemetry

![Screenshot](https://github.com/sgbj/dotnet-monitoring/assets/5178445/21954115-2806-468f-a295-c0d5336eab36)

Sample ASP.NET Core web application with instrumentation and monitoring using OpenTelemetry, Prometheus, Jaeger, Grafana, and Docker.

Dashboards from [JamesNK/aspnetcore-grafana](https://github.com/JamesNK/aspnetcore-grafana).

## Services

| Name | Endpoint |
|---|---|
| ASP.NET Core wb application | https://localhost:8081 |
| 📏 Prometheus for metrics | http://localhost:9090 |
| ⏱️ Jaeger for tracing | http://localhost:16686 |
| 📊 Grafana for dashboards | http://localhost:3000
| 🐋 Docker Compose for container orchestration | |

## To do

* 🗒️ Loki for logging
* ➡️ Simplify exports with OpenTelemetry Collector

## Getting started

```bash
docker-compose up
```
