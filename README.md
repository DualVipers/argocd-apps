# Dual Vipers Core ArgoCD Apps

This repository covers all apps used in the internal cluster and apps that exist across multiple clusters.

| Application                                 | Description                                                                              |
| ------------------------------------------- | ---------------------------------------------------------------------------------------- |
| [argocd-ingress](argocd-ingress/)           | Creates the Ingress for the ArgoCD UI.                                                   |
| [ingress](ingress/)                         | Sets up a cluster's ingress.                                                             |
| [internal-monitoring](internal-monitoring/) | Installs the systems required for the monitoring stack system onto the internal cluster. |
| [monitoring-stack](monitoring-stack/)       | Installs the monitoring stack onto a cluster.                                            |
