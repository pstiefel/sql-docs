---
title: "Start Report Builder | Microsoft Docs"
description: Report Builder is a stand-alone report authoring environment. The first time you start it, Microsoft Download Center prompts you to download it.

ms.date: 01/03/2020
ms.prod: reporting-services
ms.prod_service: "reporting-services-native"
ms.technology: report-builder


ms.topic: conceptual
helpviewer_keywords: 
  - "Report Builder, launching"
  - "launching Report Builder"
  - "SharePoint integration [Reporting Services], starting Report Builder"
  - "starting Report Builder"
ms.assetid: 8c8c7d2e-b315-418d-bf65-90e7685e4259
author: maggiesMSFT
ms.author: maggies
---

# Start Report Builder

[!INCLUDE[ssRBnoversion](../../includes/ssrbnoversion.md)] is a stand-alone report authoring environment. With it, you can create paginated reports and publish them to [!INCLUDE[ssRSnoversion](../../includes/ssrsnoversion-md.md)] installed in native or SharePoint integrated mode.  

> [!NOTE]
> Reporting Services integration with SharePoint is no longer available after SQL Server 2016.
  
 The first time you start [!INCLUDE[ssRBnoversion](../../includes/ssrbnoversion.md)] from the [!INCLUDE[ssRSnoversion](../../includes/ssrsnoversion-md.md)] web portal or [!INCLUDE[ssRSnoversion](../../includes/ssrsnoversion-md.md)] in SharePoint integrated mode, you're prompted to download it from the Microsoft Download Center. 
 
![Screenshot of the We're opening Report Builder message.](../../reporting-services/report-builder/media/report-builder-get-report-builder.png) 
 
 You or an administrator can also [install Report Builder on your computer from the Microsoft Download Center](https://go.microsoft.com/fwlink/?LinkID=219138). See "Install Report Builder with Systems Manager Server" in [Install Report Builder](../../reporting-services/install-windows/install-report-builder.md) for more details.
 
 [!INCLUDE[ssRBnoversion](../../includes/ssrbnoversion.md)] isn't installed when you install SQL Server Reporting Services; you need to download and install it separately.  
  
 When you start [!INCLUDE[ssRBnoversion](../../includes/ssrbnoversion.md)] from the web portal or SharePoint site, if an earlier version of [!INCLUDE[ssRBnoversion](../../includes/ssrbnoversion.md)] opens, contact your administrator, who can update the version on the web portal or SharePoint site.  
  
## To start [!INCLUDE[ssRBnoversion](../../includes/ssrbnoversion.md)] from the [!INCLUDE[ssRSnoversion](../../includes/ssrsnoversion-md.md)] web portal  
  
1.  In your Web browser, type the URL for your report server in the address bar. By default, the URL is https://\<*servername*>/reports.  
  
2.  In the top bar of the web portal, select **New** > **Paginated Report**.  
  
     ![PBI_SSMRP_NewMenu](../../reporting-services/mobile-reports/media/pbi-ssmrp-newmenu.png "PBI_SSMRP_NewMenu")  
  
     The first time, you're prompted to [install Report Builder](../../reporting-services/install-windows/install-report-builder.md). 
  
     After that first time, [!INCLUDE[ssRBnoversion](../../includes/ssrbnoversion.md)] opens, and you can create a paginated report or open a report from the report server.  
  
## To start [!INCLUDE[ssRBnoversion](../../includes/ssrbnoversion.md)] in SharePoint integrated mode  
  
1.  Navigate to the SharePoint site that contains the library you want.  
  
2.  Open the library.  
  
3.  Click **Documents**.  
  
4.  On the **New Document** menu, click **Report Builder Report**.  
  
     The first time, this launches the SQL Server [!INCLUDE[ssRBnoversion](../../includes/ssrbnoversion.md)] Wizard. See [Install Report Builder](../../reporting-services/install-windows/install-report-builder.md) for more details.  
  
     [!INCLUDE[ssRBnoversion](../../includes/ssrbnoversion.md)] opens, and you can create a paginated report or open a report on the report server.  
  
     **Note** If the **New Document** menu does not list **Report Builder Report**, **Report Builder Model**, or **Report Data Source**, their content types need to be added to the SharePoint library. For more information, see [Add Reporting Services Content Types to a SharePoint Library](../../reporting-services/report-server-sharepoint/add-reporting-services-content-types-to-a-sharepoint-library.md).  

## Next steps

[Report Builder in SQL Server](../../reporting-services/report-builder/report-builder-in-sql-server-2016.md)   
[Set default options for Report Builder](../../reporting-services/report-builder/set-default-options-for-report-builder.md)  

More questions? [Try asking the Reporting Services forum](/answers/search.html?c=&f=&includeChildren=&q=ssrs+OR+reporting+services&redirect=search%2fsearch&sort=relevance&type=question+OR+idea+OR+kbentry+OR+answer+OR+topic+OR+user)