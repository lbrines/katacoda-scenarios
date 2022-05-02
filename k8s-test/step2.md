# Revise los nodos del cluster
`kubectl cluster-info`{{execute}}.

`kubectl get node`{{execute}}.

Verifica que todos los nodos este ready, salida esperada:

`NAME           STATUS   ROLES    AGE    VERSION`
`controlplane   Ready    master   113s   v1.18.0`
`node01         Ready    <none>   80s    v1.18.0`