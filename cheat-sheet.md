# Itera Azure

## Login

```shell
az login
```

## Set MAD Platform as current subscription

```shell
az account set --subscription 'MAD Platform'
```

## Set up docker to be able to push to repository (ACR)

```shell
az acr login -n itetechmadacr
```

## Set up kubectl to be able to talk to kubernetes (AKS)

```shell
az aks get-credentials -g ite-tech-aks-rg -n ite-tech-mad-aks
```

# Installation links

* [Docker desktop for windows](https://hub.docker.com/editions/community/docker-ce-desktop-windows)
* [Docker desktop for mac](https://hub.docker.com/editions/community/docker-ce-desktop-windows)
* Docker for linux - use package manager or snap
* [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli)
* [Kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)

# Docker documentation

* [Dockerfile reference](https://docs.docker.com/engine/reference/builder/)
* [Docker build](https://docs.docker.com/engine/reference/commandline/build/)
* [Docker run](https://docs.docker.com/engine/reference/commandline/run/)

# Kubectl documentation

* [Kubectl](https://kubernetes.io/docs/reference/generated/kubectl/kubectl-commands)

# Utilities

* [k9s](https://github.com/derailed/k9s)