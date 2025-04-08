
# Mini SIEM Using ELK Stack + Filebeat

This is a lightweight Security Information and Event Management (SIEM) system built using the ELK Stack (Elasticsearch, Logstash, Kibana) and Filebeat. It's designed to simulate log collection, detection of suspicious events (e.g., brute force login attempts), and visualize them via dashboards.

This project is a personal cybersecurity learning project and is intended to demonstrate practical log analysis, threat detection, and SIEM architecture.

---

## Stack Used

| Tool            | Role                                         |
|-----------------|----------------------------------------------|
| **Elasticsearch** | Stores parsed and structured logs           |
| **Logstash**      | Parses logs and applies detection rules     |
| **Kibana**        | Visualizes logs with dashboards             |
| **Filebeat**      | Collects and ships logs to Logstash         |
| **Docker Compose**| Manages and runs the services               |

---

## Features

- Collect and parse JSON-formatted log files
- Detect failed login attempts (tagged as brute-force attempts)
- Display alerts and events in real-time using Kibana dashboards
- Completely containerized using Docker for easy setup
- Customizable to add more detection rules or integrate external logs

---



