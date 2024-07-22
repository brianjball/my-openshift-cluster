# My OpenShift Cluster

The purpose of this repository is to add all of the configurations to set up and play with a Red Hat OpenShift cluster.

```sh
until oc apply -k cluster/; do : ; done
```

```sh
# run gpu pod
oc apply -k https://github.com/redhat-na-ssa/demo-ai-gitops-catalog/components/app-configs/nvidia-gpu-verification/overlays/toleration/
```
