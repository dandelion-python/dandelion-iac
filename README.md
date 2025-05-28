# dandelion-iac

This repository contains **Kubernetes manifests** used to deploy the demo environment for the [Dandelion](https://github.com/dandelion-python/dandelion-python) project.

> ℹ️ **Note**  
> This setup is for demo and training purposes only. It is not intended for production use. Some configurations and values are simplified or mocked.

## Contents

- Kubernetes manifests for deploying Dandelion and supporting components
- Example configs intended for internal or non-production clusters

## Requirements

- `kubectl`
- Access to a demo/training Kubernetes cluster
- Change the mocked values.

## Usage

```bash
git clone https://github.com/dandelion-python/dandelion-iac.git
cd dandelion-iac

# Apply manifests
kubectl apply -f .
```
