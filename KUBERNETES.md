# Kubernetes setup

Kubernetes was installed on the Ubuntu server using k3s.

Verification commands:

```bash
sudo systemctl status k3s
kubectl get nodes
kubectl get pods -A
