# k8s_TASK






# Kubernetes Task: 
Here is the task specifications: 
Please use your last two homework assignments:
- The YNET news
- The Bitcoin app
#### you can find ynet and bitcoin apps in my repository.
1- Dockerize your YNET and Bitcoin applications
2- Create Kubernetes manifests (Deployment and service)
3- Deploy on your minikube
4- Deploy/Enable Ingress Controller on your cluster
5- Create an ingress that directs the traffic to the correct service:



http://.../ynet → ynet service http://.../bitcoin → bitcoin service


ADDED TWO DOCKER CONTAINERS TO DOCKERHUB



## How to Run the code? 

1) Clone this repository  
2) cd into the directory 
3) minikube start
4) kubectl apply -f .
5) minikube addons enable ingress
6) sudo minikube tunnel


Now you can visit these two websites using the following URLs: 

http://localhost/ynet 



http://localhost/bitcoin

