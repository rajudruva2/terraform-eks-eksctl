# EKS GitOps Infra

This repository creates an AWS EKS cluster using eksctl and GitHub Actions.

## Prerequisites

- AWS Account
- GitHub Repository
- AWS IAM User with EKS permissions

## Add GitHub Secrets

Go to:

Settings → Secrets and variables → Actions

Add:

- AWS_ACCESS_KEY_ID
- AWS_SECRET_ACCESS_KEY

## Create Cluster

GitHub → Actions → Create EKS Cluster → Run workflow

## Delete Cluster

GitHub → Actions → Delete EKS Cluster → Run workflow
