---
title: Adobe Experience Cloud 发行说明
description: Experience Cloud 发行说明模板
doc-type: release notes
last-update: February 2020
author: mfrei
translation-type: tm+mt
source-git-commit: c62d85f09ce596482a019aa5d0f1d517bf2df9fe

---


# Adobe Experience cloud发行说明- 2020年2月

Adobe Experience Cloud 的新增功能和修复。

>[!NOTE]
>若要通过电子邮件接收有关即将发行的版本的通知，请订阅 [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html)。对于在版本发行之后发布的新信息，将使用发布日期进行标记。

**发行日期：2020 年 2 月 20 日**

（具体产品发布日期可能有所不同）

最新更新：2020年2月10日

* [Adobe 系统状态](#status)
* [Experience Cloud 界面和核心服务](#ecloud)
* [Experience Platform](#platform)
* [Mobile Services 和 Mobile SDK](#mobile)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html)（链接到解决方案帮助）
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html)（链接到解决方案帮助）
* [!DNL Advertising Cloud](#adcloud)
* [!DNL Magento](#magento)

在找帮助主页吗？请参阅 [Adobe Experience Cloud 文档](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html)。

## Adobe 系统状态 {#status}

[!UICONTROL Adobe 系统状态]提供关于 Adobe 云产品与服务中断和维护事件的详细信息、状态更新以及电子邮件通知。请访问 [status.adobe.com](https://status.adobe.com/) 查看。

**新增功能**

* 使用Adobe ID，您可以根据产品、区域、活动和语言首选项订阅活动通知。 配置订阅首选项的用户在打开、更新或关闭相关产品事件和维护事件后会立即收到通知。 要开始使用，请访问 [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit)。

**当前可用的新增功能和增强功能**

| 功能 | 描述 |
| -----------| ---------- |
| 更快地了解产品活动 | <ul><li>提前30天通知您即将进行的服务维护。 此功能可提供更多的提前期来评估对业务运营的潜在影响，使您能够在必要时实施缓解计划。</li><li>高级通知可在Web/移动／平板电脑界面上使用，也可通过电子邮件通知提供。</li></ul> |
| 根据首选语言个性化您的体验 | <ul><li>为电子邮件通知选择首选语言。 现在提供十九种语言的自助订阅功能。</li></ul> |
| 改进的订阅和通知用户体验 | <ul><li>只需单击一下鼠标，即可为要订阅的所有产品指定区域和活动首选项。</li><li>当潜在问 _题提升为_ “次要”或“主要” _问题时_ ，获 _得通知_ 。</li><li>当任何产品或活动状态更新时，浏览器页面会自动刷新。</li></ul> |

## Experience Cloud 界面和核心服务 {#ecloud}

Experience Cloud 界面中的新增功能和修复，包括管理和核心服务（客户属性、受众、触发器、Cookie 等）。

**修复**

* **** 客户属性：客户属性UI现在可显示在Target中同步的其他配置文件状态。 (MCUI-10231)
* **** 触发器核心服务：由于使用不当，在创建放弃类型触发器时的倾向得分“30天后返回的可能性”已被删除。 (MCUI-10056)

### 统一的产品域

Adobe 将更新域和界面标题，以统一并改进您在所有 Experience Cloud 应用程序中的体验。这些增强功能旨在以细微而重要的方式简化您的体验。这些增强不会更改您当前的工作流程。

更新包括：

* 新解决方案 URL：`experience.adobe.com/<application name>`：
   * 所有产品最终都将采用此 URL 模式。寻找即将在本月内生效的新 URL。
   * Browser support: Supported browsers include [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari], and [!DNL Opera] (latest versions). **注意：**&#x200B;尽管 Experience Cloud 界面支持这些浏览器，但单个解决方案可能不会支持每个浏览器。（例如，[Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) 不支持 [!DNL Opera]，[Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html) 不支持 [!DNL Safari]。）
   * （仅限 [!DNL Safari]）域更改可能导致 [!DNL Safari] 中出现 Cookie 问题。Deselecting _Prevent cross-site tracking_ in the [!DNL Safari] Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Experience Cloud to function on this new domain.
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

**2020 年 2 月 4 日：版本 4.19.0**

此版本中进行了以下更新：

**** 生命周期：添加了新的API, `pauseCollectingLifecycleData`以减轻从某些旧iOS设备报告的异常会话长度数据。

## [!DNL Analytics] {#analytics}

Adobe Analytics 中的新增功能和修复：

* [Adobe Analytics 中的新增功能、增强功能和修复](#aa-features)（更新日期：2020 年 1 月 21 日）
* [Analytics 管理员的重要注意事项](#aa-notices)
* [AppMeasurement](#appm)

有关产品文档，请参阅 [Adobe Analytics 帮助主页](https://docs.adobe.com/content/help/en/analytics/landing/home.html)。

### Adobe Analytics 中的新增功能、增强功能和修复 {#aa-features}

<!--* **Support for multiple report suites in Workspace:** You can now bring in data from multiple report suites into a single project to view side by side. Beginning on Feb 20, 2020, the feature will roll out to all customers over the course of several weeks. [Learn more...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)-->
* **适用**&#x200B;于使用跨设备分析的组织的新工作区模板：此模板显示CDA在拼接访问方面的有效性，并指导您了解CDA独有的维度和指标。 必须使用CDA的报表包。 有关 [详细信息，请参阅设置跨设备分析](https://docs.adobe.com/content/help/en/analytics/components/cda/cda-setup.html) 。
* **** 使用专用图的组织的CDA拼接延迟缩短为一天：专用图形功能已得到增强，可减少图形生成延迟，从每周批处理流程缩短为每日更新的图形，使CDA客户能够访问更多最新的标识图形和链接。
* **** 实验室（技术预览）:这一新增的Analytics功能可让您在生产中测试新功能原型，并向Adobe提供有价值的反馈。 [了解更多...](https://docs.adobe.com/content/help/en/analytics/analyze/tech-previews/overview.html)
* **工作区中的新热键：**<ul><li>折叠／展开所有面板： `alt + m`</li><li>折叠／展开活动面板： `alt + ctrl + m`</li><li>搜索左边栏： `ctrl + /`</li><li>移到下一个面板： `alt + Right Key`</li><li>移到上一个面板： `alt + Left Key`</li></ul>[了解更多...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/fa-shortcut-keys.html)
* **其他工作区增强功能：**<ul><li>将面板或可视化放入 [!UICONTROL Workspace后]，左边栏会自动切换到组件，以实现更无缝的工作流程。</li><li>现在可以对模板组件进行配置（例如，标记、标记为收藏、已批准）。</li><li>如果找不到所需内容， `+` 则筛选的度量和区段列表会提供添加新组件的按钮。</li></ul>
* Workspace调 **试器已添加到“帮助”菜单** ，为您提供了一种更无缝的方式，以启用它来调试Workspace请求。 [了解更多...](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/reporting-tricks.md)
* **** 基于Chromium的Microsoft edge浏览器：此版本包括为报告目的识别基于Chromium的Microsoft edge浏览器（版本79及更高版本）的更改。

#### 修复

* 修复了区段UI中表示营销渠道维 [!UICONTROL 度与数据仓库兼容的问题]，实际上，这些维度并不兼容。 将来，区段生 [!UICONTROL 成器不再将这些维显示为与数据仓] 库兼容  。 (AN-202297)
* 修复了在Analytics中更新的已发布区段名称在24小时内未在Audience manager中更新的问题。 (AN-199974)

### [!DNL Analytics] 管理员的重要注意事项 {#aa-notices}

| 注意 | 添加或更新日期 | 描述 |
| -----------| ---------- | ---------- |
| 新的 Adobe Analytics 域 | 2019 年 12 月 18 日 | `https://experience.adobe.com/analytics.`<br>** 2020年1月16日，Adobe Analytics开始转向新域——注 **意：此更改适用于使用其Adobe ID或Enterprise ID访问Analytics的所有用户。<ul><li>域更改可能会导致在 Safari 中加载 Analytics 时出现 Cookie 问题。Deselecting _Prevent cross-site tracking_ in the Safari Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Analytics to function on this new Adobe Experience Cloud domain. 您可以使用其他浏览器而不会出现任何问题，因为该更改仅影响 Safari 用户。</li><li>[在特定情况下](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html)，域更改可能会导致某些客户的 [!UICONTROL Activity Map] 停止工作。</li></ul> |
| 生命周期结束 - Analytics 旧版 API | 2020 年 1 月 9 日 | 2020 年 11 月，以下 Analytics 旧版 API 服务将停止使用并关闭。当前使用这些服务构建的集成将会停止工作。 <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>旧版 OAuth 身份验证（OAuth 和 JWT）</li></ul>我们提供了[旧版 API EOL 常见问题解答](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)，以帮助回答您的问题并提供有关如何继续的指导。使用这些服务的 API 集成可以迁移到 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 或 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。旧版 OAuth 帐户可迁移到 [Adobe IO](https://console.adobe.io/home?mv=email) Analytics 集成帐户，该帐户可用于访问 1.4 Analytics API 和 2.0 Analytics API。 |
| **[!UICONTROL 查看存档]**&#x200B;选项生命周期终止 | 2019 年 10 月 30 日 | 2020 年 1 月，将终止使用功能板管理器（**[!UICONTROL 组件 > 功能板]**）中的&#x200B;**[!UICONTROL 查看存档]**&#x200B;选项。 |
| **[!UICONTROL 强制 IP 登录限制]**&#x200B;选项生命周期终止 | 2019 年 10 月 30 日 | 2020 年 1 月，将终止使用&#x200B;**[!UICONTROL 管理 > 公司设置 > 安全]**&#x200B;菜单下的 IP 登录白名单（**[!UICONTROL 强制 IP 登录限制]**）功能。 |
| 停止支持 TLS 1.1 | 2019 年 10 月 3 日 | 我们一直不懈努力，致力于维持最高安全标准并提升客户数据安全。为此，Adobe Analytics 对 TLS 1.1 的支持将持续到 2020 年 3 月 31 日，在这之后将不再支持 TLS 1.1。 |
| 圣何塞 FTP 中转站停止为伦敦和新加坡提供支持 | 2020 年 7 月 | 对于位于伦敦和新加坡的客户，我们将不再提供伦敦或新加坡与圣何塞数据中心 [ftp.omniture.com](ftp://ftp.omniture.com/) 之间的数据中转支持。<br/><ul><li>伦敦客户，请使用 [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>新加坡客户，请使用 [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| 面向 Analytics 用户的 `createDate` 字段即将发生变化 | 2019 年 8 月 30 日 | 在 2019 年 10 月或 11 月，Analytics 用户的 `createDate` 字段已由美国太平洋时间更新为包含时区信息且格式正确的日期和时间值。(AN-183468) |

### [!DNL AppMeasurement] {#appm}

请参阅 [AppMeasurement for Javascript 发行说明](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html)。版本2.18.0已于2020年2月13日发布。

## Audience Manager {#aam}

添加至 Audience Manager 的修复和功能。

### Audience Manager 中的新增功能、增强功能和修复 {#aam-features}

| 功能 | 描述 |
|----|----|
| [活动使用情况报告](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/administration/activity-usage-reporting.html) | “活 [!UICONTROL 动使用情况报告] ”可帮助您查看和跟踪Audience Manager实例的活动使用情况，让您清楚地了解活动使用情况与合同约定的相比情况。 |

### 修复和改进 {#aam-fixes-and-improvements}

* 修复了导致目标创建流程中断“集成帐户”选择的UI的错误(AAM-52414)。
* 修复了在“算法模型”创建流程中导航时导致UI中断的错误(AAM-37942)。
* 修复了使用Adobe Experience Platform集成(AAM-52814)的客户在保存新目标或现有目标的数据导出控件时，导致“数据导出”选择不保存的错误。
* 修复了导致第三方特征推荐对名称中包含管道字符(`|`)的特征(AAM-51635)工作不正确的错误。
* 整个UI中的多种辅助功能改进。

## Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新增功能、修复和更新。Adobe 建议那些采用内部部署的客户部署最新的修补程序，以便确保获得更高的稳定性、安全性和性能。

### 产品版本

* **Cloud Manager 2020.2.0**

   Cloud Manager 2020.2.0简化了Adobe Experience manager作为云服务的沙箱的自助管理。

   请参阅[发行说明](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)。

### 自助服务

* **AEM云服务教程**

   快速开始使用 [AEM云服务形式的教程](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/overview.html)。

* **AEM Forms交互式通信Batch API**

   AEM Forms交互式通信的批处理API使客户能够自动或按需生成多个交互式通信。 客户可以同时生成打印和Web输出。
请参 [阅使用Batch API生成多个交互式通信](https://docs.adobe.com/content/help/en/experience-manager-65/forms/interactive-communications/generate-multiple-interactive-communication-using-batch-api.html)。

* **JEE上的AEM Forms支持的平台**

   添加了对Oracle 19c的JEE客户AEM Forms支持。
请参 [阅JEE上的AEM Forms支持的平台](https://docs.adobe.com/content/help/en/experience-manager-65/forms/install-aem-forms/jee-installation/aem-forms-jee-supported-platforms.html)。

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

### Campaign Classic 19.2.3

有关修复和改进，请参阅 [Adobe Campaign Classic 发行说明](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html)。

### Campaign Standard 20.1

有关修复和改进，请参阅 [Adobe Campaign Standard 发行说明](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html)。

### 其他资源

* Adobe Campaign Standard：[文档](https://helpx.adobe.com/support/campaign/standard.html) - [发行说明](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [操作方法视频](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [发行计划](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic：[文档](https://helpx.adobe.com/support/campaign/classic.html) - [发行说明](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [操作方法视频](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Adobe Campaign 控制面板：[文档](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [发行说明](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

更新日期：2020 年 2 月 10 日（适用于 2 月 8 日版）

| 视图 | 功能 |
|------|---------|
| 项目组合 | 如今，您可以在项目组合中添加 Yahoo! Japan Display Network (YDN) 促销活动，以优化促销活动预算和广告组级别的竞价。相同的竞价适用于广告组中的所有广告。YDN 促销活动的数据包含在项目组合的各个模拟中。 |
| 搜索 > 批量工作表 | 现在，您可以通过批量工作表来创建、编辑和删除 Google 响应式搜索广告 (RSA)。Previously, support was available only through the standard campaign management interface at **[!UICONTROL Search]** > **[!UICONTROL Campaigns]** |
| 搜索 > 促销活动、报表 | The Google Ads prominence metrics `Impr. (Abs. Top) %` and `Impr. (Top) %` are now available in all basic reports and entity-level campaign management views except for those for shopping product groups, in the [!UICONTROL Campaign Daily Impression Share] and [!UICONTROL Keyword Daily Impression Share] reports, and in the labels and constraints views. |

## [!DNL Magento] {#magento}

有关Magento发行说明，请参阅：

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)
