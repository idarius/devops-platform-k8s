# DevOps Platform Kubernetes (GitOps)
Ce dépôt contient la partie GitOps du projet RNCP DevOps.

## Objectif
- Centraliser le déploiement de la plateforme Kubernetes
- Utiliser **Argo CD** comme base GitOps
- Déployer les composants via Helm Charts
- Garantir un déploiement reproductible et traçable

## Contenu
- Bootstrap GitOps (root application)
- Ingress Controller (Traefik)
- Gestion TLS (cert-manager)
- Monitoring (Prometheus / Grafana)
- Sauvegarde & restauration (Velero)

## Principe
Terraform :
- Provisionne l’infrastructure (AKS, ACR, Storage)
- Installe Argo CD

Argo CD :
- Déploie et maintient la plateforme depuis ce dépôt
