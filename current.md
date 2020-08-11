---
title: Adobe Experience Cloud 发行说明
description: Adobe Experience Cloud 发行说明
doc-type: release notes
last-update: August 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 1a9860da58454f3e23650b8cf98e20f2819ac3be
workflow-type: tm+mt
source-wordcount: '6333'
ht-degree: 43%

---


# 早期访问-Adobe Experience Cloud发行说明- 2020年8月

![横幅](/assets/experience-cloud-banner-3.png)

此页面介绍了 [!DNL Adobe Experience Cloud] 中的新增功能、修复和重要声明。此外，还重点提供了可帮助您充分利用 Experience Cloud 的新文档、培训课程和视频教程。

>[!IMPORTANT]
>
>此页面包含预发行内容，在发行版之前可能会发生更改。

>[!NOTE]
>
>若要通过电子邮件接收有关即将发行的版本的通知，请订阅 [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html)。

**发行日期：2020 年 13 月 8 日**

产品发行日期可能有所不同。请定期查看以获取最新信息。

最新更新： **2020年8月7日**

* [Adobe 系统状态](#status)
* [Experience Cloud 界面](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Analytics](#analytics) 和 [Customer Journey Analytics](#cust-journey)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/zh-Hans/target/using/release-notes/target-release-notes.html)
* [!DNL Magento](#magento)
* [!DNL Marketo Engage](#marketo)
* [!DNL Primetime](https://docs.adobe.com/content/help/en/primetime/release-notes/home.html)

需要帮助？请访问 [Adobe Experience League](https://experienceleague.adobe.com/#home)，查找产品和技术文档、Adobe 策划课程、视频教程、快速解答、社区洞察以及由讲师指导的培训。

## ![图标](/assets/adobe.png) Adobe 系统状态 {#status}

[!UICONTROL Adobe 系统状态]提供关于 Adobe 云产品与服务中断和维护事件的详细信息、状态更新以及电子邮件通知。请访问 [status.adobe.com](https://status.adobe.com/) 查看。

请参 [阅2020年5月](c-legacy-releases/2020/05212020.md#status) 21日的最新版本信息。

## ![图标](/assets/ec_appicon_24.png) Experience Cloud 界面 {#ecloud}

有关更新的界面 [和统一的产品域](c-legacy-releases/2020/07162020.md#ecloud) ，请参阅7月份以前的发行说明。

## ![图标](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

[!DNL Experience Platform] 和应用程序服务的发行说明，包括 [!DNL Experience Platform Launch,]、[!UICONTROL Offers]、[!UICONTROL People]、[!UICONTROL Places]、[!UICONTROL Mobile Services] 和安全公告。

Latest release date: **July 15, 2020**

有关 Experience Platform 的最新信息，请参阅 [Experience Platform 发行说明](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)。

## ![图标](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

凭借 Adobe Experience Platform，可以实时智能化预测每位客户的需求（无论其旅程通达何处），从而实现跨体验渠道大规模编排客户历程。

### Campaign 的新课程和教程

过去一个月发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| ----------- | ---------- | ---------- |---------- |  
| 2020 年 7 月 10 日 | [报告旅程事件到Adobe Experience Platform](https://docs.adobe.com/content/help/en/journey-orchestration-learn/tutorials/reporting-step-events-to-adobe-experience-platform.html) | 教程 | 了解事件是什么旅程步骤，在Experience Platform上自动创建哪些数据步骤，以及如何探索这些步骤。 |

### Journey Orchestration 的其他资源

[文档](https://docs.adobe.com/content/help/zh-Hans/journeys/using/journey-orchestration-home.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/journeys/using/release-notes/release-notes.html) - [操作方法视频](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

## ![图标](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

* [Adobe Analytics 中的新增功能](#aa-features)
* [Customer Journey Analytics 的新增功能](#cust-journey)
* [Media Analytics 的新增功能](#media-aa)
* [Adobe Analytics 中的修复](#aa-fixes)
* [Analytics 管理员的重要注意事项](#aa-notices)
* [AppMeasurement](#appm)

### Adobe Analytics 中的新增功能 {#aa-features}

| 功能 | [正式发布](https://docs.adobe.com/content/help/zh-Hans/analytics/landing/an-releases.html) - 目标日期 | 描述 |
| -----------| ---------- |-------|
| 中国数据收集的增强功能 | 2020年8月13日 | 增强功能包括：支持Experience CloudID服务；支持第一方SSL;支持服务器端转发。 有关文档，请与Adobe销售代表联系。 |
| [!UICONTROL 跨设备分析]:在EMEA和APAC的上市 | 2020年8月31日 | [跨设备分析](https://docs.adobe.com/content/help/en/analytics/components/cda/overview.html) 和专用图表将面向欧洲、中东和非洲地区和亚太地区的客户。 |
| 跨设备分析(在美洲和 [!UICONTROL EMEA提供] )中增强基于现场的拼接 | 2020年8月17日 | 这为新的跨设 [!UICONTROL 备分析客户简化了实施] ，您可以根据存储在Analytics字段(prop或eVar)中的用户ID进行拼接，而不是使用设备图（合作或专用）。 该增强功能消除了实施ECID的要求，并消除了为CDA目的实施ID同步的要求。 （某些其他功能仍需要ECID和ID同步。） |
| 工作区：下载单维50K项目 | 2020年9月17日 | [提前发布] ，您将能够在自由形式表中下载单个维度的50,000个项目，并应用细分和过滤器。 这允许您访问Analysis Workspace以外的400多行数据。 |

### Customer Journey Analytics 的新增功能 {#cust-journey}

| 功能 | [正式发布](https://docs.adobe.com/content/help/zh-Hans/analytics/landing/an-releases.html) - 目标日期 | 描述 |
| -----------| ---------- |-----|
| [!UICONTROL 人员 ID 的“身份映射”选项] | 2020 年 6 月 26 日 | [!UICONTROL Identity Map] 是一种映射数据结构，允许您在Customer Journey Analytics中创建连接时上传键值对 [!UICONTROL 。]键是身份命名空间，值是包含身份值的结构。[了解更多...](https://docs.adobe.com/content/help/zh-Hans/analytics-platform/using/cja-connections/create-connection.html#use-identity-map-as-a-person-id) |

### [!UICONTROL Media Analytics] 的新增功能 {#media-aa}

发行日期：**2020 年 7 月 16 日**

| 功能 | [正式发布](https://docs.adobe.com/content/help/zh-Hans/analytics/landing/an-releases.html) - 目标日期 | 描述 |
| -----------| ---------- | ---------- |
| [支持的设备和平台](https://docs.adobe.com/content/help/zh-Hans/media-analytics/using/supported-devices.html) | 2020 年 6 月 18 日 | The [!UICONTROL Media Launch Extension] with AEP SDK now supports the following OTT devices:<ul><li>Apple TV (tvOS)</li><li>Fire TV (Fire OS)</li><li>Android TV</li></ul> |
| [播放器状态跟踪](https://docs.adobe.com/content/help/zh-Hans/media-analytics/using/player-state-tracking/player-state-overview.html) | 2020 年 5 月 29 日 | [!UICONTROL Media Analytics] 客户可以运用一组适用于全屏、隐藏式字幕、静音、画中画和聚焦的标准解决方案变量，捕获视频播放期间观看者的交互信息。您还可以灵活地创建自定义播放器状态。[!UICONTROL 播放器状态] 跟踪变量现在可用于在Analysis Workspace [!UICONTROL 报告]。 此功能需要以下任一项： <ul><li>Media [!DNL JavaScript] SDK 3.0 或更高版本</li><li>与 [!DNL Adobe Experience Platform] (AEP) SDK 一起使用时：</li><li>[!UICONTROL Media Analytics 扩展]（用于 Web）：[!UICONTROL Adobe Media Analytics] (3.x SDK) for Audio and Video v1.0 或更高版本</li><li>[!UICONTROL Media Analytics 扩展]（用于移动设备）：[!UICONTROL Adobe Media Analytics for Audio] and Video v2.0 或更高版本</li><li>[!UICONTROL 媒体收集]</li></ul> |

### Adobe Analytics 中的修复 {#aa-fixes}

* 修复了报告API未返回最新度量值的问题。 (AN-225617)
* 修复了分类规则无 [!UICONTROL 法将渠道] 分类为营销 [!UICONTROL 详细信息的问题]。 (AN-224832)
* 修复了在虚拟报告套件 _中创建新项_ 目时导致“缺 [!UICONTROL 失组件”错误的问题]。(AN-226808)
* 修复了在创建虚拟报 _告包时_ ，导致“缺失组件”错误的问题。 (AN-228257)
* 修复了阻止创建新报告和分析 [!UICONTROL 目标和日历] 事件的问题。 (AN-224872、AN-224890、AN-224914、AN-226661)
* 修复了在Workspace的A4T面板中导致缺失活动的 [!UICONTROL 问题]。 (AN-224606)
* 修复了重复源中的 [!UICONTROL 点击问题]。 (AN-226308)
* 修复了包含参与归因的计算指标无法返回正确值的问题。 (AN-224642 和 AN-225190)
* 修复了共享的区段数据在 [!DNL Analytics] 中 [!DNL Audience Manager] 显示超过三天的问题 [!DNL Audience Manager]。(AN-226649)
* 修复了无法在智能警报电子邮件中使 [!UICONTROL 用“进一步] 分析 [!UICONTROL ”链接的问题] 。 (AN-226823)
* 修复了无法在虚拟报告套件中创建区 [!UICONTROL 段的问题]。 (AN-227039)
* 修复了无法编辑智能警报的问题。 (AN-227162)

#### 其他 Adobe Analytics 修复

AN-219351;AN-220960;AN-223788;AN-224630;AN-224948;AN-225618;AN-226261;AN-226828;AN-226845;AN-226937;AN-226961;AN-227070;AN-227079;AN-227521;AN-227610;AN-228203;AN-228451;AN-228466;AN-228538

### [!DNL Analytics] 管理员的重要注意事项 {#aa-notices}

| 注意事项 | 添加或更新日期 | 描述 |
| -----------| ---------- | ---------- |
| Adobe Data Connectors 生命周期终止 | 2020 年 7 月 13 日 | Adobe [!UICONTROL Data Connectors] are powered by legacy technology that is no longer viable or supported. 我们在 [Adobe Exchange 合作伙伴项目](https://partners.adobe.com/exchangeprogram/experiencecloud)中采用了一个新标准，任何希望继续提供和支持的集成应采用此标准。正式的生命周期终止日期仍有待确定，但我们预计将会在未来 12-18 个月（2021 年中至 2021 年底）后终止。[了解更多...](https://docs.adobe.com/content/help/zh-Hans/analytics/import/dataconnectors/data-connectors-eol.html) |
| 将报表包映射到 IMS 组织 | 2020 年 7 月 | 报表包映射工具将于 2020 年 11 月停止使用。此功能支持集成，例如 Adobe Analytics 中的 Advertising Analytics 和 Experience Cloud 区段发布。必须将报表包映射到 IMS 组织，才能启用这些服务和其他服务。之后创建新的报表包时会自动映射。但是，之前的旧报表包必须手动映射到 IMS 组织。See [Map report suites to an organization](https://docs.adobe.com/content/help/zh-Hans/core-services/interface/about-core-services/report-suite-mapping.html) in the Experience Cloud interface (Core Services) user guide to make sure all report suites belong to an IMS org. |
| 迁移到统一的产品域 | 生效日期：2020 年 5 月 28 日 | 向 Adobe Analytics 统一产品域的迁移从 2020 年 1 月开始，于 2020 年 5 月 28 日完成。虽然 Adobe Analytics 会从其架构中删除所有 `omniture.com` 域引用，但务必要将 `omniture.com` 作为第三方 Cookie 添加到白名单中。（不久）完成整个架构迁移后，我们将通过发行说明通知您，此允许列表步骤将不再需要执行。[此处](https://helpx.adobe.com/cn/analytics/kb/adobe-ip-addresses.html)提供了建议应添加到白名单中的 IP 地址和域的完整列表。<br>如果贵组织阻止第三方 Cookie，请联系客户关怀团队以重新获得 Adobe Analytics 访问权限。 |
| 新的 Adobe Analytics 默认登陆页面 | 生效日期：2020 年 6 月 18 日 | 2020 年 6 月 18 日，Adobe Analytics 的默认登陆页面将从[!UICONTROL 报表]更改为[!UICONTROL 工作区]。之前未设置自定义登陆页面的任何用户都将发生此更改。 |
| 第三方技术允许列表 | 2020 年 3 月 12 日（生效日期） | Adobe Analytics 已开始利用第三方技术进行功能推出管理和提供产品内支持。应将以下 URL 添加到所有必要的网络防火墙允许列表中，以确保能够完全访问功能：<ul><li>Gainsight：https://esp.aptrinsic.com</li><li>LaunchDarkly：https://app.launchdarkly.com</li></ul> |
| 改善了 [!UICONTROL Analysis Workspace] 可用性的冗余 | 2020 年 5 月 21 日 | 为确保 [!UICONTROL Analysis Workspace] 的可用性，我们添加了辅助 CDN（内容交付网络），以改善冗余。应将以下 URL 添加到任何必要的网络防火墙允许列表中：<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| 在[!UICONTROL 工作区]中更改[!UICONTROL 登入/退出]的计算方式 | 2020 年 4 月 7 日 | 在 [!UICONTROL Analysis Workspace] 中，从 2020 年 3 月起，我们更改了&#x200B;_无_&#x200B;值与[!UICONTROL 登入/退出]的交互方式。由于您现在可以在 _Analysis Workspace_ 中打开和关闭[!UICONTROL 无]，因此我们会在登入或退出后应用&#x200B;_无_&#x200B;值，而（对于 eVar）过去是在登入或退出前应用。例如，假定访问的第一次点击没有 eVar 值，但第二次点击有。在 [!UICONTROL Reports &amp; Analytics] 中，第一次点击将针对“登入”显示为&#x200B;_未指定_，但在 [!UICONTROL Analysis Workspace] 中，将显示第二次点击时的值。 |
| **[!UICONTROL 功能板存档]**&#x200B;生命周期终止 | 2020 年 3 月 27 日 | 自 2020 年 10 月起，在 [!UICONTROL Reports &amp; Analytics] 中，位于&#x200B;**[!UICONTROL 管理功能板]**&#x200B;下方的&#x200B;**[!UICONTROL 查看存档]**&#x200B;将不再可用。 |
| Analytics 旧版 API 生命周期终止 | 2020 年 1 月 9 日 | 2020 年 11 月，以下 Analytics 旧版 API 服务将停止使用并关闭。当前使用这些服务构建的集成将会停止工作。 <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>旧版 OAuth 身份验证（OAuth 和 JWT）</li></ul>我们提供了[旧版 API EOL 常见问题解答](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)，以帮助回答您的问题并提供有关如何继续的指导。使用这些服务的 API 集成可以迁移到 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 或 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。旧版 OAuth 帐户可迁移到 [Adobe IO](https://console.adobe.io/home?mv=email) Analytics 集成帐户，该帐户可用于访问 1.4 Analytics API 和 2.0 Analytics API。 |
| 圣何塞 FTP 中转站停止为伦敦和新加坡提供支持 | 2020 年 7 月 | 对于位于伦敦和新加坡的客户，我们将不再提供伦敦或新加坡与圣何塞数据中心 [ftp.omniture.com](ftp://ftp.omniture.com/) 之间的数据中转支持。<br/><ul><li>伦敦客户，请使用 [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>新加坡客户，请使用 [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Ad Hoc Analysis 生命周期终止 | 2018 年 8 月 6 日 | Adobe 宣布计划终止 Ad Hoc Analysis 生命周期。确定终止日期后，Adobe 会立即与大家共享此信息。有关更多信息，请参阅[探索工作区](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)。 |

#### AppMeasurement

有关 AppMeasurement 版本的最新更新，请参阅[适用于 JavaScript 的 AppMeasurement 发行说明](https://docs.adobe.com/content/help/zh-Hans/analytics/implementation/appmeasurement-updates.html)。

#### Analytics 的新课程和教程 {#tutorials-analytics}

Analytics 和 Customer Journey Analytics 中的新课程、教程视频和文章。

| 发布日期 | 名称 | 类型 | 描述 |
| ----------- | ----------- | ---------- | ---------- |  
| 2020 年 7 月 30 日 | [在Admin Console中限制报表包访问](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/administration/user-management/limit-report-suite-access-in-the-admin-console.html) | 教程 | 了解如何使用 [!UICONTROL Admin Console] ，以确保用户只能访问其角色所必需的报表包。 |
| 2020 年 7 月 24 日 | [向Adobe Analytics添加管理员](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/administration/user-management/adding-an-administrator-to-adobe-analytics.html) | 教程 | 了解如何在AdobeAdmin Console中以管理员身份添加 [!UICONTROL 用户]。 |
| 2020 年 7 月 17 日 | [Analysis Workspace快速洞察小组](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/using-panels/quick-insights-panel-in-analysis-workspace.html) | 教程 | Quick Insights 可为 Analysis Workspace 的非分析师和新用户了解如何快速轻松地回答业务问题提供指导。 |
| 2020 年 7 月 17 日 | [Analysis Workspace目标(A4T)分析面板](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/integrations/target/analytics-for-target-a4t-panel-in-analysis-workspace.html) | 教程 | The [!UICONTROL Analytics for Target] (A4T) panel lets you analyze your Adobe Target activities and experiences, with lift and confidence, in Analysis Workspace. |
| 2020 年 7 月 6 日 | [创建Advertising Cloud仪表板与Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/integrations/ad-cloud/create-advertising-cloud-dashboards-with-adobe-analytics.html?lang=en#tutorials) | 教程 | 用于创建用于实时活动监视的Advertising Cloud仪表板的技术。 |
| 2020 年 7 月 6 日 | [利用Advertising Cloud数据创建分析自定义指标](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/integrations/ad-cloud/create-analytics-custom-metrics-with-advertising-cloud-data.html?lang=en#tutorials) | 教程 | 在Adobe Analytics内使用Advertising Cloud数据时创建的有用自定义指标。 |
| 2020 年 7 月 6 日 | [创建分析网站旅程用户档案](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/integrations/ad-cloud/create-analytics-site-journey-profiles.html?lang=en#tutorials) | 教程 | 如何使用Adobe Analytics为Advertising Cloud再营销创建强大的站点重定向池。 |
| 2020 年 7 月 6 日 | [为激活和报告创建分析细分](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/integrations/ad-cloud/create-analytics-segments-for-activation-and-reporting.html?lang=en#tutorials) | 教程 | 使用Advertising Cloud维度创建细分，以实现更简洁的报告和分析。 |
| 2020 年 7 月 6 日 | [与Adobe Analytics建立启动前活动分析](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/integrations/ad-cloud/reporting-with-advertising-cloud-marketing-channels.html?lang=en#tutorials) | 教程 | 如何用Adobe Analytics为Advertising Cloud付费媒体活动的启动奠定基础。 |
| 2020 年 7 月 6 日 | [Analysis Workspace项目共享](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/curate-and-share-projects/project-sharing-in-analysis-workspace.html?lang=en#tutorials) | 教程 | 项目共享是将Analysis Workspace的数据和洞察大众化到组织内用户的一种方式。 您可以将收件人放置在三个项目角色之一，具体取决于您希望他们具有的项目体验——编辑、重复和视图。 |
| 2020 年 6 月 26 日 | [Attribution IQ中的自定义回顾窗口](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/attribution-iq/custom-lookback-windows-in-attribution-iq.html?lang=en#tutorials) | 教程 | 自定义回顾窗口允许您将归因窗口扩展到报告范围以外（最长90天），并应用于报告范围内的每次转换。 |
| 2020 年 6 月 26 日 | [Analysis Workspace纯视图项目](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/curate-and-share-projects/view-only-projects-in-analysis-workspace.html?lang=en#tutorials) | 教程 | Workspace projects can be shared to users as _Can view_ only. When a _View_ recipient opens the shared project, they receive a more restrictive project experience, with no left rail and limited interactions. |
| 2020 年 6 月 26 日 | [Attribution IQ中的算法模型](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/attribution-iq/algorithmic-model-in-attribution-iq.html?lang=en#tutorials) | 教程 | Analysis Workspace 中的“[!UICONTROL 算法归因]”模型可使用统计技术动态确定所选量度的最佳点数分配方式。 |

#### Analytics 帮助资源

* [Adobe Analytics 教程](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics 产品文档](https://docs.adobe.com/content/help/zh-Hans/analytics/landing/home.html)

## ![图标](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Audience Manager 中的新增功能、修复、文档和教程。

发行日期：**2020 年 8 月 13 日**

### Adobe Audience Manager 中的新增功能和修复

* [预测受众](https://docs.adobe.com/content/help/zh-Hans/audience-manager/user-guide/features/algorithmic-models/predictive-audiences/predictive-audiences.html) 现在支持在模型创建 [!UICONTROL 过程中根据模型] 选择用户档案合并规则。 (AAM-55178)
* 目前，目标映射开始和结束日期显示在每个区段的页面中。 (AAM-40056)
* 修复了在创建新 [!UICONTROL 特征时] ，特征的“设备类 [!UICONTROL 型] ”自动设置为“跨设备”的问题。 (AAM-55368)
* 修复了Audience Marketplace无 [!UICONTROL 法加] 载的问题。 (AAM-55549)
* 当参数无法检索时，您现 [!DNL Google] 在可以从目 [!DNL Google UserList] 标中取消映射段。 (AAM-42655)
* 修复了向目标添加多个区段时无法始终正确工作的问题。 (AAM-55651)
* 修复了限制已增加的用户 [!DNL Profile Merge Rules] 看不到“添加新规 [!UICONTROL 则”按钮的问题] 。 (AAM-55700)
* 修复了“30天重 [!UICONTROL 叠的唯一用户”标题] (在“数据馈送报告度 [!UICONTROL 量”中缺失)的问题]。 (AAM-55801)
* 当目标配置为导出时，现 [!UICONTROL 在从目] 标视图 [!DNL UUID]中排除生命周期度量。(AAM-54196)
* 修复了用户无法视图报告的问 [!DNL Tableau] 题。 (AAM-55868)
* 修复了用户在创建新的预测受众模型时会收 [!UICONTROL 到错误] 的问题。 (AAM-55921)
* 改进了整个界面的多项无障碍功能。(AAM-49062、AAM-49063、AAM-49365)。

### 新的 Audience Manager 教程 {#tutorials-aam}

| 发布日期 | 名称 | 类型 | 描述 |
| ----------- | ----------- | ---------- | ---------- |
| 2020 年 7 月 8 日 | [通过抑制广告转换器节省资金并优化客户体验](https://experienceleague.adobe.com/?recommended=AudienceManager-A-1-2020.1) | 教程 | 在本课程中，学习从开始到最终完成的所有概念，用例是通过从触及活动中移除现有客户来节省资金并优化客户体验。 这包括构建特征和区段、添加正确的用户档案合并规则、向目标添加区段，甚至在您使用此用例时计算ROI。 |
| 2020 年 7 月 8 日 | [选择正确的用户档案合并规则](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/profile-merge/choosing-the-right-profile-merge-rule.html) | 教程 | 在此视频中，您会发现用户档案合并规则的三种最 [!UICONTROL 常用用例]，以及它们如何帮助您进行营销。 |
| 2020 年 8 月 5 日 | [创建区段分类](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/creating-a-segment-taxonomy.html) | 教程 | 在Audience Manager中创建区段时，将它们存储在基于文件夹的结构或分 _类中_。 了解有关创建和管理区段分类的一些提示。 |
| 2020年8月4日 | [在AdobeI/O中检索API凭据](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/api/retrieve-api-credentials-in-adobe-io.html) | 教程 | 您无需联系Adobe咨询或客户服务部门获取使用REST API的凭据，只需在浏览器 `Adobe.io` 中访问并检索或注册您自己的凭据。 |
| 2020 年 7 月 31 日 | [在段中使用近期和频率](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/using-recency-and-frequency-in-segments.html) | 教程 | 使 [!UICONTROL 用Recency][!UICONTROL 和Frequency] （最近和频率）为区段参数指定访客在特定时间段内必须符合某个特征的次数。 非常适合内容关联和频率限制用例以及其他用例。 |
| 2020 年 7 月 22 日 | [创建区段的基础知识](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/the-basics-of-creating-segments.html) | 教程 | 浏览UI中的字段，在Audience Manager中创建区段。 |
| 2020 年 7 月 22 日 | [实用细分定义与创建](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/practical-segment-definition-and-creation.html) | 教程 | 此视频会指导您定义区段，然后根据需要创建的特征和信号细分区段。 |
| 2020 年 7 月 17 日 | [抑制广告到转换器](https://video.tv.adobe.com/v/36658?captions=chi_hans) | 教程 | 通过抑制广告转化器来节省资金并优化客户体验。 |
| 2020 年 7 月 15 日 | [在客户抑制用例中衡量ROI](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/value-realization/measuring-roi-in-a-customer-suppression-use-case.html) | 教程 | 了解如何通过抑制广告给现有客户来使用几个公式来确定活动成本节省。 |
| 2020 年 7 月 10 日 | [构建细分以抑制向客户投放广告](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/building-a-segment-to-suppress-ads-to-customers.html) | 教程 | 此视频讨论创建区段以排除已转换为客户状态的区段的选项。 |

## ![图标](/assets/aem.png) Adobe Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新增功能、修复和更新。Adobe 建议那些采用内部部署的客户部署最新的修补程序，以便确保获得更高的稳定性、安全性和性能。

### **产品版本**

* **AEM 云服务**

   AEM作为Cloud Service有何新特点？ 主要亮点包括：

   * AEM Commerce现在在Cloud Service上可用。 请参 [阅AEM Commerce as aCloud Service入门。](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/commerce/getting-started.html)
   * Adobe Target和Adobe Analytics增强的连接器包括用户界面改进、经典UI替换和Adobe启动集成。 See [Integrating Adobe Analytics](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-service/sites/integrations/integrating-adobe-analytics.html) and [Integrating Adobe Target.](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-service/sites/integrations/integrating-adobe-target.html)
   * 资产计算服务是一种可扩展的可扩展服务，用于处理资产。 管理员可以配置Experience Manager以调用使用资产计算服务创建的自定义工作器。 开发人员可利用该服务来创建专门的自定义工作程序，以满足复杂用例的需求。这项 Web 服务可以为不同文件类型生成缩略图、高质量渲染 Adobe 文件格式的图像、对视频进行编码（会在未来推出）、提取元数据、提取作为索引先导的全文，以及通过所有可用的 Sensei 服务来运行资产。See [Use asset microservices and processing profiles.](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-service/assets/manage/asset-microservices-configure-and-use.html)
   * [资产计算服务](https://docs.adobe.com/content/help/en/asset-compute/using/home.html) (Asset Compute Service)可用于扩展以创建自定义应用程序。 它是处理数字资产的可扩展 [!DNL Adobe Experience Cloud] 和可扩展服务。 它可以将图像、视频、文档和其他文件格式转换为不同的再现，包括缩略图、提取的文本和元数据、存档等。 开发人员可以创建自定义应用程序（也称为自定义工作器）来解决自定义用例。 它使用Project Firefly [构建](https://www.adobe.io/apis/experienceplatform/project-firefly/docs.html) ，在无服务器的 [Adobe I/O Runtime工作](https://www.adobe.io/apis/experienceplatform/runtime.html)。
   * 作为Cloud Service,AEM中对工作流模型和Dynamic Media进行了多项改进。
   * Release 2.11.0 of the [AEM Core Components](https://docs.adobe.com/content/help/zh-Hans/experience-manager-core-components/using/introduction.html) is now available as part of AEM Sites including the following:
      * Introduction of a new [PDF Viewer Component.](https://aemcomponents.dev/content/core-components-examples/library/page-authoring/pdf-viewer.html)
      * 核心组件的加速移动页面(AMP)支持。 通过输入来自 Google 移动设备搜索结果的站点，可实现页面即时转换，这有助于提高用户参与度和 SEO，从而实现更快速的客户体验。
请参 [阅核心组件的AMP支持。](https://docs.adobe.com/content/help/zh-Hans/experience-manager-core-components/using/developing/data-layer/overview.html)
      * 与 [Adobe 客户端数据层](https://docs.adobe.com/content/help/zh-Hans/experience-manager-core-components/using/developing/data-layer/overview.html)版本 1.0.2 的兼容性。
   * Cloud Manager中的多种UI改进。
   * Cloud Manager 管道现在支持由客户设置的变量和密钥。
请参 [阅管道变量。](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/getting-access/creating-aem-application-project.html#pipeline-variables)
   * [日志可以转发给Splunk帐户](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/developing/logging.html#splunk-logs)，让组织利用其 [!DNL Splunk] 投资。
   * You can assign [a static, dedicated egress IP address](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/developing/development-guidelines.html#dedicated-egress-ip-address) for outbound traffic programmed in Java code, which may be useful for some integrations.
   * Cloud Readiness Analyzer v1.0.2已发布。 请参 [阅在AEM 6.1上安装CRA。](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-service/moving/cloud-migration/cloud-readiness-analyzer/using-cloud-readiness-analyzer.html#installing-on-aem61)
   * 请参阅AEM [作为Cloud Service的完整发行说明。](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html?mkt_tok=eyJpIjoiWm1SallqTmtOekF6WldZMCIsInQiOiJoTTZ3Qm9LNVRXc1lsbjExdlpNMGdQNFE2UGM5ejZob1EwZXlPZHp2MEZJa1BPTHhybHBYcUxFWTgwVjNFajlzYU1Fb1NoVXRwMTc3U2IrbHZKeTVSOG02MUErbWpIb1pjNU8zYkdTbW5MZHVIRUUyNk9vUU9SckdOeUJmbXlObSJ9)

### 自助服务

* **AEM Assets**

   * 添加了更多 [Experience Manager桌面](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/troubleshoot.html) 应用程序疑难解答提示。

* **AEM 表单**

   * AEM Forms的附加软件包现在可在AEM软 [件分发上获得](https://experience.adobe.com/#/downloads/content/software-distribution/en/aem.html?2_group.propertyvalues.property=.%2Fjcr%3Content%2Fmetadata%2Fdc%3Asolution&amp;2_group.propertyvalues.operation=equals&amp;2_group.propertyvalues.0_values=目标-solution%3Aaem%2Fforms&amp;orderby=%40jcr%3Content%2Fjcr%3Alast%3AlastModifiedModiedModiedSt.st.st.st.st.st.st.st.st.st.st.st.st&amp;orderby&amp;orderby.st.st.sord&amp;ord&amp;orderby.st.st.sort=des=d.s&amp;layout=列表&amp;p.offset=0&amp;p.limit=24)。 您可以在AEM Forms版本文章中找到每个受支持版本的包 [的直接链](https://helpx.adobe.com/cn/aem-forms/kb/aem-forms-releases.html) 接。
   * 使用参 [考站点](https://docs.adobe.com/content/help/en/experience-manager-65/forms/getting-started/aem-forms-reference-collaterals/forms-gov-reference-site-user-demo.html) ，了解自动化Forms转换服务的端到端工作流程。
   * AEM [6.5.5.0](https://helpx.adobe.com/experience-manager/6-5/forms/javadocs/index.html) 和AEM [6.4.8.1版本的Javaoc](https://helpx.adobe.com/experience-manager/6-4/forms/javadocs/index.html) 可用。
   * [在JEE环境上](https://docs.adobe.com/content/help/en/experience-manager-65/forms/manage-administer-aem-forms/hardening-aem-forms-environment/hardening-aem-forms-jee-environment.html#configuring-ssl) ，将可信证书导入JVM，同时强化AEM Forms。
   * 改进 [的PDF Generator设置文档。](https://docs.adobe.com/content/help/en/experience-manager-65/forms/install-aem-forms/osgi-installation/install-configure-document-services.html)

* **核心组件**

   核心组件2.11.0版引入了对AMP的支持，现在还提供创作文档 [和开发人](https://docs.adobe.com/content/help/zh-Hans/experience-manager-core-components/using/introduction.html) 员 [详细信息，以及GitHub上的项目下载。](https://github.com/adobe/aem-core-wcm-components)

### **社区**

* **Experience League的最新AEM内容**

   这是Adobe制作的数字体验技术内容的官方来源。 在此处查看完整 [列表。](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/list-of-latest-adobe-experience-manager-content-on-experience/qaq-p/373396)

### Experience Manager 的新课程和教程

过去一个月发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 7 月 8 日 | [面向商业用户的多站点管理入门](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.sites.msm) | 课程 | 了解如何通过配置核心问题（从设置基线内容架构和分类到自定义元数据和资产处理），为您的AEM Assets实施奠定坚实的基础。 |
| 2020 年 7 月 8 日 | [为管理员配置AEM Assets](https://experienceleague.adobe.com/?recommended=ExperienceManager-A-1-2020.1.assets) | 教程 | 描述 |
| 2020 年 7 月 19 日 | [使用内容传输工具](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/migration/content-transfer-tool.html) | 教程 | 内 [!UICONTROL 容传输工] 具是将内容从Experience Manager的内部部署或AMS托管版本迁移到AEM(作为Cloud Service [!UICONTROL 环境的推荐方式] 。 |
| 2020 年 7 月 21 日 | [创建Live Copy](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/create-live-copy.html) | 教程 | 了解如何使 [!UICONTROL 用创建] Live Copy向导从 [!UICONTROL Blueprint] 为 [!UICONTROL 您的站点创建Live Copy] 。 |
| 2020 年 7 月 21 日 | [Live Copy控制台](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/live-copy-overview-console.html) | 教程 | 了解如何使用Live Copy概述控制台视图或管理站点中的继承或执行转出操作。 |
| 2020 年 7 月 21 日 | [翻译项目](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/manage-translation-projects.html) | 教程 | 了解如何为语言副本创建、编辑和管理翻译 [!UICONTROL 项目]。 |
| 2020 年 7 月 21 日 | [翻译作业](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/manage-translation-projects.html) | 教程 | 了解如何将翻译作业添加到现有翻译项目。 |
| 2020 年 7 月 21 日 | [使用启动项更新语言副本](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/updating-language-copy.html) | 教程 | 了解如何借助启动项的帮助更新、审 [!UICONTROL 阅和批准] 语言副本中的更改。 |
| 2020 年 7 月 21 日 | [多站点管理概述](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/language-copy-overview.html) | 教程 | 获取有关如何使用AEM Sites语言副本创建多语 [!UICONTROL 言站点] 的概 [!UICONTROL 述]。 |
| 2020 年 7 月 21 日 | [Live Copy和Blueprint](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/live-copy-and-blueprint.html) | 教程 | 了解Live Copy与 [!UICONTROL AEM Sites] Blueprint [!UICONTROL 之] 间 [!UICONTROL 的关]系。 |
| 2020 年 7 月 21 日 | [管理页面上的Live Copy继承](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/manage-page-inheritance-live-copy.html) | 教程 | 了解如何在页面级别 [!UICONTROL 管理Live] Copy及其 [!UICONTROL Blueprint] 之间的继承。 |
| 2020 年 7 月 21 日 | [管理组件上的Live Copy继承](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/manage-component-inheritance-live-copy.html) | 教程 | 了解如何在组件级别 [!UICONTROL 管理Live] Copy及其 [!UICONTROL Blueprint] 之间的继承。 |
| 2020 年 7 月 21 日 | [创建语言副本](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/manage-component-inheritance-live-copy.html) | 教程 | 描述。 |
| 2020 年 7 月 21 日 | [创建语言副本](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/create-launguage-copy.html) | 教程 | 了解如何使用“创 [!UICONTROL 建语言副本] ”向导为AEM [!UICONTROL 站点创建语言副本]。 |
| 2020 年 7 月 21 日 | [创建多语言翻译项目](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/create-multinational-translational-project.html) | 教程 | 了解如何从AEM项目控制台为您的语言副本创建、编辑 [!UICONTROL 和管理] 多语言翻译项目。 |
| 2020 年 7 月 21 日 | [创建国家／地区站点](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/create-new-site.html) | 教程 | 了解如何使用“创建站点”向导 [!UICONTROL 从现有语言] “副本” [!UICONTROL 创建国家／地区站点] 。 |
| 2020 年 7 月 21 日 | [“创建语言副本”页](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/create-new-page-language-copy.html) | 教程 | 了解如何在现有语言副本中创 [!UICONTROL 建页面]，然后将内容翻译为其 [!UICONTROL 他语言副本]。 |
| 2020 年 7 月 21 日 | [翻译作业状态](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/translation-job-status.html) | 教程 | 了解与翻译作业或作业中的物料关联的不同状态。 |
| 2020 年 7 月 21 日 | [多站点管理简介](https://video.tv.adobe.com/v/36686?captions=chi_hans) | 教程 | 面向商业用户的多站点管理入门课程介绍。 |
| 2020 年 7 月 21 日 | [创建自适应表单片段](https://video.tv.adobe.com/v/37325?captions=chi_hans) | 教程 | 自适应表单提供了一种便捷的机制，只需创建面板或一组字段等表单段，即可在自适应表单中重复使用它们。 这些可重用和独立的细分称为自适应表单片段。 |
| 2020 年 7 月 21 日 | [AEM收件箱](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/inbox-customization/introduction.html) | 教程 | [!UICONTROL AEM Inbox整合] 来自各种AEM组件(包括Forms工作流)的通知和任务。 |
| 2020 年 7 月 21 日 | [使用日志调试 AEM SDK 的本地快速启动](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/logs.html) | 教程 | 日志是调试AEM应用程序的前线，但依赖于部署的AEM应用程序中的适当日志记录。 |
| 2020 年 7 月 21 日 | [SPA编辑器简介](https://video.tv.adobe.com/v/37705?quality=12&learn=on&captions=chi_hans) | 教程 | 面向开发人员的AEM SPA Editor入门课程介绍。 |
| 2020 | [基线权限](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/baseline-permissions.html) | 教程 | 管理对基准资产文件夹的用户访问权限是管理中的一个关键方面，并确保可以正确支持这些流程。 |
| 2020 年 7 月 21 日 | [自动开始工作流](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/auto-start-workflows.html) | 教程 | 自动开始工作流在上传或重新处理时自动调用自定义工作流，从而将AEM中的资产处理扩展为Cloud Service。 |
| 2020 年 7 月 21 日 | [使用日志调试 AEM SDK 的本地快速启动](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/logs.html) | 教程 | 日志是调试AEM应用程序的前线，但依赖于部署的AEM应用程序中的适当日志记录。 |
| 2020 年 7 月 21 日 | [创建自适应表单模板](https://video.tv.adobe.com/v/37324?captions=chi_hans) | 教程 | 当作者使用模板创建自适应表单时，新表单会继承您在模板中指定的结构和组件。 |
| 2020 年 7 月 21 日 | [创建Apache Sling Connection池化数据源](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/prefill-fdm-db/create-form-data-model.html) | 教程 | 创建RDBMS支持的表单数据模型的第一步是配置Apache Sling Connection池化数据源。 |
| 2020 年 7 月 21 日 | [使用表单数据模型预填自适应表单](https://video.tv.adobe.com/v/36387?captions=chi_hans) | 教程 | 使用表单数据模型预填表单的简介。 |
| 2020 年 7 月 21 日 | [创建您的第一个自适应表单](https://video.tv.adobe.com/v/37701?captions=chi_hans) | 教程 | 在此视频中，了解如何创建您的第一个自适应表单。 |

### Experience Manager 发行信息

所有的 Experience Manager 发行说明均保留在以下页面：

* [AEM 云服务发行信息](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/release-notes/home.html)
* [AEM Cloud Manager 发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [自动化表单转换服务发行说明](https://docs.adobe.com/content/help/zh-Hans/aem-forms-automated-conversion-service/using/release-notes.html)
* [AEM 6.5 Service Pack 发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-65/release-notes/service-pack/sp-release-notes.html)。
* [AEM 6.4 累积修复程序包发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-64/release-notes/cfp-release-notes.html)
* [AEM Assets Dynamic Media 发行说明](https://docs.adobe.com/content/help/zh-Hans/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [AEM Brand Portal 发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)
* [AEM 桌面应用程序发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-desktop-app/using/release-notes.html)
* [AEM Dispatcher 发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-dispatcher/using/getting-started/release-notes.html)
* [Adobe Primetime 发行说明](https://docs.adobe.com/content/help/en/primetime/release-notes/home.html)
* [Livefyre 发行说明](https://docs.adobe.com/content/help/zh-Hans/livefyre/using/release-notes/c-rn.html)

### AEM 的其他帮助资源

* [AEM 云服务用户指南](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-service/landing/home.html)
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

#### Campaign Classic

* 20.2.1版本——阅 [读更多](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html#release-20-2-2-build-9180)

### Campaign 的新课程和教程

过去一个月发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| ----------- | ----------- | ---------- | ---------- |  
| 2020 年 7 月 10 日 | [控制面板- GPG密钥管理——解密数据](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/gpg-key-management/decrypting-data.html) | Campaign Classic | 了解如何创建公钥并将其导入和安装在 Campaign 实例上以进行入站数据解密。 |
| 2020 年 7 月 10 日 | [控制面板- GPG密钥管理——使用GPG密钥加密数据](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/gpg-key-management/using-a-gpg-key-to-encrypt-data.html) | Campaign Classic | 了解如何使用安装在控制面板上的 GPG 密钥导出数据。 |
| 2020 年 7 月 10 日 | [控制面板-生成和安装用于数据加密的GPG密钥](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.html) | Campaign Classic | 了解如何生成公共／私有GPG密钥对并将公共密钥安装到控制面板中，以便在从实例发送数据之前对其进行加密。 |
| 2020 年 7 月 21 日 | [管理营销活动](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/managing-marketing-campaigns.html) | Campaign Classic | 了解Adobe Campaign的主要概念，帮助有效规划、执行和衡量跨渠道营销活动。 |
| 2020 年 7 月 22 日 | [创建营销计划、项目和活动](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/creating-a-marketing-plan-programs-and-campaigns.html) | Campaign Classic | 了解如何创建营销计划、项目和活动，为活动设置属性，以及了解如何使用计划。 该视频将指导您完成一个练习，您可以随后进行。 |
| 2020 年 7 月 23 日 | [创建和管理用户档案](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/profile-management/create-and-manage-profiles.html) | Campaign Classic | 了解Adobe Campaign Classic的用户档案概念。 了解如何访问用户档案数据、对用户档案进行排序和筛选以及手动创建和管理用户档案。 |
| 2020 年 7 月 28 日 | [使用条件内容个性化电子邮件](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/email-channel/personalizing-emails-create-a-multi-lingual-newsletter-using-conditional-content.html) | Campaign Classic | 阅读多语言新闻稿的示例，了解如何向投放添加条件内容。 |
| 2020 年 7 月 28 日 | [使用个性化字段个性化电子邮件](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/email-channel/personalizing-emails-using-personalization-fields.html) | Campaign Classic | 了解如何将个性化字段添加到主题行和电子邮件投放的内容。 |
| 2020 年 7 月 28 日 | [在工作流中定位用户档案](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/targeting-profiles-in-a-workflow.html) | Campaign Classic | 了解活动工作流的使用情况，了解如何使用过滤条件在工作流中创建工作流和目标用户档案。 |
| 2020 年 7 月 31 日 | [生成描述性分析报表](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/reporting/generating-a-descriptive-analysis-report.html) | Campaign Classic | 了解如何生成描述性分析报表。 |
| 2020 年 7 月 9 日 | [控制面板- GPG密钥管理——使用GPG密钥加密数据](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/gpg-key-management/using-a-gpg-key-to-encrypt-data.html) | Campaign Standard | 了解如何使用安装在控制面板上的 GPG 密钥导出数据。 |
| 2020 年 7 月 9 日 | [控制面板- GPG密钥管理——解密数据](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/gpg-key-management/decrypting-data.html) | Campaign Standard | 了解如何创建公钥并将其导入和安装在 Campaign 实例上以进行入站数据解密。 |
| 2020 年 7 月 9 日 | [控制面板- GPG密钥管理——生成和安装用于数据加密的GPG密钥](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.html) | Campaign Standard | 了解如何在指定的 Campaign 实例上生成和安装公钥/私钥对，以加密出站数据。 |

### 帮助资源

* Adobe Campaign Standard：[帮助中心](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/campaign-standard-home.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/release-notes/release-notes.html) - [操作方法视频](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [发行计划](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/release-notes/release-planning.html) - [最新文档更新](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic：[帮助中心](https://docs.adobe.com/content/help/zh-Hans/campaign-classic/using/campaign-classic-home.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/campaign-classic/using/release-notes/latest-release.html) - [操作方法视频](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)- [最新文档更新](https://docs.adobe.com/content/help/zh-Hans/campaign-classic/using/documentation-updates.html)
* Adobe Campaign 控制面板：[文档](https://docs.adobe.com/content/help/zh-Hans/control-panel/using/control-panel-home.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/control-panel/using/release-notes.html) - 有关 [Campaign Standard](https://docs.adobe.com/content/help/zh-Hans/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html)/[Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html) 的操作方法视频

## ![图标](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Adobe Advertising Cloud 的发行说明。

### [!UICONTROL Advertising Cloud Search] 中的新增功能 {#adcloud-search}

**8月8日** 发布

| 功能 | 描述 |
| -----------| ---------- |
| [!UICONTROL 组合] | Portfolio级别职位限制在组合设置中不再可用。 已删除之前创建的任何位置限制。 |
| [!UICONTROL 限制] | 不再支持基于位置的约束和约束条件：<br/><ul><li>不再提供最小Pos和最大Pos约束，并且已从之前创建的所有竞价和位置约束和印象共享约束中删除。</li><li>包含职位约束但未暂停任何投标约束的现有“投标和职位”约束。 它们仍可在UI和报告中使用。</li><li>竞价和职位限制已更名为“竞价限制”。</li><li>已删除任何类型约束中所有基于位置的条件（使用“平均位置”、“加权平均位置”或“最后已知位置”指标）。</li></ul><br/>**注意：**只要位置数据可从搜索引擎获得，位置数据就会继续填充。 Microsoft Ads将于2020年9月退休。 |  |
| [!UICONTROL 促销活动] | (Google Ads活动)Advertising Cloud Search现在支持广告客户进行响应式搜索广告(RSA)。 以前，除RSA之外，所有广告类型都支持这些广告。 |

## ![图标](/assets/magento.png) [!DNL Magento] {#magento}

有关 Magento 的发行说明，请参阅：

* [Magento Commerce 2.3.5](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-5-open-source.html)
* [Magento Open Source 2.3.5](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-5-open-source.html)

## ![图标](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] 是一个完整的应用程序，面向希望通过参与复杂购买历程的每个阶段来转变客户体验的潜在客户管理人员和 B2B 营销人员。

### 核心 Marketo Engage 更新

请参阅 [!DNL Marketo] [发行说明](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+July+%2720)了解最新发行信息。

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
