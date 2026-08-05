# Simple-Homelab

A collection of self-hosted services managed with Docker Compose, designed for learning, experimentation.

## Goals

- Build a modular and maintainable homelab
- Practice Docker and container orchestration
- Follow production-inspired security practices
- Learn monitoring, logging, and backups

## Services

| Service | Description |
|---------|-------------|
| Traefik | Reverse proxy and TLS termination |
| PostgreSQL | Database server |
| FreshRSS | Self-hosted RSS aggregator |
| Uptime Kuma | A Fancy Self-Hosted Monitoring Tool |

## Project Structure


```text
 .
├──  services
│   ├──  freshrss
│   │   └──  docker-compose.yml
│   ├──  postgres
│   │   ├──  initdb
│   │   └──  docker-compose.yml
│   ├──  traefik
│   │   └──  docker-compose.yml
│   └──  uptime-kuma
│       └──  docker-compose.yml
├── 󰂺 README.md
└──  docker-compose.yml
```

## Planned Services

* Grafana
* Prometheus
* Loki
* Alloy
* Uptime Kuma
* Gitea
* Vaultwarden
* File Browser
* ELK stack

## Status

This project is under active development and will continue to grow with additional services, documentation, and automation.
