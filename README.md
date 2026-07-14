# Hi, I'm Kotharu Nikhil Sai Shankar

### 🌟 DevOps Engineer | AWS | Kubernetes | Terraform | CI/CD Automation

![Profile Views](https://komarev.com/ghpvc/?username=nikhilsaishankar&color=blue&style=flat)

---

## 👨‍💻 About Me

DevOps Engineer with **4+ years** of hands-on experience in AWS cloud infrastructure, CI/CD automation, and container orchestration. Passionate about building reliable, scalable delivery pipelines, reducing environment drift through Infrastructure as Code, and automating releases end to end.

- 💼 Working as a **DevOps Engineer at GrayQuest**, Mumbai
- ☁️ Experienced in **AWS cloud infrastructure**, DevOps automation, and scalable application deployments
- 🔧 Skilled in **CI/CD pipelines, Infrastructure as Code, container orchestration, and monitoring solutions**
- 🚦 Focused on **reliability, high availability, security, and delivery speed**
- 🔄 Practicing **GitOps** with Argo CD and **blue-green / canary deployment** strategies
- 🌱 Currently exploring advanced Kubernetes patterns, GitOps at scale, and cloud security practices
- ✍️ I write about DevOps on [Medium](https://medium.com/@nikhilsaishankar)

---

## 🚀 Skills and Technologies

### ☁️ Cloud Platform
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)

EC2 • ECR • ECS • EKS • S3 • VPC • IAM • ASG • ELB

### 🐳 Containerization & Orchestration
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

Deployments • StatefulSets • Services • Ingress • HPA • NetworkPolicy • Rolling Updates • Blue-Green & Canary

### ⚙️ CI/CD & Infrastructure as Code (IaC)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Argo CD](https://img.shields.io/badge/Argo%20CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)
![GitOps](https://img.shields.io/badge/GitOps-100000?style=for-the-badge&logo=git&logoColor=white)

Declarative Pipelines • GitHub Webhooks • Quality Gates • Automated Sync & Drift Self-Healing

### 📊 Monitoring & Observability
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

Alerting Rules • Dashboards • Application Health Tracking

### 🔐 Security & Quality
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=for-the-badge&logo=aqua&logoColor=white)

Vulnerability Scanning • OWASP Security Practices • Blocking Quality Gates in CI

### 💾 Database
![AWS RDS](https://img.shields.io/badge/AWS%20RDS-527FFF?style=for-the-badge&logo=amazonrds&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### 💻 Scripting & Operating Systems
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### 🔄 Version Control & Build
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)

---

## 💼 Professional Experience

### 🏢 DevOps Engineer — GrayQuest, Mumbai *(Dec 2023 - Present)*
- Designed multi-stage **CI/CD pipelines** in **Jenkins** (Declarative Pipelines) integrating **Maven** builds and **SonarQube** quality scans, reducing end-to-end deployment time by **40%**
- Built reusable **Terraform** modules for AWS infrastructure, reducing manual provisioning effort and improving environment consistency
- Containerized production services, published images to AWS **ECR**, and deployed them on **ECS**, cutting environment mismatch incidents by **60%**
- Operated production workloads on **Kubernetes** with rolling updates and supported rollback procedures
- Implemented **blue-green and canary deployments** for low-risk, near-zero-downtime releases
- Configured **Prometheus** alerting and **Grafana** dashboards to surface production issues early

### 🏢 Associate DevOps Engineer — Dignity Of Noble, Hyderabad *(Feb 2023 - Nov 2023)*
- Provisioned and managed **AWS** infrastructure with **Terraform**, keeping every change trackable, auditable, and reversible
- Implemented the organization's first **Jenkins CI/CD pipeline** with GitHub webhooks
- Integrated **Trivy** vulnerability scanning and **OWASP** security practices into the pipeline
- Supported early **Kubernetes** adoption with manifests and development-cluster deployments

### 🏢 Junior DevOps Engineer — Careerlabs Technologies, Bangalore *(Dec 2021 - Jan 2023)*
- Migrated legacy manual deployments to containerized runtimes with optimized Dockerfiles
- Maintained and extended **Jenkins CI/CD** jobs and embedded automated verification into CI workflows
- Administered **Git** repositories, branching strategies, and pull-request workflows

---

## 🌟 Featured Project

### 🩸 [PulseDeploy: GitOps-Driven Blood Donation Platform on AWS EKS](https://github.com/nikhilsaishankar/Kubernetes-e2e-php)

> A complete **end-to-end delivery platform** — from infrastructure provisioning to GitOps-reconciled production workloads.

**🔁 The E2E flow:**

```
Terraform → Amazon EKS → Jenkins CI → SonarQube Gate → Docker Build → Trivy Scan → Docker Hub → Argo CD → Kubernetes
  (IaC)     (cluster +    (7-stage     (blocking        (app + db      (security     (registry)   (GitOps     (HPA, PDB,
             EBS CSI)      pipeline)    quality gate)    images)        gate)                       sync)       StatefulSet)
```

- 🏗️ **Infrastructure as Code**: EKS cluster, managed node group, and EBS CSI storage driver provisioned entirely through **Terraform**
- 🔄 **CI pipeline**: seven **Jenkins** stages — checkout, **SonarQube** analysis, blocking quality gate, **Docker** image builds, **Trivy** vulnerability scans, registry push
- 🚀 **GitOps CD**: **Argo CD** continuously syncs the cluster to Git with automated drift self-healing — Git is the single source of truth
- ☸️ **Production-grade Kubernetes**: HPA autoscaling, PodDisruptionBudgets, MySQL **StatefulSet** with dynamic EBS persistence, NGINX **Ingress** behind an AWS ELB, and least-privilege **NetworkPolicy** isolation

`AWS EKS` `Terraform` `Jenkins` `Argo CD` `Kubernetes` `Docker` `SonarQube` `Trivy`

---

## 📈 Key Achievements

- ⚡ Reduced end-to-end deployment time by **40%** with multi-stage Jenkins CI/CD pipelines
- 📦 Cut environment mismatch incidents by **60%** through containerization and ECR/ECS delivery
- 🔄 Implemented **blue-green and canary deployments** on Kubernetes for near-zero-downtime releases
- 🏗️ Built reusable **Terraform** modules reducing manual provisioning effort
- 📊 Configured **Prometheus** alerting and **Grafana** dashboards to catch production issues early
- 🔐 Embedded **Trivy** vulnerability scanning and **OWASP** security practices into CI/CD

---

## 🌱 Currently Exploring

- Advanced Kubernetes and GitOps workflows
- Cloud security and vulnerability management
- Observability and reliability engineering
- Infrastructure automation at scale

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api?username=nikhilsaishankar&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&rank_icon=github" alt="Nikhil's GitHub Stats" />
</div>

<div align="center">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=nikhilsaishankar&layout=compact&theme=tokyonight" alt="Top Languages" />
</div>

---

## 📫 Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nikhilsaishankarkotharu/)
[![Medium](https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@nikhilsaishankar)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nikhilsaishankar@gmail.com)

---

⭐ *Thank you for visiting my profile! Let's connect and build something reliable together.*
