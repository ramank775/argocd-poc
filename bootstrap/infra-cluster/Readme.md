# Infra Cluster Setup

This directory contains IAC for infra cluster.

Setup can be automated using tools like terraform or helmfile

Steps:
    - Install ArgoCD 
    ```bash
        helm dep update charts/argocd
        helm install argo-cd charts/argocd --namespace argocd
    ```