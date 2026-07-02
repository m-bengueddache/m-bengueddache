# Mohamed Bengueddache

**FR** — Consultant VMware en transition vers le DevOps. Fort background en virtualisation, automatisation et administration système, complété par une formation intensive aux pratiques et outils DevOps modernes.

**EN** — VMware Consultant transitioning to DevOps. Strong background in virtualization, automation and system administration, complemented by intensive hands-on training in modern DevOps practices and tooling.

---

## Stack

**Infrastructure & Virtualisation**

![VMware](https://img.shields.io/badge/VMware-vSphere%20%7C%20vRA%20%7C%20vRO-607078?logo=vmware)
![Linux](https://img.shields.io/badge/Linux-Debian%20%7C%20CentOS%20%7C%20Ubuntu-FCC624?logo=linux&logoColor=black)
![Windows Server](https://img.shields.io/badge/Windows-Server-0078D6?logo=windows)

**Cloud & DevOps**

![AWS](https://img.shields.io/badge/AWS-EC2%20%7C%20EKS%20%7C%20ECR%20%7C%20Lambda%20%7C%20CLI-orange?logo=amazonaws)
![Linode](https://img.shields.io/badge/Linode-Akamai%20LKE-00A95C?logo=linode)
![Kubernetes](https://img.shields.io/badge/Kubernetes-Minikube%20%7C%20EKS%20%7C%20LKE-326CE5?logo=kubernetes)
![Helm](https://img.shields.io/badge/Helm-3%20%7C%20Helmfile-0F1689?logo=helm)
![Docker](https://img.shields.io/badge/Docker-Compose%20%7C%20Hub%20%7C%20ECR-2496ED?logo=docker)
![Jenkins](https://img.shields.io/badge/Jenkins-CI%2FCD%20%7C%20Shared%20Lib-D24939?logo=jenkins)
![Nexus](https://img.shields.io/badge/Sonatype-Nexus-1B1C30)

**Backend & Data**

![Java](https://img.shields.io/badge/Java-8%20%7C%2017-blue?logo=openjdk)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3-6DB33F?logo=springboot)
![Maven](https://img.shields.io/badge/Maven-build-red?logo=apachemaven)
![Gradle](https://img.shields.io/badge/Gradle-build-02303A?logo=gradle)
![MongoDB](https://img.shields.io/badge/MongoDB-ReplicaSet-47A248?logo=mongodb)
![MySQL](https://img.shields.io/badge/MySQL-Replication-4479A1?logo=mysql)

**Frontend**

![Node.js](https://img.shields.io/badge/Node.js-20-339933?logo=node.js)
![React](https://img.shields.io/badge/React-18-61DAFB?logo=react)
![Angular](https://img.shields.io/badge/Angular-frontend-DD0031?logo=angular)

**Observability**

![ELK](https://img.shields.io/badge/ELK-Elasticsearch%20%2B%20Kibana-005571?logo=elasticsearch)

**Languages & Scripting**

![Groovy](https://img.shields.io/badge/Groovy-DSL-4298B8?logo=apachegroovy)
![Python](https://img.shields.io/badge/Python-3-3776AB?logo=python)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?logo=javascript&logoColor=black)
![PowerShell](https://img.shields.io/badge/PowerShell-5.1-5391FE?logo=powershell)

**Certifications**

![VCP](https://img.shields.io/badge/VMware-VCP%20Cloud%20Management%20%26%20Automation-607078?logo=vmware)
![VCP](https://img.shields.io/badge/VMware-VCP%20VCF%20Administrator-607078?logo=vmware)

---

## Projects / Projets

### CI/CD & Automation

| Repo | Description |
|---|---|
| [aws-jenkins-cicd](https://github.com/m-bengueddache/aws-jenkins-cicd) | Full Jenkins pipeline: version increment, Maven build, Docker push, SSH deploy to EC2 |
| [jenkins-cicd-pipeline](https://github.com/m-bengueddache/jenkins-cicd-pipeline) | Declarative Jenkins pipeline with semantic versioning — evolves to use a shared library |
| [jenkins-groovy-shared-library](https://github.com/m-bengueddache/jenkins-groovy-shared-library) | Reusable Groovy shared library: Docker build/login/push steps with `src/` class encapsulation |
| [jenkins-eks-cicd](https://github.com/m-bengueddache/jenkins-eks-cicd) | Full CI/CD pipeline to Amazon EKS — version increment, Maven build, Dockerhub then ECR registry migration, dynamic Kubernetes manifests with imagePullSecrets |

### Cloud & Infrastructure (AWS)

| Repo | Description |
|---|---|
| [aws-ec2-docker-deployment](https://github.com/m-bengueddache/aws-ec2-docker-deployment) | Multi-stage Docker build of a React/Node.js app deployed on AWS EC2 via SSH and Docker Compose |
| [aws-cli-automation](https://github.com/m-bengueddache/aws-cli-automation) | EC2 provisioning and IAM management (users, groups, policies) entirely via AWS CLI |
| [eks-cluster-setup-aws](https://github.com/m-bengueddache/eks-cluster-setup-aws) | EKS cluster provisioning from scratch — VPC/IAM from the AWS console, Cluster Autoscaler internals (OIDC/IRSA), Fargate profile fundamentals, and the eksctl one-command alternative |

### Containerisation

| Repo | Description |
|---|---|
| [docker-node-mongodb](https://github.com/m-bengueddache/docker-node-mongodb) | Node.js app + MongoDB + Mongo Express orchestrated with Docker Compose and named volumes |

### Kubernetes

| Repo | Description |
|---|---|
| [kubernetes-cluster-setup](https://github.com/m-bengueddache/kubernetes-cluster-setup) | MongoDB (ConfigMap/Secret) and Mosquitto MQTT broker with config files mounted as volumes |
| [k8s-ecr-private-registry](https://github.com/m-bengueddache/k8s-ecr-private-registry) | Node.js app deployed on Kubernetes (Minikube) from a private AWS ECR registry — Docker auth, imagePullSecrets, and namespace-scoped Secrets |
| [helm-lke-mongodb](https://github.com/m-bengueddache/helm-lke-mongodb) | MongoDB ReplicaSet on Linode Kubernetes Engine (LKE) with Helm, persistent block storage, Mongo Express UI, and Nginx Ingress Controller |
| [k8s-microservices-helm](https://github.com/m-bengueddache/k8s-microservices-helm) | Online Boutique: 11 microservices on LKE — raw manifests, production best practices (probes, resource limits), shared Helm chart, and Helmfile deployment |
| [kubernetes-lke-springboot](https://github.com/m-bengueddache/kubernetes-lke-springboot) | Spring Boot + MySQL replication on LKE — raw manifests, Bitnami Helm, Helm chart written from scratch, and Helmfile multi-release deployment |
| [eks-fargate-nodegroup-cicd](https://github.com/m-bengueddache/eks-fargate-nodegroup-cicd) | Spring Boot + MySQL replication on EKS — hybrid compute (Fargate for the app, managed nodegroup for stateful services), EBS CSI persistent storage, Cluster Autoscaler via IRSA, Jenkins CI/CD to ECR |
| [k8s-lambda-fullstack-elk](https://github.com/m-bengueddache/k8s-lambda-fullstack-elk) | AWS Lambda (Python), Spring Boot + Angular deployed on Kubernetes, Jenkins CI/CD pipeline, and ELK stack with Filebeat DaemonSet for log centralisation |

### Artifact Management (Nexus)

| Repo | Description |
|---|---|
| [nexus-gradle-artifact-repo](https://github.com/m-bengueddache/nexus-gradle-artifact-repo) | Spring Boot JAR published to a private Sonatype Nexus repo via Gradle `maven-publish` |
| [nexus-maven-artifact-repo](https://github.com/m-bengueddache/nexus-maven-artifact-repo) | Spring Boot JAR published to a private Sonatype Nexus repo via Maven `deploy` |

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mohamed%20Bengueddache-0A66C2?logo=linkedin)](https://www.linkedin.com/in/mohamed-bengueddache-64a55a156)
[![Email](https://img.shields.io/badge/Email-bengueddache.mohamed%40gmail.com-EA4335?logo=gmail&logoColor=white)](mailto:bengueddache.mohamed@gmail.com)
