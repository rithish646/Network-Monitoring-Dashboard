# Network-Monitoring-Dashboard
Network Monitoring Dashboard using Prometheus and Grafana

This project demonstrates how to monitor Network switches using an open-source observability stack built with Prometheus, SNMP Exporter, and Grafana.  
The solution provides real-time and historical visibility into interface traffic, link status, device health, and performance metrics.

---

## Project Overview

Network switches typically expose metrics via SNMP, not HTTP.  
This project bridges that gap by using SNMP Exporter to convert SNMP data into Prometheus-compatible metrics, which are then visualized using Grafana dashboards.

---

## Architecture

Network Switch (SNMP)
---->
SNMP Exporter
---->
Prometheus (Time-Series DB)
---->
Grafana (Visualization & Alerts)


---

## Metrics & KPIs Monitored

- Interface bandwidth utilization (RX/TX)
- Interface operational status (up/down)
- Packet errors and discards
- Device availability
- Hardware health indicators (vendor dependent)

---

## Alerting Capabilities

- Interface down detection
- High bandwidth utilization alerts
- Packet error threshold alerts
- Device unreachable alerts

---

## Tools & Technologies

- Prometheus
- Grafana
- SNMP Exporter
- SNMP IF-MIB
- Linux
- Docker & Docker Compose
- YAML Configuration

---

## Use Cases

- Enterprise network monitoring
- Capacity planning and trend analysis
- Proactive incident detection
- Vendor-neutral infrastructure monitoring

---

## Outcomes

- Centralized monitoring for network switches
- Reduced manual network checks
- Improved network reliability through proactive alerts
- Scalable and cost-effective alternative to proprietary tools



