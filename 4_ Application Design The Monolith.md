# Application Design: The Monolith 
___

Application development has been influenced by the technology stack. The application design was both constrained to one infrastructure vendor with past monolithic infrastructure. When referring to **monolithic**, it means there is one, single source of every component in the stack. 

Only big businesses or government agencies could afford the monolithic infrastructure because the cost were so high. 

Monolithic applications are still around today. 

For example some banking applications build in COBOL for mainframe has been in use for at least 40 years. 

Issues with applications like this are:

* It is a single application written in a single language. 
* It is run in a batch, or is constantly executed on a single instance of infrastructure, 
* To address performance issues and bottlenecks, it is necessary to scale up by increasing compute, storage, and memory resource. These resources are always constrained to a monolithic server's capabilities. 
* The infrastructure is also monolithic. It is provided by a single vendor, who potentially also controls the application development tools, database, and operating system layers that are running on their hardware. 

