# AWS Retail Store — End-to-End DevOps Implementation

**Technologies:** AWS | Terraform | Docker | Kubernetes | Amazon EKS | Helm | Karpenter | GitHub Actions | ArgoCD | OpenTelemetry

## Project Overview

This project documents my hands-on implementation of a containerized retail-store microservices application on Amazon Web Services.

As part of my DevOps training, I provisioned cloud infrastructure in my personal AWS account, customized Terraform configurations, established an Amazon S3 remote-state backend, and deployed the application to an EKS Kubernetes cluster.

The project demonstrates how infrastructure provisioning, container orchestration, application configuration, autoscaling, and cloud services work together in a modern DevOps environment.

## My Contributions

- Configured Terraform infrastructure to use my own AWS environment and resource naming.
- Established an S3-backed remote Terraform state configuration.
- Provisioned AWS networking and Kubernetes infrastructure using Terraform.
- Deployed the retail-store microservices application to Amazon EKS.
- Worked with Kubernetes manifests and Helm charts to configure application deployments.
- Practiced integrating application workloads with AWS infrastructure and managed services.

## Architecture

The implementation uses five microservices: UI, Catalog, Cart, Checkout, and Orders.

Terraform manages the AWS infrastructure, while Kubernetes and Helm manage the application workloads.

## Project Background

This project is based on the StackSimplify *Ultimate DevOps Real-World Project Implementation on AWS Cloud* course.

The original sample application and course configurations belong to their respective authors. This repository documents my own deployment, environment customization, and additional engineering work.

## Project Status

Course deployment completed. Portfolio documentation, independent improvements, and reproducibility verification are ongoing.