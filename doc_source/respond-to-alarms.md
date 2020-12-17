# Responding to alarms<a name="respond-to-alarms"></a>


|  | 
| --- |
|  The alarms feature is in preview release for SiteWise Monitor and is subject to change\. We recommend that you use this feature only with test data, and not in production environments\.  | 

On the **Assets** page, you can respond to an alarm so that your team knows that you see the alarm\. When you respond to an alarm, you can leave a note with details about the alarm or the actions that you took\. If you don't acknowledge an active alarm before it becomes inactive, the alarm becomes latched\. The latched state indicates that the alarm became active and wasn't acknowledged\. You might need to check on the equipment or process and acknowledge the latched alarm\.

You can do the following to respond to an alarm:
+ Acknowledge an alarm to indicate that you are handling the issue\.
+ Snooze an alarm to disable it temporarily\.

**Topics**
+ [Acknowledging alarms](#acknowledge-alarms)
+ [Snoozing alarms](#snooze-alarms)

## Acknowledging alarms<a name="acknowledge-alarms"></a>

When an alarm is active or latched, you can acknowledge it to indicate to your team that you are handling the issue\. You can leave a note about the alarm when you acknowledge it\.

You can acknowledge alarms that have the following states:
+ **Active**
+ **Latched**

**Note**  
Your team can configure alarms that don't support the acknowledge option\. You can't acknowledge these alarms, and these alarms can't have the **Acknowledged** or **Latched** states\.

**To acknowledge an alarm**

1. In the navigation bar, choose the **Assets** icon\.  
![\[The "Assets" icon in the navigation bar.\]](http://docs.aws.amazon.com/iot-sitewise/latest/appguide/images/portal-navigation-asset-library-console.png)

1. <a name="asset-library-choose-project"></a>\(Optional\) Choose a project in the projects drop\-down list to show only assets from a specific project\.  
![\[The "Assets" page, with the projects drop-down list called out.\]](http://docs.aws.amazon.com/iot-sitewise/latest/appguide/images/asset-library-choose-project-console.png)

1. Choose an asset in the **Assets** hierarchy\.
**Tip**  
Choose the arrow next to an asset to view all children of that asset\.

1. Choose the **Alarms** tab for the asset\.

1. Select the alarm to acknowledge\.

1. Choose **Acknowledge**\.

   A modal opens where you can enter a comment\.

1. \(Optional\) Enter a **Comment** about the alarm or the action you will take to acknowledge it\.

1. Choose **Acknowledge**\.

   The alarm's state changes to **Acknowledged**\.

## Snoozing alarms<a name="snooze-alarms"></a>

You can snooze an alarm to temporarily disable it\. While the alarm is snoozed, it won't detect any changes\. You might want to do this if you're aware that an equipment or process is broken or malfunctioning, so you don't need an alarm to go off\. You can leave a note about the alarm when you snooze it\.

You can snooze alarms that have the following states:
+ **Normal**
+ **Active**
+ **Acknowledged**
+ **Latched**
+ **Snoozed**

**To snooze an alarm**

1. In the navigation bar, choose the **Assets** icon\.  
![\[The "Assets" icon in the navigation bar.\]](http://docs.aws.amazon.com/iot-sitewise/latest/appguide/images/portal-navigation-asset-library-console.png)

1. <a name="asset-library-choose-project"></a>\(Optional\) Choose a project in the projects drop\-down list to show only assets from a specific project\.  
![\[The "Assets" page, with the projects drop-down list called out.\]](http://docs.aws.amazon.com/iot-sitewise/latest/appguide/images/asset-library-choose-project-console.png)

1. Choose an asset in the **Assets** hierarchy\.
**Tip**  
Choose the arrow next to an asset to view all children of that asset\.

1. Choose the **Alarms** tab for the asset\.

1. Select the alarm to snooze\.

1. Choose **Snooze**\.

   A modal opens where you can specify the snooze duration and enter a comment\.

1. Enter the **Snooze duration** to snooze the alarm\.

1. \(Optional\) Enter a **Comment** about the alarm\.

1. Choose **Snooze**\.

   The alarm's state changes to **Snoozed**\. The alarm stays **Snoozed** for the duration that you specify\.