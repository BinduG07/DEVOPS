# Exercise 6: Delivery Monitoring System

## Objective

To monitor delivery application metrics using Prometheus and Grafana and automate the setup using a Jenkins Pipeline.

## Technologies Used

- Python
- Flask
- Prometheus
- Grafana
- Docker
- Jenkins
- Git and GitHub

## GitHub Repository

https://github.com/BinduG07/DEVOPS/tree/main/Exercise6

## Project Structure

```text
Exercise6/
├── delivery_monitoring/
│   ├── delivery_metrics.py
│   ├── prometheus.yml
│   ├── alert_rules.yml
│   ├── Dockerfile
│   └── Jenkinsfile
└── screenshots/
    ├── delivery metrics.png
    ├── docker ps.png
    ├── grafana dashboard.png
    ├── grafana login page.png
    ├── metrics.png
    └── prometheus target.png
```

## Monitoring Metrics

The application exposes the following delivery metrics:

- `total_deliveries` — Total number of deliveries.
- `pending_deliveries` — Number of pending deliveries.
- `on_the_way_deliveries` — Number of deliveries in transit.
- `average_delivery_time` — Delivery time measurements.

## Implementation

1. Created a Python application to expose delivery metrics.
2. Configured Prometheus to collect metrics from the application.
3. Created alert rules to monitor delivery conditions.
4. Configured Grafana dashboards to visualize delivery metrics.
5. Used Docker to run the monitoring components.
6. Created a Jenkins Pipeline to automate the setup and execution.
7. Verified the metrics, dashboards, and pipeline output.

## Access URLs

- Application Metrics: `http://localhost:8000/metrics`
- Prometheus: `http://localhost:9090`
- Grafana: `http://localhost:3000`

## Result

The delivery monitoring application exposes metrics that can be collected by Prometheus and visualized in Grafana. Jenkins automates the monitoring setup through a pipeline.

## Conclusion

This exercise demonstrates application monitoring, metric collection, dashboard visualization, alert configuration, containerization, and CI/CD automation.

## Screenshots

The `screenshots/` folder contains screenshots of the monitoring setup, Prometheus metrics, Grafana dashboards, and Jenkins pipeline execution.
