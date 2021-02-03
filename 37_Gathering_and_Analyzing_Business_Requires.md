# Laying your Foundation: Gathering and Analyzing Business Requirements

___

Throughout this lesson, we’ve talked a lot about best fit—and insuring a good fit requires talking to your stakeholders. This will give you a 360-degree view of the workloads and services you need to support.

When you’re having that discussion, it’s important to structure the conversation around 8 major requirements:

1. Application portability
2. Compliance and security
3. Cost, including TCO and ROI
4. Scalability
5. Resilience and availability
6. Performance
7. Manageability
8. Data protection and recoverability

Let’s look at each of these requirements in a little more detail.
Deeper Dive: Application Portability

Application portability describes how easily an application can be moved between different kinds of infrastructure.

* Applications that are designed with portability in mind (e.g., containerized applications) do not require major refactoring in order to move from private to public cloud providers.
* In contrast, monolithic applications require an expensive “lift and shift” process in order to move between different platforms or even to change hypervisors.
* Another approach is to employ a data-centric strategy, where you share data between services running on multiple cloud platforms without porting applications between them. This avoids "lift and shift" campaigns and leverages applications designed to take advantage of native infrastructure and toolsets.

### Deeper Dive: Compliance and Security

Companies are subject to many regulations regarding security and data-handling—and these regulations can have a significant impact on how you utilize the cloud. These are some of the main regulations that it’s important to be familiar with:

* GDPR: The General Data Protection Regulation (GDPR) protects EU citizens from data breaches and misuse. It applies to all companies with data for EU citizens, even if those companies are not located in the EU.
* HIPAA: The Health Insurance Portability and Accountability Act (HIPAA) regulates the data security of healthcare patients. Companies that handle healthcare data (e.g., hospitals, clinics and insurance companies) are required to comply with HIPAA regulations.
* Sarbanes-Oxley Act (SOX): The Sarbanes-Oxley Act (SOX) requires U.S. company boards, management, and accounting firms to follow best practices and maintain financial records for seven years. The intent is to prevent incidents like the Enron scandal.
* FISMA: The Federal Information Security Management Act of 2002 (FISMA) treats information security as a matter of national security. All federal agencies are required to develop compliant data protection methods.
* PCI-DSS: The Payment Card Industry Data Security Standard (PCI-DSS) regulations reduce fraud by protecting customer credit card information. PCI-DSS compliance is required for all companies handling credit card information.
* GPG13: The Protective Monitoring for HMG ICT Systems regulation (GPG13) is a U.K. general data-protection regulation for business processes. It is compulsory for businesses managing high-impact data.

### Deeper Dive: Cost (TCO and ROI)

When comparing the public cloud with on-prem hybrid cloud infrastructure, it's important to consider the Total Cost of Ownership (TCO) and Return on Investment (ROI).

* Because public cloud infrastructure is rented (not owned), it has no upfront capital cost—and can thus seem better than investing in on-prem hybrid cloud infrastructure.
* However, the public cloud requires significantly more operating expenditure; thus, despite the higher up-front costs, the hybrid cloud can have significantly better long-term TCO and ROI.

### Deeper Dive: Scalability

The need to scale an application or the resources supporting an application up/out can be driven by:

* An increasing number of users
* Increased demand from existing users
* A growing data set
* Increased computational complexity

In addition, many workloads are cyclical, requiring the ability to scale up/out during periods of high demand and pull back during periods of low demand. Monolithic applications require different scale up/out strategies than modular or micro-service-based applications. If application design and other requirements permit, it is possible to have individual application components or application tiers running on Private and Public Cloud simultaneously.

When you need to decide on a scaling strategy, it’s important to consider:

1. The application architecture. Is it legacy-monolithic, multi-tier, modular, or micro-services based?
2. What the the triggers points for scaling up or scaling out are?
3. Seasonality and complete demand cycles

### Deeper Dive: Resilience and Availability

Applications need to be designed for resiliency, meaning that they can suffer a failure or degradation in one or more components and still provide service.

* Applications must take the infrastructure providing resources into account.
* Many organizations implement software across multi-tier, multiple technology infrastructures, which can make designing for resilience more complicated.
* Resilience can be provided at any or every layer of the stack.

Resilience goes hand-in-hand with availability, but availability requirements need to be clearly defined.

* For example, hardware or operating system availability does not necessarily translate to application availability.
* It’s common to underestimate the cost and complexity of providing availability, as well as overstate availability requirements.
* Understanding what’s required is critical to determining the right infrastructure for a given workload or service.

### Deeper Dive: Performance

Performance has many dimensions and dependencies, and this portion of the stakeholder conversation will likely result in a large variety of requirements. You’re likely to hear about application response times, storage performance, CPU and memory requirements for workloads, and so on.

When rolling in performance data, it’s important to be mindful of the breadth and complexity of this particular requirement. For example, application response time can be influenced by network architecture, CPU type, storage architecture, or memory type. In a multi-tenant environment, CPU saturation, storage contention, or memory oversubscription can degrade performance.

Deploying multi-tiered applications requires careful planning, especially if the infrastructure is hybrid. In the case of multi-tiered applications, performance will only be as good as the least performant tier.

### Deeper Dive: Manageability

Infrastructure and application manageability is greatly influenced by tool integrations and the availability of automation for routine and repetitive tasks.

Lack of manageability can drastically increase OPEX and degrade performance of a Private Cloud. It is especially detrimental in Hybrid Cloud deployments when tasks such as updates, troubleshooting, and scaling are delayed or fail outright.

It’s also important to consider the relative complexity of a workload from the perspective of manageability. Does it need to be on-prem because every aspect needs to be managed, or can a provider be trusted to manage a part of it?

When gathering requirements and planning your strategy, remember that a well-designed management plan show allow for SLAs to be met and monitored, in order to verify performance.

# Deeper Dive: Data Protection and Recoverability

Every application or service will have specific requirements for data protection and recoverability. At a minimum, you should determine and document the requirements for each application and service in terms of:

* The Recovery Time Objective (RTO), which refers to how long an application can be down without causing damage to the business
* The Recovery Point Objective (RPO), which refers to how much data can be lost before damage to the business occurs.

100% uptime (RTO) with no lost data (RPO) requires an investment in continuous data replication and mirrored infrastructure, but not every application or service will require this level of protection. When 100% uptime requirements or zero data loss requirements do exist, cloud-based options for backup and recovery can provide low-cost alternatives.