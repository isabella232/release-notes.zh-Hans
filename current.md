---
title: Adobe Experience Cloud 发行说明
description: Adobe Experience Cloud 发行说明
doc-type: release notes
last-update: September 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 113528f8e43d06e75d9fbb9db8bc229056e6f0f2
workflow-type: tm+mt
source-wordcount: '6762'
ht-degree: 39%

---


# 早期访问-Adobe Experience Cloud发行说明- 2020年9月

![横幅](/assets/experience-cloud-banner-3.png)

此页面介绍了 [!DNL Adobe Experience Cloud] 中的新增功能、修复和重要声明。此外，还重点提供了可帮助您充分利用 Experience Cloud 的新文档、培训课程和视频教程。

>[!IMPORTANT]
>
>此页面包含预发行内容，在发行版之前可能会发生更改。

>[!NOTE]
>
>若要通过电子邮件接收有关即将发行的版本的通知，请订阅 [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html)。

**发行日期：2020 年 9 月 10 日**

产品发行日期可能有所不同。请定期查看以获取最新信息。

最新更新： **2020年9月4日**

* [Adobe 系统状态](#status)
* [Experience Cloud 界面](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Analytics](#analytics) 和 [Customer Journey Analytics](#cust-journey)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [[!DNL Target]](https://docs.adobe.com/content/help/zh-Hans/target/using/release-notes/target-release-notes.html)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo)
* [[!DNL Primetime]](https://docs.adobe.com/content/help/zh-Hans/primetime/release-notes/home.html)

需要帮助？请访问 [Adobe Experience League](https://experienceleague.adobe.com/#home)，查找产品和技术文档、Adobe 策划课程、视频教程、快速解答、社区洞察以及由讲师指导的培训。

## ![图标](/assets/adobe.png) Adobe 系统状态 {#status}

[!UICONTROL Adobe 系统状态]提供关于 Adobe 云产品与服务中断和维护事件的详细信息、状态更新以及电子邮件通知。请访问 [status.adobe.com](https://status.adobe.com/) 查看。

请参 [阅Adobe系统状态- 2020年5月](https://docs-stg.corp.adobe.com/content/help/en/release-notes/experience-cloud/previous/2020/05212020.html#status) 21日，了解最新版本信息。

## ![图标](/assets/ec_appicon_24.png) Experience Cloud 界面 {#ecloud}

有关Experience Cloud [界面的最新版本信息](https://docs.adobe.com/content/help/en/core-services/interface/release-notes/release-notes.html) (客户属性、受众、用户和产品管理)，请参阅累积发行说明。

## ![图标](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

[!DNL Experience Platform] 和应用程序服务的发行说明，包括 [!DNL Experience Platform Launch,]、[!UICONTROL Offers]、[!UICONTROL People]、[!UICONTROL Places]、[!UICONTROL Mobile Services] 和安全公告。

发行日期：**2020 年 8 月 12 日**

Adobe Experience Platform现有功能更新：

* [数据科学工作区](https://docs.adobe.com/content/help/en/experience-platform/release-notes/latest.html#dsw)
* [目标](https://docs.adobe.com/content/help/en/experience-platform/release-notes/latest.html#destinations)
* [源](https://docs.adobe.com/content/help/en/experience-platform/release-notes/latest.html#sources)

有关 Experience Platform 的最新信息，请参阅 [Experience Platform 发行说明](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)。

### Experience Platform和服务教程与课程

为Experience Platform和服务发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 8 月 17 日 | [调试启动实施](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/experience-platform-launch/debug-launch-implementation.html) | 视频 | 介绍调试Launch实现的一些常用工具和技术。 了解如何使用浏览器的开发人员控制台和Experience Platform调试器扩展来识别和排除启动实施的关键方面的故障。 |
| 2020 年 8 月 17 日 | [创建启动Cloud Service配置](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/experience-platform-launch/create-launch-cloud-service.html) | 视频 | 了解如何创建新的启动Cloud Services配置。 然后，可以将启动Cloud Service配置应用于现有站点，并可以在创作和发布环境中观察到启动库的加载情况。 |
| 2020 年 8 月 17 日 | [使用AdobeI/O将AEM与Launch连接](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/experience-platform-launch/connect-aem-launch-adobe-io.html) | 视频 | 了解如何使用AdobeI/O创建IMS配置，以通过Launch API验证AEM。 在此集成到位后，AEM将能够通过Launch API进行通信以访问Launch属性。 |
| 2020 年 8 月 17 日 | [同意管理- Google IAB TCF 2.0支持](https://docs.adobe.com/content/help/en/platform-learn/tutorials/rtcdp/integrate-with-iab-transparency-and-consent-framework-2.html) | 视频 | 此视频展示了Adobe的实时客户数据平台如何帮助品牌在消费者参与数字资产时赢得消费者的同意。 通过IAB的透明度和同意框架2.0的支持，品牌在如何与消费者互动方面获得了更大的灵活性，同时为消费者提供了对同意的更大控制。 |
| 2020 年 8 月 17 日 | [Google客户匹配](https://docs.adobe.com/content/help/en/platform-learn/tutorials/rtcdp/integrate-with-google-customer-match.html) | 视频 | 此视频展示了Adobe的实时CDP和Google的客户匹配功能如何帮助品牌在Google自有和运营的资产上与其客户互动，从而实现业务目标以增加其外联活动。 |
| 2020 年 8 月 17 日 | [数据工程师Adobe Experience Platform入门课程介绍](https://video.tv.adobe.com/v/39478?captions=chi_hans) | 视频 | 数据工程师Adobe Experience Platform [入门课程的介绍视频](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-D-1-2020.2) 。 |
| 2020 年 8 月 17 日 | [Adobe Experience Platform数据工程师入门](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-D-1-2020.2) | 课程 | 了解如何在Adobe Experience Platform完成重要的数据工程师任务。 此入门级课程使用视频和手工练习，帮助您开始使用批量数据、使用Web SDK获取流数据、运行查询等。 |
| 2020 年 8 月 17 日 | [数据架构师Adobe Experience Platform入门课程介绍](https://video.tv.adobe.com/v/39477?captions=chi_hans) | 视频 | 此视频概括介绍了面向数 [据架构师的Adobe Experience Platform入门](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-D-1-2020.1) 。 |
| 2020 年 8 月 17 日 | [数据架构师Adobe Experience Platform入门](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-D-1-2020.1) | 视频 | 了解如何在Adobe Experience Platform实现关键的数据架构师任务。  此入门级课程使用视频和手工练习，帮您开始将建模数据构建到XDM模式中，标记身份将数据整合到实时用户档案中，创建细分等。 |

## ![图标](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

凭借 Adobe Experience Platform，可以实时智能化预测每位客户的需求（无论其旅程通达何处），从而实现跨体验渠道大规模编排客户历程。

### 新的产品版本

* August release - [Read more](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html#august-release)

### [!UICONTROL Journey Orchestration] 课程和教程

为Journey Orchestration发布的新视频、教程和课 [!UICONTROL 程]。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 8 月 10 日 | [使用区段鉴别事件](https://docs.adobe.com/content/help/en/journey-orchestration-learn/tutorials/using-segment-qualification-events.html) | 视频 | This video gives you a brief introduction on how to create a journey with a [!UICONTROL Segment Qualification] event as entry or exit point. |

### Journey Orchestration 的其他资源

[文档](https://docs.adobe.com/content/help/zh-Hans/journeys/using/journey-orchestration-home.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/journeys/using/release-notes/release-notes.html) - [操作方法视频](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

## ![图标](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

* [Adobe Analytics 中的新增功能](#aa-features)
* [Customer Journey Analytics 的新增功能](#cust-journey)
* [Media Analytics 的新增功能](#media-aa)
* [Adobe Analytics 中的修复](#aa-fixes)
* [Analytics 管理员的重要注意事项](#aa-notices)
* [分析课程和教程](#tutorials-analytics)
* [AppMeasurement](#appm)

### Adobe Analytics 中的新增功能 {#aa-features}

| 功能 | [正式发布](https://docs.adobe.com/content/help/zh-Hans/analytics/landing/an-releases.html) - 目标日期 | 描述 |
| ----------- | ---------- | ------- |
| [!UICONTROL 跨设备分析]：在 EMEA 和 APAC 提供 | 2020 年 8 月 31 日 | [跨设备分析](https://docs.adobe.com/content/help/zh-Hans/analytics/components/cda/overview.html) 和专用图表适用于EMEA和APAC的客户。 |
| 跨设备分析中基于现 [!UICONTROL 场的拼接增强] （全球提供） | 2020 年 8 月 31 日 | 这为新的[!UICONTROL 跨设备分析]客户简化了实施过程，让您可以选择根据存储在 Analytics 字段（prop 或 eVar）中的用户 ID 进行拼合，而不使用设备图（协作图或专用图）。这项增强功能减免了实施 ECID 的需求，同时还消除了为 CDA 实施 ID 同步的需求。（有些其他功能仍要求实施 ECID 和 ID 同步。） |
| 中国数据收集，第2阶段 | 2020 年 9 月 1 日 | 扩展了对第一方SSL的支持。 |
| Workspace中的新日期范围 | 2020 年 9 月 10 日 | 我们将添加5个新的日期范围，这样您就可以从不包含今天部分日期数据的日期范围中进行选择：最近7整天，最近14整天，最近30整天，最近60整天，最近90整天 |
| 工作区：下载适合单个维度的 50,000 个项目 | 2020 年 9 月 17 日 | 您将能够在自由格式表中下载适合单个维度的 50,000 个项目，并应用区段和过滤器。这允许您访问 Analysis Workspace 以外 400 多行数据。[了解更多...](https://docs.adobe.com/content/help/zh-Hans/analytics/analyze/analysis-workspace/curate-share/download-send.html#download-items) |
| 工作区：对Line可视化 [!UICONTROL 的增强] | 2020 年 9 月 17 日 | <ul><li>You can show or hide the x-axis and y-axis of any [!UICONTROL Line] visualization. This can be especially helpful when your [!UICONTROL Line] visualizations are more compact.</li><li>You can overlay a minimum and maximum value label on any [!UICONTROL Line] visualization to quickly highlight the peaks and valleys in a metric.</li><li>You can overlay different regression trend lines on any [!UICONTROL Line] visualization to more easily see the trend in the data. Options include [!UICONTROL Linear], [!UICONTROL Logarithmic], [!UICONTROL Exponential], [!UICONTROL Power] and [!UICONTROL Quadratic].</li></ul> [了解更多...](https://docs.adobe.com/content/help/zh-Hans/analytics/analyze/analysis-workspace/visualizations/line.html) |

### Customer Journey Analytics 的新增功能 {#cust-journey}

| 功能 | [正式发布](https://docs.adobe.com/content/help/zh-Hans/analytics/landing/an-releases.html) - 目标日期 | 描述 |
| ----------- | ---------- | ----- |
| 对Customer Journey Analytics权限的更改 | 2020 年 9 月 9 日 | CJA不再将所有用户视为管理员。 只有在Adobe Admin Console被指定为产品管理员的 [用户](https://docs.adobe.com/content/help/zh-Hans/core-services/interface/manage-users-and-products/admin-getting-started.html) ，才能执行以下操作：<ul><li>创建／更新／删除 [!UICONTROL 连接] 或数 [!UICONTROL 据视图]</li><li>更新／删除其他用户创建的项目、过滤器或计算量度</li><li>将Workspace项目共享给所有用户</li></ul>[了解更多...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-overview/cja-overview.html#admin-access-permissions) |
| 对[!UICONTROL 异常检测]的支持 | 2020 年 9 月 10 日 | [!UICONTROL 异常检测] 允许您确定哪些统计波动很重要，哪些不重要。此功能现在在Customer Journey Analytics中 [!UICONTROL 受支持]。 |
| Workspace中的新日期范围 | 2020 年 9 月 10 日 | 我们将添加5个新的日期范围，这样您就可以从不包含今天部分日期数据的日期范围中进行选择： [!UICONTROL 最近7天], [!UICONTROL 最近14天]，最 [!UICONTROL 近30天全天]，最 [!UICONTROL 近60天全天][!UICONTROL ，最近90天全天] |
| 工作区：对Line可视化 [!UICONTROL 的增强] | 2020 年 9 月 17 日 | <ul><li>You can show or hide the x-axis and y-axis of any [!UICONTROL Line] visualization. This can be especially helpful when your [!UICONTROL Line] visualizations are more compact.</li><li>You can overlay a minimum and maximum value label on any [!UICONTROL Line] visualization to quickly highlight the peaks and valleys in a metric.</li><li>You can overlay different regression trend lines on any [!UICONTROL Line] visualization to more easily see the trend in the data. Options include [!UICONTROL Linear], [!UICONTROL Logarithmic], [!UICONTROL Exponential], [!UICONTROL Power] and [!UICONTROL Quadratic].</li></ul> [了解更多...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/visualizations/line.html) |

### [!UICONTROL Media Analytics] 的新增功能 {#media-aa}

| 功能 | [正式发布](https://docs.adobe.com/content/help/zh-Hans/analytics/landing/an-releases.html) - 目标日期 | 描述 |
| ----------- | ---------- | ---------- |
| 工作区中的“媒体并行查看者”面板 | 2020 年 9 月 17 日 | The [!UICONTROL Media Concurrent Viewers] panel enables you to understand where peak concurrency occurred or where drop-offs happened. 它为内容质量和查看者参与度提供了有价值的分析，同时有助于对批量/规模进行疑难问题解答或规划。[了解更多...](https://docs.adobe.com/content/help/en/media-analytics/using/media-reports/media-workspace-panels/media-concurrent-viewers.html) |

### Adobe Analytics 中的修复 {#aa-fixes}

* 修复了阻止按“未指 [!UICONTROL 定] ”维筛选Workspace列的问题。 (AN-222393)
* 修复了阻止计划项目传 [!UICONTROL 送的连接] 超时问题。 (AN-223916)
* 修复了虚拟报告 [!UICONTROL 包中] “访 [!UICONTROL 问区段”] 无法正常工作的问题。 (AN-225719)
* 修复了Adobe Report Builder的Chrome浏览器版本问题。 (AN-226718)
* 修复了精选虚拟 [!UICONTROL 报表包的问题] ，该问题仍可能被VRS中的任何维度／指标细分。 (AN-228035)
* 修复了“区段管理器”单元中的搜索功 [!UICONTROL 能正常工] 作的问题。 (AN-226954)
* 修复了在尝试与一个或两个以 [!UICONTROL 上用户] 共享项目时Workspace中出现超时错误的问题。 (AN-229443)
* 修复了API请求引发系统故障错误的问题。 (AN-229537)
* 修复了 [!UICONTROL 分类规则构建器] ，该问题导致键值未被分类。 (AN-229786、AN-230300、AN-230563)
* 修复了数据插入 [!UICONTROL API不报告某] 些数据的问题。 (AN-230587)
* 修复了Data warehouse [!UICONTROL 请求] 无法获取和验证具有basename的文件的问题。 (AN-230642)
* ([!UICONTROL Customer Journey Analytics])修复了在CJA中共享项目时的权限问题。 (AN-226592)

#### 其他 Adobe Analytics 修复

AN-215683;AN-216894;AN-226370;AN-227138;AN-227154;AN-227328;AN-227486;AN-227672;AN-228264;AN-228960;AN-229031;AN-229274;AN-229319;AN-229353;AN-229537;AN-229610;AN-229975;AN-230008;AN-230015;AN-230347;AN-230468;AN-230473;AN-231326;AN-231329;AN-231345;AN-231509;AN-231795;AN-231901

### [!DNL Analytics] 管理员的重要注意事项 {#aa-notices}

| 注意事项 | 添加或更新日期 | 描述 |
| ----------- | ---------- | ---------- |
| 从 `omniture.com` 域迁移至 `adobe.com` 域 | 2020 年 8 月 21 日 | 2020 年 8 月 13 日，Adobe Analytics 将其前端架构从 `omniture.com|http://omniture.com/` 域迁移至 `adobe.com|http://adobe.com/` 域。这项变更可以缓解自 2020 年 5 月 28 日首次统一产品域更改以来引发的第三方 Cookie 问题。As a result of this update, the browser may prompt users to trust the new an `.adobe.com|http://an.adobe.com/` or `experience.adobe.com|http://experience.adobe.com/` domain. |
| 关于 Ad Hoc Analysis 与 Java 8 兼容性的最新信息 | 2020 年 8 月 21 日 | Ad Hoc Analysis 目前与 Java 8 版本 1.8.0_261+ 不兼容。为了确保能够在这个工具[生命周期终止日期](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)之前持续访问该工具，我们建议您安装版本低于 1.8.0_261 的 Java 8。 |
| Adobe Data Connectors 生命周期终止 | 2020 年 7 月 13 日 | Adobe [!UICONTROL Data Connectors] 由传统技术提供支持，而这些技术不再可行或不再受支持。我们在 [Adobe Exchange 合作伙伴项目](https://partners.adobe.com/exchangeprogram/experiencecloud)中采用了一个新标准，任何希望继续提供和支持的集成应采用此标准。正式的生命周期终止日期仍有待确定，但我们预计将会在未来 12-18 个月（2021 年中至 2021 年底）后终止。[了解更多...](https://docs.adobe.com/content/help/zh-Hans/analytics/import/dataconnectors/data-connectors-eol.html) |
| 将报表包映射到 IMS 组织 | 2020 年 7 月 | 报表包映射工具将于 2020 年 11 月停止使用。此功能支持集成，例如 Adobe Analytics 中的 Advertising Analytics 和 Experience Cloud 区段发布。必须将报表包映射到 IMS 组织，才能启用这些服务和其他服务。之后创建新的报表包时会自动映射。但是，之前的旧报表包必须手动映射到 IMS 组织。请参阅 Experience Cloud 界面（核心服务）用户指南中的[将报表包映射到组织](https://docs.adobe.com/content/help/zh-Hans/core-services/interface/about-core-services/report-suite-mapping.html)，以确保所有报表包都属于 IMS 组织。 |
| 迁移到统一的产品域 | 生效日期：2020 年 5 月 28 日 | 向 Adobe Analytics 统一产品域的迁移从 2020 年 1 月开始，于 2020 年 5 月 28 日完成。虽然 Adobe Analytics 会从其架构中删除所有 `omniture.com` 域引用，但务必要将 `omniture.com` 作为第三方 Cookie 添加到白名单中。（不久）完成整个架构迁移后，我们将通过发行说明通知您，此允许列表步骤将不再需要执行。[此处](https://helpx.adobe.com/cn/analytics/kb/adobe-ip-addresses.html)提供了建议应添加到白名单中的 IP 地址和域的完整列表。<br>如果贵组织阻止第三方 Cookie，请联系客户关怀团队以重新获得 Adobe Analytics 访问权限。 |
| 新的 Adobe Analytics 默认登陆页面 | 生效日期：2020 年 6 月 18 日 | 2020 年 6 月 18 日，Adobe Analytics 的默认登陆页面将从[!UICONTROL 报表]更改为[!UICONTROL 工作区]。之前未设置自定义登陆页面的任何用户都将发生此更改。 |
| 第三方技术允许列表 | 2020 年 3 月 12 日（生效日期） | Adobe Analytics 已开始利用第三方技术进行功能推出管理和提供产品内支持。应将以下 URL 添加到所有必要的网络防火墙允许列表中，以确保能够完全访问功能：<ul><li>Gainsight：https://esp.aptrinsic.com</li><li>LaunchDarkly：https://app.launchdarkly.com</li></ul> |
| 改善了 [!UICONTROL Analysis Workspace] 可用性的冗余 | 2020 年 5 月 21 日 | 为确保 [!UICONTROL Analysis Workspace] 的可用性，我们添加了辅助 CDN（内容交付网络），以改善冗余。应将以下 URL 添加到任何必要的网络防火墙允许列表中：<ul><li>`https://aaui-879784980514.s3.us-east-2.amazonaws`</li><li>`https://d30ln29764hddd.cloudfront.net`</li><li>`https://awaascicdprodva7.blob.core.windows.net`</li><li>`https://aauicdnva7.azureedge.net`</li></ul> |
| 在[!UICONTROL 工作区]中更改[!UICONTROL 登入/退出]的计算方式 | 2020 年 4 月 7 日 | 在 [!UICONTROL Analysis Workspace] 中，从 2020 年 3 月起，我们更改了&#x200B;_无_&#x200B;值与[!UICONTROL 登入/退出]的交互方式。由于您现在可以在 _Analysis Workspace_ 中打开和关闭[!UICONTROL 无]，因此我们会在登入或退出后应用&#x200B;_无_&#x200B;值，而（对于 eVar）过去是在登入或退出前应用。例如，假定访问的第一次点击没有 eVar 值，但第二次点击有。在 [!UICONTROL Reports &amp; Analytics] 中，第一次点击将针对“登入”显示为&#x200B;_未指定_，但在 [!UICONTROL Analysis Workspace] 中，将显示第二次点击时的值。 |
| **[!UICONTROL 功能板存档]**&#x200B;生命周期终止 | 2020 年 3 月 27 日 | 自 2020 年 10 月起，在 [!UICONTROL Reports &amp; Analytics] 中，位于&#x200B;**[!UICONTROL 管理功能板]**&#x200B;下方的&#x200B;**[!UICONTROL 查看存档]**&#x200B;将不再可用。 |
| Analytics 旧版 API 生命周期终止 | 2020 年 1 月 9 日 | 2020 年 11 月，以下 Analytics 旧版 API 服务将停止使用并关闭。当前使用这些服务构建的集成将会停止工作。 <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>旧版 OAuth 身份验证（OAuth 和 JWT）</li></ul>我们提供了[旧版 API EOL 常见问题解答](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)，以帮助回答您的问题并提供有关如何继续的指导。使用这些服务的 API 集成可以迁移到 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 或 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。旧版 OAuth 帐户可迁移到 [Adobe IO](https://console.adobe.io/home?mv=email) Analytics 集成帐户，该帐户可用于访问 1.4 Analytics API 和 2.0 Analytics API。 |
| 圣何塞 FTP 中转站停止为伦敦和新加坡提供支持 | 2020 年 7 月 | 对于位于伦敦和新加坡的客户，我们将不再提供伦敦或新加坡与圣何塞数据中心 [ftp.omniture.com](ftp://ftp.omniture.com/) 之间的数据中转支持。<br/><ul><li>伦敦客户，请使用 [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>新加坡客户，请使用 [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Ad Hoc Analysis 生命周期终止 | 2018 年 8 月 6 日 | Adobe 宣布计划终止 Ad Hoc Analysis 生命周期。确定终止日期后，Adobe 会立即与大家共享此信息。有关更多信息，请参阅[探索工作区](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)。 |

### AppMeasurement {#appm}

有关 AppMeasurement 版本的最新更新，请参阅[适用于 JavaScript 的 AppMeasurement 发行说明](https://docs.adobe.com/content/help/zh-Hans/analytics/implementation/appmeasurement-updates.html)。

### Analytics courses and tutorials {#tutorials-analytics}

New courses, tutorials, and articles in [!DNL Analytics] and [!UICONTROL Customer Journey Analytics].

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 8 月 30 日 | [Analysis Workspace项目的保存、共享和协作](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/curate-and-share-projects/saving-sharing-and-collaborating-on-projects-in-analysis-workspace.html) | 视频 | 在 [!UICONTROL Analysis Workspace]，了解如何向表格添加文本说明、为项目创建直接链接并共享它。 |
| 2020 年 8 月 28 日 | [课程简介——将价值归因于客户旅程中的数字接触点](https://video.tv.adobe.com/v/39380?captions=chi_hans) | 视频 | 在此介绍性视频中，学习在客户旅程课程中将价 [值归因于数字接触点的先决条件和课程内容](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2020.2) 。 |
| 2020 年 8 月 28 日 | [将价值归因于客户旅程中的数字接触点](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2020.2) | 课程 | 了解网站访客的来源，如何为网站上的渠道分配转化信用，甚至了解网站上的其他项目如何促进转化，从而了解网站。 本课程教您显示此分析的主要可视化信息，以及如何使用 [!UICONTROL Attribution IQ] 在分析中分配归因模型。 |
| 2020 年 8 月 21 日 | [使用跨标签分析探索Analysis Workspace的基本营销归因](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/attribution-iq/using-cross-tab-analysis-to-explore-basic-marketing-attribution-in-analysis-workspace.html) | 视频 | 您可以通过多种方式将归因方法与Adobe Analytics一起提升到新的高度。 在此视频中，我们重点介绍如何使用Workspace中的跨选项卡 [!UICONTROL 渠道] ，从营销分析报表获得更深入 [!UICONTROL 的洞察]。 |
| 2020 年 8 月 21 日 | [右键单击可提高工作区效率](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/navigating-workspace-projects/right-click-for-workspace-efficiency.html) | 视频 | 了解我们最喜爱的Analysis Workspace右键点击以及如何使用它们。 从自由格式表到流失可视化，右键单击可让您更高效、更精通工作区。 |

### Analytics 帮助资源

* [Adobe Analytics 教程](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics 产品文档](https://docs.adobe.com/content/help/zh-Hans/analytics/landing/home.html)

## ![图标](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Audience Manager 中的新增功能、修复、文档和教程。

发行日期：**2020 年 9 月 20 日**

### Adobe Audience Manager 中的新增功能和修复

* 修复了受众实 [!UICONTROL 验室中] ，测试段填充在聚合报告下 [!UICONTROL 不可用的问题]。 (AAM-54553)
* 修复了使用第三方算法模型的段在Audience Marketplace的“段使用 [!UICONTROL 视图”中] 不显示的 [!UICONTROL 问题]。 (AAM-54595)
* 修复了某些用户在尝试删除数据源时遇到错误的问题，即使没有特征或区段映射到数据源。 (AAM-55609)
* 修复了访客用户档案查看器报告中不显示区段的问题。 (AAM-55780)
* 修复了“目标列表”页面上的一个问题，该问题 **[!UICONTROL 导致在]** “回顾” **[!UICONTROL 窗口的“度量”筛选器中选]** 择“生命周期”后，将返回一个空白页面。 (AAM-49732)
* 修复了特征仪表板中的一个问题，该问题 **[!UICONTROL 在从]** “所有特征”筛选到任&#x200B;**[!UICONTROL 何筛选器(基于规]**&#x200B;则、已载入 ****&#x200B;等)时，将更新度量，但特征名称和ID不会更新。 (AAM-55823)
* 修复了基于人 [!UICONTROL 员的目标中]，由于API调用中缺少字段，映射到Facebook `traitAlias` 的区段无法更新的问题。 (AAM-55952)
* 修复了趋势 [!UICONTROL 报表中] ，在特征和区段之间切换时图形无法刷新的问题(AAM-54736)
* 修复了类 [!UICONTROL 似建模中] ，按下Pause **[!UICONTROL 控件]** 不会暂停模型，而是关闭模型的问题。 (AAM-56121)
* 改进了整个界面的多项无障碍功能。(AAM-48950、AAM-48957、AAM-49022、AAM-49026、AAM-49044、AAM-49069、AAM-49370、AAM-5989、AAM-5989、-59895990)。

### Audience Manager courses and tutorials {#tutorials-aam}

为Audience Manager发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 8 月 17 日 | [将Audience Manager段映射到目标](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/mapping-audience-manager-segments-to-destinations.html) | 视频 | 了解Audience Manager中不同类型的目标以及将区段映射到每个目标类型的详细信息。 |
| 2020 年 8 月 14 日 | [充分利用用户档案合并规则——提示、技巧和策略](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/profile-merge/customer-tips-getting-the-most-out-of-profile-merge-rules.html) | 文章 | Varun Kalra是上的多解决方案顾 [!DNL Accordant]问，提供了有关选择和使用用户档案合 [!UICONTROL 并规则的提示]。 |
| 2020 年 8 月 14 日 | [特征和细分最佳实践](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/customer-tips-traits-and-segments-best-practices.html) | 文章 | Matt Vittorioso，高级营销专家， [!DNL Ally Financial]提供了有关管理特征的提示。 |
| 2020 年 8 月 12 日 | [了解和配置Google客户匹配基于人的目标](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/data-activation/people-based-destinations/understanding-and-configuring-the-google-customer-match-pbd.html) | 视频 | 此视频将指导您了解Google客户匹配基于人 [!UICONTROL 的目标的详细信息和用例]，包括创建区段并将其映射到目标的逐步操作。 还显示受众在Google广告控制台中的登录。 |
| 2020 年 8 月 13 日 | [课程介绍-受众细分创建和策略](https://video.tv.adobe.com/v/39091?captions=chi_hans) | 视频 | 在此视频中，了解受众细分创建和战略课程中等待您的内容。 |
| 2020 年 8 月 13 日 | [在构建区段时使用代码视图 ](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/using-code-view-when-building-segments.html) | 视频 | 了解如何使用代码视图定义区段，从而允许您创建复杂的特征组合，包括使用最近期和频率。 |
| 2020 年 8 月 21 日 | [受众细分创建与策略](https://experienceleague.adobe.com/?recommended=AudienceManager-U-1-2020.2) | 课程 | 在本课程中，学习从A到Z的细分。了解如何创建、管理细分，以及将其激活到目标合作伙伴。 查看一些有用的使用案例，甚至从客户那里获得一些提示和技巧。 |

## ![图标](/assets/aem.png) Adobe Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新增功能、修复和更新。Adobe 建议那些采用内部部署的客户部署最新的修补程序，以便确保获得更高的稳定性、安全性和性能。

### 产品更新

* **AEM 6.5.6.0** AEM 6.5,Service Pack 6（2020年9月3日发布，为6.5.6.0）是一个重要更新，其中包括自AEM 6.5（2019年4月发布）以来发布的新功能、关键客户增强、改进的性能、稳定性和安全性。
   * [发行说明](https://helpx.adobe.com/cn/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [AEM Forms 发布的交付内容](https://helpx.adobe.com/cn/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.2** AEM 6.4,Service Pack 8,Cumulative Fix Pack 2（2020年9月3日发布的6.4.8.2）是一项重要更新，包含自2020年3月发布AEM 6.4、Service Pack 8(6.4.8.0)以来的若干内部和客户修复。
   * [发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-64/release-notes/cfp-release-notes.html)
   * [AEM Forms 发布的交付内容](https://helpx.adobe.com/cn/aem-forms/kb/aem-forms-releases.html)

### 产品版本

* **[!UICONTROL AEM 云服务]**

   What is new on [!UICONTROL AEM as a Cloud Service]? 主要亮点包括：

   * 可以 [!UICONTROL 在AEM中作为][Cloud Service将页面和子页面（页面树）恢复到较早版本](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/sites/authoring/features/page-versions.html#reinstating-versions)。
   * 现在，资产微型服务支持视频转码，“处理 [!UICONTROL 用户档案] ”屏幕中新增了“视频”部分，支持视频比特率和尺寸的配置（输出格式为MP4，带有H.264编解码器）。 有关详细信息，请 [参阅管理视频资产。](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/manage/manage-video-assets.html#transcode-video) 要获得更多转码选项和视 [!UICONTROL 频投放] ，可使用Dynamic Media加载项。
   * 新的资产下载体验允许，
      * 异步下载，以便用户无需等待。
      * 用于开发人员可扩展性的全新模块化API。
   * 您现在可以将AEM中Dynamic Media中的CDN(内容投放网络)缓 [!UICONTROL 存作为Cloud Service] (与使用Dynamic Media Classic相 反)直接失效，以确保在几分钟内而不是几小时内提供最新的资源。 请参 [阅通过Dynamic Media使CDN缓存失效。](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/invalidate-cdn-cache-dynamic-media.html)
   * 在资产的用户界面控件、导航、浏览和搜索体验中添加了增强的辅助功能支持。
   * AEM桌面应用程序2.0.3版本现已推出，它提高了与AEM 6.5、Service Pack 5(AEM 6.5.5)的兼容性，并更新了客户端操作系统兼容性列表（删除了10.14之前的Windows 7和MacOS版本）。
   * [!UICONTROL 现在] ,AEM Commerce中提供了“产 [!UICONTROL 品控制台”功能作为Cloud Service]。 这使AEM中的营销人员和作者能够视图和浏览存储在商务后端中的类别和产品。 还在产品控制台中提供对类别和 [!UICONTROL 产品属] 性的支持。
   * [!UICONTROL 产品] 和类别 [!UICONTROL 拣选器经过改进] ，使营销人员能够通过SKU选择产品或通过类别ID选择类别。
   * [!UICONTROL 内容审核] 是Cloud Manager Sites Production Pipelines [!UICONTROL 中启用的一项功能]。 具有 [!UICONTROL Sites的项目] ，其生产管 [!UICONTROL 道配置现] 在包含 **[!UICONTROL 名为“内容审]**&#x200B;核”的第三个选项卡。 每当运行生产管道时，在自定义功 [!UICONTROL 能测试后] ，管道中将包括新的内容审核步骤，该步骤将根据多个维度(包括性能、SEO（搜索引擎优化）、辅助功能、最佳实践和PWA（渐进式Web应用程序）)评估网站。
请参 [阅内容审核测试。](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/using-cloud-manager/test-results/content-audit-testing.html)
   * 现在，资产环境 [!UICONTROL 中新] 创建的项目将自动配 [!UICONTROL 置智能内容服务]。
   * 冬眠环境可以从云管理器的概述页面 **[!UICONTROL 解除]** 。
   * 能够在页面上执行体验检查，具体由支持 [!DNL Google Lighthouse]。 作为Cloud Manager [!UICONTROL 渠道的一部分] ，可根据体验KPI检查和验证最多25个页面，并在Cloud Manager UI中 [!UICONTROL 显示得分] 。
   * See the [AEM as a Cloud Service release notes.](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)

* **Experience Manager[!UICONTROL 桌面应用]2.0.3.2**

   此次要版本包括：
   * 修复了适用于Windows的桌面应用程序版本2.0.2不能与AEM 6.5.5实例一起使用的问题。
   * 使用最新的服务包和Mac OS 10.14或更高版本将支持的操作系统平台更新为Win 10。
   * See the [release notes.](https://docs.adobe.com/content/help/zh-Hans/experience-manager-desktop-app/using/release-notes.html)

* **[!UICONTROL AEM Assets Brand Portal]**

   此版本包括以下内容：
   * 文档查看器，可增强PDF查看体验。
   * 下载资产配置和体验中的增强功能。
   * 对关键产品问题的修复。
   * See the [release notes.](https://docs.adobe.com/content/help/zh-Hans/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)

### **自助**

* **AEM作为Cloud Service[!UICONTROL 过渡的新工具]**

   * 发布的AIO-CLI插件可统一代码重构工具，使开发人员能从一个位置调用和执行代码重构工具。 有关更多 [详细信息，请参阅GitHub资源aio-cli-plugin-aem-cloud-service-migration](https://github.com/adobe/aio-cli-plugin-aem-cloud-service-migration) 。
   * [!UICONTROL AEM Dispatcher Converter] 经过扩展，可支持将内部部署和Adobe [!UICONTROL Managed ServicesDispatcher配置转] 换为AEM(作为Cloud Service兼容的Dispatcher配置)。 有关更多详细信息， [请参阅GitHub资源AEM](https://github.com/adobe/aem-cloud-service-source-migration/tree/master/packages/dispatcher-converter) Cloud Service调度程序转换器。
   * AEM Dispatcher Converter重新写入node.js并与AIO-CLI插件集成。

* **Dynamic Media中的CDN[!UICONTROL 失效]**

   您现在可以在Dynamic Media中发 [!UICONTROL 送请求] ，使CDN缓存在几分钟内过期。 当您更新资产并希望这些更改立即在您的网站上生效时，此功能非常有用。

   请参 [阅通过Dynamic Media使CDN缓存 [!UICONTROL 失效]。](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/invalidate-cdn-cache-dynamic-media.html)

* **发布页面的开启和结束时间**

   当使用开启和 [关闭时间发布页面](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/sites/authoring/fundamentals/page-properties.html#basic)，请参阅页面属性的基本选项卡，您现 [在可以预配置自动复制](https://docs.adobe.com/help/en/experience-manager-cloud-service/operations/replication.html#on-and-off-times-trigger-configuration)。

* **[!UICONTROL 核心组件]**

   [!UICONTROL 核心组件] 2.11.0版引入了对AMP的支持，现在还提供创作文档 [、开发](https://docs.adobe.com/content/help/zh-Hans/experience-manager-core-components/using/introduction.html)[人员详细信息以及GitHub上的项目下载。](https://github.com/adobe/aem-core-wcm-components)

* **[!UICONTROL 表单]**

   * 更新 [的Gov和We.Finance参考网站提供](https://docs.adobe.com/content/help/zh-Hans/experience-manager-65/forms/getting-started/aem-forms-reference-collaterals/forms-gov-reference-site-user-demo.html) -漫游。 您可以使用这些参考站点来学习端对端工作流，为政府和金融行业创建和提供表单。
   * 提供 [了“另存为草稿SPI](https://docs.adobe.com/content/help/en/experience-manager-65/forms/interactive-communications/prepare-send-interactive-communication.html#sample-ccrDocumentInstance-spi) ”的示例实现。 您可以使用此示例为交互 [!UICONTROL 式通信代理UI实] 施“另 [!UICONTROL 存为草稿”功能]。 它有助于代理保存和检索草稿，从而加快交互通信的生成。
   * 提供了 [安装Visual C++可再发行组件时安装](https://docs.adobe.com/content/help/en/experience-manager-65/forms/install-aem-forms/osgi-installation/installing-configuring-aem-forms-osgi.html#automatic-installation-visual-studio-redistributables)[!UICONTROL 和验证Visual C+] +可再发行组件的说明。 这有助于减少与Visual C++可再发行组件安装和配置相关的错误。
   * [使用自适应表单文档配置Adobe Sign](https://docs.adobe.com/content/help/en/experience-manager-65/forms/adaptive-forms-advanced-authoring/adobe-sign-integration-adaptive-forms.html) ，经过彻底的测试和改进。 现在，它包含更多说明，帮助用自适应表单顺畅配置Adobe Sign。
   * ([!UICONTROL AEM Forms] （仅限JEE上）可 [用于为Rights Management服务创建邀请外部用户处理程序的文档](https://docs.adobe.com/content/help/en/experience-manager-65/forms/developer-reference/programming-aem-forms-jee/developing-spis-aem-forms/creating-invite-external-users-handler.html) 。

### **社区**

* **Experience League 上的最新 AEM 内容**

   这是 Adobe 制作的数字体验技术内容的官方来源。请在[此处](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/list-of-latest-adobe-experience-manager-content-on-experience/m-p/377452#M27156)查看完整列表。

### Experience Manager 的新课程和教程

过去一个月发布的新视频、教程和课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 8 月 31 日 | [配置XDP模板以利用AEM Forms和Adobe Sign集成](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/forms-and-sign/using-xdp-templates-with-adobe-sign.html) | 视频 | 将现有的XDP模板与 [!UICONTROL AEM Forms] 和Sign集成在一起。 |
| 2020 年 8 月 17 日 | [查看和配置转换的自适应表单](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/forms-and-sign/configure-converted-adaptive-form.html) | 视频 | 将自动表单服务创建的自适应表单配置为使用Adobe Sign集成。 更改面板标题并根据您的要求重新排列一些字段。 |
| 2020 年 8 月 25 日 | [为2个签名者配置自适应表单](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/forms-and-sign/configure-adaptive-form-for-two-signers.html) | 视频 | 使用自适应Forms接口配置多个签名者并指定顺序（顺序或并行）。 |
| 2020 年 8 月 17 日 | [配置对AEM的访问](https://video.tv.adobe.com/v/39230?captions=chi_hans) | 视频 | 了解用户如何使用AdobeIMS作为 [!UICONTROL Cloud Service进行身份验证]，以及如何使用AdobeIMS [!UICONTROL 用户、用户组]和产  品用户档案控制对AEM及其特性和功能的访问。 |
| 2020 年 8 月 17 日 | [配置对AEM遍历的访问](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/accessing/walk-through.html) | 视频 | 简化了在AdobeAdobe中配置Admin ConsoleIMS [!UICONTROL 用户]、用户 [!UICONTROL 组和产] 品 [!UICONTROL 用户档案的]步骤。 此外，了解如何在AEM作者中利用这些Adobe [!UICONTROL IMS抽象] ，定义和管理特定的基于组的权限。 |
| 2020 年 8 月 17 日 | [AEM用户、组和权限](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/accessing/aem-users-groups-and-permissions.html) | 视频 | Adobe Experience Manager以AdobeIMS用户、用户 [!UICONTROL 组和产品]用户档案为 [!UICONTROL 基础，提供对AEM的可自定义访问] 。 了解如何定义AEM组和权限，以及它们如何与AdobeIMS抽象协同工作，以提供对AEM的无缝、可自定义的访问。 |
| 2020 年 8 月 17 日 | [调试启动实施](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/experience-platform-launch/debug-launch-implementation.html) | 视频 | 介绍调试Launch实现的一些常用工具和技术。 了解如何使用浏览器的开发人员控制台和 [!UICONTROL Experience Platform调试器] 扩展来识别和排除Experience Platform Launch实施的关键方面的故障。 |
| 2020 年 8 月 17 日 | [创建启动Cloud Service配置](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/experience-platform-launch/create-launch-cloud-service.html) | 视频 | 了解如何创建新的Experience Platform LaunchCloud Services配置。 然后，可以将启动Cloud Service配置应用于现有站点，并可以在创作和发布环境中观察到启动库的加载情况。 |
| 2020 年 8 月 17 日 | [使用AdobeI/O将AEM与Launch连接](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/experience-platform-launch/connect-aem-launch-adobe-io.html) | 视频 | 了解如何使用AdobeI/O创建IMS配置，以使用Experience Platform LaunchAPI验证AEM。 在此集成到位后，AEM将能够通过Launch API进行通信以访问Launch属性。 |
| 2020 年 8 月 17 日 | [创建 Launch 资产](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/experience-platform-launch/create-launch-property.html) | 视频 | 了解如何使用设置其余集成所需的最低裸机配置创建启动属性。 用户将被介绍到Launch UI，并了解扩展、规则和发布工作流。 |
| 2020 年 8 月 17 日 | [集成Experience Platform Launch和AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/experience-platform-launch/overview.html) | 视频 | Experience Platform Launch是Adobe的下一代标签管理平台，是部署Adobe Analytics、Audience Manager和更多解决 [!DNL Target]方案的最佳方式。 获取Experience Platform Launch概述以及建议与Adobe Experience Manager集成。 |
| 2020 年 8 月 17 日 | [为管理员配置 AEM Assets](https://video.tv.adobe.com/v/37647?captions=chi_hans) | 视频 | 在此视频中，管理员可以了解有关配置 [!UICONTROL AEM Assets]。 |
| 2020 年 8 月 12 日 | [以AEM作为Cloud ServiceSDK的本地开发](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/commerce/develop.html) | 视频 | 了解如何将AEM Commerce和AEM的本地 [!UICONTROL 开发环境][!UICONTROL 设置为Cloud Service] SDK。 |
| 2020 年 8 月 17 日 | [使用表单数据模型预填自适应表单](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.1.forms) | 课程 | 您可以使用现有数据预填自适应表单的字段。 在本课程中，了解如何使用表单数据模型的request属性预填字段。 |
| 2020 年 8 月 17 日 | [AdobeIMS产品用户档案](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/accessing/adobe-ims-product-profiles.html) | 视频 | AdobeIMS产品用户档案授权用户登录AEM作者服务，并根据用户添加到的产品用户档案提供访问基准。 |
| 2020 年 8 月 17 日 | [AdobeIMS用户组](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/accessing/adobe-ims-user-groups.html) | 视频 | AdobeIMS用户组建立向AEM公开的用户的逻辑集，利用这些用户来定义对AEM用户的微调权限。 |
| 2020 年 8 月 17 日 | [AdobeIMS用户](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/accessing/adobe-ims-users.html) | 视频 | 了解IMS用户是什么Adobe，如何在Admin Console中访问和管理他们，以及如何使用他们作为Cloud Service登录AEM。 |
| 2020 年 8 月 17 日 | [面向开发人员的HTML5Forms入门](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.forms) | 课程 | HTML5表单以HTML5格式呈现XFA表单模板的优惠。 此功能支持在不支持基于XFA的PDF的移动设备和桌面浏览器上呈现表单。 |

### Experience Manager 发行信息

所有的 Experience Manager 发行说明均保留在以下页面：

* [AEM 云服务发行信息](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-service/release-notes/home.html)
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

* 20.2.2 版本 - [了解更多](https://docs.adobe.com/content/help/zh-Hans/campaign-classic/using/release-notes/latest-release.html#release-20-2-2-build-9180)

### Campaign 的新课程和教程

过去一个月发布的新视频、教程或课程。

| 发布日期 | 名称 | 解决方案 | 描述 |
| ----------- | ----------- | ---------- | ---------- |
| 2020 年 8 月 10 日 | [通过组合目标结果来优化查询](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/automating-with-workflows/refining-targets-by-combining-query-results.html) | Campaign Classic | 了解如何通过使用交叉点或目标活动将查询结果组合到工作流中来优化合并。 |
| 2020 年 8 月 10 日 | [使用更新列表活动创建具有工作流的列表](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/automating-with-workflows/using-the-update-list-activity.html) | Campaign Classic | 了解Adobe Campaign Classic列表的概念，了解如何在工作流中使用更新列表活动创建列表。 |
| 2020 年 8 月 20 日 | [通过排除目标结果优化查询](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/automating-with-workflows/refining-targets-by-excluding-query-results.html) | Campaign Classic | 了解如何通过将标准排除应用于工作流来优化目标。 您还将学习如何创建预定义过滤器以及如何难以拍摄您的工作流。 |
| 2020 年 8 月 25 日 | [创建直邮投放](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/direct-mail/creating-direct-mail-deliveries.html) | Campaign Classic | 了解直接邮件在Adobe Campaign中的工作方式，并了解如何创建、格式化和执行直接邮件投放。 |  | 2020 年 8 月 25 日 | [创建直邮投放](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/direct-mail/creating-direct-mail-deliveries.html) | Campaign Classic | 了解直接邮件在Adobe Campaign中的工作方式，并了解如何创建、格式化和执行直接邮件投放。 |

### 帮助资源

* Adobe Campaign Standard：[帮助中心](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/campaign-standard-home.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/release-notes/release-notes.html) - [操作方法视频](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [发行计划](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/release-notes/release-planning.html) - [最新文档更新](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic：[帮助中心](https://docs.adobe.com/content/help/zh-Hans/campaign-classic/using/campaign-classic-home.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/campaign-classic/using/release-notes/latest-release.html) - [操作方法视频](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)- [最新文档更新](https://docs.adobe.com/content/help/zh-Hans/campaign-classic/using/documentation-updates.html)
* Adobe Campaign 控制面板：[文档](https://docs.adobe.com/content/help/zh-Hans/control-panel/using/control-panel-home.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/control-panel/using/release-notes.html) - 有关 [Campaign Standard](https://docs.adobe.com/content/help/zh-Hans/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html)/[Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html) 的操作方法视频

## ![图标](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Adobe Advertising Cloud 的发行说明。

* [Advertising Cloud DSP 中的新增功能](#adcloud-dsp)
* [Advertising Cloud Search 中的新增功能](#adcloud-search)

### [!UICONTROL Advertising Cloud DSP] 中的新增功能 {#adcloud-dsp}

| 功能 | 描述 |
| -----------| ---------- |
| 扩展了交互式前置式广告以包含 VAST 库存 | 现在，每个交互式前置式投放和广告都可同时支持 VPAID 和 VAST 库存。**注意：** 如果您的主要KPI是视图能力，则继续创建单独的VPAID和VAST投放和广告，因为可见印象不适用于VAST广告。 |

### [!UICONTROL Advertising Cloud Search] 中的新增功能 {#adcloud-search}

**8 月 8 日**&#x200B;发布

| 功能 | 描述 |
| ----------- | ---------- |
| [!UICONTROL 组合] | 组合级别位置限制在组合设置中不再可用。已删除之前创建的任何位置限制。 |
| [!UICONTROL 约束] | 不再支持基于位置的约束和约束条件：<br/> <ul><li>[!UICONTROL 不再提供] “最 [!UICONTROL 小位置”和“最大位置] ”约束，并已从之前创建的所有“出价和位置”约束和“印象共享”约 [!UICONTROL 束中删除了“最小位置] ”和“最大 [!UICONTROL 位置] ”约束。</li><li>Existing [!UICONTROL Bid &amp; Position] constraints that included position constraints but no bid constraints were paused. 仍可在 UI 和报表中使用。</li><li>[!UICONTROL 竞价和位置约束已重命名为竞价约束。]</li><li>All position-based conditions (using [!UICONTROL Average Position], [!UICONTROL Weighted Average Position], or [!UICONTROL Last Known Pos] metrics) in any type of constraint were removed.</li></ul> <br/> **注意：**&#x200B;只要可以从搜索引擎获得位置数据，就能继续填充位置数据。Microsoft Ads 将于 2020 年 9 月停用。 |
| [!UICONTROL 促销活动] | （Google Ads 促销活动）Advertising Coud Search 当前在响应式搜索广告 (RSA) 中支持广告定制器。以前，除 RSA 之外，所有广告类型都支持广告定制器。 |

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
| ------ | --------- |
| [!DNL Bizible] | <ul><li>新的基于帐户的分段</li><li>保存特定于功能板的过滤器</li><li>将 Bizible 功能板导出为 PDF</li></ul> |
| Sales Connect | 撰写窗口和命令中心更新/增强功能 |

### 弃用

* **Asset API“_method”参数：** 2020 年 9 月之后，Asset API 端点将不再接受 `_method` 在 POST 正文中传递查询参数以绕过 URI 长度限制。
* **弃用 Internet Explorer 支持：**&#x200B;从 2020 年 7 月 31 日发行的 7 月版本开始，Internet Explorer 将不再支持 Marketo Engage 用户界面。

有关累积和历史发行说明，请参阅 [Marketo 发行说明](https://docs.marketo.com/x/CgA6Ag)。
