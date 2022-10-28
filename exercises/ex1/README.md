# Exercise 1 - Preparations in SAP HANA Cloud

To successfully connect SAP HANA Cloud to SAP Cloud ALM, you need a service key in the SAP HANA Cloud instance so that SAP Cloud ALM can authenticate against the SAP HANA Cloud database. 

## Exercise 1.1 Log in

Your trainer will provide:  
- BTP Cockpit URL: https://cockpit.us10.hana.ondemand.com/cockpit/?idp=tdcteched1.accounts.ondemand.com#/globalaccount/fb7dfea1-5d8c-431d-bd16-1ebbe842f62f
- User: xp261-XXX@tdcteched.com (Please replace _**XXX**_ with your group number) 
- Password: coming soon

Please connect via browser to the provided URL and use your credentials to log in.  
<br>![](/exercises/ex1/images/Ex1_1.png)


## Exercise 1.2 Navigate to Instances and Subscriptions

After login, you see the SAP BTP Cockpit global account overview.  
Select the subaccount XP261-XXX  
Make sure to replace _**XXX**_ with your group number!  
<br>![](/exercises/ex1/images/Ex1_2a.png)

Please navigate to the service instance by clicking on the _number_ under "Service Instances".  
<br>![](/exercises/ex1/images/Ex1_2b.png)

## Exercise 1.3 Select Instance

Find the instance xp261-XXX-hana.  
Make sure not to click on the links, as this will navigate elsewhere.  
Make sure to replace _**XXX**_ with your group number!  
<br>![](/exercises/ex1/images/Ex1_3a.png)

## Exercise 1.4 Find Service Key

Navigate to “Service Keys” and click the “Create” button.  
<br>![](/exercises/ex1/images/Ex1_4a.png)

## Exercise 1.5 Create Service Key

Enter “xp261_XXX_key” as Service Key Name and click the “Create” button.
The creation will take a few minutes.  
Make sure to replace _**XXX**_ with your group number!  
<br>![](/exercises/ex1/images/Ex1_5a.png)

## Exercise 1.6 Download Service Key

Wait until the service key is created and available.  
After creating the Service Key, click on the three dots at the end of the row and select “Download”.  
You can also display the service key using the "View" option and leave the browser tab open. Then you can use the "Copy JSON" button to copy the service key to SAP Cloud ALM.  
<br>![](/exercises/ex1/images/Ex1_6a.png)

## Exercise 1.7 Check download location and file

Make sure that the service key file is available in your laptop’s “Download” folder.  
<br>![](/exercises/ex1/images/Ex1_7.png)


## Summary

You've now successfully downloaded the service key.

Continue to - [Exercise 2 - Connect SAP HANA Cloud to SAP Cloud ALM](../ex2/README.md)
