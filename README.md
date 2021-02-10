Microspray is an opiniated production ready Kubernetes distribution based on Kubespray
No option, we're making the choices to make it works !

Need different OS/Options? Kubespray is a better choice.

## Baremetal first-class

All the clouds propose already a 'Managed' kubernetes service.
The problem remains for the non-cloud infrastructure aka Baremetal/dedicated/On-premise, Microspray is focusing exclusivly on those type of infrastructure.

## Managing kubernetes clusters, the ecosystem

Being opinated help keeping all clusters deployments homogenous shape is essential to build the automations to upgrade, monitor and scale.

### Choices
 - No network manager
 - No app management
 - Containerd / Crictl via another lifecycle
 - Etcd via another lifecycle 
 - Operating System via another lifecycle
 - Kubeadm
 - CoreDNS 
 - Opensource only
  
Supported Linux Distributions
- Ubuntu
 
