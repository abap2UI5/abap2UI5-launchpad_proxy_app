## Extension - abap2UI5 Service Integration
### Information
This project allows the integration of abap2UI5 apps with 
* SAP Fiori Launchpad (on-premise)
* SAP Build Workzone Launchpad (cloud)
* SAP Mobile Start (device)

### Functionality
  
It encapsulates abap2UI5 into a frontend UI5 app which can be deployed to:
* SAP BTP
* ABAP Backend (S/4, R/3)
 
And calls your abap2UI5 apps via an OData Service using the Destination Service:
* S/4 Cloud
* SAP BTP ABAP Environment
* S/4 On-Premise (via Cloud Conector)

### Installation
The project consists of three additional branchens:
1. Frontend UI5 application, deploy it to your abap system or btp
2. Backend Odata Serice (abap_cloud), CDS service
3. Backend OData Service (standard_abap), SEGW service

First install the OData service with abapGit in the system where your abap2UI5 apps are running (1). Next setup your detination in SAP BTP (2). Deploy now the UI5 app to your ABAP system or BTP (3). Next configure SAP Build Workzone (4) and optionally start your app with SAP Mobile Start (5).
<br>
In on-premise scenarios you can skip stept (2)(4)(5) and follow (90) instead.

### FAQ
This project is still under construction. Your PRs and comments are welcome!
