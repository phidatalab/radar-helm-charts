

# kube-prometheus-stack

![Version: 0.3.2](https://img.shields.io/badge/Version-0.3.2-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 0.57.0](https://img.shields.io/badge/AppVersion-0.57.0-informational?style=flat-square)

A Helm chart for Prometheus operator stack. This chart is an overlay for original kube-prometheus-stack chart. It defines some the default values for namespaces to monitor, alert templates, Nginx configuration and authentication and a few extra charts for Grafana. For more details on how to customize those values refer to original chart.

**Homepage:** <https://prometheus-operator.dev>

## Source Code

* <https://github.com/prometheus-community/helm-charts/tree/main/charts/kube-prometheus-stack>

## Prerequisites
* Kubernetes 1.17+
* Kubectl 1.17+
* Helm 3.1.0+
* PV provisioner support in the underlying infrastructure

## Requirements

| Repository | Name | Version |
|------------|------|---------|
| https://prometheus-community.github.io/helm-charts | kube-prometheus-stack | 37.2.0 |
