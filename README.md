Wordpress development using Kubernetes

Requirements:
- Kubernetes cluster

How to deploy
- Run the next command inside the folder
``` bash
kubelet apply -k ./
```
What is created
- secret: mysql-pass
- service: wordpress-mysql
- service: wordpress
- deployment: wordpress-mysql
- deployment: wordpress
- persistent volume claim: mysql-pv-claim
- persistent volume claim: wp-pv-claim

Use the next reference:
https://kubernetes.io/docs/tutorials/stateful-application/mysql-wordpress-persistent-volume/
