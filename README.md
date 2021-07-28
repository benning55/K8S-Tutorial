# K8S-Tutorial

K8S Ctl command

- kubectl
- kubectl get all
- kubectl delete pod/<name>
- kubectl apply -f <file-name> create new tube
- kubectl apply -f . # access all .yaml file
- kubectl get pv # Get persisted volume

Pod

- Pod cannot access through localhost, unless make a service first.

4 type Service

1. NodePort (Development)
2. ClusterIP
3. LoadBalancer
4. Ingress

Ingress (nginx)

- https://kubernetes.github.io/ingress-nginx/deploy/#docker-desktop

Persisted data (mongo)

- look at pvc file
