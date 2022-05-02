# SERVICE
## SECRET

Crear los secretos en archivos:
`echo -n 'usertest' > ./username.txt && echo -n 'MyPassw0rd!' > ./password.txt`{{execute}}.

Crea el secret de forma imperativa
`kubectl create secret generic db-user-pass --from-file=./username.txt --from-file=./password.txt`{{execute}}.

Ver manifiesto:
`cat 09-secret.yaml`{{execute}}.

Aplica el manifiesto:
`kubectl apply -f 09-secret.yaml`{{execute}}.

`kubectl get secrets db-user-pass -o yaml`{{execute}}.

Sustituye xxxxxxxx-xxxxx por los datos de tu pod
`kubectl exec -it app-secret-xxxxxxxx-xxxxx -- env`{{execute}}.

Eliminar pod y secret:
`kubectl delete -f 09-configmap.yaml`{{execute}}.
`kubectl delete secrets db-user-pass`{{execute}}.



