---
title: Experience Cloud和Experience Platform发行说明
description: 了解有关Experience Cloud和Experience Platform的最新发行说明、新增功能和新文档。 查找有关企业版和Creative Cloud的新帮助和教程。
doc-type: release notes
last-update: February 2021
author: mfrei
translation-type: tm+mt
source-git-commit: ef6eb673a8a62d657b56ef09e694202874742459
workflow-type: tm+mt
source-wordcount: '6357'
ht-degree: 32%

---


# Adobe Experience Cloud 发行说明 - 2021 年 2 月

![横幅](/assets/experience-cloud-banner-3.png)

Experience Cloud解决方案和服务每月更新。 本页是您查找[!DNL Experience Cloud]和Experience Platform最新版本更新、文档和教程的中心位置。 您还可以找到[!DNL Creative Cloud for Enterprise]和[!DNL Document Cloud]的新文档。

>[!IMPORTANT]
>
>本页包含预发行内容，在发行日期之前可能会发生更改。

>[!NOTE]
>
>若要接收有关此页面更新的电子邮件通知，请订阅每月的 [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html)。本页在当月内进行维护，因此请定期查阅以获取Adobe企业产品和Experience League文档的更新。

最新更新：**2021年2月12日**

* [Adobe 系统状态](#status)（未更新）
* [Experience Cloud 服务和管理](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Analytics](#analytics) 和 [Customer Journey Analytics](#cust-journey)&#39;
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [[!DNL Target]](#target)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo)
* [Document Cloud](#doc-cloud)
* [Creative Cloud Enterprise](#creative-cloud)

需要帮助？请访问 [Adobe Experience League](https://experienceleague.adobe.com/#home)，查找产品和技术文档、Adobe 策划课程、视频教程、快速解答、社区洞察以及由讲师指导的培训。

## ![图标](/assets/adobe.png) Adobe 系统状态 {#status}

[!UICONTROL Adobe 系统状态]提供关于 Adobe 云产品与服务中断和维护事件的详细信息、状态更新以及电子邮件通知。请访问 [status.adobe.com](https://status.adobe.com/) 查看。

本月未进行更新。

请参阅 [Adobe 系统状态 - 2020 年 5 月 21 日](https://docs.adobe.com/content/help/zh-Hans/release-notes/experience-cloud/previous/2020/05212020.html#status)，以了解最新版本信息。

## ![图标](/assets/ec_appicon_24.png) Experience Cloud 服务和管理 {#ecloud}

[Experience Cloud 服务和管理](https://docs.adobe.com/content/help/zh-Hans/core-services/interface/experience-cloud.html)文档包括客户属性、受众库（[!UICONTROL 人员]服务）、激活、用户和产品管理，以及 Experience Cloud Cookie。

**2021 年 2 月 4 日**

* **登录更新：对Experience Cloud** 的更新将删除初始Experience Cloud登录介绍屏幕。从2月4日开始，您将直接从`https://experience.adobe.com/login`发送到Adobe登录屏幕。

## ![图标](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

包括 Experience Platform 和 Experience Platform Launch 的发行更新信息。

* [Experience Platform 发行说明](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=zh-Hans). (2021 年 1 月 27 日)
* [Experience Platform Launch 发行说明](https://experienceleague.adobe.com/docs/launch/using/release-notes/current.html). (2021 年 1 月 13 日)

### Experience Platform教程和课程

发布的关于 Experience Platform 和服务的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 2 月 10 日 | [配置Azure Blob目标](https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/configure-the-azure-blob-destination.html?lang=en#destinations) | 视频 | 了解如何在实时存储平台（实时CDP）中逐步完成设置和配置和Azure Blob目标所需的步骤。 |
| 2021 年 2 月 4 日 | [视图标识图](https://experienceleague.adobe.com/docs/platform-learn/tutorials/identities/view-identity-graphs.html) | 视频 | 如何使用标识图查看器功能搜索、浏览和筛选标识图，以便进行验证和调试。 |
| 2021 年 2 月 3 日 | [批量数据获取概述](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/batch-ingestion-overview.html) | 视频 | Adobe Experience Platform中的批量数据获取概述。 了解如何使用API收录批数据。 |
| 2021 年 2 月 3 日 | [将数据激活到非Adobe应用程序](https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/activate-data-to-non-adobe-applications.html) | 视频 | 了解Adobe的实时CDP如何帮助您通过受众创建真正的个性化战略。 此外，了解它如何融入Microsoft、Google和Facebook现有的生态系统和非Adobe应用程序。 |
| 2021 年 1 月 21 日 | [面向营销人员的智能服务入门课程介绍](https://video.tv.adobe.com/v/330805?quality=12&learn=on) | 视频 | 营销人员智能服务入门课程的简介。 |
| 2021 年 1 月 13 日 | [营销人员Offer Decisioning入门简介](https://video.tv.adobe.com/v/330520?quality=12&learn=on) | 视频 | 以及面向营销人员的Offer Decisioning入门课程的介绍。 |
| 2021 年 1 月 31 日 | [使用菜谱构建器模板培训、评分和提高模型效率](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-science-workspace/train-score-and-productize-models.html) | 视频 | 了解如何使用更新的菜谱构建器模板来使用零售销售模式和数据集构建菜谱。 |
| 2021 年 1 月 31 日 | [在JupyterLab笔记本中加载数据](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-science-workspace/load-data-in-jupyterlab-notebooks.html) | 视频 | 了解Data Science Workspace中的JupyterLab。 |
| 2021 年 1 月 12 日 | [创建合并策略](https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/create-merge-policies.html) | 视频 | 了解如何在Adobe Experience Platform中创建合并策略。 |

## ![图标](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

凭借 Adobe Experience Platform，可以实时智能化预测每位客户的需求，从而实现跨体验渠道大规模编排客户历程。

### 最新产品版本

在[Journey Orchestration发行说明](https://docs.adobe.com/content/help/zh-Hans/journeys/using/release-notes/release-notes.html)中进一步了解最新功能、改进和修复。

### Journey Orchestration 的新课程和教程

过去一个月发布的新视频、教程及课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 1 月 22 日 | [跳到另一个旅程](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/building-a-journey/jumping-to-another-journey.html) | 视频 | 了解如何将个人从一个旅程推送到另一个旅程。 |

### 更多用于Journey Orchestration的资源

[文档](https://docs.adobe.com/content/help/zh-Hans/journeys/using/journey-orchestration-home.html) - [发行说明](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html) - [操作方法视频](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

## ![图标](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

发行日期：**2021 年 1 月 14 日**

* [Adobe Analytics 中的新增功能](#aa-features)
* [Customer Journey Analytics 的新增功能](#cust-journey)
* [Adobe Analytics 中的修复](#aa-fixes)
* [Analytics 管理员的重要注意事项](#aa-notices)
* [Analytics 课程及教程](#tutorials-analytics)
* [AppMeasurement](#appm)

### Adobe Analytics 中的新增功能 {#aa-features}

| 功能 | [正式发布](https://docs.adobe.com/content/help/zh-Hans/analytics/landing/an-releases.html) - 目标日期 | 描述 |
| ----------- | ---------- | ------- |
| Analysis Workspace - 组件选择 | 2021 年 2 月 4 日 | 在 [!UICONTROL Quick Insights] 中找到的下拉组件/拖放区域组件，已添加到 [!UICONTROL Workspace] 中的所有拖放区域。通过这项增强功能，您可以从兼容组件的下拉列表中进行选择，也可以继续将空间用作拖放区域。有关视频教程，请参阅Analysis Workspace中的[“媒体并发查看器面板”。](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/using-panels/media-concurrent-viewers-panel-in-analysis-workspace.html?lang=en#analysis-workspace) |
| 分析仪表板语言选择 | 2021 年 1 月 14 日 | 您现在可以在“分析”仪表板中选择一种语言。 |

### Customer Journey Analytics 的新增功能 {#cust-journey}

| 功能 | [正式发布](https://docs.adobe.com/content/help/en/analytics/landing/an-releases.html) - 目标日期 | 描述 |
| ----------- | ---------- | ----- |
| Analysis Workspace - 组件选择 | 2021 年 2 月 4 日 | 在 [!UICONTROL Quick Insights] 中找到的下拉组件/拖放区域组件，已添加到 [!UICONTROL Workspace] 中的所有拖放区域。通过这项增强功能，您可以从兼容组件的下拉列表中进行选择，也可以继续将空间用作拖放区域。有关视频教程，请参阅Analysis Workspace中的[“媒体并发查看器面板”。](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/using-panels/media-concurrent-viewers-panel-in-analysis-workspace.html?lang=en#analysis-workspace) |
| CJA API | 2021 年 2 月 18 日 | CJA API现已可用。 这些API允许您以编程方式编辑组件和检索报表。 有关详细信息，请参阅CJA API文档（链接如下）。 |

### Adobe Analytics 中的修复 {#aa-fixes}

* 修复了导致将Adobe Analytics 2.0 API网关超时增加到300秒（5分钟）的问题。 (AN-232335)
* 修复了Workspace、API 2.0和Adobe Report Builder报告(AN-245644、AN-244504、AN-243060)的性能问题
* 修复了在Analytics [!UICONTROL 数据馈送]中单击&#x200B;**添加**&#x200B;时导致错误的问题。 (AN-243171)
* 修复了分类不分类数据的问题。 (AN-243823、AN-247049、AN-244114)
* 修复了计划项目的问题：客户只能看到他们拥有的项目，但不能看到所有计划项目(AN-246955)
* 修复了[!UICONTROL Workspace]中的A4T面板导致项目未打开的问题。 (AN-246881)
* 修复了[!UICONTROL Workspace]引发与A4T [!UICONTROL 计算量度]相关的错误的问题。 (AN-247082)
* 修复了Data warehouseAPI请求不返回数据的问题。 (AN-236931)
* 修复了仅在访问父报表包的同时才能访问虚拟报表包的问题。 (AN-247042)
* 修复了将项目从[!UICONTROL Ad Hoc Analysis]转换为[!UICONTROL Workspace]时导致错误的问题。 (AN-221215)
* 修复了在[!UICONTROL Workspace Project Manager]中显示的筛选项目数量不正确的问题。 (AN-244934)

#### 其他 Adobe Analytics 修复

AN-224987;AN-229009;AN-239750;AN-239765;AN-241620;AN-242996;AN-243577;AN-243774;AN-244509;AN-244746;AN-244763;AN-244868;AN-244960;AN-245016;AN-245097;AN-245727;AN-246141;AN-246283;AN-246340;AN-246532;AN-246669;AN-246744;246763;AN-246892;AN-246898;AN-246961;AN-247643;AN-247048;AN-247134;AN-247758;AN-247774;AN-248179;AN-248226;AN-248297;AN-248300;AN-248303;AN-248376;AN-248495;AN-248647

### [!DNL Analytics] 管理员的重要注意事项 {#aa-notices}

| 注意事项 | 添加或更新日期 | 描述 |
| ----------- | ---------- | ---------- |
| Ad Hoc Analysis 生命周期终止 | 2021年1月 | [!UICONTROL 临时] 分析将于2021年3月1日终止。有关更多信息，请参阅[探索工作区](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)。 |
| 三种 Analytics API 服务的生命周期终止 | 2021 年 1 月 6 日 | 2021 年 4 月 30 日，以下旧版 Analytics API 服务将达到其生命周期终止日期，并将停止使用。当前任何使用这些服务构建的集成都将在当日停止工作。<ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>旧版 OAuth 身份验证（OAuth 和 JWT）</li></ul>我们提供了[旧版 API EOL 常见问题解答](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)，以帮助回答您的问题并提供有关如何继续的指导。使用这些服务的 API 集成可以迁移到 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 或 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。旧版 OAuth 帐户可迁移到 [Adobe IO](https://console.adobe.io/home?mv=email#) Analytics 集成帐户，该帐户可用于访问 1.4 Analytics API 和 2.0 Analytics API。 |
| Adobe Data Connectors 生命周期终止 | 2020 年 7 月 13 日 | Adobe [!UICONTROL Data Connectors] 由传统技术提供支持，而这些技术不再可行或不再受支持。[AdobeExchange合作伙伴项目](https://partners.adobe.com/exchangeprogram/experiencecloud)中提供了新标准。 您可以将该标准用于任何集成，以便继续提供和支持。 正式终止日期为2021年8月1日。 [了解更多...](https://docs.adobe.com/content/help/zh-Hans/analytics/import/dataconnectors/data-connectors-eol.html) |
| 将 HSTS 头添加到所有传入的 HTTPS 请求 | 2020 年 9 月 29 日 | 2020年9月29日，Adobe开始向所有使用HTTPS的传入请求添加HSTS头。 此标头指示浏览器或客户端在HTTPS中发出所有将来的请求，这被认为是安全最佳实践。 此时，Adobe不会对使用HTTP的传入请求强制执行此操作。 |
| 更改为 [!UICONTROL Experience Cloud ID 服务] Cookie 设置 | 2020 年 9 月 22 日 | Chrome 版本 80 隐私设置的更新，影响了 Adobe Analytics 跟踪某些查看 Google AMP 页面的用户的能力。具体而言，这项更新阻止跨域跟踪那些查看 Google 托管的 AMP 页面的用户。结果可能会导致独特访客数量激增。修复方法：用户可通过更改其 ECID Cookie 的设置来解决此问题。<br>目前，Analytics 在设置 Experience Cloud ID 服务 (ECID) Cookie 时，使用的是 Chrome 版本 80 之前允许跨域跟踪的设置`SameSite = Lax`。现在情况已发生了变化。此项更改允许用户将 ECID Cookie 的 SameSite 设置更新为 `None`。<br>此更改允许在更多情况下共享Analytics Cookie，但Analytics Cookie不包含敏感信息。此外，在选择这项设置时，必须将 Cookie 设置为 `Secure`，以便数据只能通过 HTTPS 连接进行传递。如果您要进行此更改，受支持的用户可以在客户关怀中打开票证。 |

### AppMeasurement {#appm}

有关 AppMeasurement 版本的最新更新，请参阅[适用于 JavaScript 的 AppMeasurement 发行说明](https://docs.adobe.com/content/help/zh-Hans/analytics/implementation/appmeasurement-updates.html)。

### Analytics 的课程及教程 {#tutorials-analytics}

[!DNL Analytics] 和 [!UICONTROL Customer Journey Analytics] 中的新课程、教程和文章。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 2 月 8 日 | [将趋势线添加到行可视化](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/visualizations/adding-trendlines-to-line-visualizations.html?lang=en) | 视频 | 在“可视化设置”中，您可以选择向行序列添加回归或移动平均趋势线。 此功能有助于在数据中描绘更清晰的图案。 |
| 2021 年 2 月 8 日 | [在Platform Launch中添加实施插件](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/implementation/via-adobe-launch/adding-implementation-plug-ins-in-launch.html?lang=en#implementation) | 视频 | 实施插件是JavaScript代码片段，您可以将这些代码添加到Analytics实施中以跟踪其他自定义数据。 在此视频中，了解如何在Platform Launch中添加代码以及在何处添加代码。 |
| 2021 年 1 月 6 日 | [Analysis Workspace 中的“媒体并行查看者”面板](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/using-panels/media-concurrent-viewers-panel-in-analysis-workspace.html?lang=en#analysis-workspace) | 视频 | 了解高峰期并发或中断发生的地方。 获得有关内容质量和查看者参与度的宝贵洞察，并帮助进行批量和规模故障排除或规划。 |

### Analytics 帮助资源

* [Adobe Analytics 产品文档及教程](https://experienceleague.corp.adobe.com/docs/analytics.html)

## ![图标](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Audience Manager中的新增功能、修复、文档和教程。

| 功能 | 添加或更新日期 | 描述 |
|----|----|----|
| [Audience Manager用户迁移到Admin Console](https://experienceleague.adobe.com/docs/audience-manager/user-guide/features/administration/admin-console-migration.html) | 2020 年 2 月 1 日 | Audience Manager用户帐户管理正转向Adobe Admin Console，以在整个Adobe解决方案中实现更流畅的体验。 <br>请按照本文中所述的步骤操作，以便于用户迁移。所有Audience Manager管理员应开始尽快将其用户帐户迁移到Adobe Admin Console。 |

### 修复和改进 {#aam-fixes-and-improvements}

* 修复了[入门状态报告](https://experienceleague.adobe.com/docs/audience-manager/user-guide/reporting/onboarding-status-report.html)中的问题。 在此问题中，报表中的记录与由入职合作伙伴上传的文件中的记录存在差异。 (AAM-57415)
* 修复了在&#x200B;**[!UICONTROL 预测受众]**&#x200B;功能中克隆&#x200B;**[!UICONTROL 模型]**&#x200B;的问题。 (AAM-56775)
* 修复了重复特征和区段时，错误特征或区段会重复的问题。 (AAM-57351)
* 修复了&#x200B;**[!UICONTROL 模型>排除特征]**&#x200B;中的&#x200B;**[!UICONTROL 全选]**&#x200B;复选框对用户无法点击的问题。 (AAM-57366)
* 修复了&#x200B;**[!UICONTROL 区段生成器]**&#x200B;中&#x200B;**[!UICONTROL 全选]**&#x200B;复选框不会选择所有特征的问题。 (AAM-55640)

### Audience Manager 的课程及教程{#tutorials-aam}

发布的关于 Audience Manager 的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 2 月 5 日 | [获取基于文件的数据的步骤](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/integrating-offline-data/steps-for-ingesting-file-based-data.html?lang=en#integrating-offline-data) | 视频 | 了解将离线数据载入Audience Manager时必须考虑的步骤，包括数据文件的文件名要求。 |
| 2021 年 2 月 5 日 | [格式化和摄取基于文件的数据](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/integrating-offline-data/formatting-and-ingesting-file-based-data.html?lang=en#integrating-offline-data) | 视频 | 在将第一方数据引入Audience Manager以更好地了解和目标客户时，数据存在某些格式要求。 了解一些主要选项以及获取更多信息的位置。 |
| 2021 年 2 月 5 日 | [创建跨设备数据源和验证](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/setup-and-admin/data-sources/creating-a-cross-device-data-source-and-authenticating.html?lang=en#setup-and-admin) | 视频 | 了解如何创建跨设备数据源，以在将第一方CRM数据引入Audience Manager时存储CRM ID和数据。 此视频向您介绍如何执行此操作，并在登录Experience Platform Launch中设置`setCustomerIDs()`方法。 |
| 2021 年 2 月 3 日 | [课程介绍 — 在Audience Manager中创建和管理数据激活](https://video.tv.adobe.com/v/331001) | 视频 | 受众细分不值钱，除非您真的对它们有所行动。 本课程教您如何使用受众自定义用户体验。 此介绍视频可帮助您开始学习。 |
| 2021 年 1 月 28 日 | [特征创建和管理](https://experienceleague.adobe.com/?recommended=AudienceManager-U-1-2020.3) | 课程 | 了解从内部产品[!UICONTROL 特征生成器]到[!UICONTROL 批量管理]工具创建和组织特征的全过程。 还了解如何使用[!UICONTROL Data Explorer]工具发现进入Audience Manager的重要信号并为它们创建特征。 |
| 2021 年 1 月 22 日 | [使用Audience Optimization报告了解媒体性能](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/reports/using-audience-optimization-reports-to-understand-media-performance.html?lang=en#reports) | 视频 | 了解如何使用Audience Optimization报表来改进活动，了解在哪里投资营销资金以及在哪里停止投资。 还了解如何确定最佳频率上限并在这些报告中找到其他重要功能。 |
| 2021 年 1 月 15 日 | [了解重叠报表的相关受众](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/reports/understand-related-audiences-with-overlap-reports.html?lang=en#reports) | 视频 | 重叠报表允许您查看特征和细分受众如何相互重叠(多个特征或细分中的相同访客)，以便您了解可以在何处处理数据以提高转化率或专注于扩大受众范围。 |
| 2021 年 1 月 12 日 | [使用数据导出标签控制数据流](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/data-activation/destinations-basics/using-data-export-labels-to-control-data-flow.html?lang=en#data-activation) | 视频 | “数据导出标签”为您提供了一种Audience Manager机制，用于控制不同数据类型/源的流，以便满足您的隐私要求。 了解如何设置“数据导出控件”和“数据导出标签”，并在何处设置，以配合此工作。 |
| 2021 年 1 月 22 日 | [将区段从Adobe Analytics导入Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/import-aa-segments-into-aam.html?lang=en#build-and-manage-audiences) | 视频 | 除了将实时数据从Adobe Analytics转发到Audience Manager之外，您还可以将包括Analytics的后处理数据的细分通过Experience Cloud导入Audience Manager。 |

## ![图标](/assets/aem.png) Adobe Experience Manager {#aem}

 Experience Manager 的新增功能、修复和更新。Adobe 建议那些采用内部部署的客户部署最新的修补程序，以便确保获得更高的稳定性、安全性和性能。

>[!NOTE]
>
>Adobe建议访问[Experience Manager发布更新和路线图](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html)页面，以保持最新的发布信息。

### 产品版本

* **Experience Manager as a Cloud Service**

   Experience Manager作为Cloud Service的新增功能

   * **Experience Manager Assets as a Cloud Service**

      * **无外设内容管理服务**

         * [内容片段投放的GraphQL API](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/admin/graphql-api-content-fragments.html):能够使用GraphQL语法查询内容片段，并基于内容片段模型的模式，以JSON格式输出。
         * [GraphQL API请求的身份验证支持](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/admin/graphql-authentication-content-fragments.html):能够使用服务器端API的访问令牌验证GraphQL API请求。
         * [RemotePage组件](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/developing/hybrid/remote-page.html):增加了在AEM中使用查看和编辑外部SPA的支持。
         * [在AEM中编辑外部SPA](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/developing/hybrid/editing-external-spa.html):添加了将独立的单页应用程序上传到AEM实例、添加内容的可编辑部分以及启用创作的功能。
         * GraphQL API的增强JSON输出，包括以JSON格式和区域设置输出富文本的功能。
         * 支持嵌套内容片段模型，以允许通过多行文本字段中内嵌的专用内容片段引用数据类型或内容片段引用创建嵌套内容片段结构。
         * 内容片段模型数据类型中提供的更多验证规则，包括“唯一”、“必需”和“可翻译”。
         * 可标记内容片段模型，并允许在文件夹中按标记或路径创建包含策略的内容片段。
         * 内容片段编辑器中的可用性增强功能，包括发布操作和片段所基于的模型的显示。
         * 能够直接在内容片段编辑器中预览JSON输出。
      * **渐进式Web应用程序(PWA)**

         * [现在，可以通过简单配置在项目](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/authoring/features/enable-pwa.html?lang=en) 级别启用网站的渐进式Web应用程序(PWA)版本。
   * **Experience Manager资产作为Cloud Service**

      * Experience Manager作为Cloud Service扩展了智能标记功能，以支持在基于文本的资产中识别关键字和实体。 文本将被识别、索引，并作为元数据提供，以改进搜索体验，而无需任何配置。 请参阅[智能标签](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/manage/smart-tags.html)。
      * 现在支持MXF文件格式。 请参阅[支持的文件格式](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/file-format-support.html#video-formats)。
   * **Experience Manager Commerce as a Cloud Service**

      * **新增功能?**

         * 产品体验管理：资产和体验片段的新“商务”属性选项卡。 通过此选项卡，您可以将产品/类别关联到资产和体验片段。 该选项卡还显示链接的产品/类别的实时数据，以及在产品控制台中显示详细信息的链接。
         * 已发布CIF委内瑞拉参考站点 — 2021.02.02，其中包括最新的CIF核心组件版本v1.7.0。有关更多详细信息，请参阅[CIF委内瑞拉参考站点](https://github.com/adobe/aem-cif-guides-venia/releases/tag/venia-2021.02.02)。
         * 已发布CIF核心组件v1.7.0。有关更多详细信息，请参阅[CIF核心组件](https://github.com/adobe/aem-core-cif-components/releases/tag/core-cif-components-reactor-1.7.0)。
      * **SDK Build Analyzers**

         Experience Manager作为Cloud Service SDK Build Analyzer Maven插件可检测特定项目中的问题，包括缺少依赖项。 它为开发人员提供了在本地开发过程中发现问题的机会，而远在使用Cloud Manager部署到云环境之前。

         为此版本添加了两个新分析器：

         * 重点分析器
         * bundle-nativecode

         有关详细信息，请参阅文档[此处](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/developing/archetype/build-analyzer-maven-plugin.html#developing)。
   * **云过渡工具**

      * **内容传输工具的新增功能**

         * 内容传输工具 — 用户映射工具新增功能和UI。 此功能会自动将现有用户和用户组映射到其AdobeIdentity Management系统ID，作为内容迁移活动的一部分。
请参阅[使用用户映射工具](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-user-mapping-tool.html)。
         * 内容传输工具现在可迁移迁移集中引用的所有组和用户，包括子项。
         * 在创建迁移集时，允许用户选择`/etc`下的某些路径。







### **社区**

* **Adobe Developers Live 2021 |完整会话列表**

   根据常用请求，[此处](https://adobe.ly/3cldljt)是在Adobe Developers Live中发生的所有Experience Manager会话的汇总列表。 每个会话的所有录制内容和问题与答案都将发布到其各自的上下文线程中。

* **列表Experience League上的最新Adobe Experience Manager内容 | 2021年1月**

   由Adobe制作的数字体验技术内容的官方来源。 请参阅完整列表[此处](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/list-of-latest-adobe-experience-manager-content-on-experience/m-p/377452#M27156)。

### Experience Manager 发行信息

所有的 Experience Manager 发行说明均保留在以下页面：

* [Experience Manager 版本更新和路线图](https://docs.adobe.com/content/help/en/experience-manager-release-information/aem-release-updates/home.html)
* [Experience Manager作为Cloud Service发布信息](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-service/release-notes/home.html)
* [Experience Manager Cloud Manager发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [自动化表单转换服务发行说明](https://docs.adobe.com/content/help/zh-Hans/aem-forms-automated-conversion-service/using/release-notes.html)
* [Experience Manager 6.5 Service Pack发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
* [Experience Manager 6.4 Cumulative Fix Pack发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-64/release-notes/cfp-release-notes.html)
* [Experience Manager资产Dynamic Media发行说明](https://docs.adobe.com/content/help/zh-Hans/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Experience Manager Brand Portal发行说明](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=zh-Hans)
* [Experience Manager桌面应用程序发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-desktop-app/using/release-notes.html)
* [Experience Manager Dispatcher发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-dispatcher/using/getting-started/release-notes.html)
* [Livefyre 发行说明](https://docs.adobe.com/content/help/zh-Hans/livefyre/using/release-notes/c-rn.html)

### Experience Manager课程和教程

过去一个月发布的新视频、教程及课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 2 月 11 日 | [从外部应用程序以Cloud Service身份验证到AEM](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.1.aemcs) | 课程 | 了解外部应用程序如何使用[!UICONTROL 本地开发访问令牌]和[!UICONTROL 服务凭据]以编程方式通过HTTP验证Experience Manager为Cloud Service。 |
| 2021 年 2 月 11 日 | [与资产相关和与资产无关](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/authoring/relate-unrelate.html) | 视频 | 了解如何在Experience Manager中建立和管理资产之间的关系。 |
| 2021 年 2 月 8 日 | [AEM Sites - WKND教程](https://docs.adobe.com/content/help/en/experience-manager-learn/getting-started-wknd-tutorial-develop/overview.html) | 教程 | 欢迎使用为初次接触Experience Manager的开发人员设计的多部分教程。 本教程将介绍如何为WKND这个虚构生活方式品牌实施Experience Manager站点。 |
| 2021 年 2 月 1 日 | [创建您的第一个OSGi捆绑包](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/create-your-first-osgi-bundle.html?lang=en) | 文章 | 了解如何使用maven和eclipse创建您的第一个OSGi捆绑包。 |
| 2021 年 2 月 1 日 | [发布资产](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/sharing/publish.html) | 视频 | 了解如何将资产及其演绎版从Experience Manager作者发布到AEM发布。 |
| 2021 年 2 月 4 日 | [本地开发](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/basics/local-development-environment.html) | 视频 | 了解如何使用Experience Manager作为Cloud Service SDK下载和设置本地开发环境。 |
| 2021 年 2 月 4 日 | [项目结构](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/basics/project-structure.html) | 视频 | 探索将AEM作为Cloud Service组织为Experience Manager Maven项目的最佳实践。 |
| 2021 年 2 月 4 日 | [迁移调度程序配置](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/basics/dispatcher-configuration.html) | 视频 | 概述Dispatcher配置中的差异，以及将Dispatcher从Adobe Managed Services(AMS)迁移到Experience Manager作为Cloud Service的提示和技巧。 |
| 2021 年 2 月 2 日 | [AEM SDK简介](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/basics/aem-sdk.html) | 视频 | 将SDK用于Experience Manager并配置为Cloud Service。 |
| 2021 年 2 月 2 日 | [什么是AEM Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/introduction/what-is-aem-as-a-cloud-service.html) | 视频 | 了解什么是Experience Manager，以及它与其他Adobe Experience Manager版本有何不同。 |
| 2021 年 2 月 2 日 | [Cloud Manager的角色](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/introduction/cloud-manager.html) | 视频 | 了解[!UICONTROL Cloud Manager]的用途以及它如何将Experience Manager作为Cloud Service使用。 |
| 2021 年 2 月 2 日 | [AEM作为Cloud Service的发展](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/introduction/evolution.html) | 视频 | 探索Experience Manager的历史以及内部部署Experience Manager、Adobe Managed Services AEM和Experience Manager作为Cloud Service之间的差异。 |
| 2021 年 2 月 2 日 | [AEM as a Cloud Service 的架构](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/introduction/architecture.html) | 视频 | 探索底层架构和重要的Experience Manager片段作为Cloud Service。 深入了解Cloud Manager和API。 |
| 2021 年 2 月 2 日 | [使用Cloud Manager API](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/cloud-manager-apis.html) | 视频 | 了解如何使用Cloud Manager API扩展并与其他系统集成。 |
| 2021 年 2 月 2 日 | [分析测试结果](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/analyze-test-results.html) | 视频 | 浏览代码中的任何编译错误，以及此代码是否遵循将Experience Manager作为Cloud Service的最佳实践 |
| 2021 年 2 月 2 日 | [配置管道](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/configure-pipelines.html) | 视频 | 在Cloud Manager中探索不同类型的管道，以及如何为成功的项目配置这些管道。 |
| 2021 年 2 月 2 日 | [管理调度程序配置](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/dispatcher-configurations.html) | 视频 | 使用最佳实践和示例来探索调度程序如何将Experience Manager作为Cloud Service和Cloud Manager与Dispatcher一起使用。 |
| 2021 年 2 月 2 日 | [Continuous Integrations和Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/continuous-integration.html) | 视频 | 使用Adobe Cloud Manager了解最佳实践和持续集成。 |
| 2021 年 2 月 2 日 | [使用Cloud Manager合并AEM项目以进行部署](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/merge-projects.html) | 视频 | 了解如何将多个项目合并到单个项目中，以便使用Cloud Manager作为Cloud Service部署到Experience Manager。 |
| 2021 年 2 月 2 日 | [部署Cloud Manager项目](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/deploy-code.html) | 视频 | 将云管理器git存储库与外部git存储库集成，并将项目部署到Experience Manager作为Cloud Service。 |
| 2021 年 2 月 2 日 | [内容发布](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/basics/content-publishing.html) | 视频 | 了解作为Cloud Service在Experience Manager中进行内容发布的工作方式，包括内容分发和Adobe管道的概念。 |
| 2021 年 2 月 2 日 | [基于令牌的身份验证 — 服务凭据](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/authentication/service-credentials.html?lang=en#authentication) | 视频 | 了解基于令牌的身份验证，以将Experience Manager作为Cloud Service集成。 |
| 2021 年 2 月 2 日 | [签署多个Forms](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/sign-multiple-documents/introduction.html?lang=en#sign-multiple-documents) | 教程 | 无论您是申请抵押贷款，还是开立新的银行帐户，都需要填写和签署多个表单。 Experience Manager Forms与Adobe Sign之间的集成使您能轻松填写和签署多个表单。 |
| 2021 年 1 月 28 日 | [基于令牌的身份验证 — 本地开发访问令牌](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/authentication/local-development-access-token.html?lang=en#authentication) | 视频 | 了解Experience Manager的开发人员控制台如何允许开发人员自行生成临时访问令牌，这些临时可用于有计划地访问Experience Manager。 |
| 2021 年 1 月 28 日 | [将AEM作为Cloud Service进行基于令牌的身份验证](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/authentication/overview.html?lang=en#authentication) | 视频 | 了解外部应用程序如何使用访问令牌通过HTTP作为Experience Manager，以编程方式验证身份并与其交互。 |
| 2021 年 1 月 24 日 | [创建主表单以触发进程](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/sign-multiple-documents/create-initial-form.html) | 文章 | 初始表单（再融资表单）用于通过触发[!UICONTROL 多重Forms AEM]工作流对多个表单进行签名。 |
| 2021 年 1 月 8 日 | [Adobe Cloud Manager CI/CD生产管道执行](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/cicd-production-pipeline.html) | 视频 | CI/CD生产管道配置定义启动管道的触发器、控制生产部署的参数以及性能测试参数。 |
| 2021 年 1 月 8 日 | [Adobe Cloud Manager活动](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/activity.html) | 视频 | Cloud Manager为项目活动提供整合视图，列出所有CI/CD管道执行，包括生产和非生产。 此功能允许用户视图当前进行中的任何管道并查看以前的部署。 |
| 2021 年 1 月 8 日 | [Adobe Cloud Manager CI/CD非生产渠道](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/cicd-non-production-pipeline.html) | 视频 | CI/CD非生产管道分为两个类别、代码质量管道和部署管道。 代码质量将管道来自Git分支的所有代码，以根据Cloud Manager的代码质量扫描构建和评估。 |
| 2021 年 1 月 8 日 | [Adobe Cloud Manager CI/CD生产管道配置](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/cicd-production-pipeline.html) | 视频 | CI/CD生产管道配置定义启动管道的触发器、控制生产部署和性能测试参数的参数。 |
| 2021 年 1 月 8 日 | [Adobe Cloud Manager环境](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/environments.html) | 视频 | Cloud Manager环境由Experience Manager作者、Experience Manager发布和调度程序服务组成。 不同的环境支持角色，并可使用不同的CI/CD管道参与。 Cloud Manager环境通常具有一个生产环境、一个阶段环境和一个开发环境。 |
| 2021 年 1 月 8 日 | [无外设图形QL概述](https://internal.adobedemo.com/content/demo-hub/en/demos/internal/aem-headless-graphql.html) | 演示 | Experience Manager的GraphQL API将Experience Manager内容片段中的内容公开到下游应用程序。 GraphQL API可用于无外设和混合用例。 |
| 2021 年 1 月 8 日 | [Adobe Cloud Manager项目](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/programs.html) | 视频 | Cloud Manager项目表示支持业务计划的逻辑集的一组Experience Manager环境，通常对应于购买的服务级别协议(SLA)。 |
| 2021 年 1 月 8 日 | [基于令牌的身份验证](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/authentication/overview.html?lang=en#authentication) | 视频 | Cloud Manager项目表示支持业务计划的逻辑集的一组Experience Manager环境，通常对应于购买的服务级别协议(SLA)。 |
| 2021 年 1 月 8 日 | [批量导入](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/bulk-import.html) | 视频 | Experience Manager作为Cloud Service的批量导入工具使管理员能够以安全、高效的方式从云存储(Azure Blob存储或Amazon S3)批量导入资源。 |

### 其他帮助资源用于Experience Manager

* [Experience Manager作为Cloud Service参考线](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-service/landing/home.html)
* [Experience Manager 6.5学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-5.html)
* [Experience Manager 6.4学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-4.html)
* [Experience Manager 6.3学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-3.html)
* [Experience Manager 6.2学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-2.html)
* [Cloud Manager 用户指南](https://helpx.adobe.com/cn/experience-manager/cloud-manager/user-guide.html)
* [旧版Experience Manager文档](https://helpx.adobe.com/cn/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic 帮助主页](https://docs.adobe.com/content/help/zh-Hans/dynamic-media-classic/using/home.html)

## ![图标](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign 提供了一种直观、自动的方式，以通过在线和离线营销渠道来交付一对一的消息。您现在可以利用根据客户习惯和喜好所决定的体验，来预测客户的需求。

### 最新产品版本

进一步了解发布的最新功能、改进和修复：

* [Campaign Standard 发行说明](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/release-notes/release-notes.html)
* [Campaign Classic 发行说明](https://docs.adobe.com/content/help/zh-Hans/campaign-classic/using/release-notes/latest-release.html)

### Campaign 的新课程和教程

过去一个月发布的新视频、教程及课程。

| 发布日期 | 名称 | 解决方案 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 2 月 5 日 | [面向商业用户的Adobe Campaign Classic快速入门](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.classic) | Campaign Classic | 完成本课程后，您将了解Adobe Campaign Classic的概念并了解如何创建您的第一个营销活动。 |
| 2021 年 2 月 1 日 | [介绍多渠道和跨渠道](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/orchestration/introduction-to-cross-and-multi-channel-campaigns.html) | Campaign Classic | 了解多渠道和跨渠道活动之间的差异，以及多渠道和跨渠道活动的用例。 |
| 2021 年 2 月 1 日 | [创建SMS投放](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/sms-channel/create-a-sms-delivery.html) | Campaign Classic | 了解如何创建SMS投放。 |
| 2021 年 2 月 1 日 | [创建跨渠道活动](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/orchestration/cross-channel-campaigns.html) | Campaign Classic | 了解如何创建和执行跨渠道活动。 |
| 2021 年 1 月 29 日 | [使用对照组](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/use-control-groups.html) | Campaign Classic | 了解对照组的概念，了解如何将对照组用于投放。 |
| 2021 年 1 月 28 日 | [发送和验证验证](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/send-and-validate-proofs.html) | Campaign Classic | 了解如何发送和验证验证。 |
| 2021 年 1 月 28 日 | [设计可交付的电子邮件](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/design-emails-for-deliverability.html) | Campaign Classic | 了解如何应用可交付性最佳实践。 |
| 2021 年 1 月 28 日 | [创建和设计电子邮件投放](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/create-and-design-email-deliveries.html) | Campaign Classic | 了解创建电子邮件投放的过程，并了解如何设计和个性化电子邮件内容。 |
| 2021 年 1 月 27 日 | [创建事件触发的活动](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/getting-started/create-event-triggered-campaigns.html) | Campaign Classic | 了解如何创建事件触发的活动并了解其用途。 |

### 帮助资源

* Adobe Campaign Standard：[帮助中心](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/campaign-standard-home.html) - [发行说明](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [操作方法视频](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [发行计划](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/release-notes/release-planning.html) - [最新文档更新](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic：[帮助中心](https://docs.adobe.com/content/help/zh-Hans/campaign-classic/using/campaign-classic-home.html) - [发行说明](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html) - [操作方法视频](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)- [最新文档更新](https://docs.adobe.com/content/help/zh-Hans/campaign-classic/using/documentation-updates.html)
* Adobe Campaign 控制面板：[文档](https://docs.adobe.com/content/help/zh-Hans/control-panel/using/control-panel-home.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/control-panel/using/release-notes.html) - 有关 [Campaign Standard](https://docs.adobe.com/content/help/zh-Hans/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html)/[Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html) 的操作方法视频

## ![图标](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Adobe Advertising Cloud 的发行说明。

* [Advertising Cloud DSP 中的新增功能](#adcloud-dsp)
* [Advertising Cloud Search 中的新增功能](#adcloud-search)

### [!DNL Advertising Cloud DSP] 中的新增功能 {#adcloud-dsp} 

上次更新日期：**2020 年 10 月 28 日**

| 功能 | 描述 |
| -----------| ---------- |
| 新建帮助 | （10 月 28 日版）旧版帮助页面已替换为更新页面，这些更新页面可从 DSP 主菜单的“帮助”链接获取，也可随时从 [https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html](https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html) 获取。 |
| Campaigns | （10 月 28 日版）以前的 Campaigns 测试版视图现在成为默认的 Campaigns 视图，可以实现更快的分析、简化的工作流和自定义视图。 |
| 专用内容库 | （10 月 15 日版）如今，所有用户都可以使用新的交易 ID 表单来设置和编辑交易 ID 详细信息，该表单是旧版[!UICONTROL 智能广告投放]表单的简化版。要设置新的交易 ID 详细信息，请转到&#x200B;**[!UICONTROL 内容库 > 交易]**，单击&#x200B;**[!UICONTROL 创建]**，然后单击&#x200B;**[!UICONTROL 交易 ID 测试版]**。 |
| 投放预测 | （10 月 15 日版）在投放设置的[!UICONTROL 预测]部分，我们为具有投放级别步调的广告投放提供了一个新增的[!UICONTROL 估计的最大量]部分，它指明了当前目标配置中的可用容量。 |

### [!DNL Advertising Cloud Search] 中的新增功能 {#adcloud-search} 

上次更新日期：**2021 年 1 月 22 日，适用于 1 月 23 日版**

| 功能 | 描述 |
| -----------| ---------- |
| [!UICONTROL 搜索促销活动]<br>报表 | Advertising Cloud Search 不再报告 Microsoft Advertising 促销活动的新平均排名数据。“平均排名”列从 1 月 23 日开始显示零 (0) 值。这是为 Microsoft 在 2021 年 1 月弃用平均排名数据做准备。<br>1 月 22 日前收集的平均排名数据仍可在报告中使用。 |

### Ad Cloud 教程和课程

更新日期：**2020 年 12 月 2 日**

## ![图标](/assets/magento.png) [!DNL Magento] {#magento}

有关最新的发行信息，请参阅Magento Commerce和开放源[发行说明](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)。

## ![图标](/assets/target.png)[!DNL Target] {#target}

请参阅 [[!DNL Target]  发行说明](https://docs.adobe.com/content/help/zh-Hans/target/using/release-notes/target-release-notes.html)了解最新发行信息。

## ![图标](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] 是销售线索管理和B2B营销人员的一个完整应用程序，希望通过参与复杂购买旅程的每个阶段来转变客户体验。

### 核心 Marketo Engage 更新

请参阅 [!DNL Marketo Engage] [发行说明](https://docs.marketo.com/display/public/DOCS/Release+Notes)了解最新发行信息。

### 即将推出的功能

本季度将发布以下功能：

| 功能 | 描述 |
| ------ | --------- |
| [!DNL Bizible] | <ul><li>新的基于帐户的分段</li><li>保存特定于功能板的过滤器</li><li>将 Bizible 功能板导出为 PDF</li></ul> |
| Sales Connect | 撰写窗口和命令中心更新/增强功能 |

### 弃用

* **Asset API“_method”参数：** 2020 年 9 月之后，Asset API 端点将不再接受 `_method` 在 POST 正文中传递查询参数以绕过 URI 长度限制。
* **弃用 Internet Explorer 支持：**&#x200B;从 2020 年 7 月 31 日发行的 7 月版本开始，Internet Explorer 将不再支持 Marketo Engage 用户界面。

## ![图标](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

为 Adobe Document Cloud 发布的新视频、教程或课程。

### Acrobat 教程

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 2 月 8 日 | [Acrobat概述登陆](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html) | 学习中心 | 欢迎使用Adobe Acrobat学习中心。 您会发现专注于Adobe Acrobat的各种学习体验。 我们的教程、网络研讨会和使用案例旨在快速让初学者和高级用户了解Adobe Acrobat。 |

### Adobe Sign教程

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 2 月 8 日 | [概述登录 — 支持资产](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html) | 学习中心 | 欢迎使用Adobe Sign学习中心。 您将发现专注于Adobe Sign的各种学习体验。 我们的教程、网络研讨会和使用案例旨在让初学者和管理员快速掌握Adobe Sign。 |

有关 Document Cloud 的帮助，请参阅：

* [Adobe Acrobat 学习中心](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=zh-Hans)
* [Adobe Sign 学习中心](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=https://experienceleague.corp.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=zh-Hans)
* [Document Cloud 学习与支持](https://helpx.adobe.com/support/document-cloud.html)

## ![图](/assets/creative-cloud-24.png) 标Creative Cloud Enterprise  {#creative-cloud}

Creative Cloud Enterprise的新教程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 2 月 3 日 | [使用Photoshop创建Cinemagraph](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/cinemagraphps.html?lang=en#cceoverview) | 视频 | 了解如何通过将Adobe Stock的视频与Photoshop中巧妙的蒙版技术相结合，创建生动的照片。 |
| 2021年2月3日 | [使用Adobe Stock和Photoshop for iPad创建独特的复合图像](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/compositepsipad.html?lang=en) | 视频 | 了解如何通过重新设计的基于触摸的界面以全新方式使用您喜爱的Creative Cloud应用程序之一。 |
| 2021 年 2 月 3 日 | [使用Dimension和Adobe Stock自定义3D模型并为其添加品牌](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/3doverview/3dtutorials/3ddimensionstock.html?lang=en) | 视频 | 使用材料、环境属性、光照和摄影在Dimension中自定义和品牌化3D模型，为任何设计项目创建写实的影像。 |
| 2021 年 2 月 2 日 | [熟悉Adobe XD中的组件](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/xdoverview/components.html) | 视频 | 了解如何使用组件为您提供前所未有的灵活性，从而将速度和一致性应用于设计工作流程。 |
| 2021 年 2 月 2 日 | [掌握CGI中3D光照的技巧与技巧](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/3doverview/3dtutorials/mastering3dlighting.html?lang=en) | 文章 | 了解3D光照，以及如何创建能够完全改变计算机生成场景的不同光照条件以及对象在场景中的外观。 |
| 2021 年 2 月 2 日 | [使用3D渲染与合成创建逼真的虚拟摄影](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/3doverview/3dtutorials/photorealistic.html?lang=en#3doverview) | 文章 | 了解如何使用3D渲染与合成创建逼真的虚拟摄影。 |
| 2021 年 1 月 29 日 | [CCE快速参考指南](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/overview-ref.html) | 快速参考指南 | 访问快速参考指南，帮助您了解Creative Cloud中的新增功能。 |
