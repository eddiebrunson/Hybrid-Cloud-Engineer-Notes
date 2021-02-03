# Legacy IT: Centralized Storage and 3-Tier 

___

### Why Centralized Storage?
A key factor in the success of a business is its ability to store massive amounts of data and access it reliably. However, as distributed computing grew in popularity, this proved to be a problem. Data residing in direct attached storage grew massively, and organizations needed more space than what was locally available. At the same time, high availability was an increasingly important factor for storage, something that local storage could not provide.

The answer came in the form of centralized storage.

### What is Centralized Storage?
Centralized storage, as the name suggests, involves high volume, shareable storage that can be accessed by multiple servers over the network. It provides standalone servers with pools of storage and data protection via multiple network paths, multiple storage processors, and RAID protection at the disk level.

There are two important forms of centralized storage: SAN, or Storage Area Network, and NAS, or Network Attached Storage. A SAN is a dedicated, specialized, high speed network that provides access to block-level storage. A SAN typically consists of hosts, switches, and storage devices, all connected to each other. Previously, SAN used Fibre Channel fabrics to connect servers to storage arrays at the block level. Now, many use iSCSI or Fibre Channel over ethernet.

A NAS is a storage device that is connected to a network and allows data to be stored and retrieved from a centralized location. NAS devices use Ethernet to access shared storage devices at the file level.

### 3-tier Architecture
Centralized storage works with distributed computing to create the 3-tier infrastructure architecture that is popularly used in datacenters today. In this computing model, servers and storage are separate entities, connected through a storage network.

### Advantages
1. Centralized storage solved the data availability problem that was caused by distributed computing.
2. The ability to add storage separately from computing resources also meant that companies could scale storage to meet the needs of their growing data.
3. An added benefit was that application high-availability became easier in distributed environments, because centralized storage facilitated shared disk access for clustering.

### Disadvantages
However, there were disadvantages as well:

1. Storage array and network management became a specialized IT domain, resulting in the need for specialized skills.
2. As centralized storage increased in sophistication, it also brought increased complexity via concepts like SAN fabrics, WWPNs, RAID groups, volumes, spindle counts, and so on.
3. The flexibility to add storage separately from computing meant that scaling was also uneven – storage was scaled in large blocks, while servers were scaled in smaller increments.
4. This resulted in large CapEX commitments when storage was needed. Since storage was purchased in large blocks, it could sometimes take years to fill the available disk space, resulting in very long time to value.