# Hi there 👋, I'm Brian

**IT Infrastructure & Cloud Operations** &nbsp;·&nbsp; 📍 San Diego, CA

I'm an infrastructure and cloud operations engineer moving from traditional day-to-day Ops into automation-driven operations — building practical labs and tooling that make recurring operational work faster, more reliable, and less manual. Most projects start with one question: how would I deploy it, validate it, troubleshoot it, secure it, document it, and support it in a real environment?

The work below is organized around four practical lanes: cloud infrastructure, monitoring and observability, infrastructure automation, and workflow/platform automation.

---

## ☁️ Cloud Infrastructure

### Cloud Infrastructure Deployments
**Hands-on AWS/Azure build reference** &nbsp;`Azure` `AWS` `Terraform` `Ansible` `Jenkins` `Linux`

The fundamentals underneath everything else here — provisioning, validating, and troubleshooting cloud infrastructure by hand before automating it.

<details>
<summary>What's inside</summary>
<br>

- **Azure:** VMs, AKS, App Service, Key Vault, networking, RBAC
- **AWS:** EC2, IAM, Secrets Manager, Elastic Beanstalk
- **Ansible:** baseline config, NGINX deploy, health checks, daily ops
- **Terraform + Jenkins:** IaC examples and CI/CD practice

</details>

**[View repo →](https://github.com/byamada64/cloud-infrastructure-deployments)**

---

## 📊 Monitoring & Observability

### Grafana / Prometheus / SNMP Monitoring Lab
**Dashboards, metrics, exporters, and operational validation** &nbsp;`Grafana` `Prometheus` `SNMP` `Linux` `Docker`

Monitoring is the operations layer that connects infrastructure work to real support value. This section focuses on practical visibility: collecting metrics, validating health, building dashboards, identifying gaps, and documenting checks that could support daily operations or NOC handoff.

<details>
<summary>Planned / covered areas</summary>
<br>

- Grafana dashboards for infrastructure and network visibility
- Prometheus metrics and exporter validation
- Linux/system health checks and dashboard panels
- SNMP monitoring concepts for network devices
- Alerting, troubleshooting notes, and operational runbook checks

</details>

> Repo in progress.

---

## ⚙️ Infrastructure Automation

**Same toolset, applied to consistency and repeatable handoff** &nbsp;`Terraform` `Ansible` `Jenkins` `GitHub Actions`

The automation patterns behind this lane — repeatable provisioning, Ansible baseline configs, and CI/CD validation — live in *Cloud Infrastructure Deployments* above. The goal isn't automation for its own sake; it's fewer missed steps and cleaner operational handoff.

**[View repo →](https://github.com/byamada64/cloud-infrastructure-deployments)**

---

## 🧩 Workflow & Platform Automation

### 🔷 TracIT
**Self-hosted platform with an Azure hub-and-spoke migration target** &nbsp;`Docker` `Terraform` `Azure` `PostgreSQL` `Redis` `n8n`

Shows how I'd take a self-hosted Ops setup and evolve it into governed, production-style cloud infrastructure — the migration path most teams actually need.

<details>
<summary>Design highlights + architecture diagram</summary>
<br>

<img src="https://github.com/byamada64/tracit/raw/main/docs/tracit-architecture.png" width="600" alt="TracIT architecture diagram">

- Docker self-hosted services behind reverse proxy + secure access controls
- Azure hub-and-spoke target: app spoke + data spoke, force-tunneled through NVA
- Cost comparison: NVA-based routing vs. Azure Firewall
- CI/CD planning, container validation, security scanning

</details>

**[View repo →](https://github.com/byamada64/tracit)**

---

### 🤖 AI Secretary
**Job search workflow automation** &nbsp;`Python` `FastAPI` `SQLite` `React` `Chrome Extension`

A real example of replacing manual, repetitive tracking with an automated pipeline — the same instinct I'd apply to operational toil in a production environment.

A personal system that ingests job postings from browser and email, scores them against my resume, and tracks the full application lifecycle.

<details>
<summary>What it does</summary>
<br>

- Captures job data from browser extension and email-based intake
- Classifies roles into lanes such as cloud, infrastructure, support, and ops
- Tracks application status, follow-ups, recruiter notes, and resume alignment
- FastAPI backend + SQLite database + React/Vite dashboard

</details>

> Public repo pending — sanitizing keys and personal workflow data first.

---

## Core Areas

Cloud infrastructure, Windows/Linux systems, VMware, Active Directory, Entra ID, Terraform, Ansible, PowerShell, Bash, Docker, monitoring, security, networking, ServiceNow, Jira, documentation, and IT service delivery.

<img src="https://skillicons.dev/icons?i=azure,aws,terraform,ansible,docker,linux,py,react,postgres,git" height="40" />

Also working with: Bash · PowerShell · Jenkins · GitHub Actions · Nginx · Grafana · Prometheus · FastAPI · Redis · VMware · Windows Server · Active Directory / Entra ID · ServiceNow · Jira

---

## Currently Working Toward

I am currently focused on Security+ preparation, Azure administration, AWS architecture fundamentals, infrastructure automation, monitoring dashboards, and practical runbook documentation.

🔷 AZ-104 (Azure Administrator) &nbsp;·&nbsp; ☁️ AWS Solutions Architect Associate &nbsp;·&nbsp; 🔐 CompTIA Security+

---

## Contact

🔗 [LinkedIn](https://www.linkedin.com/in/brian-yamada) &nbsp;·&nbsp; 💻 [GitHub](https://github.com/byamada64)
