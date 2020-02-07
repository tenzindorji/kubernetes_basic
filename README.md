# kubernetes_basic

Create a Cluster commands:
First need to Install minikube
Check minikube version
  minikube version

Start minikube, this will start the kubernetes cluster
  minikube start

Interact kubernetes cluster using kubectl command line which is installed at user machine
  kubectl version

Cluster details
  kubectl cluster-info
  kubectl get nodes

Deploy App by creating deployment. Need to provide the deployment name and app image location.
