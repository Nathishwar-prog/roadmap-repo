# ☁️ DevOps & Cloud Roadmap

> **Goal:** Learn how to build, ship, and operate software reliably at scale — from CI/CD pipelines and containers to cloud infrastructure and monitoring.

---

## 📌 Overview

| Stage | Topics | Estimated Time |
|---|---|---|
| 🟢 Beginner | Linux, Git, Networking basics, Bash scripting | 4–6 weeks |
| 🟡 Intermediate | Docker, CI/CD, Cloud fundamentals, IaC | 8–12 weeks |
| 🔴 Advanced | Kubernetes, Advanced Cloud, SRE, Security | 10–16 weeks |

---

## 🟢 Stage 1 — Beginner

**Goal:** Get comfortable with the command line, networking, and version control — the foundations of every DevOps workflow.

### 🐧 Linux & Command Line
- ✅ File system navigation (`ls`, `cd`, `pwd`, `find`)
- ✅ File manipulation (`cp`, `mv`, `rm`, `mkdir`, `touch`)
- ✅ Permissions (`chmod`, `chown`, `sudo`)
- ✅ Processes (`ps`, `top`, `htop`, `kill`)
- ✅ Package managers (`apt`, `yum`, `brew`)
- ✅ Text processing (`grep`, `awk`, `sed`, `cut`, `wc`)
- ✅ SSH (connecting to remote servers, key pairs)

### 📜 Bash Scripting
- ✅ Variables, conditionals, loops
- ✅ Functions and arguments
- ✅ Input/output redirection and piping
- ✅ Cron jobs for task scheduling
- ✅ Writing automation scripts

### 🌐 Networking Basics
- ✅ IP addresses, subnets, DNS, ports
- ✅ HTTP/HTTPS, TCP/UDP protocols
- ✅ `curl`, `wget`, `ping`, `netstat`, `traceroute`
- ✅ Firewalls and security groups (conceptual)

### 🔀 Git & Version Control
- ✅ Git fundamentals: `init`, `add`, `commit`, `push`, `pull`
- ✅ Branching strategies: Gitflow, trunk-based development
- ✅ Pull requests, code reviews, merging
- ✅ GitHub / GitLab workflows

### 🛠️ Beginner Projects:
- 🖥️ Write a Bash script that backs up files to a timestamped directory
- 🔁 Automate server setup with a shell script
- 🌐 Deploy a static website to GitHub Pages or Netlify

---

## 🟡 Stage 2 — Intermediate

**Goal:** Containerize applications, automate deployments, and work with cloud providers.

### 🐳 Docker
- ✅ What is a container? Containers vs VMs
- ✅ `Dockerfile` — building custom images
- ✅ `docker build`, `docker run`, `docker ps`, `docker exec`
- ✅ Docker volumes and networking
- ✅ `docker-compose` — multi-container applications
- ✅ Publishing images to Docker Hub

### ⚙️ CI/CD Pipelines
- ✅ What is CI/CD? Continuous Integration vs Continuous Deployment
- ✅ **GitHub Actions** — writing workflows (`.github/workflows/`)
- ✅ GitLab CI / Jenkins (concepts)
- ✅ Pipeline stages: lint → test → build → deploy
- ✅ Environment variables and secrets management
- ✅ Automated testing in pipelines

### ☁️ Cloud Fundamentals
Pick one cloud provider to start with (**AWS is most popular**):

#### AWS Essentials
- ✅ IAM — users, roles, policies
- ✅ EC2 — virtual machines
- ✅ S3 — object storage
- ✅ RDS — managed relational databases
- ✅ VPC — virtual private cloud and networking
- ✅ Route 53 — DNS management
- ✅ CloudWatch — monitoring and logging
- ✅ ECS / ECR — containers on AWS

#### Alternatives
- ✅ **Google Cloud Platform (GCP)** — Compute Engine, Cloud Run, GKE
- ✅ **Azure** — VM, AKS, Azure DevOps

### 🏗️ Infrastructure as Code (IaC)
- ✅ **Terraform** — write, plan, apply infrastructure
- ✅ Providers, resources, variables, outputs
- ✅ Remote state with S3 + DynamoDB
- ✅ Terraform modules for reusability
- ✅ **Ansible** — configuration management and automation

### 🛠️ Intermediate Projects:
- 🐳 Dockerize a web app and push to Docker Hub
- ⚙️ Set up a GitHub Actions pipeline that runs tests and deploys on merge
- ☁️ Deploy a web application on AWS EC2 with a custom domain
- 🏗️ Provision cloud infrastructure with Terraform

---

## 🔴 Stage 3 — Advanced

**Goal:** Operate production systems at scale with reliability, security, and automation.

### ☸️ Kubernetes (K8s)
- ✅ Pods, Deployments, Services, Namespaces
- ✅ ConfigMaps and Secrets
- ✅ Persistent Volumes and StatefulSets
- ✅ Ingress controllers and load balancing
- ✅ Helm — package manager for Kubernetes
- ✅ HPA — Horizontal Pod Autoscaling
- ✅ Managed K8s: EKS (AWS), GKE (GCP), AKS (Azure)

### 📊 Monitoring & Observability
- ✅ **Prometheus** — metrics collection and alerting
- ✅ **Grafana** — dashboards and visualization
- ✅ **ELK Stack** — centralized logging (Elasticsearch, Logstash, Kibana)
- ✅ **Datadog / New Relic** — full-stack observability
- ✅ Distributed tracing with Jaeger or Zipkin
- ✅ SLOs, SLAs, SLIs — reliability engineering

### 🔒 DevSecOps
- ✅ Secrets management with HashiCorp Vault
- ✅ Container scanning: Trivy, Snyk
- ✅ SAST/DAST — static and dynamic security testing in pipelines
- ✅ Policy as Code with Open Policy Agent (OPA)

### 🚀 Advanced Deployment Strategies
- ✅ Blue/Green deployments
- ✅ Canary releases
- ✅ Feature flags
- ✅ GitOps with ArgoCD or Flux

### 🛠️ Advanced Projects:
- ☸️ Deploy a microservices app to Kubernetes with Helm charts
- 📊 Build a full observability stack (Prometheus + Grafana + Loki)
- 🔒 Implement a secure CI/CD pipeline with vulnerability scanning
- 🚀 Set up a GitOps workflow with ArgoCD

---

## ⏱️ Estimated Time

| Stage | Duration |
|---|---|
| Beginner | 4–6 weeks (1–2 hrs/day) |
| Intermediate | 8–12 weeks (2 hrs/day) |
| Advanced | 10–16 weeks (2–3 hrs/day) |
| **Total** | **~7–10 months** |

---

## 📚 Resources

### Free Courses:
- 🔗 [Linux Command Line Basics (Udacity)](https://www.udacity.com/course/linux-command-line-basics--ud595) — Free intro to Linux
- 🔗 [Docker Official Get Started](https://docs.docker.com/get-started/) — Official Docker tutorial
- 🔗 [GitHub Actions Docs](https://docs.github.com/en/actions) — Official GitHub Actions documentation
- 🔗 [AWS Free Tier](https://aws.amazon.com/free/) — Hands-on AWS with free credits
- 🔗 [Terraform Learn](https://developer.hashicorp.com/terraform/tutorials) — Official Terraform tutorials (free)
- 🔗 [KodeKloud Free Labs](https://kodekloud.com/) — Hands-on DevOps labs

### Books:
- 📖 *The Phoenix Project* — Gene Kim (DevOps culture, written as a novel)
- 📖 *The DevOps Handbook* — Gene Kim et al. (comprehensive DevOps guide)
- 📖 *Site Reliability Engineering* — Google (free at [sre.google](https://sre.google/books/))
- 📖 *Kubernetes in Action* — Marko Lukša (deep K8s guide)
- 📖 *Terraform: Up & Running* — Yevgeniy Brikman

### Practice:
- 🏋️ [Play with Docker](https://labs.play-with-docker.com/) — Free browser-based Docker sandbox
- 🏋️ [Killercoda](https://killercoda.com/) — Hands-on Kubernetes and Linux scenarios
- 🏋️ [AWS Skill Builder](https://skillbuilder.aws/) — Official AWS training (some free)
- 🏋️ [TechWorld with Nana (YouTube)](https://www.youtube.com/@TechWorldwithNana) — Best DevOps YouTube channel

---

## 🏅 Certifications to Aim For

| Certification | Provider | Level |
|---|---|---|
| AWS Cloud Practitioner | AWS | 🟢 Beginner |
| AWS Solutions Architect Associate | AWS | 🟡 Intermediate |
| Certified Kubernetes Administrator (CKA) | CNCF | 🔴 Advanced |
| HashiCorp Certified: Terraform Associate | HashiCorp | 🟡 Intermediate |
| Google Associate Cloud Engineer | GCP | 🟡 Intermediate |

---

## 🔮 What's Next?

- 🏗️ Scale your systems: [System Design Roadmap](../system-design/README.md)
- 🔐 Secure your infrastructure: [Cybersecurity Roadmap](../cybersecurity/README.md)
- 🌐 Full-stack apps to deploy: [Web Development Roadmap](../web-development/README.md)

---

[⬅️ Back to Main README](../../README.md)
