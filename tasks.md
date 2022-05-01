export KUBECONFIG="" 

kubectl vsphere login --server=192.168.101.130 --insecure-skip-tls-verify -u administrator@vsphere.local

kubectl config use-context vmug