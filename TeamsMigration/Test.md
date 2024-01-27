# Microsoft Teams Classic to Modern Rollout Agenda

# Table of Contents
1. [Summary](#summary)
2. [Introduction - Microsoft Teams Classic Client End of Availability](#introduction---microsoft-teams-classic-client-end-of-availability)
3. [System Administrators](#system-administrators)
4. [Client Management Team](#client-management-team)
5. [M365 Services Team](#m365-services-team)
6. [Help Desk](#help-desk)
7. [End Users](#end-users)
8. [Closing Session](#closing-session)

## Summary
Microsoft Teams Classic Client is quickly approaching product end of life. 

All clients who have not upgraded to the modern build, will need to do so prior to March 31st, 2024. Clients not in compliance will experience a forced update through Microsoft.
The intent of this meeting is to inform all parties of our intent to transition endpoint devices from Microsoft Teams Classic Build to Microsoft Teams Modern Build prior to March 31st, 2024.

## Introduction - [Microsoft Teams Classic Client End of Availability](https://learn.microsoft.com/en-us/microsoftteams/teams-classic-client-end-of-availability)
- **Overview of Rollout Plan**
  - Timeline: Expected deployment dates and dates of importance
  - Explanation of support roles and responsibilities within RCIT groups
  - Explanation of the required change, with information regarding the benefits and shortcomings of the new modern Teams client
    - Starting on February 1, 2024, any classic Teams users who haven’t updated to new Teams will begin seeing an informational banner to remind them about the timeline for the auto update. This banner will appear in the main Teams client window at the top of the page (underneath the main bar).
    - On March 31, 2024, a new Teams client will be rolled out for users who are still on classic Teams, installing the new Teams client for them and uninstalling the classic Teams client. After this time, classic Teams will be unavailable.
    - After March 31, 2024, if you’re already running on new Teams, there will be no change in behavior. Your Teams will continue working as expected. Users on classic Teams will be automatically updated to the new Teams client. Users won’t be able to switch back to classic Teams after this date, because classic Teams won’t be functional. Microsoft will attempt to uninstall classic Teams.

## System Administrators
- **Preparation and Planning**
  - Review Modern Teams client compatibility items for endpoint devices
  - Identify potential challenges and solutions
  - All RCIT staff will be included in pilot phase
- **Responsibilities**
  - Deploy Modern Microsoft Teams installer via Intune (Client Management Team)
  - Update Intune/Configuration Manager deployment items to deploy Modern Teams during device provisioning (Client Management Team)
  - Managing and enabling compliance settings via Teams administrative portal (M365 Services Team)
- **Training and Documentation**
  - Providing vendor documentation on product changes (M365 Services Team)
  - Provide Teams client deployment troubleshooting information related to Intune/Configuration Manager deployments (Client Management Team)
 
## Client Management Team
- **Support Readiness**
  - Ensure endpoint devices are compatible with Modern Teams client
  - Coordinate software deployments to device collections
  - Update any required device provisioning processes (Imaging, etc.) 
- **Responsibilities**
  - Communicate Intune deployment information to end users receiving update via Intune instead of in-place upgrade.
  - Provide support for device-related installation inquiries during the transition
  - Provide updated guidance to Help Desk and Field Services on any changes to endpoint installation process for Microsoft Teams (Configuration Manager/Intune)
  - Collaborate with M365 Services team
 
## M365 Services Team
- **Support Readiness**
  - Provide communication on rollout phases
  - Provide technical information for assigned tasks to other RCIT Teams
  - Providing support for device and policy related inquiries during the transition
- **Responsibilities**
  - Implement Teams Administrative settings to allow for in-place upgrades
  - Enforce Modern Teams compliance through Teams administrative policy

## Help Desk
- **Support Readiness**
  - Familiarizing with common issues and resolutions in Modern Teams Client
  - Review changes to user experience 
- **Responsibilities**
  - Providing support to end users
  - Escalating complex issues to Client Management for Teams client installation issues
  - Escalating complex issues to M365 Services for Teams client policy issues
  - Documentation of related issues within Service Now.

## End Users
- **Support Readiness**
  - Provide information for Rivco staff to assist with understanding the reason for the transition
- **Responsibilities**
  - Updating personal devices as required (Selection of the "Try the new Teams" option)
  - Participate in training (if needed) for Modern Teams functionality changes

## Closing Session
- **Review and Recap**
  - Recap current rollout process and update channels
  - Outline post-rollout support structure
  - Schedule follow-up meeting to monitor progress and address ongoing needs
