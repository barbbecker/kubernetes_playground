## Hello Minikube - Running on MacOs
- Instalações:
  - kubectl
  - minikube
  - hyperkit VM
  - Docker

- Dentro da pasta hello_minikube, rode:
```
docker build -t {dockerhub_id}/hello-minikube .
```

- Suba sua imagem docker para seu Docker Hub:
```
docker login
```
```
docker push {dockerhub_id}/hello-minikube:latest
```

- Inicie o minikube:
```
minikube start
```
```
minikube dashboard
```

- Continue na documentação oficial: https://kubernetes.io/docs/tutorials/hello-minikube/
