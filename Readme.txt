Kubernetes network
Network communication between containers is the most difficult part. Because Kubernetes
manages multiple nodes (hosts) running several containers, those containers on different
nodes may need to communicate with each other.
If the container's network communication is only within a single node, you can use Docker
network or Docker compose to discover the peer. However, along with multiple nodes,
Kubernetes uses an overlay network or container network interface (CNI) to achieve
multiple container communication.

Understanding Kubernetes is not easy, but a step-by-step learning process on
how to set up, configure, and manage Kubernetes is really fun.


sudo netstat -tulpn | grep LISTEN
