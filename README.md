## Extension - abap2UI5 Service Integration
#### Features
This repository enables the integration of abap2UI5 apps with the following services: 
* SAP Fiori Launchpad (on-premise)
* SAP Build Workzone Launchpad (cloud)
* SAP Mobile Start

The abap2UI5 apps can remain unchanged in your backend systems and will be accessed remotely.

#### Information
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

### FAQ
🚧 This project is still under construction. Your PRs and comments are welcome! 👷
