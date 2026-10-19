<!-- Put this file in a PUBLIC repository named exactly "mekkiamine" (same as your username), at the root, named README.md -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a3c6e,100:2f81f7&height=190&section=header&text=Mohamed%20Amine%20Mekki&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Cloud%20%C2%B7%20DevOps%20%C2%B7%20DevSecOps%20%C2%B7%20Platform%20Engineering&descSize=17&descAlignY=58" alt="header" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&pause=1200&color=2F81F7&center=true&vCenter=true&width=640&lines=Final-year+Computer+Engineering+student+%40+ESPRIT;I+design+and+deploy+on+OpenStack+%26+Kubernetes;GitOps+%C2%B7+Keycloak+%C2%B7+OAuth2+%C2%B7+Secure+microservices;Open+to+internships%2C+apprenticeships+%26+junior+roles" alt="typing animation" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mohamed%20Amine%20Mekki-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohamed-amine-mekki-b58b94212/)
[![Email](https://img.shields.io/badge/Email-mekkiamine34%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mekkiamine34@gmail.com)
![Location](https://img.shields.io/badge/Tunis%2C%20Tunisia-1a3c6e?style=for-the-badge&logo=googlemaps&logoColor=white)

</div>

---

## 👋 About me

Final-year Computer Engineering student at **ESPRIT**, specializing in **cloud-native architectures**, **DevSecOps practices** and **secure microservices platforms**.

I design and deploy production-grade systems on **OpenStack** and **Kubernetes** using **Docker**, with **GitOps** delivery (GitHub Actions, Argo CD). My focus is **identity management** (Keycloak, OAuth2, JWT, RBAC) and **infrastructure security**.

- 🔭 Currently working on **E-ComK8s**: a GitOps-driven Kubernetes platform for an e-commerce application
- 🎯 Interested in: Cloud Engineering · DevOps · DevSecOps · Platform Engineering
- 📬 Available from **December 1, 2026** for an end-of-studies internship (PFE), in Tunisia or abroad

---

## 🚀 Featured projects

| Project | What it is | Stack |
|---|---|---|
| **[E-ComK8s](https://github.com/mekkiamine/E-ComK8s)** | Containerized e-commerce app deployed on Kubernetes with CI/CD and GitOps (internship project at SIGA Solutions). HPA, MetalLB, NGINX Ingress, Longhorn, ELK logging, SonarQube, Sealed Secrets | ![](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white) ![](https://img.shields.io/badge/Argo%20CD-EF7B4D?logo=argo&logoColor=white) ![](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white) ![](https://img.shields.io/badge/Spring%20Boot-6DB33F?logo=springboot&logoColor=white) ![](https://img.shields.io/badge/Angular-DD0031?logo=angular&logoColor=white) |
| **[MediConnect](https://github.com/mekkiamine/MediConnectFrontend)** | Cloud-based patient/doctor platform: RBAC with Keycloak (OAuth2/JWT), multi-factor auth (TOTP, Google SSO, facial recognition), Google Calendar sync, deployed on OpenStack | ![](https://img.shields.io/badge/Keycloak-4D4D4D?logo=keycloak&logoColor=white) ![](https://img.shields.io/badge/Spring%20Boot-6DB33F?logo=springboot&logoColor=white) ![](https://img.shields.io/badge/OpenStack-ED1944?logo=openstack&logoColor=white) ![](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) |
| **OpenStack Private Cloud** | 7-node OpenStack Epoxy cluster built by a team of 6 (1 controller, 4 compute, 2 storage), automated with Ansible, Kubernetes on top, monitored with Prometheus + Grafana | ![](https://img.shields.io/badge/OpenStack-ED1944?logo=openstack&logoColor=white) ![](https://img.shields.io/badge/Ansible-EE0000?logo=ansible&logoColor=white) ![](https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus&logoColor=white) ![](https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white) |
| **[Urbanova](https://github.com/mekkiamine/Urbanove-Backend)** | AI-based real estate recommendation platform: bilingual NER model (spaCy, 92–95% detection accuracy) combined with XGBoost to score and rank listings | ![](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![](https://img.shields.io/badge/spaCy-09A3D5?logo=spacy&logoColor=white) ![](https://img.shields.io/badge/Angular-DD0031?logo=angular&logoColor=white) ![](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white) |

### 🔄 How E-ComK8s ships code

```mermaid
flowchart LR
    A[👨‍💻 Push to GitHub] --> B[GitHub Actions<br/>tests · ESLint · SonarQube]
    B --> C[Docker image<br/>build & publish]
    C --> D[GitOps repo<br/>manifests updated]
    D --> E[Argo CD<br/>sync]
    E --> F[☸️ Kubernetes<br/>HPA · Ingress · Longhorn]
    F --> G[📊 ELK logging<br/>& monitoring]
```

---

## 🛠️ Tech stack

**Cloud & DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Argo CD](https://img.shields.io/badge/Argo%20CD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![OpenStack](https://img.shields.io/badge/OpenStack-ED1944?style=flat-square&logo=openstack&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=icloud&logoColor=white)

**Infra, monitoring & quality**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Elastic](https://img.shields.io/badge/ELK%20Stack-005571?style=flat-square&logo=elastic&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white)
![NGINX](https://img.shields.io/badge/NGINX%20Ingress-009639?style=flat-square&logo=nginx&logoColor=white)
![Longhorn](https://img.shields.io/badge/Longhorn-5F224B?style=flat-square&logo=rancher&logoColor=white)
![MetalLB](https://img.shields.io/badge/MetalLB-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

**Security & identity**

![Keycloak](https://img.shields.io/badge/Keycloak-4D4D4D?style=flat-square&logo=keycloak&logoColor=white)
![OAuth2](https://img.shields.io/badge/OAuth2-3E4348?style=flat-square&logo=auth0&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![Sealed Secrets](https://img.shields.io/badge/Sealed%20Secrets-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

**Development & data**

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)

---

## 💼 Experience

- **DevOps / Cloud Engineer Intern**, SIGA Solutions (Jul. – Sep. 2026): Kubernetes, Argo CD, GitHub Actions, ELK, SonarQube
- **Full Stack Developer Intern**, Instar (Jul. – Sep. 2025): Angular, Node.js, AWS (EC2, S3)

## 🎓 Education

- **ESPRIT, School of Engineering**: Engineering Degree in Computer Science (expected June 2027)
- **ISET Rades**: Bachelor's Degree in Computer Science (2021 – 2024)

---

## 📊 GitHub stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=mekkiamine&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true" alt="GitHub stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mekkiamine&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=mekkiamine&theme=tokyonight&hide_border=true" alt="Streak" />

</div>

---

<div align="center">

*Let's connect, I'm always happy to talk about Kubernetes, GitOps and secure cloud platforms.*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a3c6e,100:2f81f7&height=90&section=footer" alt="footer" />

</div>
