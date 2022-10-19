# Exercise 2 - Connect SAP HANA Cloud to SAP Cloud ALM

To monitor SAP HANA Cloud, the HANA Cloud instance needs to be connected to SAP Cloud ALM using an endpoint. Over this endpoint, the data collection of the monitoring data in SAP HANA Cloud is triggered, and the data is collected.

Endpoints are created in the Landscape Management application.

## Exercise 2.1 Sub Exercise 1 Description

Your trainer will provide:
•	SAP Cloud ALM URL
•	User email
•	Password
Please connect via browser to the provided URL. Select the httpstdcteched1.accounts.ondemand.co Identity Provider.
Use your credentials to log in. 

1. Click here.
<br>![](/exercises/ex2/images/02_01_0010.png)


## Exercise 2.2 Sub Exercise 2 Description

You can close the information banner, if there is one.

2.	Click here.
<br>![](/exercises/ex2/images/02_02_0010.png)

## Exercise 2.3 Sub Exercise 2 Description

You will now see the SAP Cloud ALM Launchpad. 
Click on “Administration” → “Landscape Management”

3.	Click here.
<br>![](/exercises/ex2/images/02_02_0010.png)

## Exercise 2.4 Sub Exercise 2 Description

The Landscape Management will open in a new tab. 
Select the entry XP261-XXX-HANA for your group number.
Make sure the replace XXX with your group number!

4.	Click here.
<br>![](/exercises/ex2/images/02_02_0010.png)

## Exercise 2.5 Sub Exercise 2 Description

Under the section “Endpoints” click the “Add” button.

5.	Click here.
<br>![](/exercises/ex2/images/02_02_0010.png)

## Exercise 2.6 Sub Exercise 2 Description

Open the drop-down box  “Use Case”and select “Health Monitoring”

6.	Click here.
<br>![](/exercises/ex2/images/02_02_0010.png)

## Exercise 2.7 Sub Exercise 2 Description

Replace the value in the field “Root URL” with: 
https://api.gateway.orchestration.hana.prod-us20.hanacloud.ondemand.com 

7.	Click here.
<br>![](/exercises/ex2/images/02_02_0010.png)

## Exercise 2.8 Sub Exercise 2 Description

Open the Service Key you downloaded earlier and copy the entire key into the clipboard (Ctrl+A followed by Ctrl+C)

8.	Click here.
<br>![](/exercises/ex2/images/02_02_0010.png)

## Exercise 2.9 Sub Exercise 2 Description

Back in the endpoint creation screen, click the “Paste Service Key” button.
Allow the text to be copied.

9.	Click here.
<br>![](/exercises/ex2/images/02_02_0010.png)

## Exercise 2.10 Sub Exercise 2 Description

Click the button “Check Connection”.
You should receive a “Success” message.

10.	Click here.
<br>![](/exercises/ex2/images/02_02_0010.png)

## Exercise 2.11 Sub Exercise 2 Description

Click the “Save” button.

11.	Click here.
<br>![](/exercises/ex2/images/02_02_0010.png)

## Exercise 2.12 Sub Exercise 2 Description

The Health Monitoring data collection will be activated with the endpoint creation. 
Currently, the status is collected by an hourly background job. So it will take up to 1 hour until the status for Health Monitoring under “Capabilities” changes.
The monitoring data is collected right away, however. 

12.	Click here.
<br>![](/exercises/ex2/images/02_02_0010.png)

## Summary

You've now ...

Continue to - [Exercise 3 - Excercise 3 ](../ex3/README.md)
