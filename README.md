## Extension - abap2UI5 Service Integration
### Information
This project allows the integration of abap2UI5 apps to 
* SAP Fiori Launchpad (on-premise)
* SAP Build Workzone Launchpad (cloud)
* SAP Mobile Start
  
It encapsulates abap2UI5 into a frontend UI5 app which can be deployed to (1) SAP BTP or (2) ABAP Backend (S/4, R/3). It calls your abap2UI5 apps via an OData Service using the Destination Service. The abap2UI5 apps can remain unchanged in your backend systems (1) S/4 Cloud (2) SAP BTP ABAP Environment or (3) S/4 On-Premise (via Cloud Conector).

### Installation
The project consists of three additional branchens:
* UI5 application, deploy it to your abap system or btp
* OData Service (abap_cloud), CDS service
* OData Service (standard_abap), SEGW service

Follow this steps:
1. Install the OData service with abapGit in the system where your abap2UI5 apps are running
2. Setup your detination in SAP BTP
3. Deploy now the UI5 app to your ABAP system or BTP
4. Configure SAP Build Workzone
5. Start your app with SAP Mobile Start (optional)
   
In on-premise scenario you can skip step (2)(4)(5) and do instead:
* Configure SAP Fiori Launchpad

### FAQ
🚧 This project is still under construction. Your PRs and comments are welcome! 👷
