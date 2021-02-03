# Cloud Smart Examples

___

You can find the three examples we just discussed below, for your reference. Once you've had a chance to think over the examples, have a look at the quiz at the bottom of the page.

### A Data Processing Firm
This data processing firm had strict governance requirements that their customer data remain on-premises, so they had a private cloud hosting their data lake of customer data. However, they wanted to burst compute capacity for large end-of-the-month, quarterly, and annual reporting. So, they provided a virtual private network between their public and private clouds.

This allowed them to spin up and scale out analytics with high memory and GPU-accelerated public cloud infrastructure, save the results back on-prem, and then shut-down the analytics workloads. Because of the shared data, their analytics is a hybrid cloud application, even though the workload mainly runs in the public cloud.

### A Retail Outlet Business
This retail outlet business with many remote locations had local services (file and print sharing) in each store, but it used private networks to its private cloud datacenter for virtual desktops. This is how the IT organization has slowly modernized its infrastructure at the edge and in the datacenter.

A new initiative for a data lake with analytics kicked off and a team with skillsets favoring the public cloud got their project up and running quickly. The organization is running with both public and private infrastructure. None of the applications or data are shared though, so each cloud is a silo, and it is not a hybrid cloud model.

### An E-Commerce Company
This e-commerce company has a large inventory and customer database that they keep on-prem. They backup this database to the public cloud, but this is hybrid cloud storage use. If you’re wondering why, it’s because they operate the database application on-prem, and back-up the database itself to the public cloud. So, true to the hybrid model, there’s some sharing going on here.

Their developers use multiple public cloud compute for rapid and short-lived test workloads. This means they’re using multiple public clouds in a cloud-smart manner, but no data or applications are shared. This makes each public cloud a silo and it is not hybrid cloud use. Finally, they operate their web tier by load balancing across on-prem web servers and public cloud web servers, which is a hybrid cloud web tier.

### What do these examples demonstrate?
Ultimately, to be truly hybrid is to not have silos. But it’s also possible – as the e-commerce company illustrated – to be cloud-smart and not hybrid. Workloads that were the right fit for the public cloud were on the public cloud, and those that needed to be shared between on-prem and public were.

What matters is the best fit. Where a workload belongs is where it should be, based entirely on what’s best for the business.