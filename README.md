# kind
In order to start a default minimal kind cluster, run:
```shell
kind create cluster
```
In order to run a kind cluster with special options (multiple worker nodes, multiple control plane nodes, etc...), use
the <span style="color:red"> --config </span> flag. For example:
```shell
kind create cluster --config multi-worker-cluster-config.yaml
```
In order to list the existing clusters, run:
```shell
kind get clusters
```
In order to list a cluster's nodes, run:
```shell
kind get nodes
```
In order to delete a cluster, run:
```shell
kind delete cluster
```
In case that the kubeconfig file has been deleted you can regenerate it. Run:
```shell
kind get kubeconfig
```
