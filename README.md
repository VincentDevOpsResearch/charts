# charts
helm charts for this project

This document provides an introduction to each Helm chart used within our Kubernetes environment:

## ITPP

## Itppbackend

ITPP Backend 

## Itppui

ITPP Frontend

## Monitoring Dashboard

### Cluster-polling

Responsible for periodically polling Kubernetes cluster metrics, such as node utilization and resource status, ensuring accurate and up-to-date monitoring data.

### Custom-prometheus

A tailored Prometheus deployment specifically configured for collecting and managing custom monitoring metrics from Kubernetes clusters and related applications.

### Emailnotificationservice

A service responsible for managing and sending email notifications based on defined alerts and system events detected in the monitoring dashboard.

### Forecasting-service

Provides predictive analytics and forecasting for infrastructure resource usage (CPU, RAM, disk) to enable proactive resource management and capacity planning.

### Monitoringdashboardbackend

Core backend service powering the monitoring dashboard, integrating various monitoring data sources (such as Kubernetes and RabbitMQ) and providing APIs for frontend consumption.

### Monitoringdashboardui

Web-based frontend interface for the monitoring dashboard, enabling visualization of infrastructure and application monitoring metrics, alerts, and trends.

## Other Infrastructure

### Nginx-ingress

Manages external access to services within the Kubernetes cluster, acting as a reverse proxy and load balancer, enhancing the efficiency and security of traffic management.

### Rabbitmq

Provides a deployment of RabbitMQ, a robust message broker, to handle asynchronous messaging and communication between distributed microservices.

### sql-server

Deploys an MSSQL SQL Server database instance within the Kubernetes environment, serving as the primary datastore for monitoring and analytics data.