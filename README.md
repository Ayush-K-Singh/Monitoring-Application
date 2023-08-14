# Monitoring Application

This is a flask Monitoring Application which displays current status of CPU Utilization and Memory Utilization of the system.

## Execution(Docker)

1. Clone the repository

```
git clone https://github.com/Ayush-K-Singh/Monitoring-Application.git
```

2. Build the app

```
docker build . -t monitoring-application
```

3. Run the app

```
docker run -d -p 5000:5000 monitoring-application
```

## Execution(Kubernetes)

1. Create the deployment

```
kubectl create -f .\deployment.yaml
```

2. Create the service

```
kubectl create -f .\service.yaml
```

3. Run the app

```
<your-ip>:30001
```
