### Guideline - Develop and deploy a new UI5 app

1. Start your Business Application Studio and Login to BTP

<img width="350" alt="image" src="https://github.com/abap2UI5/ext-service_integration/assets/102328295/88247f70-2661-4f12-990c-06f99075b075">
<br>
<img width="350" alt="image" src="https://github.com/abap2UI5/ext-service_integration/assets/102328295/6bc46022-045b-48da-9ac6-7fff49de87e6">

2. Create a new UI5 app (or Import the branch ui5_app)

<img width="700" alt="image" src="https://github.com/abap2UI5/ext-service_integration/assets/102328295/9b3ba6b7-742b-48ec-a165-03d7143ee61d">

<img width="700" alt="image" src="https://github.com/abap2UI5/ext-service_integration/assets/102328295/2b763e0f-088b-4ee5-8044-b3e5ffb25b94">

<img width="700" alt="image" src="https://github.com/abap2UI5/ext-service_integration/assets/102328295/51fbd60f-276e-4542-9a7c-0c57f767fa8c">

Add to the controller the following onAfterRendering method:
<img width="700" alt="image" src="https://github.com/abap2UI5/ext-service_integration/assets/102328295/60b89480-f6f6-48a2-bb99-0a6d40509b8f">

<br>

3. Deploy your App to SAP BTP (or to your ABAP system)

npx fiori add deploy-config
And choose your target:
<img width="500" alt="image" src="https://github.com/abap2UI5/ext-service_integration/assets/102328295/ffea36b0-b311-48d6-8e96-725262023662">
And destination:
<img width="700" alt="image" src="https://github.com/abap2UI5/ext-service_integration/assets/102328295/8f4af03c-eeba-4de8-a941-2403905147ec">
for use in sap workzone launchapad choose Add application to managed application router (yes):
<img width="700" alt="image" src="https://github.com/abap2UI5/ext-service_integration/assets/102328295/c4d43c4b-e39b-40ce-9d3c-979dd9fc887e">


Next add launchpad configuration:
npx fiori add flp-config

<img width="700" alt="image" src="https://github.com/abap2UI5/ext-service_integration/assets/102328295/41d8dbf7-ea60-4d62-bd1b-a9f3e3c1519d">

npm run build:mta
<img width="700" alt="image" src="https://github.com/abap2UI5/ext-service_integration/assets/102328295/d426a249-951d-4a9f-bb2c-68becee41c5f">

npm run deploy
<img width="700" alt="image" src="https://github.com/abap2UI5/ext-service_integration/assets/102328295/5518073e-46a3-4e73-92d5-4509815a7563">

Check 
<img width="700" alt="image" src="https://github.com/abap2UI5/ext-service_integration/assets/102328295/06231cea-19f5-42aa-ae8b-33146c30e639">
It is now running with odata:
<img width="700" alt="image" src="https://github.com/abap2UI5/ext-service_integration/assets/102328295/9617e6a0-61d1-419a-97ed-a16e7e69869c">
