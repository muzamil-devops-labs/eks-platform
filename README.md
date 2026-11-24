# Resilient, Cost-Optimized Kubernetes Platform on AWS

A production-style Kubernetes infrastructure project focused on scalability, reliability, cost optimization, observability, and disaster recovery using Amazon EKS.

**Status:** 🚧 Work in Progress

## Project Overview

This project aims to design and implement a scalable Kubernetes platform on AWS using Terraform.

The infrastructure will leverage Amazon EKS for container orchestration, Karpenter for dynamic node provisioning, and Horizontal Pod Autoscaler (HPA) for workload scaling.

Monitoring and observability will be implemented using Prometheus and Grafana, while k6 will be used for performance and load testing.

Velero will provide Kubernetes backup and recovery capabilities.

## Architecture

Planned infrastructure components:

1. Terraform provisions AWS networking and infrastructure.
2. Amazon EKS provides the Kubernetes control plane.
3. Karpenter dynamically provisions worker nodes.
4. HPA scales application replicas based on resource utilization.
5. AWS Spot Instances help optimize infrastructure costs.
6. Prometheus collects infrastructure and application metrics.
7. Grafana provides monitoring dashboards.
8. k6 performs load and performance testing.
9. Velero handles Kubernetes backup and disaster recovery.

## Technology Stack

| Category | Technologies |
|---|---|
| Cloud | AWS |
| Container Orchestration | Amazon EKS, Kubernetes |
| Infrastructure as Code | Terraform |
| Containerization | Docker |
| Autoscaling | HPA, Karpenter |
| Cost Optimization | AWS Spot Instances |
| Monitoring | Prometheus, Grafana |
| Load Testing | k6 |
| Backup & Recovery | Velero |
| Operating System | Linux |

## Key Features (Planned)

- Infrastructure provisioning using Terraform.
- Scalable Amazon EKS architecture.
- Dynamic node provisioning with Karpenter.
- Application autoscaling with HPA.
- Cost optimization using Spot Instances.
- Infrastructure and application monitoring.
- Performance testing using k6.
- Kubernetes backup and disaster recovery.
- Resilience and failure-recovery testing.

## Repository Structure

```text
eks-platform/
├── terraform/
│   ├── modules/
│   ├── networking/
│   └── eks/
├── kubernetes/
│   ├── deployments/
│   ├── services/
│   └── autoscaling/
├── karpenter/
├── monitoring/
│   ├── prometheus/
│   └── grafana/
├── load-testing/
├── velero/
└── README.md
```

## Implementation Roadmap

- [ ] Design AWS infrastructure architecture.
- [ ] Provision VPC and networking using Terraform.
- [ ] Deploy Amazon EKS cluster.
- [ ] Configure Kubernetes workloads and services.
- [ ] Implement HPA for application autoscaling.
- [ ] Install and configure Karpenter.
- [ ] Configure Spot Instances for cost optimization.
- [ ] Deploy Prometheus and Grafana.
- [ ] Perform load testing using k6.
- [ ] Configure Velero backups and recovery.
- [ ] Perform failure and resilience testing.
- [ ] Document architecture, results, and lessons learned.

## Project Goals

Demonstrate practical experience in building, operating, monitoring, scaling, and maintaining Kubernetes infrastructure on AWS while applying cost optimization and reliability engineering principles.

---

**Note:** This project is actively being developed. Features and implementation details will be updated as development progresses.
