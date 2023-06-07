# kubernetes--tips

## start a pod 
kubectl run mypod --image nginx

## operations on pod
kubectl exec --stdin --tty mypod -- sh

kubectl exec --stdin --tty mypod -- ls

kubectl exec  mypod -- ps 

https://reviewnprep.com/blog/cheat-sheet-kubernetes-and-linux-commands/#Creating_and_Updating_a_Resource

kubectl get componentstatus


#Wait for pod to start 
kubectl get pods -w --namespace default

NAME                 READY   STATUS    RESTARTS   AGE
mysql-1685213458-0   0/1     Pending   0          105s


Getting certificates from cluster 

kubectl config view --minify --flatten --context kind-terraform


