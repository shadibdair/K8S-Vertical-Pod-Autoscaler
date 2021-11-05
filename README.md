# Understanding CPU  & Memory with the K8S Vertical Pod Autoscaler !

## What’s mean Scheduler:
#### It selects processes from the queue and loads them into memory for execution. Process loads into the memory for CPU scheduling. The primary objective of the job scheduler is to provide a balanced mix of jobs, such as I/O bound and processor bound. It also controls the degree of multiprogramming.

----

## Kind: 
#### is a tool for running local Kubernetes clusters using Docker container “nodes”.kind was primarily designed for testing Kubernetes itself, but may be used for local development or CI.

----

## Horizontal Pod Autoscaling: 
#### HPA allows us to scale pods when their resource utilization goes over a threshold

#### The cluster autoscaler allows us to add more nodes to the cluster when the cluster becomes full, the horizontal pod autoscaler allows us to scale our pods up & down based on metrics like CPU & Memory.

#### In order for autoscaler to work they are driven by metrics and in order to get metrics we need to component called Metric Server 

