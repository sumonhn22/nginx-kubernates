# nginx-kubernates

##  Run NGINX on Kubernetes

``` minikube start ```

## create ``` nginx.yaml ``` file with essential configuration

``` kubectl apply --filename nginx.yaml ```

Check is it worked:

``` kubectl get pods ```
``` kubectl get deployments```
``` kubectl get services ```

Access the app from localhost

``` kubectl port-forward service/nginx 8080:80 ```

Open   ```http://localhost:8080```
