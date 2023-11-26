# requirements :

check this article to install necessaru requirments :

https://medium.com/@khaledhadjali1/get-solid-hands-on-experience-with-kubernetes-and-be-able-to-deploy-any-application-into-production-af47b5218140


kubectl apply -f postgres-pv.yml
kubectl apply -f postgres-pvc.yml
kubectl apply -f postgres.yml


 kubectl apply -f accountant_dep.yml
 kubectl apply -f warehouse_dep.yml
 kubectl apply -f sales_dep.yml

 kubectl apply -f web_api_dep.yml

# How to apply migration 

kubectl exec -it pod_name bash
alembic upgrade head