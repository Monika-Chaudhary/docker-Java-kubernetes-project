# docker-Java-kubernetes-project
Deploying Java Applications with Docker and Kubernetes

Credit: https://github.com/danielbryantuk/oreilly-docker-java-shopping/

Steps
1. Create Ubuntu EC2 Instance on AWS
2. Install Java on EC2 Instance
3. Install Jenkins on EC2 Instance
4. Open 8080 port on SG of EC2 Instance and access jenkins using http://publicIpOfInstance:8080/
5. Install plugins and configure tools(git, java, maven) on Jenkins
6. Install kubectl on ec2 instance
7. Install docker & give docker permission to current user
   > sudo usermod -aG docker $USER && docker newgrp
9. Create K8S Cluster using KIND
   a. Install kind
   b. Create cluster
   > kind create cluster --name my-k8s-cluster
