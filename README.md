# Sprint2
## Docker

### Dockerfile
It is a text document that contains all the commands required to build/assemble a docker image.

```
FROM openjdk:8
EXPOSE 8080
COPY target/sprint.jar sprint.jar
CMD java, -jar, sprint.jar
```

### Building the docker image
```
docker build -t sprint .
```

### Pushing the docker Image
```
docker push saurabhdhumal/sprint2
```

### Deploying the sprint deployment

```

```

## Kubernetes

## Creating the deployment files



## Deploying to kubernetes
```
kubectl apply -f postgres-deployment.yaml
kubectl apply -f postgres-service.yaml
kubectl apply -f sprint-deployment.yaml
kubectl apply -f sprint-service.yaml

```

## Checking the deployments
```
kubectl get deployment
kubectl get svc
kubectl get pods

```

## To check our deployment outside the cluster
Copy the ip address of the sprint service and view it on localhost port
ex:
```

```
