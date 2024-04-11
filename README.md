# kubernetes-php
Simple deploy of apache and php on kubernetes

# Steps
* Apply the configuration files to kubernetes
* Verify the status of the deploy
* Get the IP of the minikube node
* Open the browser and connect to the port

# Apply the configuration to kubernetes

$ kubectl apply -f hellophp-deployment.yaml

$ kubectl apply -f hellophp-service.yaml

# Verify the status of the deploy
$ kubectl get pods

$ kubectl get service

# Get the ip of the node of minikube
$ kubectl get nodes -o wide

# Open the browser and connect 
http://<node-ip>:<node-port>
