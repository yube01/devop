minikube start

kubectl get nodes

Visiting kubernetes pods
create pod.yaml for simple nginx 


kubectl create -f pod.yaml

kubectl get pods

kubectl get pods -o wide [shows Ip address]

minikube ssh [same as -it in docker image]
curl [ip address]

kubernetes cheatsheets for more refrence in website

kubectl delete pod nginx


kubectl describe pod [pod name]
kubectl logs [pod name]

-------------------------------------------------------------------

kubectl get all


kubernetes deployment pods website
create deployment.yaml

kubectl get deploy

deploy -> creates replica set -> creates pods

kubectl get rs [replica set]


kubectl get pods -w [watch mode]

kubectl delete deploy [deployment yaml file]





