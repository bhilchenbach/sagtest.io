# Software AG Reference architecture 

## Capability Architecture 

###  Overview 

We have chosen a “boxes and connectors” style1 for the visual representation of the reference architecture with boxes representing capabilities (or products in the product view) and connectors signifying data (information) flow between the respective elements. 

The following diagram depicts the capability view of the SAG reference architecture or (short) capability architecture. 

![Software AG Reference Archiecture Capability View](/images/Software_AG_Reference_Architecture_10_Capability_View.png)
#### Figure 1.  Reference Architecture — Capability View. 

### Capabilities 

Capabilities from SAG are shown as light-blue boxes in the large middle section of the architecture diagram, surrounded by non-SAG components.  

The left side depicts ‘in-house’ components SAG customers currently own or operate, being installed either on-premise, in a private cloud, or on the edge. One also finds ‘Internet of Things’ (IoT) assets there, including devices and gateways (which then connect to the devices).  

The right side shows external parties a business typically interacts with, in particular customers, suppliers, and partners (including government and other official authorities). Additionally, SaaS (software as a service) applications are shown as well as three typical data-related applications, namely DBaaS (database as a service), business intelligence tools (BI), and historians (e.g., for process industries). 

### On premise/edge v. SaaS 

The middle area contains Software AG components or products (depending on the view selected) and comprises two horizontal sections:  

1.Software as a Service (SaaS): This section includes all offerings Software AG provides as Software as a Service for the ‘Integration & API’ and ‘IoT & Analytics’ business units. (Additional SaaS offerings on www.softwareag.cloud belong to the business unit ‘Aris & Alfabet’.)  
2.On-Premise & Edge Deployment: This section depicts components or capabilities which are typically deployed either directly on customer premises or in private clouds. For historical reasons (some) local deployments are called edge deployments in IoT (i.e., at the edge of the cloud, close to the devices and machines). 

### Data Flows 

The connecting lines between the components show the main flows of data essentially rendering this a data-flow architecture.  

The term “data” refers to business data, i.e. data that has a direct business value for the organisation using the system. Data not considered business data is not shown, for instance data flows that involve user authentication, usage metrics, machine learning models, code artefacts, or configuration data. 

Among other factors, the actual information flow will of course depend on the products employed. For example, if a customer decides not to use the «Managed File Transfer» capability, «files» would be directly connected to the «Integration & Messaging» capability 

### Aims 

The main aims of this architecture are  

*to give a (visual) summary of the major high-level capabilities  
*to show how these capabilities map to Software AG products, and  
*to show how these elements (capabilities or products) are connected to each other through the typical flow of data. 

Even though the reference architecture is quite comprehensive, it neither shows all capabilities nor all products Software AG offers. Please refer to the ‘Products A-Z’ page on www.softwareag.com for a comprehensive list of products.  

Furthermore, this is a reference architecture illustrating typical deployments of Software AG technology with its major and most characteristic communication links. Individual installations will therefore deviate from this reference architecture only for good and sound (architectural) reasons (but we know that this may very well be the case).  

## Product Architecture 

The following diagram depicts the product view of the SAG reference architecture or (short) product architecture. 

![Software AG Reference Archiecture Capability View](/images/Software_AG_Reference_Architecture_10_Product_View.png)
#### Figure 2. Reference Architecture — Product view. 

A «product» in the aforementioned diagram represents a software component or service which a customer may purchase (in the case of software) or contract (in the case of services) from SAG. 

# Software AG Reference Architecture: Integration & IoT 

 (I removed the heading title from the Visio document for some reasons)  

 

[interactive version of the architecture] 

 

Very close to the architecture, like a footer:  

## How to use the diagram? 

Please try out the interactive features of this diagram! Use the green button to toggle between the capability description and product names. Use «mouse over» near any architecture component to display further details about the capability or product. Also, when product names are visible, click on the product to open the details page for the product. 

## What does this architecture show? 

This diagram shows the fundamental components and products offered by Software AG in the area of Integration, API, IoT and Analytics. 

The main purpose of this architecture is to give you a visual summary of the major high-level capabilities, and to show how these map to Software AG products. The diagram is neither showing all capabilities nor all products that Software AG offers. For example, business transformation capabilities offered by ARIS are not shown. Please refer to the ‘Products A-Z’ page on www.softwareag.com for a comprehensive list of products. 

Capabilities or products from Software AG are shown as boxes with blue borders in the middle of the architecture diagram, surrounded by non-Software AG components. The left side depicts ‘in-house’ components our customers currently own or operate, being installed either on-premise, in a private cloud, or on the edge. One also finds Internet of Things (IoT) assets there, including devices and gateways (which then connect to the devices). The right side shows external parties a business typically interacts with, in particular customers, suppliers, and partners (including government and other official authorities). You will also find SaaS (software as a service) offerings of third parties you subscribe to, which may also include PaaS (platform as a service)-like offerings such as DBaaS (database as a service). Additionally, we have depicted data-related functions like business intelligence tools (BI) and historians (e.g., for process industries) which are often utilized in customer use cases. 

The middle area contains Software AG components or products (depending on the view selected) and comprises two horizontal sections:  

1. Software as a Service (SaaS): This section includes all offerings Software AG provides as Software as a Service for the Integration, API, IoT, and Analytics domains. (Additional SaaS offerings on www.softwareag.cloud belong to the domain Business Transformation)  
2. On-Premise & Edge Deployment: This section depicts similar products or capabilities as the SaaS section, but are deployed either directly on customer premises, on the edge, or in private clouds. 

The connecting lines show the main flows of data essentially rendering this a data-flow architecture. Among other factors, the actual data flow will of course depend on the products employed. For example, if a customer decides not to use the «Managed File Transfer» capability, «files» would be directly connected to the «Integration & Messaging» capability 

Furthermore, this is a reference architecture illustrating typical deployments of Software AG technology with its major and most characteristic communication links. Individual installations will therefore deviate from this reference architecture only for good and sound (architectural) reasons (but we know that this may very well be the case).  

Note that this architecture focuses on run-time aspects of our portfolio. That implies that governance and design-time related capabilities and products of the Business Transformation domain, ARIS and Alfabet, are not included here. 

## Hybrid Architecture 

Many companies employ a “cloud first” strategy, which demands to preferably use cloud-based capabilities (SaaS) where reasonable, while maintaining robust on-premise capabilities in protection of existing investments. The resulting architecture (often called a ‘hybrid’ architecture) requires seamless interoperability of the components on both sides of the firewall. The above architecture illustrates this: the cloud part is shown in the upper part, the on-premise part is shown below (at the bottom), and both parts are connected at various points to create a true hybrid architecture. 

## How to use this architecture diagram 

The above reference architecture can be used as the basis for your enterprise specific architecture. You can use the reference architecture, copy it and modify it for your specific use cases. To do that, feel free to access the artifacts of the reference architecture here:  

https://github.com/SoftwareAG/softwareag-reference-architecture 

Software AG is happy to work with you on an individual solution architecture that suits your specific requirements. 
