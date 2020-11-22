# Kubernetes commands

**Get list of pods**
```shell
    kubectl get pods
```

**Get list of deployments**
```shell
    kubectl get deployments
```
**Get list of replica sets**
```shell
    kubectl get replicasets
```

--------

**Get information about pod:**

```shell
    kubectl describe pod <pod_name>
```

**Get logs from pod:**

```shell
    kubectl logs <pod_name>
```

----

**Connect to terminal inside container**
```shell
    kubectl exec -it <pod_name> -- bin/bash
```

---- 

**Delete deployment**
```shell
    kubectl delete deployment <deployment_name>
```

----
**Execute kubernetes configuration file**
```shell
    kubectl apply -f <file_name>
```