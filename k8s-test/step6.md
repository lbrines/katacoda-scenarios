# DEPLOYMENT

Ver manifiesto:
`cat 03-deployment.yml`{{execute}}.

Despliega el segundo pod:
`kubectl apply -f 03-deployment.yml`{{execute}}.

`kubectl get deployments`{{execute}}.

`kubectl get pods`{{execute}}.

`kubectl delete pod nginx-deployment-xxxxxxxxx-xxxx`

`kubectl get pods`{{execute}}.

Eliminar pod:
`kubectl delete -f 03-deployment.yml&`{{execute}}.

`kubectl get pods`{{execute}}.

