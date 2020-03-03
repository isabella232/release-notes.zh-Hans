---
title: Adobe Experience Cloud 发行说明
description: Experience Cloud 发行说明模板
doc-type: release notes
last-update: February 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 9ed727b23cbc90965f44c4bb914728bbc2394d6b

---


# Adobe Experience cloud发行说明- 2020年3月

Adobe Experience Cloud 的新增功能和修复。

>[!NOTE]
>若要通过电子邮件接收有关即将发行的版本的通知，请订阅 [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html)。对于在版本发行之后发布的新信息，将使用发布日期进行标记。

**发行日期：2020 年 3 月**

（具体产品的发布日期可能有所不同）

* [Adobe 系统状态](#status)
* [Experience Cloud 界面和核心服务](#ecloud)（更新日期：**2020 年 2 月 26 日**）
* [Experience Platform](#platform)
* [Mobile Services 和 Mobile SDK](#mobile)
* [!DNL Analytics](#analytics)（更新日期：2020 年 2 月 21 日）
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html)（链接到解决方案帮助）
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html)（链接到解决方案帮助）
* [!DNL Advertising Cloud](#adcloud)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)

在找帮助主页吗？请参阅 [Adobe Experience Cloud 文档](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html)。

## Adobe 系统状态 {#status}

[!UICONTROL Adobe 系统状态]提供关于 Adobe 云产品与服务中断和维护事件的详细信息、状态更新以及电子邮件通知。请访问 [status.adobe.com](https://status.adobe.com/) 查看。

**新增功能**

* 使用 Adobe ID，可以根据您的产品、所在的地区、事件和语言首选项订阅事件通知。配置订阅首选项的用户，在打开、更新或关闭相关的产品事故和维护事件时会收到通知。要开始使用，请访问 [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit)。

**当前可用的新增功能和增强功能**

| 功能 | 描述 |
| -----------| ---------- |
| 更快地了解产品事件 | <ul><li>我们将在进行服务维护前 30 天通知您。此功能可提供更多的前置时间来评估对业务运营的潜在影响，使您能够在必要时实施缓解计划。</li><li>高级通知可在 Web/移动设备/平板电脑界面上获取，也可通过电子邮件通知获取。</li></ul> |
| 根据首选语言个性化您的体验 | <ul><li>为电子邮件通知选择首选语言。现在提供十九种语言的自助订阅功能。</li></ul> |
| 改进了订阅和通知用户体验 | <ul><li>只需单击一次，即可为要订阅的所有产品指定区域和事件首选项。</li><li>当&#x200B;_潜在_&#x200B;问题提升为&#x200B;_次要_&#x200B;或&#x200B;_主要_&#x200B;问题时，收到通知。</li><li>当任何产品或事件状态更新时，浏览器页面会自动刷新。</li></ul> |

## Experience Cloud 界面和核心服务 {#ecloud}

发布更新：**2016 年 2 月 26 日**

Experience Cloud 界面中的新增功能和修复，包括管理和核心服务（客户属性、受众、触发器、Cookie 等）。

| 功能 | 描述 |
| -----------| ---------- |
| 管理工具 - 查看用户详细信息 | 管理员可以在新的“管理工具”中查看所有 Experience Cloud 用户的可排序、可过滤列表及其详细信息。用户详细信息包括用户的产品访问、角色和上次访问信息。有关详细信息，请参阅 [Experience Cloud 管理工具](https://docs.adobe.com/content/help/en/core-services/interface/manage-users-and-products/admin-tool-experience-cloud.html)。 |

### 统一的产品域

Adobe 将更新域和界面标题，以统一并改进您在所有 Experience Cloud 应用程序中的体验。这些增强功能旨在以细微而重要的方式简化您的体验。这些增强不会更改您当前的工作流程。

更新包括：

* 新解决方案 URL：`experience.adobe.com/<application name>`：
   * 所有产品最终都将采用此 URL 模式。寻找即将在本月内生效的新 URL。
   * 浏览器支持：支持的浏览器包括 [!DNL Microsoft Edge]、[!DNL Google Chrome]、[!DNL Firefox]、[!DNL Safari] 和 [!DNL Opera]（最新版本）。**注意：**&#x200B;尽管 Experience Cloud 界面支持这些浏览器，但单个解决方案可能不会支持每个浏览器。（例如，[Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) 不支持 [!DNL Opera]，[Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html) 不支持 [!DNL Safari]。）
   * （仅限 [!DNL Safari]）域更改可能导致 [!DNL Safari] 中出现 Cookie 问题。取消选中 [!DNL Safari] 隐私首选项中的&#x200B;_阻止跨站跟踪_，将支持跨域的 Cookie（以及所有跨站点体验），并允许 Experience Cloud 在这个新的域上正常运行。
* 更轻松地在组织之间切换，或切换到其他应用程序。
* 改进了产品帮助：[!UICONTROL Experience League] 已集成到产品中，以便帮助搜索还包括来自社区论坛及视频内容的答案。此更改会简化对更多内容的访问，并有助于您充分利用 Experience Cloud。此外，单击&#x200B;**[!UICONTROL 帮助]** > **[!UICONTROL 反馈]**，可报告问题或与 Adobe 分享您的想法。
* 改进了通知：现在，[!UICONTROL 通知]下拉菜单有两个选项卡，一个用于您自己的产品通知，一个用于全球产品通知。

**注意：**[!UICONTROL 信息源]页面将在 2020 年 1 月被弃用。请查看产品内的弃用通知。

有关产品文档，请参阅 [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html)。

## Experience Platform {#platform}

Experience Platform、Experience Platform Launch、Identity Service 和安全公告的发行说明。

* [Experience Platform 发行说明](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [安全公告与建议](https://helpx.adobe.com/security.html)（所有 Adobe 产品）

### Experience Platform Launch {#launch}

有关发行说明和产品文档，请参阅 [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html)。

## Mobile Services 和 Mobile SDK {#mobile}

移动内容。

## [!DNL Analytics] {#analytics}

Adobe Analytics 中的新增功能和修复：

* [Adobe Analytics 中的新增功能、增强功能和修复](#aa-features)
* [Analytics 管理员的重要注意事项](#aa-notices)
* [AppMeasurement](#appm) (2020 年 2 月 21 日更新)

有关产品文档，请参阅 [Adobe Analytics 帮助主页](https://docs.adobe.com/content/help/en/analytics/landing/home.html)。

### Adobe Analytics 中的新增功能、增强功能和修复 {#aa-features}

* **Analysis Workspace中的多个报表包**:您现在可以将多个报表包中的数据并入一个Analysis Workspace项目中，以并排查看。 从2020年3月12日开始，该功能将在几周内向所有客户推出。 [了解更多...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)
* **Experience Cloud受众优化**:利用此功能，您可以在8小时内（而不是之前的48小时处理时间）将区段发布到Experience Cloud。 [了解更多...](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segmentation-workflow/seg-publish.html)

#### 修复

* 修复了Reports &amp; Analytics中阻止客户下载。xls报表的问题。（AN-206541、AN-204008）
* 新Shell的推出修复了与切换Experience cloud组织相关的几个客户问题。（AN-200844、AN-186920）

### [!DNL Analytics] 管理员的重要注意事项 {#aa-notices}

| 注意 | 添加或更新日期 | 描述 |
| -----------| ---------- | ---------- |
| “转换级别”设置的EOL | 2020 年 3 月 3 日 | 2020年3月12 [日，将从UI中删除“管理工具](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/general-acct-settings-admin.html) ”>“报表包”>“常规帐户设置”中的“无效转换级别”设置。 |
| 仪表板存档的EOL | 2020 年 3 月 3 日 | 自2020年3月12日起，“报告与分析”中“管理仪表板”下的“查看存档”设置将不再可用。 |
| 新的 Adobe Analytics 域 | 2019 年 12 月 18 日 | 自 2020 年 1 月 16 日起，Adobe Analytics 将开始转移到新域 - `https://experience.adobe.com/analytics.`<br>**注意：**这项更改适用于使用 Adobe ID 或 Enterprise ID 访问 Analytics 的所有用户。<ul><li>域更改可能会导致在 Safari 中加载 Analytics 时出现 Cookie 问题。取消选中 Safari 隐私首选项中的&#x200B;_阻止跨站跟踪_，将支持跨域的 Cookie（以及所有跨站点体验），并允许 Analytics 在这个新的 Adobe Experience Cloud 域上运行。您可以使用其他浏览器而不会出现任何问题，因为该更改仅影响 Safari 用户。</li><li>[在特定情况下](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html)，域更改可能会导致某些客户的 [!UICONTROL Activity Map] 停止工作。</li></ul> |
| 生命周期结束 - Analytics 旧版 API | 2020 年 1 月 9 日 | 2020 年 11 月，以下 Analytics 旧版 API 服务将停止使用并关闭。当前使用这些服务构建的集成将会停止工作。 <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>旧版 OAuth 身份验证（OAuth 和 JWT）</li></ul>我们提供了[旧版 API EOL 常见问题解答](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)，以帮助回答您的问题并提供有关如何继续的指导。使用这些服务的 API 集成可以迁移到 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 或 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。旧版 OAuth 帐户可迁移到 [Adobe IO](https://console.adobe.io/home?mv=email) Analytics 集成帐户，该帐户可用于访问 1.4 Analytics API 和 2.0 Analytics API。 |
| **[!UICONTROL 查看存档]**&#x200B;选项生命周期终止 | 2019 年 10 月 30 日 | 2020 年 1 月，将终止使用功能板管理器（**[!UICONTROL 组件 > 功能板]**）中的&#x200B;**[!UICONTROL 查看存档]**&#x200B;选项。 |
| **[!UICONTROL 强制 IP 登录限制]**&#x200B;选项生命周期终止 | 2019 年 10 月 30 日 | 2020 年 1 月，将终止使用&#x200B;**[!UICONTROL 管理 > 公司设置 > 安全]**&#x200B;菜单下的 IP 登录白名单（**[!UICONTROL 强制 IP 登录限制]**）功能。 |
| 停止支持 TLS 1.1 | 2019 年 10 月 3 日 | 我们一直不懈努力，致力于维持最高安全标准并提升客户数据安全。为此，Adobe Analytics 对 TLS 1.1 的支持将持续到 2020 年 3 月 31 日，在这之后将不再支持 TLS 1.1。 |
| 圣何塞 FTP 中转站停止为伦敦和新加坡提供支持 | 2020 年 7 月 | 对于位于伦敦和新加坡的客户，我们将不再提供伦敦或新加坡与圣何塞数据中心 [ftp.omniture.com](ftp://ftp.omniture.com/) 之间的数据中转支持。<br/><ul><li>伦敦客户，请使用 [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>新加坡客户，请使用 [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| 面向 Analytics 用户的 `createDate` 字段即将发生变化 | 2019 年 8 月 30 日 | 在 2019 年 10 月或 11 月，Analytics 用户的 `createDate` 字段已由美国太平洋时间更新为包含时区信息且格式正确的日期和时间值。(AN-183468) |

### [!DNL AppMeasurement] {#appm}

请参阅 [AppMeasurement for Javascript 发行说明](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html)。版本 2.19.0 于 2020 年 2 月 21 日发布。

## Audience Manager {#aam}

添加至 Audience Manager 的修复和功能。

### Audience Manager 中的新增功能、增强功能和修复 {#aam-features}

| 功能 | 描述 |
|----|----|
|  |  |
|  |  |

### 修复和改进 {#aam-fixes-and-improvements}

针对AAM的修复。

## Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新增功能、修复和更新。Adobe 建议那些采用内部部署的客户部署最新的修补程序，以便确保获得更高的稳定性、安全性和性能。

### 其他资源

* [AEM 作为云服务](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 学习和支持主页](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 学习和支持主页](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 学习和支持主页](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 学习和支持主页](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager 用户指南](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [更早版本的 AEM 文档](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic 帮助主页](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Dynamic Media 发行说明](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre 发行说明](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign 提供了一种直观、自动的方式，以通过在线和离线营销渠道来交付一对一的消息。您现在可以利用根据客户习惯和喜好所决定的体验，来预测客户的需求。

### 其他资源

* Adobe Campaign Standard：[文档](https://helpx.adobe.com/support/campaign/standard.html) - [发行说明](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [操作方法视频](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [发行计划](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic：[文档](https://helpx.adobe.com/support/campaign/classic.html) - [发行说明](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [操作方法视频](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Adobe Campaign 控制面板：[文档](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [发行说明](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

更新日期：2020 年 2 月 10 日（适用于 2 月 8 日版）

## [!DNL Magento] {#magento}

有关 Magento 的发行说明，请参阅：

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] 是一个完整的解决方案，面向希望通过参与复杂购买历程的每个阶段来转变客户体验的潜在客户管理人员和 B2B 营销人员。

### 核心 Marketo Engage 更新

发行日期：2020 年 2 月 21 日

* **Microsoft Dynamics _在 Microsoft 中更改所有者_流程操作**：直接从 Marketo Engage 中更改潜在客户或联系所有者
* **对 API 调用的增强：**
   * 用户管理 API
   * 自定义对象架构 API
   * 登陆页面重定向规则 API
* **表单描述符缓存：**&#x200B;对登陆页面和表单的改进。

有关更多信息，请参阅 [!DNL Marketo] [2020 年 2 月版](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720)发行说明

### 即将推出的功能

本季度将发布以下功能：

| 功能 | 描述 |
|------|---------|
| [!DNL Bizible] | <ul><li>新的基于帐户的分段</li><li>保存特定于功能板的过滤器</li><li>将 Bizible 功能板导出为 PDF</li></ul> |
| Sales Connect | 撰写窗口和命令中心更新/增强功能 |

### 公告

**Marketo Engage 成功中心：**&#x200B;于 2020 年 2 月推出。成功中心是一个产品内帮助中心，允许您搜索产品文档和社区、启动操作指南、访问采用内容等。注意：此功能将作为测试版在澳新银行推出，并将在本季度晚些时候推出到北美洲。

### 弃用

* **Asset API“_method”参数：** 2020 年 9 月之后，Asset API 端点将不再接受“_method”在 POST 正文中传递查询参数以绕过 URI 长度限制。
* **弃用 Internet Explorer 支持：**&#x200B;从 2020 年 7 月 31 日发行的 7 月版本开始，Internet Explorer 将不再支持 Marketo Engage 用户界面。

有关累积和历史发行说明，请参阅 [Marketo 发行说明](https://docs.marketo.com/x/CgA6Ag)。