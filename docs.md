kubectl apply -f postgres-pv.yml
kubectl apply -f postgres-pvc.yml
kubectl apply -f postgres.yml


 kubectl delete pod --force postgres-statefulset-0
