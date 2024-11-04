# Kubernetes DevOps Tools Deployment with Ansible

This project automates the deployment of a Kubernetes environment and essential DevOps tools on a minicube, such as:
- Fluentd
- Grafana
- Jenkins
- Loki
- Prometheus
- Traefik

## Requirements
- Ansible
- Minikube (or another Kubernetes environment)
- Helm
- kubectl

## Usage
1. Install the tools by running:
   ```bash
   ansible-playbook install-tools.yml
   ```
