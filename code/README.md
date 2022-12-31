# code
A code-server with (optional) dind and nginx sidecars.

# minikube
```bash
helm upgrade --install --create-namespace --namespace code code .
minikube service -n code code --url --https
```
