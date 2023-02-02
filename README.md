# kubernetes-php
Simple deploy of apache and php on kubernetes



# DOWNLOAD THE 2 .yaml FILES 

# APPLY CONFIGURATION FILES TO KUBERNETES

kubectl apply -f barto-deployment.yaml

kubectl apply -f barto-service.yaml

# VERIFY THE STATUS OF THE DEPLOY

kubectl get pods
kubectl get service

# GET THE IP OF THE MINIKUBE NODE 
kubectl get nodes -o wide

# OPEN THE BROWSER AND CONNECT 
http://<node-ip>:<node-port>
