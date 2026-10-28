# Hi, I'm Nitish

[![Crafting scalable cloud infrastructure | Automating CI/CD and GitOps pipelines | Kubernetes, Terraform, AWS EKS](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1500&color=2EA043&vCenter=true&width=560&lines=Crafting+scalable+cloud+infrastructure;Automating+CI%2FCD+and+GitOps+pipelines;Kubernetes+%E2%80%A2+Terraform+%E2%80%A2+AWS+EKS)](https://github.com/Nitish0223)

**Aspiring DevOps Engineer** from India. I build and automate cloud infrastructure on AWS: CI/CD pipelines, Kubernetes, GitOps, infrastructure as code and monitoring.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nitish-mahakul-766b9a25a/) &nbsp; [![Gmail](https://img.shields.io/badge/Gmail-Email_me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nitishmahakul02@gmail.com)

## Tech stack

**Cloud & infrastructure as code**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logoColor=white) &nbsp; ![Amazon EKS](https://img.shields.io/badge/Amazon_EKS-FF9900?style=flat-square&logoColor=white) &nbsp; ![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)

**Containers & orchestration**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) &nbsp; ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) &nbsp; ![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)

**CI/CD & GitOps**

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) &nbsp; ![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat-square&logo=argo&logoColor=white)

**Monitoring & observability**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) &nbsp; ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

**Networking & security**

![NGINX](https://img.shields.io/badge/ingress--nginx-009639?style=flat-square&logo=nginx&logoColor=white) &nbsp; ![cert-manager](https://img.shields.io/badge/cert--manager-326CE5?style=flat-square&logoColor=white) &nbsp; ![Let's Encrypt](https://img.shields.io/badge/Let's_Encrypt-003A70?style=flat-square&logo=letsencrypt&logoColor=white)

**Development**

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) &nbsp; ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) &nbsp; ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) &nbsp; ![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white) &nbsp; ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) &nbsp; ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) &nbsp; ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

## Featured project

### [go-web-app](https://github.com/Nitish0223/go-web-app): Go web app on AWS EKS with CI/CD, GitOps and observability

A production-style deployment of a Go web application, from `git push` to a live HTTPS site.

- **CI with GitHub Actions**: build, tests, `gofmt` and `golangci-lint`, then a Docker image pushed to Docker Hub, tagged with the commit SHA
- **GitOps with Argo CD**: CI commits the new image tag to the Helm chart, Argo CD rolls it out with self-heal and pruning
- **AWS EKS** with a managed node group, autoscaling (HPA) and EBS-backed persistent storage
- **HTTPS** through ingress-nginx and cert-manager with Let's Encrypt certificates
- **GitHub single sign-on** for Argo CD (Dex) and Grafana, restricted by RBAC
- **Monitoring and alerting** with Prometheus, Grafana and Alertmanager email alerts, including custom rules for app downtime, Argo CD sync and certificate expiry
- **Terraform modules** for the VPC, EKS cluster, IAM roles (IRSA) and platform Helm releases

Live: [app.myexample.sbs](https://app.myexample.sbs/home)

## Open to

DevOps and cloud internships and entry-level roles. Feel free to reach out on [LinkedIn](https://www.linkedin.com/in/nitish-mahakul-766b9a25a/).
