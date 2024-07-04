# K8s_Init_Containers

Check Logs for the Init Container `kubectl logs pod/myapp-pod -c init-myservice`

Create a Nginx Deployment `kubectl create deploy nginx-deploy --image nginx --port 80`

Create a service expose to the Nginx deployment `kubectl expose deploy nginx-deploy --name myservice --port 80`

Create a Redis Deployment `kubectl create deploy mydb --image nginx --port 80`

Create a service expose to the Redis deployment `kubectl expose deploy mydb --name mydb --port 80`

Print the Enviroment Variables in a Pod without actually logging in `kubectl exec -it myapp-pod -- printenv`

Enter the shell in a Pod `kubectl exec -it myapp-pod -- sh`
