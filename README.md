# AWS Docker and Grafana Observability

This project deploys:

- Multiple Docker applications on an AWS EC2 VM
- Grafana Alloy on the EC2 VM
- Amazon EKS
- Argo CD
- Grafana
- Loki

Grafana Alloy discovers Docker containers, adds readable container labels and sends their logs to Loki running in EKS.
