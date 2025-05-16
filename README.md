# Widgetario Kubernetes Setup

This repository contains Kubernetes manifests to deploy the Widgetario multi-service app.

## Components

- `frontend`: Web UI
- `api`: Backend logic
- `auth`: Authentication microservice
- `db`: PostgreSQL database

## How to deploy

```bash
kubectl apply -f .
