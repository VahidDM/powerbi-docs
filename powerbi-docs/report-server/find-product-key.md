---
title: How to find your report server product key
description: Learn how you can find your Power BI Report Server product key to install your server in a production environment.
author: maggiesMSFT
ms.author: maggies
ms.reviewer: ''
ms.service: powerbi
ms.subservice: powerbi-report-server
ms.topic: how-to
ms.custom: video-6CQnf-NGtpU
ms.date: 09/19/2023
---
# How to find your report server product key
Learn how you can find your Power BI Report Server product key to install your server in a production environment.

> [!NOTE]  
> This video might use earlier versions of Power BI Report Server or the Power BI service.

> [!VIDEO https://www.youtube.com/embed/6CQnf-NGtpU?rel=0&amp;showinfo=0]

You downloaded [Power BI Report Server](get-started.md), and you have a SQL Server Enterprise Software Assurance agreement. Or, you purchased [Power BI Premium](../enterprise/service-premium-what-is.md). You want to install the server in a production environment, but you need a product key in order to do that. Where is the product key? The product key will be in one of two places depending on what you purchased. 

> [!NOTE]
> If you have a subscription license for SQL Server Enterprise Edition with Software Assurance, it also grants use rights to Power BI Report Server. Submit a support request through the software portal you normally use to get assistance for this scenario.
>
> You can't use a developer product key in a production environment.
>
> For more details, see the section "Use of Power BI Report Server – SQL Server Enterprise Edition" in [SQL Server licensing](https://www.microsoft.com/licensing/terms/productoffering/SQLServer/EAEAS).

## Purchased Power BI Premium
If you have purchased Power BI Premium, within the **Capacity settings** tab of the Power BI admin portal, you'll have access to your Power BI Report Server product key. This will only be available for Global Admins or users assigned the Fabric administrator role.

![Power BI Report Server key within Premium settings](media/find-product-key/pbirs-product-key.png)

Selecting **Power BI Report Server key** will display a dialog contain your product key. You can copy it and use it with the installation.

![Power BI Report Server product key](media/find-product-key/pbirs-product-key-dialog.png)

## Purchased Software Assurance agreement
If you have a SQL Server Enterprise SA agreement, you can get your product key from the [Volume Licensing Service Center](https://www.microsoft.com/Licensing/servicecenter/). Look under the latest service pack, for the latest version of SQL Server. If you don't see it there, look under the RTM release of the latest SQL Server version.

> [!NOTE]
> You need to look under the download section. Not the keys section.

![Screenshot of SQL Server Enterprise showing Downloads and Keys tab with Power B I Report integration information.](media/find-product-key/vlsc-download.png "Volume Licensing Service Center")

### Volume licensing in the Microsoft 365 Admin Center

If your volume licensing has moved to the Microsoft 365 Admin Center, you can find your product key by choosing a SQL Server version and then looking under the **Downloads** section.

1. Select the key next to the version of the software that you have.

    :::image type="content" source="media/find-product-key/m365-choose-version.png" alt-text="Screenshot of the key next to the version of the software that you have.":::

1. Under Downloads, select the **View additional instructions** link.

    :::image type="content" source="media/find-product-key/m365-downloads.png" alt-text="Screenshot of Additional instructions dialog.":::

1. Find the Power BI Report Server Software Assurance information displayed with your license key.

    :::image type="content" source="media/find-product-key/m365-additional-instructions.png" alt-text="Screenshot of View additional instructions.":::

## Next steps

[Install Power BI Report Server](install-report-server.md)  
[Install Power BI Desktop for Power BI Report Server](install-powerbi-desktop.md)  
[Download Report Builder](https://www.microsoft.com/download/details.aspx?id=53613)  
[Download SQL Server Data Tools (SSDT)](/sql/ssdt/download-sql-server-data-tools-ssdt)

More questions? [Try asking the Power BI Community](https://community.powerbi.com/)
