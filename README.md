# VMUG DK Summermeeting Tanzu Presentation


Prep env
```
export KUBECONFIG="" 
```

Deploy Cluster
```
kubectl vsphere login --server=192.168.101.130 --insecure-skip-tls-verify -u administrator@vsphere.local
```

Change context
```
kubectl config use-context vmug
```