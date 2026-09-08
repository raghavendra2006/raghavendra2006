<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:0f3460,100:1a1a2e&height=200&section=header&text=Leela%20Krishna%20Raghavendra&fontSize=40&fontColor=ffffff&fontAlignY=38&desc=Cloud%20Engineer%20%E2%80%A2%20DevOps%20Engineer%20%E2%80%A2%20Backend%20Engineer&descAlignY=58&descSize=16&animation=fadeIn" width="100%"/>

<br/>

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=15&pause=1400&color=4A9EFF&center=true&vCenter=true&width=760&lines=AWS+Certified+Developer+%E2%80%93+Associate+%7C+Azure+Administrator+Associate;Designing+CI%2FCD+pipelines+%2C+cloud-native+systems+%26+serverless+architectures;Java+%7C+Spring+Boot+%7C+Docker+%7C+Kubernetes+%7C+Terraform+%7C+Python" />

<br/><br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/patchipulusu-raghavendra/)
[![Portfolio](https://img.shields.io/badge/Portfolio-0f3460?style=for-the-badge&logo=vercel&logoColor=white)](https://my-portfolio-five-snowy-13.vercel.app/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/raghavendra2006)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:patchipulusuraghavendra@gmail.com)

</div>

---

## About

I build systems where infrastructure is defined in code, deployments are fully automated, and every component is observable from day one. My work spans cloud-native backend services, CI/CD pipelines, container orchestration, and secure cloud infrastructure — designed to scale and fail gracefully.

Currently pursuing B.Tech Computer Science Engineering at **Aditya College of Engineering and Technology** (CGPA **8.45 / 10**), with two industry internships delivering measurable outcomes across AWS networking and AI/ML deployment at scale.

The engineering choices I make are driven by one principle: systems should run themselves, not require a human watching them.

---

## Experience

<table width="100%">
<tr>
<td width="50%" valign="top">

**AWS Cloud Intern — Technical Hub Pvt Ltd**
`May 2025 – Jun 2025`

Designed and hardened VPC networking across a production AWS environment supporting 10+ EC2 instances. Restructured IAM policies using least-privilege access patterns, eliminating over-permissioned roles across the full account. Configured subnets, route tables, and security groups to enforce network segmentation and high availability.

`AWS EC2` `VPC` `IAM` `Security Groups` `Route Tables`

[![Verify](https://img.shields.io/badge/Internship%20Letter-0f3460?style=flat-square&logo=google-drive&logoColor=white)](https://drive.google.com/file/d/1uIoucOXvtXpXrFVi441Z5WLCoTkgtD7L/view)

</td>
<td width="50%" valign="top">

**Artificial Intelligence Intern — Infosys Springboard**
`Sep 2025 – Nov 2025`

Built an AI-driven agricultural advisory system and integrated model outputs into backend REST services for near real-time recommendations. Reduced inference latency by deploying inference workloads on AWS Lambda and optimising the full request/response pipeline. Delivered end-to-end ML deployment covering model serving, backend integration, and cloud hosting.

`Python` `AWS Lambda` `REST APIs` `Model Serving` `AI/ML`

[![Verify](https://img.shields.io/badge/Internship%20Letter-0f3460?style=flat-square&logo=google-drive&logoColor=white)](https://drive.google.com/file/d/1OSC9Z4b0YEn80vOYMzoO9W4gIAjCqN8i/view)

</td>
</tr>
</table>

---

## Tech Stack

**Cloud Platforms**

<p>
  <img src="https://skillicons.dev/icons?i=aws,azure,gcp&theme=dark" />
</p>

`EC2` `S3` `Lambda` `VPC` `IAM` `RDS` `DynamoDB` `SQS` `CloudWatch` `CloudFormation` `Azure Resource Manager` `Azure Virtual Networks` `GCP Cloud Run`

**Containers & Orchestration**

<p>
  <img src="https://skillicons.dev/icons?i=docker,kubernetes&theme=dark" />
</p>

`Docker Compose` `Dockerfile` `Kubernetes Deployments` `Helm` `ArgoCD`

**Infrastructure as Code & CI/CD**

<p>
  <img src="https://skillicons.dev/icons?i=terraform,ansible,jenkins,githubactions&theme=dark" />
</p>

`Terraform Modules` `Ansible Playbooks` `Jenkins Pipelines` `GitHub Actions Workflows`

**Backend & Languages**

<p>
  <img src="https://skillicons.dev/icons?i=java,python,spring&theme=dark" />
</p>

`Spring Boot 3` `Spring Security` `Spring Data JPA` `REST APIs` `JWT` `Microservices` `Maven`

**Monitoring & Security**

`CloudWatch` `Prometheus` `Grafana` `SonarQube` `Trivy` `OWASP` `DevSecOps`

**Databases & Storage**

<p>
  <img src="https://skillicons.dev/icons?i=mysql,mongodb&theme=dark" />
</p>

`MySQL` `MongoDB` `DynamoDB` `AWS RDS` `S3`

**Developer Tools**

<p>
  <img src="https://skillicons.dev/icons?i=git,github,linux,bash,vscode,postman&theme=dark" />
</p>

---

## Projects

<table width="100%">
<tr>
<td width="33%" valign="top">

### Student Management System

A production-grade full-stack application with a fully automated DevOps pipeline. Every commit to `main` triggers a quality gate, Docker image build, registry push, and auto-deployment to EC2 — pipeline completes in under 3 minutes.

**Architecture:** Spring Boot 3 backend → MySQL 8 database → Docker Compose → Jenkins pipeline → SonarQube gate → Docker Hub → EC2

**Engineering Highlights**
- JWT + Spring Security applied across all API endpoints
- Photo upload to S3 with direct public URL resolution
- SonarQube quality gate blocks failing commits from reaching production
- Docker Compose manages multi-service environment in a single command

`Java 17` `Spring Boot 3` `MySQL 8` `Docker` `Jenkins` `AWS EC2` `AWS S3`

[![Repo](https://img.shields.io/badge/GitHub-View%20Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/raghavendra2006/Student-Management)

</td>
<td width="33%" valign="top">

### CloudCompare AI

An AI-powered decision engine that analyses and compares AWS, GCP, Azure, OCI, and Alibaba Cloud using Groq LLM (Llama 3.1). Designed to handle concurrent workloads without blocking under bursty traffic.

**Architecture:** Spring Boot 3 → Groq LLM API → MySQL → Jenkins CI/CD → Docker → EC2

**Engineering Highlights**
- Java 21 virtual threads enable high concurrency with minimal overhead
- IP-based rate limiting enforced at 50 requests per 15-minute window
- Resilience4J circuit breaker prevents cascade failures on upstream LLM timeouts
- Chart.js dashboards render cost and performance comparisons in real time

`Java 17` `Spring Boot 3` `Groq AI` `MySQL` `Docker` `Jenkins` `AWS EC2`

[![Repo](https://img.shields.io/badge/GitHub-View%20Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/raghavendra2006/CLOUD-COMPARE-AI)

</td>
<td width="33%" valign="top">

### Serverless ML Inference Pipeline

Event-driven, fully serverless architecture for ML inference at scale. Zero idle compute cost — the pipeline wakes on S3 uploads, processes through Lambda, queues bursts through SQS, and persists results in DynamoDB.

**Architecture:** S3 Upload → Lambda Trigger → SQS Queue → Inference Lambda → DynamoDB

**Engineering Highlights**
- S3 object events trigger Lambda inference automatically — no polling
- SQS absorbs burst traffic and ensures no inference requests are dropped
- DynamoDB provides low-latency result retrieval at any scale
- 1024MB Lambda allocation with sub-30s timeout per inference job

`Python` `AWS Lambda` `S3` `SQS` `DynamoDB`

[![Repo](https://img.shields.io/badge/GitHub-View%20Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/raghavendra2006/Serverless-ML-Inference-Pipeline)

</td>
</tr>
</table>

---

## Engineering Philosophy

These principles guide every system I design and every line of infrastructure I write.

| Principle | What it means in practice |
|:---|:---|
| **Automation First** | If a task runs twice manually, it becomes a pipeline. Manual steps are toil, not process. |
| **Everything as Code** | Infrastructure, configuration, security policies, and pipelines live in version control — not dashboards. |
| **Shift Left Security** | Security checks (SAST, image scanning, IAM validation) belong in the CI pipeline, not in post-deployment reviews. |
| **Cloud Native Design** | Stateless services, event-driven patterns, managed datastores. Design for ephemerality and horizontal scale. |
| **Observability by Default** | Metrics, logs, and traces are built in from the start. If you can't measure it, you can't operate it. |
| **Cost as a System Property** | Resource sizing, auto-scaling policies, and serverless patterns are engineering decisions — not finance ones. |
| **Reliability over Velocity** | Circuit breakers, retries, graceful degradation, and health checks are not optional extras. |

---

## Certifications

<div align="center">

| Certification | Issuer | Status | Credential |
|:---|:---:|:---:|:---:|
| AWS Certified Developer – Associate | Amazon Web Services | Active | [View](https://drive.google.com/file/d/1wsZBHxZy_Vry1O9odeNXuOchrWr11Hf8/view?usp=drive_link) |
| Azure Administrator Associate | Microsoft | Active · Expires Aug 2027 | [View](https://learn.microsoft.com/en-us/users/patchipulusuleelakrishnaraghavendr-2916/credentials/certification/azure-administrator?tab=credentials-tab) |
| AWS Cloud Developing | Amazon Web Services | Completed | [View](https://drive.google.com/file/d/1sa0FCx4swCmwd1lZAujInIdtZDgbHfeo/view) |
| Google Cloud Career Launchpad | Google | Completed | — |

</div>

---

## GitHub Analytics

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=raghavendra2006&theme=react-dark&hide_border=true&area=true&radius=6" width="100%" alt="Contribution Graph"/>

<br/><br/>

<img height="165" src="https://github-readme-stats.vercel.app/api?username=raghavendra2006&show_icons=true&theme=tokyonight&hide_border=true&border_radius=10&include_all_commits=true&count_private=true&hide=issues"/>
&nbsp;
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=raghavendra2006&layout=compact&theme=tokyonight&hide_border=true&border_radius=10&langs_count=8"/>

<br/><br/>

<img src="https://streak-stats.demolab.com?user=raghavendra2006&theme=tokyonight&hide_border=true&border_radius=10" alt="GitHub Streak"/>

<br/><br/>

<img src="https://github-profile-trophy.vercel.app/?username=raghavendra2006&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=6" alt="GitHub Trophies"/>

</div>

---

## Currently Exploring

These are the areas I am actively building depth in right now.

```text
Advanced Kubernetes      ████████████░░░   Operators, custom controllers, resource management
Platform Engineering     █████████░░░░░░   Internal developer platforms, golden paths
Service Mesh             ███████░░░░░░░░   Istio, traffic management, mTLS
Distributed Systems      ████████░░░░░░░   Consensus, eventual consistency, CAP theorem
MLOps                    ██████░░░░░░░░░   Model versioning, feature stores, deployment pipelines
GitOps                   █████████░░░░░░   ArgoCD, Flux, declarative delivery
Cloud Security           ████████░░░░░░░   Zero-trust, secrets management, policy as code
System Design            ████████████░░░   Large-scale architecture patterns and trade-offs
```

---

## Open Source

My current open-source footprint is through personal projects built in public — all repositories documented with architecture decisions, infrastructure code, and deployment runbooks. The goal is to build in the open and make the systems reusable.

**Planned contributions:**

- Terraform modules for production-ready AWS environments
- Helm charts for Spring Boot microservices deployments
- GitHub Actions reusable workflows for Java + Docker + SonarQube pipelines
- ArgoCD ApplicationSet templates for multi-environment GitOps delivery

Open to collaborating on cloud infrastructure tooling, DevOps automation, and backend platform engineering work.

---

## Education

<div align="center">

| Institution | Degree | Period | Score |
|:---|:---|:---:|:---:|
| Aditya College of Engineering and Technology, Surampalem | B.Tech — Computer Science Engineering | 2023 – Present | CGPA 8.45 / 10 |
| Narayana Junior College, Andhra Pradesh | Class 12 | 2021 – 2023 | 90.4% |

</div>

---

## Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/patchipulusu-raghavendra/)
[![Portfolio](https://img.shields.io/badge/Portfolio-0f3460?style=for-the-badge&logo=vercel&logoColor=white)](https://my-portfolio-five-snowy-13.vercel.app/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/raghavendra2006)
[![Gmail](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:patchipulusuraghavendra@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/raghavendra2006)
[![HackerRank](https://img.shields.io/badge/HackerRank-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white)](https://www.hackerrank.com/raghavendra2006)

</div>

---

<div align="center">

**Open to Cloud Engineer, DevOps Engineer, and Backend Engineer roles — internships and full-time.**

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,50:0f3460,100:0d1117&height=120&section=footer&animation=fadeIn" width="100%"/>

<div align="center">
  <sub>If it runs twice manually, it's already a pipeline.</sub>
</div>
