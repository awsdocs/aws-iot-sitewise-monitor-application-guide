# Getting started with AWS IoT SiteWise Monitor<a name="getting-started"></a>

You use AWS IoT SiteWise Monitor portals to view, analyze, and share access to your operational data\. Each AWS IoT SiteWise Monitor portal is a managed web application that is created from the AWS IoT SiteWise console\. When you are given access to a portal, you receive an email that contains a link to the portal\. The topics in this section help you understand what you can do in the portal\.

Depending on your role, you might have different tasks to perform\.


**Roles and tasks for AWS IoT SiteWise Monitor**  

| Role | Tasks | Getting started | 
| --- | --- | --- | 
| Portal administrator |  [\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/iot-sitewise/latest/appguide/getting-started.html)  | [Getting started as an AWS IoT SiteWise Monitor portal administrator](portal-admin-getting-started.md) | 
| Project owner |  [\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/iot-sitewise/latest/appguide/getting-started.html)  | [Getting started as an AWS IoT SiteWise Monitor project owner](project-owner-getting-started.md) | 
| Project viewer |  [\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/iot-sitewise/latest/appguide/getting-started.html)  | [Getting started as an AWS IoT SiteWise Monitor project viewer](project-viewer-getting-started.md) | 

If you don't have an AWS IoT SiteWise Monitor portal, contact your AWS administrator\. For information about how to create a portal, see [Getting started with AWS IoT SiteWise Monitor](https://docs.aws.amazon.com/iot-sitewise/latest/userguide/monitor-getting-started) in the *AWS IoT SiteWise User Guide*\.

## Signing in to an AWS IoT SiteWise Monitor portal<a name="portal-login"></a>

Whether you're a portal administrator, a project owner, or a viewer, your first step is to sign in to the AWS IoT SiteWise Monitor application with your enterprise email and password, or AWS Identity and Access Management \(IAM\) credentials\. SiteWise Monitor validates your credentials with AWS Single Sign\-On or  IAM to ensure that only authorized users can access your company assets\.

You can choose one of the following to sign in to the AWS IoT SiteWise Monitor portal:
+ Use your AWS SSO identity\.

  1. Open the email that contains the link to the portal and open the web portal\.

  1. In the dialog box, for **Email**, enter your enterprise email address\.

  1. For **Password**, enter your enterprise password\.

  1. Choose **Sign in**\.

     AWS SSO validates your credentials and, if valid, opens the portal so that you can perform the tasks allowed for your role\.
+ Use your IAM identity\.
  + 

**If you use an IAM user, do the following:**

    1. Open the link to the portal and open the web portal\. You might have received an email that contains the link\.

    1. In the dialog box, enter your **IAM user name**\.

    1. For **Password**, enter your IAM password\.

    1. Choose **Sign in**\.

       IAM validates your credentials and, if valid, opens the portal so that you can perform the tasks allowed for your role\.
  + 

**If you want to assume an IAM role, do the following:**

    1. Sign in to the IAM with federation\.

    1. Assume an IAM role\.

    1. Open the the link to the portal and open the web portal\. You might have received an email that contains the link\.

       If the IAM role was added to the portal, you automatically sign in to the portal\. You can now perform the tasks allowed for your role\.

## Navigation in the AWS IoT SiteWise Monitor portal<a name="portal-navigation"></a>

You use the left navigation bar to navigate within the AWS IoT SiteWise Monitor portal\.

![\[The navigation bar in the AWS IoT SiteWise Monitor portal.\]](http://docs.aws.amazon.com/iot-sitewise/latest/appguide/images/portal-navigation-bar-console.png)

When the bar is collapsed, only the icons are shown\.

**Note**  
Only portal administrators see all four icons\.