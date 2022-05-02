# SERVICE
## NODEPORT

Ver manifiesto:
`cat 07-nodeport.yaml`{{execute}}.

Despliega el segundo pod:
`kubectl apply -f 07-nodeport.yaml`{{execute}}.

`kubectl get pods -o wide`{{execute}}.

`kubectl describe service web-nodeport`{{execute}}

`kubectl get service`{{execute}}.

`kubectl get node -o wide`{{execute}}.

Revisar servicio web
`curl IP:PORT`{{execute}}

Eliminar pod:
`kubectl delete -f 07-nodeport.yaml`{{execute}}.


