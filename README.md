# Kubernetes deployment of code

This is the configuration spec files to create a kubernetes deployment of api built with node.js and mongo database.

You can deploy the code with this command in current directory
```
kubectl apply -k .
```

if kustomization doesn't work with your version, use
```
kubectl apply -f databse.yaml;\
kubectl apply -f node.yaml;
```

Hope it was helpful to you.
