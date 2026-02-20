# Florian CARTRON
**DevOps Engineer**

📧 [florian.cartron@gmail.com](mailto:florian.cartron@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/florian-cartron/)
🐙 [GitHub](https://github.com/floriancartron)
✍️ Blog articles: [dev.to](https://dev.to/florian_cartron_99c9a9c4a)

---

## Expertises

| Technology    | Level        |
|---------------|--------------|
| Google Cloud  | Expert       |
| Terraform     | Expert       |
| Ansible       | Advanced     |
| Python        | Intermediate     |
| Go            | Intermediate |
| Docker        | Advanced     |
| Kubernetes    | Expert     |
| Gitlab        | Intermediate |
| Github        | Intermediate |

---

## Certifications

- **Google Cloud:** Professional Cloud Architect, DevOps Engineer, Network Engineer, Authorized Trainer
- **Terraform:** Associate (003)
- **Kubestronaut** (5x Kubernetes Certified)

🏅 [View all badges on Credly](https://www.credly.com/users/florian-cartron.d52d6472/badges#credly)

---

## Work Experience

### Prestashop — DevOps / Platform Engineer
*September 2025 – Present*

Ensuring reliability of the infrastructure and CI/CD pipelines (GitHub Actions).

**Kubernetes platform & GitOps:**

- Designed and led the transition from Terraform-based application deployment to a streamlined GitOps solution with ArgoCD (ApplicationSets and App of Apps patterns), with the goal of easing deployment of existing and new projects through platform engineering.
- Enforced best practices for image builds (12-factor app) to enable a promotion pattern for applications across environments.
- Implemented Crossplane to provision Google Cloud resources (service accounts, Workload Identity configuration, etc.) directly from Helm charts provided to teams, removing the need to maintain Terraform configuration for these objects.
- Deployed Renovate in self-hosted mode to enable frequent, small dependency updates; promoted this best practice within the infra team through a dedicated ritual and a promotion pipeline for infrastructure components, then extended it to dev teams for their application dependencies.

**Observability:**

- Reworked Grafana dashboard deployment using ArgoCD, with templating and provisioning through ConfigMaps.

**FinOps:**

- Implemented Custom Compute Classes to define Kubernetes node preferences and optimize compute costs.
- Deployed Kube-Green to automatically stop non-critical workloads at night.
- Rightsizing of Kubernetes workloads (requests/limits tuning).
- Automated Cloud SQL instance shutdown during off-hours.

**Migration:**

- In charge of migrating legacy workloads hosted on VMs to Google Cloud and Kubernetes.

**Stack:** Google Cloud, Google Kubernetes Engine, GitHub Actions, ArgoCD, Crossplane, OpenTelemetry, Terraform, Terragrunt

---

### Zenika — Cloud & DevOps Consultant / Trainer
*October 2023 – August 2025*

I worked with many customers on SRE missions, migration projects to Google Cloud, and FinOps topics. I was also involved in pre-sales activities, particularly for migration topics and the design of target architectures. In addition, I was a trainer for Kubernetes and Google Cloud topics, and I also authored, updated and maintained the Kubernetes training materials.

---

#### Koralplay — DevOps Consultant *(Zenika, June 2025 – August 2025)*

**Centralized observability platform for 10 Kubernetes clusters:**

- Design of the network architecture (including Private Service Connect for ingestion endpoints to handle overlapping IP address plans across clusters) and infrastructure code to deploy a centralized monitoring platform across 10 Kubernetes clusters.
- Full implementation of the observability stack via ArgoCD: Victoria Metrics, Victoria Logs, Tempo, OpenTelemetry Collector (with tail sampling for traces), Fluentd, Node Exporter, Grafana, Alertmanager.
- Team training on the chosen stack.
- Auto-instrumentation for Java applications via OpenTelemetry.

**Terraform codebase refactoring:**

- Full refactoring of the existing Terraform codebase and introduction of best practices.
- Leveraged Atlantis to automate and streamline Terraform apply workflows via pull requests.

**Stack:** Google Cloud, Terraform, ArgoCD, Victoria Metrics, Victoria Logs, Tempo

---

#### Nutravalia — Cloud Consultant *(Zenika, November 2024 – January 2025)*

- Design of the target architecture: workload migration to Cloud Run (via containerization), performance optimization with Cloud SQL and Redis (shared cache), FinOps.
- Support and acculturation of teams: training sessions (Google Cloud, Terraform, Docker).
- Automation of the release and deployment process: CloudBuild, Semantic Release, Renovate.
- Infrastructure code, deployment and migration.

**Stack:** Google Cloud, Terraform

---

#### Miasin — Cloud Consultant *(Zenika, October 2024 – December 2024)*

Migration from Ionos to Google Cloud of a social network application:

- Design of the target architecture, moving from an "all-in-one" installation on one server (apps and database) to a distributed and scalable architecture (managed SQL database, Redis, instance autoscaling, load balancing...).
- Support and acculturation of teams.
- Infrastructure code, deployment (Terraform) and migration.

**Stack:** Google Cloud, Terraform

---

#### AODocs — Site Reliability Engineer *(Zenika, October 2023 – September 2024)*

I worked within the SRE team in a rich environment, based almost entirely on Google Cloud services. I participated in the migration of the infrastructure with Atlantis (Terraform Pull Request Automation) to optimize costs and performance. I brought my CI/CD expertise on CloudBuild, then designed a new CD solution with CloudDeploy. I automated tasks with Cloud Functions (Python, Go) for integrations like Slack and Jira. I also managed the creation and configuration of landing zones in self-service mode for developers, all automated with Terraform (GCP Projects, GitHub Repositories), and worked on a cloud-agnostic platform design and implementation (Kubernetes based).

**Stack:** Google Cloud (CloudBuild, CloudDeploy, CloudRun, GKE...), Terraform, Atlantis, Python, Go, GitHub, Kubernetes

---

### Orange Business — Cloud Engineer
*2022 – 2023*

As part of a multi-cloud managed services offer, I built cloud environments for several clients within agile teams.

**Infrastructure as Code implementations:**
- Landing Zone (tenants/projects, VPCs, interconnections, IAM, etc.)
- Lift & shift
- Replatforming
- Handover to offshore Run teams

**Design of the monitoring solution for managed services on GCP:**
- Definition of the architecture, based on GCP Cloud Monitoring
- Management of alerting to internal tools
- Industrialization of the solution (Terraform modules)

**Stack:** Google Cloud, Flexible Engine, Terraform, Terraspace, Ansible, Gitlab

---

### Orange — DevOps Engineer
*2019 – 2022*

Contributor within an Agile Release Train for mass-market services, in the system team, with the objectives of streamlining application deployments and transformation to a micro-services architecture with Kubernetes:

- Definition of the technical architecture of the DevOps tooling base, deployment of the infrastructure on private Cloud and on premise, administration of tools (SSO with the internal solution, Jenkins, SonarQube, nginx, apacheDS).
- Development of CI/CD pipelines with Jenkins and Gitlab-CI.
- Lead developer on specific tools in PHP (Laravel framework).

**Stack:** Gitlab-CI, Jenkins, Docker, Kubernetes, Terraform, Ansible, PHP (Laravel), SonarQube, apacheDS, nginx, Openstack

---

### Orange — App, System and Storage Expert
*2014 – 2019*

- System administration, deployment automation and administration of shared storage infrastructure.
- Network administration (Load Balancers, Application Delivery Controllers).

**Stack:** Netapp, Isilon, Linux (Redhat), VMware, F5, Ansible, Openstack

---

## Education

**ENI** — *Master en informatique, Management des systèmes d'information, option Infrastructures* (Master's Degree)

---

## Languages

- **French** — Native
- **English** — Professional
