---
name: devops-tools
description: Master DevOps tools and practices. Covers Docker, Kubernetes, CI/CD, Infrastructure as Code, Terraform, Ansible, monitoring, and automation.
---

# DevOps Tools & Practices Skill

Master DevOps automation and infrastructure tools.

## Containerization

### Docker
- Images and layers
- Dockerfile best practices
- Docker Compose for multi-container
- Registry management (ECR, GCR, Docker Hub)
- Image optimization and security

### Container Runtime Alternatives
- Podman - Daemonless containers
- containerd - Industry standard
- CRI-O - Kubernetes-focused

## Orchestration

### Kubernetes (K8s)
- Pods, Deployments, Services
- ConfigMaps, Secrets, PersistentVolumes
- Ingress for external access
- RBAC for access control
- Namespaces for isolation

### Helm
- Kubernetes package manager
- Charts and values
- Templating and customization
- Repository management

### Service Mesh
- **Istio** - Advanced networking
- **Linkerd** - Lightweight alternative
- Distributed tracing
- Circuit breaking and retry logic

## Infrastructure as Code

### Terraform
- HCL syntax and logic
- Modules and workspaces
- State management
- Remote backends
- Multi-cloud support

### Ansible
- YAML-based playbooks
- Agentless architecture
- Idempotent operations
- Dynamic inventories
- Roles for reusability

### CloudFormation (AWS)
- JSON/YAML templates
- AWS-specific resources
- Stack management
- Change sets

## CI/CD Pipelines

### GitHub Actions
- Workflows and jobs
- Event-driven automation
- Secrets management
- Self-hosted runners

### GitLab CI/CD
- .gitlab-ci.yml configuration
- Runner management
- Pipeline scheduling
- Artifact storage

### Jenkins
- Pipeline as Code (Jenkinsfile)
- Distributed builds
- Plugin ecosystem
- Master-agent setup

### Other Tools
- **CircleCI** - Cloud-based
- **Travis CI** - Open-source friendly
- **Drone** - Container-based

## Monitoring & Logging

### Metrics Collection
- **Prometheus** - Time-series database
- **Grafana** - Visualization and dashboards
- **Datadog** - Comprehensive monitoring
- **New Relic** - Application Performance Monitoring

### Log Aggregation
- **ELK Stack** - Elasticsearch, Logstash, Kibana
- **Splunk** - Enterprise logging
- **CloudWatch** - AWS native
- **DataDog Logs** - Integrated with metrics

### Tracing
- **Jaeger** - Distributed tracing
- **Zipkin** - Alternative tracing
- **AWS X-Ray** - AWS native

## Automation & Scripting

### Bash/Shell
- System administration
- CI/CD scripting
- Infrastructure automation
- Text processing (sed, awk, grep)

### Python for DevOps
- Automation scripts
- Tool development
- Cloud SDKs
- Configuration management

## Secret Management

### HashiCorp Vault
- Centralized secret storage
- Dynamic secrets
- Encryption as a service
- Audit logging

### Cloud Native
- AWS Secrets Manager
- Google Secret Manager
- Azure Key Vault

## Best Practices

1. **Infrastructure as Code** - Version control everything
2. **Immutable Infrastructure** - Rebuild vs. update
3. **Gitops** - Git as single source of truth
4. **Monitoring** - Observe everything
5. **Security** - Least privilege, secrets management
6. **Cost Optimization** - Track and reduce cloud spend
7. **Disaster Recovery** - Automated backups and runbooks

## Recommended Learning Path

1. Docker fundamentals
2. Kubernetes basics (with managed service like EKS)
3. CI/CD pipelines (GitHub Actions or GitLab CI)
4. Infrastructure as Code (Terraform)
5. Configuration management (Ansible)
6. Monitoring (Prometheus + Grafana)
7. Advanced: Service mesh, advanced K8s

## Common DevOps Workflow

1. Code commit
2. Automated build (Docker image)
3. Automated tests
4. Registry push
5. Infrastructure setup (Terraform)
6. Deployment (Kubernetes or ECS)
7. Health checks
8. Monitoring and alerting
9. Automated rollback if needed

---

[Explore DevOps on Roadmap.sh](https://roadmap.sh/)