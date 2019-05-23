# Devops-training
Devops-training

To launch tomcat using kubernetes

$ kubectl create -f k8s_tomcat.yml

$ kubectl expose deployment tomcat-deployment --type=NodePort --name=tomcat

$ kubectl describe service tomcat

get the target port and access in your browser with your public IP
