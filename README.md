## Extension - abap2UI5 Service Integration
This repository enables the integration of abap2UI5 apps with the following services: 
| Services  | |
| ------------- | ------------- |
| **SAP BTP HTML5 Repo** <br> Use your abap2UI5 apps from everywhere | **SAP Build Workzone Launchpad** <br> Configure different start apps with a launchpad running on SAP BTP|
| <img width="333" alt="image" src="https://github.com/abap2UI5/ext-service_integration/assets/102328295/b6406c48-0b09-4f0e-b261-6d7f1a8892b2">  | <img width="333" alt="image" src="https://github.com/abap2UI5/ext-service_integration/assets/102328295/e6e9da75-021a-45c4-a3c5-bb471d1aedb4">  |
| **SAP Mobile Start** <br> Use your mobile device and download SAP mobile start for apple and android  | **SAP Fiori Launchpad (on-premise)** <br> Use the on-premise Fiori Launchpad |
| <img width="333" alt="image" src="https://github.com/abap2UI5/ext-service_integration/assets/102328295/207d4538-ceaa-4f7d-a7f1-a15412492188"> | 🚧 under construction 🚧  |

❗️ _The abap2UI5 framework & apps can remain unchanged in your backend systems and will be accessed remotely_ ❗️
#### Technical Background
The project consists of a (generic) frontend UI5 app, which can be deployed to:
* SAP BTP (Business Technology Platform)
* ABAP Backend (S/4, R/3)

The abap2UI5 framework & apps are accessed through an OData Service, which can connect to:
* S/4 Public Cloud
* SAP BTP ABAP Environment
* S/4 and R/3 On-Premise (via Cloud Connector)

#### Installation
Follow these steps:
1. [Install the OData service with abapGit in the system where your abap2UI5 apps are running](https://github.com/abap2UI5/ext-service_integration/blob/main/docs/01_odata_installation.md)
2. [Setup your destination in SAP BTP](https://github.com/abap2UI5/ext-service_integration/blob/main/docs/02_destination_service_configuration.md)
3. [Deploy the UI5 app to your ABAP system or BTP](https://github.com/abap2UI5/ext-service_integration/blob/main/docs/03_app_deployment.md)
4. [Configure SAP Build Workzone](https://github.com/abap2UI5/ext-service_integration/blob/main/docs/04_build_workzone_configuration.md)
5. [Start your app with SAP Mobile Start](https://github.com/abap2UI5/ext-service_integration/blob/main/docs/05_mobile_start_configuration.md) (optional)
   
In on-premise scenario you can skip step (2)(4)(5) and instead:
* [Configure SAP Fiori Launchpad](https://github.com/abap2UI5/ext-service_integration/blob/main/docs/90_fiori_launchpad_configuration.md)

#### FAQ
* your comments, questions, wishes and bugs are welcome, please create an [issue](https://github.com/abap2UI5/ext-service_integration/issues)
