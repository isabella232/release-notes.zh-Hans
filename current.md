---
title: Adobe Experience Cloud 发行说明
description: Adobe Experience Cloud 发行说明
doc-type: release notes
last-update: November 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 73caf10aa872e7b98875bdd0b8050cc301e3d500
workflow-type: tm+mt
source-wordcount: '8005'
ht-degree: 99%

---


# Adobe Experience Cloud 发行说明 - 2020 年 11 月

![横幅](/assets/experience-cloud-banner-3.png)

此页面介绍了 [!DNL Adobe Experience Cloud] 中的新增功能、修复和重要声明。此外，还重点提供了可帮助您充分利用 Experience Cloud 的新文档、培训课程和视频教程。

>[!IMPORTANT]
>
>此页面可能包含某些产品的预发行内容，这些内容或许会在发行日期之前有所变更。请定期查看以获取最新信息。

>[!NOTE]
>
>若要通过电子邮件接收有关即将发行的版本的通知，请订阅 [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html)。

最近更新日期：**2020 年 12 月 2 日**

* [Adobe 系统状态](#status)
* [Experience Cloud 服务和管理](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Analytics](#analytics) 和 [Customer Journey Analytics](#cust-journey) (更新 **日期：2020年12月2日**)
* [Audience Manager](#aam)
* [Experience Manager](#aem)（更新日期：**2020 年 10 月 28 日**）
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)（更新日期：**2020 年 10 月 28 日**）
* [[!DNL Target]](#target)（更新日期：**2020 年 11 月 2 日**）
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo)
* [[!DNL Primetime]](https://docs.adobe.com/content/help/zh-Hans/primetime/release-notes/home.html)
* [Document Cloud](#doc-cloud)

需要帮助？请访问 [Adobe Experience League](https://experienceleague.adobe.com/#home)，查找产品和技术文档、Adobe 策划课程、视频教程、快速解答、社区洞察以及由讲师指导的培训。

>[!NOTE]
>
>Experience Cloud 文档正在迁移至 Experience League。在 10 月份，所有的发行说明、文章、视频和教程都将从其当前位置 (`docs.adobe.com`) 迁移至 Experience League。此次迁移可确保从一个位置提供所有的学习、自助、支持和社区内容。关于发生的这项变更，您无需执行任何操作，因为所有的链接都将重定向到 Experience League。我们会在实施转换时更新发行说明。

## ![图标](/assets/adobe.png) Adobe 系统状态 {#status}

[!UICONTROL Adobe 系统状态]提供关于 Adobe 云产品与服务中断和维护事件的详细信息、状态更新以及电子邮件通知。请访问 [status.adobe.com](https://status.adobe.com/) 查看。

未更新。

请参阅 [Adobe 系统状态 - 2020 年 5 月 21 日](https://docs.adobe.com/content/help/zh-Hans/release-notes/experience-cloud/previous/2020/05212020.html#status)，以了解最新版本信息。

## ![图标](/assets/ec_appicon_24.png) Experience Cloud 服务和管理 {#ecloud}

以前的 _Experience Cloud 核心服务_&#x200B;现在改称 [Experience Cloud 服务和管理](https://docs.adobe.com/content/help/zh-Hans/core-services/interface/experience-cloud.html)，其文档包括客户属性、受众库（[!UICONTROL 人员]服务）激活、用户和产品管理以及 Experience Cloud cookie。

未更新。

请参阅 [Experience Cloud 服务的发行说明汇总](https://docs.adobe.com/content/help/zh-Hans/core-services/interface/release-notes/release-notes.html)，以了解最新发行信息。

## ![图标](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

包括 Experience Platform 和 Experience Platform Launch 的发行更新信息。

发行日期：**2020 年 10 月 14 日**

有关以下项的更新，请参阅 [Experience Platform 发行说明](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)：

* 数据准备
* 实时客户资料
* 分段服务
* 源

### Experience Platform Launch

有关 Platform Launch 的更多信息，请参阅 [Experience Platform Launch 发行说明](https://docs.adobe.com/content/help/zh-Hans/launch/using/intro/release-notes/current.html)。

### Experience Platform 和服务教程及课程

发布的关于 Experience Platform 和服务的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 10 月 26 日 | [Offer Decisioning 简介](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/introduction-to-offer-decisioning.html) | 视频 | 此视频概述了 [!UICONTROL Offer Decisioning]，它是一项基于 Adobe Experience Platform 构建的应用程序服务。此视频涵盖 [!UICONTROL Offer Decisioning] 解决的业务挑战，以及它的主要功能、基本架构和主要用例。 |
| 2020 年 10 月 29 日 | [Offer Decisioning](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/demo-of-offer-decisioning.html?lang=zh-Hans) | 视频 | 此视频介绍各大品牌如何使用 Adobe 新的 [!UICONTROL Offer Decisioning] 服务来定义和管理优惠、利用实时客户数据，以及提供与客户预期相符的体验。 |
| 2020 年 9 月 14 日 | [Attribution AI 的商业价值](https://docs.adobe.com/content/help/en/platform-learn/tutorials/intelligent-services/business-value-of-attribution-ai.html) | 视频 | [!UICONTROL Attribution AI] 作为 [!UICONTROL Intelligent Services] 的一部分，是一种多渠道的算法归因服务，它计算客户交互对特定结果的影响和增量影响。利用 [!UICONTROL Attribution AI]，营销人员可以通过了解客户旅程各个阶段每个客户互动的影响来衡量和优化营销和广告支出。 |
| 2020 年 9 月 14 日 | [客户人工智能的商业价值](https://docs.adobe.com/content/help/en/platform-learn/tutorials/intelligent-services/business-value-of-customer-ai.html) | 视频 | 此视频展示了[!UICONTROL 客户人工智能]如何通过基于人工智能的倾向性来丰富客户档案，并支持客户细分和定位工作。 |
| 2020 年 9 月 14 日 | [Platform 和 Magento 的商业价值](https://docs.adobe.com/content/help/en/platform-learn/tutorials/experience-cloud/business-value-of-platform-and-magento.html) | 视频 | 此视频显示 Adobe Experience Platform 可与 [!DNL Magento] Commerce 一起使用来创建客户的单一视图，并在数字店面和各个渠道上智能地个性化体验。 |

## ![图标](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

凭借 Adobe Experience Platform，可以实时智能化预测每位客户的需求（无论其旅程通达何处），从而实现跨体验渠道大规模编排客户历程。

### Journey Orchestration 的其他资源

[文档](https://docs.adobe.com/content/help/zh-Hans/journeys/using/journey-orchestration-home.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/journeys/using/release-notes/release-notes.html) - [操作方法视频](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

## ![图标](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

发行日期：**2020 年 10 月 29 日**

* [Adobe Analytics 中的新增功能](#aa-features)
* [Customer Journey Analytics 的新增功能](#cust-journey) （更新日期：2020年12月2日）
* [Media Analytics 的新增功能](#media-aa)
* [Adobe Analytics 中的修复](#aa-fixes)
* [Analytics 管理员的重要注意事项](#aa-notices)
* [Analytics 课程及教程](#tutorials-analytics)
* [AppMeasurement](#appm)

### Adobe Analytics 中的新增功能 {#aa-features}

| 功能 | [正式发布](https://docs.adobe.com/content/help/zh-Hans/analytics/landing/an-releases.html) - 目标日期 | 描述 |
| ----------- | ---------- | ------- |
| Adobe Analytics 文档 | 2020 年 11 月 11 日 | Adobe Analytics 文档已迁移至 Experience League。在 11 月份，所有的文章、视频、发行说明和教程都已从其当前位置 (`docs.adobe.com`) 迁移至 `experienceleague.adobe.com`。此次迁移可确保从一个位置提供所有的学习、自助、支持和社区内容。所有链接都已重定向到 Experience League。 |
| [!UICONTROL 工作区][!UICONTROL 折线图]可视化图表：移动平均趋势线选项 | 2020 年 10 月 8 日 | 移动平均值已添加到[!UICONTROL 折线图]可视化图表的趋势线设置。移动平均值也称为滚动平均值，它使用特定数量的数据点（由[!UICONTROL 周期]选择确定)，对其求平均值，并将平均值用作折线中的点。[了解更多](https://docs.adobe.com/content/help/zh-Hans/analytics/analyze/analysis-workspace/visualizations/line.html) |
| [!UICONTROL 数据修复] API | 2020 年 10 月 8 日 | [!UICONTROL 数据修复] API 是一种从 Analytics 报表包中删除数据的工具。10 月版本包括的功能可以删除指定日期范围内的指定 eVars、props 和 [!UICONTROL Activity Map] 变量。将来将发布其他功能。使用[!UICONTROL 数据修复] API 会永久删除现有 Adobe Analytics 数据。我们建议采取谨慎的方法执行修复，以最大限度地减少意外删除。访问[!UICONTROL 数据修复] API 需要签订合同 - 请联系您的帐户团队以了解更多详细信息。[了解更多](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/data-repair.md) |
| [!UICONTROL 工作区]：性能帮助页面 | 2020 年 10 月 22 日 | [!UICONTROL Analysis Workspace] 性能帮助页面显示影响项目性能的不同因素，并提供有关性能优化提示的链接。[了解更多](https://docs.adobe.com/content/help/zh-Hans/analytics/analyze/analysis-workspace/workspace-faq/optimizing-performance.html) |
| 对 Analytics [!UICONTROL 仪表板] UI 的增强 | 2020 年 10 月 23 日 | 在[!UICONTROL 工作区]中构建移动记分卡时，记分卡的样式现在与移动端应用程序的样式一致。 |

### Customer Journey Analytics 的新增功能 {#cust-journey}

| 功能 | [正式发布](https://docs.adobe.com/content/help/zh-Hans/analytics/landing/an-releases.html) - 目标日期 | 描述 |
| ----------- | ---------- | ----- |
| Customer Journey Analytics 文档 | 2020 年 11 月 11 日 | Customer Journey Analytics 文档已迁移至 Experience League。在 11 月份，所有的文章、视频、发行说明和教程都已从其当前位置 (`docs.adobe.com`) 迁移至 `experienceleague.adobe.com`。此次迁移可确保从一个位置提供所有的学习、自助、支持和社区内容。所有链接都已重定向到 Experience League。 |
| [!UICONTROL 折线图]可视化图表：移动平均趋势线选项 | 2020 年 10 月 8 日 | 移动平均值已添加到折线图可视化图表趋势线设置。移动平均值计算指定前期的平均值并将其用作趋势线数据点，然后移动到下一个期间。[了解更多](https://docs.adobe.com/content/help/zh-Hans/analytics/analyze/analysis-workspace/visualizations/line.html) |
| 删除回填限制 | 2020 年 10 月 19 日 | 为了提供更好的 CJA 体验，我们删除了回填（历史数据导入）限制。以前，您自己最多可以回填 25 亿行，超出这个限制则需工程团队介入。现在，您自己即可不受任何限制地回填数据。[了解更多](https://docs.adobe.com/content/help/zh-Hans/analytics-platform/using/cja-connections/create-connection.html#enable-connection) |
| Analysis Workspace 性能帮助页面 | 2020 年 10 月 22 日 | Analysis Workspace 性能帮助页面显示影响项目性能的不同因素，并提供有关性能优化提示的链接。[了解更多](https://docs.adobe.com/content/help/zh-Hans/analytics/analyze/analysis-workspace/workspace-faq/optimizing-performance.html) |
| [!UICONTROL 逗留时间]量度和维度 | 2020 年 10 月 30 日 | [!UICONTROL 逗留时间]量度和维度可以让您从客户历程的各个方面，查看客户逗留的时间长短，从而更全面地了解各个渠道的参与情况和瓶颈。 |
| [!UICONTROL 设备]和[!UICONTROL 地理]维度 | 2020 年 10 月 30 日 | [!UICONTROL 设备]和[!UICONTROL 地理]维度现在默认情况下作为 [Adobe Analytics 源连接器](https://docs.adobe.com/content/help/en/platform-learn/tutorials/data-ingestion/ingest-data-from-adobe-analytics.html)中“全局查找支持”项目的一部分提供。在用户强烈要求下添加的这些维度增加了 [Adobe Analytics 与 CJA 之间的对等性](https://docs.adobe.com/content/help/zh-Hans/analytics-platform/using/cja-overview/cja-aa.html)。 |
| 历程 IQ：跨渠道分析 | 2020 年 12 月 11 日 | 历程 IQ：跨渠道分析功能允许客户为 Adobe Experience Platform 数据湖中的 Adobe Analytics（或其他）事件数据集重新生成键值，即，从一个 ID 命名空间的键值重新生成另一个 ID 命名空间的键值。通常，这意味着为事件数据集从基于 Cookie 的 ID 重新生成一个基于人员的 ID。按照这种方式，重新生成密钥的数据集可以同 CJA 连接中其他基于人员的数据相结合，从而在 Analysis Workspace 中实现跨设备/跨渠道分析。[了解更多](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-connections/cca/overview.html?lang=en#cja-connections) |

### [!UICONTROL Media Analytics] 的新增功能{#media-aa}

| 功能 | [正式发布](https://docs.adobe.com/content/help/zh-Hans/analytics/landing/an-releases.html) - 目标日期 | 描述 |
| ----------- | ---------- | ---------- |
| [!UICONTROL 工作区]中的“媒体并行查看者”面板 | 2020 年 9 月 17 日 | 通过[!UICONTROL 媒体并行查看者]面板，您可以了解出现并发峰值或发生锐减的位置。它为内容质量和查看者参与度提供了有价值的分析，同时有助于对批量/规模进行疑难问题解答或规划。[了解更多...](https://docs.adobe.com/content/help/zh-Hans/media-analytics/using/media-reports/media-workspace-panels/media-concurrent-viewers.html) |

### Adobe Analytics 中的修复 {#aa-fixes}

* 修复了涉及分类的划分问题；之前，如果量度具有分配模型，则此类划分无法正常工作。这种情况出现在报表包迁移到最新分类架构时。(AN-230364)
* 修复了将值粘贴到容器后区段 UI 中断的问题。(AN-233998)
* 修复了[!UICONTROL 数据馈送]作业历史记录中缺少某些每小时数据的问题。(AN-231776)
* 修复了复制计算量度时出现的问题。此问题导致出现错误消息“您未被授权使用此量度”。(AN-238070)
* 修复了在[!UICONTROL 工作区]中的[!UICONTROL 文本]可视化图表上，无法设置正确对齐方式的问题。(AN-238188)

#### 其他 Adobe Analytics 修复

AN-224702、AN-232791、AN-233982、AN-234384、AN-235608、AN-236538、AN-236598、AN-236738、AN-237434、AN-237672、AN-237850、AN-237943、AN-238081、AN-238508、AN-238527、AN-238536、AN-238619

### [!DNL Analytics] 管理员的重要注意事项 {#aa-notices}

| 注意事项 | 添加或更新日期 | 描述 |
| ----------- | ---------- | ---------- |
| 将 HSTS 头添加到所有传入的 HTTPS 请求 | 2020 年 9 月 29 日 | 2020 年 9 月 29 日，我们开始向所有使用 HTTPS 的传入请求添加 HSTS 头。这会指示浏览器/客户端在以后使用 HTTPS 发出所有请求，这被视为最佳安全实践。目前，我们不会对使用 HTTP 的传入请求强制执行此操作。 |
| 更改为 Experience Cloud ID 服务 Cookie 设置 | 2020 年 9 月 22 日 | Chrome 版本 80 隐私设置的更新，影响了 Adobe Analytics 跟踪某些查看 Google AMP 页面的用户的能力。具体而言，这项更新阻止跨域跟踪那些查看 Google 托管的 AMP 页面的用户。结果可能会导致独特访客数量激增。修复方法：用户可通过更改其 ECID Cookie 的设置来解决此问题。<br>目前，Analytics 在设置 Experience Cloud ID 服务 (ECID) Cookie 时，使用的是 Chrome 版本 80 之前允许跨域跟踪的设置`SameSite = Lax`。现在情况已发生了变化。此项更改允许用户将 ECID Cookie 的 SameSite 设置更新为 `None`。<br>请注意，它允许在更多的情况下共享 Analytics Cookie，但 Analytics Cookie 不包含敏感信息。此外，在选择这项设置时，必须将 Cookie 设置为 `Secure`，以便数据只能通过 HTTPS 连接进行传递。如果您要进行这项更改，请让受支持的用户通过客户关怀部门开具相关票证。 |
| 从 `omniture.com` 域迁移至 `adobe.com` 域 | 2020 年 8 月 21 日 | 2020 年 8 月 13 日，Adobe Analytics 将其前端架构从 `omniture.com|http://omniture.com/` 域迁移至 `adobe.com|http://adobe.com/` 域。这项变更可以缓解自 2020 年 5 月 28 日首次统一产品域更改以来引发的第三方 Cookie 问题。作为本次更新的结果，浏览器可能会提示用户信任这个新的 `.adobe.com|http://an.adobe.com/` 域或 `experience.adobe.com|http://experience.adobe.com/` 域。 |
| 关于 Ad Hoc Analysis 与 Java 8 兼容性的最新信息 | 2020 年 8 月 21 日 | Ad Hoc Analysis 目前与 Java 8 版本 1.8.0_261+ 不兼容。为了确保能够在这个工具[生命周期终止日期](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)之前持续访问该工具，我们建议您安装版本低于 1.8.0_261 的 Java 8。 |
| Adobe Data Connectors 生命周期终止 | 2020 年 7 月 13 日 | Adobe [!UICONTROL Data Connectors] 由传统技术提供支持，而这些技术不再可行或不再受支持。我们在 [Adobe Exchange 合作伙伴项目](https://partners.adobe.com/exchangeprogram/experiencecloud)中采用了一个新标准，任何希望继续提供和支持的集成应采用此标准。正式的生命周期终止日期仍有待确定，但我们预计将会在未来 12-18 个月（2021 年中至 2021 年底）后终止。[了解更多...](https://docs.adobe.com/content/help/zh-Hans/analytics/import/dataconnectors/data-connectors-eol.html) |
| Ad Hoc Analysis 生命周期终止 | 2018 年 8 月 6 日 | Adobe 宣布计划于 2021 年 3 月 1 日终止 Ad Hoc Analysis 生命周期。有关更多信息，请参阅[探索工作区](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)。 |

### AppMeasurement {#appm}

有关 AppMeasurement 版本的最新更新，请参阅[适用于 JavaScript 的 AppMeasurement 发行说明](https://docs.adobe.com/content/help/zh-Hans/analytics/implementation/appmeasurement-updates.html)。

### Analytics 的课程及教程 {#tutorials-analytics}

[!DNL Analytics] 和 [!UICONTROL Customer Journey Analytics] 中的新课程、教程和文章。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 10 月 8 日 | [自由格式表 - 进行分析的基础](https://video.tv.adobe.com/v/41766?captions=chi_hans) | 视频 | 了解您应该掌握的知识，以及在本课程中将会学到的知识。 |
| 2020 年 10 月 5 日 | [在 Analysis Workspace 中使用参与量度](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/building-freeform-tables/using-participation-metrics-in-analysis-workspace.html) | 视频 | 使用这一简单技巧，随时获取 [!UICONTROL Analysis Workspace] 中的任意参与量度。 |
| 2020 年 10 月 5 日 | [在 Analysis Workspace 中自动构建自由格式表](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/building-freeform-tables/auto-build-freeform-tables-in-analysis-workspace.html) | 视频 | 将组件直接放入空白项目、面板或自由格式表中，系统会按照建议的格式自动为您构建一个表。 |
| 2020 年 10 月 5 日 | [在自由格式表中使用量度](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/building-freeform-tables/working-with-metrics-in-a-freeform-table.html) | 视频 | 了解在自由格式表（位于 [!UICONTROL Analysis Workspace] 中）中可以使用量度的各种方式。 |
| 2020 年 9 月 21 日 | [Journey AI - 优化预测的发送时间](https://docs.adobe.com/content/help/zh-Hans/campaign-standard-learn/tutorials/communication-channels/email/journey-ai/predictive-send-time-optimization.html) | 视频 | 了解哪些工作流需要在 Adobe Campaign 和 Journey AI 模型之间同步数据。了解如何在个人用户档案级别查看发送时间得分以及如何使用发送时间公式执行电子邮件传递。 |

### Analytics 帮助资源

* [Adobe Analytics 教程](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics 产品文档](https://docs.adobe.com/content/help/zh-Hans/analytics/landing/home.html)

## ![图标](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Audience Manager 中的新增功能、修复、文档和教程。

发行日期：截至 **2020 年 10 月 8 日**

### Audience Manager 中的新增功能、增强功能和修复 {#aam-features}

| 功能 | 添加或更新日期 | 描述 |
|----|----|----|
| [预测受众](https://docs.adobe.com/content/help/zh-Hans/audience-manager/user-guide/features/algorithmic-models/predictive-audiences/predictive-audiences.html) | 2020 年 10 月 21 日 | <ul><li>**预测受众模型克隆**：现在，您可以克隆现有模型并根据需要更改其配置。有关更多信息，请参阅[克隆和编辑预测受众模型](https://docs.adobe.com/content/help/zh-Hans/audience-manager/user-guide/features/algorithmic-models/predictive-audiences/predictive-audiences-start.html#clone-predictive-audiences)。</li><li>**预测受众批次分类**：除了按不同角色类型对访客进行实时分类之外，现在，预测受众还支持批量分类，可以帮助您分类已参与用户并将其激活到批次目标。</li></ul> |
| [重叠报表](https://docs.adobe.com/content/help/zh-Hans/audience-manager/user-guide/reporting/interactive-and-overlap-reports/dynamic-reports.html) | 2020 年 10 月 23 日 | 我们更新了计算重叠报表的方法（[特征到特征](https://docs.adobe.com/content/help/zh-Hans/audience-manager/user-guide/reporting/interactive-and-overlap-reports/trait-trait-overlap-report.html)、[区段到特征](https://docs.adobe.com/content/help/zh-Hans/audience-manager/user-guide/reporting/interactive-and-overlap-reports/segment-trait-overlap-report.html)、[区段到区段](https://docs.adobe.com/content/help/zh-Hans/audience-manager/user-guide/reporting/interactive-and-overlap-reports/segment-segment-overlap-report.html)）。现在，重叠报表的计算是基于报表独特性和 MinHash 签名（而非 [1/54 的数据采样](https://docs.adobe.com/content/help/zh-Hans/audience-manager/user-guide/reporting/report-sampling.html#data-sampling-ratio)）。 |

### 修复和改进 {#aam-fixes-and-improvements}

* 修复了“预测受众”功能中即使没有区段映射到模型，某些用户也无法删除任何模型的问题。(AAM-55881)
* 修复了当特征或区段被用作已删除的预测受众模型的基准时，一些用户无法删除此类特征或区段的问题。(AAM-56476)
* 我们继续改进整个界面的无障碍功能。(AAM-53215)

### Audience Manager 的课程及教程{#tutorials-aam}

发布的关于 Audience Manager 的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 10 月 28 日 | [理解特征图中的数字](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/understanding-numbers-in-the-trait-graph.html?lang=zh-Hans#build-and-manage-audi) | 视频 | 获取相关提示，了解如何理解特征信息屏幕中报告的特征数字。 |
| 2020 年 10 月 23 日 | [规划 Analytics 数据的特征创建](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/planning-trait-creation-from-analytics-data.html?lang=zh-Hans#build-and-manage-audi) | 视频 | 了解一些提示和技巧，有助于您规划如何将 Adobe Analytics 数据用于 Audience Manager 中的特征。 |
| 2020 年 10 月 23 日 | [创建特征时选择数据源](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/choosing-a-data-source-when-creating-traits.html?lang=zh-Hans#build-and-manage-audi) | 视频 | 创建特征时需要填写的重要字段之一就是“数据源”字段。获得相关提示，了解如何为基于规则的特征和载入的特征选择正确的数据源。 |
| 2020 年 9 月 14 日 | [使用代码视图创建和编辑特征](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/using-code-view-to-create-and-edit-traits.html?lang=zh-Hans#build-and-manage-audien) | 视频 | 了解如何在创建新特征或编辑现有特征时使用代码视图。设置特征表达式时，代码视图是表达式生成器的一种替代方法。 |
| 2020 年 10 月 10 日 | [了解预测受众](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/understanding-predictive-audiences.html) | 视频 | 在此视频中，我们将讨论 Audience Manager 的预测受众，介绍其工作方式的详细信息以及相关用例。 |

## ![图标](/assets/aem.png) Adobe Experience Manager {#aem}

AEM 本月未更新。以下内容均来自上个月（新课程和新教程除外）。

Adobe Experience Manager (AEM) 中的新增功能、修复和更新。Adobe 建议那些采用内部部署的客户部署最新的修补程序，以便确保获得更高的稳定性、安全性和性能。

>[!NOTE]
>
>Adobe 建议您经常访问 [Experience Manager 版本更新和路线图](https://docs.adobe.com/content/help/en/experience-manager-release-information/aem-release-updates/home.html)，以保证及时了解最新发行信息。

### 产品版本

* **AEM as a Cloud Service**

   AEM as a Cloud Service 有哪些新增功能？

   * **Adobe Experience Manager Sites as a Cloud Service**
      * 单页应用程序 (SPA) 编辑器 Javascript SDK [现在是开放源代码。](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-service/implementing/headless/spa/reference-materials.html)
   * **Adobe Experience Manager Assets as a Cloud Service**

      * 通过 Asset 微服务生成的演绎版支持对图像文件添加水印。它可以配置为处理用户档案，并使用 PNG 文件作为水印。请参阅[对资产添加水印](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-service/assets/manage/watermark-assets.html)。
      * Dynamic Media 中的增强功能：
         * 选择性发布 - 营销团队现在可以访问同步到 Dynamic Media的 [!UICONTROL Dynamic Media] 智能裁剪图像和动态演绎版，以便创建促销材料，而无需将这些资产发布到 Dynamic Media 进行全球交付。Experience Manager 和 [!UICONTROL Dynamic Media] 发布是相互分离的，可单独进行以实现这一点。请参阅[选择性发布](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-service/assets/dynamicmedia/selective-publishing.html)。
         * 密码重置 - 管理员现在可以重置在预配置时收到的 [!UICONTROL Dynamic Media] Cloud Service 密码。可在 Experience Manager 用户界面中完成重置，无需使用 [!UICONTROL Dynamic Media] Classic 桌面应用程序。请参阅[将密码更改为 Dynamic Media](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-service/assets/dynamicmedia/config-dm.html#change-dm-password)。
      * 要了解以下增强功能，请参阅 [Brand Portal 中的新增功能](https://docs.adobe.com/content/help/zh-Hans/experience-manager-brand-portal/using/introduction/whats-new.html)。
         * Adobe Document Cloud 视图 SDK 集成的增强 PDF 预览。
         * 单击下载功能。
         * 下载体验的新管理配置。
   * **Adobe Experience Manager Commerce as a Cloud Service**

      * 已发布 CIF 核心组件 v1.3.0。有关更多详细信息，请参阅 [CIF 核心组件](https://github.com/adobe/aem-core-cif-components/releases/tag/core-cif-components-reactor-1.3.0)。
      * 产品和类别模板的产品/类别预览功能现已可用。这使 AEM 的业务用户/营销人员能够查看带有真实数据的产品/类别模板。
      * 产品和类别中添加了属性页面，以允许业务用户查看与产品 SKU/类别 ID 相关的详细信息。
      * 产品控制台中添加了排序功能，以允许按名称或价格属性对产品/类别进行排序。
      * 产品搜索功能已添加到[!UICONTROL 产品控制台]。
   * **Cloud Manager**

      * [!UICONTROL 内容审核]已重新标记为[!UICONTROL 体验审核]。
      * 构建过程已分为三个单独的 Maven 命令。
      * 如果无法克隆 Git 存储库，则最多将重新尝试三次。
   * **Cloud Readiness Analyzer**

      * Cloud Readiness Analyzer (CRA) 具有开始状态控制台，该控制台显示一个明确的&#x200B;**[!UICONTROL 生成报告]**&#x200B;按钮，供用户单击以执行 CRA。
      * CRA UI 在运行时会显示进度。它显示正在分析的项目和在执行过程中找到的结果。
      * CRA 报告以表格形式显示了调查结果的摘要和数量，按调查结果类型和重要性级别进行整理。单击该调查结果的编号将自动滚动到该调查结果在报告中的位置。
   * **内容传输工具**

      * 内容传输工具 (CTT) 支持 Azure Blob 存储数据存储。
      * CTT 用户界面具有自动重新加载功能，每 30 秒重新加载一次概述页面。
      * CTT 用户界面中添加了按钮，以轻松检索访问令牌。
      * 为 *URL* 和&#x200B;*迁移集名称*&#x200B;添加了描述性验证消息。
   * **代码重构工具**

      * AIO-CLI 插件支持 Repository Modernizer，并允许用户使用插件执行该工具。有关更多详细信息，请参阅 [Git 资源：aio-cli-plugin-aem-cloud-service-migration](https://github.com/adobe/aio-cli-plugin-aem-cloud-service-migration)。
      * Repository Modernizer 实用程序可用于将现有项目包重构为与针对 AEM as a Cloud Service 定义的项目结构兼容的包。有关更多详细信息，请参阅 [Git 资源：Repository Modernizer](https://github.com/adobe/aem-cloud-service-source-migration/tree/master/packages/repository-modernizer)。







请参阅 [AEM as a Cloud Service 发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)。

### 自助服务

**[!DNL Experience Manager]Sites**

已更新富文本编辑器文档，列出了 [RTE 中支持的所有链接协议](https://docs.adobe.com/content/help/zh-Hans/experience-manager-65/administering/operations/configure-rich-text-editor-plug-ins.html#linkstyles)。

**[!DNL Experience Manager]Assets**

* 提供了适用于所有用户的[如何访问 AEM Assets](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-service/assets/accessibility.html) 的最新帮助内容。

* **[视图模式参数](https://docs.adobe.com/content/help/zh-Hans/experience-manager-65/assets/using/search-assets.html#assetpicker)**&#x200B;会添加到资产选择器（资产选取器），以在搜索模式下打开资产选择器。要在搜索模式下打开资产选择器并与 `assettype` 和 `mimetype` 一起使用，用户需要为 `viewmode=search` 参数（在 url `https://[aem-server]:[port]/aem/assetpicker.html` 中）添加后缀。例如：`https://[aem-server]:[port]/aem/assetpicker.html?viewmode=search&assettype=images`。

* 在[删除专用文件夹](https://docs.adobe.com/content/help/zh-Hans/experience-manager-65/assets/managing/private-folder.html#delete-private-folder)时，会删除专用文件夹的相关用户组，并且可以使用 JMX 中的 clean 方法从存储库中清理冗余、未使用和自动生成的现有用户组。

* [Service Pack 6.5.5.0](https://docs.adobe.com/content/help/zh-Hans/experience-manager-65/release-notes/service-pack/previous-hotfixes-featurepacks.html#assets-6550) 的桌面应用程序登录问题已在桌面应用程序版本 2.0.3.2 中修复。

* 如果用户已修改 [Apache Jackrabbit Oak TokenConfiguration](https://helpx.adobe.com/experience-manager/kb/How-to-set-token-session-expiration-AEM.html)，将超时配置设置为小于上传资产所花费的时间，则用户可能会遇到会话超时情况。因此，用户需要更改 `chunkUploadMinFileSize` 和 `chunksize`，以便每个区块请求都会刷新会话。有关更多信息，请参阅[上传资产](https://docs.adobe.com/content/help/en/experience-manager-65/assets/managing/managing-assets-touch-ui.html#uploading-assets)。

* 除了使用[!UICONTROL 移动]操作来打开[!UICONTROL 移动资产]向导之外，还可以[使用拖动操作将资产移入同级文件夹](https://docs.adobe.com/content/help/en/experience-manager-65/assets/managing/managing-assets-touch-ui.html#moving-or-renaming-assets)。

* 对于 Assets Insights，请使用 [Adobe Launch](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/advanced/asset-insights-launch-tutorial.html)。[DTM 集成](https://docs.adobe.com/content/help/en/experience-manager-65/assets/managing/touch-ui-using-dtm-for-asset-insights.html)是作为文档中一个弃用的方法而存在。

更新日期：**2020 年 10 月 28 日**

* **Brand Portal 增强功能**：[!DNL Brand Portal] 提供了以下新增功能及更多功能：

   * [更好的下载体验](https://docs.adobe.com/content/help/zh-Hans/experience-manager-brand-portal/using/download/brand-portal-download-assets.html)，使下载更简单、更快。管理员还可配置其他下载配置，以提供贴合用户和企业需求的体验。
   * 现在，从任何页面都可一键导航到[!UICONTROL 文件]、[收藏集](https://docs.adobe.com/content/help/zh-Hans/experience-manager-brand-portal/using/share/brand-portal-share-collection.html)和[!UICONTROL 共享链接]。
   * 用户现在可以[选择和下载特定演绎版](https://docs.adobe.com/content/help/zh-Hans/experience-manager-brand-portal/using/download/brand-portal-download-assets.html#download-assets-from-asset-details-page)。新的演绎版下载选项位于“资产”详情页面的[!UICONTROL 演绎版]面板中。
   * 来宾用户会话超时时间为 15 分钟，这可确保所有并行用户获得更好的体验。

### [!DNL Experience Manager] 表单

6.5.6.0 版本中包含的以下功能现已提供相关文档。您现在可以：

* 在客户端运行自适应表单预填充数据操作。[在客户端运行预填充](https://docs.adobe.com/content/help/zh-Hans/experience-manager-65/forms/adaptive-forms-advanced-authoring/prepopulate-adaptive-form-fields.html)可显著减少合并数据和渲染自适应表单所需的时间。
* 在表单数据模型中，[为 RESTful 和 SOAP Web 服务使用基于证书的双向身份验证](https://docs.adobe.com/content/help/zh-Hans/experience-manager-65/forms/form-data-model/configure-data-sources.html#mutual-authentication)。
* 包括[作为 URL 选择器的区域设置信息](https://docs.adobe.com/content/help/zh-Hans/experience-manager-65/forms/manage-administer-aem-forms/supporting-new-language-localization.html)。使用 URL 选择器有助于[将翻译后的自适应表单缓存到](https://docs.adobe.com/content/help/zh-Hans/experience-manager-65/forms/install-aem-forms/configure-aem-forms/configure-adaptive-forms-cache.html)调度程序上。
* 将[多个文件附加到自适应表单的“文件附件”](https://docs.adobe.com/content/help/zh-Hans/experience-manager-65/forms/getting-started/introduction-forms-authoring.html)组件。

针对自动化表单转换服务发布的以下功能现已提供相关文档。您现在可以：

* 通过该服务使用[支持 PDF 表单的 Adobe Sign](https://git.corp.adobe.com/AdobeDocs/aem-forms-automated-conversion-service.en/blob/master/help/frequently-asked-questions.md)。如果源 PDF 表单带有 Adobe Sign 文本标签，那么该服务在转换过程中将保留所有 Adobe Sign 相关的信息，并将源 PDF 中存在的签名者信息与相应的自适应表单字段进行关联。

* 现在，该服务支持[将彩色 PDF 表单转换为自适应表单](https://docs.adobe.com/content/help/zh-Hans/aem-forms-automated-conversion-service/using/release-notes.html)。

### [!DNL Adobe Experience Manager] 版本更新和路线图文档

发布了关于 Adobe Experience Manager 版本路线图、版本更新和加载项信息的一站式文档解决方案。为便于访问，不同 AEM 空间中提供的许多有关联性的文章都放入了一个位置。包括以下重要文章：

* [AEM 版本路线图](https://docs.adobe.com/content/help/en/experience-manager-release-information/aem-release-updates/update-releases-roadmap.html)：列出即将发行的 AEM as a Cloud Service 的版本，以及受支持的内部部署和托管服务的 AEM 版本。
* [AEM 版本更新](https://docs.adobe.com/content/help/en/experience-manager-release-information/aem-release-updates/aem-releases-updates.html)：列出 AEM as a Cloud Service 的最新发行版本，以及受支持的内部部署和托管服务的 AEM 版本，并带您找到这些发行版本的相关文档。
* [AEM Forms 版本](https://docs.adobe.com/content/help/en/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html)：列出所有已发布的 Forms 加载项软件包的软件分发包链接。

此外，该知识库还包括其他重要文章（例如，[AEM 更新版本工具定义](https://docs.adobe.com/content/help/en/experience-manager-release-information/aem-release-updates/update-release-vehicle-definitions.html)和[近期 AEM 文档更新](https://docs.adobe.com/content/help/en/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html)。

### [!DNL Adobe Experience Manager] 桌面应用程序

* 如果用户在注销后又登录桌面应用程序，或者首次登录桌面应用程序，则应当提供其 [!DNL Experience Manager] 服务器 URL 并且该 URL 应采用 `https://[aem-server-url]:[port]/` 格式，然后选择[!UICONTROL 连接]选项，以此来避免出现错误“应用程序遇到未知错误”。有关更多信息，请参阅[使用 Adobe Experience Manager 桌面应用程序](https://docs.adobe.com/content/help/zh-Hans/experience-manager-desktop-app/using/using.html)。

### 社区

* **宣布提交 Experience Manager 功能请求的新流程**

   您是否希望看到 Experience Manager 路线图中新增一项功能？Adobe 很兴奋地宣布 *FeatureBit* - 这个项目可以改善客户和合作伙伴向 Experience Manager 产品团队请求功能增强（称为 RFE）的方式。通过 [Experience League AEM 社区](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/announcing-the-new-process-to-submit-experience-manager-feature/td-p/380425)了解更多信息。

* **Experience League 上的最新 AEM 内容**

   这是 Adobe 制作的数字体验技术内容的官方来源。请在[此处](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/list-of-latest-adobe-experience-manager-content-on-experience/m-p/377452#M27156)查看完整列表。

### Experience Manager 的新课程和教程

更新日期：**2020 年 10 月 21 日**

过去一个月发布的新视频、教程及课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 11 月 2 日 | [加载和触发 Target 调用](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/target/load-and-fire-target.html) | 视频 | 了解如何加载参数并将参数传递到页面请求，以及如何使用 Launch 规则从网页上触发 Target 调用。使用 Adobe 客户端数据层不仅能够检索页面信息并将其作为参数进行传递，还能让您收集和存储有关访客在网页上的体验数据，并轻松访问这些数据。 |
| 2020 年 10 月 28 日 | [视频智能标签](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/metadata/video-smart-tags.html) | 视频 | Experience Manager Assets 利用 Adobe Sensei，通过描述视频关键元素的关键字对视频资产进行智能标记，从而使 AEM 用户能够通过搜索关键字，轻松找到这些视频。 |
| 2020 年 10 月 27 日 | [AEM Document Security Extension for Microsoft Office 简介](https://docs.adobe.com/content/help/en/experience-manager-document-security/using/document-security-extension-microsoft-office.html) | 文章 | Adobe Experience Manager Document Security Extension for Microsoft Office 可确保只有经您授权的人员才能使用包含您的知识产权的 Word、Excel 和 PowerPoint 文件。通过使用 Document Security Extension for Microsoft Office，您可以为文件应用预定义保密设置。 |
| 2020 年 10 月 7 日 | [Adobe Analytics 中的“查看页面”量度](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/analytics/create-analytics-workspace.html) | 文章 | 了解如何将 Adobe Experience Manager 网站中捕获的数据映射到 Adobe Analytics 报表包中的量度和维度。 |
| 2020 年 10 月 8 日 | [完整网页体验的个性化](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/target/personalization-web-page.html) | 视频 | 了解如何使用 Adobe Target 创建活动，将 AEM 托管的网页重定向到新的页面。 |
| 2020 年 10 月 8 日 | [使用可视化体验编辑器进行个性化](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/target/personalization-using-vec.html) | 视频 | 了解如何使用可视化体验编辑器 (VEC) 来创建 A/B 测试 Target 活动。 |
| 2020 年 9 月 14 日 | [使用 Experience Fragment 选件创建 Target 活动](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/target/create-target-activity.html) | 视频 | 了解如何使用 AEM Experience Fragment 选件创建和测试 Adobe Target 活动。 |
| 2020 年 10 月 8 日 | [导出 Experience Fragment 到 Adobe Target](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/target/export-experience-fragment-target.html) | 视频 | 了解如何将 AEM Experience Fragment 导出为 Adobe Target 选件。 |
| 2020 年 10 月 5 日 | [使用表单数据模型变量在数据库中插入行](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/variables-aem-workflow/form-data-model.html) | 视频 | 表单数据模型类型的变量通常用于在表单数据模型的底层数据源中插入行。此视频介绍使用 AEM 工作流在数据库中插入行所需的步骤。 |
| 2020 年 9 月 28 日 | [使用短信进行双重身份验证](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/some-useful-integrations/two-factor-authentication.html) | 文章 | 在自适应表单中使用短信执行 OTP 验证。 |
| 2020 年 9 月 28 日 | [资产计算课程](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.1.asset.compute) | 课程 | 本课程探讨如何扩展 AEM as a Cloud Service Asset 计算微服务！您现在应该能够设置、开发、测试、调试和部署自定义资产计算工作程序，以供 AEM as a Cloud Service 作者服务使用。 |
| 2020 年 9 月 23 日 | [使用 Adobe Analytics 跟踪已单击的组件](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/analytics/track-clicked-component.html) | 文章 | 使用事件驱动的 Adobe 客户端数据层，在 Adobe Experience Manager 中收集有关网页和用户在网站上的互动情况数据。了解如何使用 Experience Platform Launch 中的规则来侦听这些事件，并将数据发送到 Adobe Analytics 报表包。 |
| 2020 年 9 月 25 日 | [集成资产计算工作程序与 AEM 处理用户档案](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/deploy/processing-profiles.html) | 视频 | AEM as a Cloud Service 通过 AEM 资产处理用户档案与部署到 Adobe I/O 运行时的资产计算工作程序集成。处理用户档案在作者服务中配置为使用自定义工作程序处理特定资产，并将工作程序生成的文件存储为资产演绎版。 |
| 2020 年 9 月 25 日 | [部署到 Adobe I/O 运行时 - 教程](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/deploy/runtime.html) | 视频 | 资产计算项目及其包含的工作程序必须部署到 Adobe I/O 运行时，以供 AEM as a Cloud Service 使用。 |
| 2020 年 9 月 25 日 | [调试资产计算工作程序](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/asset-compute/test-debug/debug.html) | 文章 | 资产计算工作程序可以通过多种方式进行调试，从简单的调试日志语句，到作为远程调试器的附加 VS Code，再到在 Adobe I/O 运行时中为从 AEM as a Cloud Service 启动的激活提取日志。 |
| 2020 年 9 月 25 日 | [使用资产计算开发工具](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/develop/development-tool.html) | 文章 | 资产计算开发工具是一个本地 Web 工具，允许开发人员在 AEM SDK 上下文之外针对 Adobe I/O 运行时中的资产计算资源在本地配置和执行资产计算工作程序。 |
| 2020 年 9 月 27 日 | [开发资产计算工作程序](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/develop/worker.html) | 文章 | 资产计算工作程序是资产计算应用程序的核心，它提供对资产执行或协调工作以创建新的演绎版的自定义功能。 |
| 2020 年 9 月 25 日 | [配置 manifest.yml](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/develop/manifest.html) | 文章 | 资产计算项目的 manifest.yml 描述了此应用程序中要部署的所有工作程序。 |
| 2020 年 9 月 14 日 | [配置环境变量](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/develop/environment-variables.html) | 视频 | 环境变量在“.env”文件中进行维护以用于本地开发，并用于提供本地开发所需的 Adobe I/O 凭据和云存储凭据。 |
| 2020 年 9 月 14 日 | [创建资产计算项目](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/develop/project.html) | 文章 | 资产计算应用程序是使用 Adobe I/O CLI 生成的 Node.js 项目，符合特定结构，允许将它们部署到 Adobe I/O 运行时并与 AEM as a Cloud Service 集成。 |
| 2020 年 9 月 14 日 | [配置环境变量](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/develop/environment-variables.html) | 文章 | 环境变量在“.env”文件中进行维护以用于本地开发，并用于提供本地开发所需的 Adobe I/O 凭据和云存储凭据。 |
| 2020 年 9 月 14 日 | [创建资产计算项目](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/develop/project.html) | 视频 | 资产计算应用程序是使用 Adobe I/O CLI 生成的 Node.js 项目，符合特定结构，允许将它们部署到 Adobe I/O 运行时并与 AEM as a Cloud Service 集成。 |
| 2020 年 9 月 14 日 | [设置 Adobe I/O 项目 Firefly](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/set-up/firefly.html) | 教程 | 资产计算应用程序是特别定义的 Adobe 项目 Firefly 应用程序，因此，需要访问 Adobe 开发者控制台中的 Adobe 项目 Firefly 才能设置和部署它们。 |
| 2020 年 9 月 25 日 | [设置本地开发环境](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/set-up/development-environment.html) | 文章 | 开发资产计算工作程序（即 Node.js JavaScript 应用程序）需要与传统 AEM 开发不同的特定开发工具，这些工具从 Node.js 和各种 npm 模块到 Docker Desktop 和 Microsoft Visual Studio Code，不一而足。 |
| 2020 年 9 月 25 日 | [设置帐户和服务](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/set-up/accounts-and-services.html) | 文章 | 开发资产计算工作程序需要访问帐户和服务，包括 AEM as a Cloud Service 、Adobe Project Firefly 以及 Microsoft 或 Amazon 提供的云存储。 |
| 2020 年 9 月 30 日 | [探索 Adobe 客户端数据层](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/adobe-client-data-layer/data-layer-overview.html) | 文章 | 探索事件驱动的 Adobe 客户端数据层的特性和功能，以及它与 AEM Sites 核心组件的集成。了解如何侦听事件、获取当前状态和修改数据层。 |
| 2020 年 9 月 30 日 | [Adobe 客户端数据层简介](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/adobe-client-data-layer/data-layer-overview.html) | 视频 | 了解事件驱动的 Adobe 客户端数据层如何公开来自 AEM Sites 核心组件的数据。使用 Adobe 客户端数据层，Experience Platform Launch 等标签管理解决方案可以将网站数据传输到 Analytics 和 Target 等应用程序。 |
| 2020 年 10 月 8 日 | [将 Target 扩展添加到 Launch 属性](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/target/add-target-launch-extension.html) | 视频 | 了解如何加载参数并将参数传递到页面请求，以及如何使用 Launch 规则从网页上触发 Target 调用。使用 Adobe 客户端数据层不仅能够检索页面信息并将其作为参数进行传递，还能让您收集和存储有关访客在网页上的体验数据，并轻松访问这些数据。 |
| 2020 年 10 月 7 日 | [创建 Adobe Target 云服务帐户](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/target/setup-aem-target-cloud-service.html) | 视频 | 了解如何使用云服务和 Adobe IMS 身份验证，将 Adobe Experience Manager as a Cloud Service 与 Adobe Target 集成。 |
| 2020 年 10 月 2 日 | [AEM 和 Adobe Target 概述](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/target/overview.html) | 视频 | AEM 和 Target 都是功能强大的解决方案，但看上去似乎有一些功能重叠。客户有时难以理解如何以及何时结合使用这两个产品来交付个性化体验。为了给每一位最终用户交付最佳体验，贵组织内的不同团队应密切合作且明确分工。 |
| 2020 年 10 月 2 日 | [AEM Forms 与 Adobe Sign 集成](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.2.forms) | 课程 | 通过将 Adobe Sign 和 AEM Forms 结合使用，您可以自动执行复杂的事务，还可以使用安全合法的电子签名作为无缝数字体验的一部分。 |
| 2020 年 10 月 6 日 | [为打印渠道创建交互式文档](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.5.forms) | 课程 | 交互式通信可以集中管理安全、个性化的交互式信函的创建、编排和交付，例如商务信函、文档、声明、福利通知、市场营销邮件、账单和欢迎资料包。本课程将重点介绍构成交互式通信文档的各种组件的创建。 |
| 2020 年 10 月 10 日 | [适用于开发人员的 AEM SPA Editor 快速入门](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.1.spaeditor) | 课程 | 了解如何通过 AEM SPA Editor 构建可在 AEM 中编写的高性能单页应用程序 (SPA)。本课程介绍的主要开发任务，涵盖了从创建一个新的 SPA Editor 项目到构建自定义组件的全过程。还提供了有关 Angular 和 React 框架的等效课程；预计大多数开发人员将选择使用单一框架。 |
| 2020 年 10 月 7 日 | [资产计算可扩展性](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/overview.html) | 文章 | 本教程介绍如何为 AEM as a Cloud Service 创建自定义资产微服务工作程序。 |
| 2020 年 10 月 6 日 | [创建您的第一个自适应表单](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.4.forms) | 课程 | 通过 AEM Forms，您可以创建有吸引力的响应式、动态化自适应表单。本课程从创建自定义的自适应表单模板开始，逐步引导您通过使用各种表单组件来创建自适应表单。 |
| 2020 年 10 月 21 日 | [本地 Dispatcher 工具](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/dispatcher-tools.html) | 文章 | AEM 的 Dispatcher 是一个 Apache HTTP Web 服务器模块，在 CDN 和 AEM 发布层之间提供一个安全和性能层。了解如何将 Dispatcher 设置为本地开发环境的一部分。 |
| 2020 年 10 月 14 日 | [适用于开发人员的 AEM Sites 快速入门](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.2.guided) | 课程 | 本课程是对 Experience League 一个[现有课程](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2019.2.guided)的更新。 |
| 2020 年 10 月 7 日 | [AEM 项目结构](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-service/implementing/developing/aem-project-content-package-structure.html) | 视频 | 本文概述了 Adobe Experience Manager Maven 项目要兼容 AEM as a Cloud Service 所需的更改，需要确保这些项目能够支持对可变和不可变内容的拆分，建立依赖关系以创建无冲突的确定性部署，并将它们打包为可部署的结构。 |

### Experience Manager 发行信息

所有的 Experience Manager 发行说明均保留在以下页面：

* [Experience Manager 版本更新和路线图](https://docs.adobe.com/content/help/en/experience-manager-release-information/aem-release-updates/home.html)
* [AEM as a Cloud Service 发行信息](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-service/release-notes/home.html)
* [AEM Cloud Manager 发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [自动化表单转换服务发行说明](https://docs.adobe.com/content/help/zh-Hans/aem-forms-automated-conversion-service/using/release-notes.html)
* [AEM 6.5 Service Pack 发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
* [AEM 6.4 累积修复程序包发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-64/release-notes/cfp-release-notes.html)
* [AEM Assets Dynamic Media 发行说明](https://docs.adobe.com/content/help/zh-Hans/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [AEM Brand Portal 发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)
* [AEM 桌面应用程序发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-desktop-app/using/release-notes.html)
* [AEM Dispatcher 发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-dispatcher/using/getting-started/release-notes.html)
* [Adobe Primetime 发行说明](https://docs.adobe.com/content/help/zh-Hans/primetime/release-notes/home.html)
* [Livefyre 发行说明](https://docs.adobe.com/content/help/zh-Hans/livefyre/using/release-notes/c-rn.html)

### AEM 的其他帮助资源

* [AEM as a Cloud Service 指南](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-5.html)
* [AEM 6.4 学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-4.html)
* [AEM 6.3 学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-3.html)
* [AEM 6.2 学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-2.html)
* [Cloud Manager 用户指南](https://helpx.adobe.com/cn/experience-manager/cloud-manager/user-guide.html)
* [更早版本的 AEM 文档](https://helpx.adobe.com/cn/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic 帮助主页](https://docs.adobe.com/content/help/zh-Hans/dynamic-media-classic/using/home.html)

## ![图标](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign 提供了一种直观、自动的方式，以通过在线和离线营销渠道来交付一对一的消息。您现在可以利用根据客户习惯和喜好所决定的体验，来预测客户的需求。

### 新的产品版本

Campaign Classic、Campaign Standard 和控制面板的发行信息。

#### 控制面板

* 使用 CNAME 的子域配置 - [了解详情](https://docs.adobe.com/content/help/zh-Hans/control-panel/using/subdomains-and-certificates/setting-up-new-subdomain.html#use-cnames)

* 增强数据库监控 - [了解详情](https://docs.adobe.com/content/help/zh-Hans/control-panel/using/performance-monitoring/database-monitoring.html)

### Campaign 的新课程和教程

过去一个月发布的新视频、教程或课程。

| 发布日期 | 名称 | 解决方案 | 描述 |
| ----------- | ----------- | ---------- | ---------- |
| 2020 年 11 月 2 日 | [控制面板 - 生成 SSH 密钥 - 功能视频](https://docs.adobe.com/content/help/zh-Hans/campaign-classic-learn/control-panel/sftp-management/generate-ssh-key.html) | Campaign Classic | 了解如何使用终端生成 SSH 密钥，以及如何在控制面板中存储该密钥的公共版本。 |
| 2020 年 11 月 2 日 | [控制面板 - 连接到 SFTP 服务器 - 功能视频](https://docs.adobe.com/content/help/zh-Hans/campaign-classic-learn/control-panel/sftp-management/connect-to-sftp-server.html) | Campaign Classic | 了解如何使用您存储在控制面板中的密钥，通过客户端 SFTP 应用程序连接到 SFTP 服务器。 |
| 2020 年 10 月 20 日 | [控制面板 - 控制面板入门 - 文章](https://docs.adobe.com/content/help/zh-Hans/campaign-classic-learn/control-panel/getting-started-with-the-control-panel.html) | Campaign Classic | 本文介绍如何访问控制面板，以及使用控制面板的先决条件。 |
| 2020 年 10 月 20 日 | [控制面板 - 控制面板入门 - 文章](https://docs.adobe.com/content/help/zh-Hans/campaign-standard-learn/control-panel/getting-started-with-the-control-panel.html) | Campaign Standard | 本文介绍如何访问控制面板，以及使用控制面板的先决条件。 |
| 2020 年 10 月 19 日 | [控制面板 - 向允许列表添加 IP 范围](https://docs.adobe.com/content/help/zh-Hans/campaign-classic-learn/control-panel/sftp-management/adding-ip-range-to-allow-list.html) | Campaign Classic | 了解如何在控制面板中向允许列表添加 IP 地址范围。 |
| 2020 年 10 月 19 日 | [控制面板 - 向允许列表添加 IP 范围](https://docs.adobe.com/content/help/zh-Hans/campaign-standard-learn/control-panel/sftp-management/adding-ip-range-to-allow-list.html) | Campaign Standard | 了解如何在控制面板中向允许列表添加 IP 地址范围。 |
| 2020 年 10 月 16 日 | [控制面板 - 使用 CNAME（测试版）委派子域 - 功能视频](https://docs.adobe.com/content/help/zh-Hans/campaign-classic-learn/control-panel/subdomains-and-certificates/delegating-subdomains-using-cname.html) | Campaign Classic | 了解如何在控制面板中使用 CNAME 来设置和提交子域。 |
| 2020 年 10 月 16 日 | [控制面板 - 使用 CNAME（测试版）委派子域 - 功能视频](https://docs.adobe.com/content/help/zh-Hans/campaign-standard-learn/control-panel/subdomains-and-certificates/delegating-subdomains-using-cname.html) | Campaign Standard | 了解如何在控制面板中使用 CNAME 来设置和提交子域。 |

### 帮助资源

* Adobe Campaign Standard：[帮助中心](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/campaign-standard-home.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/release-notes/release-notes.html) - [操作方法视频](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [发行计划](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/release-notes/release-planning.html) - [最新文档更新](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic：[帮助中心](https://docs.adobe.com/content/help/zh-Hans/campaign-classic/using/campaign-classic-home.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/campaign-classic/using/release-notes/latest-release.html) - [操作方法视频](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)- [最新文档更新](https://docs.adobe.com/content/help/zh-Hans/campaign-classic/using/documentation-updates.html)
* Adobe Campaign 控制面板：[文档](https://docs.adobe.com/content/help/zh-Hans/control-panel/using/control-panel-home.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/control-panel/using/release-notes.html) - 有关 [Campaign Standard](https://docs.adobe.com/content/help/zh-Hans/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html)/[Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html) 的操作方法视频

## ![图标](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Adobe Advertising Cloud 的发行说明。

* [Advertising Cloud DSP 中的新增功能](#adcloud-dsp)
* [Advertising Cloud Search 中的新增功能](#adcloud-search)

### [!DNL Advertising Cloud DSP] 中的新增功能 {#adcloud-dsp} 

更新日期：2020 年 10 月 28 日

| 功能 | 描述 |
| -----------| ---------- |
| 新建帮助 | （10 月 28 日版）旧版帮助页面已替换为更新页面，这些更新页面可从 DSP 主菜单的“帮助”链接获取，也可随时从 [https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html](https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html) 获取。 |
| 促销活动 | （10 月 28 日版）以前的 Campaigns 测试版视图现在成为默认的 Campaigns 视图，可以实现更快的分析、简化的工作流和自定义视图。 |
| 专用内容库 | （10 月 15 日版）如今，所有用户都可以使用新的交易 ID 表单来设置和编辑交易 ID 详细信息，该表单是旧版[!UICONTROL 智能广告投放]表单的简化版。要设置新的交易 ID 详细信息，请转到&#x200B;**[!UICONTROL 内容库 > 交易]**，单击&#x200B;**[!UICONTROL 创建]**，然后单击&#x200B;**[!UICONTROL 交易 ID 测试版]**。 |
| 投放预测 | （10 月 15 日版）在投放设置的[!UICONTROL 预测]部分，我们为具有投放级别步调的广告投放提供了一个新增的[!UICONTROL 估计的最大量]部分，它指明了当前目标配置中的可用容量。 |

### [!DNL Advertising Cloud Search] 中的新增功能 {#adcloud-search} 

发行日期：**2020 年 10 月 17 日**

| 功能 | 描述 |
| -----------| ---------- |
| 搜索促销活动 | 如今，[!UICONTROL 帐户]视图的[!UICONTROL 访问]列可指明 [!DNL Advertising Cloud Search] 何时无法登录到已启用搜索引擎的帐户。要了解错误原因，请将光标悬停在警告图标上。 |
| [!UICONTROL 自定义警报] | 此前的[!UICONTROL 测试版警报]现已更名为[!UICONTROL 自定义警报]。 |
|  | 在自定义警报中，我们简化了下面的工作流程并将其移至[!UICONTROL 过滤器]选项卡：用来确定与上一期间的量度相比，指定日期范围的量度何时发生增减。 |

## ![图标](/assets/magento.png) [!DNL Magento] {#magento}

有关 Magento 的发行说明，请参阅：

* [Magento Commerce 2.3.5](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-5-open-source.html)
* [Magento Open Source 2.3.5](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-5-open-source.html)

## ![图标](/assets/target.png)[!DNL Target] {#target}

请参阅 [[!DNL Target]  发行说明](https://docs.adobe.com/content/help/zh-Hans/target/using/release-notes/target-release-notes.html)了解最新发行信息。

### Adobe Target 的新课程和教程

更新日期：**2020 年 11 月 2 日**

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 10 月 11 日 | [混合个性化部署模型](https://docs.adobe.com/content/help/en/target-learn/tutorials/implementation/hybrid-deployment.html) | 视频 | Adobe Target 提供了一个用于实现个性化的独特混合部署模型 - 将客户端和服务器端实施混合在一起。该混合模型允许非技术用户使用 WYSIWYG Visual Experience Composer 创作实验或个性化活动，并让服务器端执行、交付和渲染，从而实现高性能交付。 |

## ![图标](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] 是一个完整的应用程序，面向希望通过参与复杂购买历程的每个阶段来转变客户体验的潜在客户管理人员和 B2B 营销人员。

### 核心 Marketo Engage 更新

请参阅 [!DNL Marketo] [发行说明](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+July+%2720)了解最新发行信息。

### 即将推出的功能

本季度将发布以下功能：

| 功能 | 描述 |
| ------ | --------- |
| [!DNL Bizible] | <ul><li>新的基于帐户的分段</li><li>保存特定于功能板的过滤器</li><li>将 Bizible 功能板导出为 PDF</li></ul> |
| Sales Connect | 撰写窗口和命令中心更新/增强功能 |

### 弃用

* **Asset API“_method”参数：** 2020 年 9 月之后，Asset API 端点将不再接受 `_method` 在 POST 正文中传递查询参数以绕过 URI 长度限制。
* **弃用 Internet Explorer 支持：**&#x200B;从 2020 年 7 月 31 日发行的 7 月版本开始，Internet Explorer 将不再支持 Marketo Engage 用户界面。

有关累积和历史发行说明，请参阅 [Marketo 发行说明](https://docs.marketo.com/x/CgA6Ag)。

## ![图标](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

Adobe Document Cloud 的发行信息和帮助资源。

### Adobe Sign 的新课程和教程

为 Adobe Document Cloud 发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 9 月 29 日 | [快速浏览 Adobe Sign](https://docs.adobe.com/content/help/en/document-cloud-learn/sign-learning-hub/getting-started/getting-started-sending/quick-tour.html) | 视频 | 在本视频中，我们将从主屏幕开始快速浏览一下 Adobe Sign。 |

有关 Document Cloud 的帮助，请参阅：

* [Adobe Acrobat 学习中心](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=en)
* [Adobe Sign 学习中心](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=en)
* [Document Cloud 学习与支持](https://helpx.adobe.com/support/document-cloud.html)
