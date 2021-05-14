Hello Kubernetes
---

This is just a basic hello world setup to test a kubernetes cluster.

...or you can use this as a quick skelleton to check if your installation worked...

whatever floats your boat 🤷‍♂️

# Requirements:

* Kubernetes

# Usage

1. Clone
2. `kubectl apply -f namespace.yaml -f deployment.yaml -f service.yaml`
3. `kubectl port-forward deployment/hello -n hello 80:80`
4. :rocket:
