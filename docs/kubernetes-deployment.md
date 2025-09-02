# Kubernetes Deployment

This document describes the Kubernetes resources used to deploy the backend application.

**Note:** The YAML files in the `k8s/` directory are placeholders. They need to be filled in with the actual configuration for the application.

## Deployment

The `Deployment` resource manages the application pods.

**File:** `k8s/backend-deployment.yaml`

## Service

The `Service` resource exposes the application pods within the cluster.

**File:** `k8s/backend-service.yaml` (This file needs to be created)

## Ingress

The `Ingress` resource exposes the application to the internet.

**File:** `k8s/backend-ingress.yaml`
