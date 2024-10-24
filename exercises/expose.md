# kubectl expose --help

```
Usage:
  kubectl expose (-f FILENAME | TYPE NAME) [--port=port]
[--protocol=TCP|UDP|SCTP] [--target-port=number-or-name] [--name=name]
[--external-ip=external-ip-of-service] [--type=type] [options]
```

### Create a service for a replicated nginx, which serves on port 80 and connects to the containers on port 8000

### Create a service for a replicated nginx, which serves on port 80 and connects to the containers on port 8000
  
### Create a service for a replication controller identified by type and name specified in "nginx-controller.yaml", which serves on port 80 and connects to the containers on port 8000
  
### Create a service for a pod valid-pod, which serves on port 444 with the name "frontend"
  
### Create a second service based on the above service, exposing the container port 8443 as port 443 with the name "nginx-https"

### Create a service for a replicated streaming application on port 4100 balancing UDP traffic and named 'video-stream'.
  
### Create a service for a replicated nginx using replica set, which serves on port 80 and connects to the containers on port 8000
  
### Create a service for an nginx deployment, which serves on port 80 and connects to the containers on port 8000
