---
title: Adobe Experience Cloud 发行说明
description: Adobe Experience Cloud 发行说明
doc-type: release notes
last-update: January 2021
author: mfrei
translation-type: tm+mt
source-git-commit: 3d0946fe6fc0bf74ec45a19931c106afb8a8208d
workflow-type: tm+mt
source-wordcount: '6185'
ht-degree: 43%

---


# Adobe Experience Cloud 发行说明 - 2021 年 1 月

![横幅](/assets/experience-cloud-banner-3.png)

此页面介绍了 [!DNL Adobe Experience Cloud] 中的新增功能、修复和重要声明。此外，还重点提供了可帮助您充分利用 Experience Cloud 的新文档、培训课程和视频教程。

>[!NOTE]
>
>订阅每月[Adobe优先级产品更新](https://www.adobe.com/subscription/priority-product-update.html)，以接收有关此页面更新的电子邮件通知。 本页面在当月内进行维护，因此请定期回访，了解Adobe企业产品和Experience League文档更新。

最新更新：**2020年1月11日**

* [Adobe系统状态](#status) （未更新）
* [Experience Cloud 服务和管理](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Analytics](#analytics) 和 [Customer Journey Analytics](#cust-journey) (发行日期：**2021 年 1 月 14 日**)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [[!DNL Target]](#target)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo) (已更新： **2021年1月11日**)
* [Document Cloud](#doc-cloud)

需要帮助？请访问 [Adobe Experience League](https://experienceleague.adobe.com/#home)，查找产品和技术文档、Adobe 策划课程、视频教程、快速解答、社区洞察以及由讲师指导的培训。内容已从`docs.adobe.com`移到此位置。 请相应地更新书签。

## ![图标](/assets/adobe.png) Adobe 系统状态 {#status}

[!UICONTROL Adobe 系统状态]提供关于 Adobe 云产品与服务中断和维护事件的详细信息、状态更新以及电子邮件通知。请访问 [status.adobe.com](https://status.adobe.com/) 查看。

本月未进行更新。

请参阅 [Adobe 系统状态 - 2020 年 5 月 21 日](https://docs.adobe.com/content/help/zh-Hans/release-notes/experience-cloud/previous/2020/05212020.html#status)，以了解最新版本信息。

## ![图标](/assets/ec_appicon_24.png) Experience Cloud 服务和管理 {#ecloud}

[Experience Cloud服务](https://docs.adobe.com/content/help/zh-Hans/core-services/interface/experience-cloud.html) 和管理文档包括受众属性、库( Peopleservice)、激活、用户和产品管理以及Experience Cloudcookie。

本月未进行更新。

请参阅 [Experience Cloud 服务的发行说明汇总](https://docs.adobe.com/content/help/zh-Hans/core-services/interface/release-notes/release-notes.html)，以了解最新发行信息。

## ![图标](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

包括有关Experience Platform和Experience Platform Launch的发布更新信息。

| 功能 | 发行日期 | 描述 |
| ------- | ------| ------- |
| 增强的产品内支持交互以实现Experience Platform | 2021 年 1 月 15 日 | 您现在无需离开Experience Platform界面即可提出问题或报告问题。 导航到&#x200B;**[!UICONTROL 帮助]** > **[!UICONTROL 支持]** > **[!UICONTROL 创建支持票证]**，然后输入查询并直接将案例提交给客户支持。 您将收到一封带有案例ID的电子邮件通知，客户支持团队将通过票证联系您，以满足您的需求。 |

最近更新日期：**2020 年 12 月 9 日**

请参阅[Experience Platform发行说明](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)，了解适用于以下对象的最新更新：

* [!UICONTROL 数据流]
* [!UICONTROL 数据科学工作区]
* [!UICONTROL 源]

### Experience Platform Launch

有关 Platform Launch 的更多信息，请参阅 [Experience Platform Launch 发行说明](https://experienceleague.adobe.com/docs/launch/using/release-notes/current.html)。

### Adobe Mobile

iOS版本4.21.0

常规- SDK现在使用[!DNL XCFrameworks]进行分发，以支持采用新Apple M1架构的硬件，同时保持对现有Intel架构的支持。

* 重要：升级到AdobeMobile [!DNL XCFrameworks]需要Xcode 12.0或更高版本。
* 重要：如果使用[!DNL Cocoapods]，则升级到AdobeMobile [!DNL XCFrameworks]需要[!DNL Cocoapods] 1.10.0或更高版本。

### Experience Platform 和服务教程及课程

发布的关于 Experience Platform 和服务的新视频、教程或课程。

更新：**2021年1月6日**

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 12 月 23 日 | [合并模式概述](https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/union-schemas-overview.html) | 视频 | 了解Adobe Experience Platform实时客户用户档案所使用的合并模式。 |
| 2020 年 12 月 22 日 | [创建多实体区段](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/create-multi-entity-segments.html) | 视频 | 了解如何在Adobe Experience Platform的细分构建器中构建多实体细分。 |
| 2020 年 12 月 21 日 | [创建优惠活动](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-offer-activities.html) | 视频 | 了解如何在[!UICONTROL Offer Decisioning]中创建优惠活动。 优惠活动将您的定位和收藏合并为一个实体，以便能够决定向客户提供最相关的优惠。 |
| 2020 年 12 月 21 日 | [创建集合](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-collections.html) | 视频 | 了解如何在[!UICONTROL Offer Decisioning]中创建集合。 集合用于管理逻辑组中的优惠，并且是构建Offer Decisioning活动所必需的。 |
| 2020 年 12 月 21 日 | [通过决策API提供优惠](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/deliver-offers-with-the-decisions-api.html) | 视频 | 了解如何使用决策API提供[!UICONTROL Offer Decisioning]优惠。 |
| 2020 年 12 月 15 日 | [创建个性化优惠](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-personalized-offers.html) | 视频 | 了解如何在[!UICONTROL Offer Decisioning]中创建个性化优惠。 |
| 2020 年 12 月 15 日 | [创建后备优惠](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-fallback-offers.html) | 视频 | 了解如何在[!UICONTROL Offer Decisioning]中创建回退优惠。 |
| 2020年12月14日（更新） | [了解实时客户用户档案](https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/understanding-the-real-time-customer-profile.html) | 视频 | 此视频介绍Adobe Experience Platform如何组装和更新实时客户用户档案，以及如何访问和使用这些用户档案。 |
| 2020 年 12 月 10 日 | [创建标记](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-tags.html) | 视频 | 了解如何在[!UICONTROL Offer Decisioning]中创建标记。 标记是优惠的可选构建块组件。 它们可用于组织优惠并将其分组到动态集合中。 |
| 2020 年 12 月 9 日 | [在Offer Decisioning制定规则](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-rules.html) | 视频 | 了解如何在[!UICONTROL Offer Decisioning]中创建规则。 规则是使用平台[!UICONTROL 实时客户用户档案]中的事件和属性构建的，并形成优惠的资格限制。 |
| 2020 年 12 月 9 日 | [创建位置](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-placements.html) | 视频 | 了解如何在Offer Decisioning创建版面。 位置是内容类型和渠道的组合，如电子邮件中的图像或网站上的HTML代码。 |
| 2020年10月29日（更新） | [Offer Decisioning](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/demo-of-offer-decisioning.html?lang=zh-Hans) | 视频 | 此视频介绍各大品牌如何使用 Adobe 新的 [!UICONTROL Offer Decisioning] 服务来定义和管理优惠、利用实时客户数据，以及提供与客户预期相符的体验。 |
| 2020年10月26日（更新） | [Offer Decisioning 简介](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/introduction-to-offer-decisioning.html) | 视频 | 此视频概述了 [!UICONTROL Offer Decisioning]，它是一项基于 Adobe Experience Platform 构建的应用程序服务。此视频涵盖 [!UICONTROL Offer Decisioning] 解决的业务挑战，以及它的主要功能、基本架构和主要用例。 |
| 2020年10月26日（更新） | [使用Salesforce CRM源连接器收录数据](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/ingest-data-from-salesforce-crm.html) | 视频 | Salesforce CRM源连接器使您能够以无缝且可伸缩的方式轻松地将数据从Salesforce CRM批量引入Adobe Experience Platform的实时客户用户档案和体验数据湖。 |
| 2020年10月13日（更新） | [使用Salesforce CRM源连接器收录数据](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/ingest-data-from-adobe-analytics.html) | 视频 | Salesforce CRM源连接器使您能够以无缝且可伸缩的方式轻松地将数据从Salesforce CRM批量引入Adobe Experience Platform的实时客户用户档案和体验数据湖。 |
| 2020年10月23日（更新） | [将数据引入实时客户用户档案](https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/bring-data-into-the-real-time-customer-profile.html) | 视频 | 实时客户用户档案在客户旅程的每个阶段支持大规模的跨渠道个性化。 |
| 2020年10月13日（更新） | [配置 Attribution AI](https://experienceleague.adobe.com/docs/platform-learn/tutorials/intelligent-services/configure-attribution-ai.html) | 视频 | 了解如何创建 Attribution AI 实例，以便分析营销渠道和营销活动带来的影响。 |
| 2020年10月13日（更新） | [配置 Customer AI](https://experienceleague.adobe.com/docs/platform-learn/tutorials/intelligent-services/configure-customer-ai.html) | 视频 | 了解如何创建 Customer AI 实例，以便预测客户的行为。 |

## ![图标](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

使用Adobe Experience Platform实时智能预测每位客户的需求，跨体验渠道大规模地编排客户旅程。

### 新的产品版本

* 11月版本- [阅读更多](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html#november-release)
* 10月版本- [阅读更多](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html#october-release)

### Journey Orchestration 的其他资源

[文档](https://docs.adobe.com/content/help/zh-Hans/journeys/using/journey-orchestration-home.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/journeys/using/release-notes/release-notes.html) - [操作方法视频](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

## ![图标](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

发行日期：**2021 年 1 月 14 日**

* [Adobe Analytics 中的新增功能](#aa-features)
* [Customer Journey Analytics 的新增功能](#cust-journey)
* [Adobe Analytics 中的修复](#aa-fixes)
* [Analytics 管理员的重要注意事项](#aa-notices)
* [AppMeasurement](#appm)

### Adobe Analytics 中的新增功能 {#aa-features}

| 功能 | [正式发布](https://docs.adobe.com/content/help/zh-Hans/analytics/landing/an-releases.html) - 目标日期 | 描述 |
| ----------- | ---------- | ------- |
| Analysis Workspace -组件选择 | 2021 年 2 月 4 日 | 在[!UICONTROL Quick Insights]中找到的下拉／下拉区域组件已添加到[!UICONTROL Workspace]中的所有下拉区域。 此增强功能允许您从兼容组件的下拉列表中进行选择，或继续将空间用作拖放区域。 |
| Analysis Workspace-图像URL | 2021 年 1 月 14 日 | 可以通过引用公共图像URL向[!UICONTROL Workspace]项目添加图像。 |

### Customer Journey Analytics 的新增功能 {#cust-journey}

| 功能 | [正式发布](https://docs.adobe.com/content/help/en/analytics/landing/an-releases.html) - 目标日期 | 描述 |
| ----------- | ---------- | ----- |
| [!UICONTROL 设备]和[!UICONTROL 地理]维度 | 2020 年 10 月 30 日 | 现在，这些维在Adobe Analytics[!UICONTROL 源连接器]中作为[全局查找](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-usecases/global-lookups.html?lang=en#use-global-lookups-with-adobe-data-connector-datasets)支持项目的一部分默认可用。 在用户强烈要求下添加的这些维度增加了 [Adobe Analytics 与 CJA 之间的对等性](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-overview/cja-aa.html?lang=en#cja-overview)。 |
| 旅程IQ:[!UICONTROL 跨渠道分析] | 2021 年 1 月 11 日 | 旅程IQ:[!UICONTROL 跨渠道分析]使您能够将Experience Platform数据湖中的Adobe Analytics（或其他）事件数据集从一个ID命名空间重新键入到另一个ID。 通常，这意味着为事件数据集从基于 Cookie 的 ID 重新生成一个基于人员的 ID。这样，重新键入的数据集可以与CJA连接中的其他基于人的数据相结合，从而在Analysis Workspace实现跨设备和跨渠道分析。 [了解更多](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-connections/cca/overview.html?lang=zh-Hans#cja-connections) |
| Analysis Workspace-组件选择 | 2021 年 2 月 4 日 | 在[!UICONTROL Quick Insights]中找到的下拉／下拉区域组件已添加到[!UICONTROL Workspace]中的所有下拉区域。 此增强功能允许您从兼容组件的下拉列表中进行选择，或继续将空间用作拖放区域。 |
| Analysis Workspace-图像URL | 2021 年 1 月 14 日 | 您可以通过引用公共图像URL将图像添加到Workspace项目。 |

### Adobe Analytics 中的修复 {#aa-fixes}

* 修复了Workspace中下载的CSV报表的格式设置、下载和发送问题。 (AN-224844
AN-240295)
* 修复了即使Analytics报表包包含数据，移动属性数据也不会显示在Livestream中的问题。 (AN-241169)
* 修复了实时报告无法显示任何数据的问题。 (AN-242477)
* 在报告和分析中，修复了在使用&#x200B;_包含_&#x200B;过滤器时不显示数据的问题。 (AN-237354)
* 修复了导致从Adobe Analytics删除的段继续用于活动数据连接器的问题。 (AN-236713)
* 修复了计划报告卡在报告队列中的问题。 (AN-242599、AN-242554、AN-242900、AN-243329)
* 修复了报告和分析中共享目标报告的问题。 (AN-234638)
* 修复了条形图在工作区中不显示数据的问题。 (AN-232127)
* 修复了客户无法登录Adobe Analytics的问题。 (AN-241882 AN-238802)
* 已更新移动设备报告以包含Samsung Galaxy Z Fold2 5G。 (AN-238246)
* 修复了Workspace中计划报告中出错的问题。 （AN-236707 和 AN-243449）
* 修复了FTP无法拾取数据源文件的问题。 (AN-240347)
* 修复了在尝试访问[!UICONTROL Advertising Analytics]时导致错误的问题。 (AN-241478)
* 修复了文件未从分类FTP中拾取的问题。 (AN-242490)
* 修复了Workspace中的UI渲染错误。 (AN-243123)
* 修复了无法从SFTP服务器接收文件的Data warehouse问题。 (AN-244679)
* 修复了在]Admin[!UICONTROL  > ]Logs[!UICONTROL  > ]使用和访问日志[!UICONTROL 下发现的阻止下载报告[!UICONTROL 链接工作的问题。 ](AN-238058)

#### 其他 Adobe Analytics 修复

AN-204659;AN-221726;AN-230949;AN-231984;AN-232835; AN-233989;AN-235593;AN-235989;AN-236823;AN-236840;AN-237168;AN-237262;AN-237265;AN-237633;AN-237740;AN-238523;AN-238870;AN-238941;AN-239414;AN-239649;AN-239652;AN-239676;AN-239703;AN-240184;AN-240219;AN-240412;AN-240530;AN-240609;AN-240625;AN-240664;AN-240682;AN-240715;AN-241052;AN-241077;AN-241112;AN-241149;AN-241578;AN-241714;AN-242157;AN-242485;AN-242535;AN-242573;AN-242608;AN-242728;AN-242818;AN-242820;AN-242963;AN-242978;AN-243013;AN-243054;AN-243105;AN-243172;AN-243181;AN-243255;AN-243326;AN-243418;AN-243449;AN-243463;AN-243507;AN-243518;AN-243519;AN-243598;AN-243805;AN-243814;AN-243910;AN-243929;AN-244009;AN-244012;AN-244105;AN-244121;AN-244137;AN-244188;AN-244225;AN-244305;AN-244357;AN-244363;AN-244419;AN-244607;AN-244695;AN-244713;AN-244828;AN-244843;AN-244876;AN-244877;AN-245388;AN-245470

### [!DNL Analytics] 管理员的重要注意事项 {#aa-notices}

| 注意事项 | 添加或更新日期 | 描述 |
| ----------- | ---------- | ---------- |
| 三种Analytics API服务的生命周期结束 | 2021 年 1 月 6 日 | 2021年4月30日，以下Analytics Legacy API服务将达到其终止日期并将关闭。 使用这些服务构建的任何当前集成将在该天停止工作。<ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>旧版 OAuth 身份验证（OAuth 和 JWT）</li></ul>我们提供了[旧版API EOL常见问题解答](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)，以帮助回答您的问题并提供有关如何继续的指导。 使用这些服务的API集成可以迁移到[1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email)和／或[2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。 旧版 OAuth 帐户可迁移到 [Adobe IO](https://console.adobe.io/home?mv=email#) Analytics 集成帐户，该帐户可用于访问 1.4 Analytics API 和 2.0 Analytics API。 |
| 将 HSTS 头添加到所有传入的 HTTPS 请求 | 2020 年 9 月 29 日 | 2020 年 9 月 29 日，我们开始向所有使用 HTTPS 的传入请求添加 HSTS 头。这会指示浏览器/客户端在以后使用 HTTPS 发出所有请求，这被视为最佳安全实践。目前，我们不会对使用 HTTP 的传入请求强制执行此操作。 |
| 更改为[!UICONTROL Experience CloudID服务] cookie设置 | 2020 年 9 月 22 日 | Chrome 版本 80 隐私设置的更新，影响了 Adobe Analytics 跟踪某些查看 Google AMP 页面的用户的能力。具体而言，这项更新阻止跨域跟踪那些查看 Google 托管的 AMP 页面的用户。结果可能会导致独特访客数量激增。修复方法：用户可通过更改其 ECID Cookie 的设置来解决此问题。<br>目前，Analytics 在设置 Experience Cloud ID 服务 (ECID) Cookie 时，使用的是 Chrome 版本 80 之前允许跨域跟踪的设置`SameSite = Lax`。现在情况已发生了变化。此项更改允许用户将 ECID Cookie 的 SameSite 设置更新为 `None`。<br>请注意，它允许在更多的情况下共享 Analytics Cookie，但 Analytics Cookie 不包含敏感信息。此外，在选择这项设置时，必须将 Cookie 设置为 `Secure`，以便数据只能通过 HTTPS 连接进行传递。如果您要进行这项更改，请让受支持的用户通过客户关怀部门开具相关票证。 |
| 从 `omniture.com` 域迁移至 `adobe.com` 域 | 2020 年 8 月 21 日 | 2020 年 8 月 13 日，Adobe Analytics 将其前端架构从 `omniture.com|http://omniture.com/` 域迁移至 `adobe.com|http://adobe.com/` 域。这项变更可以缓解自 2020 年 5 月 28 日首次统一产品域更改以来引发的第三方 Cookie 问题。作为本次更新的结果，浏览器可能会提示用户信任这个新的 `.adobe.com|http://an.adobe.com/` 域或 `experience.adobe.com|http://experience.adobe.com/` 域。 |
| 关于 Ad Hoc Analysis 与 Java 8 兼容性的最新信息 | 2020 年 8 月 21 日 | Ad Hoc Analysis 目前与 Java 8 版本 1.8.0_261+ 不兼容。为了确保能够在这个工具[生命周期终止日期](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)之前持续访问该工具，我们建议您安装版本低于 1.8.0_261 的 Java 8。 |
| Adobe Data Connectors 生命周期终止 | 2020 年 7 月 13 日 | Adobe [!UICONTROL Data Connectors] 由传统技术提供支持，而这些技术不再可行或不再受支持。我们在 [Adobe Exchange 合作伙伴项目](https://partners.adobe.com/exchangeprogram/experiencecloud)中采用了一个新标准，任何希望继续提供和支持的集成应采用此标准。正式的生命周期终止日期仍有待确定，但我们预计将会在未来 12-18 个月（2021 年中至 2021 年底）后终止。[了解更多...](https://docs.adobe.com/content/help/zh-Hans/analytics/import/dataconnectors/data-connectors-eol.html) |
| Ad Hoc Analysis 生命周期终止 | 2018 年 8 月 6 日 | Adobe 宣布计划于 2021 年 3 月 1 日终止 Ad Hoc Analysis 生命周期。有关更多信息，请参阅[探索工作区](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)。 |

### AppMeasurement {#appm}

有关 AppMeasurement 版本的最新更新，请参阅[适用于 JavaScript 的 AppMeasurement 发行说明](https://docs.adobe.com/content/help/zh-Hans/analytics/implementation/appmeasurement-updates.html)。

### Analytics 帮助资源

* [Adobe Analytics产品文档和Tutorials](https://experienceleague.corp.adobe.com/docs/analytics.html)

## ![图标](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Audience Manager 中的新增功能、修复、文档和教程。

<!-- ### Fixes and Improvements {#aam-fixes-and-improvements}

* Fixed an issue in the Predictive Audience feature where some users were unable to delete any of their models, even if no segments were mapped to the models. (AAM-55881)
* Fixed an issue where some users were unable to delete traits or segments which had been used as baseline for deleted predictive audience models. (AAM-56476)
* We continued making accessibility improvements across the interface. (AAM-53215) -->

### Audience Manager 的课程及教程{#tutorials-aam}

发布的关于 Audience Manager 的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 12 月 15 日 | [使用基于角色的访问控制设置权限](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/setup-and-admin/user-management/setting-permissions-with-role-based-access-control.html?lang=en#setup-and-admin) | 视频 | 了解如何在组级别管理权限，控制谁有权查看和使用资产，包括特征、区段、目标和模型。 设置权限组，并向其添加用户。 |

## ![图标](/assets/aem.png) Adobe Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新增功能、修复和更新。Adobe 建议那些采用内部部署的客户部署最新的修补程序，以便确保获得更高的稳定性、安全性和性能。

>[!NOTE]
>
>Adobe 建议您经常访问 [Experience Manager 版本更新和路线图](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html)，以保证及时了解最新发行信息。

### 产品更新

* **AEM 6.5.7.0**
AEM 6.5,Service Pack 7（2020年11月26日发布的6.5.7.0）是一项重要更新，包含新功能、关键客户增强、改进的性能、稳定性和安全性，自AEM 6.5正式发布以来已发布。
   * [发行说明](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=en#service-pack)
   * [AEM Forms 发布的交付内容](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html#forms-updates)

* **AEM 6.4.8.3**
AEM 6.4,Service Pack 8,Cumulative Fix Pack 3（2020年11月26日发布的6.4.8.3）是重要更新，包含自2020年3月发布AEM 6.4、Service Pack 8(6.4.8.0)以来的几个内部和客户修复。
   * [发行说明](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=en)
   * [AEM Forms 发布的交付内容](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html#forms-updates)

### 产品版本

* **AEM as a Cloud Service**

   AEM as a Cloud Service 有哪些新增功能？

   * **Adobe Experience Manager Sites as a Cloud Service**
      * [内容片段HTTP API](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/admin/assets-api-content-fragments.html):添加使用HTTP API添加／更新和删 [!UICONTROL 除内] 容片段变量的功能。
   * **Adobe Experience Manager Assets as a Cloud Service**

      * 与Adobe InDesign Server的集成现在可作为[!UICONTROL Cloud Service]进行Experience Manager。 它提供使用Adobe InDesign Server脚本处理Adobe InDesign文件的自动化功能，并允许用户使用资产模板用户界面创建小册子或广告。 只有Adobe Managed Services托管的InDesign Server才支持作为[!UICONTROL Cloud Service]进行Experience Manager。
      * Experience Manager经过增强，可在使用[!UICONTROL 已连接资产]功能在远程Experience Manager站点部署中使用资产时跟踪和显示资产引用。 资产的[!UICONTROL 属性]页面中新增的[!UICONTROL 引用]选项卡现在会列表资产的本地和远程引用。 引用允许DAM用户跟踪[!UICONTROL 站点]页面和[!UICONTROL 资产]中复合资产中的资产使用情况。
请参阅[配置和使用连接的资产](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/admin/use-assets-across-connected-assets-instances.html)。
      * [!UICONTROL 现] 在可通过基于站点的核  心组件访问动态媒体。作者可以在创建网页时快速配置组件以使用[!UICONTROL 图像预设]、[!UICONTROL 智能裁剪]和[!UICONTROL 图像修饰符]。
请参阅[核心组件2.13.0版本](https://github.com/adobe/aem-core-wcm-components/releases/tag/core.wcm.components.reactor-2.13.0)。
      * Experience Manager桌面应用程序允许用户通过从Windows资源管理器或桌面应用程序界面上的Mac Finder拖动文件来上传文件和文件夹。
请参阅[使用桌面应用程序](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/using.html?lang=en#upload-and-add-new-assets-to-aem)添加资产。
   * **Adobe Experience Manager Commerce as a Cloud Service**

      * 已发布CIF Venia参考站点- 2020.12.01，其中包括最新的CIF核心组件版本1.6.0。
请参阅[CIF Venia Reference Site](https://github.com/adobe/aem-cif-guides-venia/releases/tag/venia-2020.12.01)。
      * 已发布CIF核心组件v1.6.0。
请参阅[CIF核心组件](https://github.com/adobe/aem-core-cif-components/releases/tag/core-cif-components-reactor-1.6.0)。
   * **Cloud Manager**

      * 对[SSL证书](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/onboarding/getting-access/manage-ssl-certificates/introduction.html)和[自定义域名](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/onboarding/getting-access/custom-domain-names/introduction.html)进行自助管理。
      * [IP允许列表](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/onboarding/getting-access/ip-allow-lists/introduction.html)的自助服务管理。
      * 更新的环境详细信息页现在允许用户管理[!UICONTROL 自定义域名]和[!UICONTROL IP允许列表]的环境。
   * **代码重构工具**

      * 已发布新版AIO-CLI插件。 此插件的最新版本包括针对AEM Dispatcher Converter和Repository Modernizer的错误修复，还支持新的实用程序——索引转换器。
请参阅[统一体验](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/moving/refactoring-tools/unified-experience.html#benefits)以进一步了解此插件。
      * Index Converter是一个实用程序，可用于将客户的自定义OAK索引定义转换为AEM作为Cloud Service兼容的OAK索引定义。
请参阅[索引转换器](https://github.com/adobe/aem-cloud-service-source-migration/tree/master/packages/index-converter)。
      * 添加到[存储库Modernizer](https://github.com/adobe/aem-cloud-service-source-migration/tree/master/packages/repository-modernizer)的新功能，该功能创建单独的包`ui.config`以包含所有OSGi配置。





请参阅 [AEM as a Cloud Service 发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)。

### 自助服务

**[!DNL Experience Manager as a Cloud Service]**

以上链接提供新增功能文档更新。 其他文档更新包括：

* **最佳实践分析器**

   * [!UICONTROL Cloud Readiness Analyzer] 现在是 [!UICONTROL 最佳实践分析] 器(BPA)。BPA为您当前的AEM实施提供最佳实践评估，并帮助评估从现有AEM实例迁移到AEM(a [!UICONTROL Cloud Service])的准备情况。

* **基础**

   * 工作流-增加了基于[!UICONTROL 工作流标题]、[!UICONTROL 工作流模型]、[!UICONTROL 状态]、[!UICONTROL 启动器]、[!UICONTROL 有效负荷路径]和[!UICONTROL 开始日期&lt;a1的工作流实例搜索支持1/>。
]请参阅[搜索工作流实例](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/administering/workflows-administering.html#administering)。
   * 发布层用户用户档案同步——可以在发布层上保留用户数据，包括属性和组成员关系。
请参阅[注册、登录和用户用户档案文档](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/authoring/personalization/user-and-group-sync-for-publish-tier.html#authoring)。

### [!DNL Experience Manager] 表单

6.5.7.0版本包含以下功能的文档现已发布：

* 安装Service Pack后，您体验到更快的服务器端验证和PDF到自适应表单转换。

* 您现在可以撤消所有调整大小的更改，并在自适应表单的布局模式下将默认布局应用于每个组件。 请参阅[使用布局模式调整组件大小](https://experienceleague.adobe.com/docs/experience-manager-65/forms/adaptive-forms-basic-authoring/resize-using-layout-mode.html?lang=en)。

* [!DNL Experience Manager Forms] 与RESTful web服务作为数据源集成时，表单数据模型现在包括用于连接管理的HTTP客户端配置。请参阅[配置数据源](https://experienceleague.adobe.com/docs/experience-manager-65/forms/form-data-model/configure-data-sources.html?lang=en#configure-relational-database)。

### 社区

**2021年1月最新的Adobe Experience ManagerExperience League内** 容——请 [在此处查看功能视频、文章、教程和课程的全面列表](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/list-of-latest-adobe-experience-manager-content-on-experience/td-p/392549)。

### Experience Manager 的新课程和教程

更新：**2021年1月10日**

过去一个月发布的新视频、教程及课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 12 月 7 日 | [使用片段引用进行高级数据建模](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/fragment-references.html) | 文章 | 开始使用Adobe Experience Manager(AEM)和GraphQL。 了解如何使用[!UICONTROL 片段引用]功能进行高级数据建模并创建两个不同的[!UICONTROL 内容片段]之间的关系。 了解如何修改GraphQL查询以包含引用模型中的字段。 |
| 2020 年 12 月 7 日 | [查询AEM从外部应用程序使用GraphQL](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/explore-graphql-api.html) | 文章 | 开始使用Adobe Experience Manager(AEM)和GraphQL。 浏览AEM GraphQL API示例WKND GraphQL React应用程序。 了解此外部应用程序如何通过调用GraphQL来提升体验。 了解如何执行基本错误处理。 |
| 2020 年 12 月 7 日 | [浏览GraphQL API](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/explore-graphql-api.html) | 文章 | 开始使用Adobe Experience Manager(AEM)和GraphQL。 使用内置的GrapiQL IDE浏览AEM GraphQL API。 了解AEM如何根据内容片段模型自动生成GraphQL模式。 尝试使用GraphQL语法构建基本查询。 |
| 2020 年 12 月 | [创作内容片段](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/author-content-fragments.html) | 文章 | 开始使用Adobe Experience Manager(AEM)和GraphQL。 根据[!UICONTROL 内容片段模型]创建和编辑新的内容片段。 了解如何创建[!UICONTROL 内容片段]的变体。 |
| 2020 年 12 月 7 日 | [定义内容片段模型](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/content-fragment-models.html) | 文章 | 开始使用Adobe Experience Manager(AEM)和GraphQL。 了解如何在AEM中使用内容片段模型建立内容模型和构建模式。 检查现有模型并创建新模型。 了解可用于定义模式的不同数据类型。 |
| 2020 年 12 月 9 日 | [API兼容性](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/admin/developer-reference-material-apis.html) | 文章 | 创建一篇简单的文章，其中明确说明哪些AEM API(npm、Java、HTTP)可用于各种[!UICONTROL Assets]操作。 |
| 2020 年 12 月 2 日 | [下载内容片段](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/content-fragments/content-fragments-feature-video-use.html) | 视频 | 内容片段下载功能概述。 |
| 2020 年 12 月 7 日 | [内容片段编辑功能](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/content-fragments/content-fragments-feature-video-use.html) | 视频 | [!UICONTROL 内容片段]编辑器高级功能的视频概述。 了解如何与[!UICONTROL 内容片段]一起使用批注和版本比较。 |
| 2020 年 12 月 4 日 | [OCR提取(无论是否包含来自政府颁发的文档的条形码)](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/some-useful-integrations/ocr-data-extraction.html?lang=en#some-useful-integrations) | 文章 | 从政府颁发的文档（如驾照或护照）中提取数据，以填充自适应表单。 |
| 2020 年 12 月 14 日 | [AEM无头GraphQL概述](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/overview.html) | 视频 | 概述在Adobe Experience Manager或AEM中实现的GraphQL API。 AEM中的GraphQL API主要设计为将[!UICONTROL 内容片段]数据交付到下游应用程序，作为无头部署的一部分。 |
| 2020 年 12 月 16 日 | [Dynamic Media核心组件](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/dynamic-media/dynamic-media-core-components.html) | 视频 | 图像组件是Experience Manager核心组件的一部分，它内置了对Dynamic Media的支持。 了解图像组件如何允许内容作者在AEM Sites页面上使用Dynamic Media的功能，如图像预设、智能裁剪和图像修饰符。 |

### Experience Manager 发行信息

所有的 Experience Manager 发行说明均保留在以下页面：

* [Experience Manager 版本更新和路线图](https://docs.adobe.com/content/help/en/experience-manager-release-information/aem-release-updates/home.html)
* [AEM as a Cloud Service 发行信息](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-service/release-notes/home.html)
* [AEM Cloud Manager 发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [自动化表单转换服务发行说明](https://docs.adobe.com/content/help/zh-Hans/aem-forms-automated-conversion-service/using/release-notes.html)
* [AEM 6.5 Service Pack 发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
* [AEM 6.4 累积修复程序包发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-64/release-notes/cfp-release-notes.html)
* [AEM Assets Dynamic Media 发行说明](https://docs.adobe.com/content/help/zh-Hans/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [AEM Brand Portal 发行说明](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=en)
* [AEM 桌面应用程序发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-desktop-app/using/release-notes.html)
* [AEM Dispatcher 发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-dispatcher/using/getting-started/release-notes.html)
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

#### Campaign Classic

<!-- [Incident Response Bulletin](https://helpx.adobe.com/security/products/campaign/apsb21-04.html) (January 12) -->

* 20.3.3 版本 - [了解更多](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html#release-notes)
* 20.3.1 版本 - [了解更多](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html#release-notes)
* 20.2.4 版本 - [了解更多](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/previous-releases/release--20-2.html#release-20-2-4-build-9187)
* 20.1.4 版本 - [了解更多](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/previous-releases/release--20-1.html#release-20-1-4-build-9126)
* 19.2.4 版本 - [了解更多](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/previous-releases/release--19-2.html#release-19-2-4-build-9082)
* 19.1.8 版本 - [了解更多](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-8-build-9039)

#### Campaign Classic金本位

* 金标11版- [阅读更多](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/gs-release/gold-standard.html?lang=en#gs-11)

### 帮助资源

* Adobe Campaign Standard：[帮助中心](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/campaign-standard-home.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/release-notes/release-notes.html) - [操作方法视频](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [发行计划](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/release-notes/release-planning.html) - [最新文档更新](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic：[帮助中心](https://docs.adobe.com/content/help/zh-Hans/campaign-classic/using/campaign-classic-home.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/campaign-classic/using/release-notes/latest-release.html) - [操作方法视频](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)- [最新文档更新](https://docs.adobe.com/content/help/zh-Hans/campaign-classic/using/documentation-updates.html)
* Adobe Campaign 控制面板：[文档](https://docs.adobe.com/content/help/zh-Hans/control-panel/using/control-panel-home.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/control-panel/using/release-notes.html) - 有关 [Campaign Standard](https://docs.adobe.com/content/help/zh-Hans/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html)/[Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html) 的操作方法视频

#### Campaign 的新课程和教程

过去一个月发布的新视频、教程及课程。

| 发布日期 | 名称 | 解决方案 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 12 月 23 日 | [配置动态内容](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/configuring-dynamic-content.html#sending-messages) | Campaign Classic | （视频）了解不同类型的动态内容，并了解如何创建个性化块和条件语句并将它们应用到投放。 |
| 2020 年 12 月 9 日 | [控制面板 - Google TXT 记录管理](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/subdomains-and-certificates/google-txt-record-management.html#subdomains-and-certificates) | Campaign Standard | （视频）了解如何将Google TXT站点验证记录添加到所有子域，这些子域用于向GMAIL地址发送电子邮件，活动控制面板。 |

## ![图标](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Adobe Advertising Cloud 的发行说明。

* [Advertising Cloud DSP 中的新增功能](#adcloud-dsp)
* [Advertising Cloud Search 中的新增功能](#adcloud-search)

### [!DNL Advertising Cloud DSP] 中的新增功能 {#adcloud-dsp} 

上次更新：**2020年10月28日**

| 功能 | 描述 |
| -----------| ---------- |
| 新建帮助 | （10 月 28 日版）旧版帮助页面已替换为更新页面，这些更新页面可从 DSP 主菜单的“帮助”链接获取，也可随时从 [https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html](https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html) 获取。 |
| 促销活动 | （10 月 28 日版）以前的 Campaigns 测试版视图现在成为默认的 Campaigns 视图，可以实现更快的分析、简化的工作流和自定义视图。 |
| 专用内容库 | （10 月 15 日版）如今，所有用户都可以使用新的交易 ID 表单来设置和编辑交易 ID 详细信息，该表单是旧版[!UICONTROL 智能广告投放]表单的简化版。要设置新的交易 ID 详细信息，请转到&#x200B;**[!UICONTROL 内容库 > 交易]**，单击&#x200B;**[!UICONTROL 创建]**，然后单击&#x200B;**[!UICONTROL 交易 ID 测试版]**。 |
| 投放预测 | （10 月 15 日版）在投放设置的[!UICONTROL 预测]部分，我们为具有投放级别步调的广告投放提供了一个新增的[!UICONTROL 估计的最大量]部分，它指明了当前目标配置中的可用容量。 |

### [!DNL Advertising Cloud Search] 中的新增功能 {#adcloud-search} 

上次更新：**2020年10月17日**

| 功能 | 描述 |
| -----------| ---------- |
| [!UICONTROL 搜索促销活动] | 如今，[!UICONTROL 帐户]视图的[!UICONTROL 访问]列可指明 [!DNL Advertising Cloud Search] 何时无法登录到已启用搜索引擎的帐户。要了解错误原因，请将光标悬停在警告图标上。 |
| [!UICONTROL 自定义警报] | 此前的[!UICONTROL 测试版警报]现已更名为[!UICONTROL 自定义警报]。 |
| [!UICONTROL 自定义警报] | 在自定义警报中，我们简化了下面的工作流程并将其移至[!UICONTROL 过滤器]选项卡：用来确定与上一期间的量度相比，指定日期范围的量度何时发生增减。 |

### Ad Cloud 教程和课程

更新日期：**2020 年 12 月 2 日**

| 发布日期 | 名称 | 解决方案 | 描述 |
| ----------- | ----------- | ---------- | ---------- |
| 2020 年 11 月 14 日 | [使用 Adobe Analytics 创建 Advertising Cloud 功能板](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-dashboards-a4adc.html?lang=zh-Hans) | 视频 | 用于创建适合实时监控促销活动的 Advertising Cloud 功能板的技术。 |
| 2020 年 11 月 14 日 | [创建 Advertising Cloud 站点登入报表](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-site-entry-a4adc.html?lang=zh-Hans#analytics) | 视频 | 创建 Advertising Cloud 站点登入报表，以监控每周的某天、每天的某个时间、浏览器和地理影响。 |
| 2020 年 11 月 14 日 | [利用 Advertising Cloud 数据创建 Analytics 自定义量度](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-custom-metrics-a4adc.html?lang=zh-Hans#analytics) | 视频 | 在 Adobe Analytics 中使用 Advertising Cloud 数据时创建的有用自定义量度。 |
| 2020 年 11 月 14 日 | [为激活和报表创建 Analytics 区段](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-segments-a4adc.html?lang=zh-Hans#analytics) | 视频 | 使用 Advertising Cloud 维度创建区段，以实现更简洁的报表和分析。 |
| 2020 年 11 月 14 日 | [了解预测受众](https://experienceleague.corp.adobe.com/docs/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/understanding-predictive-audiences.html?lang=zh-Hans#build-and-manage-audiences) | 视频 | 在此视频中，我们将讨论 Audience Manager 的预测受众，介绍其工作方式的详细信息以及相关用例。 |
| 2020 年 11 月 14 日 | [为 Advertising Cloud 激活和报表创建 Analytics 配置文件](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-profiles-a4adc.html?lang=zh-Hans#analytics) | 视频 | 如何使用 Adobe Analytics 为 Advertising Cloud 再营销创建稳固的站点重定向池。 |
| 2020 年 11 月 14 日 | [使用 Advertising Cloud 营销渠道进行报告](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-reporting-a4adc.html?lang=zh-Hans#analytics) | 视频 | 如何将 Advertising Cloud 浏览进入和点进登入数据与 Adobe Analytics 营销渠道结合使用。 |
| 2020 年 11 月 14 日 | [使用 Adobe Analytics 创建启动前促销活动分析](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-pre-launch-a4adc.html?lang=zh-Hans) | 视频 | 如何使用 Adobe Analytics 为启动 Advertising Cloud 付费媒体促销活动奠定基础。 |

## ![图标](/assets/magento.png) [!DNL Magento] {#magento}

有关 Magento 的发行说明，请参阅：

* [Magento Commerce 2.3.5](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-5-open-source.html)
* [Magento Open Source 2.3.5](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-5-open-source.html)

## ![图标](/assets/target.png)[!DNL Target] {#target}

请参阅 [[!DNL Target]  发行说明](https://docs.adobe.com/content/help/zh-Hans/target/using/release-notes/target-release-notes.html)了解最新发行信息。

## ![图标](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] 是一个完整的应用程序，面向希望通过参与复杂购买历程的每个阶段来转变客户体验的潜在客户管理人员和 B2B 营销人员。

### 核心 Marketo Engage 更新

请参阅 [!DNL Marketo] [发行说明](https://docs.marketo.com/display/public/DOCS/Jan+%2721)了解最新发行信息。

### 即将推出的功能

本季度将发布以下功能：

| 功能 | 描述 |
| ------ | --------- |
| [!DNL Bizible] | <ul><li>新的基于帐户的分段</li><li>保存特定于功能板的过滤器</li><li>将 Bizible 功能板导出为 PDF</li></ul> |
| Sales Connect | 撰写窗口和命令中心更新/增强功能 |

### 弃用

* **Asset API“_method”参数：** 2020 年 9 月之后，Asset API 端点将不再接受 `_method` 在 POST 正文中传递查询参数以绕过 URI 长度限制。
* **弃用 Internet Explorer 支持：**&#x200B;从 2020 年 7 月 31 日发行的 7 月版本开始，Internet Explorer 将不再支持 Marketo Engage 用户界面。

有关累积和历史发行说明，请参阅 [Marketo 发行说明](https://docs.marketo.com/display/public/DOCS/Release+Notes)。

## ![图标](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

Adobe Document Cloud 的发行信息和帮助资源。

### Acrobat教程

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 12 月 29 日 | [整理页面](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/organize.html) | 文章 | 使用AcrobatDocument Cloud中的[!UICONTROL 组织页面]在PDF中添加、替换、提取、旋转、删除和移动页面。 |
| 2020 年 12 月 29 日 | [创建可填写的表单](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/create-fillable-forms.html) | 文章 | 将在InDesign、Microsoft Word或Excel或其他应用程序中创建的扫描纸质表单或文档转换为可填写的PDF表单。 |
| 2020 年 12 月 29 日 | [扫描和OCR](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/scan-and-ocr.html) | 文章 | 将文档的扫描件或图像转换为可搜索、可编辑的PDF文件，并调整生成文件的质量。 |
| 2020 年 12 月 28 日 | [准备具备辅助工具的PDF文件](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/accessibility.html) | 文章 | 创建可普遍访问的PDF文件。 |
| 2020 年 12 月 28 日 | [使用表单数据](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/formdata.html) | 文章 | 如果您有一组已填写的表单并且需要编译数据，则可以使用AcrobatDC将响应合并到单个电子表格中。 |
| 2020 年 12 月 28 日 | [减小文件大小并优化](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/reduce.html) | 文章 | 减少大文件并优化PDF，同时保持共享、发布或归档的质量。 |
| 2020 年 12 月 21 日 | [使PDF投票更易于访问](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/by-industry/gov/pdfs/making-pdf-ballots-accessible.html) | 网络研讨会 | 了解PDF辅助工具的关键方面，这些辅助技术使用户（如屏幕阅读器）能够阅读并完成投票。 |
| 2020 年 12 月 21 日 | [标记密文和清理](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/redact.html) | 文章 | 使用密文工具从PDF中永久删除隐私或敏感信息并清理文档。 |
| 2020 年 12 月 18 日 | [Action Wizard](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/action.html) | 文章 | 创建一个动作，将一组命令自动应用于一个或多个文件。 |
| 2020 年 12 月 15 日 | [使用生存时间(TTL)设置配置特征过期](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/configuring-trait-expiration-with-the-time-to-live-ttl-setting.html?lang=en#build-and-manage-audiences) | 视频 | 了解如何使用[!UICONTROL 实时时间]，如果您未在指定时间段内重新获得资格，则该特征中的成员资格将过期。 |
| 2020 年 12 月 4 日 | [使用Adobe PDF工具API对OCR PDF文件进行签名](https://experienceleague.adobe.com/docs/document-services/document-services/tutorials/ocr.html) | 文章 | 了解如何使用[!UICONTROL 光学字符识别]解锁扫描的PDF，以提取文本并创建可搜索的文件。 |
| 2020 年 12 月 4 日 | [Adobe PDF工具API和Java入门](https://experienceleague.adobe.com/docs/document-services/document-services/tutorials/gettingstartedjava.html) | 文章 | 开发人员只需几分钟即可开始，随时可以运行示例文件，该示例文件是为访问所有可用的Web服务而提供的。 本教程将指导您完成使用PDF工具Java SDK开始运行示例的所有步骤。 |
| 2020 年 12 月 4 日 | [Adobe PDF工具API和。Net入门](https://experienceleague.adobe.com/docs/document-services/document-services/tutorials/gettingstartednet.html) | 文章 | 开发人员只需几分钟即可开始，随时可以运行示例文件，该示例文件是为访问所有可用的Web服务而提供的。 本教程将指导您完成使用PDF工具。Net SDK运行示例的开始的所有步骤。 |
| 2020 年 12 月 4 日 | [利用PDF工具APIExport PDFWord、PowerPoint等](https://experienceleague.adobe.com/docs/document-services/document-services/tutorials/exportpdf.html) | 文章 | 将PDF文件转换为MS Word，以编辑内容、审批，稍后再发送以供签名，从而创建自定义合同工作流。 或者，将PDF内容导出为MS Excel格式，以便进行发票、财务计算或数据分析。 |
| 2020 年 12 月 4 日 | [使用PDF工具API和Node.js在几分钟内从HTML或MS Office创建PDF](https://experienceleague.adobe.com/docs/document-services/document-services/tutorials/createpdffromhtml.html) | 文章 | 了解如何使用新的Adobe PDF工具API实现文档工作流的数字化。 此API为开发人员提供了各种自由选择服务，它们可以选择几种功能强大的PDF处理服务，以满足复杂业务工作流的需求。 |

### Adobe Sign 的新课程和教程

为 Adobe Document Cloud 发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 12 月 22 日 | [工资保障](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/expand/recipes/gov/usecasegovpaycheck.html) | 演示 | 了解如何使用Adobe Sign将支付保护项目表单转换为在线交互式表单。 |

有关 Document Cloud 的帮助，请参阅：

* [Adobe Acrobat 学习中心](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=zh-Hans)
* [Adobe Sign 学习中心](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=https://experienceleague.corp.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=zh-Hans)
* [Document Cloud 学习与支持](https://helpx.adobe.com/support/document-cloud.html)
