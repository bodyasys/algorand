# Algon
 
Stable channel Alogrand Node helm chart

## Install

### Prerequisites

- Kubernetes cluster accessible https://birthday.play-with-docker.com/kubernetes-docker-desktop/
- kubectl https://kubernetes.io/docs/tasks/tools/install-kubectl/
- https://helm.sh/docs/intro/install/

### Steps

```sh
helm repo add algon https://randmeister.github.io/algon
helm repo update
helm upgrade --install algon algon/algon
```
