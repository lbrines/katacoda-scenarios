# UPDATE DEPLOYMENT

Ver manifiesto:
`cat 04-deployment.yml`{{execute}}.

Despliega el segundo pod:
`kubectl apply -f 04-deployment.yml`{{execute}}.

`kubectl get pods`{{execute}}.

`kubectl describe pod nginx-deployment-xxxxxxxxx-xxxx`

Eliminar pod:
`kubectl delete -f 04-deployment.yml&`{{execute}}.

