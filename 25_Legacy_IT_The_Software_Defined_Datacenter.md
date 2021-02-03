# Legacy IT: The Software Defined Datacenter (SDDC)

### What is The Software Defined Datacenter (SDDC)?
The idea behind the software defined datacenter, or SDDC, is that everything is implemented in a single layer.

To put it in more technical terms, an SDDC is an integrated abstraction layer that defines a complete datacenter by means of a layer of software that presents the resources of the datacenter as pools of virtual and physical resources and allows their composition into arbitrary user-defined services. A modern SDDC deployment is defined by virtualized, software-defined resources that can be scaled up or down as required and can be deployed as needed in a number of distinct ways.

There are three key components to the SDDC:

* Software defined computing
* Software defined networking
* Software defined storage

There's also often a fourth layer known as the orchestration management layer. Gartner's John Morency describes it as "The intelligence that enables the operations team to do the initial configuration in terms of defining the virtual machines, the storage, the network interconnections, and if they need to, support a specific application or set of applications."

SDDC as a concept began with virtualized compute, and so most enterprises tend to start with that layer as well. Forrester’s Robert Stroud goes so far as to say that software-defined computing is extremely well adopted, but that he is seeing growth in software-defined storage and networking as well.

The automation layer that an SDDC adds facilitates single-pane deployment and management of VMs, network resources, and storage required to provide any service requested by a user. By pooling all datacenter resources, an SDDC converges compute and networking in a software layer that logically spans the entire datacenter. However, the storage layer remains unvirtualized. It still has a different management plane. It still requires specialized skills to manage the physical network that it’s connected to and the storage devices as well.

A three-tier software-defined datacenter is close, but it isn’t completely converged.

SDDC allows for huge gains in productivity through API-addressable management, automation, and orchestration tools with virtual switches, firewalls, load-balancers, and other devices running on the hypervisor.

These tools provide a number of benefits, including:

* Consolidated infrastructure and user management
* Automated lifecycle management
* Increased security through network segmentation and traffic inspection
* Automatic scale out of VMs on demand
* Failover and failback
* Configuration management
* Automated updates, health checks
* Chargeback for resource usage

In 3-Tier SDDC implementations the shared storage may be logically pooled, but the devices are still hardware-based, SAN or NAS, and separated from physical servers by a dedicated network. This means that SAN, NAS and the networks supporting them are typically outside the natural SDDC management plane and must be managed separately.

SAN and NAS also scale in big blocks while the rest of the SDDC scales per server. This can lead to huge blocks of storage resources sitting idle for extended periods of time. It doesn’t make sense economically to have such a large mismatch between the way servers and storage need to scale. And finally, 3 Tier SDDC is only 66% converged by design. This means you’re missing a full one-third of the power of SDDC!

As with legacy IT, an SDDC’s cloud readiness can also be low or high.

Cloud readiness will be high if there is:

* Catalog-based self-service available to users
* A DevOps initiative
* Micro-serviced-based application architecture is in use
* Containers are being used for some applications.

 Cloud readiness will be low if:

* The current SDDC environment is used to run legacy, shrink-wrapped applications exclusively
* The IT staff managing the physical infrastructure is still siloed and segregated based on the 3-tier model