# devops-infrastructure

Status: monitoring, ansible and documentation complete

![CI](https://github.com/elnuraErkinbekova/devops-infrastructure/actions/workflows/ci.yml/badge.svg)

## Description
This repository contains end-to-end DevOps infrastructure configurations for containerizing, provisioning, configuring, orchestrating, and monitoring a web application. It integrates modern Cloud-Native tooling including Docker, Terraform, Ansible, Kubernetes, and Prometheus alongside automated CI/CD workflows using GitHub Actions.

---

## Project Structure

```text
devops-infrastructure/
├── .github/
│   └── workflows/
│       └── ci.yml
├── .gitignore
├── README.md
├── docker/
│   ├── Dockerfile
│   ├── .dockerignore
│   └── index.html
├── terraform/
│   ├── main.tf
│   ├── variables.tf
│   └── outputs.tf
├── kubernetes/
│   ├── deployment.yaml
│   └── service.yaml
├── ansible/
│   ├── inventory
│   └── playbook.yml
└── monitoring/
    └── prometheus.yml
