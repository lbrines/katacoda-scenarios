## POD

Ver manifiesto:
`cat 02-pod.yml `{{execute}}.

Despliega el segundo pod:
`kubectl apply -f 02-pod.yml`{{execute}}.

`kubectl get pods`{{execute}}.

`kubectl describe pod myapp-pod`{{execute}}.

Revisar logs del pods:
`kubectl logs myapp-pod`{{execute}}.

Eliminar pod:
`kubectl delete -f 02-pod.yml&`{{execute}}.

