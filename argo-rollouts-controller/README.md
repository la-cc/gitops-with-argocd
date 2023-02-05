# GitOps with Argo CD Examples

> NOTE: Please check the latest version of the argo rollouts controller.

You can find the newest version and alle needed information under [Argo Rollouts Docu](https://argo-rollouts.readthedocs.io/en/stable/installation/).

## Controller Installation - Imperative Way

```
kubectl create namespace argo-rollouts
kubectl apply -n argo-rollouts -f https://github.com/argoproj/argo-rollouts/releases/latest/download/install.yaml
```

This will create a new namespace, argo-rollouts, where Argo Rollouts controller will run.

## Kubectl Plugin Installation

The kubectl plugin is optional, but is convenient for managing and visualizing rollouts from the command line.

### Brew

```
brew install argoproj/tap/kubectl-argo-rollouts
```

### Manual

```
curl -LO https://github.com/argoproj/argo-rollouts/releases/latest/download/kubectl-argo-rollouts-darwin-amd64
```
