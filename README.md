# kubernetes-playground
Kubernetes and related tools study.

## grafana-loki-stack
An implementation of [grafana-loki-stack-example](https://github.com/GusAntoniassi/grafana-loki-stack-example) using Kubernetes.

## kong-dbless
A playground that uses Kong in DBLess mode, an example application and some routes, services and upstreams.

## prometheus-operator
Prometheus Operator adapted for running on Minikube

---

## minikube tips
If you want to run multiple minikubes simultaneosly, set this alias on your `.bashrc` or `.zshrc`:

```
alias minikube='minikube --profile $(basename $PWD)'
```

