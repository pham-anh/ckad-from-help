# kubectl create service --help

Create a service using a specified subcommand.

Aliases:
service, svc

```
Available Commands:
  clusterip      Create a ClusterIP service
  externalname   Create an ExternalName service
  loadbalancer   Create a LoadBalancer service
  nodeport       Create a NodePort service

Usage:
  kubectl create service [flags] [options]
```


# kubectl create service clusterip --help

Create a ClusterIP service with the specified name.

```
Usage:
  kubectl create service clusterip NAME [--tcp=<port>:<targetPort>] [--dry-run=server|client|none] [options]
```

Examples:
  ## Create a new ClusterIP service named my-cs
  kubectl create service clusterip my-cs --tcp=5678:8080
  
  ## Create a new ClusterIP service named my-cs (in headless mode)
  kubectl create service clusterip my-cs --clusterip="None"

