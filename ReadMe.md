### Kubernetes Commands 👋
-  🌱 Commands
- minikube start-stop start
- minikube status
- minikube dashboard -enable kubernetes dashboard
- kubectl get pods - get all pods
- minikube stop - stop cluster
- minikube delete - delete cluster 
- kubectl get deployment 
- kubectl get service
- kubectl -h - help command
- kubectl get replicaset
    
- kubectl describe deployment {deployment_name}
- kubectl describe pod 
- kubectl logs {pod_name}
    
- kubectl apply -f .\deploy.yml
- kubectl get pods -0 wide (all info about pods)
- minikube service {service_name}
    
    
     
- kubectl get namespaces
- kubectl create namespace {namespace_name}
    
- minikube addons list  - (list all addons)
    
- minikube addons enable {addons_name}
    
- kubectl scale --replicas=3 -f .\deploy.yaml {scale deployment}
- kubectl delete -f ./

    
