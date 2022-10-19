# Exercise 3 - Setup Notification Management

To receive emails from SAP Cloud ALM in case of an alert, you first must register your user in Notification Management and confirm that you want to receive emails. Usually, you will receive an email when your user is added to SAP Cloud ALM, and you can verify your email address in this invitation email.
In this section, you will learn how to add an email for a user manually or add a distribution list email as a notification recipient in SAP Cloud ALM. 

Please note: Entering your email address is not mandatory to finish the exercise, but you will not receive an email alert notification from SAP Cloud ALM. We will remove all email recipients from Notification Management after this session.

## Exercise 3.1 Go back to Launchpad

Navigate back to the SAP Cloud ALM Launchpad

1.	Click here.
<br>![](/exercises/ex2/images/3-1.png)


## Exercise 3.2 Open Notification Management

Open the application “SAP Cloud ALM for Operations” → “Notification Management”

2.	Click here.
<br>![](/exercises/ex2/images/3-2.png)

## Exercise 3.3 Add new recipient

In the “Notification Management” start screen, click the “+” button to add a new recipient.

3.	Click here.
<br>![](/exercises/ex2/images/3-3.png)

## Exercise 3.4 Add email address

Enter your email address and click the “Save” button*

Please note: Your email address will be visible to the other attendees of this session

4.	Click here.
<br>![](/exercises/ex2/images/3-4.png)

## Exercise 3.5 Receive verification link

The new email address is created as “Pending”. An email is sent to this address with a verification link.

5.	Click here.
<br>![](/exercises/ex2/images/3-5.png)

## Exercise 3.6 Verify email address"

Check your email inbox and verify your email address.

6.	Click here.
<br>![](/exercises/ex2/images/3-6.png)

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
