HPA - Exercise 
---------------

In this demo we will show how to scale K8S (HPA) using custom metrics.
The aim of this tutorial is to demonstrate the required steps for implementing custom metrics. 

### Pre requirements

- Existing Cluster 
- kubectl
- helm3 [Installation](https://helm.sh/docs/intro/install/)

### Step 01
    
- Create deployment and autoscale by number of request in the last 30 seconds
  Write yourself the yaml files (practice) - 
   - [Namespace](./k8s/01-namespace.yaml)
   - [Deployment](./k8s/02-deployment)
   - [Service](./k8s/03-service)
   - [HPA](./k8s/04-hpa)

### Step 02
    
- In this step we are going to install prometheus and configure custom metrics.
- Install prometheus
- configure HPA metrics
- Test the scale

