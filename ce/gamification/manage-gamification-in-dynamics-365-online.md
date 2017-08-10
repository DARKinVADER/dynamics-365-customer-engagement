﻿---
title: "Install and configure Dynamics 365 – Gamification in Dynamics 365 (online) | Microsoft Docs"
description: "Learn how to install the Gamification solution in Dynamics 365 (online) and  its associated web portal and security roles."
ms.custom: ""
ms.date: 05/31/2017
ms.reviewer: ""
ms.service: gamification
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: get-started-article
applies_to: Dynamics 365 (online)
ms.assetid: cff88aa0-01a3-4cd7-adcf-8d4b8dec9f20
caps.latest.revision: 36
author: "m-hartmann"
ms.author: mhart
manager: sakudes
---
# Install and configure the Gamification solution in Dynamics 365 (online)

The [!INCLUDE[pn_gamification](includes/pn-gamification-md.md)] capabilities are a solution for [!INCLUDE[pn_CRM_Online](includes/pn-crm-online-md.md)], hosted on [!INCLUDE[pn_microsoft_appsource](includes/pn-microsoft-appsource-md.md)], that you need to install before you can start using the capabilities to manage your [!INCLUDE[pn_gamification_shortest](includes/pn-gamification-shortest-md.md)] games, KPIs, and players.  
  
## Prerequisites  
  
-   [!INCLUDE[pn_gamification_shortest](includes/pn-gamification-shortest-md.md)] requires at least [!INCLUDE[pn_crm_8_1_0_online](includes/pn-crm-8-1-0-online-md.md)].  
  
-   Users must have a [!INCLUDE[pn_CRM_Online](includes/pn-crm-online-md.md)] license assigned to access the [!INCLUDE[pn_gamification_shortest](includes/pn-gamification-shortest-md.md)] service.  
  
-   Users must have an up-to-date browser. [!INCLUDE[proc_more_information](includes/proc-more-information-md.md)] [Browser requirements to enable a seamless experience in Gamification](browser-system-requirements.md)  
  
## Install Dynamics 365 - Gamification  

 [!INCLUDE[pn_gamification_shortest](includes/pn-gamification-shortest-md.md)] capabilities in [!INCLUDE[pn_crm_shortest](includes/pn-crm-shortest-md.md)] are a solution for [!INCLUDE[pn_CRM_Online](includes/pn-crm-online-md.md)] that you install from [Microsoft AppSource](https://go.microsoft.com/fwlink/p/?linkid=830919).  
  
> [!NOTE]
> [!INCLUDE[pn_gamification_shortest](includes/pn-gamification-shortest-md.md)] can be used exclusively on a single [!INCLUDE[pn_CRM_Online](includes/pn-crm-online-md.md)] instance per [!INCLUDE[pn_CRM_Online](includes/pn-crm-online-md.md)] tenant. [!INCLUDE[proc_more_information](includes/proc-more-information-md.md)] [TechNet: Multiple online instances or tenants](https://technet.microsoft.com/library/dn722373.aspx)  
  
### Install the solution from AppSource  
  
1.  In [AppSource](https://go.microsoft.com/fwlink/p/?linkid=830919), select **[!INCLUDE[pn_gamification](includes/pn-gamification-md.md)]**.  
  
2.  Sign in to your [!INCLUDE[pn_CRM_Online](includes/pn-crm-online-md.md)] system admin account, if you aren't already signed in.  
  
3.  Click **Get** to start installing the solution.  
  
4.  Review and accept the disclaimer and the terms to add [!INCLUDE[pn_gamification_shortest](includes/pn-gamification-shortest-md.md)] to [!INCLUDE[pn_CRM_Online](includes/pn-crm-online-md.md)].  
  
 It may take a few minutes for the solution to be installed in [!INCLUDE[pn_CRM_Online](includes/pn-crm-online-md.md)].  
  
## KPI manager security role  

 When you install [!INCLUDE[pn_gamification_shortest](includes/pn-gamification-shortest-md.md)], a security role called **KPI manager** is created. System admins can assign this security role to [!INCLUDE[pn_CRM_Online](includes/pn-crm-online-md.md)] users they want to enable to create KPIs for [!INCLUDE[pn_gamification_shortest](includes/pn-gamification-shortest-md.md)] in [!INCLUDE[pn_CRM_Online](includes/pn-crm-online-md.md)].  
  
 To learn more about security roles and privileges, see [TechNet: Security roles and privileges](https://technet.microsoft.com/library/dn531090.aspx)  
  
 For more information about KPIs in [!INCLUDE[pn_CRM_Online](includes/pn-crm-online-md.md)], see [Configure KPIs for Gamification in Dynamics 365 (online)](configure-kpis.md).  
  
## Activate Gamification in Dynamics 365  

 Before you can sync [!INCLUDE[pn_gamification](includes/pn-gamification-md.md)] with [!INCLUDE[pn_CRM_Online](includes/pn-crm-online-md.md)], a user who has a global admin role in [!INCLUDE[pn_Office_365](includes/pn-office-365-md.md)] and a system administrator security role in [!INCLUDE[pn_CRM_Online](includes/pn-crm-online-md.md)] needs to complete the setup process to obtain the security key.  
  
### Activate the Gamification portal for your organization  
  
1.  In [!INCLUDE[pn_microsoftcrm](includes/pn-microsoftcrm-md.md)], go to **Settings** > **Solutions** and then double-click the **Gamification** solution.  
  
2.  Click **Start Activation** and sign in with your admin credentials.  
  
3.  Accept the disclaimer and provide a **Name** and a **Location** for your instance of the Gamification portal.  
  
4.  Click **Register** to start the activation and obtain the security key.  
  
5.  Copy the **Security Key** and paste it in the input box.  
  
6.  Click **Authorize** to complete the connection between [!INCLUDE[pn_CRM_Online](includes/pn-crm-online-md.md)] and [!INCLUDE[pn_gamification](includes/pn-gamification-md.md)].  
  
 You'll receive an email with additional details, and then you can access your organization's [!INCLUDE[pn_gamification_shortest](includes/pn-gamification-shortest-md.md)] instance.  
  
 Additionally, the system creates a set of default KPIs in [!INCLUDE[pn_CRM_Online](includes/pn-crm-online-md.md)] so you can quickly get started with the first game in [!INCLUDE[pn_gamification_portal](includes/pn-gamification-portal.md)]. [!INCLUDE[proc_more_information](includes/proc-more-information-md.md)] [Configure KPIs for Gamification in Dynamics 365 (online)](configure-kpis.md)  
  
 To sign in as the first Commissioner, go to [Gamification sign-in](https://go.microsoft.com/fwlink/p/?linkid=830344).  
  
## Update the Gamification solution

 A system administrator can update the solution.
  
 If an update is available, a notification is displayed on the **Gamification Settings** page.   
  
1.  Sign in to [https://portal.office.com](https://portal.office.com) with your Global administrator or [!INCLUDE[pn_microsoftcrm](includes/pn-microsoftcrm-md.md)] System Administrator credentials.  
  
2.  Click **Admin centers** > **Dynamics 365**.  
  
3.  Click the **Instances** tab, and then select the instance the solution is connected to.  
  
4.  Click **Solutions**.  
  
5.  Select the solution you want to update and click **Upgrade**.  
  
6.  In [!INCLUDE[pn_microsoftcrm](includes/pn-microsoftcrm-md.md)], go to **Gamification** > **Gamification Settings** and click **Configure App** to update all dependencies to the latest version.  
  
    > [!IMPORTANT]
    >  This step is required to keep all synchronization processes running.  
  
 The system will apply all necessary changes and validate the update to ensure data keeps flowing smoothly.  
  
> [!NOTE]
>  You need to repeat the above steps whenever you update the solution.  
  
## View active games in Dynamics 365  

 You can view information about the active games in [!INCLUDE[pn_CRM_shortest](includes/pn-crm-shortest-md.md)].  
  
### View active games  
  
1.  In [!INCLUDE[pn_CRM_Online](includes/pn-crm-online-md.md)], go to **Gamification** > **Games**.  
  
2.  In the list of games, click the game name you want to see details about.  
  
3.  In the **Game Details** section, you'll find basic information about the game, like the name and the start and end date.  
  
     In the **Setup KPIs** section, you can see the KPIs and their setup status in the selected game. For more information about KPIs in [!INCLUDE[pn_CRM_Online](includes/pn-crm-online-md.md)], see [Configure KPIs for Gamification in Dynamics 365 (online)](configure-kpis.md).  
  
## Privacy notice  

[!INCLUDE[cc_privacy_gamification_solution](includes/cc-privacy-gamification-solution-md.md)]  
  
### See also  

 [Overview for commissioners and game managers in Gamification](for-commissioners-game-managers.md)   
 [Configure KPIs for Gamification in Dynamics 365 (online)](configure-kpis.md)   
 [Import players and fans from Dynamics 365 (online) and manage their security roles](manage-players-fans.md)   
 [Set up and run games in Gamification](run-games.md)   
 [Privacy information and license terms for Gamification](legal-information.md)