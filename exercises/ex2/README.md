# Exercise 2 - Connect SAP HANA Cloud to SAP Cloud ALM

To monitor SAP HANA Cloud, the HANA Cloud instance needs to be connected to SAP Cloud ALM using an endpoint. Over this endpoint, the data collection of the monitoring data in SAP HANA Cloud is triggered, and the data is collected.

Endpoints are created in the Landscape Management application.

## Exercise 2.1 Log to SAP Cloud ALM

Your trainer will provide:  
- SAP Cloud ALM URL: https://teched22-cloudalm-002.eu10.alm.cloud.sap/launchpad#Shell-home
- User: xp261-XXX@tdcteched.com (Please replace _**XXX**_ with your group number)
- Password: S4PT3ch3d-22!

Please connect via browser to the provided URL. Select the **httpstdcteched1.accounts.ondemand.co** Identity Provider.
Use your credentials to log in.  
<br>![](/exercises/ex2/images/Ex2_1.png)  
<br>![](/exercises/ex2/images/Ex2_2.png)

## Exercise 2.2 Close Information Banner

You can close the information banner, if there is one.  
<br>![](/exercises/ex2/images/Ex2_3.png)

## Exercise 2.3 Open Landscape Management

You will now see the SAP Cloud ALM Launchpad.  
Click on “Administration” → “Landscape Management”  
<br>![](/exercises/ex2/images/Ex2_4.png)

## Exercise 2.4 Find your HANA Cloud Service

The Landscape Management will open in a new browser tab.  
Select the entry XP261-XXX-HANA for your group number.  
Make sure to replace _**XXX**_ with your group number!  
<br>![](/exercises/ex2/images/Ex2_5.png)

## Exercise 2.5 Add a new Endpoint

Under the section “Endpoints” click the “Add” button.  
<br>![](/exercises/ex2/images/Ex2_6.png)

## Exercise 2.6 Select use case "Health Monitoring"

Open the drop-down box “Use Case” and select “Health Monitoring”  
<br>![](/exercises/ex2/images/Ex2_7.png)

## Exercise 2.7 Adjust Root URL

Replace the value in the field “Root URL” with:  
"**https://api.gateway.orchestration.prod-us20.hanacloud.ondemand.com**"  
Do not copy the "" and be careful that no blanks are in front or behind the root URL.  
<br>![](/exercises/ex2/images/Ex2_7a.png)

## Exercise 2.8 Select Authentication Method

Select the authentication method "OAuth2ClientCredentials"  
<br>![](/exercises/ex2/images/Ex2_7b.png)

## Exercise 2.9 Copy Service Key JSON to Clipboard

Open the Service Key you downloaded earlier and copy the entire key into the clipboard (Ctrl+A followed by Ctrl+C)  
<br>![](/exercises/ex2/images/Ex2_9.png)  
<br>![](/exercises/ex2/images/Ex2_10.png)  

If you decided to keep the browser tab of the BTP Cockpit open, you can copy the JSON there.  
<br>![](/exercises/ex2/images/Ex2_9b.png)

## Exercise 2.10 Paste Service Key

Back in the endpoint creation screen, click the “Paste Service Key” button.  
<br>![](/exercises/ex2/images/Ex2_11.png)  

Allow the text to be copied.  
<br>![](/exercises/ex2/images/Ex2_12.png)

## Exercise 2.11 Check Connection

Click the button “Check Connection”.  
<br>![](/exercises/ex2/images/Ex2_13.png)  

You should receive a “Success” message.  
<br>![](/exercises/ex2/images/Ex2_14.png)

## Exercise 2.12 Save Endpoint

Click the “Save” button.  
<br>![](/exercises/ex2/images/Ex2_15.png)

## Exercise 2.12 Start Data Collection

The Health Monitoring data collection will be activated automatically with the endpoint creation.  
The status in Landscape Management will be updated after the first data collection. The monitoring data is collected within the next 5 minutes.  
<br>![](/exercises/ex2/images/Ex2_16a.png)

## Summary

You've now successfully connected SAP HANA Cloud to SAP Cloud ALM

Continue to - [Exercise 3 -	Set up Notification Management ](../ex3/README.md)
