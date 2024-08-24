---
layout: post
title: Restrict access to Copilot Studio
description: Restrict access to Copilot Studio by removing service plans and restricting self-service trials.
categories: [Identity and Access Management (IAM), Microsoft Entra ID]
tags: [copilot,m365,ai]
---

With the increase in Copilot licenses being assigned to users in your organisation, you might find that there are some eager users creating Copilot Chatbots with restricted and/or confidential information or you might just want to slow down the use of AI in while your get some policies and procedures in place.

We still want our users to be able to use Copilot in Microsoft 365 Apps such as Outlook and Teams, but we don't want the majority of users to be able to access Copilot Studio.

To do this, we can simply remove the 'XYZ' Plan on the Copilot License assigned to our users.

# Remove 'Copilot Studio' service plan from licensed users

## Group Assigned Licenses

## Direct Assigned Licenses

# Disable self-service trials

Users in your organization can try Copilot Studio for a limited time period by signing up for a trial license.

You can disable the ability for users to sign up for a trial themselves by modifying the ```AllowAdHocSubscriptions``` flag in your organization settings to block all trial licenses or just restricting trials for Copilot Studio.

## AllowAdHocSubscription

## CopilotStudioTrial

# Verify the results

## Copilot Licensed Users

## Unlicensed Users

# Reference

For more information about managing access to Copilot Studio, refer to the following docs:

- [Assign licenses and manage access to Copilot Studio](https://learn.microsoft.com/en-us/microsoft-copilot-studio/requirements-licensing?tabs=web)
- [Manage self-service purchases and trials (for admins)](https://learn.microsoft.com/en-us/microsoft-365/commerce/subscriptions/manage-self-service-purchases-admins?view=o365-worldwide)