# GPU MIG Setup

Reference nvidia link - https://docs.nvidia.com/datacenter/cloud-native/gpu-operator/latest/gpu-operator-mig.html

On a H100 or A100 nvidia GPU based VM/Server, perform below steps:

1. Install Kubernetes running `install-k8s.sh` script
2. Install helm
3. Install **GPU Operator** helm chart
4. Follow nvidia documentation to label nodes for configuring MIG on GPU's
