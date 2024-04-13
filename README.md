# Kubernetes

### What is Kubernetes
Kubernetes is an open-source container management also known as container orchestration tool for automating software deployment, scaling, and management.

### Why Kubernetes?
Kubernetes offers several key advantages that make it a popular choice for container orchestration and management:

🧑🏻‍💻Deployment: Deploy a specified number of containers to a specified host and keep them running in a wanted state.

✏️Rollouts: A rollout is a change to a deployment. Kubernetes lets you initiate, pause, resume or roll back rollouts.

🌎Service discovery: Kubernetes can automatically expose a container to the internet or to other containers by using a domain name system (DNS) name or IP address.

🛢️provisioning: Set Kubernetes to mount persistent local or cloud storage for your containers as needed.

⚖️Load balancing: Based on CPU usage or custom metrics, Kubernetes load balancing can distribute the workload across the network to maintain performance and stability.

📈Autoscaling: When traffic spikes, Kubernetes autoscaling can spin up new clusters as needed to handle the additional workload.

🌐 Self-healing for high availability: When a container fails, Kubernetes can restart or replace it automatically to prevent downtime. It can also take down containers that don’t meet your health check requirements.




### What is Container Orchestration
Orchestration enables developers to easily build containerized applications and services, as well as scale, schedule and monitor those containers.

### Nodes
Nodes are physical or virtual machine in which kubernetes is installed.

### Cluster
Cluster is group of nodes, if one node fails we have our application accessible from other nodes.

### Master
Master is other node in which kubernetes is installed and it manages other nodes

### Components
  1.API Server

  2.etcd

  3.kubelet

  4.Container Runtime

  5.Controller

  6.Scheduler

### Master V/S Worker node
Master has kube-apiserver installed and nodes have kubelet installed (Kubelet is an agent which make sure nodes are healthy) which provides information to master which stores information in etcd (key value storage)

### Minikube
Minikube is a lightweight Kubernetes implementation that creates a VM on your local machine and deploys a simple cluster containing only one node.

 Download kubectl and minikube to start using minikube
 
### PODS
A Pod is a group of one or more containers, with shared storage and network resources, and a specification for how to run the containers.

### Replication Controllers
Replication Controller used for high availability, it ensures that a specified number of pod replicas are running at any one time. It also helps load balancing and scaling when demand increases.

ReplicaSets replaced replication controllers. A ReplicaSet's purpose is to maintain a stable set of replica Pods running at any given time.

