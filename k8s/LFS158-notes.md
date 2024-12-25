## Kubernetes Building Blocks
#### Labels
- key-value pairs attached to Kubernetes objects
- Equality-Based Selectors
- Set-Based Selectors
#### ReplicationControllers
- ensures a specified number of replicas of a Pod are running at any given time the desired version of the application container
- supports only equality-based Selectors
- **the default recommended controller is the Deployment**
#### ReplicaSets
- the next-generation ReplicationController
- implements the replication and self-healing aspects of the ReplicationController
- supports both equality- and set-based Selectors
- scale(manually or through the use of an [autoscaler](https://kubernetes.io/docs/tasks/run-application/horizontal-pod-autoscale/))
  the number of Pods running a specific application container image
  
  
