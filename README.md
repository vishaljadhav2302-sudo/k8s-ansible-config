# Kubernetes Worker Node Configuration with Ansible

This repository contains Ansible playbooks and roles to configure EC2 worker nodes for a Kubernetes cluster. This is Part 2 of the DevOps Capstone Project.

## Roles Included in this Repository
- **node-setup**: Basic OS hardening and firewall (UFW) configuration.
- **node-exporter**: Installs Prometheus Node Exporter for system monitoring.
- **prometheus-config**: Configuration setup for Prometheus monitoring.
- **alertmanager-config**: Configuration setup for Alertmanager notifications.

## Prerequisites
- Ansible installed on the control node.
- SSH access to the target EC2 instances (Worker Nodes).

## Usage
To run this playbook:
