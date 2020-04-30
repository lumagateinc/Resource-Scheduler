
![Documentation Home](https://github.com/lumagateinc/scheduler/blob/master/images/header_img.png)

# Resource Scheduler<!-- omit in toc -->

Resource Scheduler for Microsoft Azure provides a quick and easy way to create group schedules to stop and start VMs on dates and times you specify.

## Table of Contents<!-- omit in toc -->

- [Install and Configure](#install-and-configure)</br>
  - [Installation](#installation)</br>
  - [Grant Permissions](#grant-permissions)</br>
  - [Connect Subscriptions](#connect-subscriptions)</br>
  - [Configure Time Zone](#configure-time-zone)</br>
- [Using Resource Scheduler](#using-resource-scheduler)</br>
  - [Managing Schedules](#managing-schedules)</br>
  - [Schedule Resources Directly](#schedule-resources-directly)</br>
  - [Schedule Resources by Tag](#schedule-resources-by-tag)</br>
- [Troubleshooting and Support](#troubleshooting-and-support)</br>
  - [View Logs](#view-logs)</br>
  - [Request Support](#request-support)</br>

## Install and Configure<!-- omit in toc -->

This section covers the initial installation and configuration of the Resource Scheduler. 

## Installation<!-- omit in toc -->

**Video demo:**
Step-by-step demo of this task [HERE](http://example.com/link "title").

[back to ToC](#table-of-contents)

## Grant Permissions<!-- omit in toc -->

The Resource Scheduler includes custom roles based on Azure role-based access control. Roles include:

- **Administrator**. Enables a user to manage schedules for resources to which they have access, as well as to schedule. Additionally, this role can 
- **Schedule Manager**. Enables a user to manage schedules for resources to which they have access, as well as to schedule.
- **Auditor**. This role has read-only access to resources, schedules, logs, and subscriptions connected to the Resource Scheduler instance.

> **IMPORTANT NOTE:** Since the **Scheduler Manager** role can schedule based on Tags, a member of this role may be able to schedule resources they cannot see. This issue also exists when using tags with script or runbook-based scheduling, because Azure does not support RBAC for tags.

To assign a Resource Scheduler role to a user or group, perform the following steps:

1. In the Azure portal or Office 365 Admin Center, select **Azure Active Directory**.
2. Then, select Enterprise Applications. From the list, find and select Resource Scheduler (shown in Figure 1 below).
3. Click **Add user > Users and Groups**. Then, select the user or group you wish to add the role. Click **Select** to save your changes.
4. Next, click **Select Role**, and choose the role you would like to assign to the selected user or group (Administrator, Auditor, or Schedule Manager). Click **Select** to save your changes.

![entapps](https://github.com/lumagateinc/scheduler/blob/master/images/ent_apps.png)

**Figure 1**. Enterprise Apps list in Azure Active Directory

**Video demo:**
Step-by-step demo of this task [HERE](http://example.com/link "title").

[back to ToC](#table-of-contents)

## Connect Subscriptions<!-- omit in toc -->

**Video demo:**
Step-by-step demo of this task [HERE](http://example.com/link "title").

[back to ToC](#table-of-contents)

## Configure Time Zone<!-- omit in toc -->

**Video demo:**
Step-by-step demo of this task [HERE](http://example.com/link "title").

[back to ToC](#table-of-contents)

## Using Resource Scheduler<!-- omit in toc -->

## Managing Schedules<!-- omit in toc -->

**Video demo:**
Step-by-step demo of this task [HERE](http://example.com/link "title").

[back to ToC](#table-of-contents)

### Schedule Resources Directly<!-- omit in toc -->

**Video demo:**
Step-by-step demo of this task [HERE](http://example.com/link "title").

[back to ToC](#table-of-contents)

### Schedule Resources by Tag<!-- omit in toc -->

**Video demo:**
Step-by-step demo of this task [HERE](http://example.com/link "title").

[back to ToC](#table-of-contents)

## Troubleshooting and Support<!-- omit in toc -->

## Viewing Resource Logs<!-- omit in toc -->

**Video demo:**
Step-by-step demo of this task [HERE](http://example.com/link "title").

[back to ToC](#table-of-contents)

## View Logs<!-- omit in toc -->

## Request Support<!-- omit in toc -->

To request support, please follow these steps

**STEP 1: Check the FAQs**

[HERE](http://example.com/link "title")gin by checking our FAQs to see if your question is answered there. If it is not, proceed to STEP 2.

**STEP 2: Screenshot your Claims**

Visit **[https://\<tenant\>.azurewebsites.net/claims](https://\<tenant\>.azurewebsites.net/claims)** and capture a screenshot of the claims associated with your account. If you are logging a request for another user, ask them to capture this data and forward to you.

> **IMPORTANT!** [HERE](http://example.com/link "title") sure to complete this step. You will need to attach this info to your support request.

**STEP 3: Log a ticket**

To log a ticket, visit https://lumagate.us/support and click the "CONTACT US" button. Complete the form, which will log a ticket, and send you a confirmation email with case number.
