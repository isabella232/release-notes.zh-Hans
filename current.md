---
title: Adobe Experience Cloud 发行说明
description: Experience Cloud 发行说明模板
doc-type: release notes
last-update: June 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 1f0caf618aad2dd27a0642852a7a45c20b76bf07
workflow-type: tm+mt
source-wordcount: '6484'
ht-degree: 45%

---


# 提前访问- Adobe Experience Cloud发行说明- 2020年6月

![横幅](/assets/experience-cloud-banner-3.png)

This page describes new features, fixes, and important notices in [!DNL Adobe Experience Cloud]. 它还重点介绍新文档、培训课程和视频教程，帮助您充分利用Experience Cloud。

>[!IMPORTANT]
>
>此页面包含预发行内容，在发行版之前可能会发生更改。

>[!NOTE]
>
>若要通过电子邮件接收有关即将发行的版本的通知，请订阅 [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html)。

**发布日期：2020 年 6 月 18 日**

产品发布日期可能不同。 请经常查阅更新。

最新更新日期：**2020 年 6 月 15 日**

* [Adobe 系统状态](#status)
* [Experience Cloud 界面](#ecloud)
* [Experience Platform](#platform)
* [旅程编排](#journey-orch)
* [Analytics](#analytics) (和 [Customer Journey Analytics](#cust-journey))
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/zh-Hans/target/using/release-notes/target-release-notes.html)
* [!DNL Magento](#magento)
* [!DNL Marketo Engage](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/cn/primetime/user-guide.html)（链接到 Primetime 帮助页面）

需要帮助？访 [问Adobe Experience League](https://experienceleague.adobe.com/#home) ，查找产品和技术文档、Adobe特选课程、视频教程、快速答案、社区洞察以及有导师指导的培训。

## ![图标](/assets/adobe.png) Adobe 系统状态 {#status}

[!UICONTROL Adobe 系统状态]提供关于 Adobe 云产品与服务中断和维护事件的详细信息、状态更新以及电子邮件通知。请访问 [status.adobe.com](https://status.adobe.com/) 查看。

已发布： **2020年5月21日**

**新增功能**

* 凭借您的 Adobe ID，您可以订阅粒度更细的事件通知，具体可达到产品和加载项级别。为了帮助您更快地设置订阅，现在，自助订阅过程会根据您的产品权利推荐一系列产品和服务。这样应当会减少您收到的电子邮件数量，并向收件箱中发送更多相关的通知。要开始使用，请访问 [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit)。

**当前可用的新增功能和增强功能**

| 功能 | 描述 |
| -----------| ---------- |
| 改进了订阅和通知用户体验 | <ul><li>现在，系统会根据所选产品的列表过滤 [!DNL Marketo Engage] 区域位置。</li><li>[!DNL Marketo Engage] 电子邮件通知与用户的区域、位置和环境首选项相关。</li></ul> |
| 事件订阅确认 | <ul><li>现在，在订阅正在进行的单个事件更新时，您会收到电子邮件确认。</li></ul> |
| 全局导航可用性增强功能 | <ul><li>顶级导航菜单的用户体验与 `Adobe.com` 一致。</li></ul> |

## ![图标](/assets/ec_appicon_24.png) Experience Cloud 界面 {#ecloud}

Experience Cloud界面的常规更新。

**统一的产品域**

Adobe 一直在更新域和界面标题，以统一并改进您在所有 Experience Cloud 应用程序中的体验。这些增强功能旨在以细微而重要的方式简化您的体验。这些增强不会更改您当前的工作流程。

更新包括：

* 新应用程序URL：`experience.adobe.com/<application name>`：
   * 所有产品最终都将采用此 URL 模式。寻找即将在本月内生效的新 URL。
   * 浏览器支持：支持的浏览器包括 [!DNL Microsoft Edge]、[!DNL Google Chrome]、[!DNL Firefox]、[!DNL Safari] 和 [!DNL Opera]（最新版本）。**注意：** 虽然Experience Cloud界面支持这些浏览器，但单个应用程序可能不支持每个浏览器。 （例如，[Analytics](https://docs.adobe.com/content/help/zh-Hans/analytics/admin/sys-reqs.html) 不支持 [!DNL Opera]，[Target](https://docs.adobe.com/help/zh-Hans/target/using/implement-target/before-implement/supported-browsers.html) 不支持 [!DNL Safari]。）
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
| Adobe Analytics | `experience.adobe.com/analytics` |
| Customer Journey Analytics | `experience.adobe.com/platform/analytics` |
| Adobe Campaign 控制面板 | `experience.adobe.com/controlpanel` |
| Cloud Manager | `experience.adobe.com/cloud-manager` |
| Places Service | `experience.adobe.com/places` |
| Software Distribution | `experience.adobe.com/downloads` |
| 管理员工具（测试版） | `experience.adobe.com/admin` |

>[!NOTE]
>
>[!UICONTROL Marketing Cloud Assets] 选择器中的旧版筛选器&#x200B;**[!UICONTROL 留言板和收藏集]**&#x200B;即将停用。

## ![图标](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Release notes for the [!DNL Experience Platform] and application services, including [!DNL Experience Platform Launch,] [!UICONTROL Offers], [!UICONTROL People], [!UICONTROL Places], [!UICONTROL Mobile Services], and security bulletins.

发布日期：**2020 年 6 月 10 日**

[!DNL Adobe Experience Platform] 包括以下新增功能：

* **数据科学工作区：** 现 [!DNL JupyterLab Launcher] 在包含一 [!DNL Python] 个用于实时机器学习(Alpha)的笔记本启动器。
* **细分：** 添加了日期功能的周年日期字段，使用户能够评估不带年份的日期。
* **来源：** 和的新源接 [!DNL Apache HDFS] 口 [!DNL Couchbase]。

有关这些功能的更多信息，请参阅 [Experience Platform发行说明](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)。

### 其他 Experience Platform 发行信息

* [Experience Platform Launch发行说明](https://docs.adobe.com/content/help/zh-Hans/launch/using/intro/release-notes/current.html)
* [安全公告与建议](https://helpx.adobe.com/cn/security.html)（所有 Adobe 产品）

### 新的Experience Platform课程和教程 {#tutorials-plat}

| 内容 | 内容类型 | 描述 |
| -----------| ---------- | ---------- |
| [Adobe Experience Platform简介](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-U-1-2020.1) | 课程 | 了解Adobe Experience Platform如何通过将数据转换为可在每个渠道激活的可靠实时客户用户档案和AI驱动的洞察来帮助您提供正确的体验。 此入门级课程概述了Experience Platform的功能、使用案例、与Adobe Experience Cloud的关系、基本架构、界面和项目角色。 |
| [Web SDK和Edge Network简介](https://docs.adobe.com/content/help/en/platform-learn/tutorials/data-ingestion/web-sdk/introduction-to-web-sdk-and-edge-network.html) | 视频教程 | Adobe Experience PlatformSDK和Edge Network的概述。 Experience PlatformWeb SDK是客户端JavaScript库，客户可使用一个JavaScript库、一个信标类型、一个数据流、一个服务器端目标将数据发送到所有Adobe应用程序和第三方目标。 |
| [Web SDK和Edge Network的演示](https://docs.adobe.com/content/help/en/platform-learn/tutorials/data-ingestion/web-sdk/demo-of-web-sdk-and-edge-network.html) | 视频教程 | 观看Adobe Experience PlatformWeb SDK和Edge Network的实际操作情况，只需向Adobe发送数据至Experience Platform、Analytics、Audience Manager和Target。 |
| [实时客户数据Platform演示](https://docs.adobe.com/content/help/en/platform-learn/tutorials/rtcdp/demo.html) | 视频教程 | 了解如何使用实时CDP从多个源收集数据。 您可以将该数据合并到单个实时客户用户档案，并激活该数据以创建个性化的客户体验。 |

## ![图标](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

凭借 Adobe Experience Platform，可以实时智能化预测每位客户的需求（无论其旅程通达何处），从而实现跨体验渠道大规模编排客户历程。

### 最新版本

有关最新版本更新，请参阅 [Journey Orchestration发行说明](https://docs.adobe.com/content/help/zh-Hans/journeys/using/release-notes/release-notes.html)

### 新的Journey Orchestration课程和教程 {#jo-tutorials}

| 内容 | 内容类型 | 描述 |
| -----------| ---------- | ---------- |
| [管理员Journey Orchestration入门](https://experienceleague.adobe.com/?recommended=JourneyOrchestration-A-1-2020.2) | 课程 | 了解如何配置和使用Journey Orchestration。 本课程涵盖实现旅程编排所需的主要概念和配置步骤。 了解如何创建、发布以及如何报告和分析精心编排的旅程。 |
| [面向商业用户的Journey Orchestration入门](https://experienceleague.corp.adobe.com/?recommended=JourneyOrchestration-U-1-2020.1) | 课程 | 了解如何配置和使用Journey Orchestration。 本课程涵盖主要概念。 您将学习如何创建、发布、报告和分析精心编排的旅程。 |

### Journey Orchestration 的其他资源

[文档](https://docs.adobe.com/content/help/zh-Hans/journeys/using/journey-orchestration-home.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/journeys/using/release-notes/release-notes.html) - [操作方法视频](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

## ![图标](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Updated **June 10, 2020**

* [Adobe Analytics 中的新增功能](#aa-features)
* [Customer Journey Analytics 的新增功能](#cust-journey)
* [Media Analytics](#media-aa) 的新增功能
* [AdobeAnalytics的修复](#aa-fixes)
* [Analytics 管理员的重要注意事项](#aa-notices)
* [新的AdobeAnalytics课程和教程](#tutorials-analytics)
* [AppMeasurement](#appm)

### Adobe Analytics 中的新增功能 {#aa-features}

| 功能 | [正式发布](https://docs.adobe.com/content/help/zh-Hans/analytics/landing/an-releases.html) - 目标日期 | 描述 |
| -----------| ---------- |-------|
| 归因 IQ：算法归因 | 2020 年 6 月 18 日 | Analysis Workspace 中的“[!UICONTROL 算法归因]”模型可使用统计技术动态确定所选量度的最佳点数分配方式。[了解更多...](https://docs.adobe.com/content/help/zh-Hans/analytics/analyze/analysis-workspace/panels/attribution/algorithmic.html) |
| 归因 IQ：自定义回顾时间范围 | 2020 年 6 月 18 日 | 现在，您可以将“[!UICONTROL 归因 IQ]”中的任意归因模型配置为最多包含在报告期开始前的 90 天内的接触点。通过计算在之前月份发生的交互，通常可以提高在报告期初期所发生事件的归因准确性。[了解更多...](https://docs.adobe.com/content/help/zh-Hans/analytics/analyze/analysis-workspace/panels/attribution/attribution.html#lookback-windows) |
| 共享工作区项目中的项目角色 | 2020 年 6 月 18 日 | 现在，在共享工作区项目时，您可以根据希望收件人获得的项目体验为收件人分配以下三个项目角色中的一个角色：“编辑”、“复制”和“查看”。[了解更多...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| 仅查看工作区项目 | 2020 年 6 月 18 日 | 可以将工作区项目仅以“可以查看”的形式共享给用户。当具有“查看”角色的收件人打开共享项目时，他们将获得比较受限的项目体验，因为项目无左边栏而且可进行的交互也有限。[了解更多...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/view-only-projects.html) |
| 能够共同编辑工作区项目 | 2020 年 6 月 18 日 | 添加到“可以编辑”角色的收件人可以保存已共享给他们的项目。这同时适用于管理员和非管理员用户。[了解更多...](https://docs.adobe.com/content/help/zh-Hans/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| 工作区中已更新的“空白”面板 | 2020 年 6 月 18 日 | 现在，工作区中的“空白”面板包含多个面板和可视化功能，使您能够更加顺畅地选择最适合自己的分析工作流程。 |
| 可在 China RDC 中使用的第一方域 | 2020 年 6 月 18 日 | 允许具有 `.cn` 域的客户请求要在中国大陆境内使用的第一方域。（购买“China 性能优化”SKU 时提供的文档。） |
| 工作区中的 Quick Insights 面板 | 2020 年 6 月 25 日 | Quick Insights 可为 Analysis Workspace 的非分析师和新用户了解如何快速轻松地回答业务问题提供指导。[了解更多...](https://docs.adobe.com/content/help/zh-Hans/analytics/analyze/analysis-workspace/panels/quickinsight.html) |
| 工作区中的 Analytics for Target 面板 | 2020 年 6 月 25 日 | AnalyticsTarget(A4T)面板可让您分析Analysis Workspace中的Adobe Target活动和体验，并保持信心。 [了解更多...](https://docs.adobe.com/content/help/zh-Hans/analytics/analyze/analysis-workspace/panels/a4t-panel.html) |

### Customer Journey Analytics 的新增功能 {#cust-journey}

| 功能 | [正式发布](https://docs.adobe.com/content/help/zh-Hans/analytics/landing/an-releases.html) - 目标日期 | 描述 |
| -----------| ---------- |-----|
| Attribution IQ: [!UICONTROL Algorithmic Attribution] | 2020 年 6 月 18 日 | Analysis Workspace 中的“[!UICONTROL 算法归因]”模型可使用统计技术动态确定所选量度的最佳点数分配方式。[了解更多...](https://docs.adobe.com/content/help/zh-Hans/analytics/analyze/analysis-workspace/panels/attribution/algorithmic.html) |
| 归因 IQ：自定义回顾时间范围 | 2020 年 6 月 18 日 | You can now configure any attribution model in [!UICONTROL Attribution IQ] to include touch-points from up to 90 days before the reporting time period. 通过计算在之前月份发生的交互，通常可以提高在报告期初期所发生事件的归因准确性。[了解更多...](https://docs.adobe.com/content/help/zh-Hans/analytics/analyze/analysis-workspace/panels/attribution/attribution.html#lookback-windows) |
| Support for [!UICONTROL Anomaly Detection] | 2020 年 6 月 18 日 | [!UICONTROL “异常检测”提供了一种统计方法来确定给定的量度相对于以前的数据发生了什么变化。][了解更多...](https://docs.adobe.com/content/help/zh-Hans/analytics/analyze/analysis-workspace/virtual-analyst/anomaly-detection/anomaly-detection.html) |
| Project roles for shared [!UICONTROL Workspace] projects | 2020 年 6 月 18 日 | When sharing a [!UICONTROL Workspace] project, you can now place recipients in one of three project roles, depending on the project experience you want them to have: Edit, Duplicate and View. [了解更多...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| View-only [!UICONTROL Workspace] projects | 2020 年 6 月 18 日 | [!UICONTROL 工作区] 项目可共享给用户， _[!UICONTROL 仅可视图]_。 当视图收件人打开共享项目时，他们将获得限制性更强的项目体验，无左边栏且交互有限。[了解更多...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/view-only-projects.html) |
| Ability to co-edit [!UICONTROL Workspace] projects | 2020 年 6 月 18 日 | Recipients added to the _[!UICONTROL Can Edit]_role can save over a project that has been shared to them.[了解更多...](https://docs.adobe.com/content/help/zh-Hans/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| [!UICONTROL Workspace] 中的 Quick Insights 面板 | 2020 年 6 月 25 日 | Quick Insights 可为 [!UICONTROL Analysis Workspace] 的非分析师和新用户了解如何快速轻松地回答业务问题提供指导。[了解更多...](https://docs.adobe.com/content/help/zh-Hans/analytics/analyze/analysis-workspace/panels/quickinsight.html) |

### [!UICONTROL Media Analytics] 的新增功能 {#media-aa}

更新日期：**2020 年 5 月 29 日**

**播放器状态跟踪：**[!UICONTROL Media Analytics] 客户可以使用一组用于全屏、隐藏式字幕、静音、画中画和聚焦的标准解决方案变量在播放过程中捕获观看者交互。您还可以灵活地创建自定义播放器状态。播放器状态跟踪变量现在可以在 [!UICONTROL Analysis Workspace] 中进行报告。此功能需要以下任一项：

* Media [!DNL JavaScript] SDK 3.0 或更高版本
* 与 [!DNL Adobe Experience Platform] (AEP) SDK 一起使用时：
   * [!UICONTROL Media Analytics 扩展]（用于 Web）：[!UICONTROL Adobe Media Analytics] (3.x SDK) for Audio and Video v1.0 或更高版本
   * [!UICONTROL Media Analytics 扩展]（用于移动设备）：[!UICONTROL Adobe Media Analytics for Audio] and Video v2.0 或更高版本
* [!UICONTROL 媒体收集]

请参阅[关于播放器状态跟踪](https://docs.adobe.com/content/help/zh-Hans/media-analytics/using/player-state-tracking/player-state-overview.html)。

### AdobeAnalytics的修复 {#aa-fixes}

* 修复了导致对某些报表包进行多字节搜索的区段与任何字符串均不匹配的问题。这些区段现在可匹配到正确的字符串。(AN-220043)
* Fixed an issue with the [!UICONTROL Item Filter] in [!UICONTROL Reports &amp; Analytics] not working. (AN-206132)
* Fixed slow response time in [!UICONTROL Scheduled Projects] interface. (AN-214837)
* 修复了 Analytics 报表 API 2.0 抛出日期范围错误的问题。(AN-215087)
* Fixed a case in which the instance/visit/visitor wasn&#39;t being counted in the denominator for the [!UICONTROL Time Spent] metrics. 如果在同一秒内紧接着发生没有值的维度（例如 Pagename）的命中时，就会发生这种情况。(AN-211074)
* Fixed an issue with users unable to access [!UICONTROL Workspace] projects shared with them. (AN-217561)
* Fixed issue with keys not being classified by [!UICONTROL Classification Rule Builder]. (AN-221538)
* Fixed an issue with the [!UICONTROL Server Call Usage] not reporting any usage data. (AN-210452)
* 修复了已发布的AdobeAnalytics区段在Audience Manager中缺少数据的问题。 (AN-220208 和 AN-220659)
* Fixed an issue with reports showing data but [!UICONTROL Data Feeds] logs saying &quot;No Data Warehouse data&quot;. (AN-220784 和 AN-220858)
* Fixed issues that prevented the launch of [!UICONTROL Ad Hoc Analysis] from the `experiencecloud.com` domain. (AN-219680 和 AN-221629)
* 修复了与“Ctrl（或 Command）+ C”热键使用相关的问题。(AN-221101 和 AN-221537)
* Fixed an issue with the [!UICONTROL Activity Map] enablement page. (AN-222029 和 AN-221242)
* Fixed an issue with not being able to add a touch-point in the middle of a [!UICONTROL Fallout] visualization. (AN-221648)

#### 其他 Adobe Analytics 修复

AN-218269、AN-218455、AN-218492、AN-219888、AN-220447、AN-220546、AN-220788、AN-220866、AN-221165、AN-221545、AN-221712、AN-221832、AN-221853、AN-222000、AN-222505、AN-222559

### [!DNL Analytics] 管理员的重要注意事项 {#aa-notices}

| 注意事项 | 添加或更新日期 | 描述 |
| -----------| ---------- | ---------- |
| 迁移到统一的产品域 | 生效日期：2020 年 5 月 28 日 | 向 Adobe Analytics 统一产品域的迁移从 2020 年 1 月开始，于 2020 年 5 月 28 日完成。虽然 Adobe Analytics 会从其架构中删除所有 `omniture.com` 域引用，但务必要将 `omniture.com` 作为第三方 Cookie 添加到白名单中。当完全架构迁移（即将完成）时，我们将通过发行说明通知您，并且不再需要此allowlist步骤。 [此处](https://helpx.adobe.com/cn/analytics/kb/adobe-ip-addresses.html)提供了建议应添加到白名单中的 IP 地址和域的完整列表。<br>如果贵组织阻止第三方 Cookie，请联系客户关怀团队以重新获得 Adobe Analytics 访问权限。 |
| 新的 Adobe Analytics 默认登陆页面 | 生效日期：2020 年 6 月 18 日 | 2020 年 6 月 18 日，Adobe Analytics 的默认登陆页面将从[!UICONTROL 报表]更改为[!UICONTROL 工作区]。之前未设置自定义登陆页面的任何用户都将发生此更改。 |
| 第三方技术允许列表 | 2020 年 3 月 12 日（生效日期） | Adobe Analytics 已开始利用第三方技术进行功能推出管理和提供产品内支持。应将以下 URL 添加到所有必要的网络防火墙允许列表中，以确保能够完全访问功能：<ul><li>Gainsight：https://esp.aptrinsic.com</li><li>LaunchDarkly：https://app.launchdarkly.com</li></ul> |
| Improved redundancy for [!UICONTROL Analysis Workspace] availability | 2020 年 5 月 21 日 | In order to ensure availability of [!UICONTROL Analysis Workspace], we are adding a secondary CDN (Content Delivery Network) for improved redundancy. 应将以下URL添加到任何必要的网络防火墙允许列表中：<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| 在[!UICONTROL 工作区]中更改[!UICONTROL 登入/退出]的计算方式 | 2020 年 4 月 7 日 | 在 [!UICONTROL Analysis Workspace] 中，从 2020 年 3 月起，我们更改了&#x200B;_无_&#x200B;值与[!UICONTROL 登入/退出]的交互方式。由于您现在可以在 _Analysis Workspace_ 中打开和关闭[!UICONTROL 无]，因此我们会在登入或退出后应用&#x200B;_无_&#x200B;值，而（对于 eVar）过去是在登入或退出前应用。例如，假定访问的第一次点击没有 eVar 值，但第二次点击有。在 [!UICONTROL Reports &amp; Analytics] 中，第一次点击将针对“登入”显示为&#x200B;_未指定_，但在 [!UICONTROL Analysis Workspace] 中，将显示第二次点击时的值。 |
| **[!UICONTROL 功能板存档]**&#x200B;生命周期终止 | 2020 年 3 月 27 日 | 自 2020 年 10 月起，在 [!UICONTROL Reports &amp; Analytics] 中，位于&#x200B;**[!UICONTROL 管理功能板]**&#x200B;下方的&#x200B;**[!UICONTROL 查看存档]**&#x200B;将不再可用。 |
| 生命周期结束 - Analytics 旧版 API | 2020 年 1 月 9 日 | 2020 年 11 月，以下 Analytics 旧版 API 服务将停止使用并关闭。当前使用这些服务构建的集成将会停止工作。 <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>旧版 OAuth 身份验证（OAuth 和 JWT）</li></ul>我们提供了[旧版 API EOL 常见问题解答](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)，以帮助回答您的问题并提供有关如何继续的指导。使用这些服务的 API 集成可以迁移到 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 或 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。旧版 OAuth 帐户可迁移到 [Adobe IO](https://console.adobe.io/home?mv=email) Analytics 集成帐户，该帐户可用于访问 1.4 Analytics API 和 2.0 Analytics API。 |
| 圣何塞 FTP 中转站停止为伦敦和新加坡提供支持 | 2020 年 7 月 | 对于位于伦敦和新加坡的客户，我们将不再提供伦敦或新加坡与圣何塞数据中心 [ftp.omniture.com](ftp://ftp.omniture.com/) 之间的数据中转支持。<br/><ul><li>伦敦客户，请使用 [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>新加坡客户，请使用 [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Ad Hoc Analysis 生命周期终止 | 2018 年 8 月 6 日 | Adobe 宣布计划终止 Ad Hoc Analysis 生命周期。确定终止日期后，Adobe 会立即与大家共享此信息。有关更多信息，请参阅[探索工作区](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)。 |

#### Analytics新课程和教程 {#tutorials-analytics}

Analytics和Customer Journey Analytics中的新课程、教程视频和文章。

| 内容 | 内容类型 | 描述 |
| -----------| ---------- | ---------- | 
| [用户Customer Journey Analytics入门](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-U-1-2020.1) | 课程 | 在本课程中，您将学习如何使用Customer Journey Analytics(CJA)分析来自许多不同数据源的数据。 您将了解AdobeAnalytics与Customer Journey Analytics之间的差异，以及CJA中如何处理数据。 参加本课程后，您应能够创建和自定义交叉渠道可视化，以加深对客户的了解。 |
| [管理员Customer Journey Analytics入门](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-A-1-2020.1) | 课程 | 了解如何配置和使用 [!UICONTROL Journey Orchestration]。 本课程涵盖实现旅程编排所需的主要概念和配置步骤。 您将学习如何创建、发布以及如何报告和分析精心编排的旅程。 |
| [Customer Journey Analytics工程师入门](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-D-1-2020.1) | 课程 | 在本课程中，您将了解Customer Journey Analytics中的数据以及数据对分析师报告的影响。 本课程以您对Adobe Experience Platform的一般知识为基础。 |
| [管理员Customer Journey Analytics入门](https://video.tv.adobe.com/v/34349?captions=chi_hans) | 视频教程 | 面向管理员的Customer Journey Analytics介绍视频。 |
| [指导Analytics实施](https://experienceleague.adobe.com/?recommended=Analytics-D-1-2019.1) | 课程 | 在本课程中，您将学习如何开始实施AdobeAnalytics、了解Analytics概念、制定计划以及使用Experience Platform Launch实施AdobeAnalytics。 |
| [AdobeAnalytics面向领导者的基础知识](https://experienceleague.adobe.com/?recommended=Analytics-L-1-2020.1) | 课程 | 在本课程中，了解Analytics的基本面，以及Analysis Workspace如何改变您的业务。 了解如何通过Adobe Sensei发掘洞察、听取客户评价并观看2019年峰会行业专家的亮点。 |
| [Analysis Workspace入门](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2020.1.workspace) | 课程 | 了解如何开始使用Analysis Workspace。 构建您的第一个项目，了解如何定义日期范围、应用细分以及共享和协作项目。 |
| [AdobeAnalytics仪表板记分卡构建器](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/additional-tools/analytics-dashboards/adobe-analytics-dashboards-scorecard-builder.html) | 视频教程 | 在此视频中，了解如何在Analysis Workspace中创建 [!UICONTROL 和共享] Scordan [!UICONTROL 卡] ，以便在AdobeAnalytics仪表板（移动应用程序）上查看。 |
| [AdobeAnalytics仪表板应用程序内体验](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/additional-tools/analytics-dashboards/adobe-analytics-dashboards-in-app-experience.html) | 视频教程 | 在此视频中，了解如何使用AdobeAnalytics仪表板（移动应用程序）访问和视图由您创建 [!UICONTROL 或与您] 共享的记分卡。 |

#### Analytics 帮助资源

* [Adobe Analytics 教程](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics 产品文档](https://docs.adobe.com/content/help/zh-Hans/analytics/landing/home.html)

## ![图标](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Audience Manager 中的新增功能、修复、文档和教程。

Updated **June 10, 2020**

### 用户界面更新

Audience Manager 将发布对域和标题栏的更新，以改进您的体验并与其他 Experience Cloud 应用程序相结合。

* 更轻松地在组织之间切换，或切换到其他应用程序。
* 改进了用户帮助，包括“帮助”菜单中的精选文章和与上下文相关的视频。
* 能够提供有关Experience Platform和文件支持票证的反馈。
* 更简单的新 URL 模式。将书签更新到新 URL：`experience.adobe.com/audience-manager`。

这些更新仅适用于使用 Adobe ID 登录的用户。要切换到 Adobe ID 登录，请参阅[管理 Experience Cloud 用户和产品](https://docs.adobe.com/content/help/zh-Hans/core-services/interface/manage-users-and-products/admin-getting-started.html)。

### Adobe Audience Manager 中的新增功能和修复

| 功能 | 描述 |
| -----------| ---------- |  
| [IAB TCF v2.0的Audience Manager插件 ](https://docs.adobe.com/content/help/zh-Hans/audience-manager/user-guide/overview/data-privacy/consent-management/aam-iab-plugin.html) | 继续Adobe专注于“从设计入手保护隐私”，我们将IAB TCF的Audience Manager插件升级到IAB透明度与同意框架(TCF)版本2.0，从2020年6月10日开始。 已为IAB TCF实施Audience Manager插件的客户必须在2020年8月15日之前升级到版本2.0，才能继续使用该功能。 在2020年8月15日之后，版本1.1将弃用并不再受支持。 |

**修复**

* 更新了 [!UICONTROL Audience Marketplace条款和条件] ，以反映特定地区的法律要求。 (AAM-54518)
* 修复了从书签访 [!UICONTROL 问] “特征”页面会导致404错误的问题。 (AAM-54768)
* 修复了检索算法模型时目标更新API超时 [!UICONTROL 的问题]。 (AAM-54342)
* 用户现在可以看到智能人员的模型分类准确 [!UICONTROL 度指标]。 (AAM-54847)
* 修复了添加特征表达式后按Enter将删除表达式而不保存的问题。 (AAM-54210)
* 修复了未具有视图模型权限的 [!UICONTROL 用户] ，对Traits API的GET方法的调用将失败的问题。 (AAM-53104)
* 修复了用户无法删除包含文件夹 [!UICONTROL 特征的算法] 模型 [!UICONTROL 的问题]。 (AAM-50192)
* 长特征表达式现在跨多行换行。 (AAM-54972)
* 修复了具有只读权限的用户在算法模型页 [!UICONTROL 面中可以看] 到“创建新”按钮的问题。 (AAM-54889)
* 修复了在CSV下载 [!UICONTROL 完成后] ,“常 [!UICONTROL 规”和“趋势] ”报表加载指示器继续旋转的问题。 (AAM-54571)
* 修复了用户无法向区段生成器中的区段添加批量特 [!UICONTROL 征的问题]。 (AAM-55033)
* 改进了整个界面的多项辅助功能。(AAM-47269、AAM-48966、AAM-48976、AAM-49369、AAM-49023、AAM-49042)。

### 新的Audience Manager课程和教程 {#tutorials-aam}

| 内容 | 内容类型 | 描述 |
| -----------| ---------- | ---------- |  
| [Audience Manager简介](https://experienceleague.adobe.com/?recommended=AudienceManager-U-1-2020.1) | 课程 | 本课程教您Audience Manager的基础知识以及使用它可以解决的问题。 了解常见使用案例和主要Audience Manager术语和概念。 |
| [Audience Manager中的身份介绍](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/introduction-to-identity-in-audience-manager.html) | 视频教程 | 了解Adobe Audience Manager如何管理身份，包括内部用户档案和用户档案合并以及与合作伙伴的ID同步。 |
| [了解和配置LinkedIn基于人的目标](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/data-activation/people-based-destinations/understanding-and-configuring-the-linkedin-pbd.html) | 课程 | 此视频将引导您逐步了解创建LinkedIn的基于人的目标的概念和步骤。 它以关于基于人的目标的其他视频和文档为基础。 |
| [创建基于规则的特征](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/creating-rule-based-traits.html) | 视频教程 | 了解如何在Audience Manager [!UICONTROL 界面中使用] Trait Builder创建基于规则的特征，从而使您能够将实时活动捕获到Audience Manager用户档案。 |
| [为IAB TCF 2.0启用Audience Manager插件](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/setup-and-admin/data-governance-and-privacy/iab-tcf-support.html#enabling-iab-tcf) | 视频教程 | 了解如何为IAB TCF启用Audience Manager插件。 如果您使用Adobe Experience Platform启动，则启用此插件很简单。 |
| [IAB TCF 2.0Audience Manager插件演示](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/setup-and-admin/data-governance-and-privacy/iab-tcf-support.html#demo) | 视频教程 | 在此视频中，查看Experience CloudID服务和解决方案的cookie和信标如何受IAB用户选择选择的影响。 |

## ![图标](/assets/aem.png) Adobe Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新增功能、修复和更新。Adobe 建议那些采用内部部署的客户部署最新的修补程序，以便确保获得更高的稳定性、安全性和性能。

### 产品更新

* **AEM 6.5.5.0**

   AEM 6.5,Service Pack 5（2020年6月4日发布）是一个重要更新，包含新功能、客户请求的重要增强功能以及自2019年4月AEM 6.5正式发布以来发布的性能、稳定性和安全性改进。

   * [发行说明](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
   * [AEM Forms 发布的交付内容](https://helpx.adobe.com/cn/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.1**

   AEM 6.4、Service Pack 8、累积修复包（2020年6月04日发布）是自2020年3月AEM 6.4、Service Pack 8(6.4.8.0)正式发布以来，包含多个内部和客户修复的重要更新。

   * [发行说明](https://docs.adobe.com/content/help/en/experience-manager-64/release-notes/cfp-release-notes.html)
   * [AEM Forms 发布的交付内容](https://helpx.adobe.com/cn/aem-forms/kb/aem-forms-releases.html)

### 自助服务

* **AEM 作为云服务**

   AEM作为Cloud Service有哪些新增功能？

   亮点包括：

   * AEM Sites商务集成框架。
   * 增强的智能标记和UI中新增的向导式培训体验。
   * 针对Adobe Xd的Adobe Asset Link支持。
   * AEM AssetsDynamic Media3D支持。
   * 新的自助服务改进减少了对Adobe沙箱操作的依赖性。
      * 云管理器中增强的自助沙箱支持允许授权用户删除沙箱内的所有环境并接收积分。
      * 自动休眠沙箱环境在一段时间不活动后自动“休眠”沙箱。 客户可以主动触发“去休眠”。
   * 支持云加速的过渡工具
   为了减少过渡从事先到Cloud Service的时间和成本，本月推出了两款过渡工具。 这些工具设计为在过渡过程中自动执行一些关键任务，从而减少总体工作量。 .

   1. [使用内容传输工具](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-content-transfer-tool.html) （SD上提供）简化内容传输活动并使其可伸缩。 借助用户友好的UI，该工具可为正在以Cloud Service身份过渡到AEM的现有客户和合作伙伴（在预先/AMS）提供自助服务。
   1. [AMSDispatcher转换器](https://github.com/adobe/aem-cloud-service-dispatcher-converter) （开放源代码）工具可自动将AMSDispatcher配置转换为Cloud ServiceDispatcher配置。
   [AEM作为Cloud Service2020.6.0的发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)

   过渡工具：

   https://github.com/adobe/aem-cloud-service-dispatcher-converter

   https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-content-transfer-tool.html

* **核心组件**

   核心组件2.9.0引入了与Adobe Client Data Layer和新 [进度栏组件的集成](https://github.com/adobe/adobe-client-data-layer) ，现在还提供创作文档 [、开发](https://docs.adobe.com/content/help/zh-Hans/experience-manager-core-components/using/introduction.html) 人员详细信息以及GitHub上的项目下载 [](https://github.com/adobe/aem-core-wcm-components)。

* **作为Cloud Service移到AEM**

   [以Cloud Service身份转移到AEM](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/home.html) ，描述了现有AEM客户转到Cloud Service的推荐过渡旅程。 本文档旨在为客户提供信息、指导和最佳实践，帮助他们为此过渡做好准备，并使此旅程具有结构化和可预测性。

   已发布一种云过渡工具——内容传输工具。 [内容传输工具](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/overview-content-transfer-tool.html) 由Adobe开发，可用于将现有内容从源AEM实例（内部部署或AMS）移至目标AEMCloud Service实例。

   已发布一个代码重构工具- AEMDispatcher转换器。 [AEMDispatcher转换器](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/refactoring-tools/dispatcher-transformation-utility-tools.html) 是一种将现有AEMDispatcher配置转换为AEM的工具，可用作Cloud ServiceDispatcher配置。

* **辅助功能和WCAG 2.1准则**

   与WCAG 2.1准则相关的更新：

   * [Adobe Experience Manager 云服务和 Web 无障碍准则](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/accessibility/web-accessibility.html)
   * [WCAG 2.1 快速指南](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/accessibility/quick-guide-wcag.html)
   * [创建无障碍内容（WCAG 2.1 合规性）](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/sites/authoring/fundamentals/accessible-content.html)

* **AEM 新闻稿**

   Experience League 撰写的 AEM 新闻稿旨在帮助您快速掌握 AEM，以便立即开始实现价值。以下是最新的新闻稿：

   * [第 31 卷](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.31.html)：Experience Manager 现已作为云服务提供。
   * [订阅](https://adobeeventsonline.com/AEM/2017/NL/Optin/) Experience 内部新闻稿。
   * 在 Adobe Experience Manager 6.5“学习与支持”页面的 [AEM 资源](https://helpx.adobe.com/cn/support/experience-manager/6-5.html)部分中查看新闻稿存档。

### **社区**

* **AEM社区讨论**

   现在，您可以在一个位置查看所有AEM公告以及对内部和外部博客作者的有趣引用。 请参阅AEM Community的“讨 [论”部分。](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/bd-p/adobe-experience-manager-discussions)

### 新的Experience Manager课程和教程

| 内容 | 内容类型 | 描述 |
| -----------| ---------- | ---------- |
| [面向商业用户的Adobe Asset Link快速入门](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.asset.link) | 课程 | 在本课程中，了解如何使用Adobe Asset Link的特性和功能，通过Adobe Experience Manager资产中存储的内容助力您的创意设计。 本课程涵盖方方面面，从如何启动adobe资产链接、基本资产操作、搜索和浏览选项，以及如何与其他用户高效协作。 |
| [面向商业用户的AEM Assets入门](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.assets) | 课程 | 了解如何开始为商业用户使用AEM Assets。 浏览有关AEM Assets、协作功能、搜索、组织资产以及下载资产及其演绎版的基础知识。 |
| [面向商业用户的AEM Sites入门](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.sites) | 课程 | 了解如何使用AEM Sites的核心功能和功能来管理您组织的网页。 本课程涵盖从AEM Sites简介、创作的基本概念、高级创作功能和页面管理功能等一切内容。 |
| [AEM 项目结构](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/developing/aem-project-content-package-structure.html) | 文章 | 介绍Adobe Experience ManagerMaven项目以使其与AEMCloud Service兼容所需的更改。 |
| [Sling Models](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/osgi-web-consoles.html#sling-models) | 视频教程 | 了解如何使用Sling Models Web控制台将AEM作为Cloud ServiceSDK的本地快速启动进行调试。 |
| [AEM Web Console组件](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/osgi-web-consoles.html#components) | 视频教程 | 了解如何使用组件Web控制台将AEM作为Cloud ServiceSDK的本地快速启动进行调试。 |
| [使用日志调试AEM SDK的本地快速启动](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/logs.html) | 视频教程 | 了解如何使用Bundles Web控制台将AEM作为Cloud ServiceSDK的本地快速启动进行调试。 |
| [将AEM作为Cloud ServiceSDK的本地快速启动进行远程调试](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/remote-debugging.html) | 视频教程 | 了解从IDE进行的远程Java调试，它允许您在AEM中逐步执行实时代码，以了解确切的执行流程。 |
| [智能标记设置](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/metadata/smart-tags-technical-video-setup.html) | 视频教程 | 使用Adobe I/O将Adobe Experience Manager(AEM)与智能内容服务集成的分步说明。 |
| [批量生成文档](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/interactive-communications/batch-generation-interactive-communications.html) | 文章 | 了解如何使用Batch API从模板生成多个交互式通信。 |
| [在AEM Forms中创建打印渠道文档](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/ic-print-channel-tutorial/introduction.html) | 文章 | 了解为印刷渠道创建交互式通信所需的步骤。 |
| [访问Adobe Asset Link](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/launch-adobe-asset-link.html) | 视频教程 | 了解如何访问存储在Adobe Experience Manager资产(AEM Assets)中的内容，而不离开您最熟悉的Creative Cloud桌面应用程序。 |
| [资产链接面板概述](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/panel-overview.html) | 视频教程 | Adobe Asset Link使创意用户能够使用InDesign、Photoshop和Illustrator中的应用程序内面板浏览、搜索、签出和签入存储在AEM Assets中的资源。 了解Adobe Asset Link面板的UI及其功能。 |
| [资产搜索](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/asset-search.html) | 视频教程 | 创意用户可以使用关键字搜索存储在AEM Assets中的资产，或在特定位置下执行搜索。 |
| [文件版本和注释](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/file-versioning-and-comments.html) | 视频教程 | 使用Adobe Asset Link面板，您可以从面板中访问AEM Assets中资产（如缩略图、基本元数据和版本）的文件详细信息。 |
| [登记注销](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/check-in-check-out.html) | 视频教程 | Adobe Asset允许您直接从您正在处理的创意应用程序中签出AEM Assets，并可立即开始进行编辑。 |
| [仅用于AEM Assets的放置再现](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/for-placement-only.html) | 视频教程 | 了解如何为AEM资产创建和使用仅限放置(FPO)再现。 |
| [置入副本](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/place-copy.html) | 视频教程 | 了解如何使用置入副本操作从AEM Assets使用资产。 |
| [下载和上传](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/download-and-upload.html) | 视频教程 | 了解如何使用“资产链接”面板从AEM Assets下载资产文件并将其上传到客户。 |
| [文件和集合](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/files-and-collections.html) | 视频教程 | 了解如何从“资产链接”面板快速轻松地访问AEM Assets文件和集合。 |
| [下载](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/sharing/download.html) | 视频教程 | 了解如何将资产及其演绎版下载到本地机器以供使用和共享。 |

### 其他资源

* [AEM 作为云服务](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-5.html)
* [AEM 6.4 学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-4.html)
* [AEM 6.3 学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-3.html)
* [AEM 6.2 学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-2.html)
* [Cloud Manager 用户指南](https://helpx.adobe.com/cn/experience-manager/cloud-manager/user-guide.html)
* [更早版本的 AEM 文档](https://helpx.adobe.com/cn/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic 帮助主页](https://docs.adobe.com/content/help/zh-Hans/dynamic-media-classic/using/home.html)
* [Dynamic Media 发行说明](https://docs.adobe.com/content/help/en/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Livefyre 发行说明](https://docs.adobe.com/content/help/zh-Hans/livefyre/using/release-notes/c-rn.html)

## ![图标](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign 提供了一种直观、自动的方式，以通过在线和离线营销渠道来交付一对一的消息。您现在可以利用根据客户习惯和喜好所决定的体验，来预测客户的需求。

### 新产品版本

[Adobe Campaign经典20.2版本](https://docs.adobe.com/content/help/zh-Hans/campaign-classic/using/release-notes/latest-release.html) 包括：

* _支持表情图标_ - _Azure突触联合数据访问连接器_ -新 _的隐私法规_
* 活动控制面板： [主动用户档案监视](https://docs.adobe.com/content/help/en/control-panel/using/performance-monitoring/active-profiles-monitoring.html)

### 新的Campaign课程和教程

| 内容 | 内容类型 | 描述 |
| -----------| ---------- | ---------- |  
| [面向商业用户的Adobe Campaign Standard入门](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.standard) | 课程 | 了解如何导航界面、处理投放以及创建和管理收件人数据。 |
| [安装和设置Adobe Campaign客户端](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.standard) | 视频 | 了解如何下载和安装Adobe Campaign客户端控制台，创建和管理与多个环境的连接，以及验证对Adobe Campaign客户端控制台的访问权限 |

### 帮助资源

* Adobe Campaign Standard：[帮助中心](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/campaign-standard-home.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/release-notes/release-notes.html) - [操作方法视频](https://docs.adobe.com/content/help/zh-Hans/campaign-learn/campaign-standard-tutorials/overview.html) - [发行计划](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/release-notes/release-planning.html) - [最新文档更新](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic：[帮助中心](https://docs.adobe.com/content/help/en/campaign-classic/using/campaign-classic-home.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/campaign-classic/using/release-notes/latest-release.html) - [操作方法视频](https://docs.adobe.com/content/help/zh-Hans/campaign-learn/campaign-classic-tutorials/overview.html)- [最新文档更新](https://docs.adobe.com/content/help/zh-Hans/campaign-classic/using/documentation-updates.html)
* Adobe Campaign 控制面板：[文档](https://docs.adobe.com/content/help/zh-Hans/control-panel/using/control-panel-home.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/control-panel/using/release-notes.html) -针对Campaign Standard/的 [操作](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html) / [Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

## ![图标](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Updated **June 3, 2020**

* [Advertising Cloud DSP 中的新增功能](#adcloud-dsp)
* [Advertising Cloud Search 中的新增功能](#adcloud-search)

### Advertising Cloud DSP 中的新增功能 {#adcloud-dsp}

| 功能 | 描述 |
| -----------| ---------- |
| [!UICONTROL 活动] 主页 | （6月3日版本）根据提供的活动预算和已用时间，推出新的活动级节奏指标。 |
| 位置预测 | （6月3日发布）对于具有位置级别优化的CTV和视频放置，位置设置现在包括对多个广告长度（15秒和30秒）的预测。 还包括对VAST和VPAID库存的预测。 |
| CPA/ROAS优化 | （5月20日发布）活动经理不再需要将新职位安排限制在包中，以防止预算过度分配。 现在，定位将根据其CPM或CPA/ROAS绩效获得动态预算分配。 |

### [!UICONTROL Advertising Cloud Search] 中的新增功能 {#adcloud-search}

| 功能 | 描述 |
| -----------| ---------- |
| [!UICONTROL 促销活动] | 2020年9月30日之后，Microsoft Advertising（以前称为Bing Ads）正在弃用平均职位指标。 为此，从7月11日开始，将忽略基于位置的约束，也忽略任何类型约束中基于位置的条件。 |
| [!UICONTROL 广告洞察] | （6月13日发布）删除了以下洞察：<br/><br/><ul><li>受众Target性能（较新版本）</li><li>历史性能（较新版本）</li><li>匹配类型（较新版本）</li><li>设置审核（较新版本）</li><li>Portfolio Pre-Post（旧版）</li></ul><br/>其余的洞察是旧版本，并且 _从名称_ 中删除了旧版标签。 此外，还删除了“实时／编辑”模式。 |

## ![图标](/assets/magento.png) [!DNL Magento] {#magento}

有关 Magento 的发行说明，请参阅：

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![图标](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

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
