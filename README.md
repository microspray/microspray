# Microspray

Microspray is an opiniated fork of the [kubernetes/kubespray](https://github.com/kubernetes-sigs/kubespray) project.

## WHY ? 

With my friend @smana, we created Kubespray in 2015 just after thee kubernetes release 1.0.
Kubernetes was still unknown, hard to install, we decided to help to promote it by building automation to easily deploy and maintain Kubernetes in production. 

Beyond our expectations, Kubespray became one of the major Kubernetes deployment tool.
With 700 individual contributors, it has became a large project and there are now,
so many buttons&knobs that it could be overwhelming and complex for newcomers. 

Microspray is proposing a very opiniated production ready Kubernetes distribution. 
No option, we're making the choices to make it works great ! 

## Baremetal first-class 

All the main and most of the small Clouds have now a 'Managed' kubernetes service, in this space the problem is already solved. 
The problem remains for the non-cloud infrastructure aka Baremetal/dedicated/On-premise, Microspray is focusing exclusivly on those type of infrastructure.

## Main lesson of the last 5 years
If you look at all the existing tools the initial installation is ALWAYS easy. 
All distribution have a one-liner deployment command and it works. 

The problems appear day-2, when components need to be upgraded ! The container-engines, etcd, control-plane, nodes,
not only upgrading the kubernetes API version but also all softwares/operating system. 
Very few succeed in providing a good experience for the maintenance part. 

Being opinated is key, keeping all cluster deployments a reasonably homogenous shape is essential to build the right tooling to upgrade, monitor and scale.

## What know?
Want to help, please ping me on slack(@ant31) or open github Issues
