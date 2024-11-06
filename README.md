# Hands-on Kubernetes
Deploying Microservices and Service Level Autoscaling

Purpose of the this project is to deploy the project the of  Autoscaling and Microservices

# Outcomes

-Deployand manage of microservices

- Explain the Kubernetes Autoscaling

- Explain Horizontal Pod Autoscaler Business Logic

- Understand the Need for Metric Server

## Outline

- Part 1 - Setting up the Kubernetes Cluster

- Part 2 - Outline of the Hands-on Setup

- Part 3 - Microservices

- Part 4 - Autoscaling in Kubernetes

## Part 1 - Setting up the Kubernetes Cluster

- Using the given Terraform files, launch a two-node Kubernetes cluster based on Ubuntu 24.04, consisting of one master node and one worker node. *Note: Once the master node up and running, worker node automatically joins the cluster.*
## Part 2 - Outline of the Hands-on Setup

- First one is simple web&database application to hold the to-do-lists. This sub-application uses MongoDB to store to-do lists created through the web application. For the front-end web application layer, Node.JS is used. Thus, this sub-aplication has 2 microservices.

## Part 3 - Microservices

- The MongoDB application will use a static volume provisioning with the help of persistent volume (PV) and persistent volume claim (PVC). 
