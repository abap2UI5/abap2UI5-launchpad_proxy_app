## abap2UI5 Integration - SAP Fiori Launchpad (On-Premise) <img src="https://github.com/abap2UI5/abap2UI5/assets/102328295/52ac0bb6-a219-4e9d-9e4f-62698dab3063" width="30">

_Running into problems or found a bug? Create an issue [**here**](https://github.com/abap2UI5/abap2UI5/issues)_

#### Key Features
* enables the integration of abap2UI5 Apps into SAP Fiori Launchpads (On-Premise)
* the repository contains an UI5 App (BSP) and a HTTP Service for the communication with abap2UI5
* the abap2UI5 apps and the framework's functionality remain unaltered
* the integration is compatible with SAP Netweaver (v.7.50 or higher) or S/4 Private (Standard ABAP)
* installation can be performed using [**abapGit**](https://abapgit.org) ![abapGit](https://docs.abapgit.org/img/favicon.png)
  
#### Functionality
<img width="800" alt="Bildschirmfoto 2023-12-26 um 11 31 11" src="https://github.com/abap2UI5/abap2UI5-launchpad_on_premise/assets/102328295/6c4b5977-61ec-40e9-a246-b223387666d5">
<img width="700" alt="image" src="https://github.com/abap2UI5/ext-fiori_launchpad_on_premise/assets/102328295/17c375e8-10cd-471e-83f8-d62ed27224e3">

#### Installation
After the installation with abapGit, three ICF nodes are created (1) HTTP Service and (2)(3) for the UI5 App. Check in transaction SICF if they are available and activated. Launch the UI5 app from this provided node:<br>
<img width="500" alt="image" src="https://github.com/abap2UI5/abap2UI5-launchpad_on_premise/assets/102328295/48ccfcce-4f20-49f4-8687-652327e25687"><br>
<img width="500" alt="Bildschirm­foto 2023-08-06 um 14 52 42" src="https://github.com/abap2UI5/ext-fiori_launchpad_on_premise/assets/102328295/1ddaba83-70d8-49b1-8a19-60cdd7d3b748">

Use this app for the launchpad integration as described [**here.**](https://github.com/abap2UI5/abap2UI5-documentation/blob/main/docs/ext-fiori_launchpad_integration/launchpad_setup.md)
For more installation guidelines, check out this [**link.**](https://github.com/abap2UI5/abap2UI5-documentation/blob/main/docs/ext-fiori_launchpad_integration/installation.md)

#### Parameters
Maintain the following start parameters:
| Name  | Explanation |
| ------------- | ------------- |
| APP_START  | classname of the app for the initial call |
| APP_TITLE  | title which is set via frontend  (optional) |

_If your classname is developed in a custom namespace, use -MY_NS-CL_MY_CLASS instead of /MY_NS/CL_MY_CLASS, "-" is mapped to "/" automatically_
#### FAQ
* check out the [**documentation**](https://github.com/abap2UI5/abap2UI5-documentation) for installation & configuration guidelines
* your comments, questions, wishes and bugs are welcome, please create an [**issue**](https://github.com/abap2UI5/integration-fiori_launchpad_on_premise/issues)
