
**canary-deployments-guide.md:**

# Canary Deployments Guide

## Steps to Set Up Canary Deployments with Istio
1. Install Istio on your cluster.
2. Apply the `destination-rule.yaml` and `virtual-service.yaml` manifests:

   ```bash
   kubectl apply -f manifests/canary/destination-rule.yaml
   kubectl apply -f manifests/canary/virtual-service.yaml
