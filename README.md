# K8s_Init_Containers

`kubectl logs pod/myapp-pod -c init-myservice`

`kubectl create deploy nginx-deploy --image nginx --port 80`

`kubectl expose deploy nginx-deploy --name myservice --port 80`

`kubectl create deploy mydb --image nginx --port 80`

`kubectl expose deploy mydb --name mydb --port 80`

`kubectl exec -it myapp-pod -- printenv`

`kubectl exec -it myapp-pod -- sh`
