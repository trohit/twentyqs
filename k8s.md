
Sure, here are 20 multiple choice questions about Kubernetes:

What is Kubernetes?
A. A programming language
B. A container orchestration platform
C. A database management system
D. A virtualization technology

Which of the following components manages container scheduling in Kubernetes?
A. kube-proxy
B. kubelet
C. kube-scheduler
D. kube-controller-manager

In Kubernetes, what is a Pod?
A. A network abstraction
B. A storage volume
C. A group of containers
D. A virtual machine

What is the purpose of a Kubernetes Deployment?
A. To monitor resource usage
B. To manage container images
C. To define desired state for Pods
D. To control network traffic

Which Kubernetes resource is used for storing and managing sensitive information such as passwords or API tokens?
A. Pod
B. Secret
C. ConfigMap
D. PersistentVolume

What is the main function of the kube-controller-manager in Kubernetes?
A. Manage networking
B. Maintain cluster state
C. Handle container lifecycle events
D. Manage storage resources

Which Kubernetes component is responsible for scaling applications based on resource usage?
A. kube-apiserver
B. kube-controller-manager
C. kube-scheduler
D. Horizontal Pod Autoscaler

What does Kubernetes use for container runtime by default?
A. Docker
B. LXC
C. rkt
D. Containerd

What is the purpose of Kubernetes Service?
A. Load balancing network traffic across Pods
B. Managing container lifecycle
C. Storing configuration data
D. Monitoring cluster health

Which Kubernetes object defines a set of rules for how network traffic is allowed to flow between Pods?
A. Ingress
B. NetworkPolicy
C. Service
D. PodSecurityPolicy

How does Kubernetes handle node failures?
A. By automatically repairing the failed node
B. By redistributing Pods from the failed node to healthy nodes
C. By stopping all affected Pods until the node is manually repaired
D. By notifying administrators to manually intervene

Which Kubernetes feature allows you to automatically mount storage systems like AWS EBS or GCP Persistent Disks into Pods?
A. PersistentVolume
B. StatefulSet
C. VolumeSnapshot
D. StorageClass

What Kubernetes resource is used to define a set of rules for how requests for external access to services should be routed to Pods?
A. Ingress
B. Service
C. Endpoint
D. NodePort

What is the primary role of a kubelet in Kubernetes?
A. Managing networking
B. Scheduling Pods
C. Monitoring container health
D. Interacting with the Kubernetes API server

Which Kubernetes component serves as the central management entity for the entire cluster?
A. kube-proxy
B. kubelet
C. kube-apiserver
D. kube-scheduler

What is the primary benefit of using Kubernetes for container orchestration?
A. Simplified container creation
B. Efficient resource utilization
C. Enhanced container security
D. Automated deployment and scaling

What is the recommended approach for scaling applications horizontally in Kubernetes?
A. By manually adding more resources to existing Pods
B. By increasing the size of the underlying VMs
C. By deploying more Pods of the same application
D. By upgrading the Kubernetes cluster to a larger instance type

What is the purpose of a Kubernetes ConfigMap?
A. To store sensitive information like passwords
B. To manage container images
C. To define environment variables and configuration data
D. To monitor cluster health

Which Kubernetes resource is used for persistent storage that can be dynamically provisioned and attached to Pods?
A. PersistentVolume
B. VolumeClaim
C. StorageClass
D. StatefulSet

In Kubernetes, what is the purpose of a DaemonSet?
A. To ensure that a specified number of Pods are running
B. To manage batch workloads
C. To run a single instance of a specified Pod on every node
D. To handle incoming network traffic to the cluster

Answers
B. A container orchestration platform
C. kube-scheduler
C. A group of containers
C. To define desired state for Pods
B. Secret
B. Maintain cluster state
D. Horizontal Pod Autoscaler
A. Docker
A. Load balancing network traffic across Pods
B. NetworkPolicy
B. By redistributing Pods from the failed node to healthy nodes
D. StorageClass
A. Ingress
C. Monitoring container health
C. kube-apiserver
D. Automated deployment and scaling
C. By deploying more Pods of the same application
C. To define environment variables and configuration data
C. StorageClass
C. To run a single instance of a specified Pod on every node
