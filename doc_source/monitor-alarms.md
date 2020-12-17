# Monitoring with alarms<a name="monitor-alarms"></a>


|  | 
| --- |
|  The alarms feature is in preview release for SiteWise Monitor and is subject to change\. We recommend that you use this feature only with test data, and not in production environments\.  | 

Alarms alert you and your team when equipment or processes perform sub\-optimally\. Optimal performance of a machine or process means that the values for certain metrics should be within a range of high and low limits\. When these metrics are outside their operating range, equipment operators must be notified so that they can fix the issue\. Alarms help you quickly identify issues and notify operators to maximize performance of your equipment and processes\.

AWS IoT SiteWise Monitor supports two types of alarms:
+ Alarms that detect in the AWS Cloud – You can view and customize the thresholds and notification settings for these alarms\. You can also acknowledge and snooze these alarms\.
+ External alarms – These alarms detect on external equipment and then send the alarm state to the AWS Cloud\. You can't customize, acknowledge, or snooze these alarms\. These alarms don't have any information other than their state\.

Alarms have the following states:
+ **Normal** – The alarm is enabled but inactive\. The equipment or process operates as expected\.
+ **Active** – The alarm is active\. The equipment or process is outside its operating range and needs attention\.
+ **Acknowledged** – An operator acknowledged the state of the alarm\.
+ **Latched** – The alarm returned to normal but was active and no operator acknowledged it\. The equipment or process requires attention to reset the alarm to normal\.
+ **Snoozed** – The alarm is inactive because an operator snoozed the alarm\. The operator defines the duration for which the alarm snoozes\. After that duration, the alarm returns to normal state\.
+ **Disabled** – The alarm is inactive and won't detect any changes\.

You can perform the following alarm\-related tasks\.


| Task | Required role | Description | 
| --- | --- | --- | 
|  [Viewing alarm details](view-alarm-details.md)  |  Portal administrator, project owner, and project viewer  |  View details about the alarms that you can access\.  | 
|  [Responding to alarms](respond-to-alarms.md)  |  Portal administrator, project owner, project viewer  |  Acknowledge or snooze the alarms that you can access\.  | 
|  [Configuring alarms](configure-alarms.md)  |  Portal administrator, project owner  |  Customize the threshold and notification settings for the alarms that you can access\.  | 
|  [Visualizing alarms in dashboards](visualize-alarms.md)  |  Portal administrator, project owner  |  Add alarms to dashboards to visualize alarm state or alarms as thresholds in your dashboards\.  | 

**Topics**
+ [Viewing alarm details](view-alarm-details.md)
+ [Responding to alarms](respond-to-alarms.md)
+ [Configuring alarms](configure-alarms.md)
+ [Visualizing alarms in dashboards](visualize-alarms.md)