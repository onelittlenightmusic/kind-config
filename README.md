# Sample configuration file for Kind (Kubernetes in Docker)

[Kind Quickstart](https://kind.sigs.k8s.io/docs/user/quick-start)

## Prerequisite

- `kubectl` installed
- `kind` command installed

## TL;DR

- Start with this command

```sh
kind create cluster --config kind-config.yaml
```

## `kubectl alpha debug` enabling

```sh
kind create cluster --config kind-config-debug.yaml
```

About `kubectl alpha debug`, please refer to [kubernees.io document](https://kubernetes.io/docs/tasks/debug-application-cluster/debug-running-pod/#ephemeral-container)

About `FeatureGate`, please refer to [kind document](https://kind.sigs.k8s.io/docs/user/quick-start/#enable-feature-gates-in-your-cluster)

## Appendix

- [`kind` command guide in Japaense](https://qiita.com/Hiroyuki_OSAKI/items/2395e6bbb98856df12f3)

