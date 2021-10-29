---
title: 最新发行说明
description: 了解  [!DNL Experience Cloud] 产品和服务的最新发行说明、新增功能和新文档。查找有关  [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise], and [!DNL Document Cloud] 的新的帮助内容和教程。
doc-type: release notes
last-update: November 2021
author: mfrei
mini-toc-levels: 1
exl-id: null
source-git-commit: 88923d059ec73215facae2efc1888b07b2e60fc7
workflow-type: tm+mt
source-wordcount: '4513'
ht-degree: 55%

---

# Adobe Experience Cloud 发行说明 - 2021 年 11 月

![横幅](assets/experience-cloud-banner-3.png)

[!DNL Experience Cloud] 应用程序和服务每月更新一次。在此页面上可集中查找 [!DNL Experience Cloud] 和 [!DNL Experience Platform] 的最新版本更新、文档和教程。还可查找 [!DNL Creative Cloud for enterprise] 和 [!DNL Document Cloud] 的新文档。

>[!NOTE]
>
>订阅每月一期的 [Adobe Priority Product Update](https://www.adobe.com/cn/subscription/priority-product-update.html) 即可收到关于此页面更新的电子邮件通知。整月都在维护此页面，因此请定期回来查看 Adobe 企业产品和 Experience League 文档的更新。

发布月份： **2021年11月**

最近更新：**2021 年 10 月 28 日**

* [[!DNL Experience League] 现场活动](#events)
* [[!DNL Experience Cloud Central Interface Components] 和管理](#ecloud)
* [Adobe [!UICONTROL 系统状态]](#status)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics) 和 [Customer Journey Analytics](#cust-journey)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL Adobe Commerce]](#magento)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Journey Orchestration]](#journey-orch)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Adobe Advertising Cloud]](#adcloud) (**2021 年 10 月 27 日**)
* [[!DNL Document Cloud]](#doc-cloud)
* [[!DNL Creative Cloud for enterprise]](#creative-cloud)

需要帮助？请访问 [Adobe Experience League](https://experienceleague.adobe.com/?lang=zh-Hans/#home)，查找产品和技术文档、Adobe 策划课程、视频教程、快速解答、社区洞察以及由讲师指导的培训。

## ![图标](/assets/experience-league.png) [!DNL Experience League] 现场活动 {#events}

[Experience League实时事件](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=en) 是与Adobe专家和特邀客人进行的讨论，这些专家和特邀客人在为您带来Adobe技术方面发挥了重要作用。 查看下面的时间表，并参与现场活动或观看以前录制的活动。

| 活动日期 | 时间 | 活动名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2021 年 11 月 18 日 | TBA | 在Experience Manager中快速创建网站，使其上线速度比以往任何时候都快 | 视频直播活动 | Experience Manager Sites包含几项功能，可加快交付引人入胜的Web体验。 了解如何使用低代码方法通过预定义的网站模板在Adobe Experience Manager中创建网站。 更多细节待定！ |
| 2021 年 10 月 21 日 | 按需 | [谁点击了？有关 Adobe Analytics 的链接点击的高级报告](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=en) | 视频直播活动 | 有关用户与您的 Web 或移动资产的互动的报告是了解客户历程的关键部分。利用 Adobe Analytics，您可以了解应用程序中的每次点击的人员、内容、原因和位置。从 Adobe Analytics 专家那里获得有关使用 Activity Map 分类和自定义属性更好地了解用户参与的重要技巧。 |
| 2021 年 10 月 4 日 | 按需 | [Adobe开发人员上线](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2021/oct2021/overview.html?lang=en) | 视频 | 是否错过了事件或正在查找特定会话的重播？ 在Experience League上找到它们。 开发人员上线展示了最新的技术进步和开发人员工具，为各行业的设计、内容创建工作流程、文档服务和客户体验管理提供强大动力。 查看主旨演讲、了解Analytics API、客户端数据层、Adobe I/O开源项目等。 |

{style=&quot;table-layout:auto&quot;}

有关更多视频，请访问 YouTube 上的 [Adobe Experience League 频道](https://www.youtube.com/channel/UCN-7ZEctit8Qu01BWeHQ0Fw)。

## ![图标](/assets/ec_appicon_24.png) [!DNL Experience Cloud Central UI Components] 和管理 {#ecloud}

| 功能 | 描述 |
| ------- | ------- |
| 首页 | Experience Cloud主页页脚信息已移至用户配置文件卡，包括“首选项”中的法律声明和语言选择。 |
| AEP功能板 | [!DNL Helios Lite] 在Experience Platform小组件创建工作流中提供图表推荐。 给定数据选择（当前为单变量数据选择）， [!DNL Helios] 建议在选择数据时使用适当的可视化图表。 |
| AEP功能板 | [!DNL Instory] 为图表提供基于ML的书面叙述和字幕。 它对AEP功能板页面中的图表进行修饰，以包含相关要点，指出图表数据中的主要更改和事件。 |

{style=&quot;table-layout:auto&quot;}

**关于 [!DNL Experience Cloud Central UI Components] 和管理**&#x200B;的更多帮助资源

* [中央界面组件](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=zh-Hans)和用户管理的管理帮助
* [地点 - 位置服务](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=zh-Hans)的帮助和发行说明
* [人员 - 客户属性和受众库](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=zh-Hans)的相关帮助

## ![图标](/assets/adobe.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] 提供了关于 Adobe 产品与服务中断和维护活动的详细信息、状态更新以及电子邮件通知。请访问 [status.adobe.com](https://status.adobe.com/) 查看。

（在 [2020 年 5 月 21 日](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=zh-Hans)的发行说明中找到 [!DNL Adobe System Status] 的最新发布信息。）

## ![图标](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

包括 Experience Platform 和 [!UICONTROL Mobile SDK] 的发行更新信息和新文档。

**2021 年 9 月 29 日**

有关所有详细信息，请参阅 [Experience Platform 发行说明](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=zh-Hans)。

### Experience Platform 教程和课程 {#tutorials-platform}

发布的关于 Experience Platform 和服务的最新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 11 月 | [ 第一方数据上下文中的数据协作 ](https://experienceleague.adobe.com/docs/platform-learn/tutorials/industry/data-collaboration-in-the-first-party-data-context.html?lang=en#) | 视频 | 实现体验承诺，并减少数据访问。 无论您是广告商、出版商还是代理商，此网络研讨会都有助于在未来挖掘数据协作机会，而无需使用第三方Cookie。 |
| 2021 年 10 月 | [[!DNL Platform] 管理](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-A-1-2021.1.admin) | 课程 | 了解 Experience Platform 的管理活动，包括权限和沙盒管理。 |

{style=&quot;table-layout:auto&quot;}

### Adobe Mobile SDK

请参阅 Adobe Experience Platform Mobile SDK 的[发行说明和更改日志](https://aep-sdks.gitbook.io/docs/release-notes)。

## ![图标](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

发行日期：**2021 年 10 月 28 日**

* [Adobe Analytics 中的新增功能](#aa-features)
* [Customer Journey Analytics 中的新增功能](#cust-journey)
* [Adobe Analytics 中的修复](#aa-fixes)
* [Analytics 管理员的重要注意事项](#aa-notices)
* [Analytics 的课程及教程](#tutorials-analytics)
* [AppMeasurement](#appm)

### Adobe Analytics 中的新增功能 {#aa-features}

| 功能 | 描述 | [正式发布](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=en) - 目标日期 |
| ----------- | ---------- | ------- |
| Analysis Workspace中的分钟级日期范围 | 您可以在面板日历的高级设置下应用分钟级日期范围，或在生成自定义日期范围时应用。 如果您报告的日期范围跨越多天，则开始时间适用于第一天，结束时间适用于范围内的最后一天。 | 2021 年 10 月 18 日 |
| [!UICONTROL 媒体播放耗时] | Adobe 流媒体播放[!UICONTROL 耗时]提供有关查看者参与的有价值见解，并使媒体组织能够通过具备时段分割功能的高级耗时分析，利用以分钟计的用户参与获得更深入、更精细的见解。您可以观察在特定时间点查看媒体流的耗时。您可以按不同粒度（包括新的5分钟、15分钟和30分钟粒度）划分播放持续时间。 [了解详情](https://experienceleague.adobe.com/docs/media-analytics/using/media-reports/media-workspace-panels/media-playback-time-spent.html?lang=en) | 2021 年 10 月 18 日 |
| 快速[!UICONTROL 区段生成器] | 允许商业用户在简化的嵌入式项目工作流中快速应用基本区段。无需转至[!UICONTROL 区段生成器]。[了解详情](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/components/segments/quick-segments.html?lang=en) | 2021 年 10 月 21 日 |
| Analysis Workspace 左边栏搜索改进 | 左边栏搜索1)除继续考虑组件的新近度和相关性外，还会将精确匹配优先于广泛匹配。 2) 突出显示匹配的字符以使搜索结果更易于理解。3) 让查找与维度相关的分类变得更加轻松。4) 支持通配符 (`*`) 搜索以更轻松地找到所需的特定组件。注意：通配符搜索在维度项级别尚不可用。 | 2021 年 10 月 21 日 |
| 深色主题 | [深色主题作为显示选项提供。](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/user-preferences.html?lang=en#dark-theme) | 2021 年 10 月 21 日 |

{style=&quot;table-layout:auto&quot;}

### Customer Journey Analytics 中的新增功能 {#cust-journey}

| 功能 | 描述 | [正式发布](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html) - 目标日期 |
| ----------- | ---------- | ----- |
| Analysis Workspace中的分钟级日期范围 | 您可以在面板日历的高级设置下应用分钟级日期范围，或在生成自定义日期范围时应用。 如果您报告的日期范围跨越多天，则开始时间适用于第一天，结束时间适用于范围内的最后一天。 | 2021 年 10 月 18 日 |
| 快速[!UICONTROL 筛选器生成器] | 允许商业用户在简化的嵌入式项目工作流中快速应用基本区段。无需转至[!UICONTROL 筛选器生成器]。[了解详情](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-components/cja-filters/quick-filters.html) | 2021 年 10 月 21 日 |
| Analysis Workspace 左边栏搜索改进 | 左边栏搜索1)除继续考虑组件的新近度和相关性外，还会将精确匹配优先于广泛匹配。 2) 突出显示匹配的字符以使搜索结果更易于理解。3) 让查找与维度相关的分类变得更加轻松。4) 支持通配符 (`*`) 搜索以更轻松地找到所需的特定组件。注意：通配符搜索在维度项级别尚不可用。 | 2021 年 10 月 21 日 |
| 深色主题 | [深色主题作为显示选项提供。](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-workspace/user-preferences.html?lang=en#dark-theme) | 2021 年 10 月 21 日 |
| 维分配的回顾窗口 | 向“数据视图”配置中的“持久性”下的维度分配设置添加最多90天的回顾窗口。 [了解详情](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dataviews/component-settings/persistence.html) | 2021 年 10 月 28 日 |

{style=&quot;table-layout:auto&quot;}

### Adobe Analytics 中的修复 {#aa-fixes}

* 修复了无法删除警报管理器中警报的问题。 (AN-270656)
* 修复了Data warehouse请求间歇性失败的问题。 （AN-273713、AN-272790）
* 修复了分类未更新的问题。 (AN-272211)

### 修复了Customer Journey Analytics {#cja-fixes}

* 修复了CJA性能问题（加载项目时出现的错误消息）。 （AN-269451、AN-270649）
* 修复了CJA中的问题：会话开始与页面名称的流条目不匹配。 (AN-273501)
* 修复了CJA中的“流失”报表无法正常运行的问题。 (AN-269761)

#### Adobe Analytics 中的其他修复

AN-263327;AN-267807;AN-269757;AN-272789;AN-272888;AN-273155;AN-273320;AN-273369;AN-273405;AN-273469;AN-273581;AN-273642;AN-273688;AN-273988;AN-274007;AN-274030;AN-274156;AN-274188;AN-274226

#### CJA中的其他修复

AN-270649

### [!DNL Analytics] 管理员的重要注意事项 {#aa-notices}

| 注意事项 | 添加或更新日期 | 描述 |
| ----------- | ---------- | ---------- |
| 三种 Analytics API 服务的生命周期结束 | 2021 年 9 月 16 日 | **2021 年 10 月 20 日**，以下几项 Analytics 旧版 API 服务将达到其生命周期结束日期并将被关闭。当前任何使用这些服务构建的集成都将在当日停止工作。<ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>旧版 OAuth 身份验证（OAuth 和 JWT）</li></ul>Adobe 已提供[旧版 API EOL 常见问题解答](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)以帮助回答您的问题并提供关于如何继续的指导。使用这些服务的 API 集成可以迁移到 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 或 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。旧版 OAuth 帐户可迁移到 [Adobe I/O](https://developer.adobe.com/console) Analytics 集成帐户，该帐户可用于访问 1.4 Analytics API 和 2.0 Analytics API。 |
| 数据源中完全处理生命周期终止 | 2021 年 10 月 18 日 | 开 **2022年1月31日**,Adobe将终止完全处理生命周期，完全处理允许用户将离线点击数据摄取到Analytics中。 此功能可通过 [批量数据插入API](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md). [了解详情](https://experienceleague.adobe.com/docs/analytics/import/data-sources/data-types-and-categories/datasrc-fullproc-eol.html?lang=zh-CN?lang=zh-Hans) |

{style=&quot;table-layout:auto&quot;}

### AppMeasurement {#appm}

有关 AppMeasurement 版本（版本 2.22.2）的最新更新，请参阅[适用于 JavaScript 的 AppMeasurement 发行说明](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=zh-Hans)。

### Analytics 的课程及教程 {#tutorials-analytics}

[!DNL Analytics] 和 [!UICONTROL Customer Journey Analytics] 中的最新课程、教程和文章。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 11 月 | [Adobe Analytics中的区段容器](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/segment-containers.html?lang=en) | 视频（已更新） | 在此视频中，了解如何使用容器并听取每种类型容器的一些示例。 |
| 2021 年 11 月 | [Adobe Analytics中的顺序区段](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/sequential-segmentation.html?lang=en#) | 视频（已更新） | 了解如何根据网站或应用程序中的一系列行为在Analysis Workspace中构建区段。 |
| 2021 年 11 月 | [在顺序分段中的序列之前/之后](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/before-after-sequences-in-sequential-segmentation.html?lang=en) | 视频（已更新） | 了解如何在Adobe Analytics中进行分段，以便仅从特定用户路径之前或之后的数据获取。 |
| 2021 年 11 月 | [Customer Journey Analytics 的 Report Builder](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/report-builder-for-customer-journey-analytics.html) | 视频 | 借助 Report Builder 简单灵活的拖放 UI，您可以在 Excel 中从 Customer Journey Analytics 数据创建复杂的数据查询和自定义报表。 |
| 2021 年 10 月 | [利用可视化项讲述您的数据故事](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2021.1.visualizations) | 课程 | 了解有关可视化的基础知识，包括如何将可视化添加到项目、将数据导入到其中，以及每个可视化图表可以向您显示的内容。 了解如何配置设置以获取所需的确切数据。此外，获取一些提示和用例以帮助您在常规分析中实施可视化。 |

{style=&quot;table-layout:auto&quot;}

### Analytics 帮助资源

* [Adobe Analytics 产品文档及教程](https://experienceleague.adobe.com/docs/analytics.html?lang=zh-Hans)

## ![图标](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager 中的修复和改进。

* 解决了导致所有API调用返回 `Undocumented` 通过Swagger界面执行时出错。 (AAM-59190)
* 解决了在某些情况下导致向合作伙伴分配错误的用户角色的问题。 (AAM-59451)
* 解决了导致API需要区分大小写的身份验证标头的问题。 (AAM-58528)

## ![图标](/assets/aem.png) Experience Manager {#aem}

Adobe 建议访问 [Experience Manager 版本更新和路线图](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html)页面以及时了解版本信息。

### 发行概述视频

* [2021年10月版概述](https://video.tv.adobe.com/v/338253) 新增功能视频。
* [2021年9月版概述](https://video.tv.adobe.com/v/337381) 新增功能视频。

### 社区

* [Adobe Developers Live](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk) | 2021 年 10 月 4 日 - 5 日 7:00 PDT

   Adobe Developers Live 将具有不同的背景和单一目的的 Adobe 开发人员和体验构建者聚集在一起，以创造令人难以置信的端到端体验。这个为期两天的会议包括重要的开发人员信息更新、技术研讨会和社区关系网建立机会。

   跨Experience Cloud、Document Cloud和Creative Cloud的Adobe产品团队展示了最新的技术进步和开发人员工具，可为跨行业的设计、内容创建工作流、文档服务和客户体验管理提供强大动力。

   Adobe 计划举办 20 场 Experience Manager 研讨会。请向大家告知这个消息！

   * [完整研讨会列表](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-developers-live-october-2021-complete-session-list/m-p/423041#M120517)
   * [免费注册 – 登录 RSVP](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk)
   * [Adobe Developers Live 社区](https://experienceleaguecommunities.adobe.com:443/t5/adobe-experience-manager/registration-for-adobe-developers-live-is-now-open-4th-amp-5th/td-p/422127)

### Experience Manager 的新课程和教程 {#tutorials-aem}

过去一个月发布的新视频、教程及课程。

| 发布日期 | 名称 | 描述 | 类型 | 版本 |
| -----------| ---------- | ---------- |---------- | ---------- |
| 2021 年 11 月 | [Adobe Experience Manager Sites基础知识](https://experienceleague.adobe.com/docs/experience-manager-skill-builder/skill-builder/2021/authoring-fundamentals.html?lang=en) | 视频系列 | 通过这个由五部分组成的网络研讨会系列，了解如何在Adobe Experience Manager创建丰富而引人入胜的客户体验。 从内容创作的构建基块开始，同时了解基本概念和操作。 了解站点管理功能以及在AEM中处理数字资产的基础知识。 稍后，会发现一些功能，这些功能可通过重复使用内容并跨渠道交付来帮助您节省时间并提高效率。 | AEM Sites |
| 2021 年 11 月 | [计划迁移到AEMas a Cloud Service](https://experienceleague.adobe.com/?recommended=ExperienceManager-A-1-2021.1.migration) | 课程 | 了解迁移到AEM as a Cloud Service的注意事项以及可简化流程的可用工具。 | AEM CS |
| 2021 年 11 月 | [迁移到 AEM as a Cloud Service ](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2021.1.migration) | 课程 | 了解如何成功从AEM 6迁移到Experience Manageras a Cloud Service。 | AEM CS |
| 2021 年 11 月 | [下载交互式DoR](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/document-services/generate-interactive-dor.html?lang=en#create-custom-servlet) | 视频 | 了解如何下载包含自适应表单数据的交互式DoR。 | AEM 表单 |
| 2021 年 11 月 | [Adobe Experience Manager as a Cloud Service专家系列](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/aem-experts-series.html?lang=en) | 视频系列 | 了解Adobe Experience Manager(AEM)的as a Cloud Service信息，包括Adobe负责构建该工具的专家工程师以及负责提供该工具的专业服务团队。 与Adobe的专家一起探索AEM的as a Cloud Service概念、与AEM 6的比较方式，以及如何从AEM 6迁移到AEM的as a Cloud Service。 | AEM CS |
| 2021 年 11 月 | [服务用户](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/advanced/service-users.html?lang=en) | 视频 | 了解如何在AEM代码中创建和使用服务用户，以提供对AEM存储库的受控、编程访问。 | AEM CS |

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
* [[!DNL Cloud Manager] 《用户指南》](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=zh-Hans)
* [[!DNL Dynamic Media Classic] 帮助主页](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=zh-Hans)
* [Experience Manager 文档：最近的更新](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=zh-Hans#aem-as-a-cloud-service)

## ![图标](/assets/magento.png) [!DNL Commerce] (Magento) {#magento}

有关 Adobe Commerce 发行说明，请参阅以下链接：

* [Adobe Commerce 和 Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [适用于 Adobe Commerce 的云套件](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### 新的Adobe Commerce教程 {#commerce-tutorials}

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 11 月 | [Adobe Commerce视频和Tutorials](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/overview.html?lang=en) | 教程主页 | 这些教程资源包括提供主题高级视图的视频系列，以及针对特定任务和流程的各个视频。 该集合旨在为后端开发人员、前端开发人员、系统管理员、商家以及您组织内的其他角色提供有用的内容。 |

## ![图标](/assets/target.png) [!DNL Target] {#target}

上次更新时间： **2021年10月20日**

请参阅[[!DNL Target] 发行说明](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=zh-Hans)了解最新发行信息。

## ![图标](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign 提供了一种直观、自动的方式，以通过在线和离线营销渠道来交付一对一的消息。您现在可以利用根据客户习惯和偏好确定的体验，来预测客户的需求。

### 最新营销活动产品版本

详细了解最新发布的功能、改进和修复：

* [Campaign v8 发行说明](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/release-notes.html?lang=zh-Hans)
* [Campaign Classic v7 发行说明](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=zh-Hans)
* [Campaign Standard 发行说明](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=zh-Hans)

### [!UICONTROL Campaign] 的新课程及教程 {#tutorials-campaign}

Adobe Campaign 的最新教程和课程

| 发布日期 | 名称 | 描述 | 类型 | 版本 |
| -----------| ---------- | ---------- |---------- | ---------- |
| 2021 年 11 月 | [将 Campaign 连接到作为目标的 Experience Platform](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-platform/import-experience-platform-data-into-campaign/connect-campaign-to-experience-platform-as-destination.html?lang=en) | 视频 | 了解如何使用 Amazon S3 连接类型将 Adobe Experience Platform 区段激活到目标。 | AEP和Campaign V8 |
| 2021 年 11 月 | [与 Experience Platform 集成 - 概述](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-platform/overview.html?lang=en) | 视频 | 了解如何在 Campaign 和 Experience Cloud 之间共享数据。 | AEP和Campaign V8 |
| 2021 年 11 月 | [从 Experience Platform 导入收件人数据并发送电子邮件](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-platform/import-experience-platform-data-into-campaign/import-recipient-data-from-platform.html?lang=en) | 视频 | 了解如何在 Adobe Campaign 中配置外部帐户，以将收件人数据从 Adobe Experience Platform 导入 Campaign。了解如何创建工作流以上传和定位从 Experience Platform 接收的收件人。 | AEP和Campaign V8 |
| 2021 年 11 月 | [在工作流中使用SOAP API](https://experienceleague.adobe.com/docs/campaign-learn/use-soap-apis/introduction.html?lang=en) | 视频教程 | 了解如何使用 Adobe Campaign Soap API 并根据通过 API 接收的数据创建高级交付工作流。 | Campaign V8 |

{style=&quot;table-layout:auto&quot;}

### 营销活动帮助资源

* Adobe Campaign v8: [文档](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=zh-Hans) - [发行说明](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/whats-new.html?lang=zh-Hans) - [实施指南](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=zh-Hans)
* Adobe Campaign Standard：[Campaign Standard 文档](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=zh-Hans) - [发行说明](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [操作方法视频](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=zh-Hans) - [发行计划](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=zh-Hans) - [最新文档更新](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=zh-Hans)
* Adobe Campaign Classic：[Campaign Classic v7 文档](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=zh-Hans) - [发行说明](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [操作方法视频](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=zh-Hans) - [最新文档更新](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=zh-Hans)
* Adobe Campaign 控制面板：[文档](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hans) - [发行说明](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=zh-Hans) - 有关 [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=zh-Hans)/[Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=zh-Hans) 的操作方法视频

## ![图标](/assets/experience_platform_appicon_24.png) Journey Optimizer {#journey-opt}

借助 Adobe Journey Optimizer，您可以通过单个应用程序为数百万客户管理预定的全渠道营销活动和一对一互动时刻，整个历程都通过智能决策和见解得到了优化。

### 最新 Journey Optimizer 产品版本

有关最新的功能、改进和修复的详细信息，请参见 [Journey Optimizer 发行说明](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html)。

### Journey Optimizer 教程和课程 {#tutorials-ajo}

最新 Journey Optimizer 教程：

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 10 月 | [在 [!DNL Journey Optimizer] 中为数据工程师配置和管理数据](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.2) | 课程 | 了解如何在 Journey Optimizer 中配置和管理历程管理所需的数据。 |
| 2021 年 10 月 | [面向历程管理员的 [!DNL Journey Optimizer] 入门](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.1) | 课程 | 了解创建首个历程所必须掌握的一切信息。 |
| 2021 年 10 月 | [为历程管理员配置 [!DNL Journey Optimizer] ](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-A-1-2021.1) | 课程 | 了解 [!DNL Journey Optimizer] 架构和集成点。了解如何配置 [!DNL Journey Optimizer]。 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Journey Optimizer] 的更多资源

* [Journey Optimizer文档](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=zh-Hans) - [发行说明](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [操作方法视频](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=zh-Hans)
* [决策管理文档](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started/starting-offer-decisioning.html) - [发行说明](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [操作方法视频](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/introduction-to-offer-decisioning.html) - [最新文档更新](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html)

## ![图标](/assets/experience_platform_appicon_24.png) [!DNL Journey Orchestration] {#journey-orch}

凭借 Experience Platform，可以实时智能化预测每位客户的需求，从而实现跨体验渠道大规模编排客户历程。

### 最新 [!DNL Journey Orchestration] 产品版本

在 [[!DNL Journey Orchestration] 发行说明](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=zh-Hans).

#### [!DNL Journey Orchestration] 的更多资源

* [Journey Orchestration文档](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=zh-Hans) - [发行说明](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [操作方法视频](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=zh-Hans) - [最新文档更新](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=zh-Hans)

## ![图标](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] 是一个全面的应用程序，适用于寻求通过积极参与复杂购买过程的每个阶段而改善客户体验的销售线索管理和 B2B 营销人员。

### 核心 Marketo Engage 更新

有关最新的发布计划信息和发行说明，请参阅[!DNL Marketo Engage] [发布计划](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=zh-Hans)。

## ![图标](/assets/workfront.png) [!DNL Workfront] {#workfront}

Adobe [!DNL Workfront] 是一个统一的工作管理应用程序，可用于分享创意、创建内容、管理复杂的流程以及将工作做到尽善尽美。

请参阅[[!DNL Workfront] 版本](https://one.workfront.com/s/product-releases)页面，查看所有产品的最新信息综述。

## ![图标](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

[!DNL Adobe Advertising Cloud] 的发行说明。

* [跨 [!DNL Advertising Cloud]](#adcloud-all)
* [ [!DNL Advertising Cloud DSP] 中的新增功能](#adcloud-dsp)
* [ [!DNL Advertising Cloud Search] 中的新增功能](#adcloud-search)

### 跨 [!DNL Advertising Cloud] {#adcloud-all}

上次更新日期：**2021 年 10 月 27 日**

| 功能 | 描述 |
| ------- | ----------- |
| 适用于Advertising Cloud的Analytics | 如果贵组织希望从使用旧版Adobe Analytics `visitorAPI.js` 库到Adobe Experience Platform库(`alloy.js`)，则需要进行一些更改才能启用ID拼合。 请参阅“[使用 [!DNL Last Event Service] 包含Adobe Experience Platform的JavaScript库 [!DNL Web SDK]](https://experienceleague.adobe.com/docs/advertising-cloud/integrations/analytics/planning/web-sdk.html).&quot; |

{style=&quot;table-layout:auto&quot;}

### [!DNL Advertising Cloud DSP] 中的新增功能 {#adcloud-dsp}

上次更新日期：**2021 年 10 月 27 日**

| 功能 | 描述 |
| ------- | ----------- |
| 自定义报表 | 您现在可以创建和管理 [!DNL Amazon S3] 和不同类型的FTP交付位置(称为 *[!DNL report destinations]*，用于自定义报表。 配置报表目标后，您可以设置每个新的自定义报表，以将其提交到单个目标类型的一个或多个位置，或电子邮件收件人。 更新了 [!DNL Amazon S3] 和FTP凭据不会中断报表交付。<br><br>您的现有报表仍会发送到指定的电子邮件收件人。 要配置到其他报表目标的投放，请使用新目标创建新报表。 |
| [!UICONTROL 包], [!UICONTROL 版面]和 [!UICONTROL 广告] 视图 | 当您查看某一天的数据时，趋势图现在包含每小时数据。 将光标悬停在任意点上可查看该小时的数据。 |
| [!UICONTROL 版面] | 版面 [!UICONTROL 检查员] 现在包含 [!UICONTROL 库存] 选项卡，其中显示了该版面的所有交易及其相关量度。 无需生成自定义报告，即可使用信息进行快速调整或解决问题。 |
| [!UICONTROL 广告] | （有权在其广告中包含Clearcastclock编号的用户）如果您使用附加到其他广告的时钟编号，DSP不再显示错误。 **注意：**  最佳做法是为每个视频广告使用唯一的时钟号。 否则，发布者不会批准所有广告。 |
| [!UICONTROL 交易ID] | 的 [!UICONTROL 交易ID] 设置和用户界面中的其他位置反映了 [!DNL Magnite] SSP:<br><ul><li>SSP &quot;[!DNL Tremor]&quot;([!DNL Telaria])现在为“[!DNL Magnite CTV].&quot;</li><li>在接下来的几周里， [!DNL Rubicon]“ ”将更改为“ ”[!DNL Magnite DV+]，其中 [!DNL DV+] 表示显示、视频和其他格式，如音频。</li></ul> |
| [!DNL Freewheel] 程序保证的交易 | 您现在可以找到 [!DNL Freewheel] 通过 [!UICONTROL 广告] 中。 以前，您只能从 [!UICONTROL 交易] 中。 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Advertising Cloud Search] 中的新增功能 {#adcloud-search}

上次更新日期：**2021 年 10 月 7 日**

| 功能 | 描述 |
| ------- | ----------- |
| [!UICONTROL 报表], [!UICONTROL 通知中心] | （10月9日版）现在，所有报表的电子邮件通知由Advertising Cloud Search处理，自定义或计划报表完成或失败时，Adobe会发送这些通知 [!UICONTROL 通知中心]. 默认情况下，报表会启用电子邮件通知和Web通知，但您可以选择更改通知设置。 通过此更改：<ul><li>电子邮件收件人仅限于已注册且已通过Advertising Cloud Search用户身份验证并有权访问广告商帐户的用户。 此功能可确保不会向未经授权的用户发送任何机密数据。</li><li>电子邮件的格式和内容使用 [!UICONTROL 通知中心] 模板，其中包含报表的更多详细信息以及所有报表格式的直接下载链接。</li><li>报表通知是一种新的通知类型，具有自己的通知首选项，位于 [!UICONTROL 通知中心].</li></ul>如果您使用任何自动功能从电子邮件通知中提取报表，则可能需要更新筛选逻辑以确保流程的连续性。 |
| 广告见解 | Beta 模式中提供了其他见解。 |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

为 Adobe Document Cloud 发布的新视频、教程或课程。

### Document Cloud 课程和教程 {#tutorials-doc-cloud}

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 11 月 | [工作区基础知识](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/get-to-know-the-acrobat-dc-interface.html) | 视频（已更新） | 了解Acrobat DC界面如何通过一致的工作区体验，轻松访问跨桌面、Web和移动设备的文件和工具。 |
| 2021 年 11 月 | [随处使用Acrobat Web](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/acrobatweb.html) | 视频 | 了解如何在浏览器中使用Acrobat Web工具从任何位置处理业务文档请求。 |
| 2021 年 11 月 | [在Office中为Web创建PDF ](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/createofficeweb.html) | 视频 | 了解如何创建PDF文件，而无需离开Microsoft® Office的Web应用程序。 此加载项需要订阅Acrobat DC团队版或Acrobat DC企业版订阅。 |
| 2021 年 11 月 | [实时协作](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/collaborate.html) | 视频 | 通过收集评论、协作响应和实时跟踪文档进度，随时随地推进项目。 |
| 2021 年 11 月 | [ 在旅途中工作](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/productivity.html) | 视频 | 使用Acrobat Reader移动应用程序，在平板电脑或手机上执行更多操作。 |

{style=&quot;table-layout:auto&quot;}

有关 Document Cloud 的帮助，请参阅：

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=zh-Hans)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=zh-Hans)
* [Document Cloud 学习与支持](https://helpx.adobe.com/cn/support/document-cloud.html)

## ![图标](/assets/creative-cloud-24.png) Creative Cloud 企业版 {#creative-cloud}

有关最新教程，请参阅 [Creative Cloud 企业版教程](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=zh-Hans)。
