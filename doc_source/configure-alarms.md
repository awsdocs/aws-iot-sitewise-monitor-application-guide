# Configuring alarms<a name="configure-alarms"></a>

On the **Assets** page, project owners can configure each alarm to set it up for their equipment and processes\. You can update the alarm's threshold value and notification settings\.

**Notes**  
You can only configure alarms that your team sets up to detect in the AWS Cloud\. You can't configure external alarms\.
You can only configure alarm properties that your team sets up for you to customize\. For example, your AWS administrator might define a threshold or notification recipient as a static value that you can't change\.

**To configure an alarm**

1. In the navigation bar, choose the **Assets** icon\.  
![\[The "Assets" icon in the navigation bar.\]](http://docs.aws.amazon.com/iot-sitewise/latest/appguide/images/portal-navigation-asset-library-console.png)

1. <a name="asset-library-choose-project"></a>\(Optional\) Choose a project in the projects drop\-down list to show only assets from a specific project\.  
![\[The "Assets" page, with the projects drop-down list called out.\]](http://docs.aws.amazon.com/iot-sitewise/latest/appguide/images/asset-library-choose-project-console.png)

1. Choose an asset in the **Assets** hierarchy\.
**Tip**  
Choose the arrow next to an asset to view all children of that asset\.

1. Choose the **Alarms** tab for the asset\.

1. Select the alarm to configure\.

1. Choose **Configure**\.

1. On the **Configure alarm** page, do any of the following:

   1. Edit the threshold value for the alarm\. You can preview the threshold on the recent data for the property that the alarm monitors\.  
![\[The "Configure alarm" page with the alarm threshold highlighted.\]](http://docs.aws.amazon.com/iot-sitewise/latest/appguide/images/alarms-configure-threshold-console.png)

   1. Choose a new **Notification recipient** for the alarm notification\. You can choose an AWS Single Sign\-On \(AWS SSO\) user in your organization\.

   1. Change the message **Protocol** for the alarm notification\.

   1. Change the **Custom message** to include in the notification\. The notification message includes this message and information about the alarm state change\.

1. Choose **Save**\.