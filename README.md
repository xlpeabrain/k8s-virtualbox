# k8s-virtualbox
A Vagrant setup for K8s on Virtualbox using kubeadm.
Perfect for experimenting with multi-node k8s locally

### Environment
- Vagrant 2.2.6
- Virtualbox 6.0.15
- Internet connection (required during initial setup)

### Usage
- Update VagrantFile with the specifications of the VM configuration in servers section
- Run 'vagrant up' in the same folder as the VagrantFile
- copy kubeconfig file from master by running : 'vagrant scp {name of master node}:.kube/config {destination}'

