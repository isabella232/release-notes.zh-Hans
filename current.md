---
title: 最新发行说明
description: 了解 Experience Cloud 产品和服务的最新发行说明、新增功能和新文档。查找关于 Experience Cloud、Creative Cloud 企业版和 Document Cloud 的新帮助和教程。
doc-type: release notes
last-update: June 2021
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: 6778e1f9e6d8059d0453eb0cc5e572d16a7a7e7c
workflow-type: tm+mt
source-wordcount: '4958'
ht-degree: 51%

---

# Adobe Experience Cloud 发行说明 - 2021 年 6 月

![横幅](assets/experience-cloud-banner-3.png)

Experience Cloud 应用程序和服务每月更新一次。在此页面上可集中查找 [!DNL Experience Cloud] 和 [!DNL Experience Platform] 的最新版本更新、文档和教程。还可查找 [!DNL Creative Cloud for Enterprise] 和 [!DNL Document Cloud] 的新文档。

>[!NOTE]
>
>订阅每月一期的 [Adobe Priority Product Update](https://www.adobe.com/cn/subscription/priority-product-update.html) 即可收到关于此页面更新的电子邮件通知。整月都在维护此页面，因此请定期回来查看 Adobe 企业产品和 Experience League 文档的更新。

最新更新日期：**2021 年 6 月 14 日**

* [Experience Cloud 中央界面组件](#ecloud)
* [Adobe 系统状态](#status)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Offer Decisioning](#offer-decisioning)
* [[!DNL Analytics]](#analytics) 和 [Customer Journey Analytics](#cust-journey)
* [[!DNL Audience Manager]](#aam)
* [[!DNL Experience Manager]](#aem)
* [[!DNL Campaign]](#ac)
* [[!DNL Advertising]](#adcloud)
* [[!DNL Target]](#target)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo)
* [[!DNL Workfront]](#workfront)
* [Document Cloud](#doc-cloud)
* [Creative Cloud 企业版](#creative-cloud)

需要帮助？请访问 [Adobe Experience League](https://experienceleague.adobe.com/?lang=zh-Hans/#home)，查找产品和技术文档、Adobe 策划课程、视频教程、快速解答、社区洞察以及由讲师指导的培训。

## ![](/assets/ec_appicon_24.png) 图标Experience Cloud中央UI组件 {#ecloud}

Experience Cloud中心界面组件包括从统一产品标题访问的更新，例如自助、搜索和用户帐户首选项。 此处提供了人员、位置（位置）和产品管理的更新。

| 功能 | 日期 | 描述 |
| ------- | ------- | ------- |
| 对AdobeFederated ID的单点登录支持 | 2021 年 6 月 17 日 | 如果您使用Federated ID，则无需输入电子邮件地址或密码即可登录Experience Cloud。 要使用此功能，请将&#x200B;**#/sso:@domain**&#x200B;添加到Experience CloudURL。 <br><br>例如，假定您拥有域 **adobecustomer.** com，并且想要登录Adobe Analytics。URL应为：**https://experience.adobe.com/#/sso:@adobecustomer.com/analytics**。 |
| Experience League搜索 | 2021 年 6 月 1 日 | Experience League文档搜索已得到改进。 导航到[Experience League](https://experienceleague.adobe.com/docs/?lang=en)并使用&#x200B;**[!UICONTROL 搜索]**&#x200B;字段找到教程、文档、课程等内容。 |

{style=&quot;table-layout:auto&quot;}

**更多帮助资源**

* [中央接口组件](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=zh-cn)和用户管理的管理帮助
* [Places - Location Service](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=en)的帮助和发行说明
* 有关[人员 — 客户属性和受众库](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en)的帮助。

## ![图标](/assets/adobe.png) Adobe 系统状态 {#status}

[!UICONTROL Adobe 系统状态]提供关于 Adobe 云产品与服务中断和维护事件的详细信息、状态更新以及电子邮件通知。请访问 [status.adobe.com](https://status.adobe.com/) 查看。

可在 [Adobe 系统状态 - 2020 年 5 月 21 日](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=zh-Hans)上找到 Adobe 系统状态的最新更新，了解最新的发行信息。

## ![图标](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

包括发行更新信息以及有关Experience Platform和Experience Platform Launch的新文档。

* **2021年5月26日：** [Experience Platform发行说明](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=zh-Hans)
* **2021年5月17日：** [Experience Platform数据收集发行说明](https://experienceleague.adobe.com/docs/launch/using/release-notes/current.html?lang=zh-Hans) (以前称为Experience Platform Launch)

### Experience Platform 教程和课程 {#tutorials-platform}

发布的关于 Experience Platform 和服务的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 6 月 | [使用查询服务准备数据](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/prepare-data.html) | 视频 | 了解如何清理、准备和合并来自多个数据集的数据，以使用创建表AS(CTAS)和Spark SQL函数创建数据集，以用于报告和功能板。 |
| 2021 年 6 月 | [在沙箱之间复制架构](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/copy-schemas-between-sandboxes.html) | 视频 | 了解如何使用[!UICONTROL 导出/导入架构API]将架构从一个沙箱复制到Adobe Experience Platform中的另一个沙箱。 在开发沙箱中构建并测试您的模式，然后将其复制到生产环境。 |
| 2021 年 6 月 | [更新架构](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/update-schemas.html) | 视频 | 了解在Adobe Experience Platform中更新现有模式时要注意的基本事项。 |
| 2021 年 6 月 | [架构构建块](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/schema-building-blocks.html) | 视频 | 了解体验数据模型(XDM)架构的关键构建基块元素，包括字段、数据类型、架构字段组、类和行为。 |
| 2021 年 6 月 | [创建架构类](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-classes.html) | 视频 | 了解如何在Adobe Experience Platform中创建类以在Experience Data Model(XDM)模式中使用。 |
| 2021 年 6 月 | [配置架构之间的关系](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/configure-relationships-between-schemas.html) | 视频 | 了解如何在Adobe Experience Platform中配置两个模式之间的关系。 关系允许您将一个数据集用作另一个数据集的查询表。 |
| 2021 年 6 月 | [创建架构数据类型](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-data-types.html) | 视频 | 了解如何在Adobe Experience Platform中创建您自己的数据类型，以便在Experience Data Model(XDM)模式中使用。 |
| 2021 年 6 月 | [将数据模型转换为体验数据模型](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/convert-your-data-model-to-xdm.html) | 视频 | 了解数据架构师如何利用他们现有的事务型数据模型并将其转换为体验数据模型。 此视频展示了使用实体 — 关系图的建模方法的不同。 |
| 2021 年 6 月 | [规划数据模型](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/plan-your-data-model.html) | 视频 | 在开始在Adobe Experience Platform中构建模式之前，了解要执行的操作。 记录您的业务用例、了解您的平台许可证、了解产品防护，并在最终确定数据模型之前确定要摄取的数据。 |
| 2021 年 6 月 | [将表格连接到查询服务](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/psql-client-tableau.html) | 视频 | 了解如何从支持`PostgreSQL`协议的各种桌面客户端应用程序连接到[!UICONTROL 查询服务]，以及如何使用`PostgreSQL`工具和驱动程序连接和写入查询。 |
| 2021 年 6 月 | [Adobe查询服务中定义的函数](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/adobe-defined-functions.html) | 视频 | 了解如何在Adobe Experience Platform [!UICONTROL 查询服务]中使用Adobe定义的函数，对体验事件数据执行常见的业务相关任务。 |
| 2021 年 6 月 | [使用查询服务进行数据探索](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/explore-data.html) | 视频 | 了解如何使用SQL函数验证摄取的数据、预览数据，以及探索数据的统计和分析属性。 |
| 2021 年 6 月 | [查询服务概述](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/understanding-query-service.html) | 视频 | 了解Adobe Experience Platform中的查询服务，以及它如何帮助了解客户行为并生成有影响的洞察。 |
| 2021 年 6 月 | [查询服务UI概述](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/query-service-ui.html) | 视频 | 了解如何在Adobe Experience Platform查询服务中编写和执行查询、查看以前执行的查询，以及访问您的IMS组织内其他用户保存的查询。 |
| 2021 年 6 月 | [查询 API](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/query-service-api.html) | 视频 | 了解如何使用Adobe Experience Platform [!UICONTROL 查询服务API]编写和执行查询、创建计划查询以及创建查询模板。 |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

凭借Experience Platform，可实时智能化预测每位客户的需求，从而实现跨体验渠道大规模编排客户旅程。

* 更新日期： 2021年6月 — [Journey Orchestration发行说明](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=zh-Hans)

**Journey Orchestration 的更多资源**

[文档](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=zh-Hans) - [发行说明](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=en) - [操作方法视频](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=zh-Hans)

## ![图标](/assets/experience_platform_appicon_24.png) Offer Decisioning {#offer-decisioning}

[!UICONTROL Offer Decisioning] 是与 Adobe Experience Platform 集成的一项应用程序服务。使用 [!UICONTROL Offer Decisioning] 可在适当的时候将优质的产品和体验提供给您在所有接触点上的客户。

* 更新日期： 2021年4月 — [Offer decisioning发行说明](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html?lang=zh-Hans#new)

**Offer Decisioning 的更多资源**

[文档](https://experienceleague.adobe.com/docs/offer-decisioning/using/offer-decisioning-home.html?lang=zh-Hans) - [发行说明](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html?lang=en#new) - [操作方法视频](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html?lang=zh-Hans)

## ![图标](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

发布日期：**2021 年 6 月 17 日**

* [Adobe Analytics 中的新增功能](#aa-features)
* [Customer Journey Analytics 的新增功能](#cust-journey)
* [Adobe Analytics 中的修复](#aa-fixes)
* [Analytics 管理员的重要注意事项](#aa-notices)
* [Analytics 的课程及教程](#tutorials-analytics)
* [AppMeasurement](#appm)

### Adobe Analytics 中的新增功能 {#aa-features}

| 功能 | [正式发布](https://experienceleague.adobe.com/docs/analytics/landing/an-releases.html?lang=zh-Hans) - 目标日期 | 描述 |
| ----------- | ---------- | ------- |
| 不适用 | 不适用 |

{style=&quot;table-layout:auto&quot;}

### Customer Journey Analytics 的新增功能 {#cust-journey}

| 功能 | [正式发布](https://experienceleague.adobe.com/docs/analytics/landing/an-releases.html?lang=en) - 目标日期 | 描述 |
| ----------- | ---------- | ----- |
| 不适用 | 不适用 |

{style=&quot;table-layout:auto&quot;}

### Adobe Analytics 中的修复 {#aa-fixes}

* 修复了收入实时报表中货币显示不正确的问题。 (AN-254649)
* 更新了有关[报表中eVar区分大小写的文档](https://experienceleague.adobe.com/docs/analytics/components/dimensions/evar.html)。 (AN-246438)
* 更新了文档，以便更好地说明[数据馈送实施](https://experienceleague.adobe.com/docs/analytics/export/analytics-data-feed/create-feed.html)和[此处](https://experienceleague.adobe.com/docs/analytics/export/analytics-data-feed/df-faq.html#BucketOwnerFullControl)。 (AN-219485)
* 修复了某些数据未在Data warehouse报表中发送的问题(AN-259951;AN-259712;AN-260107;AN-259953)

#### Adobe Analytics或CJA中的其他修复

AN-246344;AN-250035;AN-250354;AN-252482;AN-254661;AN-254965;AN-255424;AN-256515;AN-257232;AN-257572;AN-257893;AN-258393;AN-259203;AN-259513;AN-259614;AN-259665;AN-259931;AN-260074;AN-260085;AN-260147;AN-260190;AN-260198;AN-260290;AN-260306(CJA);AN-260508;AN-260625;AN-260793;AN-260861;AN-260938;AN-260945;AN-261149;AN-261317

### [!DNL Analytics] 管理员的重要注意事项 {#aa-notices}

| 注意事项 | 添加或更新日期 | 描述 |
| ----------- | ---------- | ---------- |
| 浏览器用户代理反映的 macOS 操作系统版本有误 | 2021 年 5 月 19 日 | 所有主要浏览器当前都将 macOS X 11 和更高版本的用户错误地报告为使用的是 macOS 10，如浏览器的用户代理字符串中记录的那样。此问题影响 Adobe Analytics 报表，因为它使用用户代理确定操作系统等设备信息。这种不准确性显然是为了防止某些网站发生兼容性问题。请参阅 [Bugzilla 服务单](https://bugs.webkit.org/show_bug.cgi?id=213622&amp;utm_source=convertkit&amp;utm_medium=email&amp;utm_campaign=User+Agent+strings%2C+new+BigQuery+features%2C+custom+Google+Tag+Manager+loader...+%E2%80%93+Simmer+Newsletter+%2311%20-%205873454)以供参考。目前尚不清楚此问题何时或是否会得到修复。<br>某些浏览器最初正确记录了 macOS 11，因此可能有一些流量与此值相符。但是，由于报告得不准确，因此筛选 macOS 11 操作系统并无用处。<br>这个问题有重大意义，因为从 macOS 11 上的 Safari 起，Apple 更新了要适用于 CNAME 实现的 ITP Cookie 到期限制（请参阅 [WebKit 博客帖子](https://webkit.org/blog/11338/cname-cloaking-and-bounce-tracking-defense/)）。<br>在此次更新之前，这些限制仅适用于通过 JavaScript 设置的客户端 Cookie。这种不准确性使得难以评估有多少流量正在使用 macOS 11，并因此受 ITP 变更的影响。可在[此处](https://experienceleague.adobe.com/docs/analytics/technotes/cookies/cookies.html?lang=zh-Hans#cookies)详细了解 Cookie 和 Adobe Analytics。 |
| 三种 Analytics API 服务的生命周期终止 | 2021 年 5 月 19 日 | 2021 年 8 月 18 日，以下几项 Analytics 旧版 API 服务达到其生命周期结束日期并被关闭。任何使用这些服务构建的当前集成都在当天停止工作。<ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>旧版 OAuth 身份验证（OAuth 和 JWT）</li></ul>Adobe 已提供[旧版 API EOL 常见问题解答](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)以帮助回答您的问题并提供关于如何继续的指导。使用这些服务的 API 集成可以迁移到 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 或 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。旧版 OAuth 帐户可迁移到 [Adobe I/O](https://console.adobe.io/home?mv=email#) Analytics 集成帐户，该帐户可用于访问 1.4 Analytics API 和 2.0 Analytics API。 |
| 2021 年 ISO 区域更新 | 2021 年 5 月 13 日 | Adobe 将在 2021 年 5 月 21 日执行 2021 年 ISO 区域更新。预计在这个版本之后将看到小规模更新。 |
| 完全处理数据源生命周期终止 | 2021 年 4 月 12 日 | Adobe 计划在 2021 年 7 月 31 日弃用完全处理数据源。从 2021 年 3 月 25 日起，无法再创建此类型的新导入。请使用[批量数据插入 API](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md) 来导入此类型的数据。 |
| [!UICONTROL Report Builder] 的登录更新 | 2021 年 4 月 9 日 | 2021 年 1 月 14 日，[!UICONTROL Report Builder] 登录更新移除了对传统技术的依赖，与 Experience Cloud 的登录过程保持一致。Experience Cloud 使用 Enterprise ID（电子邮件和密码）。要确保对 [!UICONTROL Report Builder] 的访问不会出现中断，请在 2021 年 7 月 22 日之前将 [!UICONTROL Report Builder] 插件更新到 5.6.47 版本或更新的版本。Report Builder 的 5.6.47 版本及更新的版本仅支持 Experience Cloud 登录，不再支持单点登录。 |
| Data Feed and Data Warehouse IP 地址更改 | 2021 年 4 月 6 日 | 从 6 月 17 日开始，Data Feeds and Data Warehouse 传递系统将在 Adobe 的数据中心重新进行布置，因此可能会导致您看到的外部 IP 地址发生更改。Adobe 建议您确认，作为您的报告和馈送来源的数据中心的所有 IP CIDR 区块均在您控制的目标系统的防火墙内。[以下是可放入防火墙允许列表的 IP 地址范围的完整列表](https://experienceleague.adobe.com/docs/analytics/technotes/ip-addresses.html?lang=zh-Hans#data-collection-and-ftp-ip-address-blocks)。 |
| 即将推出的 Analytics 菜单更改的通知 | 2021 年 3 月 24 日 | 在 2021 年 4 月 22 日，Adobe 更新了&#x200B;**[!UICONTROL 组件]**、**[!UICONTROL 工具]**&#x200B;和&#x200B;**[!UICONTROL 管理员]**&#x200B;下拉菜单，以实现一定程度的性能提升。仍可通过&#x200B;**[!UICONTROL 所有组件]**、**[!UICONTROL 所有工具]**&#x200B;和&#x200B;**[!UICONTROL 所有管理员]**&#x200B;链接进入所有这些页面 - 但将从下拉菜单中删除这些页面。以下是将从下拉菜单中删除并放在其相应链接页面上的菜单项：<br><br> [!UICONTROL 组件]<ul><li>[!UICONTROL 书签]</li><li>[!UICONTROL 仪表板]</li><li>[!UICONTROL 目标]</li><li>[!UICONTROL 日历活动]</li><li>[!UICONTROL 计划报告]</li><li>[!UICONTROL 报表设置]</li></ul>[!UICONTROL 工具]<ul><li>[!UICONTROL Recommendations Classic]</li><li>[!UICONTROL Search &amp; Promote]</li></ul>[!UICONTROL 管理员]<ul><li>[!UICONTROL User Management]</li><li>[!UICONTROL 分类导入器]</li><li>[!UICONTROL 分类规则生成器]</li><li>[!UICONTROL 数据源]</li><li>[!UICONTROL 数据连接器]</li><li>[!UICONTROL 公司设置]</li><li>[!UICONTROL 日志]</li><li>[!UICONTROL 动态标记管理]</li><li>[!UICONTROL 代码管理器]</li><li>[!UICONTROL 通过 IP 排除]</li><li>[!UICONTROL 流量管理]</li></ul> |
| Same-as-SiteCatalyst VISTA 处理开启 | 2021 年 3 月 17 日 | 在 2021 年 6 月 17 日，所有报表包都将更新为将 [!UICONTROL Same-as-SiteCatalyst VISTA Processing] 设置为 ON。此更改影响 Data Warehouse 报表，其中处理数据以匹配处理规则。如有疑问或需要说明，请联系客户关怀团队。 |
| Reports &amp; Analytics 登陆页面选项 | 2021 年 2 月 19 日 | 2021 年 3 月 25 日，将新的 Reports &amp; Analytics 功能板或其他内容设置为 Adobe Analytics 登陆页面的选项已被移除。如果以前曾将 Reports &amp; Analytics 页面设置为自定义登陆页面，它将保持原样，直到在[!UICONTROL “用户首选项”]中修改登陆页面。 |
| Adobe Data Connectors 生命周期终止 | 2020 年 7 月 13 日 | Adobe [!UICONTROL Data Connectors] 由传统技术提供支持，而这些技术不再可行或不再受支持。可在 [Adobe Exchange Partner Program](https://partners.adobe.com/exchangeprogram/experiencecloud) 中找到新标准。可使用该标准继续提供和支持任何集成。正式的生命周期结束日期为 2021 年 8 月 1 日。[了解详情...](https://experienceleague.adobe.com/docs/analytics/import/dataconnectors/data-connectors-eol.html?lang=zh-Hans) |

{style=&quot;table-layout:auto&quot;}

### AppMeasurement {#appm}

有关 AppMeasurement 版本的最新更新，请参阅[适用于 JavaScript 的 AppMeasurement 发行说明](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=zh-Hans)。

### Analytics 的新课程和教程 {#tutorials-analytics}

[!DNL Analytics] 和 [!UICONTROL Customer Journey Analytics] 中的新课程、教程和文章。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 6 月 | [Customer Journey Analytics 管理员入门](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-A-1-2020.1) | 课程 | 了解如何设置、配置和管理Customer Journey Analytics。 了解一些基本概念，为您奠定基础，然后进入更多配置步骤。 然后，对于将计算量度和区段从Adobe Analytics迁移到Customer Journey Analytics，我们将为本课程添加一些建议。 |
| 2021 年 6 月 | [配置内部站点搜索报告](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/configure-internal-site-search-reports.html?lang=en) | 视频 | 在Analysis Workspace中创建并配置自由格式表，以分析您网站上的内部搜索功能。 |
| 2021 年 6 月 | [将 Web SDK 变量映射到 Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/map-web-sdk-variables-into-adobe-analytics.html?lang=en) | 视频 | 了解如何使用处理规则将分析变量从Web SDK映射到Adobe Analytics。 |
| 2021 年 6 月 | [利用 Web SDK 实施内部搜索变量](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/implement-internal-search-variables-using-web-sdk.html?lang=en) | 视频 | 了解如何使用Web SDK为内部搜索词跟踪用例实施Adobe Analytics变量。 查看从页面到Experience Edge的数据流，然后再到Adobe Analytics。 |
| 2021 年 6 月 | [利用 AppMeasurement 实施内部搜索变量](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/implement-internal-search-variables-using-appmeasurement.html?lang=en) | 视频 | 在此视频中，了解使用Experience Platform数据收集/启动为Adobe Analytics实施内部网站搜索变量的步骤，包括搜索词、结果数量等。 |
| 2021 年 6 月 | [定义您的内部网站搜索业务要求](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/defining-your-internal-site-search-business-requirements.html?lang=en) | 视频 | 在决定跟踪网站上的内部搜索时，必须首先确定要跟踪的搜索方面，以及在分析结果时可以采取哪些操作，这一点很重要。 此视频将逐步介绍业务要求的文档。 |

{style=&quot;table-layout:auto&quot;}

### Analytics 帮助资源

* [Adobe Analytics 产品文档及教程](https://experienceleague.adobe.com/docs/analytics.html?lang=zh-Hans)

## ![图标](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager 中的修复和改进。

### 修复和改进功能 {#aam-fixes-and-improvements}

* 发布了[活动使用情况报表](https://experienceleague.adobe.com/docs/audience-manager/user-guide/features/administration/activity-usage-reporting.html?lang=en)的增强功能，该功能现在允许您查看超过一年的数据。 (AAM-58268)
* Adobe为Audience Manager客户提供Audience ManagerAmazon S3存储段的用户访问密钥。 出于安全原因，密钥在处于不活动状态100天后会自动禁用。 有关更多信息，请参阅[数据收集和产品集成常见问题解答](https://experienceleague.adobe.com/docs/audience-manager/user-guide/faqs/faq-data-collection.html?lang=en)中页面底部的问题。

## ![图标](/assets/aem.png) Experience Manager {#aem}

 Experience Manager (AEM) 中的新增功能、修复和更新。Adobe 建议采用内部部署的客户部署最新的修补程序以确保稳定性、安全性和性能得到提高。

>[!NOTE]
>
>Adobe 建议访问 [Experience Manager 版本更新和路线图](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=zh-Hans)页面以及时了解版本信息。

### Experience Manager产品更新

* **Experience Manager 6.5.9.0**

   Experience Manager6.5,Service Pack 9.0（6.5.9.0,2021年5月27日发布）是一项重要更新，其中包括自2019年4月推出AEM 6.5通用版本以来发布的新功能、客户请求的关键增强功能、改进的性能、稳定性和安全性。

   * [发行说明](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=zh-Hans)
   * [AEM Forms 发布的交付内容](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html?lang=en)

### Experience Manager产品版本

* **Experience Manager 即云服务**

   Experience Manager 即云服务中的新增功能：

   * **Adobe Experience Manager Sites 即云服务 基础**

      * [预发行渠道](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/prerelease.html?lang=en):在即将推出的功能投入生产前一个月预览这些功能！
      * [API弃用](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/deprecated-apis.html?lang=en):最新已弃用API的列表。
      * [Experience Manager作为Cloud ServiceSDK Build Analyzer Maven插件](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/developing/archetype/build-analyzer-maven-plugin.html?lang=en):将您的Maven项目更新到最新版本，该版本包括已弃用的Java™ API检查和其他改进。
   * **Experience Manager Sites as a Cloud Service**

      现在，您可以在新的[预览层](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/authoring/fundamentals/previewing-content.html?lang=en)上验证内容，以模拟最终体验外观，就像在发布层一样。 此新功能由Experience Manager站点管理的发布向导启用，通过该向导，您可以在[!UICONTROL 发布]或[!UICONTROL 预览]之间选择发布目标。 然后，可以通过专用URL访问[!UICONTROL 预览]上的体验。 在[!UICONTROL Preview]上进行验证后，您可以照常将内容从[!UICONTROL Author]发布]发布到[!UICONTROL 。 在Experience Manager环境中启用[!UICONTROL 预览]服务，这项服务将在接下来的几周逐步推出。

   * **Experience Manager Assets as a Cloud Service**

      预发行渠道的新增功能：

      * 元数据架构可以直接应用到文件夹属性。
      * [!UICONTROL 资产批量摄取]工具允许您在批量摄取期间添加元数据。
      * 用户体验增强功能可显示文件夹中存在的资产数量。 对于文件夹中超过1000个资产，Experience Manager资产显示的资产数量超过1000个。

      [!UICONTROL Dynamic Media]的新增功能：

      * 智能成像设备像素比(DPR)和网络带宽优化让您能够在具有高分辨率显示器和有限网络带宽的设备上高效交付最佳质量的图像。 请参阅[智能成像常见问题解答](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/dynamicmedia/imaging-faq.html?lang=en)。



### **Experience Manager社区**

* [一站式购买所有Experience Manager博客](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/bd-p/adobe-experience-manager-discussions)

* [提交新Experience Manager构思的准则](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/guidelines-for-submitting-a-new-experience-manager-aem-idea/td-p/382376)

* [2021年Adobe Summit与丹·利维私下](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-summit-2021-sneaks-with-dan-levy/td-p/405865):每年，每位Adobe员工（从工程师、数据科学家到UX设计师和产品经理）都有机会分享创新想法，以改进品牌与客户交互的方式。加入我们的Adobe“秘密”，我们分享前七个项目，利用人工智能和低代码应用程序等领域的最新技术。

### Experience Manager 发行信息

所有的 Experience Manager 发行说明均保留在以下页面：

* [Experience Manager 即云服务版本信息](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/home.html?lang=en)
* [Experience Manager为Cloud Service发行说明](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html?lang=en)
* [Experience Manager Cloud Manager 发行说明](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=en)
* [Automated Forms Conversion Service 发行说明](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=en)
* [Experience Manager 6.5 Service Pack 发行说明](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=en)
* [Experience Manager 6.4 Cumulative Fix Pack 发行说明](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=zh-Hans)
* [Experience Manager Assets Dynamic Media 发行说明](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=zh-Hans)
* [Experience Manager Brand Portal 发行说明](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=zh-Hans)
* [Experience Manager 桌面应用程序发行说明](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=en)
* [Experience Manager Dispatcher 发行说明](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=zh-Hans)
* [Livefyre 发行说明](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=zh-Hans)

### Experience Manager 的新课程和教程 {#tutorials-aem}

过去一个月发布的新视频、教程及课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 6 月 | [实现接口的方法](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/implement-interface.html?lang=en) | 文章 | 了解如何实施界面方法以使用Document CloudREST API创建PDF。 |
| 2021 年 6 月 | [创建服务界面](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/create-interface.html) | 文章 | 在界面中定义要公开的方法。 |
| 2021 年 6 月 | [创建自定义OSGi配置](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/create-doc-cloud-configuration.html?lang=en) | 文章 | 了解自定义OSGi配置，以便捕获Adobe I/O项目详细信息。 |
| 2021 年 6 月 | [创建内容分析器](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/get-content-analyzer.html?lang=en) | 文章 | 了解如何创建JSON部件，其中包含有关创建PDF REST调用的输入参数的信息。 |
| 2021 年 6 月 | [创建自定义流程步骤](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/custom-process-step.html?lang=en) | 文章 | 查看自定义流程步骤的完整代码，该步骤将转换本机文件并将其替换为转换的PDF。 此自定义步骤将搜索文件夹名称下的所有附件，该文件夹名称将作为工作流中的进程参数提供。 此自定义流程步骤使用自定义`DocumentCloudSDKService`的方法创建PDF。 |
| 2021 年 6 月 | [GraphQL持久查询](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/video-series/graphql-persisted-queries.html?lang=en) | 视频 | 了解如何在Experience Manager中启用、创建、更新和运行持久查询。 |
| 2021 年 6 月 | [在AEM Forms中创建您的第一个Servlet](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/creating-your-first-osgi-bundle/create-servlet.html?lang=en) | 文章 | 构建您的第一个sling servlet，以便将数据与表单模板合并。 |
| 2021 年 6 月 | [使用Experience Manager表单创建您的首个OSGi服务](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/creating-your-first-osgi-bundle/create-osgi-service.html?lang=en) | 文章 | 使用AEM Forms构建您的第一个OSGi服务，以便通过将数据与模板合并来生成PDF。 |

{style=&quot;table-layout:auto&quot;}

### Experience Manager 的其他帮助资源

* [Experience Manager Sites 即云服务指南](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/landing/home.html?lang=en)
* [Experience Manager 6.5 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=zh-Hans)
* [Experience Manager 6.4 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=zh-Hans)
* [Experience Manager 6.3 学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-3.html)
* [Experience Manager 6.2 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=zh-Hans#previous-updates)
* [Experience Manager 文档的旧版本](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Cloud Manager 用户指南](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=zh-Hans)
* [Dynamic Media Classic 帮助主页](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=zh-Hans)
* [Experience Manager 文档：最近的更新](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=zh-Hans#aem-as-a-cloud-service)

## ![图标](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign 提供了一种直观、自动的方式，以通过在线和离线营销渠道来交付一对一的消息。您现在可以利用根据客户习惯和喜好所决定的体验，来预测客户的需求。

### 最新产品版本

详细了解最新发布的功能、改进和修复：

* **新的Adobe Campaign v8** 提供了重要的基础架构、安全性、可交付性和监控增强功能。Adobe Campaign v8显着提高了其规模和速度，能够管理更多的客户用户档案，以及更高的每小时交付率和交易。 请参阅[Campaign v8文档](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html)，以了解更多信息。

* **Adobe Campaign Classic v7 21.1.3版本：** 在Campaign Classicv7发行说明中 [了解详情](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=zh-Hans)。

* **Adobe Campaign Standard 21.2版本：** 在Campaign Standard发行说明中 [了解更多信息](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=zh-Hans)。

### 新的[!UICONTROL Campaign]课程和教程 {#tutorials-campaign}

| 发布日期 | 名称 | 解决方案 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 6 月 | [将 Campaign Standard 与 Analytics 集成以优化电子邮件营销](https://experienceleague.adobe.com/?lang=zh-Hans?recommended=Campaign-U-1-2021.1.integration) | Campaign Standard | （课程）了解如何将Campaign Standard与Adobe Analytics集成，以及如何使用实时数据优化电子邮件营销策略。 本课程展示如何在 Adobe Analytics 中构建 Campaign Standard 报表。然后，学习如何使用 Experience Cloud 触发器和 Platform Launch 根据客户活动配置营销和事务性消息。 |
| 2021 年 6 月 | [Adobe Campaign V8 教程](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/overview.html) | Campaign V8 | 本用户指南包含了有关 Adobe Campaign V8 的众多特性和功能的视频和教程。 |
| 2021 年 6 月 | [创建和设计电子邮件发送](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/content-creation/email/create-and-design-email-deliveries.html) | Campaign V8 | （视频）了解创建电子邮件投放的流程，并了解如何设计和个性化电子邮件内容。 |
| 2021 年 6 月 | [针对可达性设计电子邮件](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/email/design-emails-for-deliverability.html) | Campaign V8 | （视频）了解如何将投放能力最佳实践应用于电子邮件投放。 |
| 2021 年 6 月 | [使用分类规则管理疲劳](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/fatigue-management/typology-rules-for-fatigue-management.html) | Campaign V8 | （视频）了解如何通过应用分类规则来实施疲劳管理。 |
| 2021 年 6 月 | [使用过滤器设置疲劳管理](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/fatigue-management/fatigue-management-using-filters.html) | Campaign Standard | （视频）了解如何使用过滤器在Adobe Campaign中实施疲劳管理。 |

{style=&quot;table-layout:auto&quot;}

### Campaign 帮助资源

* Adobe Campaign Standard：[帮助中心](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=zh-Hans) - [发行说明](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=en) - [操作方法视频](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=zh-Hans) - [发行计划](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=zh-Hans) - [最新文档更新](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=zh-Hans)
* Adobe Campaign Classic：[帮助中心](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=zh-Hans) - [发行说明](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=en) - [操作方法视频](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=zh-Hans)- [最新文档更新](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=zh-Hans)
* Adobe Campaign 控制面板：[文档](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en) - [发行说明](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=en) - 有关 [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=zh-Hans)/[Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=zh-Hans) 的操作方法视频

## ![Icon](/assets/advertising-cloud.png) 广告 {#adcloud}

[!DNL Adobe Advertising] 的发行说明。

* [Advertising DSP 中的新增功能](#adcloud-dsp)
* [Advertising Search 中的新增功能](#adcloud-search)

### [!DNL Advertising DSP] 中的新增功能   {#adcloud-dsp}

上次更新时间：**2021年6月10日（适用于6月16日版）**

| 功能 | 描述 |
| -----------| ---------- |
| 营销活动管理 | （6月16日发布）预测适用于具有投放级别步调和预算的标准展示版面。 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Advertising Search] 中的新增功能   {#adcloud-search}

上次更新：**2021 年 5 月 19 日发布 5 月 18 日版**

| 功能 | 描述 |
| -----------| ---------- |
| [!UICONTROL 通知中心 Beta 版] | [!UICONTROL 通知中心 Beta 版]现在向所有用户开放。使用它订阅关于帐户身份验证错误、触发的自定义警报以及完成您生成的 [!UICONTROL Advertising Insights] 的电子邮件和 Web 通知。<br>可从以下任意一项中查看通知：<ul><li>[!UICONTROL “通知”]面板，从任意页面右上角的“通知”链接打开它。</li><li>[!UICONTROL “见解和报表”>“通知中心 Beta 版”]上的[!UICONTROL “通知中心”]。</li></ul><br><b>注意：</b>由于改进了通知的存储方式，因此清除了所有现有的通知。 |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/magento.png) [!DNL Magento] {#magento}

有关最新版本信息，请参阅 Magento Commerce 和开源[发行说明](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)。

## ![图标](/assets/target.png)[!DNL Target] {#target}

请参阅[[!DNL Target] 发行说明](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=zh-Hans)了解最新发行信息。

## ![图标](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] 是一个全面的应用程序，适用于寻求通过积极参与复杂购买过程的每个阶段而改善客户体验的销售线索管理和 B2B 营销人员。

### 核心 Marketo Engage 更新

请参阅[!DNL Marketo Engage] [发行计划](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=en) ，了解最新发行计划信息和发行说明。

## ![图标](/assets/workfront.png) [!DNL Workfront] {#workfront}

Adobe[!DNL Workfront]是一个统一的工作管理应用程序，用于分享想法、创建内容、管理复杂流程并尽其最大努力。

有关所有产品的最新信息汇总，请参阅[[!DNL Workfront] 发行版](https://one.workfront.com/s/product-releases)页面。

## ![图标](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

为 Adobe Document Cloud 发布的新视频、教程或课程。

### Document Cloud课程和教程 {#tutorials-doc-cloud}

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 6 月 | [Adobe Acrobat for Google Drive](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/acrobatandgoogle.html) | 视频 | 直接在Google Drive应用程序内访问节省时间的PDF工具和电子签名工作流。 |

{style=&quot;table-layout:auto&quot;}

有关 Document Cloud 的帮助，请参阅：

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=zh-Hans)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=zh-Hans)
* [Document Cloud 学习与支持](https://helpx.adobe.com/cn/support/document-cloud.html)

## ![](/assets/creative-cloud-24.png) IconCreative Cloud企业版 {#creative-cloud}

发布的关于企业Creative Cloud的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| ----------| --------- | --------- | --------- |
| 2021 年 6 月 | [在iPad（和iPhone）上尝试Fresco](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/frescoworkshop.html) | 视频 | 在这个15分钟的动手实践研讨会上，探索与Adobe Fresco一起进行数码绘画的全新世界。 快速学习如何使用图层和剪贴蒙版，以便将绘画和纹理与基本形状保持一致。 |
| 2021 年 6 月 | [解读图形格式的字母汤](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/alphabetsoup.html) | 视频 | PG、PNG、SVG、GIF和EPS文件都常用于设计，有的用于网页，有的用于演示文稿、出版物和创意项目。 但是……他们什么意思，你该选哪个？ 在这个15分钟的动手练习研讨会上了解。 |

{style=&quot;table-layout:auto&quot;}

有关最新教程，请参阅 [Creative Cloud 企业版教程](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=zh-Hans)。
