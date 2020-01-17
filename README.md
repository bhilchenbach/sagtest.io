## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/bhilchenbach/sagtest.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/bhilchenbach/sagtest.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

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
