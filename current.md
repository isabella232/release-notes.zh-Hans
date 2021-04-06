---
title: 最新发行说明
description: 了解 Experience Cloud 产品和服务的最新发行说明、新增功能和新文档。查找关于 Experience Cloud、Creative Cloud 企业版和 Document Cloud 的新帮助和教程。
doc-type: release notes
last-update: March 2021
author: mfrei
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
translation-type: tm+mt
source-git-commit: 6146981c558499f22dbdc56bc12e2ebce2d00439
workflow-type: tm+mt
source-wordcount: '7872'
ht-degree: 88%

---

# Adobe Experience Cloud 发行说明 - 2021 年 3 月

![横幅](/assets/experience-cloud-banner-3.png)

Experience Cloud 解决方案和服务每月更新一次。在此页面上可集中查找 [!DNL Experience Cloud] 产品和服务的最新版本更新、文档和教程。还可查找 [!DNL Creative Cloud for Enterprise] 和 [!DNL Document Cloud] 的新文档。

>[!NOTE]
>
>订阅每月一期的 [Adobe Priority Product Update](https://www.adobe.com/cn/subscription/priority-product-update.html) 即可收到关于此页面更新的电子邮件通知。整月都在维护此页，其中包含的内容在发布日期之前可能会变更。请定期回来查看 Adobe 企业版产品和 Experience League 文档是否有更新。

最新更新：**2021 年 4 月 6 日**

* [Digital Experience Blueprints](#blueprints) （新实施文档）
* [Adobe 系统状态](#status)
* [Experience Cloud UI 组件、服务和管理](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Offer Decisioning](#offer-decisioning)
* [分析](#analytics) **（2021年4月6日更新）** 和 [Customer Journey Analytics](#cust-journey)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [[!DNL Target]](#target)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo)
* [Document Cloud](#doc-cloud)
* [Creative Cloud 企业版](#creative-cloud)

需要帮助？请访问 [Adobe Experience League](https://experienceleague.adobe.com/#home)，查找产品和技术文档、Adobe 策划课程、视频教程、快速解答、社区洞察以及由讲师指导的培训。

## ![图](/assets/adobe.png) 标Digital Experience Blueprint  {#blueprints}

Digital Experience Blueprint是可重复实施的产品，用于解决战略和解决已建立的业务问题。 Blueprint可加快实现价值的速度，并提供快速的成功之路。

| 发布日期 | 描述 |
| -----------| ---------- |
| [数字体验蓝图](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html) | [!UICONTROL Digital Blueprints]概述。 每个Blueprint都会优惠一系列伪像，用于解释高价值业务问题、体系结构、实施步骤、技术考虑事项以及指向相关文档的链接。 |
| [Audience Activation Blueprint](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/audience-activation/overview.html) | 这一受众优先激活使品牌能够连接多个渠道的客户互动，以提供可激活给所有渠道的集中受众。 |
| [客户活动中心蓝图](https://experienceleague.adobe.com/docs/blueprints-learn/architecture//customer-activity-hub/overview.html) | 了解外部应用程序如何访问Adobe Experience Platform的[!UICONTROL 实时客户用户档案]。 |
| [Customer Journey Analytics Blueprint](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/customer-journey-analytics/overview.html) | 了解品牌如何统一来自各种交互渠道和来源的客户数据和行为，以创建所有客户交互的基于旅程的视图。 |
| [用户档案扩充蓝图的自定义数据科学](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/data-science/overview.html) | 了解[!UICONTROL 数据科学工作区]如何使用Adobe Experience Platform中的数据来培训、部署和评分模型以提供机器学习洞察。 |
| [数据准备和摄取蓝图](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/data-ingestion/overview.html) | 了解如何将源数据映射到[!UICONTROL 体验数据模型](XDM)模式。 此蓝图还包括对数据执行转换，包括日期格式、字段拆分、连接和转换，以及加入、合并和重新键入记录。 |
| [企业数据探索与报告蓝图](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/data-exploration/overview.html) | Experience Platform的[!UICONTROL 查询服务]允许对数据执行SQL查询。 了解[!UICONTROL 数据科学工作区]如何实现对数据执行数据探索、数据科学和机器学习工作负载。 |
| [多渠道消息编排蓝图](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/multi-channel-message-orchestration/overview.html) | 了解品牌如何通过电子邮件、短信和移动提醒等渠道主动与客户互动并与其通信。 |
| [服务器端企业数据收集蓝图](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/server-side-enterprise-data-collection/overview.html) | 了解如何将通过Adobe Experience Platform Web和移动SDK收集的数据从Experience Platform [!UICONTROL Edge Network]转发到所需目标。 |
| [Web和移动个性化蓝图](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/web-personalization/overview.html) | 了解如何在多个应用程序中使用受众细分来个性化和优化客户体验。 您可以使用客户行为、人口统计、忠诚度级别和先前交易个性化布局、行动号召和内容。 |

## ![图标](/assets/adobe.png) Adobe 系统状态 {#status}

[!UICONTROL Adobe 系统状态]提供关于 Adobe 云产品与服务中断和维护事件的详细信息、状态更新以及电子邮件通知。请访问 [status.adobe.com](https://status.adobe.com/) 查看。

可在 [Adobe 系统状态 - 2020 年 5 月 21 日](https://docs.adobe.com/content/help/zh-Hans/release-notes/experience-cloud/previous/2020/05212020.html#status)上找到 Adobe 系统状态的最新更新。

## ![图标](/assets/ec_appicon_24.png) Experience Cloud UI 组件、服务和管理{#ecloud}

| 功能 | 描述 |
| -----------| ---------- |
| 统一搜索 | “统一搜索”(目前可用于Experience Platform)现在支持对Experience Platform用户的源和目标进行搜索。 通过此功能，可搜索区段、数据集、架构、源和目标。 |

## ![图标](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

包括 Experience Platform 和 Experience Platform Launch 的发行更新信息。

* [Experience Platform 发行说明](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html)。(2021 年 2 月 24 日更新)
* [Experience Platform Launch 发行说明](https://experienceleague.adobe.com/docs/launch/using/release-notes/current.html)。(2021 年 2 月 18 日更新)

### Experience Platform 教程和课程

发布的关于 Experience Platform 和服务的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 3 月 | [监视仪表板](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/monitoring-dashboard.html) | 视频 | 了解如何使用监视仪表板监视和跟踪引入 Adobe Experience Platform 的数据。此监视仪表板在源、数据流和数据流运行级别针对通过数据湖对 Profile 和 Identity Services 的源数据处理提供自上而下的视图，并及时提供可操作的建议。 |
| 2021 年 3 月 | [使用源连接器流数据](https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/streaming-ingestion-source-connector.html) | 视频 | 此视频展示如何实时让数据从云存储源流入 Platform 以及实时使用数据吸引客户参与。 |
| 2021 年 3 月 5 日 | [数据引入之于数据工程师](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-D-1-2020.1.dataingestion) | 课程 | 如何从多个源将数据引入 Adobe Experience Platform 等等。 |
| 2021 年 3 月 | [配置 Azure Blob 目标](https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/configure-the-azure-blob-destination.html?lang=en#destinations) | 视频 | 了解如何轻松完成在 [!UICONTROL Real-time Customer Data Platform] (Real-time CDP) 中设置和配置 Azure Blob 存储目标所需的步骤。 |
| 2021 年 3 月 5 日 | [Offer Decisioning 营销人员快速入门](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-U-1-2020.1.offerdecisioning) | 课程 | 了解以 Adobe Experience Platform 为基础构建的 [!UICONTROL Offer Decisioning] 应用程序服务。本课程专为希望通过向客户提供优质产品而提高收入、客户体验和忠诚度的营销人员设计而成。 |
| 2021 年 3 月 5 日 | [通过 API 流式处理数据引入](https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/streaming-ingestion-http-api.html) | 视频 | 此视频展示如何使用 HTTP API 端点实时让数据流入 Adobe Experience Platform。 |
| 2021 年 3 月 5 日 | [使用 API 监视数据引入](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/data-monitoring.html?lang=en#data-ingestion) | 视频 | 了解如何使用 Platform 的 UI 和 API 监视和跟踪引入 Adobe Experience Platform 的数据。 |
| 2021 年 3 月 5 日 | [从数据库引入数据](https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/ingest-data-from-databases.html?lang=en#sources) | 视频 | 此视频介绍如何以无缝和可伸缩的方式将数据从数据库源批量引入 Adobe Experience Platform 的 Real-time Customer Profile 和 Experience Data Lake。 |
| 2021 年 3 月 5 日 | [从 Amazon S3 引入数据](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/ingest-data-from-amazon-s3.html) | 视频 | 此视频介绍如何轻松地以无缝和可伸缩的方式将数据从云存储服务引入 Adobe Experience Platform 的 Real-time Customer Profile 和 Data Lake。 |
| 2021 年 3 月 5 日 | [从 Salesforce CRM 引入数据](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/ingest-data-from-salesforce-crm.html) | 视频 | 此视频介绍如何轻松地以无缝和可伸缩的方式将数据从 CRM 源批量引入 Adobe Experience Platform 的 Real-time Customer Profile 和 Data Lake。 |
| 2021 年 3 月 5 日 | [从 Adobe Analytics 引入数据](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/ingest-data-from-adobe-analytics.html) | 视频 | 通过 Adobe Analytics 源连接器，可轻松地以无缝和可伸缩的方式让数据从 Adobe Analytics 流入 Adobe Experience Platform 的 Real-time Customer Profile 和 Experience Data Lake。 |
| 2021 年 3 月 5 日 | [了解源连接器](https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/overview.html?lang=en#sources) | 视频 | 此视频概述 Experience Platform 中的“源”，即源连接器。 |
| 2021 年 3 月 5 日 | [Adobe IO 控制台导出 Postman 详细信息](https://experienceleague.adobe.com/docs/platform-learn/tutorials/apis/postman.html) | 视频 | 了解如何验证和访问 Experience Platform API。 |
| 2021 年 3 月 5 日 | [了解数据引入](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/understanding-data-ingestion.html#data-ingestion) | 视频 | 了解 Experience Platform 的数据引入功能，通过这些功能可将数据集中到一个开放且可伸缩的平台中以管理实时客户个人资料。 |

## ![图标](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

凭借 Adobe Experience Platform，可以实时智能化预测每位客户的需求，从而实现跨体验渠道大规模编排客户历程。

### 最新产品版本

2021 年 2 月版 - 在 [Journey Orchestration 发行说明](https://docs.adobe.com/content/help/zh-Hans/journeys/using/release-notes/release-notes.html)中详细了解最新的功能、改进和修复。

### Journey Orchestration 的新课程和教程

过去一个月发布的新视频、教程及课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 3 月 16 日 | [“更新个人资料”操作](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/building-a-journey/update-profile-action.html?lang=en#building-a-journey) | 视频 | 了解如何用来自活动、数据源的信息或使用特定值更新现有的 Experience Platform 个人资料。 |

### Journey Orchestration 的更多资源

[文档](https://docs.adobe.com/content/help/zh-Hans/journeys/using/journey-orchestration-home.html) - [发行说明](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html) - [操作方法视频](https://docs.adobe.com/content/help/zh-Hans/platform-learn/tutorials/journey-orchestration/introduction.html)

## ![图标](/assets/experience_platform_appicon_24.png) Offer Decisioning {#offer-decisioning}

[!UICONTROL Offer Decisioning] 是与 Adobe Experience Platform 集成的一项应用程序服务。使用 [!UICONTROL Offer Decisioning] 可在适当的时候将优质的产品和体验提供给您在所有接触点上的客户。

### 最新产品版本

2021 年 2 月版 - 在 [Offer Decisioning 发行说明](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html?lang=en#new)中详细了解最新的功能。

### Offer Decisioning 的更多资源

[文档](https://experienceleague.adobe.com/docs/offer-decisioning/using/offer-decisioning-home.html?lang=en) - [操作方法视频](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html?lang=en)

## ![图标](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

发布日期：**2021 年 3 月 25 日**

* [Adobe Analytics 中的新增功能](#aa-features)
* [Customer Journey Analytics 的新增功能](#cust-journey)
* [Adobe Analytics 中的修复](#aa-fixes)
* [Analytics 管理员的重要注意事项](#aa-notices)  **（2021年4月6日更新）**
* [AppMeasurement](#appm)

### Adobe Analytics 中的新增功能 {#aa-features}

| 功能 | [正式发布](https://docs.adobe.com/content/help/zh-Hans/analytics/landing/an-releases.html) - 目标日期 | 描述 |
| ----------- | ---------- | ------- |
| 数据修复 API 更新 | 2021 年 3 月 25 日 | 数据修复API现在支持标准变量，包括[!UICONTROL Page]和[!UICONTROL  IP地址]、移动和视频变量，以及自定义[!UICONTROL props]和[!UICONTROL  eVars]。  可删除变量中的值，也可设置新值。该 API 现在还可过滤 URL、查询字符串、@ 符号等。 |
| Analysis Workspace：[!UICONTROL “组件”]>[!UICONTROL “用户首选项”] | 2021 年 3 月 25 日 | 通过[!UICONTROL “组件”]>[!UICONTROL “用户首选项”]页面可为用户管理 [!UICONTROL Analysis Workspace] 设置及其相关的组件。[!UICONTROL “用户首选项”]适用于所有新的项目和面板。<br>**注意：**&#x200B;以下设置已移至[!UICONTROL “用户首选项”]页面：<ul><li>报表设置：千位分隔符（现在称为&#x200B;_“数字格式”_）</li><li>报表设置：CSV 分隔符</li><li>Workspace 项目：“帮助”>“启用提示”</li><li>Workspace 项目：空白面板的&#x200B;_“用此面板开始新项目”_&#x200B;选项</li></ul> |
| Analysis Workspace：[!UICONTROL 直方图智能存储桶预测] | 2021 年 3 月 25 日 | [!UICONTROL “直方图智能存储桶预测”]帮助高势指标直方图为您的数据分布自动识别存储桶的合适宽度和数量。对于低势指标，可视化的表现与以前相同。 |
| [!UICONTROL 使用情况日志] API | 2021 年 3 月 25 日 | 这是一个新的 v2.0 Analytics API，通过它可按编程方式访问可在&#x200B;**[!UICONTROL “管理”]**>**[!UICONTROL “日志”]**>**[!UICONTROL “使用情况和访问日志”]**&#x200B;下找到的相同使用情况日志数据。可在[此处](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/usage-logs.md)找到关于身份验证、架构和示例响应的其他详细信息。 |
| Analytics 功能板支持自定义日期范围 | 2021 年 4 月 22 日 | 记分卡创建者可创建自定义日期范围并将其应用于移动记分卡项目。创建者可从熟悉的 Workspace 和移动日期范围预设中进行选择或创建自定义日期范围。[了解详情](https://experienceleague.adobe.com/docs/analytics/analyze/mobapp/curator.html#mobapp). |

### Customer Journey Analytics 的新增功能 {#cust-journey}

| 功能 | [正式发布](https://docs.adobe.com/content/help/en/analytics/landing/an-releases.html) - 目标日期 | 描述 |
| ----------- | ---------- | ----- |
| 支持 [!UICONTROL Adobe Analytics 功能板] | 2021 年 3 月 25 日 | [!UICONTROL Customer Journey Analytics] (CJA) 现在支持 [!UICONTROL Adobe Analytics 功能板记分卡生成器]和移动应用程序。这样使管理人员和商业用户可使用他们可能已用于 Adobe Analytics 的相同应用程序，根据 CJA 数据查看其跨渠道 KPI。 |
| Analysis Workspace：**[!UICONTROL “组件”]**>**[!UICONTROL “用户首选项”]** | 2021 年 3 月 25 日 | 通过[!UICONTROL “组件”]>[!UICONTROL “用户首选项”]页面可为用户管理 [!UICONTROL Analysis Workspace] 设置及其相关的组件。[!UICONTROL “用户首选项”]适用于所有新的项目和面板。<br>**注意：**&#x200B;以下设置已移至[!UICONTROL “用户首选项”]页面：<ul><li>Workspace 项目：“帮助”>“启用提示”</li><li>Workspace 项目：空白面板的&#x200B;_“用此面板开始新项目”_&#x200B;选项</li></ul> |
| Analysis Workspace：[!UICONTROL 直方图智能存储桶预测] | 2021 年 3 月 25 日 | [!UICONTROL “直方图智能存储桶预测”]帮助高势指标直方图为您的数据分布自动识别存储桶的合适宽度和数量。对于低势指标，可视化的表现与以前相同。 |
| Analytics 功能板支持 Customer Journey Analytics | 2021 年 3 月 25 日 | Analytics 功能板应用程序现在支持 Customer Journey Analytics。Customer Journey Analytics 的用户可在 Analytics 功能板应用程序中从任何引入 Adobe Experience Platform 的数据得出 KPI。通过 Customer Journey Analytics，可结合多个数据源，真正从多渠道观察客户体验。现在与 Analytics 功能板应用程序相结合，可随时随地全面了解业务的最新进展。[了解详情](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dashboards/curator.html?lang=en#cja-dashboards). |

### Adobe Analytics 中的修复{#aa-fixes}

* 修复了一个问题，其中在编辑并保存区段的新所有者之后，这名新所有者未反映在区段 UI 中。（AN-234502、AN-250970、AN-250286）
* 修复了一个问题，该问题导致应用程序报表包既使用主服务器调用，又使用移动主服务器调用。(AN-244029)
* 修复了在打开 [!UICONTROL Workspace] 项目时 UI 响应缓慢的问题。(AN-242553)
* 修复了在升级到最新版本后无法登录到 [!UICONTROL Report Builder] 的问题。(AN-248825)
* 修复了非管理员用户的用户权限问题：在 [!UICONTROL Admin Console] 中，只要将用户添加到其至少一个个人资料，该用户就应具有权限。将用户添加到个人资料应仅添加到这些用户拥有的权限，而不应删除他们通过其他产品个人资料已有资格访问的任何内容。(AN-242723)
* 修复了[!UICONTROL 数据馈送]的一个语言编码问题。(AN-249862)
* 修复了用户无法访问共享的 [!UICONTROL Workspace] 项目的问题。(AN-247814)
* 修复了[!UICONTROL 警报预览]与所触发的[!UICONTROL 警报]数量不同的问题。（AN-249392、AN-250804）

#### 其他 Adobe Analytics 修复

AN-206099、AN-237460、AN-241803、AN-243735、AN-244081、AN-244615、AN-244687、AN-246832、AN-247227、AN-248237、AN-248478、AN-248852、AN-249115、AN-249140、AN-249216、AN-249275、AN-249538、AN-249963、AN-250034、AN-250270、AN-250320、AN-250338、AN-250377、AN-250378、AN-250557、AN-250609、AN-250614、AN-250615、AN-250885、AN-251088、AN-251137、AN-251190、AN-251192、AN-251193、AN-251301、AN-251496、AN-251545、AN-251734、AN-251735、AN-251744、AN-251816、AN-251982、AN-251972、AN-252051、AN-252073、AN-252105、AN-252409、AN-252640

### [!DNL Analytics] 管理员的重要注意事项 {#aa-notices}

| 注意事项 | 添加或更新日期 | 描述 |
| ----------- | ---------- | ---------- |
| 数据馈送和Data warehouseIP地址更改 | 2021年4月6日 | 从6月17日开始，数据馈送和Data warehouse投放系统将重新部署到我们的数据中心内，因此可能会导致对您可见的外部IP地址发生更改。  您应确认，您所控制的任何目标系统的任何防火墙中都包含来自报告和源的数据中心的所有IP CIDR块。 [以下是要放入防火墙允许列表的IP地址范围的完整列表](https://https://experienceleague.adobe.com/docs/analytics/technotes/ip-addresses.html#data-collection-and-ftp-ip-address-blocks)。 |
| Analytics菜单即将更改的通知 | 2021 年 3 月 24 日 | 在2021年4月22日，我们将更新&#x200B;**[!UICONTROL Components]**、**[!UICONTROL Tools]**&#x200B;和&#x200B;**[!UICONTROL Admin]**&#x200B;下拉菜单，以获得一些性能提升。 所有这些页面仍将位于&#x200B;**[!UICONTROL 所有组件]**、**[!UICONTROL 所有工具]**&#x200B;和&#x200B;**[!UICONTROL 所有管理员]**&#x200B;链接下 — 它们将从下拉菜单中删除。 以下是将从下拉菜单中删除并放置在相应链接页面上的菜单项：<br><br> [!UICONTROL 组件]<ul><li>[!UICONTROL 书签]</li><li>[!UICONTROL 仪表板]</li><li>[!UICONTROL 目标]</li><li>[!UICONTROL 日历事件]</li><li>[!UICONTROL 计划报表]</li><li>[!UICONTROL 报表设置]</li></ul>[!UICONTROL 工具]<ul><li>[!UICONTROL Recommendations Classic]</li><li>[!UICONTROL Search&amp;Promote]</li></ul>[!UICONTROL 管理员]<ul><li>[!UICONTROL 用户管理]</li><li>[!UICONTROL 分类导入器]</li><li>[!UICONTROL 分类规则生成器]</li><li>[!UICONTROL 数据源]</li><li>[!UICONTROL Data Connectors]</li><li>[!UICONTROL 公司设置]</li><li>[!UICONTROL 日志]</li><li>[!UICONTROL Dynamic Tag Management]</li><li>[!UICONTROL 代码管理器]</li><li>[!UICONTROL 按IP排除]</li><li>[!UICONTROL 流量管理]</li></ul> |
| [!UICONTROL Same-as-SiteCatalyst VISTA Processing] = ON | 2021 年 3 月 17 日 | 在 2021 年 6 月 17 日，所有报表包都将更新为将 [!UICONTROL Same-as-SiteCatalyst VISTA Processing] 设置为 ON。此更改影响 [!UICONTROL Data Warehouse] 报表，其中处理数据以匹配处理规则。如有疑问或需要说明，请联系 Adobe 客户关怀团队。 |
| [!UICONTROL Full Processing] [!UICONTROL Data Sources] 生命周期结束 | 2021 年 3 月 10 日 | Adobe 未来打算弃用 [!UICONTROL Full Processing] [!UICONTROL Data Sources]。从 2021 年 3 月 25 日起，无法再创建此类型的新导入。请使用 [Bulk Data Insertion API](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md) 导入此类型的数据。[了解详情](https://experienceleague.adobe.com/docs/analytics/import/data-sources/data-types-and-categories/datasrc-fullproc-eol.html) |
| Reports &amp; Analytics 登陆页面选项 | 2021 年 2 月 19 日 | 2021 年 3 月 25 日，将新的 Reports &amp; Analytics 功能板或其他内容设置为 Adobe Analytics 登陆页面的选项将被移除。如果以前曾将 Reports &amp; Analytics 页面设置为自定义登陆页面，它将保持原样，直到在[!UICONTROL “用户首选项”]中修改登陆页面。 |
| Ad Hoc Analysis 生命周期终止 | 2021 月 1 日 | [!UICONTROL Ad Hoc Analysis] 于 2021 年 3 月 1 日到达其生命周期终止日期。有关详细信息，请参阅[探索工作区](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)。 |
| 三种 Analytics API 服务的生命周期终止 | 2021 年 1 月 6 日 | 2021 年 4 月 30 日，以下旧版 Analytics API 服务将达到其生命周期终止日期，并将停止使用。当前任何使用这些服务构建的集成都将在当日停止工作。<ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>旧版 OAuth 身份验证（OAuth 和 JWT）</li></ul>我们提供了[旧版 API EOL 常见问题解答](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)，以帮助回答您的问题并提供有关如何继续的指导。使用这些服务的 API 集成可以迁移到 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 或 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。旧版 OAuth 帐户可迁移到 [Adobe IO](https://console.adobe.io/home?mv=email#) Analytics 集成帐户，该帐户可用于访问 1.4 Analytics API 和 2.0 Analytics API。 |
| Adobe Data Connectors 生命周期终止 | 2020 年 7 月 13 日 | Adobe [!UICONTROL Data Connectors] 由传统技术提供支持，而这些技术不再可行或不再受支持。可在 [Adobe Exchange Partner Program](https://partners.adobe.com/exchangeprogram/experiencecloud) 中找到新标准。可使用该标准继续提供和支持任何集成。正式的生命周期结束日期为 2021 年 8 月 1 日。[了解详情...](https://docs.adobe.com/content/help/zh-Hans/analytics/import/dataconnectors/data-connectors-eol.html) |

### AppMeasurement {#appm}

有关 AppMeasurement 版本的最新更新，请参阅[适用于 JavaScript 的 AppMeasurement 发行说明](https://docs.adobe.com/content/help/zh-Hans/analytics/implementation/appmeasurement-updates.html)。

### Analytics 帮助资源

* [Adobe Analytics 产品文档及教程](https://experienceleague.corp.adobe.com/docs/analytics.html)

## ![图标](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Audience Manager 中的修复和改进。

### 修复和改进{#aam-fixes-and-improvements}

* 修复了[登记状态报告](https://experienceleague.adobe.com/docs/audience-manager/user-guide/reporting/onboarding-status-report.html)。在此问题中，报告中的记录与登记合作伙伴上传的文件中的记录之间存在差异。(AAM-57415)
* 修复了一个问题，该问题导致对于 **[!UICONTROL People-Based Destinations]** 验证重复区段映射有误。(AAM-56631)
* 修复了阻止某些用户访问 **[!UICONTROL Audience Reports]** 的问题。(AAM-57412)
* 修补了[!UICONTROL 远程执行代码]的一个漏洞，攻击者有可能利用它访问敏感数据。(AAM-57495)

### Audience Manager 的课程及教程{#tutorials-aam}

发布的关于 Audience Manager 的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 3 月 19 日 | [帮助 Audience Manager 用户了解 Real-time CDP 中的数据治理](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-data-gov-for-aam-users.html) | 视频 | 了解 [!UICONTROL Real-time Customer Data Platform] 中的数据治理功能。 |
| 2021 年 3 月 19 日 | [一个故事，两种看法 - 品牌对消费者](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/industry/brands-vs-consumers.html) | 视频 | 在这场网络研讨会中，Adobe 剖析广告商和发布者对于未来无 Cookie 场景的理解和准备程度、对其用例的影响以及他们对更广泛的生态系统有何看法。 |
| 2021 年 3 月 5 日 | [负责任的客户数据管理的 10 个注意事项](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/industry/ten-considerations-for-responsible-customer-data-management.html) | 活动 | 听取 Adobe和 Scotiabank Digital 讲述关于负责任的数据管理的重要注意事项。 |
| 2021 年 3 月 19 日 | [数据管理的未来和复杂多变的环境](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/industry/the-future-of-data-management-and-the-changing-environment.html) | 活动 | 在这场网络研讨会中，观看 Adobe 和 451 Research 如何思考技术和数据的未来以应对新型营销环境并开始为您的企业对于未来的数据管理做好准备。 |
| 2021 年 3 月 21 日 | [帮助 Audience Manager 用户了解 Real-time CDP 中的架构和 XDM](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-schemas-xdm-for-aam-users.html?lang=en#other-integrations) | 视频 | 当您从 Audience Manager 改用 Real-time Customer Data Platform (Real-time CDP) 时，您将遇到一些新的概念和做法。架构和 XDM 就属于这个类别。此视频阐明这些概念。 |
| 2021 年 3 月 17 日 | [帮助 Audience Manager 用户了解 Real-time CDP 中的信号](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-signals-for-aam-users.html) | 视频 | 此视频适用于要改用 Real-time Customer Data Platform (Real-time CDP) 的 Audience Manager 用户，其中讨论如何在 Platform 中使用您在 Audience Manager 中用于构建特征的信号（键值对）。 |
| 2021 年 3 月 12 日 | [帮助 Audience Manager 用户了解 Real-time CDP 中的架构和 XDM](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-schemas-xdm-for-aam-users.html) | 视频 | 当您从 Audience Manager 改用 Real-time Customer Data Platform (Real-time CDP) 时，您将遇到一些新的概念和做法。架构和 XDM 就属于这个类别。此视频阐明这些概念。 |
| 2021 年 3 月 12 日 | [帮助 Audience Manager 用户了解 Real-time CDP 中的 Web 数据引入](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-web-ingestion-for-aam-users.html) | 视频 | 了解关于将网站数据引入 Real-time Customer Data Platform (Real-time CDP) 的各种概念，并概括性地介绍 Audience Manager 数据连接器适合哪些方面以及数据如何能够从网站直接通过 Web SDK 引入 Real-time CDP。 |
| 2021 年 3 月 3 日 | [帮助 Audience Manager 用户了解 Real-time CDP 中的区段](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-segments-for-aam-users.html?lang=en#other-integrations) | 视频 | 了解 Audience Manager 与 Real-time CDP 之间在区段和区段创建方面的区别。 |
| 2021 年 3 月 3 日 | [帮助 Audience Manager 用户了解 Real-time CDP 中的特征](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-traits-for-aam-users.html?lang=en#other-integrations) | 视频 | 了解 Audience Manager 中的特征以及 Real-time CDP 中的哪项与其相当。 |
| 2021 年 3 月 3 日 | [帮助 Audience Manager 用户了解 Real-time CDP 中的第一方数据引入](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-1pd-ingestion-for-aam-users.html?lang=en#other-integrations) | 视频 | 了解第一方离线数据引入 Real-time Customer Data Platform (Real-time CDP) 的过程。了解这两种产品在数据引入方面的一些主要区别，并展示可怎样使用 Audience Manager 数据连接器作为过渡，直到已将流程转移到 Real-time CDP。 |
| 2021 年 3 月 1 日 | [通过在 Audience Marketplace 上提供受众信息，从您拥有的受众获得商业利益](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/audience-marketplace/selling-data/commercialize-owned-audiences-on-marketplace.html?lang=en#audience-marketplace) | 视频 | 了解如何在 Audience Marketplace 上将您的数据设置为私有或公开的数据馈送，使您成为第二方或第三方数据的数据提供者。 |
| 2021 年 3 月 | [在 Audience Manager 中创建和管理数据激活](https://experienceleague.adobe.com/?recommended=AudienceManager-U-1-2020.4) | 课程 | 在本课程中，可了解关于激活受众的一切，例如，将受众数据发给目标合作伙伴以自定义最终用户的体验。了解目标的基本情况、如何选择正确的目标以及如何根据人而非 Cookie 准备受众数据并将其发送到社交网络目标。 |
| 2021 年 3 月 | [Audience Manager 高级技能](https://experienceleague.adobe.com/?recommended=AudienceManager-U-1-2020.5) | 课程 | 掌握 Audience Manager 的基础知识后，请参加本课程以了解如何将您的 Audience Management 提升到一个新的水平。了解如何使用 AI 配合算法模型、如何使用个人资料合并规则以人而非设备的形式理解您的客户以及扩展 DMP 用法的其他精彩主题。 |

## ![图标](/assets/aem.png) Adobe Experience Manager {#aem}

Experience Manager 的新增功能、修复和更新。Adobe 建议采用内部部署的客户部署最新的修补程序以确保稳定性、安全性和性能得到提高。

>[!NOTE]
>
>Adobe 建议访问 [Experience Manager 版本更新和路线图](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html)页面以及时了解版本信息。

### 产品版本

* **AEM 6.5.8.0**
AEM 6.5 Service Pack 8（2021 年 3 月 11 日发布的 6.5.8.0）是一项重要更新，其中包括自 2019 年 4 月正式发布 AEM 6.5 以来发布的新功能、关键客户增强、改进的性能、稳定性和安全性。
   * [发行说明](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=zh-Hans#service-pack)
   * [AEM Forms 发布的交付内容](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html#forms-updates)

* **AEM 6.4.8.4**
AEM 6.4 Service Pack 8 Cumulative Fix Pack 4（2021 年 2 月 25 日发布的 6.4.8.4）是一项重要更新，其中包括自 2020 年 3 月正式发布 AEM 6.4 Service Pack 8 (6.4.8.0) 以来的若干内部和客户修复。
   * [发行说明](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=zh-Hans)
   * [AEM Forms 发布的交付内容](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html#forms-updates)

* **Adobe Experience Manager 即云服务**

   Experience Manager 即云服务上有什么新功能？

   * **Experience Manager Sites 即云服务**

      * [RemotePage 组件](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/developing/hybrid/remote-page.html?lang=en)：新增支持使用在 Experience Manager 内查看和更改外部 SPA。
      * [在 Experience Manager 内编辑外部 SPA](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/developing/hybrid/editing-external-spa.html?lang=en)：添加了将独立单页应用程序上传到 Experience Manager 实例、添加内容的可编辑部分以及启用创作的功能。
   * **Experience Manager Assets 即云服务**

      * Experience Manager Assets 即云服务有资格预先配置品牌门户 Brand Portal 。Cloud Manager 用户可在 Experience Manager Assets 即云服务上激活品牌门户。请参阅[使用品牌门户激活品牌门户](https://experienceleague.corp.adobe.com/docs/experience-manager-cloud-service/assets/brand-portal/configure-aem-assets-with-brand-portal.html)。
      * 企业现在可使用品牌门户获取资源。资源获取功能使用品牌门户帮助客户与机构用户接洽，为新营销活动、摄影和项目获取资源。请参阅《品牌门户指南》中的[资源获取概述](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/asset-sourcing-in-brand-portal/brand-portal-asset-sourcing.html?lang=en)。
      * 品牌门户使用情况报表现在仅显示有效用户。现在不显示无效用户。有效用户是其帐户在 Admin Console 中被分配给某个产品个人资料的用户。请参阅《品牌门户指南》中的[使用报表](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/admin-tools/brand-portal-reports.html?lang=en)。
      * 在品牌门户中引入了一个新的下载设置，通过该设置，在下载文件夹、收藏集等等时可为每项资源创建单独的文件夹。请参阅《品牌门户指南》中&#x200B;**从品牌门户下载资源**&#x200B;中的[下载资源](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/download/brand-portal-download-assets.html?lang=en)。
   * **Experience Manager Forms 即云服务**

      多年以来，AEM Forms 已帮助众多组织创造了优异的入职和登记体验。这些体验已帮助组织将潜在客户转化为销售、处理捕获的客户数据、根据受众个人资料提供响应式体验等等。现在 AEM Forms 提供云服务版本。

      可使用 AEM Forms 即云服务创建数字表单、将表单连接到现有数据源、将表单与 Adobe Sign 集成以将电子签名添加到表单、生成记录文档 (DoR) 以将提交的表单存档为 PDF 文件。该服务还可将您现有的 PDF 表单转换为数字表单。除了 AEM Forms 的标准功能之外，该服务还提供若干云原生的功能，如自动伸缩、升级不停机和云原生开发环境。请阅读[这篇博客帖子](https://blog.adobe.com/en/publish/2021/03/11/experience-manager-forms-as-a-cloud-service.html)以了解 AEM Forms 即云服务的功能和特性。

      可联系 Adobe 代表以索取演示或注册该服务。


   * **Experience Manager Commerce 即云服务**

      * 产品体验管理：用体验片段单独地为产品目录页丰富内容。
      * 扩展了产品控制台属性，可显示所链接的资源和体验片段，包括快速导航到相关内容的操作。
      * 发布了 CIF Venia 参考网站 - 2021.02.24，其中包括最新的 CIF 核心组件 1.8.0 版。有关更多详细信息，请参阅 [CIF Venia 参考网站 2021.02.24](https://github.com/adobe/aem-cif-guides-venia/releases/tag/venia-2021.02.24)。
      * 发布了 CIF 核心组件 1.8.0 版。有关更多详细信息，请参阅 [CIF 核心组件 1.8.0](https://github.com/adobe/aem-core-cif-components/releases/tag/core-cif-components-reactor-1.8.0)。
   * **Cloud Manager**

      * 其环境中具有预先存在的 [IP 允许列表](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/ip-allow-lists/check-ip-allow-list-status.html?lang=en#pre-existing-cdn)、[SSL 证书](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/manage-ssl-certificates/check-status-ssl-certificate.html?lang=en#pre-existing-cdn)和[自定义域名](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/custom-domain-names/check-domain-name-status.html?lang=en#pre-existing-cdn)的自定义域名配置的客户现在可看到关于其以前存在的配置的消息。他们还可通过用户界面自助服务。
      * 具有所需权限的用户现在可编辑计划，于是这些用户可按自助方式执行以下操作：
         * 将 Sites 解决方案添加到具有 Assets 的现有计划或反之。
         * 从具有 Sites 和 Assets 的现有计划中删除 Sites 或 Assets。
         * 将另一未使用的解决方案权利添加到现有计划或添加为新计划。
      * 现在对&#x200B;*“管道执行”*&#x200B;和&#x200B;*“活动”*&#x200B;屏幕都显示&#x200B;**“AEM 推送更新”**&#x200B;标签。
      * 如果环境已休眠，但还有 Experience Manager 更新可用，则&#x200B;**“已休眠”**&#x200B;状态优先于&#x200B;**“有更新可用”**。
      * 用户们现在通过在导航到 Unified Shell 的“用户个人资料”图标（右上角）之后选择&#x200B;**“查看 Cloud Manager 角色”**，即可查看其 Cloud Manager 角色。
      * 为了更加清晰明了，**“申请批准”**&#x200B;标签已变为&#x200B;**“批准生产”**。
      * “生产管道执行”屏幕中的&#x200B;**“版本”**&#x200B;标签已变为&#x200B;**“Git 标签”**。
      * 已改变定义在重要指标不符合所定义的阈值时发生的行为的若干标签以反映其真实行为：**“立即取消”**&#x200B;和&#x200B;**“立即批准”**。
      * 已根据 Experience Manager Cloud Service SDK 的 `2021.3.4997.20210303T022849Z-210225` 版本更新了类和方法的弃用列表。
      * Cloud Manager Production 管道现在包括[“自定义 UI 测试”](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/test-results/functional-testing.html?lang=en#custom-ui-testing)功能。




### **社区**

* **Adobe Developers Live 2021 | 完整的讲座列表**

   [此处](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-developers-live-2021-complete-session-list/m-p/394595#M27875)是在 **Adobe Developers Live** 上召开的所有 Experience Manager 讲座的汇总列表。

* **Adobe Summit 2021 | Experience Manager 讲座的完整列表**

   [此处](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-summit-2021-complete-aem-session-list/td-p/398344)是在 **Adobe Summit 2021** 上召开的所有 Experience Manager 讲座的汇总列表。

### Experience Manager 发行信息

所有的 Experience Manager 发行说明均保留在以下页面：

* [Experience Manager 版本更新和路线图](https://docs.adobe.com/content/help/zh-Hans/experience-manager-release-information/aem-release-updates/home.html)
* [Experience Manager 即云服务版本信息](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-service/release-notes/home.html)
* [Experience Manager Cloud Manager 发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Automated Forms Conversion Service 发行说明](https://docs.adobe.com/content/help/zh-Hans/aem-forms-automated-conversion-service/using/release-notes.html)
* [Experience Manager 6.5 Service Pack 发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
* [Experience Manager 6.4 Cumulative Fix Pack 发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-64/release-notes/cfp-release-notes.html)
* [Experience Manager Assets Dynamic Media 发行说明](https://docs.adobe.com/content/help/zh-Hans/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Experience Manager Brand Portal 发行说明](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)
* [Experience Manager 桌面应用程序发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-desktop-app/using/release-notes.html)
* [Experience Manager Dispatcher 发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-dispatcher/using/getting-started/release-notes.html)
* [Livefyre 发行说明](https://docs.adobe.com/content/help/zh-Hans/livefyre/using/release-notes/c-rn.html)

### Experience Manager 课程和教程

过去一个月发布的新视频、教程及课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 3 月 | [Experience Manager Cloud Service 上的内容交付](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/content/feb2021/content-delivery.html#content) | 活动 | Adobe Experience Manager 即云服务具有强大、预先配置的内容交付体系结构。演示如何充分利用优化的内容交付配置 |
| 2021 年 3 月 | [将关于各种类型表单和文档的帮助文章迁移到 ExL](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/document-services/pdf-forms-and-documents.html?lang=en#document-services) | 文章 | 一篇解释不同类型的 PDF 表单和文档的文章。 |
| 2021 年 3 月 | [AEM Publish 环境的生产部署](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/production-deployment.html#graphql) | 教程 | 设置本地环境以模拟将内容从 Author 实例分发到 Publish 实例。使用 GraphQL API 创建配置为从 AEM Publish 环境中使用内容的 React 应用程序的生产版本。您将逐渐学会如何有效地使用环境变量以及如何更新 AEM CORS 配置。 |
| 2021 年 3 月 | [使用 GraphQL API 进行无头内容管理](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.1.headless) | 课程 | 探索可怎样使用 AEM 的 GraphQL API 和无头功能改善在外部应用程序中浮现的体验。 |
| 2021 年 3 月 | [发布 - 特色视频](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/page-authoring/launches.html) | 视频 | AEM Sites 中的发布提供一种创建、创作和审查网站内容以供未来发布的方式。在创建发布期间，生产网站可继续像以往一样每天演进和变更。 |
| 2021 年 3 月 | [关联和取消关联资源 - 特色视频](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/authoring/relate-unrelate.html) | 视频 | 了解如何在 AEM 中建立和管理资源之间的关系。 |
| 2021 年 3 月 | [从外部应用程序向 AEM 即云服务进行身份验证](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.1.aemcs) | 课程 | 了解外部应用程序可怎样使用本地开发访问令牌和服务凭据以编程方式通过 HTTP 向 AEM 即云服务进行身份验证。 |
| 2021 年 3 月 | [在申请抵押贷款过程中填写并签署多个表单](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.7.forms) | 课程 | 使用 AEM Forms and Sign 集成，无缝地签署一套文档。输入到表单中的数据可用于预先填充这套文档中的后续表单。 |
| 2021 年 3 月 | [AEM 中的版本控制/回溯](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/page-authoring/timewarp-feature-video-use.html) | 视频 | 回溯是 Adobe Experience Manager Sites 的一项功能，它提供一种快捷的方式，让创作者可回顾页面在过去特定时间的状态。 |
| 2021 年 3 月 | [基础 - 工作流管理](https://experienceleague.adobe.com/docs/experience-manager-learn/foundation/workflow/use-workflow-management.html?lang=en#workflow) | 视频 | 此视频使用工作流模型演示这组功能，但这些功能也适用于 AEM 启动器。 |
| 2021 年 3 月 | [体验片段构建基块](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/experience-fragments/building-blocks.html) | 视频 | 构建基块是体验片段的一项分支功能。通过构建基块，内容创作者可在体验片段的不同变体间重用组件。 |
| 2021 年 3 月 | [工作流编辑器](https://experienceleague.adobe.com/docs/experience-manager-learn/foundation/workflow/use-the-workflow-editor.html?lang=en#workflow) | 视频 | 工作流在 Experience Manager 中实现业务流程管理，并用于自动处理内容以及为需要人为决策的治理和流程创造便利。 |
| 2021 年 3 月 | [AEM Assets 中的封闭用户组](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/advanced/closed-user-groups.html) | 视频 | 封闭用户组 (CUG) 是一项功能，它仅限一组精选的用户访问已发布的网站上的内容。此视频展示封闭用户组如何与 Adobe Experience Manager Assets 配合使用以仅限访问资源的特定文件夹。 |
| 2021 年 3 月 | [报表](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/advanced/asset-reports.html) | 视频 | 了解 AEM Assets 如何通过一种直观的用户体验，提供可为大型存储库扩大规模的企业级报表框架。 |
| 2021 年 3 月 | [AEM Assets 的图像智能标签](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/metadata/image-smart-tags.html) | 视频 | 图像智能标签增强 AEM 的搜索功能，其中自动并智能地根据图像的内容将元数据标签添加到图像资源。 |
| 2021 年 3 月 | [元数据层叠、可见性](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/metadata/cascade-metadata-feature-video-use.html) | 视频 | 了解字段要求、可见性和上下文选择的新动态规则。此视频还详细介绍管理员将这些规则应用于自定义元数据架构所需的步骤。 |
| 2021 年 3 月 | [项目母版](https://experienceleague.adobe.com/docs/experience-manager-learn/foundation/projects/use-project-masters.html?lang=en#delete-project-masters) | 视频 | 删除母版项目导致派生的项目不可用。 |
| 2021 年 3 月 | [自定义页面属性](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/developing/page-properties-technical-video-develop.html) | 视频 | 制作一段关于如何最佳地扩展和自定义页面属性的技术视频。 |
| 2021 年 3 月 | [翻译内容片段](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/content-fragments/content-fragments-translation-feature-video-use.html) | 视频 | 了解可怎样用 Adobe Experience Manager 本地化和翻译内容片段。还有资格提取和翻译与内容片段关联的混合媒体资源。 |
| 2021 年 3 月 | [体验片段](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/experience-fragments/experience-fragments-feature-video-use.html) | 视频 | 了解体验片段如何使内容创作者可在渠道（包括 Sites 页面和第三方系统）间重用内容。 |
| 2021 年 3 月 | [增强了 Search Boost](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/search-and-discovery/search-boost.html) | 视频 | 了解 Search Boost。 |

### Experience Manager 的其他帮助资源

* [Experience Manager 即云服务指南](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-service/landing/home.html)
* [Experience Manager 6.5 学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-5.html)
* [Experience Manager 6.4 学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-4.html)
* [Experience Manager 6.3 学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-3.html)
* [Experience Manager 6.2 学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-2.html.html)
* [Cloud Manager 用户指南](https://helpx.adobe.com/cn/experience-manager/cloud-manager/user-guide.html)
* [Experience Manager 文档的旧版本](https://helpx.adobe.com/cn/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic 帮助主页](https://docs.adobe.com/content/help/zh-Hans/dynamic-media-classic/using/home.html)

## ![图标](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign 提供了一种直观、自动的方式，以通过在线和离线营销渠道来交付一对一的消息。您现在可以利用根据客户习惯和喜好所决定的体验，来预测客户的需求。

### 最新产品版本

详细了解最新发布的功能、改进和修复：

* [Campaign Standard 发行说明](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/release-notes/release-notes.html)
* [Campaign Classic 发行说明](https://docs.adobe.com/content/help/zh-Hans/campaign-classic/using/release-notes/latest-release.html)。

>[!IMPORTANT]
>
>了解 Adobe Campaign Classic [需要的配置更新](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/acc-config-updates.html?lang=en)。

### Campaign 的新课程和教程

过去一个月发布的新视频、教程及课程。

| 发布日期 | 名称 | 解决方案 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 2 月 23 日 | [可交付性 - 可交付性的指标](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/metrics-overview.html) | Campaign Classic/Standard | 了解要监视的关键可交付性指标以及如何使用它们发现信誉问题。 |
| 2021 年 2 月 23 日 | [可交付性 - 退信](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/bounces.html) | Campaign Classic/Standard | 了解不同类型的退信。 |
| 2021 年 2 月 23 日 | [可交付性 - 投诉](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/complaints.html) | Campaign Classic/Standard | 了解当用户表示电子邮件多余或意外时提出的投诉。 |
| 2021 年 2 月 23 日 | [可交付性 - 垃圾邮件陷阱](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/spam-traps.html) | Campaign Classic/Standard | 了解不同类型的退信。 |
| 2021 年 2 月 23 日 | [可交付性 - 群发和阻止](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/bulking-and-blocking.html) | Campaign Classic/Standard | 了解 ISP 将电子邮件放入群发文件夹或阻止它们的原因。 |
| 2021 年 2 月 23 日 | [可交付性 - 过渡过程 - 基础架构](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/infrastructure.html) | Campaign Classic/Standard | 了解需要什么才能正确地构造电子邮件基础架构。 |
| 2021 年 2 月 23 日 | [可交付性 - 参与](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/engagement.html) | Campaign Classic/Standard | 了解不同类型的参与以及参与对于可交付性很重要的原因。 |
| 2021 年 2 月 23 日 | [可交付性 - 过渡过程：定位条件](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/targeting-criteria.html) | Campaign Classic/Standard | 了解如何从一开始就建立较好的信誉以有效地建立信任，然后再联系较少参与的受众。 |
| 2021 年 2 月 23 日 | [可交付性 - 过渡过程 - IP 预热期间 ISP 特有的注意事项](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/isp-specific-considerations-during-ip-warming.html) | Campaign Classic/Standard | 了解 ISP 提供商为观察其流量所制定的不同规则和方式 |
| 2021 年 2 月 24 日 | [可交付性 - 第一印象 - 简介](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/first-impressions/introduction.html) | Campaign Classic/Standard | 了解怎样才能通过在这些方面留下良好的第一印象，为成功运转电子邮件计划做好准备。 |
| 2021 年 2 月 24 日 | [可交付性 - 过渡过程：数量](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/volume.html) | Campaign Classic/Standard | 了解发送数量如何影响您的电子邮件营销活动的可交付性。 |
| 2021 年 2 月 24 日 | [可交付性 - 第一印象 - 地址收集和列表增长](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/first-impressions/address-collection-and-list-growth.html) | Campaign Classic/Standard | 了解新电子邮件地址的最佳来源是什么、如何确保较高的数据质量并遵守法律准则。 |
| 2021 年 2 月 25 日 | [可交付性 - 第一印象 - 欢迎电子邮件](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/first-impressions/welcome-emails.html) | Campaign Classic/Standard | 了解您的欢迎策略应有哪些关键要素。 |
| 2021 年 2 月 25 日 | [可交付性 - 过渡过程：切换电子邮件平台](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/switching-email-platforms.html) | Campaign Classic/Standard | 了解如何在切换电子邮件平台时平稳过渡。 |
| 2021 年 2 月 26 日 | [可交付性 - 为达到最佳可交付性的内容最佳实践](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/content-best-practices-for-optimal-delivery.html) | Campaign Classic/Standard | 关于为可交付性优化您的电子邮件内容的提示。 |
| 2021 年 2 月 26 日 | [可交付性 - 发件人持久性](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/sender-permanence.html) | Campaign Classic/Standard | 了解保持稳定的发送量很重要的原因。 |
| 2021 年 2 月 26 日 | [可交付性 - 持续监视](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/ongoing-monitoring.html) | Campaign Classic/Standard | 了解在监视交付时需要注意哪些问题。 |
| 2021 年 2 月 26 日 | [可交付性 - 付诸实施](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/putting-it-in-practice.html) | Campaign Classic/Standard | 取得成功的四大支柱。 |
| 2021 年 3 月 10 日 | [领导者、商业用户和管理员的交付性最佳实践](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.deliverability) | Campaign Classic | 了解可交付性的关键术语、概念和方法以使您可确保营销计划取得成功。 |

### 帮助资源

* Adobe Campaign Standard：[帮助中心](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/campaign-standard-home.html) - [发行说明](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [操作方法视频](https://docs.adobe.com/content/help/zh-Hans/campaign-learn/campaign-standard-tutorials/overview.html) - [发行计划](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/release-notes/release-planning.html) - [最新文档更新](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic：[帮助中心](https://docs.adobe.com/content/help/zh-Hans/campaign-classic/using/campaign-classic-home.html) - [发行说明](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html) - [操作方法视频](https://docs.adobe.com/content/help/zh-Hans/campaign-learn/campaign-classic-tutorials/overview.html)- [最新文档更新](https://docs.adobe.com/content/help/zh-Hans/campaign-classic/using/documentation-updates.html)
* Adobe Campaign 控制面板：[文档](https://docs.adobe.com/content/help/zh-Hans/control-panel/using/control-panel-home.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/control-panel/using/release-notes.html) - 有关 [Campaign Standard](https://docs.adobe.com/content/help/zh-Hans/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html)/[Campaign Classic](https://docs.adobe.com/content/help/zh-Hans/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html) 的操作方法视频

## ![图标](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Adobe Advertising Cloud 的发行说明。

* [Advertising Cloud DSP 中的新增功能](#adcloud-dsp)
* [Advertising Cloud Search 中的新增功能](#adcloud-search)

### [!DNL Advertising Cloud DSP] 中的新增功能 {#adcloud-dsp} 

上次更新日期：**2020 年 10 月 28 日**

| 功能 | 描述 |
| -----------| ---------- |
| 新建帮助 | （10 月 28 日版）旧版帮助页面已替换为更新页面，这些更新页面可从 DSP 主菜单的“帮助”链接获取，也可随时从 [https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html?lang=zh-Hans](https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html?lang=zh-Hans) 获取。 |
| Campaigns | （10 月 28 日版）以前的 Campaigns 测试版视图现在成为默认的 Campaigns 视图，可以实现更快的分析、简化的工作流和自定义视图。 |
| 专用内容库 | （10 月 15 日版）如今，所有用户都可以使用新的交易 ID 表单来设置和编辑交易 ID 详细信息，该表单是旧版[!UICONTROL 智能广告投放]表单的简化版。要设置新的交易 ID 详细信息，请转到&#x200B;**[!UICONTROL 内容库 > 交易]**，单击&#x200B;**[!UICONTROL 创建]**，然后单击&#x200B;**[!UICONTROL 交易 ID 测试版]**。 |
| 投放预测 | （10 月 15 日版）在投放设置的[!UICONTROL 预测]部分，我们为具有投放级别步调的广告投放提供了一个新增的[!UICONTROL 估计的最大量]部分，它指明了当前目标配置中的可用容量。 |

### [!DNL Advertising Cloud Search] 中的新增功能 {#adcloud-search} 

上次更新时间：**2022年3月29日，3月27日版本**

| 功能 | 描述 |
| -----------| ---------- |
| [!UICONTROL 搜索促销活动]<br>报表 | (Microsoft广告活动)现在，对Microsoft增强的按点击成本(eCPC)竞价策略提供竞价支持，该策略是Microsoft广告活动的默认竞价策略。 您现在可以为活动指定活动级别[!UICONTROL 竞价策略]。 选项包括[!UICONTROL 手动CPC]和[!UICONTROL 增强CPC]。 您可以将[!UICONTROL 增强的CPC]与搜索、现有动态搜索广告和购物活动一起使用。<br>将具有eCPC的活动添加到优化的Advertising Cloud产品组合时，Advertising Cloud将优化基本竞价，并在启用“自动调整活动预算限制”选项时优化活动预算。Microsoft应用所有竞价调整，并可能根据专有数据和洞察在用户查询时更改Advertising Cloud生成的竞价。<br>“竞 [!UICONTROL 价策] 略”自定义列可在Campaigns  视图和报表中找到。 |
| [!UICONTROL 搜索促销活动]<br> [!UICONTROL 布尔克谢特] | (Microsoft广告活动)对于扩展的文本广告，现在支持可选的第三个标题（[!UICONTROL 广告标题3]）和可选的第二个说明（[!UICONTROL 说明2]）。 [!UICONTROL Ads]视图和[!UICONTROL Bulksheets]中提供支持。 |
| [!UICONTROL 广告分析] | 提供两个新的[!UICONTROL 广告洞察]:<ul><li>[!UICONTROL 延迟的收入]:衡量组合的转化延迟（SEM点击和后续转化之间经过的时间），并显示因该滞后而在加权收入、ROI和模型准确性方面出现的任何差异。</li><li>[!UICONTROL 查询交叉匹配]:查找Google与多个关键字匹配的搜索查询实例，并提供指导流量的位置建议。</li></ul> |

### Advertising Cloud 教程和课程

更新时间：**2021 年 2 月 23 日**

| 教程 | 描述 |
| -----------| ---------- |
| [工作区和报表简介](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-analysis-workspace-a4adc.html?lang=zh-Hans) | 了解如何在 Adobe Analytics Analysis Workspace 中使用 Advertising Cloud 数据创建可视报告。 |

## ![图标](/assets/magento.png) [!DNL Magento] {#magento}

有关最新版本信息，请参阅 Magento Commerce 和开源[发行说明](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)。

## ![图标](/assets/target.png)[!DNL Target] {#target}

请参阅 [[!DNL Target]  发行说明](https://docs.adobe.com/content/help/zh-Hans/target/using/release-notes/target-release-notes.html)了解最新发行信息。

## ![图标](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] 是一个全面的应用程序，适用于寻求通过积极参与复杂购买过程的每个阶段而改善客户体验的销售线索管理和 B2B 营销人员。

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

有关 Document Cloud 的帮助，请参阅：

* [Adobe Acrobat 学习中心](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html)
* [Adobe Sign 学习中心](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html)
* [Document Cloud 学习与支持](https://helpx.adobe.com/cn/support/document-cloud.html)

## ![图标](/assets/creative-cloud-24.png) Creative Cloud Enterprise {#creative-cloud}

Creative Cloud Enterprise 的新教程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 3 月 | [了解指名用户许可](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/deploy/nameduserlicensing.html) | 文章 | 了解指名用户许可的重要性。 |
| 2021 年 3 月 5 日 | [序列号到期](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/deploy/cceserial.html) | 视频 | 了解确保最终用户可持续访问其 Adobe 应用程序和服务所需的步骤。 |
| 2021 年 3 月 | [部署和管理登陆 - 支持性资源](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/deploy/overview-deploy.html) | 视频 | 了解 Creative Cloud 企业版如何支持自定义部署和灵活的许可证调整，以及它如何与其他 Adobe 企业版产品配合工作。 |
| 2021 年 3 月 5 日 | [自定义 Adobe Stock 矢量插图中的颜色](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/customizecolors.html) | 视频 | 用美观的插图为任何项目增添亮点。在 Adobe Stock 中找到合适的矢量，然后使用 Adobe Illustrator 让颜色与您项目的调色板相匹配。 |
| 2021 年 3 月 5 日 | [自定义 Adobe Stock 演示模板，以使其看上去专业而又抢眼](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/presentationtemplate.html) | 视频 | 利用 Adobe Stock 中的图像和模板以及一些简单的特效，只需短短几分钟即可创作出风格优美的演示文稿。 |
| 2021 年 3 月 5 日 | [用 Adobe Stock 和 XD 自定义加载屏幕动画](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/loadingscreen.html) | 视频 | 自定义 Adobe Stock 中的矢量图稿，为移动应用程序创建令人惊叹的加载屏幕动画。 |
| 2021 年 3 月 5 日 | [用 Adobe Stock 图像创作逼真的合成照片](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/realisticcomposite.html) | 视频 | 将两张精彩的 Adobe Stock 照片汇集在一起，吸引人们观看您的社交帖子。 |
| 2021 年 3 月 5 日 | [用 Adobe Stock 在短时间内创作启发灵感的情绪板](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/moodboard.html) | 视频 | 创建项目情绪板，将信息、主意、视觉效果和调色板转交到团队/客户。 |
| 2021 年 3 月 5 日 | [用优美的渐变和 Adobe Stock 资源创作具有凝聚力的品牌形象](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/brandgradients.html) | 视频 | 用 Adobe Stock 的可编辑矢量将动画带入您的新闻稿图形。 |
| 2021 年 3 月 5 日 | [用 Adobe Stock 和 Photoshop 为电子邮件创作动画](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/animationemail.html) | 视频 | 用 Adobe Stock 和 Photoshop 为您的电子邮件加入停止动作动画。 |
| 2021 年 3 月 5 日 | [用 Adobe Stock 和 XD 创作交互式旅游业宣传照](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/interactivetourismphoto.html) | 视频 | 用 Adobe Stock 和 XD 在您的网站原型中快速创作交互式照片。 |
