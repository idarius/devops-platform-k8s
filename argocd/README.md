# Argo CD – Bootstrap GitOps

Ce dossier contient les définitions Argo CD permettant de déployer
l’intégralité de la plateforme Kubernetes selon le modèle **App of Apps**.

## Root Application
La `root-app` référence le dossier `platform/` et orchestre
le déploiement de toutes les applications plateforme.