# Adding properties and alarms to dashboards<a name="add-assets-to-dashboards"></a>

As the project owner, you define dashboards to give your viewers a standard way to look at asset properties and alarms\. By providing a consistent view, you ensure that everyone sees the data that you want them to see, in the same manner\. You group asset properties and alarms on to dashboards in a way that makes sense for your business and viewers\.

**Note**  
Project viewers can't modify a dashboard\.

You can add asset properties to a new dashboard or an existing dashboard\.

**To add asset properties**

1. In the navigation bar, choose the **Projects** icon\.  
![\[The "Projects" icon in the navigation bar.\]](http://docs.aws.amazon.com/iot-sitewise/latest/appguide/images/portal-navigation-projects-console.png)

1. Choose one of the following options:
   + To add asset properties and alarms to an existing dashboard, choose the dashboard to update, and then choose **Edit**\.
   + To add asset properties and alarms to a new dashboard, choose **Create dashboard**\.  
![\[The "Dashboards" page with an existing dashboard and "Create dashboard" highlighted.\]](http://docs.aws.amazon.com/iot-sitewise/latest/appguide/images/project-create-or-modify-dashboard-console.png)

1. Choose the asset whose properties or alarms that you want to add to the dashboard\.

1. Choose **Properties** to view the asset's properties or **Alarms** to view the asset's alarms\. If an alarm monitors a property, you automatically add that alarm to the dashboard when you add its property\.

1. Drag a property or alarm from the asset hierarchy to the dashboard\. You can add multiple properties and alarms to one visualization\.  
![\[A dashboard with a callout highlighting an asset property that you can drag onto the dashboard.\]](http://docs.aws.amazon.com/iot-sitewise/latest/appguide/images/dashboard-add-visualization-console.png)

   The asset property appears on the dashboard with a default visualization type:<a name="default-visualization-types"></a>
   + The default visualization type for non\-string properties is the [line chart](choose-visualization-types.md#line-charts)\.
   + The default visualization type for string properties is the [KPI widget](choose-visualization-types.md#kpi-charts)\.
   + The default visualization type for alarms is the [status grid widget](choose-visualization-types.md#status-grid-chart)\.

   You can change the visualization type and customize the visualization settings\. For more information, see [Customizing visualizations](customize-visualizations.md)\.