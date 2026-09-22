# Tamra Sherwood

**DevOps / Platform Engineer** — Franklin, TN

I build and operate production Kubernetes infrastructure at scale. Currently a Devops Engineer, owning EKS provisioning, CI/CD, and observability across a large multi-account AWS environment.

I like turning manual toil into self-service, guard-railed automation — and I care about the reliability of the systems people depend on.

---

### What I work on

- **Infrastructure as Code** — Built and maintain the Terraform platform provisioning **21 EKS clusters across 4 AWS accounts** and 4 environment tiers, driven by a layered, deep-merge configuration model.
- **Kubernetes & service mesh** — EKS, Helm/Helmfile, Istio, Karpenter, admission controllers, ingress/egress gateways across 100+ microservices.
- **CI/CD & developer platform** — GitLab CI/CD for 100+ services; self-service tooling that removes bottlenecks (e.g. an RBAC-gated, audited RDS query pipeline).
- **Observability & reliability** — Led a Fluentd → Splunk OpenTelemetry Collector migration with zero permanent log loss; Datadog monitoring, alerting, and dashboards; blue/green zero-downtime deployments.
- **Cloud security & cost** — Least-privilege cross-account IAM, WAF, secrets management; active right-sizing and scale-to-zero automation.

---

### Featured projects

**[eks-platform-terraform](https://github.com/tamrakareen/eks-platform-terraform)** — Reusable Terraform modules that provision four services across four environments (`dev → qa → stage → prod`) from a single set of modules, with CI-validated plans and release-branch-gated production. Demonstrates DRY multi-environment IaC, secure-by-default resources, cost-vs-HA trade-offs, and GitHub Actions gating.

**[ec2-platform-terraform](https://github.com/tamrakareen/ec2-platform-terraform)** — The EC2 counterpart to the EKS platform: the same workloads built on Auto Scaling Groups + an Application Load Balancer instead of Kubernetes, with web (ALB-fronted) and worker (queue) services. Shows the EKS-vs-EC2 trade-off.

**[terraform-github-actions-demo](https://github.com/tamrakareen/terraform-github-actions-demo)** — The same Terraform pipeline (fmt → init → validate → plan) implemented in both GitHub Actions and GitLab CI, side by side — a practical comparison of the two platforms' models.

**[eks-helm-addons-terraform](https://github.com/tamrakareen/eks-helm-addons-terraform)** — Companion to the platform repo: installs cluster add-ons (metrics-server, cert-manager, ingress-nginx) via Terraform + Helm and bootstraps ArgoCD with the app-of-apps pattern — demonstrating the cluster-creation vs. add-ons boundary and the Terraform → GitOps handoff.

**[rds-query-pipeline](https://github.com/tamrakareen/rds-query-pipeline)** — Self-service database access: an Aurora PostgreSQL cluster (Terraform) plus a GitLab CI pipeline that lets developers run ad-hoc SQL with RBAC tiers, short-lived IAM-token auth (no static credentials), reader/writer endpoint enforcement, and write auditing.

**[connectivity-checks](https://github.com/tamrakareen/connectivity-checks)** — A template for checking TLS endpoints across environments: reports connectivity, the full certificate chain (leaf/intermediate/root) with expiry dates, and a 90-day certificate-expiry report. Includes a self-signed local demo that proves the checker end to end.

---

### Toolbox

`AWS` · `Terraform` · `Kubernetes (EKS)` · `Helm` / `Helmfile` · `Istio` · `Karpenter`
`Docker` · `GitLab CI/CD` · `ArgoCD` · `Datadog` · `Splunk` · `OpenTelemetry`
`Python` · `Bash` · `Go` · `SQL` · `Linux`

---

### Certifications

AWS Certified DevOps Engineer – Professional · AWS Certified Cloud Practitioner · Snowflake SnowPro Core

---

### Connect

- LinkedIn: [linkedin.com/in/tamra-sherwood](https://linkedin.com/in/tamra-sherwood)

<sub>Outside of work: open-water swimmer (last race was in Alaska), pianist, former backpacking guide.</sub>
