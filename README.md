https://www.youtube.com/watch?v=X48VuDVv0do



# 0:00 - [Course Overview](https://www.youtube.com/watch?v=X48VuDVv0do&t=0s)


# 2:18 - [What is K8s](https://www.youtube.com/watch?v=X48VuDVv0do&t=138s)

# 5:20 - [Main K8s Components](https://www.youtube.com/watch?v=X48VuDVv0do&t=320s)
## Node

A physicla or virtual machine

## Pod

Smallest Kubernetes component. 
An abstraction over a container.
Usually only one container in a Pod, unless they are tighly coupled.  

**Each Pod gets its own IP address that allows Pods communicate with eachother.**

**If a Pod dies and a new instance is created it will get a new IP address** :-(  
So we access Pods via Services.

## Service

Effectively a Load Balancer  

### Internal / External (Ingress) Service

External - Accessible publicly

### Config Maps & Secrets

### Volumes

**K8s doesn't manaage any data persistance.**  
Attaches a physical storage volume to your Pod.  It can be local or remote.

### Deployments

An abstraction on top of stateless pods.  

### Stateful Set

An abstraction on top of stateful pods.  
Meant for stateful applications, like databases, etc.

**DBs are often hosted outside the K8s cluster.**






# 22:29 -  [K8s Architecture](https://www.youtube.com/watch?v=X48VuDVv0do&t=1349s)  

* Worker Node
* Master Node

## Worker Node
3 processes must be installed on every
* Node kubelet
  * Schedules containers to run.  It takes the config and ensures that the containers are running as expected and assignes resources to them
* kube-proxy
* container runtime

Git to here https://youtu.be/X48VuDVv0do?t=1493

# 34:47 - [Minikube and kubectl - Local Setup](https://www.youtube.com/watch?v=X48VuDVv0do&t=2087s)
# 44:52 - [Main Kubectl Commands - K8s CLI](https://www.youtube.com/watch?v=X48VuDVv0do&t=2692s)
# 1:02:03 - [K8s YAML Configuration File](https://www.youtube.com/watch?v=X48VuDVv0do&t=3723s)
# 1:16:16 - [Demo Project: MongoDB and MongoExpress](https://www.youtube.com/watch?v=X48VuDVv0do&t=4576s)
# 1:46:16 - [Organizing your components with K8s Namespaces](https://www.youtube.com/watch?v=X48VuDVv0do&t=6376s)
# 2:01:52 - [K8s Ingress explained](https://www.youtube.com/watch?v=X48VuDVv0do&t=7312s)
# 2:24:17 - [Helm - Package Manager](https://www.youtube.com/watch?v=X48VuDVv0do&t=8657s)
# 2:38:07 - [Persisting Data in K8s with Volumes](https://www.youtube.com/watch?v=X48VuDVv0do&t=9487s)
# 2:58:38 - [Deploying Stateful Apps with StatefulSet](https://www.youtube.com/watch?v=X48VuDVv0do&t=10718s)
# 3:13:43 - [K8s Services explained](https://www.youtube.com/watch?v=X48VuDVv0do&t=11623s)