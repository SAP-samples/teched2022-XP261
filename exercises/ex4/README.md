# Exercise 4 - Register your Automation from Automation Pilot

If an alert is triggered for your SAP HANA Cloud service, you can use Automation Pilot automations to perform actions in the SAP HANA Cloud.
These automations have to be built first. For this exercise, we created an automation to restart SAP HANA Cloud if it is offline. You only have to register the existing automation to be able to use it for your SAP HANA Cloud instance.

## Exercise 4.1 Go back to Launchpad

Navigate back to the SAP Cloud ALM Launchpad  
<br>![](/exercises/ex4/images/Ex4_1.png)

## Exercise 4.2 Open Operation Automation

Open the application “SAP Cloud ALM for Operations” → “Operation Automation”  
<br>![](/exercises/ex4/images/Ex4_2.png)

## Exercise 4.3 Register Operation Flow

In the “Operation Automation” screen, click the button “Register Operation Flow” → “SAP Automation Pilot”  
<br>![](/exercises/ex4/images/Ex4_3.png)

In this step you enter the endpoint name to Automation Pilot.  
Enter the endpoint name “XP261_AUTOPILOT”.  
Then click the “Input Help” for the field “ID”.  
<br>![](/exercises/ex4/images/Ex4_4.png)

In this step you select the automation we created in Automation Pilot before the exercise.  
Enter **XP261-T000156R3:StartHanaCloudInstance:1** in the search field and press Enter.  
Select the line “StartHanaCloudInstance”  
<br>![](/exercises/ex4/images/Ex4_5.png)

Now you have to select the predefined input parameters, to make sure that the correct HANA Cloud is restarted.  
Enter **XP261-T000156R3:InputXp261HanaXXX** in the field “Input Reference”.  
Select the input for your group number **“InputXp261HanaXXX”** by clicking on the input name.  
Make sure to replace _**XXX**_ with your group number!  
<br>![](/exercises/ex4/images/Ex4_6.png)

To be able to easier find the correct automation flow later, enter “Start xp261-XXX-hana” in the description field.  
You can also enter your name or something else that will help you to find the correct operation flow later.  
Make sure to replace _**XXX**_ with your group number!  
<br>![](/exercises/ex4/images/Ex4_7.png)

Select the use case “Health Monitoring” to make sure the automation flow is available in the alerts for Health Monitoring.  
<br>![](/exercises/ex4/images/Ex4_8.png)

Click the “Ok” button.  
<br>![](/exercises/ex4/images/Ex4_9.png)

Your operation flow will be added to the list.  
<br>![](/exercises/ex4/images/Ex4_10.png)

## Summary

You've now registered your Automation from Automation Pilot

Continue to - [Exercise 5 -	Find SAP HANA Cloud in Health Monitoring and set up an alert ](../ex5/README.md)
