---
title: Adobe Experience Cloud 发行说明
description: Experience Cloud 发行说明模板
doc-type: release notes
last-update: May 2020
author: mfrei
translation-type: tm+mt
source-git-commit: be2f2b5ad468ad63bfcb2fdd67d063203ac08654
workflow-type: tm+mt
source-wordcount: '5030'
ht-degree: 81%

---


# Adobe Experience Cloud 发行说明 - 2020 年 5 月

![横幅](/assets/experience-cloud-banner-3.png)

本页介绍了 [!DNL Adobe Experience Cloud] 中的新功能、修复和重要声明。解决方案发行日期可能有所不同。请经常回来检查最新更新。

>[!NOTE]
>
>若要通过电子邮件接收有关即将发行的版本的通知，请订阅 [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html)。

**发行日期：2020 年 5 月**

最新更新日期：**2020 年 6 月 4 日**

* [Adobe 系统状态](#status)
* [Experience Cloud 界面](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)（**更新日期：2020 年 6 月 4 日**）
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/zh-Hans/target/using/release-notes/target-release-notes.html)（链接到 Target 帮助页面）
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/cn/primetime/user-guide.html)（链接到 Primetime 帮助页面）

需要帮助？访问 [[!DNL Adobe Experience League]](https://experienceleague.adobe.com/#home)，查找 Adobe 策划的课程、技术文档、快速回答、社区见解以及导师指导的培训。

## ![图标](/assets/adobe.png) Adobe 系统状态 {#status}

[!UICONTROL Adobe 系统状态]提供关于 Adobe 云产品与服务中断和维护事件的详细信息、状态更新以及电子邮件通知。请访问 [status.adobe.com](https://status.adobe.com/) 查看。

发行日期：**2020 年 5 月 21 日**

**新增功能**

* 凭借您的 Adobe ID，您可以订阅粒度更细的事件通知，具体可达到产品和加载项级别。为了帮助您更快地设置订阅，现在，自助订阅过程会根据您的产品权利推荐一系列产品和服务。这样应当会减少您收到的电子邮件数量，并向收件箱中发送更多相关的通知。要开始使用，请访问 [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit)。

**当前可用的新增功能和增强功能**

| 功能 | 描述 |
| -----------| ---------- |
| 改进了订阅和通知用户体验 | <ul><li>现在，系统会根据所选产品的列表过滤 [!DNL Marketo Engage] 区域位置。</li><li>[!DNL Marketo Engage] 电子邮件通知与用户的区域、位置和环境首选项相关。</li></ul> |
| 事件订阅确认 | <ul><li>现在，在订阅正在进行的单个事件更新时，您会收到电子邮件确认。</li></ul> |
| 全局导航可用性增强功能 | <ul><li>顶级导航菜单的用户体验与 `Adobe.com` 一致。</li></ul> |

## ![图标](/assets/ec_appicon_24.png) Experience Cloud 界面 {#ecloud}

Experience Cloud 界面的常规更新。

**统一的产品域**

Adobe 一直在更新域和界面标题，以统一并改进您在所有 Experience Cloud 应用程序中的体验。这些增强功能旨在以细微而重要的方式简化您的体验。这些增强不会更改您当前的工作流程。

更新包括：

* 新应用程序URL：`experience.adobe.com/<application name>`：
   * 所有产品最终都将采用此 URL 模式。寻找即将在本月内生效的新 URL。
   * 浏览器支持：支持的浏览器包括 [!DNL Microsoft Edge]、[!DNL Google Chrome]、[!DNL Firefox]、[!DNL Safari] 和 [!DNL Opera]（最新版本）。**注意：**&#x200B;尽管 Experience Cloud 界面支持这些浏览器，但单个应用程序可能不会支持每个浏览器。（例如，[Analytics](https://docs.adobe.com/content/help/zh-Hans/analytics/admin/sys-reqs.html) 不支持 [!DNL Opera]，[Target](https://docs.adobe.com/help/zh-Hans/target/using/implement-target/before-implement/supported-browsers.html) 不支持 [!DNL Safari]。）
   * （仅限 [!DNL Safari]）域更改可能导致 [!DNL Safari] 中出现 Cookie 问题。取消选中 [!DNL Safari] 隐私首选项中的&#x200B;_阻止跨站跟踪_，将支持跨域的 Cookie（以及所有跨站点体验），并允许 Experience Cloud 在这个新的域上正常运行。
* 更轻松地在组织之间切换，或切换到其他应用程序。
* 改进了产品帮助：[!UICONTROL Experience League] 已集成到产品中，以便帮助搜索还包括来自社区论坛及视频内容的答案。此更改会简化对更多内容的访问，并有助于您充分利用 Experience Cloud。此外，单击&#x200B;**[!UICONTROL 帮助]** > **[!UICONTROL 反馈]**，可报告问题或与 Adobe 分享您的想法。

以下应用程序使用新的 experience.adobe.com 域：

| 应用程序或服务 | Domain |
| -----------| ---------- |
| Experience Cloud 主页 | `experience.adobe.com/home` |
| Adobe Target | `experience.adobe.com/target` |
| Adobe Audience Manager | `experience.adobe.com/audience-manager` |
| Adobe Launch | `experience.adobe.com/launch` |
| Adobe Experience Platform | `experience.adobe.com/platform` |
| 历程管理 | `experience.adobe.com/journeys` |
| Customer Journey Analytics | `experience.adobe.com/platform/analytics` |
| Adobe Campaign 控制面板 | `experience.adobe.com/controlpanel` |
| Cloud Manager | `experience.adobe.com/cloud-manager` |
| Places Service | `experience.adobe.com/places` |
| Software Distribution | `experience.adobe.com/downloads` |
| 管理员工具（测试版） | `experience.adobe.com/admin` |

>[!NOTE]
>
>[!UICONTROL Marketing Cloud Assets] 选择器中的旧版筛选器&#x200B;**[!UICONTROL 留言板和收藏集]**&#x200B;即将停用。

## ![图标](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

[!DNL Experience Platform,] 的发行说明，包括 [!DNL Experience Platform Launch,] [!UICONTROL Journey Orchestration]、[!UICONTROL Offers]、[!UICONTROL People]、[!UICONTROL Places]、[!UICONTROL Mobile Services] 和安全公告。

### 界面增强

更新日期：**2020 年 5 月 15 日**

[!DNL Adobe Experience Platform] 将发布对域和标题栏的更新，以改进您的体验并与其他 Experience Cloud 应用程序相结合。更新包括：

* 更轻松地在组织之间切换，或切换到其他应用程序。
* 改进了用户帮助，包括“帮助”菜单中的精选文章和与上下文相关的文档。
* 能够提供有关 Experience Platform 和文件支持票证的反馈。

有关更多信息，请参阅 [Experience Platform 发行说明](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)。

### 客户属性 - 新文档

更新日期：**2020 年 5 月 15 日**

* [客户属性对 CCPA（《加州消费者隐私法》）的支持](https://docs.adobe.com/content/help/zh-Hans/core-services/interface/customer-attributes/ccpa.html)
* [客户属性对 GDPR（《通用数据保护条例》）的支持](https://docs.adobe.com/content/help/zh-Hans/core-services/interface/customer-attributes/gdpr.html)

### Journey Orchestration {#journey}

凭借 Adobe Experience Platform，可以实时智能化预测每位客户的需求（无论其旅程通达何处），从而实现跨体验渠道大规模编排客户历程。

* [文档](https://docs.adobe.com/content/help/zh-Hans/journeys/using/journey-orchestration-home.html)
* [发行说明](https://docs.adobe.com/content/help/zh-Hans/journeys/using/release-notes/release-notes.html)
* [操作方法视频](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### 其他 Experience Platform 发行信息

* [Experience Platform Launch 发行说明](https://docs.adobe.com/content/help/zh-Hans/launch/using/intro/release-notes/current.html)。
* [Experience Platform 发行说明](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [安全公告与建议](https://helpx.adobe.com/cn/security.html)（所有 Adobe 产品）

## ![图标](/assets/analytics.png) [!DNL Analytics] {#analytics}

Updated **June, 2020**

* [Adobe Analytics 中的新增功能](#aa-features)
* [Customer Journey Analytics 的新增功能](#cust-journey)
* [Media Analytics](#media-aa) 的新增功能
* [Adobe Analytics 修复](#aa-fixes)
* [Analytics 管理员的重要注意事项](#aa-notices)
* [AppMeasurement](#appm)
* [新的 Analytics 教程](#tutorials-analytics)

### Adobe Analytics 中的新增功能 {#aa-features}

| 功能 | [正式发布](https://docs.adobe.com/content/help/zh-Hans/analytics/landing/an-releases.html) - 目标日期 | 描述 |
| -----------| ---------- |-------|
| 归因IQ: 算法归因 | 2020 年 6 月 18 日 | 分析 [!UICONTROL 工作区中] 的算法归因模型使用统计技术动态地确定所选指标的最佳信用分配。 [了解更多...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/algorithmic.html) |
| 归因IQ: 自定义回顾窗口 | 2020 年 6 月 18 日 | 您现在可以在归因IQ中配 [!UICONTROL 置任何归因模型] ，以在报告时间段前90天内包含接触点。 通常，这会通过计入上个月发生的交互，提高在报告期初发生的事件的归因准确性。 [了解更多...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/attribution.html#lookback-windows) |
| 共享Workspace项目的项目角色 | 2020 年 6 月 18 日 | 在共享Workspace项目时，您现在可以将收件人放置在三个项目角色之一，具体取决于您希望他们具有的项目体验： 编辑、重复和视图。 [了解更多信息……]((https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| 仅限视图的Workspace项目 | 2020 年 6 月 18 日 | 工作区项目只能以“Can视图”的形式共享给用户。 当视图收件人打开共享项目时，他们将获得限制性更强的项目体验，无左边栏且交互有限。 [了解更多...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/view-only-projects.html) |
| 能够共同编辑Workspace项目 | 2020 年 6 月 18 日 | 添加到“可以编辑”角色的收件人可以保存已共享给他们的项目。 这同时适用于管理员和非管理员。 [了解更多...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Workspace中更新的“空白”面板 | 2020 年 6 月 18 日 | Workspace中的空白面板现在包括面板和可视化功能，使您能更无缝地选择最适合您的分析工作流程。 |
| China RDC中提供的第一方域 | 2020 年 6 月 18 日 | 允许具有域 `.cn` 的客户请求第一方域以在中国大陆境内使用。 （购买“中国性能优化”SKU时提供的文档。） |
| Workspace 中的 Quick Insights 面板 | 2020 年 6 月 25 日 | Quick Insights 可为 Analysis Workspace 的非分析师和新用户了解如何快速轻松地回答业务问题提供指导。[了解更多...](https://docs.adobe.com/content/help/zh-Hans/analytics/analyze/analysis-workspace/panels/quickinsight.html) |
| Workspace 中的 Analytics for Target 面板 | 2020 年 6 月 25 日 | 通过 Analytics for Target (A4T) 面板，可以在 Analysis Workspace 中分析 Adobe Target 活动和体验。[了解更多...](https://docs.adobe.com/content/help/zh-Hans/analytics/analyze/analysis-workspace/panels/a4t-panel.html) |

### Customer Journey Analytics 的新增功能 {#cust-journey}

| 功能 | [正式发布](https://docs.adobe.com/content/help/zh-Hans/analytics/landing/an-releases.html) - 目标日期 | 描述 |
| -----------| ---------- |-----|
| 异常检测支持 | 2020 年 6 月 18 日 | 异常检测提供了一种统计方法来确定给定度量相对于先前数据的变化情况。 [了解更多...](https://docs.adobe.com/content/help/zh-Hans/analytics/analyze/analysis-workspace/virtual-analyst/anomaly-detection/anomaly-detection.html) |
| 共享Workspace项目的项目角色 | 2020 年 6 月 18 日 | 在共享Workspace项目时，您现在可以将收件人放置在三个项目角色之一，具体取决于您希望他们具有的项目体验： 编辑、重复和视图。 [了解更多...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| 仅限视图的Workspace项目 | 2020 年 6 月 18 日 | 工作区项目只能以“Can视图”的形式共享给用户。 当视图收件人打开共享项目时，他们将获得限制性更强的项目体验，无左边栏且交互有限。 [了解更多...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/view-only-projects.html) |
| 能够共同编辑Workspace项目 | 2020 年 6 月 18 日 | 添加到“可以编辑”角色的收件人可以保存已共享给他们的项目。 [了解更多...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |

### [!UICONTROL Media Analytics] 的新增功能 {#media-aa}

更新日期：**2020 年 5 月 29 日**

**播放器状态跟踪：**[!UICONTROL Media Analytics] 客户可以使用一组用于全屏、隐藏式字幕、静音、画中画和聚焦的标准解决方案变量在播放过程中捕获观看者交互。您还可以灵活地创建自定义播放器状态。播放器状态跟踪变量现在可以在 [!UICONTROL Analysis Workspace] 中进行报告。此功能需要以下任一项：

* Media [!DNL JavaScript] SDK 3.0 或更高版本
* 与 [!DNL Adobe Experience Platform] (AEP) SDK 一起使用时：
   * [!UICONTROL Media Analytics 扩展]（用于 Web）：[!UICONTROL Adobe Media Analytics] (3.x SDK) for Audio and Video v1.0 或更高版本
   * [!UICONTROL Media Analytics 扩展]（用于移动设备）：[!UICONTROL Adobe Media Analytics for Audio] and Video v2.0 或更高版本
* [!UICONTROL 媒体收集]

请参阅[关于播放器状态跟踪](https://docs.adobe.com/content/help/zh-Hans/media-analytics/using/player-state-tracking/player-state-overview.html)。

### Adobe Analytics Fixes {#aa-fixes}

* 修复了导致对某些报表包进行多字节搜索的区段不匹配的问题。 他们现在将匹配正确的字符串。 AN-220043
* 修复了报告和分析中的项目筛选器不起作用的问题。 AN-206132
* 修复了计划项目UI中的慢响应时间。 AN-214837
* 修复了Analytics报告API 2.0引发日期范围错误的问题。 AN-215087
* 修复了实例／访问/访客未计入“停留时间”量度的分母的情况。 当维度（如Pagename）没有值的点击在同一秒后跟时，会发生这种情况。 AN-211074
* 修复了用户无法访问与他们共享的Workspace项目的问题。 AN-217561
* 修复了密钥未被分类规则生成器分类的问题。 AN-221538
* 修复了服务器调用使用情况不报告任何使用数据的问题。 AN-210452
* 修复了已发布的Adobe Analytics细分在AAM中缺少数据的问题。 AN-220208、AN-220659
* 修复了显示数据但数据馈送日志显示“无数据仓库数据”的报告的问题。 AN-220784、AN-220858
* 修复了阻止从域启动临时分析的 `experiencecloud.com` 问题。 AN-219680、AN-221629
* 修复了使用“Ctrl（或命令）+ C”热键的问题。 AN-221101、AN-221537
* 修复了活动图启用页面的问题。 AN-222029、AN-221242
* 修复了无法在流失可视化的中间添加接触点的问题。 AN-221648

#### 其他 Adobe Analytics 修复

AN-218269; AN-218455; AN-218492; AN-219888; AN-220447; AN-220546; AN-220788; AN-220866; AN-221165; AN-221545; AN-221712; AN-221832; AN-221853; AN-222000; AN-222505; AN-222559

### [!DNL Analytics] 管理员的重要注意事项 {#aa-notices}

| 注意事项 | 添加或更新日期 | 描述 |
| -----------| ---------- | ---------- |
| 迁移到统一的产品域 | 生效日期：2020 年 5 月 28 日 | 向 Adobe Analytics 统一产品域的迁移从 2020 年 1 月开始，于 2020 年 5 月 28 日完成。While Adobe Analytics works to remove all `omniture.com` domain references from its architecture, it is important to allowlist `omniture.com` as a third-party cookie. （不久）完成整个架构迁移后，我们将通过发行说明通知您，此白名单步骤将不再需要执行。[此处](https://helpx.adobe.com/cn/analytics/kb/adobe-ip-addresses.html) 是建议的IP地址和域的完整列表，您应允许列出这些地址和域。<br>如果贵组织阻止第三方 Cookie，请联系客户关怀团队以重新获得 Adobe Analytics 访问权限。 |
如果贵组织阻止第三方 Cookie，请联系客户关怀团队以重新获得 Adobe Analytics 访问权限。|新建Adobe Analytics默认登陆页|生效日期： 2020年6月18日|2020年6月18日，Adobe Analytics的默认登陆页将从“报告”更改为“工作区”。 之前未设置自定义登陆页面的任何用户都将发生此更改。|
|第三方技术allowlist|2020年3月12日（生效日期）|Adobe Analytics已开始利用第三方技术进行功能推出管理和产品内支持。 应将以下URL添加到任何必要的网络防火墙允许列表，以确保完全功能访问：<ul><li>Gainsight：https://esp.aptrinsic.com</li><li>LaunchDarkly：https://app.launchdarkly.com</li></ul>|
|分析工作区可用性的增强冗余|2020年5月21日|为确保分析工作区的可用性，我们添加了辅助CDN(内容投放网络)，以提高冗余性。 应将以下 URL 添加到任何必要的网络防火墙白名单中：<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul>|
在2020年4月7 [!UICONTROL 日|在Workspace中] ，对“条目／退出”的计算方式进行了更改。自2020年3月20日起，在 [!UICONTROL 分析InDes中，我们更改了OrdInDesign与OrdExits]__/Exits与Reximets无交互的方式。 由于您现在可以在 _Analysis Workspace_ 中打开和关闭[!UICONTROL 无]，因此我们会在登入或退出后应用&#x200B;_无_&#x200B;值，而（对于 eVar）过去是在登入或退出前应用。例如，假定访问的第一次点击没有 eVar 值，但第二次点击有。在 [!UICONTROL Reports &amp; Analytics] 中，第一次点击将针对“登入”显示为&#x200B;_未指定_，但在 [!UICONTROL Analysis Workspace] 中，将显示第二次点击时的值。|
|EOL of **[!UICONTROL Dashboard Archive]**|March 27, 2020|The **[!UICONTROL View Archive]** setting under **[!UICONTROL Manage Dashboards]** in [!UICONTROL Reports &amp; Analytics] will no longer be available as of October, 2020.|
|寿命结束- Analytics传统API|2020年1月9日|2020年11月，以下Analytics传统API服务将终止其使用并将关闭。 当前使用这些服务构建的集成将会停止工作。 <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>旧版 OAuth 身份验证（OAuth 和 JWT）</li></ul>我们提供了[旧版 API EOL 常见问题解答](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)，以帮助回答您的问题并提供有关如何继续的指导。使用这些服务的 API 集成可以迁移到 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 或 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。旧版 OAuth 帐户可迁移到 [Adobe IO](https://console.adobe.io/home?mv=email) Analytics 集成帐户，该帐户可用于访问 1.4 Analytics API 和 2.0 Analytics API。|
|San Jose FTP代理结束于伦敦和新加坡|2020年7月|对于伦敦和新加坡的客户，我们不再支持伦敦或新加坡与圣何塞数据中心ftp.omniture.com之 [间的数据代理](ftp://ftp.omniture.com/)。<br/><ul><li>伦敦客户，请使用 [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>新加坡客户，请使用 [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul>|
临时分析的EOL|2018年8月6日|Adobe宣布计划终止临时分析。 确定终止日期后，Adobe 会立即与大家共享此信息。有关更多信息，请参阅[探索工作区](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)。|

### [!DNL AppMeasurement] {#appm}

请参阅 [AppMeasurement for Javascript 发行说明](https://docs.adobe.com/content/help/zh-Hans/analytics/implementation/appmeasurement-updates.html)。版本 2.20.0 于 2020 年 3 月 5 日发布。

### 新的 Analytics 教程 {#tutorials-analytics}

| 内容 | 描述 |
| -----------| ---------- |
| [Analysis Workspace 中的培训教程模板](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/navigating-workspace-projects/training-tutorial-template-in-analysis-workspace.html) | [!UICONTROL Analysis Workspace] 培训教程将指导您逐步了解在 [!UICONTROL Workspace] 中构建第一个项目的常用术语和步骤。 |
| [向趋势中添加前一个月和前一年的比较](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/calendar-and-date-ranges/adding-prior-month-and-year-comparisons-to-trends.html) | 了解如何在 [!UICONTROL Analysis Workspace] 中应用自定义日期范围为任何量度创建月度和年度趋势比较。 |
| [适用于 Analysis Workspace 的深色模式扩展](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/dark-mode-extension-for-analysis-workspace.html) | 启用 Dark Reader Chrome 扩展程序以使 Analysis Workspace 变为深色。 |
| [用于定义自定义调色板的颜色吸管扩展](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/color-eyedropper-extension-for-defining-custom-palettes.html) | 了解如何使用 ColorPick EyeDropper Chrome 扩展轻松地在 [!UICONTROL Workspace] 中找到自定义调色板所需的十六进制值。 |

#### Analytics 帮助资源

* [Adobe Analytics 教程](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics 产品文档](https://docs.adobe.com/content/help/zh-Hans/analytics/landing/home.html)

## ![图标](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager 中的新增功能、修复、文档和教程。

### 用户界面更新

Audience Manager 将发布对域和标题栏的更新，以改进您的体验并与其他 Experience Cloud 应用程序相结合。

* 更轻松地在组织之间切换，或切换到其他应用程序。
* 改进了用户帮助，包括“帮助”菜单中的精选文章和与上下文相关的视频。
* 能够提供有关 Experience Platform 和文件支持票证的反馈。
* 更简单的新 URL 模式。将书签更新到新 URL：`experience.adobe.com/audience-manager`。

这些更新仅适用于使用 Adobe ID 登录的用户。要切换到 Adobe ID 登录，请参阅[管理 Experience Cloud 用户和产品](https://docs.adobe.com/content/help/zh-Hans/core-services/interface/manage-users-and-products/admin-getting-started.html)。

### Adobe Audience Manager 中的新增功能和修复

| 功能 | 描述 |
| -----------| ---------- |  
| [批量管理工具 (BAAAM)](https://docs.adobe.com/content/help/zh-Hans/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html#download) | 我们上传了一个新的批量管理工具工作表，该工作表：<br><br><ul><li>允许您在特征层次结构中列出子文件夹 (AAM-51528)</li><li>在提示输入与 CRM ID（跨设备 ID）相关的特征时检索量度 (AAM-52135)</li><li>修复了韩文字符的语言编码问题 (AAM-AAM-54006)</li></ul> |

**修复**

* 修复了趋势报表对于具有大量特征的文件夹超时的问题。(AAM-54457)
* 修复了客户无法在特征创建/编辑工作流中查看[!UICONTROL 表达式生成器]的问题。(AAM-54255)
* 修复了以下问题：UI 中的错误消息显示时间较短，在客户阅读之前便会消失。例如，在尝试删除映射到目标的区段时会发生这种情况。(AAM-54031)
* 修复了以下问题：不再使用 [!UICONTROL Audience Marketplace] 的客户仍会每月收到发票电子邮件。(AAM-54602)
* 修复了以下问题：用户从 UI 的其他位置单击某些特征时，会看到断开的链接，而不是特征。(AAM-54768)
* 修复了以下问题：在编辑特征表达式模式下，按 ENTER 会刷新页面，并且特征表达式会丢失。(AAM-54210)
* 改进了整个界面的多项辅助功能。（AAM-47781、AAM-49075、AAM-49360、AAM-49361、AAM-49376、AAM-50432、AAM-52550、AAM-54660）。

### 新的 Audience Manager 教程 {#tutorials-aam}

| 内容 | 描述 |
| -----------| ---------- |  
| [了解 Audience Manager 中的基本术语和概念](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-basic-terms-and-concepts-in-audience-manager.html) | 该视频介绍了一些帮助您开始使用 Audience Manager 的基本术语和概念，包括信号、特征、区段等。 |
| [了解 Audience Manager 中的数据流](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-the-data-flow-in-audience-manager.html) | 该视频通过描述流入、经过和流出应用程序的数据，帮助您了解 Adobe Audience Manager。 |
| [Audience Manager - DMP 概述](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-overview-of-a-dmp.html) | 了解跨渠道个性化的主要挑战以及 Adobe Audience Manager 如何推动客户历程。另外，了解哪些数据类型可在 Audience Manager 中载入，并确定与 Audience Manager 集成的广告技术生态系统合作伙伴。 |
| [Audience Manager 用例](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-use-cases.html) | 在此视频中，我们确定了四个常见的 Audience Manager 用例，并介绍了与这些用例相关的最佳实践。 |
| [了解 Audience Manager 中的跨设备量度](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/profile-merge/understanding-cross-device-metrics-in-audience-manager.html) | 在本视频中，我们讨论了设备配置文件和跨设备配置文件之间的区别，并显示了 UI 中的编号与这些不同的配置文件类型匹配的位置。 |
| [了解 Audience Manager 中的预测受众](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/understanding-predictive-audiences.html) | 在此视频中，我们将讨论 Audience Manager 的预测受众，介绍其工作方式的详细信息以及相关用例。 |
| [在 Audience Manager 中配置和报告预测受众](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/configure-and-report-on-predictive-audiences.html) | 在本视频中，我们介绍了 Audience Manager 界面中的预测受众配置。我们还会看到显示模型结果的报表。 |

## ![图标](/assets/aem.png) Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新增功能、修复和更新。Adobe 建议那些采用内部部署的客户部署最新的修补程序，以便确保获得更高的稳定性、安全性和性能。

### 产品更新

* **AEM 作为云服务**

   * 资产处理方面的改进和修复。资产重新处理对话框为用户提供更多控制权，允许用户选择特定的处理配置文件，以及是否应触发后处理工作流。
   * Dynamic Media 资产摄取性能改进。

### 自助服务

* **自动化表单转化服务 - 版本 AFC-2020.03.1**

   安装最新连接器时，可以使用新选项：

   **[!UICONTROL 自动检测逻辑部分]**：可使用[!UICONTROL 自动检测逻辑部分]选项拖放页面级面板（基于页码的面板）并仅创建逻辑面板。它还会将不属于任何之前逻辑部分的字段和跨页面逻辑部分的字段合并到一个逻辑部分中。例如，如果某个逻辑部分的一部分字段位于第 1 页结尾而另一部分位于第 2 页开头，则所有此类字段会被合并到一个逻辑部分中。

* **Dynamic Media 中不支持的图像格式**

   有关 [!UICONTROL Dynamic Media] 不支持的栅格图像文件格式的子类型的信息。

   请参阅 [Dynamic Media 中不支持的栅格图像格式](https://docs.adobe.com/content/help/zh-Hans/experience-manager-65/assets/administer/assets-formats.html#unsupported-image-formats-dynamic-media)。

* **内容片段**

   有关 [AEM Assets HTTP API 中的内容片段支持](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-service/assets/admin/assets-api-content-fragments.html)、[自定义和扩展内容片段](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-customizing.html)，以及[用于配置组件以进行渲染的内容片段](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-configuring-components-rendering.html)的信息。

* **AEM Experience League 社区**

   与 [AEM Experience League 社区](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/ct-p/adobe-experience-manager-community)建立联系：咨询学习者和 AEM 专家，浏览主题，并分享您的技巧和专业知识！

* **AEM 新闻稿**

   [!UICONTROL Experience League] 撰写的 AEM 新闻稿旨在帮助您快速掌握 AEM，以便立即开始实现价值。以下是最新的新闻稿：

   * [第 30 卷](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html)：Experience Manager 现已作为云服务提供。
   * [订阅](https://adobeeventsonline.com/AEM/2017/NL/Optin/) Experience 内部新闻稿。
   * 在 Adobe Experience Manager 6.5“学习与支持”页面的 [AEM 资源](https://helpx.adobe.com/cn/support/experience-manager/6-5.html)部分中查看新闻稿存档。

### 新的 Experience Manager 教程

| 内容 | 描述 |
| -----------| ---------- |  
| [设置本地 AEM 运行时](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | Adobe Experience Manager (AEM) 可以使用 [!UICONTROL AEM 作为云服务] SDK 的[!UICONTROL 快速入门 Jar] 在本地运行。这允许开发人员在将自定义代码、配置和内容提交到源控件之前，先对它们进行部署和测试，然后将其部署到 [!UICONTROL AEM 作为云服务]环境。 |
| [AEM Assets 快速入门](https://video.tv.adobe.com/v/33624?captions=chi_hans) | 有关面向企业用户的 AEM Assets 入门的介绍性视频。 |
| [元数据文件夹架构](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-folder-schemas.html) | 元数据文件夹架构允许用户管理和查看与资产文件夹本身相关的元数据，而不是直接管理和查看资产。 |
| [标记](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/tagging.html) | 标记是用于跨资产文件夹层次结构管理资产的不可或缺工具。建立标记分类对于允许用户在 AEM 中发现和组织资产至关重要。 |
| [元数据配置文件](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-profiles.html) | 元数据配置文件允许将默认元数据自动应用到资产文件夹中的资产。这有助于减轻 AEM 用户管理元数据的负担并可提高元数据一致性。 |
| [元数据架构](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-schemas.html) | 元数据架构定义在 AEM 中公开资产元数据的界面。本视频探讨了用于应用资产的各种方法的组合。 |

### Journey Orchestration

* [AEM 作为云服务发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)
* [AEM 作为云服务文档](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-5.html)
* [AEM 6.4 学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-4.html)
* [AEM 6.3 学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-3.html)
* [AEM 6.2 学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-2.html)
* [Cloud Manager 用户指南](https://helpx.adobe.com/cn/experience-manager/cloud-manager/user-guide.html)
* [AEM Cloud Manager 发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [更早版本的 AEM 文档](https://helpx.adobe.com/cn/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic 帮助主页](https://docs.adobe.com/content/help/zh-Hans/dynamic-media-classic/using/home.html)
* [Dynamic Media 发行说明](https://marketing.adobe.com/resources/help/zh_CN/s7/release_notes/index.html)
* [Livefyre 发行说明](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## ![图标](/assets/campaign.png) [!DNL Campaign] {#ac}

Adobe Campaign 提供了一种直观、自动的方式，以通过在线和离线营销渠道来交付一对一的消息。您现在可以利用根据客户习惯和喜好所决定的体验，来预测客户的需求。

### Campaign Standard

* [Adobe Campaign Standard 20.3 版本](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/release-notes/release-notes.html)

### Campaign Classic

* [Adobe Campaign Classic 20.1.3](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html#release-20-1-3-build-9124)
* [Adobe Campaign Classic 19.1.4](https://docs.adobe.com/content/help/zh-Hans/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### Campaign 控制面板

| 功能 | 描述 |
| -----------| ---------- |  
| GPG 密钥管理 | 可在营销实例上安装和/或生成 GPG 密钥，以便加密从 Campaign 发送的数据并解密传入的数据。 |
| CNAME 子域的证书管理 | 控制面板现在允许您续订已使用 CNAME 方法委派的子域的 SSL 证书。 |

### 新的 Campaign 教程

* 新的 Campaign Standard 教程

| 内容 | 描述 |
| -----------| ---------- |  
| [控制面板 - Google TXT 记录管理](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/google-txt-record-management.html) | 了解如何通过 Campaign 控制面板将 Google TXT 网站验证记录添加到用于向 GMAIL 地址发送电子邮件的所有子域。 |
| [使用外部 API 活动配置和运行工作流](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) | 了解如何使用外部 API 活动来调用外部 REST API 端点。 |
| [Android 推送通知入门 - 教程](https://docs.adobe.com/content/help/en/campaign-standard-learn/getting-started-with-push-notifications-android/introduction.html) | 本教程说明了使用 Campaign Standard 和 Android 应用程序设置推送通知所需的步骤。 |

* 新的 Campaign Classic 教程

| 内容 | 描述 |
| -----------| ---------- |  
| [Snowflake 上的大数据管理](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | 了解如何在 Adobe Campaign Classic 中利用 Snowflake 连接器。 |
| [控制面板 - Google TXT 记录管理](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/google-txt-record-management.html) | 了解如何通过 Campaign 控制面板将 Google TXT 网站验证记录添加到用于向 GMAIL 地址发送电子邮件的所有子域。 |

### Campaign 帮助资源

* Adobe Campaign Standard：[帮助中心](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/campaign-standard-home.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/release-notes/release-notes.html) - [操作方法视频](https://docs.adobe.com/content/help/zh-Hans/campaign-learn/campaign-standard-tutorials/overview.html) - [发行计划](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/release-notes/release-planning.html) - [最新文档更新](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic：[帮助中心](https://docs.adobe.com/content/help/en/campaign-classic/using/campaign-classic-home.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/campaign-classic/using/release-notes/latest-release.html) - [操作方法视频](https://docs.adobe.com/content/help/zh-Hans/campaign-learn/campaign-classic-tutorials/overview.html)- [最新文档更新](https://docs.adobe.com/content/help/zh-Hans/campaign-classic/using/documentation-updates.html)
* Adobe Campaign 控制面板：[文档](https://docs.adobe.com/content/help/zh-Hans/control-panel/using/control-panel-home.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/control-panel/using/release-notes.html)

## ![图标](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

* [Advertising Cloud DSP 中的新增功能](#adcloud-dsp)
* [Advertising Cloud Search 中的新增功能](#adcloud-search)

### Advertising Cloud DSP 中的新增功能 {#adcloud-dsp}

| 功能 | 描述 |
| -----------| ---------- |
| [!UICONTROL Campaigns Classic] 和 [!UICONTROL Campaigns 测试版] | 您可以选择性地为每个促销活动配置的针对欺诈和品牌安全的 IAS 测量设置现在包括用于测量 VAST 和 VPAID 内容库的选项。 |
| [!UICONTROL Campaigns 测试版] | 数据可视化和页面加载时间得到了改进。 |
|  | 现在，您可以在所有页面上下载基于当前过滤器和视图的 Excel 报表。 |
|  | （在 5 月 22 日版本中）新量度包括所有时间量度、当前时间间隔提交、日期特定的 OTS。 |
| [!UICONTROL 黑名单] | 预测系统现在将自动使用广告商级别或帐户级别的黑名单。用户不再需要将黑名单粘贴到展示设置中。 |
| [!UICONTROL 内容库交易] | （内部测试版）利用简化的新表单，您可以快速设置、编辑交易 ID 收件箱中不可用的供应方平台 (SSP) 交易并对其进行故障排除。 |
|  | 当您在交易 ID 收件箱中接受一系列程序化保证交易时，系统会提醒您需要为每个交易 ID 创建一个默认展示位置。 |

### [!UICONTROL Advertising Cloud Search] 中的新增功能 {#adcloud-search}

| 功能 | 描述 |
| -----------| ---------- |
| [!UICONTROL 促销活动] | （Google Ads 帐户；测试版服务）从 5 月下旬开始，Advertising Cloud Search 能够将 Google Gmail 展示促销活动和 Google Smart Shopping 促销活动的数据与 Google 转化进行同步，以进行跟踪和报告。该服务还允许您从“促销活动”和“广告组”视图编辑现有促销活动的促销活动设置和广告组设置。该服务将为可选。服务正式可用后，将收取额外费用。<br>有关该服务（包括测试版项目和未来范围）的更多信息，请联系您的 Adobe 客户经理。 |

## ![图标](/assets/magento.png) [!DNL Magento] {#magento}

有关 Magento 的发行说明，请参阅：

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![图标](/assets/marketo.png) [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] 是一个完整的应用程序，面向希望通过参与复杂购买历程的每个阶段来转变客户体验的潜在客户管理人员和 B2B 营销人员。

### 核心 Marketo Engage 更新

请参阅 [!DNL Marketo] [发行说明](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720)了解最新发行信息。

### 即将推出的功能

本季度将发布以下功能：

| 功能 | 描述 |
|------|---------|
| [!DNL Bizible] | <ul><li>新的基于帐户的分段</li><li>保存特定于功能板的过滤器</li><li>将 Bizible 功能板导出为 PDF</li></ul> |
| Sales Connect | 撰写窗口和命令中心更新/增强功能 |

### 公告

**Marketo Engage 成功中心：**&#x200B;于 2020 年 2 月推出。成功中心是一个产品内帮助中心，允许您搜索产品文档和社区、启动操作指南、访问采用内容等。注意：此功能将作为测试版在澳新银行推出，并将在本季度晚些时候推出到北美洲。

### 弃用

* **Asset API“_method”参数：** 2020 年 9 月之后，Asset API 端点将不再接受 `_method` 在 POST 正文中传递查询参数以绕过 URI 长度限制。
* **弃用 Internet Explorer 支持：**&#x200B;从 2020 年 7 月 31 日发行的 7 月版本开始，Internet Explorer 将不再支持 Marketo Engage 用户界面。

有关累积和历史发行说明，请参阅 [Marketo 发行说明](https://docs.marketo.com/x/CgA6Ag)。
