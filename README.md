# DevOps + Python Bootcamp

My hands-on learning repo combining two Udemy courses into one path: **Python for automation and building real projects**, and **DevOps for shipping and running them in the cloud**. Everything I build, script, configure, and deploy along the way lives here.

> Personal study notes and my own code only! (No course videos, slides, or paid materials are included.)

## At a Glance

| | DevOps | Python | Combined |
|---|---|---|---|
| Course | [Master DevOps with AWS, Docker, Kubernetes, GCP, GitHub Actions, ArgoCD, GitOps, Terraform, Monitoring & AI](https://www.udemy.com/course/decodingdevops/) | [100 Days of Code: Python Pro Bootcamp](https://www.udemy.com/course/100-days-of-code/) | |
| Video hours | 64 h | 57 h | **~121 h** |
| Lectures | 378 | 604 | **982** |
| Style | Cloud + tooling labs, 8+ real projects | 100 projects in 100 days | **Learn, build, deploy** |

Hours are Udemy's listed video time. Labs, exercises, and debugging will take longer.

## Why Combine Them

- **Python** is the glue of DevOps (scripting, AWS automation, APIs, tooling).
- **DevOps** is how the Python apps I build get containerized, tested, deployed, and monitored.
- The end goal is a portfolio that shows both sides: apps I wrote, and the pipeline and infrastructure that runs them.

## My Starting Point

I'm not starting from zero so I'll list what I already know and spend time where there are gaps / new things.

| Area | Status |
|---|---|
| Python fundamentals (server-side programming class) | Known, refresh and skim |
| Linux fundamentals, networking, YAML & JSON | Known, skim |
| Bash scripting, variables, conditions, loops | Known, skim |
| Basic automation | Touched, going deeper |
| CI/CD, Docker | Known, skim |
| Cloud (AWS/GCP), Terraform, Ansible, Kubernetes, monitoring, GitOps | **New, main focus** |

## What I'll Learn

### DevOps Track

| Layer | Topics |
|---|---|
| **Foundation** (skim) | Linux and server management, Vagrant, networking, YAML/JSON, Bash, multi-VM setup (VProfile project) |
| **AI-assisted automation** | GitHub Copilot for scripting, Amazon Q for cloud automation, AI-assisted Helm |
| **AWS** | IAM, EC2, EBS, ELB, S3, RDS, Route53, Auto Scaling, CloudWatch, SSM, CLI. Projects: lift-and-shift and re-architecting an app on AWS |
| **CI/CD** | Git, GitHub, Maven, Jenkins (Nexus, SonarQube), GitHub Actions (self-hosted runners, security scanning), GitLab CI/CD |
| **Python automation** | OS automation, AWS automation with Python, Amazon Q assisted development |
| **Infrastructure as Code** | Terraform (variables, modules, remote state, best practices). Project: AWS VPC with Terraform |
| **Monitoring & observability** | Prometheus, Grafana, Loki, Alloy, PromQL, alerting, Slack integration |
| **Configuration management** | Ansible (playbooks, roles, templates, handlers), AWS automation with Ansible |
| **Advanced AWS** | VPC deep dive, Lambda, custom metrics, Elastic Beanstalk, CodePipeline. Project: CI/CD on AWS |
| **Google Cloud** | Multi-tier app on GCP: VPC, firewall rules, Cloud SQL, Memorystore, Cloud DNS, managed instance groups, HTTPS load balancers |
| **Containers & Kubernetes** | Docker, Kubernetes (pods, deployments, services, ingress, autoscaling), Helm, Lens. Project: VProfile on Kubernetes |
| **GitOps** | End-to-end project: GitHub Actions, Docker builds, registry, Helm, Kubernetes, ArgoCD |

### Python Track

| Area | Topics |
|---|---|
| **Core & tooling** | Python 3, PyCharm, Jupyter, Google Colab, Git/GitHub, command line |
| **Automation & scraping** | Scripting, Beautiful Soup, Selenium, Requests |
| **Data science** | Pandas, NumPy, Matplotlib, Plotly, Seaborn, Scikit-learn |
| **Web development** | HTML5, CSS3, Bootstrap, Flask, REST APIs, WTForms, authentication |
| **Databases** | SQL, SQLite, PostgreSQL |
| **Apps & games** | Tkinter desktop apps, Turtle games (Snake, Pong, Blackjack) |
| **Deployment** | GitHub Pages, Heroku, Gunicorn |

## What I'll Build

- **Python:** 100 projects, including an auto-apply LinkedIn bot, automated birthday emails/SMS, a full blog site, a public API, and data analysis projects (Google Trends, Lego datasets, Google Play Store).
- **DevOps:** a multi-VM environment, an AWS lift-and-shift and re-architecture, a Terraform-built AWS VPC, a multi-tier GCP deployment, VProfile on Kubernetes, and a full GitOps platform.
- **Capstone (my own idea):** take a Flask app from the Python track, containerize it with Docker, build it with GitHub Actions, provision infrastructure with Terraform, deploy it with Helm and ArgoCD, and monitor it with Prometheus and Grafana.

## What I'll Have at the End

- Build and manage cloud infrastructure on **AWS and GCP**
- Write **Infrastructure as Code** with Terraform and configure systems with Ansible
- Automate with **Bash and Python**
- Build **CI/CD pipelines** with Jenkins, GitHub Actions, and GitLab CI
- Containerize with **Docker** and run workloads on **Kubernetes**
- Set up **monitoring and observability** (Prometheus, Grafana, Loki, Alloy)
- Ship with **GitOps** (ArgoCD + Helm)
- Use **AI tools** (Copilot, Amazon Q) in real DevOps workflows
- Have a **portfolio of 100+ Python projects** plus real DevOps projects on GitHub

## Repo Structure

```
.
├── README.md
├── devops/
│   ├── 01-foundation/
│   ├── 02-aws/
│   ├── 03-cicd/
│   ├── 04-iac-terraform/
│   ├── 05-monitoring/
│   ├── 06-ansible/
│   ├── 07-gcp/
│   ├── 08-docker-kubernetes/
│   └── 09-gitops/
├── python/
│   └── day-001-name/ ... day-100-name/
├── capstone/
└── notes/
```

## Progress

**DevOps**
- [ ] Foundation (skim)
- [ ] AI-assisted automation
- [ ] AWS fundamentals + projects
- [ ] CI/CD (Jenkins, GitHub Actions, GitLab)
- [ ] Python automation
- [ ] Terraform
- [ ] Monitoring & observability
- [ ] Ansible
- [ ] Advanced AWS + CI/CD on AWS
- [ ] GCP project
- [ ] Docker & Kubernetes
- [ ] GitOps project

**Python**
- [ ] Refresh fundamentals
- [ ] Automation & scraping
- [ ] Data science
- [ ] Web development (Flask, APIs, databases)
- [ ] GUI apps & games
- [ ] Projects: 0 / 100

**Capstone**
- [ ] Python app to containers to CI/CD to Kubernetes to GitOps

## Course Links

- [Decoding DevOps (Udemy)](https://www.udemy.com/course/decodingdevops/)
- [100 Days of Code: Python Pro Bootcamp (Udemy)](https://www.udemy.com/course/100-days-of-code/)
