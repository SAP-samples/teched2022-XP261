# Exercise 7 - Analyze the Alert and trigger the automation from the Alert Details

After some minutes, you will receive an alert from SAP Cloud ALM Notification that the database is unavailable.   
Please note that it can take up to 5 minutes after the HANA Cloud completely stopped until the alert appears. The metrics for SAP HANA Cloud are currently only collected every 5 minutes.  
If you entered your email address you will receive an alert notification email. If you didn’t enter your email address, you could also find the alert directly in the Health Monitoring application.  
After receiving the alert, you can trigger the automation flow to restart your HANA Cloud instance.

## Exercise 7.1 Look up email notification

Check your email inbox. You will find an email from SAP Cloud ALM.  
The email contains two links:  
1)	The first link takes you to the Alert Inbox of Health Monitoring  
2)	The second link takes you to the metric details for the service in Health Monitoring  

Since you probably didn’t receive the email on your Teched Laptop, let’s return to Health Monitoring to find the alert there.  
<br>![](/exercises/ex7/images/Ex7_1.png)

## Exercise 7.2 Log on to SAP Cloud ALM

Log on to SAP Cloud ALM again.  
Your trainer will provide:  
- SAP Cloud ALM URL: https://teched22-cloudalm-002.eu10.alm.cloud.sap/launchpad#Shell-home
- User: xp261-XXX@tdcteched.com (Please replace _**XXX**_ with your group number)
- Password: Coming soon

Please connect via browser to the provided URL. Select the **httpstdcteched1.accounts.ondemand.co** Identity Provider.  
Use your credentials to log in.  
<br>![](/exercises/ex7/images/Ex7_2.png)  
<br>![](/exercises/ex7/images/Ex7_3.png)

## Exercise 7.3 Go to Health Monitoring

Open the application “SAP Cloud ALM for Operations” → “Health Monitoring”  
<br>![](/exercises/ex7/images/Ex7_4.png)

## Exercise 7.4 Access alert

In the Health Monitoring Overview screen, you will find the same services you selected the last time and your favorites.  
You can see that the XP261-XXX-HANA has a critical status.  
To access the alert, you can (1) click on the number of alerts or (2) navigate directly to the Alert Inbox.  
Make sure to replace _**XXX**_ with your group number!  
<br>![](/exercises/ex7/images/Ex7_5.png)

## Exercise 7.5 Open alert details

In the Alert Inbox, you can now find your alert.  
Click on the row of the alert to open the alert details.  
<br>![](/exercises/ex7/images/Ex7_6.png)

In the alert details, you can see how long the alert has been going on and which metrics caused the alert.  
You see that the alert is caused because the “Database Availability Check” has a red rating.  
This means the database is offline and needs to be restarted.  
<br>![](/exercises/ex7/images/Ex7_8.png)

## Exercise 7.6 Start an Operation Flow

Click on “Actions” → “Start Operation Flow” to trigger your operation flow to restart the SAP HANA Cloud instance.  
<br>![](/exercises/ex7/images/Ex7_9.png)

Filter for “xp261-XXX-hana” to find the correct operation flow to start your HANA DB.  
If you used another description for you operations flow during the registration, you have to enter this as search string.  
Click the “Start” button in the line of the operation flow.  
Make sure to replace _**XXX**_ with your group number!  
<br>![](/exercises/ex7/images/Ex7_10.png)

## Exercise 7.7 Wait for Operation Flow to finish

You can see the status of the operations flow under the tab “Operation Automation Logs”.  
You can use the “Refresh Alert Details” button to update the status.  
Please note that is can take several minutes for the operation flow to finish start HANA Cloud.  
<br>![](/exercises/ex7/images/Ex7_11.png)

Wait until your Operation Flow is successfully finished.  
<br>![](/exercises/ex7/images/Ex7_12.png)

## Exercise 7.8 Navigate back to the Health Monitoring Home Screen

Navigate back to the Health Monitoring Home screen.  
<br>![](/exercises/ex7/images/Ex7_13.png)

You can see that your HANA Cloud service is no longer in a critical state.  
Please note that it can take up to 5 minutes after the SAP HANA Cloud restarted until Health Monitoring picks up the new status. The metrics for HANA Cloud are currently collected every 5 minutes.  
<br>![](/exercises/ex7/images/Ex7_14.png)

Please refresh the application if the HANA Cloud still shows a critical state.  
<br>![](/exercises/ex7/images/Ex7_15.png)

## Exercise 7.9 Alert Inbox

Navigate back to the Alert Inbox.  
<br>![](/exercises/ex7/images/Ex7_16.png)

## Exercise 7.10 Go to Alert Details

As you can see, the alert is rated green now.  
Select the alert to navigate to the alert details.  
<br>![](/exercises/ex7/images/Ex7_17.png)

## Exercise 7.11 Confirm Alert

Select “Actions” → “Confirm” to close the alert.  
<br>![](/exercises/ex7/images/Ex7_18.png)

Enter an explanation for closing the alert and click the “Save” button.  
<br>![](/exercises/ex7/images/Ex7_19.png)

## Summary

You've now analyzed the alert and triggered the automation from the Alert Details

You have completed the exercise!

You are now able to:
- Connect SAP HANA Cloud to SAP Cloud ALM
- Activate Health Monitoring for SAP HANA Cloud
- Maintain notification recipients and register operation flows
- Analyze metrics in Health Monitoring
- Trigger an operation flow from an alert
- Confirm an alert in Health Monitoring

