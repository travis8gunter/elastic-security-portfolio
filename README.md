# Elastic Security Portfolio – Personal Lab

A personal Elastic Stack lab environment focused on **detection engineering**, **SIEM configurations**, and **security operations experimentation**. Built to deepen hands-on expertise with Elastic Security (Elasticsearch + Kibana + Elastic Agent/Fleet) through prototyping custom detection logic, data ingestion pipelines, index management, and threat enrichment workflows.

This repo serves as my portfolio showcase of Elastic configurations I've designed, tested, and refined in a self-hosted lab. It's ideal for blue-team skill-building, rule tuning, and understanding production-grade SIEM architecture.

## Project Goals
- Prototype and validate **custom detection rules** for common attack patterns (e.g., brute-force, credential access, anomalous execution).
- Build and optimize **ingest pipelines** for log normalization, enrichment (geoip, threat intel simulation), and noise reduction.
- Experiment with **Index Lifecycle Management (ILM)** policies, rollover aliases, and data retention strategies.
- Create **index templates** and component templates for consistent mappings and security-focused settings.
- Develop **Kibana dashboards**, saved searches, and visualizations for threat hunting and alert monitoring.
- Explore automation for threat intelligence ingestion and rule management (Python scripts).

All configurations are tested in a controlled, isolated lab environment using simulated or open-source log sources.

## Lab Architecture & Setup
Single-node Elastic Stack deployment (suitable for laptop/home server) using Docker Compose or direct install.

### Core Components
- **Elasticsearch** (8.x series) – Indexing, search, and security rules engine.
- **Kibana** – Dashboards, detection engine, and rule creation.
- **Elastic Agent / Fleet** – Endpoint and log collection simulation.
- **Filebeat / Syslog sources** – Ingesting perimeter logs, auth events, system telemetry.

### Quick Start (Docker-based)
1. Clone the repo:
   ```bash
   git clone https://github.com/travis8gunter/elastic-security-portfolio.git
   cd elastic-security-portfolio
   docker-compose up -d


