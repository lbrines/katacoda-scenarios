# SERVICE
## CONFIGMAP

Ver manifiesto:
`cat 08-configmap.yaml`{{execute}}.

Aplica el manifiesto:
`kubectl apply -f 08-configmap.yaml`{{execute}}.

`kubectl get configmaps`{{execute}}.

`kubectl describe configmaps test-configmap`{{execute}}.

Sustituye xxxxxxxx-xxxxx por los datos de tu pod
`kubectl exec -it app-configmap-xxxxxxxx-xxxxx -- env`{{execute}}.

Eliminar pod:
`kubectl delete -f 08-configmap.yaml`{{execute}}.

