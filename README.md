> Supports **Ubuntu-based** systems.

## 📁 Repository Structure
```


├── ubuntu\
│ ├── install-master.sh # Script to setup control plane on Ubuntu
│ ├── install-worker.sh # Script to join worker node on Ubuntu
│ └── delete-k8s.sh # Script to uninstall cluster on Ubuntu

```

## ✅ Features

- Sets up `containerd` and `kubeadm`
- Configures system modules and sysctl
- Sets firewall ports (optional)
- Initializes control plane with Flannel CNI
- Auto-generates the worker join command
- Includes a clean uninstall script

## 🚀 Quick Start

- [Ubuntu-based Instructions](./ubuntu/README.md)
