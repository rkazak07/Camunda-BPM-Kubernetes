# Camunda-Bpm-Kubernetes-Deploy
## In case of need , you can change image in values file.
## You can set our host or tls in ‘ingress.yaml’ file.

## First of all , we create the Namespace.
```
 kubectl create ns camunda-bpm
```
## Then , we edit the our ‘values.yaml’ file.
```
kubectl apply -f values.yaml -n camunda-bpm
```
## And we deploy the ‘ingress.yaml’ file.
```
kubectl apply -f ingress.yaml -n camunda-bpm
```
