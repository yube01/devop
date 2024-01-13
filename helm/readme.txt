helm create [folder name]

helm install myApp

helm upgrade myApp

helm rollback myApp

helm install helm-test helm/
[program runs on localhost:30007]


helm upgrade helm-test helm/ --values helm/values.yaml

-----------------------------------
delete helm chart

helm list

helm uninstall [Name]  