# otus-minikube
OTUS minikube ДЗ

путь для теста
http://arch.homework/health

### Заметки для себя

### Команды

##### Команда _применить кофиг в кубере_
```shell
kubectl apply -f dp.yaml
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
kubectl delete ingress kuber-ingress
kubectl apply -f ingres.yaml
kubectl get ingress
```