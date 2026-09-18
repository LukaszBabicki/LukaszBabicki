# Łukasz Babicki

10+ years in Network/Infrastructure/NOC. Now focused on **SRE, Observability &
Platform Engineering**.

## Currently building

A homelab that works like a small SRE/platform: a K3s cluster monitored by
Zabbix (Zabbix-as-Code, SNMP), and an MCP server that gives Claude Code direct, read-only
access to live monitoring data — so an AI assistant can answer "what's
broken right now?" without a human opening the Zabbix UI first.

## Tech I work with

![Zabbix](https://img.shields.io/badge/Zabbix-D40000?style=for-the-badge&logo=zabbix&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Dynatrace](https://img.shields.io/badge/Dynatrace-1496FF?style=for-the-badge&logo=dynatrace&logoColor=white)

## Featured projects

- **[zabbix-mcp](https://github.com/LukaszBabicki/zabbix-mcp)** — MCP
  server integration giving Claude Code read-only access to live Zabbix
  monitoring data. The read-only permission boundary has been tested
  directly: a write attempt was correctly rejected by the Zabbix API.
- **[DM-multi-stage-builds](https://github.com/LukaszBabicki/DM-multi-stage-builds)**
  — Multi-stage Docker build (dev/builder/production) serving a static app
  via Nginx with a non-root user. Final project for the Docker Maestro course.
- **[ed_apka_1](https://github.com/LukaszBabicki/ed_apka_1)** — Coursework
  for "Ewolucja Developera" (AI agents / Claude Code), built on the
  RunwayBriefing FIDS starter (flight information display boards).
