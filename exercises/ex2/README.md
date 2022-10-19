# Exercise 2 - Connect SAP HANA Cloud to SAP Cloud ALM

To monitor SAP HANA Cloud, the HANA Cloud instance needs to be connected to SAP Cloud ALM using an endpoint. Over this endpoint, the data collection of the monitoring data in SAP HANA Cloud is triggered, and the data is collected.

Endpoints are created in the Landscape Management application.

## Exercise 2.1 Log in

Your trainer will provide:

•	SAP Cloud ALM URL

•	User email

•	Password

Please connect via browser to the provided URL. Select the httpstdcteched1.accounts.ondemand.co Identity Provider.
Use your credentials to log in. 

1. Click here.
<br>![](/exercises/ex2/images/2-1-1.png)

<br>![](/exercises/ex2/images/2-1-2.png)


## Exercise 2.2 SAP Cloud ALM Starting Page

You can close the information banner, if there is one.

2.	Click here.
<br>![](/exercises/ex2/images/2-2.png)

## Exercise 2.3 Open Landscape Management

You will now see the SAP Cloud ALM Launchpad. 
Click on “Administration” → “Landscape Management”

3.	Click here.
<br>![](/exercises/ex2/images/2-3.png)

## Exercise 2.4 Select your group number

The Landscape Management will open in a new tab. 
Select the entry XP261-XXX-HANA for your group number.
Make sure the replace XXX with your group number!

4.	Click here.
<br>![](/exercises/ex2/images/2-4.png)

## Exercise 2.5 Add Enpoint

Under the section “Endpoints” click the “Add” button.

5.	Click here.
<br>![](/exercises/ex2/images/2-5.png)

## Exercise 2.6 Select "Health Monitoring"

Open the drop-down box  “Use Case”and select “Health Monitoring”

6.	Click here.
<br>![](/exercises/ex2/images/2-6.png)

## Exercise 2.7 Change Root URL

Replace the value in the field “Root URL” with: 
https://api.gateway.orchestration.hana.prod-us20.hanacloud.ondemand.com 

7.	Click here.
<br>![](/exercises/ex2/images/2-7.png)

## Exercise 2.8 Copy Service Key

Open the Service Key you downloaded earlier and copy the entire key into the clipboard (Ctrl+A followed by Ctrl+C)

8.	Click here.
<br>![](/exercises/ex2/images/2-8-1.png)

<br>![](/exercises/ex2/images/2-8-2.png)

## Exercise 2.9 Past Service Key

Back in the endpoint creation screen, click the “Paste Service Key” button.
Allow the text to be copied.

9.	Click here.
<br>![](/exercises/ex2/images/2-9-1.png)

<br>![](/exercises/ex2/images/2-9-2.png)

## Exercise 2.10 Check Connection

Click the button “Check Connection”.
You should receive a “Success” message.

10.	Click here.
<br>![](/exercises/ex2/images/2-10-1.png)

<br>![](/exercises/ex2/images/2-10-2.png)

## Exercise 2.11 Save Endpoint

Click the “Save” button.

11.	Click here.
<br>![](/exercises/ex2/images/2-11.png)

## Exercise 2.12 Sub Exercise 2 Description

The Health Monitoring data collection will be activated with the endpoint creation. 
Currently, the status is collected by an hourly background job. So it will take up to 1 hour until the status for Health Monitoring under “Capabilities” changes.
The monitoring data is collected right away, however. 

12.	Click here.
<br>![](/exercises/ex2/images/2-12.png)

## Summary

You've now successfully connected SAP HANA Cloud to SAP Cloud ALM

Continue to - [Exercise 3 - Excercise 3 ](../ex3/README.md)
