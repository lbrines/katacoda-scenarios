## POD

Ver manifiesto:
`cat 01-pod.yml `{{execute}}.

Verificar si hay pods:
`kubectl get pods`{{execute}}.

Despliega el primer pod:
`kubectl apply -f 01-pod.yml`{{execute}}.

`kubectl get pods`{{execute}}.

`kubectl describe pod nginx`{{execute}}.

Eliminar pod:
`kubectl delete pod nginx`{{execute}}.

