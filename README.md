# Kubernetes Manifests

This directory contains Kubernetes manifests for deploying and managing the application.

## Structure

- `deployments/`: Deployment manifests.
- `services/`: Service manifests.
- `storage/`: PersistentVolume and PersistentVolumeClaim definitions.
- `configs/`: ConfigMap files for environment-specific configurations.
- `secrets/`: Secret files for sensitive data.

## Usage

To deploy the application:
```bash
kubectl apply -f k8s/
