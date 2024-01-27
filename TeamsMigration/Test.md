# Microsoft Teams Classic to Modern Rollout Agenda

# Table of Contents
1. [Summary](#summary)
2. [Introduction - Microsoft Teams Classic Client End of Availability](#introduction---microsoft-teams-classic-client-end-of-availability)
3. [Pre-Migration Phase](#pre-migration-phase)
4. [Migration Phase](#migration-phase)
5. [System Administrators](#system-administrators)
6. [Client Management Team](#client-management-team)
7. [M365 Services Team](#m365-services-team)
8. [Help Desk](#help-desk)
9. [End Users](#end-users)
10. [Closing Session](#closing-session)

## Summary: [Microsoft Teams Classic Client End of Availability](https://learn.microsoft.com/en-us/microsoftteams/teams-classic-client-end-of-availability)
Microsoft Teams Classic Client is approaching product end of life. 

Endpoint devices which have not upgraded from the Microsoft Teams Classic Client to the new modern Teams client, will be required to do so prior to March 31st, 2024. Clients not in compliance will experience a forced update through Microsoft on March 31st, 2024.
The intent of this meeting is to inform all parties of our intent to transition endpoint devices from Microsoft Teams Classic Build to Microsoft Teams Modern Build prior to March 31st, 2024, and of any other work which may need to be completed by RCIT groups.

Using the table of contents above, we have attempted to narrow the scope of several actionable items to specific groups for ease of consumption. Our current Pre-Migration and Migartion Phase timeline dates are subject to change based on the outcome of this meeting.

## Timeline: Expected deployment dates and dates of importance
  
### Pre-Migration Phase
### Assessment and Inventory (Week 1: January 29th through February 2nd)
- Evaluate Customization Requirements: Identify any specific configurations, requirements, or customizations needed in the new Teams version.
- Announce Migration Plan: Inform RCIT staff about the migration timeline and what to expect.
- Teams Warning Banner: Starting on February 1, 2024, any classic Teams users who haven’t updated to new Teams will begin seeing an informational banner to remind them about the timeline for the auto update. This banner will appear in the main Teams client window at the top of the page (underneath the main bar). Note: This notification is enforced and displayed by Microsoft. It can be dismissed, but it cannot be disabled. This will also prompt any time the Teams client is initially run.

### User Communication and Training (Week 2: February 5th through February 9th)

- Schedule Training Sessions: Organize training for the new Microsoft Teams features.

## Migration Phase
### Initial Setup and Pilot Testing (Week 3: February 5th through February 9th)
- Set up Intune for Teams Deployment: Configure Microsoft Intune for opt-in deployment of new Teams version.
- Conduct Pilot Migration: Migrate a small, controlled group using Intune and gather feedback.
- Adjust Migration Strategy: Make necessary adjustments based on pilot feedback.

### Optional Migration (Week 4-7: February 12th through March 8th)
- Intune: Deploy "Opt-In" New Teams Version: Use Microsoft Intune to deploy the new version of Teams to all users.
- Notification: Notification sent to BRMs and Agencies informing them of the required change and cut-off dates.

### Forced Migration (Week 8: March 11th, 2024)
- Intune: Deploy Mandatory installation of New Teams Version to all users.
- Teams Admin: Enforce usage of new Teams via admin center.

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
