# ArgoCD GitOps Repository

This repository contains ArgoCD application manifests for managing Kubernetes deployments.

## Structure

```
environments/
├── dev/          # Development environment configurations
├── local/        # Local development configurations
├── prod/         # Production environment configurations
└── stage/        # Staging environment configurations

projects/
└── elastic.yaml  # Elastic Stack project definition
```

## Environments

### Development
Contains development-specific application configurations.

### Local
Contains local development environment configurations including:
- Elasticsearch
- Filebeat
- Kibana
- Logstash

### Production
Production environment configurations.

### Stage
Staging environment configurations.

## Applications

This repository manages ArgoCD applications for the Elastic Stack:
- **Elasticsearch**: Search and analytics engine
- **Filebeat**: Lightweight shipper for log data
- **Kibana**: Visualization and exploration tool
- **Logstash**: Data processing pipeline

## Usage

These manifests are managed by ArgoCD and deployed to Kubernetes clusters automatically.

## Contributing

Changes to production environments require:
1. Branch creation
2. Pull request with approval
3. Security and compliance checks
4. Deployment via ArgoCD

---

**Last Updated**: January 2, 2026  
**Managed By**: MCP GitOps Automation
