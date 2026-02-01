# PaySecure – Decision Log

## Primary Cloud Provider
Chosen: AWS  
Reason: Mature managed services, strong EKS + RDS HA support, PCI-DSS-friendly offerings.

## Container Orchestration
Chosen: Kubernetes (EKS)  
Reason: Auto-scaling, portability, GitOps compatibility.

## Database
Chosen: Amazon RDS PostgreSQL (Multi-AZ)  
Reason: Managed HA, automated backups, encryption, easier PCI-DSS alignment.

## CI/CD Strategy
Chosen: GitHub Actions (GitOps-style)  
Reason: Native Git integration, auditability, automation.

## Observability
Chosen: Prometheus + Grafana  
Reason: Industry standard, deep Kubernetes & DB metrics.

## Security Strategy
Chosen: IAM least privilege, private networking, secrets management, encryption everywhere.
