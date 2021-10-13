---
title: 最新发行说明
description: 了解 [!DNL Experience Cloud] 产品和服务的最新发行说明、新增功能和新文档。 查找有关 [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise], and [!DNL Document Cloud]的新帮助和教程。
doc-type: release notes
last-update: October 2021
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: d2d02b2130c11f1971220646ac19f4fa6f0ab5da
workflow-type: tm+mt
source-wordcount: '5553'
ht-degree: 38%

---

# Adobe Experience Cloud 发行说明 - 2021 年 10 月

![横幅](assets/experience-cloud-banner-3.png)

[!DNL Experience Cloud] 应用程序和服务每月更新一次。在此页面上可集中查找 [!DNL Experience Cloud] 和 [!DNL Experience Platform] 的最新版本更新、文档和教程。还可查找 [!DNL Creative Cloud for enterprise] 和 [!DNL Document Cloud] 的新文档。

>[!NOTE]
>
>订阅每月一期的 [Adobe Priority Product Update](https://www.adobe.com/cn/subscription/priority-product-update.html) 即可收到关于此页面更新的电子邮件通知。整月都在维护此页面，因此请定期回来查看 Adobe 企业产品和 Experience League 文档的更新。

最近更新：**2021 年 10 月 13 日**

* [[!DNL Experience League] 现场活动](#events)
* [[!DNL Experience Cloud Central Interface Components] 和管理](#ecloud)
* [Adobe [!UICONTROL 系统状态]](#status)
* [[!DNL Adobe Analytics]](#analytics) 和 [Customer Journey Analytics](#cust-journey)  **更新日期： 2021年10月7日**
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Adobe Experience Manager]](#aem) (更新日 **期：2021年10月13日**)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Commerce]](#magento)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Document Cloud]](#doc-cloud)
* [[!DNL Creative Cloud for enterprise]](#creative-cloud)

需要帮助？请访问 [Adobe Experience League](https://experienceleague.adobe.com/?lang=zh-Hans/#home)，查找产品和技术文档、Adobe 策划课程、视频教程、快速解答、社区洞察以及由讲师指导的培训。

## ![图标](/assets/experience-league.png) [!DNL Experience League] 现场活动 {#events}

[!DNL Experience League] 现场活动是与 Adobe 专家和特别嘉宾进行讨论，他们帮助向您介绍 Adobe 技术。查看下面的时间表，并参与现场活动或观看以前录制的活动。

| 活动日期 | 时间 | 活动名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2021 年 10 月 21 日 | 中午12点(EST) | [谁点击了？使用Adobe Analytics](https://www.youtube.com/channel/UCN-7ZEctit8Qu01BWeHQ0Fw)高级报告链接点击量 | 实时视频事件 | 报告用户与您的Web或移动资产的交互情况是了解客户历程的关键。 通过Adobe Analytics，您可以了解应用程序中每次点击的对象、内容、原因和位置。 向Adobe Analytics专家学习有关使用Activity Map分类和自定义归因以更好地了解用户参与度的主要提示。 |
| 2021 年 9 月 23 日 | 按需 | [专家提示让您的假日营销活动引人注目](https://www.youtube.com/watch?v=bsU1lAv0xes) | 视频直播活动 | 就像假日购物越早开始越好一样，计划非常成功的假日营销活动也是越早开始越好。借助 Adobe Campaign，您可以设计、规划和执行营销活动，使您的组织的所有假日愿望都成真。<br>但是，您知道所有有关运行营销活动的提示吗？与Sandra一起参加一次现场讨论，由三位Adobe专家参加，他们拥有大量的集体专业知识来做到这一点。 |
| 2021 年 8 月 26 日 | 按需 | [更智能地确定下一个受众区段](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-02.html?lang=zh-Hans) | 录制的活动 | 每一个好的营销活动的成功都离不开准确定位受众。利用新的 Adobe Experience Platform [!UICONTROL 区段生成器]，您可以使用各个渠道的个人资料数据和基于时间的用户行为来构建下一个受众区段。要确保您的信息传达给最需要听到的人，没有比这更好的方法了。 |
| 2021 年 7 月 29 日 | 按需 | [我喜欢的三个 Adobe Analytics 实施技巧](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-01.html?lang=zh-Hans) | 录制的活动 | 您在峰会的舞台上见过他。您曾在 Adobe Insider Tour 听到他分享专家建议。您甚至可能受益于与他合作完成自己的 Adobe Analytics 实施。现在，Eric Matisoff 将在这个专享 Experience League Live 讨论现场分享他喜欢的三个 Adobe Analytics 实施技巧。 |

{style=&quot;table-layout:auto&quot;}

有关更多视频，请访问 YouTube 上的 [Adobe Experience League 频道](https://www.youtube.com/channel/UCN-7ZEctit8Qu01BWeHQ0Fw)。

## ![图标](/assets/ec_appicon_24.png) [!DNL Experience Cloud Central UI Components] 和管理 {#ecloud}

| 功能 | 描述 |
| ------- | ------- |
| 统一搜索 | 统一搜索会继续向搜索索引中添加对象类型。 在此更新中，全局搜索现在会跨Experience League内容和以下Journey Optimizer对象类型进行搜索： <ul><li>数据集</li><li>目标</li><li>查询</li><li>架构</li><li>区段</li><li>源</li><li>优惠</li><li>组件</li><li>消息</li><li>历程</li></ul> |
| 产品使用数据同意 | 首次登录后，系统会要求您根据Experience Cloud产品使用情况数据提交首选项，以了解Adobe如何为您提供有用的个性化内容，例如教程、指南、快速提示、推荐、学习视频等。 此请求还包含对您的首选项的更新，以便在<https://experience.adobe.com/preferences>收集和使用这些数据。 |
| Experience Cloud[!UICONTROL 触发器]导航 | [Experience Cloud](https://experienceleague.adobe.com/docs/core-services/interface/services/activation/triggers.html?lang=en) 触发器可用于从应用程序切换器（位于标题中）为已配置用户进行直接导航。 |
| **注意：** 计划的界面导航更新 | 2021年11月，将从<https://experience.adobe.com/implement>中删除&#x200B;_[!UICONTROL 转到Launch /数据收集]_&#x200B;导航功能。 |

{style=&quot;table-layout:auto&quot;}

**关于 [!DNL Experience Cloud Central UI Components] 和管理**&#x200B;的更多帮助资源

* [中央界面组件](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=zh-Hans)和用户管理的管理帮助
* [地点 - 位置服务](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=zh-Hans)的帮助和发行说明
* [人员 — 客户属性和受众库](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en)帮助

## ![图标](/assets/adobe.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] 提供了关于 Adobe 产品与服务中断和维护活动的详细信息、状态更新以及电子邮件通知。请访问 [status.adobe.com](https://status.adobe.com/) 查看。

（在 [2020 年 5 月 21 日](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=zh-Hans)的发行说明中找到 [!DNL Adobe System Status] 的最新发布信息。）

## ![图标](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

发行日期：**2021 年 10 月 7 日**

* [Adobe Analytics 中的新增功能](#aa-features)
* [Customer Journey Analytics 中的新增功能](#cust-journey)  **更新日期： 2021年10月7日**
* [Adobe Analytics 中的修复](#aa-fixes)
* [Analytics 管理员的重要注意事项](#aa-notices)
* [Analytics 的课程及教程](#tutorials-analytics)
* [AppMeasurement](#appm)

### Adobe Analytics 中的新增功能 {#aa-features}

| 功能 | 描述 | [正式发布](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=zh-Hans) - 目标日期 |
| ----------- | ---------- | ------- |
| Analytics功能板的可视化图表 | Analytics [!UICONTROL 功能板]将引入三种新的可视化图表，以便执行人员和决策者更好地了解其数据。 新的[!UICONTROL 圆环图]、[!UICONTROL 折线图]和[!UICONTROL 水平]条形图都可以更轻松地查看各个维度项目的数据，而无需打开详细信息视图。 [了解详情](https://experienceleague.adobe.com/docs/analytics/analyze/mobapp/create-scorecard.html?lang=en#apply-visualizations) | 2021 年 10 月 7 日 |
| [!UICONTROL 媒体播放耗时] | Adobe流媒体播放[!UICONTROL 逗留时间]对查看者参与度提供了有价值的分析，使媒体组织能够通过使用时段划分功能进行高级逗留时间分析，从而逐分钟的用户参与度中获得更深入、更精细的洞察。 您可以观察在特定时间点观看媒体流所花费的时间。 您可以按不同的粒度（包括新的5分钟、15分钟和30分钟粒度）划分播放持续时间。 [了解详情](https://experienceleague.adobe.com/docs/media-analytics/using/media-reports/media-workspace-panels/media-playback-time-spent.html?lang=en) | 2021 年 10 月 18 日 |
| 快速[!UICONTROL 区段生成器] | 允许企业用户在一个简化的在线项目工作流程中快速应用基本区段。 无需转到[!UICONTROL 区段生成器]。 [了解详情](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/components/segments/quick-segments.html?lang=en) | 2021 年 10 月 21 日 |
| Analysis Workspace左边栏搜索改进 | 左边栏搜索将1)除继续考虑组件的新近度和相关性外，将精确匹配优先于广泛匹配。 2)突出显示匹配的字符，使搜索结果更易于理解。 3)更容易找到与维度相关的分类。 4)最后，它支持通配符(`*`)搜索，以便更轻松地找到您需要的特定组件。 注意：通配符搜索在维度项目级别尚不起作用。 | 2021 年 10 月 21 日 |
| Analysis Workspace暗主题 | 深色主题可作为显示选项使用。 | 2021 年 10 月 21 日 |

{style=&quot;table-layout:auto&quot;}

### Customer Journey Analytics 中的新增功能 {#cust-journey}

| 功能 | 描述 | [正式发布](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=en) - 目标日期 |
| ----------- | ---------- | ----- |
| [!UICONTROL 连接]数据保留的滚动窗口 | **注意：请联系客户关怀或您的Adobe客户经理以实施此设置。尚无法通过CJA UI使用。**<p>允许您在[!UICONTROL 连接]级别（而不是[!UICONTROL 数据集]级别）将CJA数据保留设置定义为以月（3个月、6个月等）表示的滚动窗口。 数据保留基于事件数据集时间戳，并且仅适用于事件数据集。 配置文件或查找数据集不存在数据保留设置，因为没有适用的时间戳。 主要好处是您仅存储或报告适用且有用的数据，并删除不再有用的旧数据。 它有助于您遵守合同限制并降低超额成本风险。 | 2021 年 10 月 7 日 |
| Report Builder支持 | Report Builder是Microsoft® [!DNL Excel]加载项，可让您使用Customer Journey Analytics数据轻松创建、编辑和刷新自定义报表。 借助Report Builder和Excel，您可以使用简单而灵活的拖放UI轻松构建复杂的数据请求。 通过Report BuilderCustomer Journey Analytics，您可以：<ul><li>引用现有工作表单元格，以获取完美的行顺序、日期范围或过滤器</li><li>使用日历、单元格引用或日期数学创建自定义日期</li><li>使用熟悉的Excel格式工具设计表格和可视化图表</li><li>适用于macOS、Microsoft 365（Web版）和Microsoft Windows上的Excel</li></ul>[了解详情](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-reportbuilder/report-buider-overview.html#) | 2021 年 10 月 7 日 |
| Analytics功能板的可视化图表 | Analytics [!UICONTROL 功能板]将引入三种新的可视化图表，以便让执行人员和决策者更好地了解其数据。 新的圆环图、折线图和水平条形图都更便于查看各个维度项目的数据，而无需打开详细信息视图。 [了解详情](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dashboards/create-scorecard.html?lang=en#apply-visualizations) | 2021 年 10 月 7 日 |
| Customer Journey Analytics审核日志API | [审核日志](https://adobe.io/cja-apis/docs/endpoints/auditlogs/) API端点允许您从Adobe请求审核日志数据。 它是安全合规性以及审核数据或用户操作的重要部分。 | 2021 年 10 月 7 日 |
| 快速[!UICONTROL 过滤器生成器] | 允许企业用户在一个简化的在线项目工作流程中快速应用基本区段。 无需转到[!UICONTROL 过滤器生成器]。 [了解详情](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-components/cja-filters/quick-filters.html?lang=en) | 2021 年 10 月 21 日 |
| Analysis Workspace左边栏搜索改进 | 左边栏搜索将1)除继续考虑组件的新近度和相关性外，将精确匹配优先于广泛匹配。 2)突出显示匹配的字符，使搜索结果更易于理解。 3)更容易找到与维度相关的分类。 4)最后，它支持通配符(`*`)搜索，以便更轻松地找到您需要的特定组件。 注意：通配符搜索在维度项目级别尚不起作用。 | 2021 年 10 月 21 日 |
| Analysis Workspace暗主题 | 深色主题可作为显示选项使用。 | 2021 年 10 月 21 日 |

{style=&quot;table-layout:auto&quot;}

### Adobe Analytics 中的修复 和 CJA {#aa-fixes}

* 修复了计划报表错误的Customer Journey Analytics。 (AN-271721)
* 修复了[!UICONTROL Workspace]中的[!UICONTROL 搜索组件]未导致完全匹配的问题。 （AN-253937、AN-271707）

#### Adobe Analytics 中的其他修复

AN-256136;AN-265420;AN-268455;AN-269768;AN-270276;AN-270287;AN-271601;AN-271969;AN-272056;AN-272111;AN-272457

### [!DNL Analytics] 管理员的重要注意事项 {#aa-notices}

| 注意事项 | 添加或更新日期 | 描述 |
| ----------- | ---------- | ---------- |
| 三种 Analytics API 服务的生命周期结束 | 2021 年 9 月 16 日 | 2021年10月20日&#x200B;****，以下Analytics旧版API服务将达到其生命周期终止日期并被关闭。 当前任何使用这些服务构建的集成都将在当日停止工作。<ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>旧版 OAuth 身份验证（OAuth 和 JWT）</li></ul>Adobe 已提供[旧版 API EOL 常见问题解答](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)以帮助回答您的问题并提供关于如何继续的指导。使用这些服务的 API 集成可以迁移到 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 或 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。旧版 OAuth 帐户可迁移到 [Adobe I/O](https://developer.adobe.com/console) Analytics 集成帐户，该帐户可用于访问 1.4 Analytics API 和 2.0 Analytics API。 |

{style=&quot;table-layout:auto&quot;}

### AppMeasurement {#appm}

有关 AppMeasurement 版本（版本 2.22.2）的最新更新，请参阅[适用于 JavaScript 的 AppMeasurement 发行说明](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=zh-Hans)。

### Analytics 的课程及教程 {#tutorials-analytics}

[!DNL Analytics]和[!UICONTROL Customer Journey Analytics]中的最新课程、教程和文章。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 10 月 | [使用可视化图表讲述您的数据故事](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2021.1.visualizations) | 课程 | 谁想在一桌又一桌的地方，试着从数据中挖掘出洞见？ 不是你！ 在本课程中，了解有关可视化的基础知识，包括如何将可视化添加到项目、将数据导入这些可视化，以及每个可视化图表可以向您显示的内容。 了解如何配置设置以获取所需的确切数据。 此外，获取一些提示和用例，帮助您使可视化图表对于常规分析更实用。 |

{style=&quot;table-layout:auto&quot;}

### Analytics 帮助资源

* [Adobe Analytics 产品文档及教程](https://experienceleague.adobe.com/docs/analytics.html?lang=zh-Hans)

## ![图标](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager 中的新增功能 - 更新于&#x200B;**2021 年 9 月 14 日**：

| 功能 | 描述 |
| ------- | ------- |
| 同意移动 ID 数据收集 | 增加了对同意移动 ID 数据收集的支持。为了从这次更新中获益，客户必须升级到 [AEP Mobile SDK iOS Core 2.8.0](https://aep-sdks.gitbook.io/docs/foundation-extensions/mobile-core/mobile-core-release-notes#november-4-2020) 或更高版本。 |

## ![图标](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

包括有关Experience Platform和[!UICONTROL Mobile SDK]的发行更新信息和新文档。

**2021 年 9 月 29 日**

| 功能 | 描述 |
| ------- | ------- |
| [[!UICONTROL 数据登陆区]](https://experienceleague.adobe.com/docs/experience-platform/sources/connectors/cloud-storage/data-landing-zone.html) | [!UICONTROL 数据登] 陆区是一个 [!DNL Platform]配置的Azure  [!UICONTROL Blob Store，] 允许每个沙盒有一个安全的临时存储，以将文件引入Experience Platform。 |
| 流源支持[数据准备](https://www.adobe.com/go/monitor-streaming-dataflows-en) | 流源现在支持数据准备，允许您提供JSON源模式，以将不兼容XDM的源数据映射到目标XDM模式。 |
| [未过期的凭据](https://experienceleague.adobe.com/docs/experience-platform/query/ui/credentials.html) | [!UICONTROL 查询服务]用户的未过期凭据允许与外部客户端建立更永久的连接，而不是每24小时续订一次凭据。 |
| [[!UICONTROL 目标SDK]](https://www.adobe.com/go/destination-sdk-overview-en) | 使用[!UICONTROL 目标SDK]与[!DNL Platform]集成，并为不断增长的目标目录做出贡献。 仅Experience Platform激活客户可访问此功能。 |

有关所有详细信息，请参阅 [Experience Platform 发行说明](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=zh-Hans)。

### Experience Platform 教程和课程 {#tutorials-platform}

发布的最新视频、教程或课程，用于Experience Platform和服务。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 10 月 | [[!DNL Platform] 管理](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-A-1-2021.1.admin) | 课程 | 了解Experience Platform的管理活动，包括权限和沙盒管理。 |

{style=&quot;table-layout:auto&quot;}

### Adobe Mobile SDK

请参阅 Adobe Experience Platform Mobile SDK 的[发行说明和更改日志](https://aep-sdks.gitbook.io/docs/release-notes)。

## ![图标](/assets/experience_platform_appicon_24.png) Journey Optimizer {#journey-opt}

有关最新的功能、改进和修复的详细信息，请参见 [Journey Optimizer 发行说明](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=zh-Hans)。

### Journey Optimizer教程及课程 {#tutorials-ajo}

最新的Journey Optimizer教程：

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 10 月 | [为数据工程师配 [!DNL Journey Optimizer] 置和管理数据](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.2) | 课程 | 了解如何在Journey Optimizer中配置和管理历程管理所需的数据。 |
| 2021 年 10 月 | [历程管理 [!DNL Journey Optimizer] 员和经理入门](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.1) | 课程 | 了解创建首个历程所需了解的所有信息。 |
| 2021 年 10 月 | [ [!DNL Journey Optimizer] 为历程管理员配置](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-A-1-2021.1) | 课程 | 了解[!DNL Journey Optimizer]架构和集成点。 了解如何配置 [!DNL Journey Optimizer]. |

{style=&quot;table-layout:auto&quot;}

### [!DNL Journey Optimizer]的更多资源

[帮助中心](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=zh-Hans) - [发行说明](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [操作方法视频](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=zh-Hans)

## ![图标](/assets/experience_platform_appicon_24.png) [!DNL Journey Orchestration] {#journey-orch}

凭借 Experience Platform，可以实时智能化预测每位客户的需求，从而实现跨体验渠道大规模编排客户历程。

### 最新的[!DNL Journey Orchestration]产品版本

有关最新的功能、改进和修复的详细信息，请参见 [[!DNL Journey Orchestration]  发行说明](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=zh-Hans)。

#### [!DNL Journey Orchestration]的更多资源

[帮助中心](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=zh-Hans) - [发行说明](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [操作方法视频](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=zh-Hans) - [最新文档更新](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=zh-Hans)

## ![图标](/assets/experience_platform_appicon_24.png) Offer Decisioning {#offer-decisioning}

[!UICONTROL Offer Decisioning] 是与Adobe Experience Platform集成的服务。使用 [!UICONTROL Offer Decisioning] 可在适当的时候将优质的产品和体验提供给您在所有接触点上的客户。

### 最新Offer decisioning产品版本

有关[Offer decisioning发行说明](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html)中最新功能、改进和修复的更多信息。

#### [!UICONTROL Offer Decisioning] 的更多资源

[帮助中心](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started/starting-offer-decisioning.html?lang=zh-Hans) - [发行说明](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [操作方法视频](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html?lang=zh-Hans) - [最新文档更新](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html)

## ![图标](/assets/aem.png) Experience Manager {#aem}

Adobe 建议访问 [Experience Manager 版本更新和路线图](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=zh-Hans)页面以及时了解版本信息。

**更新10/13/2021:** 请观看2021年9 [月版概](https://video.tv.adobe.com/v/337381) 述视频，以了解新增功能概述。

### 社区

* [Adobe开发人员上线](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk) | 2021年10月4-5日，太平洋夏季时间7:00

   Adobe开发人员上线活动将具有不同背景和独特用途的Adobe开发人员和体验构建者汇集在一起，以创造令人难以置信的端到端体验。 为期两天的会议提供重要的开发人员更新、技术会议和社区网络机会。

   跨Adobe Experience Cloud、Document Cloud和Creative Cloud的Adobe产品团队展示了最新的技术进步和开发人员工具，为跨行业的设计、内容创建工作流、文档服务和客户体验管理提供强大动力。

   Adobe计划举行20次Experience Manager会议。 传话！

   * [完成会话列表](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-developers-live-october-2021-complete-session-list/m-p/423041#M120517)
   * [免费注册 — 登录RSVP](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk)
   * [Adobe开发人员实时社区](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/registration-for-adobe-developers-live-is-now-open-october-4-5/td-p/422127)

### Experience Manager 的新课程和教程 {#tutorials-aem}

过去一个月发布的新视频、教程及课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 10 月 | [XML文档快速入门](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.xmldocs) | 课程 | 了解如何使用Adobe Experience Manager的XML文档创建、组织、创作和发布内容。 |
| 2021 年 10 月 | [使用和Assets Essentials管理创 [!DNL Workfront] 作工作流](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.2.assets.essentials) | 课程 | 了解Adobe[!DNL Workfront]和Experience Manager。 |
| 2021 年 10 月 | [AEM Assets Essentials快速入门](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.assets.essentials) | 课程 | 了解AEM Assets Essentials如何简化贵组织的资产管理。 |
| 2021 年 10 月 | [[!UICONTROL 内容传输工具]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/content-migration/content-transfer-tool.html?lang=en) | 视频 | 了解[!UICONTROL 内容传输工具]如何帮助您将内容从AEM 6.3+迁移到AEMas a Cloud Service。 |
| 2021 年 10 月 | [[!UICONTROL 批量导入服务]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/content-migration/bulk-import-service.html?lang=en) | 视频 | 了解如何使用AEM as a AssCloud Services[!UICONTROL 批量导入服务]从非AEM源导入资产。 |
| 2021 年 10 月 | [通信（输出服务）](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/communications.html?lang=en) | 视频 | 了解AEM Formsas a Cloud Service如何支持通信用例。 |
| 2021 年 10 月 | [数字注册](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/digital-enrollment.html?lang=en) | 视频 | 了解AEM Formsas a Cloud Service如何支持数字注册用例。 |
| 2021 年 10 月 | [使用 [!UICONTROL Cloud Acceleration Manager工] 具](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/using.html) | 视频 | 使用[!UICONTROL Cloud Acceleration Manager]工具的讲解演示。 |
| 2021 年 10 月 | [导航 [!UICONTROL Cloud Acceleration Manager]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/navigating.html) | 视频 | 探索[!UICONTROL Cloud Acceleration Manager]的导航体验，以了解Experience Manageras a Cloud Service。 |
| 2021 年 10 月 | [资产工作流迁移工具](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/asset-workflow-migration-tool.html) | 视频 | 了解[!UICONTROL 资产工作流迁移]工具如何帮助将您现有的AEM Assets工作流迁移到AEMas a Cloud Service。 |
| 2021 年 10 月 | [[!UICONTROL 索引转换器]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/index-converter.html) | 视频 | 了解[!UICONTROL 索引转换器]如何自动转换现有的AEM索引定义，使其与AEMas a Cloud Service兼容。 |
| 2021 年 10 月 | [[!UICONTROL Dispatcher Converter]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/dispatcher-converter.html) | 视频 | 了解[!UICONTROL Dispatcher Converter]如何自动更新现有的AEM Dispatcher配置，使其与AEMas a Cloud Service兼容。 |
| 2021 年 10 月 | [[!UICONTROL 代码存储库Modernizer]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/code-repository-modernizer.html) | 视频 | 了解[!UICONTROL 核心Repository Modernizer]如何自动更新现有AEM Maven项目，使其与AEMas a Cloud Service兼容。 |
| 2021 年 10 月 | [[!UICONTROL 代码重构工具]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/code-refactoring-tools.html) | 视频 | 了解AEM [!UICONTROL 代码重构工具]如何帮助自动转换现有AEM项目以使其as a Cloud Service兼容。 |
| 2021 年 10 月 | [[!UICONTROL 内容传输工具]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/content-transfer-tool.html) | 视频 | 了解[!UICONTROL 内容传输工具]如何让您有效地将内容从AEM 6.5移动到AEMas a Cloud Service。 |
| 2021 年 10 月 | [Cloud Acceleration Manager的实 [!UICONTROL 施阶段]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/implementation-phase.html) | 视频 | 使用[!UICONTROL Cloud Acceleration Manager]查看并了解主要实施阶段或迁移到AEMas a Cloud Service。 |
| 2021 年 10 月 | [就绪和最 [!UICONTROL 佳实践分析器]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/readiness-and-best-practice-analyzer.html) | 视频 | 了解[!UICONTROL 最佳实践分析器]如何帮助您准备从AEM内部部署或Adobe Managed Services移动到Experience Manageras a Cloud Service。 |
| 2021 年 10 月 | [Cloud Acceleration Manager简介](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/introduction.html) | 视频 | 了解[!UICONTROL Cloud Acceleration Manager]如何帮助您快速、轻松地移动到Experience Manageras a Cloud Service。 |
| 2021 年 10 月 | [AEM Formsas a Cloud Service — 迁移到AEM CS](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/introduction.html?lang=en) | 视频 | 了解AEM Formsas a Cloud Service支持的用例和功能。 |
| 2021 年 10 月 | [AEMas a Cloud Service故障诊断](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/troubleshooting.html?lang=en) | 视频 | 了解如何对AEM SDK、AEMas a Cloud Service和构建和部署过程进行故障诊断和调试。 |
| 2021 年 10 月 | [AEM  [!UICONTROL Assets微服务]  — 迁移到AEMas a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/asset-compute-microservices.html?lang=en) | 视频 | 了解AEM Assets as a Cloud Service的asset compute微服务如何允许您自动高效地为资产生成任何演绎版，从而取代传统AEM工作流的这一角色。 |
| 2021 年 10 月 | [搜索和索引](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/search-and-indexing.html?lang=en) | 视频 | 了解AEMas a Cloud Service搜索索引，如何将AEM 6索引定义转换为与AEMas a Cloud Service兼容，以及如何将索引部署到AEMas a Cloud Service。 |
| 2021 年 10 月 | [[!UICONTROL Dispatcher]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/dispatcher.html?lang=en) | 视频 | 了解AEM [!UICONTROL Dispatcher] for AEMas a Cloud Service，重点介绍对AEM 6的[!UICONTROL Dispatcher]、[!UICONTROL Dispatcher]转换工具以及如何使用Dispatcher Tools SDK做出的显着更改。 |
| 2021 年 10 月 | [[!UICONTROL Cloud Manager]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/cloud-manager.html?lang=en) | 视频 | 了解Cloud Manager for AEMas a Cloud Service，以及它与Cloud Manager for AEM on Adobe Manage Services(AMS)的差异。 |
| 2021 年 10 月 | [上手使用 AEM as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/onboarding.html?lang=en) | 视频 | 了解从合同阶段开始，通过使用[!UICONTROL Cloud Manager]设置环境，从始至终的AEMas a Cloud Service入门。 |
| 2021 年 10 月 | [存储库现代化](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/repository-modernization.html?lang=en) | 视频 | 了解存储库现代化、可变和不可变内容、包结构和存储库现代化器CLI工具。 |
| 2021 年 10 月 | [[!UICONTROL AEM 现代化工具]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-modernization-tools.html?lang=en) | 视频 | 了解如何使用AEM [!UICONTROL 现代化工具]升级现有AEM项目和内容，使其与AEMas a Cloud Service兼容。 |
| 2021 年 10 月 | [AEM 现代化工具](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/introduction.html?lang=en) | 视频 | 了解如何以不同方式考虑AEMas a Cloud Service实施。 |
| 2021 年 10 月 | [Best Practice Analyzer和Cloud Acceleration Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/bpa-and-cam.html?lang=en) | 视频 | 了解Best Practice Analyzer(BPA)和Cloud Acceleration Manager(CAM)如何为迁移到AEMas a Cloud Service提供自定义指南。 |
| 2021 年 10 月 | [维护版本历史记录](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/versions.html) | 视频 | 了解Adobe Workfront和Assets Essentials]如何帮助您维护[!DNL Workfront]文档和Assets Essentials资产的版本。[!UICONTROL  |
| 2021 年 10 月 | [发送文档和链接资产](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/link-send.html?lang=en) | 视频 | 了解如何将Workfront文档发送到Assets Essentials，以及将Assets Essentials资产关联到Workfront。 |
| 2021 年 10 月 | [配置该集成](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/configure.html?lang=en) | 视频 | 了解如何配置Adobe Workfront和Assets Essentials集成。 |
| 2021 年 10 月 | [什么是数字签名](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/sign-with-a-digital-signature.html?lang=en) | 视频 | 了解基于证书的数字签名，它符合全球最严格的法律法规，并为签名者的身份提供最高级别的保证。 |
| 2021 年 10 月 | [Adobe Analytics中的区段生成器](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/segment-builder-overview.html?lang=en#) | 视频 | 在Adobe Analytics中通过分段对数据进行细分。 此视频将指导您完成[!UICONTROL 区段生成器]并提供基本概述。 |
| 2021 年 10 月 | [映射元数据](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/map-metadata.html?lang=en) | 视频 | 了解如何配置Workfront字段和Assets Essentials属性之间的元数据映射，以及如何配置Assets Essentials以显示映射的值。 |

{style=&quot;table-layout:auto&quot;}

### Experience Manager 发行信息 {#aem-links}

以下是 Experience Manager 的发行说明和其他发行信息链接：

* [[!DNL Experience Manager as a Cloud Service] 发行说明](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html?lang=zh-Hans)
* [[!DNL Experience Manager as a Cloud Service] 发行信息](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/home.html?lang=zh-Hans)
* [[!DNL Experience Manager Cloud Manager] 发行说明](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=zh-Hans)
* [Automated Forms Conversion Service 发行说明](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=zh-Hans)
* [Experience Manager 6.5 Service Pack 发行说明](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=zh-Hans)
* [Experience Manager 6.4 Cumulative Fix Pack 发行说明](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=zh-Hans)
* [[!DNL Experience Manager Assets Dynamic Media] 发行说明](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=zh-Hans)
* [[!DNL Experience Manager Brand Portal] 发行说明](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=zh-Hans)
* [Experience Manager 桌面应用程序发行说明](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=zh-Hans)
* [[!DNL Experience Manager Dispatcher] 发行说明](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=zh-Hans)
* [Adobe Primetime 发行说明](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html?lang=zh-Hans)
* [Livefyre 发行说明](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=zh-Hans)

### Experience Manager 的其他帮助资源

* [[!DNL Experience Manager as a Cloud Service] 指南](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/landing/home.html?lang=zh-Hans)
* [Experience Manager 6.5 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=zh-Hans)
* [Experience Manager 6.4 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=zh-Hans)
* [Experience Manager 6.3 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=zh-Hans)
* [Experience Manager 6.2 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=zh-Hans#previous-updates)
* [Experience Manager 文档的旧版本](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [[!DNL Cloud Manager] 用户指南](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=zh-Hans)
* [[!DNL Dynamic Media Classic] 帮助主页](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=zh-Hans)
* [Experience Manager 文档：最近的更新](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=zh-Hans#aem-as-a-cloud-service)

## ![图标](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign 提供了一种直观、自动的方式，以通过在线和离线营销渠道来交付一对一的消息。您现在可以利用根据客户习惯和偏好确定的体验，来预测客户的需求。

### 最新营销活动产品版本

详细了解最新发布的功能、改进和修复：

* [Campaign v8 发行说明](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/release-notes.html?lang=zh-Hans)
* [Campaign Classic v7 发行说明](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=zh-Hans)
* [Campaign Standard 发行说明](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=zh-Hans)

### [!UICONTROL Campaign] 的新课程及教程 {#tutorials-campaign}

Adobe Campaign的最新教程和课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 10 月 | [使用Adobe Campaign V8为企业用户构建高级营销活动](https://experienceleague.adobe.com/?recommended=Campaign-U-1.2021.1.v8) | 课程 | 了解如何使用Adobe Campaign V8配置和执行高级营销活动。 了解先决条件、构建和配置高级营销活动、投放，以及管理订阅。 |
| 2021 年 10 月 | [在工作流中使用SOAP API — 简介](https://experienceleague.adobe.com/docs/campaign-learn/use-soap-apis/introduction.html?lang=en) | 教程 | 了解如何使用Adobe Campaign Soap API并根据通过API收到的数据创建高级交付工作流。 |
| 2021 年 10 月 | [创建事件](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/journey-configuration/create-events.html?lang=en) | 教程 | 了解如何配置事件、指定流端点和事件的有效负载。 |
| 2021 年 10 月 | [配置数据源](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/journey-configuration/configure-data-sources.html?lang=en) | 教程 | 了解数据源，并了解如何配置Experience Platform和外部数据源。 |
| 2021 年 10 月 | [用例 — 突发消息](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-journeys/use-case-burst-message.html?lang=en) | 教程 | 了解突发消息的适用用例。了解如何为突发消息配置历程以及要应用的最佳实践。 |

{style=&quot;table-layout:auto&quot;}

### 营销活动帮助资源

* Adobe Campaign v8：[帮助中心](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=zh-Hans) - [发行说明](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/whats-new.html?lang=zh-Hans) - [实施指南](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=zh-Hans)
* Adobe Campaign Standard：[Campaign Standard 文档](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=zh-Hans) - [发行说明](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [操作方法视频](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=zh-Hans) - [发行计划](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=zh-Hans) - [最新文档更新](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=zh-Hans)
* Adobe Campaign Classic：[Campaign Classic v7 文档](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=zh-Hans) - [发行说明](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [操作方法视频](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=zh-Hans) - [最新文档更新](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=zh-Hans)
* Adobe Campaign 控制面板：[文档](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hans) - [发行说明](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=zh-Hans) - 有关 [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=zh-Hans)/[Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=zh-Hans) 的操作方法视频

## ![图标](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

[!DNL Adobe Advertising Cloud] 的发行说明。

* [ [!DNL Advertising Cloud DSP] 中的新增功能](#adcloud-dsp)
* [ [!DNL Advertising Cloud Search] 中的新增功能](#adcloud-search)

### [!DNL Advertising Cloud DSP] 中的新增功能 {#adcloud-dsp}

上次更新时间：**2021年9月28日**

| 功能 | 描述 |
| ------- | ----------- |
| 促销活动管理视图 | 现在，“[!UICONTROL 创建日期]”列在[!UICONTROL 促销活动]、[!UICONTROL 包]、[!UICONTROL 版面]和[!UICONTROL 广告]视图的自定义列集中可用。 您还可以通过[!UICONTROL 创建日期]过滤[!UICONTROL 版面]和[!UICONTROL 广告]视图。 |
| 程序化保证交易 | （9月8日发布）现在，您可以编辑程序化保证(PG)交易的默认位置的[!UICONTROL 最高竞价]。 但是，由于PG交易始终具有固定的CPM，因此只有国际客户才应编辑[!UICONTROL 最高竞价]以考虑货币兑换费用。 |
|  | （9月8日发布）现在，具有“[!DNL FreeWheel Programmatic Guaranteed]”权限的用户可以从[!UICONTROL 广告]视图或[!UICONTROL 版面]视图向[!DNL FreeWheel Programmatic Creative API]提交广告。 您仍可以从[!UICONTROL Deals]视图提交广告。 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Advertising Cloud Search] 中的新增功能 {#adcloud-search}

上次更新时间：**2021年9月28日**

| 功能 | 描述 |
| ------- | ----------- |
| 广告见解 | 在测试版模式下，提供了其他分析。 |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/magento.png) [!DNL Commerce] (Magento) {#magento}

有关 Adobe Commerce 发行说明，请参阅以下链接：

* [Adobe Commerce 和 Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [适用于 Adobe Commerce 的云套件](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

## ![图标](/assets/target.png) [!DNL Target] {#target}

上次更新日期：**2021 年 8 月 3 日**

请参阅[[!DNL Target] 发行说明](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=zh-Hans)了解最新发行信息。

## ![图标](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] 是一个全面的应用程序，适用于寻求通过积极参与复杂购买过程的每个阶段而改善客户体验的销售线索管理和 B2B 营销人员。

### 核心 Marketo Engage 更新

有关最新的发布计划信息和发行说明，请参阅[!DNL Marketo Engage] [发布计划](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=zh-Hans)。

## ![图标](/assets/workfront.png) [!DNL Workfront] {#workfront}

Adobe [!DNL Workfront] 是一个统一的工作管理应用程序，可用于分享创意、创建内容、管理复杂的流程以及将工作做到尽善尽美。

请参阅[[!DNL Workfront] 版本](https://one.workfront.com/s/product-releases)页面，查看所有产品的最新信息综述。

## ![图标](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

为 Adobe Document Cloud 发布的新视频、教程或课程。

### Document Cloud 课程和教程 {#tutorials-doc-cloud}

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 10 月 | [什么是数字签名？](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/sign-with-a-digital-signature.html?lang=en) | 视频 | 了解如何使用Adobe Sign使用来自全球的数字ID。 |
| 2021 年 10 月 | [Adobe Sign新发件人入门](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-sending/new-sender.html) | 视频 | 如果您是初次使用Adobe Sign，则可以从本教程开始学习。 本完整的教程重点介绍帮助您快速启动并运行Adobe Sign的所有基础知识。 |
| 2021 年 10 月 | [将PDF注释加载到InDesign](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/indesign.html) | 视频 | 在此60秒的视频教程中，了解如何在Acrobat共享审阅后将PDF评论加载回InDesign。 此数字工作流可帮助您在创纪录的时间内完成修订。 |
| 2021 年 10 月 | [从 [!DNL Intesi Group] 获取数字ID（符合条件）](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-qualified.html) | 视频 | 了解如何从[!DNL Intesi]组获取合格的数字签名证书。 注册并验证您的身份后，[!DNL Intesi]组会向您发出用于应用Adobe Sign云签名的数字ID问题。 |
| 2021 年 10 月 | [使用进行签名 [!DNL Intesi Group]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-sign.html) | 视频 | 了解如何使用您的Intesi Group数字ID来验证您的身份，并在文档上授权远程数字签名（云签名）。 |
| 2021 年 10 月 | [从 [!DNL Intesi Group] 获取数字ID（高级）](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-advanced.html) | 视频 | 了解如何从英特尔组获取高级数字签名证书。 注册并验证您的身份后，Intesi Group会向您发送用于应用Adobe Sign云签名的数字ID。 |
| 2021 年 10 月 | [使用进行签名 [!DNL Digidentity]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/digidentity/digidentity-sign.html) | 视频 | 了解如何使用[!DNL Digidentity]数字ID来验证您的身份，并授权文档上的远程数字签名（云签名）。 |
| 2021 年 10 月 | [从获取数字ID [!DNL Digidentity]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/digidentity/digidentity-reg.html) | 视频 | 了解如何从[!DNL Digidentity]获取数字签名证书。 注册并验证您的身份后，[!DNL Digidentity]会向您发出用于应用Adobe Sign云签名的数字ID。 |
| 2021 年 10 月 | [检测两个PDF之间的差异](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/compare.html) | 视频 | 切勿使用错误版本的文件。 快速、准确地检测两个PDF文件之间的差异，以改进文档审阅工作流。 |
| 2021 年 10 月 | [使用Microsoft® Edge浏览时创建PDF内容](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/edge.html) | 视频 | 了解如何使用Microsoft® Edge的Adobe Acrobat扩展即时存档网页以PDF。 此仅限Windows的工具对于研究项目和离线查看基于Web的信息非常有价值。 |
| 2021 年 10 月 | [在Outlook中将电子邮件和附件转换为PDF](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/outlook.html) | 视频 | 了解如何在Outlook中为您的项目存档电子邮件和附件以PDF。 了解如何通过自动将附件转换为PDF，以更专业、更安全的方式提供信息。 此工具仅适用于Windows。 |

{style=&quot;table-layout:auto&quot;}

有关 Document Cloud 的帮助，请参阅：

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=zh-Hans)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=zh-Hans)
* [Document Cloud 学习与支持](https://helpx.adobe.com/cn/support/document-cloud.html)

## ![图标](/assets/creative-cloud-24.png) Creative Cloud 企业版 {#creative-cloud}

有关最新教程，请参阅[企业教程Creative Cloud](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=zh-Hans) 。
