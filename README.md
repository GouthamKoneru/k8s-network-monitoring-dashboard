Title: Kubernetes Network Monitoring Dashboard

Overview:

This project implements a cloud native monitoring system using Kubernetes to observe real time CPU, memory, and network performance of microservices under simulated load.

Architecture:

Microservices deployed on Kubernetes cluster
Metrics collected using Prometheus
Visualization using Grafana dashboards
Traffic generated using curl-based load simulation

Tech Stack:

Kubernetes
Prometheus
Grafana
Docker
Minikube
Linux (WSL/Ubuntu)

Features:

Real-time CPU monitoring
Memory usage tracking
Network traffic analysis (receive/transmit bytes)
Load testing using curl
Grafana dashboards for visualization

How it works:

Deploy services on Kubernetes
Prometheus scrapes system/container metrics
Grafana visualizes data in dashboards
Load generator simulates traffic
Metrics update in real-time

Results:

Observed CPU spikes under load
Network traffic increased during request bursts
Stable memory usage across services
Real-time observability achieved

Future Improvements:

Add autoscaling (HPA)
Deploy on AWS EKS
Add alerting via Alertmanager
Integrate application-level HTTP metrics

Author:

Goutham Reddy
