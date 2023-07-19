## Extension - abap2UI5 Service Integration
#### Features
This repository enables the integration of abap2UI5 apps with the following services: 
* SAP Fiori Launchpad (on-premise)
* SAP Build Workzone Launchpad (cloud)
* SAP Mobile Start

The abap2UI5 apps can remain unchanged in your backend systems and will be accessed remotely.

| SAP BTP Deployment  | SAP Build Workzone Launchpad | SAP Mobile Start |
| ------------- | ------------- | ------------- |
| <img width="300" alt="image" src="https://github.com/abap2UI5/ext-service_integration/assets/102328295/b6406c48-0b09-4f0e-b261-6d7f1a8892b2">  | <img width="300" alt="image" src="https://github.com/abap2UI5/ext-service_integration/assets/102328295/e6e9da75-021a-45c4-a3c5-bb471d1aedb4">  | <img width="300" alt="image" src="https://github.com/abap2UI5/ext-service_integration/assets/102328295/207d4538-ceaa-4f7d-a7f1-a15412492188"> |

#### Technical Background
The project involves the encapsulation of abap2UI5 into a "fake" frontend UI5 app, which can be deployed to:
* SAP BTP (Business Technology Platform)
* ABAP Backend (S/4, R/3)

The abap2UI5 apps are accessed through an OData Service (Destination Service), which can connect to:
* S/4 Public Cloud
* SAP BTP ABAP Environment
* S/4 On-Premise (via Cloud Connector)

#### Installation
The project consists of three additional branchens:
* UI5 application, deploy it to your abap system or btp
* OData Service (abap_cloud), CDS service
* OData Service (standard_abap), SEGW service

Follow these steps:
1. Install the OData service with abapGit in the system where your abap2UI5 apps are running
2. Setup your detination in SAP BTP
3. Deploy the UI5 app to your ABAP system or BTP
4. Configure SAP Build Workzone
5. Start your app with SAP Mobile Start (optional)
   
In on-premise scenario you can skip step (2)(4)(5) and instead:
* Configure SAP Fiori Launchpad

#### FAQ
* your comments, questions, wishes and bugs are welcome, please create an [issue](https://github.com/abap2UI5/ext-service_integration/issues)
