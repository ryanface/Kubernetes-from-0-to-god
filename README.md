<h1 align="center">Kubernetes From Zero to God</h1>


<p align="center">An Overview of Kubernetes Concepts</p>


![Badge](https://img.shields.io/static/v1?label=Kubernetes&message=From%20Zero%20To%20God&color=326CE5&style=for-the-badge&logo=ghost)


<h4 align="center"> 
	🚧  🚀 Em construção...  🚧
</h4>

<!--ts-->
### Table Contents
    * [Basic Terminology](#Basic-Terminology)
    * [Advanced Terminology](#Advanced-Terminology)
      * [Plus](#Plus)
<!--te-->


### Basic Terminology
  -> Container
  -> Image
  -> Container Image
  -> Image Layer
  -> Index
  -> Registry
  -> Repository
  -> Tag
  -> Base Image
  -> Platform Image
  -> Layer 
<a href="https://developers.redhat.com/blog/2016/01/13/a-practical-introduction-to-docker-container-terminology/">Here</a>

### Advanced Terminology 
  -> Container Image Format
  -> Container Engine
  -> Container Host
  -> Registry Server
  -> Container Orchestration
  -> Container Runtime
  -> Kernel Namespace
  -> Graph Driver
  -> Container Use Cases
  -> Application Containers
  -> Operating System Containers
  -> Pet Containers
  -> Super Privileged Containers
  -> Architecture of Containers
  -> Application Images
  -> Containerized  Components
  -> Deployer Images
  -> System Containers  
<a href="https://developers.redhat.com/blog/2018/02/22/container-terminology-practical-introduction/#h.6yt1ex5wfo3l">Here</a>


[![GitHub issues](https://img.shields.io/static/v1?label=Kubernetes&message=From%20Zero%20To%20God&color=326CE5&style=for-the-badge&logo=ghost)](https://github.com/ryanface/Kubernetes-from-zero-to-god/issues)


### Plus

- understanding-user-space-vs-kernel-space : <a href="https://www.redhat.com/en/blog/architecting-containers-part-1-why-understanding-user-space-vs-kernel-space-matters">Here</a>

  ![kernel-space-matters](./img/user-space-vs-kernel-space-system-calls-gears.png =300x200)


Open Container Initiative Runtime Specification : <a href="https://github.com/opencontainers/runtime-spec/blob/master/spec.md">Here</a>
 -> The Open Container Initiative develops specifications for standards on Operating System process and application containers.



- Cgroup vs Namespaces


cgroup: Control Groups provide a mechanism for aggregating/partitioning sets of tasks, and all their future children, into hierarchical groups with specialized behaviour.
namespace: wraps a global system resource in an abstraction that makes it appear to the processes within the namespace that they have their own isolated instance of the global resource.

In short:

Cgroups = limits how much you can use;
namespaces = limits what you can see (and therefore use)
See more at "Anatomy of a Container: Namespaces, cgroups & Some Filesystem Magic" by Jérôme Petazzoni.

Cgroups involve resource metering and limiting:

memory
CPU
block I/O
network
Namespaces provide processes with their own view of the system

Multiple namespaces:

pid
net
mnt
uts
ipc


- Docker vs LXD vs LXC

 -> Comparativo: 
 ![file](./pdf/docker vs LXD&LXC.pdf) 

 -> kubernetes-is-removing-docker-support: <a href="https://www.openshift.com/blog/kubernetes-is-removing-docker-support-kubernetes-is-not-removing-docker-support">Here</a>

