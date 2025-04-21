# 🎮 Kubernetes 2048 Game Project on EKS

This project demonstrates how to deploy the classic 2048 game on Amazon EKS (Elastic Kubernetes Service) using AWS Fargate, an ALB Ingress Controller, and Kubernetes best practices. It walks through setting up the cluster, configuring IAM roles and policies, deploying the app, and exposing it to the internet via DNS.

---

## 📦 [Module-1:Install EKS with Fargate](#module-1:Install EKS with Fargate) 

In this step, you will create the EKS cluster and set up Fargate for your workloads. This will provide a serverless Kubernetes environment for your application.

---

## 🎯 [Module 2: Deploy 2048 App](#module-2-deploy-2048-app)

Here, you will create a Fargate profile for the deployment and apply the Kubernetes manifests to deploy the 2048 game application to your cluster.

---

## 🔐 [Module 3: Configure IAM OIDC Provider](#module-3-configure-iam-oidc-provider)

The OIDC (OpenID Connect) provider will allow Kubernetes to authenticate with AWS IAM roles securely. In this module, you will associate the OIDC provider with your EKS cluster and ensure that the necessary permissions are in place.

---

## 🧰 [Module 4: Set Up ALB Ingress Controller](#module-4-set-up-alb-ingress-controller)

The ALB (Application Load Balancer) Ingress Controller is responsible for managing ingress resources and routing traffic to the appropriate services. You will configure IAM roles, install the ALB controller, and ensure it is deployed within your cluster.

---

## 📊 [Module 5: Results and Access](#module-5-results-and-access)

Once everything is set up, you will be able to access the 2048 game via DNS. AWS will provide a load balancer with a DNS name, allowing you to play the game in your browser.

#### ✅ Firewall Configuration
The firewall rule was successfully configured, allowing external access to the application.

#### 🌐 Game Running on DNS
The game can now be accessed through the DNS provided by the AWS Load Balancer.

🧠 **DNS Used:**
`k8s-game2048-ingress2-bcac0b5b37-1715446488.us-east-1.elb.amazonaws.com`

> You can now play the 2048 game in your browser via the DNS URL.

---

✅ Project Completed Successfully!

---
