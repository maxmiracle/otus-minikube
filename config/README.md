# otus-minikube
OTUS minikube ДЗ

путь для теста
http://arch.homework/health

### Заметки для себя

### Команды

Запускаем миникуб, если он не был запущен ранее
```shell
minikube delete
```
```shell
minikube start
```
```shell install ingress-ingnx
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/main/deploy/static/provider/baremetal/deploy.yaml
```
```shell
kubectl get pods -n ingress-nginx
```
```shell
minikube addons enable ingress
```
!!!Важно
```shell
minikube addons enable ingress-dns
```
```shell
minikube tunnel
```

```shell
kubectl get po
```
```shell
kubectl get services
```

```shell
kubectl apply -f dp.yaml
```
```shell
kubectl apply -f service.yaml
```
```shell
kubectl apply -f ingres.yaml
```

##### Команда для запуска bash в pod
```shell
kubectl exec -it pod-name -- /bin/bash
```

##### Команда удаления конфига
```shell
kubectl delete pod <pod-name>
```


```shell
kubectl get pods -n ingress-nginx
```
```shell
kubectl delete ingress kuber-ingress
kubectl apply -f ingres.yaml
```

```shell
kubectl get ingress
```
https://www.baeldung.com/ops/kubernetes-ingress-empty-address


```shell
#minikube tunnel
minikube ssh 
```
curl http://<cluster-ip>:8000

```shell
kubectl get po -A -o wide
```