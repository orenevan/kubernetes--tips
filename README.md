# kubernetes--tips

## start a pod 
kubectl run mypod --image nginx

## operations on pod
kubectl exec --stdin --tty mypod -- sh

kubectl exec --stdin --tty mypod -- ls

kubectl exec  mypod -- ps 

