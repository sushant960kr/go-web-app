# go-web-app

In is a simple web app which is written in go language. Basically we can run it On Local Host first, Then Created A Distroless Image Of The App After That We Deploy The App On Eks Through Console And Access It From The Node Ip After That We Install Nginx For Ingress Controller Which Create A Network Load Balancer Which Manages The Traffic. With The Help Of Nginx We Create A Dns In The Pods And Accessing The App Through The Dns. Now We Install Helm For Variablising The Kubernates Manifest.Lastly We Use Ci To Build & Test, Static Code Analysis, Docker Image Creation & Pushing It And Update The Helm After We Use Argocd Which Pull Helm Chart And Deploy In k8s.Basically Argocd Update The K8s Whenever There Is A Change In Helm Chart.

 
 What we do in this porject :- 
- Containerization (Multi Stage Docker Build)
- Creating Kubernetes Manifests
- Continuous Integration using GitHub Actions
- Continuous Delivery using Argo CD
- Kubernetes Cluster creation and setup
- Helm chart creation and configuration for multiple environments
- Ingress controller creation, configuration to expose application
- DNS mapping for our domain
- End to End CI/CD demonstration
