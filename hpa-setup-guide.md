# Horizontal Pod Autoscaler Setup Guide

## Steps to Set Up HPA
1. Ensure your cluster has the metrics-server installed.
2. Apply the HPA manifest:

   ```bash  
   kubectl apply -f manifests/hpa.yaml
