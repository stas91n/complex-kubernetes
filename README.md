# complex-kubernetes
runs on minikube
prerequisite:
  minikube
  ingress
  complex project (client,server & worker)
  k8s folder with yaml files.
  
  steps:
cd to folder
run " minikube start --driver=hyperv "
run " minikube addons enable ingress "
run " kubecli apply -f k8s "

the project is a simple fibonacci calculator.
