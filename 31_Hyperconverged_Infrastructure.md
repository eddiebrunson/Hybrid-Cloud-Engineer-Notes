# Hyperconverged Infrastructure (HCI)

### What is Hyperconverged Infrastructure (HCI)

**Hyperconverged Infrastructure (HCI)** converges the entire datacenter stack, including compute, storage, networking, and virtualization. Some key points to remember about HCI are:

Software running on each server node distributes all operating functions across a cluster. This allows incremental scaling, so that a cluster can be grown one node at a time; performance increases as the environment grows.
The software also creates clusters and pools local storage, eliminating the need for SAN or NAS infrastructure​.
The removal of the physical storage fully unleashes the power of the SDDC.
The use of solid state drives (SSDs), combined with data locality, provides excellent cluster performance without bottlenecks.
Note that unlike its 3-tier incarnation – which was only 66% converged – HCI is fully converged.

### SSDs and HCI

They key points to remember about SSDs and HCI are:

* SSDs improve performance of the storage tier if they are bottlenecking on read-write performance at the disk level.
* To leverage the extreme advances in performance, the controllers and network need to be able to handle the vast I/O capabilities of SSDs.
* Data locality is a key component of HCI; not having to transit the network provides better utilization of an SSDs capabilities.

### HCI and Private Cloud

Out of the box, HCI isn’t a true private cloud. To have a fully operational private cloud, you also need to have:

* Unified management support
* One-click upgrades
* Customizable security
* Built-in data services for file, block, and object storage
* Sophisticated backup and disaster recovery solutions
* Tools for automation and self-service; and cost governance

Having HCI infrastructure in place will bring you much closer to being hybrid cloud-ready vs. having your infrastructure stack built on legacy IT.

Your cloud readiness will be high if:

* A Private Cloud is deployed on the HCI
* There is catalog-based self-service available to users
* There is a DevOps initiative and micro-service-based application architecture is in use
* Containers are being used for some applications,
* The use of the Public Cloud is being considered to supplement the infrastructure where appropriate

In contrast, you can have an HCI deployment but still have low cloud readiness if:

* An HCI deployment is being used exclusively to run legacy, shrink-wrapped applications
* Automation and orchestration tools are not being leveraged
* There is no supplemental use of Public Cloud