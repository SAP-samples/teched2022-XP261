# Exercise 4 - Register your Automation from Automation Pilot

If an alert happens for your SAP HANA Cloud service, you can use Automation Pilot automations to perform actions in the SAP HANA Cloud.
These automations have to be built first. For this exercise, we created an automation to restart SAP HANA Cloud if it is offline. You only have to register the existing automation to be able to use it for your SAP HANA Cloud instance.

## Exercise 4.1 Go back to Launchpad

Navigate back to the SAP Cloud ALM Launchpad

1.	Click here.
<br>![](/exercises/ex4/images/Ex4_1.png)


## Exercise 4.2 Open Operation Automation

Open the application “SAP Cloud ALM for Operations” → “Operation Automation”

2.	Click here.
<br>![](/exercises/ex4/images/Ex4_2.png)

## Exercise 4.3 Register Operation Flow

In the “Operation Automation” screen, click the button “Register Operation Flow” → “SAP Automation Pilot”

3.	Click here.
<br>![](/exercises/ex4/images/Ex4_3.png)

## Exercise 4.4 Enter Endpoint

In this step you enter the endpoint name to Automation Pilot.
Enter the endpoint name “XP261_AUTOPILOT”
Then click the “Input Help” for the field “ID”

4.	Click here.
<br>![](/exercises/ex4/images/Ex4_4.png)

## Exercise 4.5 Select Automation

In this step you select the automation we created in Automation Pilot before the exercise.
Enter “XP261-T000153R3:StartHanaCloudInstance:1” in the search field and press Enter.
Select the line “StartHanaCloudInstance”

5.	Click here.
<br>![](/exercises/ex4/images/Ex4_5.png)

## Exercise 4.6 Add parameters

Now you have to select the predefined input parameters, to make sure that the correct HANA Cloud is restarted.
Start typing “XP261” in the field “Input Reference”
Select the input for your group number “InputXp261HanaXXX” by clicking on the input name.
Make sure the replace XXX with your group number!

6.	Click here.
<br>![](/exercises/ex4/images/Ex4_6.png)

## Exercise 4.7 Replace group number

To be able to easier find the correct automation flow later, enter “Start xp261-XXX-hana” in the description field.
Make sure the replace XXX with your group number!

7.	Click here.
<br>![](/exercises/ex4/images/Ex4_7.png)

## Exercise 4.8 Select Health Monitoring

Select the use case “Health Monitoring” to make sure the automation flow is available in the alerts for Health Monitoring.

8.	Click here.
<br>![](/exercises/ex4/images/Ex4_8.png)

## Exercise 4.9 Confirm

Click the “Ok” button

9.	Click here.
<br>![](/exercises/ex4/images/Ex4_9.png)

## Exercise 4.10 Check operation flow

Your operation flow will be added to the list.

10.	Click here.
<br>![](/exercises/ex4/images/Ex4_10.png)


## Summary

You've now registered your Automation from Automation Pilot

Continue to - [Exercise 3 - Excercise 3 ](../ex3/README.md)
