# Horizontal Pod Autoscaler

- The Kubernetes Horizontal Pod Autoscaler automatically scales the number of Pods in a deployment, replication controller, or replica set based on that resource's CPU utilization. This can help your applications scale out to meet increased demand or scale in when resources are not needed, thus freeing up your nodes for other applications. When you set a target CPU utilization percentage, the Horizontal Pod Autoscaler scales your application in or out to try to meet that target.

# Prerequisites

- You have an existing Amazon EKS cluster. If you don't, see Getting started with Amazon EKS.

- You have the Kubernetes Metrics Server installed. For more information, see Installing the Kubernetes Metrics Server.
- https://docs.aws.amazon.com/eks/latest/userguide/metrics-server.html

- You are using a kubectl client that is configured to communicate with your Amazon EKS cluster.