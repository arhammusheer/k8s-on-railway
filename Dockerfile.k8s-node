# Use a base image (e.g., Ubuntu)
FROM ubuntu:latest

# Install kubeadm, kubelet, and kubectl (or use kind-specific setup)
RUN apt-get update && apt-get install -y kubeadm kubelet kubectl

# Join the node to the cluster (replace with actual commands)
CMD ["kubeadm", "join", "--token", "your-token", "control-plane:6443"]
