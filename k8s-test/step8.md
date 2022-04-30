# SERVICE
## CLUSTERIP

Ver manifiesto:
`cat 06-clusterip.yml`{{execute}}.

Despliega el segundo pod:
`kubectl apply -f 06-clusterip.yml`{{execute}}.

`kubectl get service`{{execute}}.

`kubectl get pods -o wide`{{execute}}.

`kubectl describe service web-clusterip`{{execute}}

Cambia la cantidad de replicas a 1:
`nano 06-clusterip.yml`{{execute}}

`kubectl apply -f 06-clusterip.yml`{{execute}}.

`kubectl get pods -o wide`{{execute}}.

`kubectl describe service web-clusterip`{{execute}}

Eliminar pod:
`kubectl delete -f 06-clusterip.yml`{{execute}}.

`kubectl get pods`{{execute}}.

