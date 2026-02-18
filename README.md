# Network-Monitoring-Dashboard
Network Monitoring Dashboard using Prometheus and Grafana

This project demonstrates how to monitor Network switches using an open-source observability stack built with Prometheus, SNMP Exporter, and Grafana.  
The solution provides real-time and historical visibility into interface traffic, link status, device health, and performance metrics.

---

## Project Overview

Network switches typically expose metrics via SNMP, not HTTP.  
This project bridges that gap by using SNMP Exporter to convert SNMP data into Prometheus-compatible metrics, which are then visualized using Grafana dashboards.

---



