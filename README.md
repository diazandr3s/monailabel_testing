# Monai Label testing k8s

kubectl apply -f kubernetes/monailabel-deployment.yaml


kubectl apply -f kubernetes/monailabel-service.yaml


### Command utils:

**Map port should is considered a service:**
 
kubectl exec -it POD_NAME -- bash -> Access pod's Bash
 
kubectl apply -f kubernetes/monailabel-service.yaml -> Apply YAML configuration
 
kubectl get namespace -> Get namespaces
 
kubectl get pods -> Get pods
 
kubectl delete pod POD_NAME -> Delete pod name
 
kubectl delete -f FILE_NAME.yaml -> Delete pod from the "root"
 
kubectl describe pod POD_NAME -> Describe pod logs



### Questions


What is a namespace?

What is the Bastion "pod"?

What are the types of services? i.e. NodePort, Port, LoadBalancer, Ingress

What the purpose of Helm?

What is Bare-Metal?
