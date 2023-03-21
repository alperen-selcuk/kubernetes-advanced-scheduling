# kubernetes-advanced-scheduling

# lab PRE-REQ

## docker install

````
curl https://raw.githubusercontent.com/alperen-selcuk/docker-install/main/ubuntu-1804.sh | bash -
````

## minikube install ve start

````
curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
sudo install minikube-linux-amd64 /usr/local/bin/minikube

minikube start --driver=docker --nodes=4
````

## kubectl install

```
curl https://raw.githubusercontent.com/alperen-selcuk/kubectl-install/main/install-kubectl-helm.sh | bash -
```

kubectl get nodes
