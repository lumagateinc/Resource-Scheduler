# Resource Scheduler <!-- omit in toc -->

![header](../images/_img.png)

Resource Scheduler for Microsoft Azure provides a quick and easy way to create group schedules to stop and start VMs on dates and times you specify.

# Table of Contents <!-- omit in toc -->

- [Install and Configure](#install-and-configure)</br>
  - [Installation](#installation)</br>
  - [Grant Permissions](#grant-permissions)</br>
  - [Connect Subscriptions](#connect-subscriptions)</br>
  - [Configure Time Zone](#configure-time-zone)<br/>
- [Using Resource Scheduler](#using-resource-scheduler)</br>
  - [Managing Schedules](#managing-schedules)
  - [Schedule Resources Directly](#schedule-resources-directly)</br>
  - [Schedule Resources by Tag](#schedule-resources-by-tag)</br>
- [Troubleshooting and Support](#troubleshooting-and-support)</br>
  - [View Logs](#view-logs)</br>
  - [Request Support](#request-support)</br>

# Install and Configure <!-- omit in toc -->
This section covers the initial installation and configuration of the Resource Scheduler. 

## Installation <!-- omit in toc -->

**Video demo:**
Step-by-step demo of this task.
[![alt text](http://example.com/exampl.png)](http://example.com/link "title")

[back to ToC](#table-of-contents)

## Grant Permissions <!-- omit in toc -->

The Resource Scheduler includes custom roles based on Azure role-based access control. Roles include:

- **Administrator**. sdfsdf
- **Schedule Manager**. Enables a user to manage schedules for resources to which they have access, as well as to schedule.
- **Auditor**. This role has read-only access to resources, schedules, logs, and subscriptions connected to the Resource Scheduler instance.

> **IMPORTANT NOTE:** Since the **Scheduler Manager** role can schedule based on Tags, a member of this role may be able to schedule. This issue also exists when using tags with script or runbook-based scheduling, because Azure does not support RBAC for tags.

**Video demo:**
Step-by-step demo of this task.
[![alt text](http://example.com/exampl.png)](http://example.com/link "title")

[back to ToC](#table-of-contents)

## Connect Subscriptions <!-- omit in toc -->

**Video demo:**
Step-by-step demo of this task.
[![alt text](http://example.com/exampl.png)](http://example.com/link "title")

[back to ToC](#table-of-contents)

## Configure Time Zone <!-- omit in toc -->

**Video demo:**
Step-by-step demo of this task.
[![alt text](http://example.com/exampl.png)](http://example.com/link "title")

[back to ToC](#table-of-contents)

# Using Resource Scheduler <!-- omit in toc -->

## Managing Schedules <!-- omit in toc -->

**Video demo:**
Step-by-step demo of this task.
[![alt text](http://example.com/exampl.png)](http://example.com/link "title")

[back to ToC](#table-of-contents)

### Schedule Resources Directly <!-- omit in toc -->

**Video demo:**
Step-by-step demo of this task.
[![alt text](http://example.com/exampl.png)](http://example.com/link "title")

[back to ToC](#table-of-contents)

### Schedule Resources by Tag <!-- omit in toc -->

**Video demo:**
Step-by-step demo of this task.
[![alt text](http://example.com/exampl.png)](http://example.com/link "title")

[back to ToC](#table-of-contents)

# Troubleshooting and Support <!-- omit in toc -->

## Viewing Resource Logs <!-- omit in toc -->

**Video demo:**
Step-by-step demo of this task.
[![alt text](http://example.com/exampl.png)](http://example.com/link "title")

[back to ToC](#table-of-contents)

## View Logs <!-- omit in toc -->

## Request Support <!-- omit in toc -->

To request support, please follow these steps

**STEP 1: Check the FAQs**

Begin by checking our FAQs to see if your question is answered there. If it is not, proceed to STEP 2.

**STEP 2: Screenshot your Claims**

Visit **https://\<tenant>.azurewebsites.net/claims** and capture a screenshot of the claims associated with your account. If you are logging a request for another user, ask them to capture this data and forward to you.

> **IMPORTANT!**Besure to complete this step. You will need to attach this info to your support request.

**STEP 3: Log a ticket**
If you 