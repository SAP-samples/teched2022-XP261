# Exercise 5 - Find SAP HANA Cloud in Health Monitoring and set up an alert

Now we will find SAP HANA Cloud in Health Monitoring and navigate to the metric details and metric history. Then we will set up an alert. When this alert is triggered, an email will be sent to your registered email address.

## Exercise 5.1 Go back to Launchpad

Navigate back to the SAP Cloud ALM Launchpad.  
<br>![](/exercises/ex5/images/Ex5_1.png)

## Exercise 5.2 Open Health Monitoring

Open the application “SAP Cloud ALM for Operations” → “Health Monitoring”  
<br>![](/exercises/ex5/images/Ex5_2.png)

## Exercise 5.3 Open Scope Selection

In the Health Monitoring start screen, you will see all services that are configured.  
Click the “Scope Selection” button to select only _your_ HANA Cloud.  
<br>![](/exercises/ex5/images/Ex5_3.png)

## Exercise 5.4 Select your HANA Cloud

Select the HANA Cloud with the name XP261-**XXX**-HANA and press the “Apply” button  
Make sure to replace _**XXX**_ with your group number!  
<br>![](/exercises/ex5/images/Ex5_4.png)

Now you will see only your HANA Cloud.  
<br>![](/exercises/ex5/images/Ex5_5.png)

## Exercise 5.5 Navigate to HANA Cloud monitoring details

Click on “SAP HANA Cloud” to navigate to the details for the service.  
<br>![](/exercises/ex5/images/Ex5_6.png)

Click on the row with your HANA Cloud to navigate to the metric details.  
<br>![](/exercises/ex5/images/Ex5_7.png)

In this screen, you can see all metrics that are collected for SAP HANA Cloud.  
<br>![](/exercises/ex5/images/Ex5_8.png)

## Exercise 5.6 Add your HANA Cloud as Favorite

Click the “Favorites” button to add this SAP HANA Cloud service to your favorites.  
<br>![](/exercises/ex5/images/Ex5_9.png)

## Exercise 5.7 Navigate to Metric Reporting

Select the metric “Ping Time”  
<br>![](/exercises/ex5/images/Ex5_10.png)

In the right-hand screen area, you see all HANA service instances for which this metric was collected.  
Click on the “History” button to open the metric reporting.  
<br>![](/exercises/ex5/images/Ex5_11.png)

The default resolution for the metric reporting is 15 minutes.  
The metrics for SAP HANA Cloud are collected every 5 minutes. You can display all collected values by adjusting the reporting resolution.
Use the controls in the upper left area to adjust the metric history’s timeframe and resolution.  
<br>![](/exercises/ex5/images/Ex5_12.png)

Close the window by clicking on the “Close” button.  
<br>![](/exercises/ex5/images/Ex5_13.png)

## Exercise 5.8 Return to Health Monitoring Home Screen

Click the “Home” icon to return to the Health Monitoring start screen.   
<br>![](/exercises/ex5/images/Ex5_14.png)

You will now see your SAP HANA Cloud service in the “Favorites” area  
<br>![](/exercises/ex5/images/Ex5_15.png)

## Exercise 5.9 Open Health Monitoring Configuration

Click on the “Configuration” button to open the Configuration tray to set up an alert.  
<br>![](/exercises/ex5/images/Ex5_16.png)

## Exercise 5.10 Select HANA Cloud service

Open the “Services” tray  
<br>![](/exercises/ex5/images/Ex5_17.png)

Click on the name of your SAP HANA Cloud  
<br>![](/exercises/ex5/images/Ex5_18.png)

## Exercise 5.11 Set up Threshold

Here you see all metrics that are collected for this SAP HANA Cloud.  
Click on the metric “Database Availability Check”  
<br>![](/exercises/ex5/images/Ex5_19.png)

Leave the status mapping as suggested and click the “Save” button to activate the threshold.  
<br>![](/exercises/ex5/images/Ex5_20.png)

The threshold is now activated.  
Click on the tab “Events” to activate alerting.  
<br>![](/exercises/ex5/images/Ex5_21.png)

## Exercise 5.12 Set up Alert

In this screen you see all events that are available for the SAP HANA Cloud service.  
Click on “Database Accessibility” to set up an availability alert.  
<br>![](/exercises/ex5/images/Ex5_22.png)

Switch the slider button for “Create Alert” and “Send Email” to ON.  
<br>![](/exercises/ex5/images/Ex5_23.png)

Click the “+” button to add your email recipient (Optional).  
<br>![](/exercises/ex5/images/Ex5_24.png)

Select _your_ email address from the list and click the “OK” button (Optional).  
<br>![](/exercises/ex5/images/Ex5_25.png)

Click the “Save” button to save your setup.  
<br>![](/exercises/ex5/images/Ex5_26.png)

You have now set up an alert with an email recipient.  
Click the “Close” button to close the configuration.  
<br>![](/exercises/ex5/images/Ex5_27.png)

## Exercise 5.13 Close Health Monitoring Configuration

Click the configuration icon again to close the configuration panel.  
<br>![](/exercises/ex5/images/Ex5_28.png)

## Summary

You've now set up an alert in Health Monitoring

Continue to - [Exercise 6 -	Stop SAP HANA Cloud DB to trigger an alert ](../ex6/README.md)
