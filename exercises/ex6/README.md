# Exercise 6 - Stop SAP HANA Cloud to Trigger an Alert

To stop SAP HANA Cloud, you have to access the BTP Cockpit again. From there, you can access SAP HANA Cloud Central and stop the SAP HANA Cloud database.

## Exercise 6.1 Open BTP Cockpit

Your trainer will provide:  
- BTP Cockpit URL: https://cockpit.us10.hana.ondemand.com/cockpit/?idp=tdcteched1.accounts.ondemand.com#/globalaccount/fb7dfea1-5d8c-431d-bd16-1ebbe842f62f
- User: xp261-XXX@tdcteched.com (Please replace _**XXX**_ with your group number) 
- Password: S4PT3ch3d-22!

Please connect via browser to the provided URL and use your credentials to log in.  
<br>![](/exercises/ex6/images/Ex6_1.png)

## Exercise 6.2 Navigate to your SAP HANA Cloud

After login, you see the SAP BTP Cockpit global account overview.  
Select the subaccount XP261-XXX  
Make sure to replace _**XXX**_ with your group number!  
<br>![](/exercises/ex6/images/Ex6_2a.png)

Please navigate to Cloud Foundry → Spaces.  
<br>![](/exercises/ex6/images/Ex6_2b.png)

Click on the space XP261-XXX-DEV  
Make sure to replace _**XXX**_ with your group number!  
<br>![](/exercises/ex6/images/Ex6_3.png)

Navigate to SAP HANA Cloud  
<br>![](/exercises/ex6/images/Ex6_4.png)

## Exercise 6.3 Navigate to SAP HANA Cloud Central

Find the xp261-XXX-hana database and click on “Actions” → “Open in SAP HANA Cloud Central”.  
Make sure to replace _**XXX**_ with your group number!  
<br>![](/exercises/ex6/images/Ex6_5.png)

## Exercise 6.4 Logon to SAP HANA Cloud Central

Enter **“tdcteched1-platform”** as origin key for the identity provider.  
<br>![](/exercises/ex6/images/Ex6_6.png)

## Exercise 6.5 Stop HANA Cloud Instance

In the row for your xp261-XXX-hana click on the three dots at the end of the line and select "Stop".  
Make sure to replace _**XXX**_ with your group number!  
<br>![](/exercises/ex6/images/Ex6_7.png)

Confirm that you want to stop the SAP HANA Cloud instance.  
<br>![](/exercises/ex6/images/Ex6_8.png)

## Exercise 6.9 Refresh execution

The SAP HANA Cloud instance will be stopped. You can click the “refresh” button to see when it is fully stopped.  
Please note that it can take a few minutes until the HANA Cloud is completely stopped.  
<br>![](/exercises/ex6/images/Ex6_9.png)  
<br>![](/exercises/ex6/images/Ex6_10.png)  

## Summary

You've now stoped the SAP HANA Cloud service

Continue to - [Exercise 7 -	Analyze the alert and trigger the automation from the alert details ](../ex7/README.md)
