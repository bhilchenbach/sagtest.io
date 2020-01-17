# Software AG Reference Architecture 

link to site https://github.com/bhilchenbach/sagtest.io

<iframe></iframe>

<iframe src="https://github.com/bhilchenbach/sagtest.io/blob/master/Software_AG_Reference_Architecture.html" style="border:none;"></iframe> 

### Aims 

The main aims of this architecture are  

* to give a (visual) summary of the major high-level capabilities  
* to show how these capabilities map to Software AG products, and  
* to show how these elements (capabilities or products) are connected to each other through the typical flow of data. 

This architecture focuses on run-time aspects of our portfolio. That implies that governance and design-time related capabilities and products of the Business Transformation domain, ARIS and Alfabet, are not included here. 

Furthermore, even though the reference architecture is quite comprehensive, it neither shows all capabilities nor all products Software AG offers. Please refer to the ‘Products A-Z’ page on www.softwareag.com for a comprehensive list of products.  

As a reference, this architecture illustrating typical deployments of Software AG technology with its major and most characteristic communication links. Individual installations will therefore deviate from this reference architecture only for good and sound (architectural) reasons (but we know that this may very well be the case).  


## Capability Architecture 

###  Overview 

We have chosen a “boxes and connectors” style for the visual representation of the reference architecture with boxes representing capabilities (or products in the product view) and connectors signifying data (information) flow between the respective elements. 

The following diagram depicts the capability view of the SAG reference architecture or (short) capability architecture. 

![Software AG Reference Archiecture Capability View](/images/Software_AG_Reference_Architecture_10_Capability_View.png)
#### Figure 1.  Reference Architecture — Capability View 

### Capabilities 

Capabilities from SAG are shown as light-blue boxes in the large middle section of the architecture diagram, surrounded by non-SAG components.  

The left side depicts ‘in-house’ components SAG customers currently own or operate, being installed either on-premise, in a private cloud, or on the edge. One also finds ‘Internet of Things’ (IoT) assets there, including devices and gateways (which then connect to the devices).  

The right side shows external parties a business typically interacts with, in particular customers, suppliers, and partners (including government and other official authorities). Additionally, SaaS (software as a service) applications are shown as well as three typical data-related applications, namely DBaaS (database as a service), business intelligence tools (BI), and historians (e.g., for process industries). 


### On premise/edge v. SaaS 

The middle area contains Software AG components or products (depending on the view selected) and comprises two horizontal sections:  

**1. Software as a Service (SaaS):** This section includes all offerings Software AG provides as Software as a Service for the ‘Integration & API’ and ‘IoT & Analytics’ business units. (Additional SaaS offerings on www.softwareag.cloud belong to the business unit ‘Aris & Alfabet’.)  
**2. On-Premise & Edge Deployment:** This section depicts components or capabilities which are typically deployed either directly on customer premises or in private clouds. For historical reasons (some) local deployments are called edge deployments in IoT (i.e., at the edge of the cloud, close to the devices and machines). 

### Data Flows 

The connecting lines between the components show the main flows of data essentially rendering this a data-flow architecture.  

The term “data” refers to business data, i.e. data that has a direct business value for the organisation using the system. Data not considered business data is not shown, for instance data flows that involve user authentication, usage metrics, machine learning models, code artefacts, or configuration data. 

Among other factors, the actual information flow will of course depend on the products employed. For example, if a customer decides not to use the «Managed File Transfer» capability, «files» would be directly connected to the «Integration & Messaging» capability 


## Product Architecture 

The following diagram depicts the product view of the SAG reference architecture or (short) product architecture. 

![Software AG Reference Archiecture Capability View](/images/Software_AG_Reference_Architecture_10_Product_View.png)
#### Figure 2. Reference Architecture — Product view. 

A «product» in the aforementioned diagram represents a software component or service which a customer may purchase (in the case of software) or contract (in the case of services) from SAG. 

## How to use this architecture diagram 

The above reference architecture can be used as the basis for your enterprise specific architecture. You can use the reference architecture, copy it and modify it for your specific use cases. To do that, feel free to access the artifacts of the reference architecture here:  

https://github.com/SoftwareAG/softwareag-reference-architecture 




Software AG is happy to work with you on an individual solution architecture that suits your specific requirements. 
