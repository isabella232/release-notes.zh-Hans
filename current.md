---
title: 最新发行说明
description: 了解 [!DNL Experience Cloud] 产品和服务的最新发行说明、新增功能和新文档。查找有关  [!DNL Experience Cloud]、 [!DNL Creative Cloud for enterprise] 和  [!DNL Document Cloud] 的新的帮助内容和教程。
doc-type: release notes
last-update: January 2022
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: 3ecd5dfeeee5692b7fb5c5fa4dcac497b3c49ce0
workflow-type: tm+mt
source-wordcount: '6573'
ht-degree: 98%

---

# Adobe Experience Cloud 发行说明 - 2022 年 1 月

![横幅](assets/experience-cloud-banner-3.png)

了解 [Adobe Experience Cloud 产品](https://business.adobe.com/products/adobe-experience-cloud-products.html)的最新版本更新。在 Experience League 上获取最新的自助文档、教程和课程。

>[!NOTE]
>
>要收到有关此页面更新的每月电子邮件通知，请订阅 [Adobe 优先产品更新](https://www.adobe.com/cn/subscription/priority-product-update.html)。经常回来查看 Experience League 的最新动态。

**2022 年 1 月**

最新更新日期：**2022 年 1 月 26 日**

* [[!DNL Experience League] 活动](#events)
* [[!DNL Experience Cloud Central Interface Components] 和管理](#ecloud)
* [Adobe [!UICONTROL 系统状态]](#status)
* [[!DNL Adobe Experience Platform]](#platform)（更新日期：**2022 年 1 月 26 日**）
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Customer Journey Analytics]](#cust-journey)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL XML Documentation for Adobe Experience Manager]](#xml-doc)
* [[!DNL Adobe Commerce]](#magento)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Journey Orchestration]](#journey-orch)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Document Cloud]](#doc-cloud)
* [[!DNL Adobe Creative Cloud for enterprise]](#creative-cloud)

需要帮助？请访问 [Adobe Experience League](https://experienceleague.adobe.com/?lang=zh-Hans/#home)，获取产品和技术文档、Adobe 策划课程、视频教程、快速解答、社区洞察以及由讲师指导的培训。

## ![图标](/assets/experience-league.png) [!DNL Experience League] 活动 {#events}

Experience League 活动是从 Adobe 产品专家处获得答案的好地方。下面是开展的活动：

* [Experience League Live](#exl-live)：要查看实时和点播视频活动，请访问 YouTube
* [社区问答喝咖啡休息时间](#coffee)：在 Experience League 社区中与产品经理聊天
* [Adobe Developer&#39;s Live](#dev-live)：要查看点播视频活动，请访问 Experience League

计划和活动如下所示：

### Experience League LIVE{#exl-live}

[Experience League LIVE](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=zh-Hans) 是 Experience League 团队制作的直播节目。利用这个机会，您可以与 Adobe 产品专家联系。学习可用于 Adobe Experience Cloud 应用程序的可操作性提示、技巧和策略。

| 活动日期 | 时间 | 活动名称 | 格式 | 描述 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022 年 1 月 25 日 | 上午 9:00（太平洋标准时间） | [跨数据源分析您的业务](https://www.youtube.com/watch?v=L2EWCOHeyXI) | 视频直播活动 | 使用 Customer Journey Analytics 将您的所有数据集中到一个地方。 |
| 2022 年 2 月 3 日 | 中午 12:00（东部标准时间） | [在 AEM 中引入所有新的参考演示](https://www.youtube.com/watch?v=FEREXV826NQ) | 视频直播活动 | 了解配置、演示和探索 AEM as a Cloud Service 功能的最快方法。 |

{style=&quot;table-layout:auto&quot;}

[Experience League Live](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=en) 上提供精彩回放。

### 社区问答喝咖啡休息时间{#coffee}

与特邀嘉宾共度一小时，并在 Experience League 社区中提交您的问题。向 Adobe 产品专家寻求解答！

| 活动名称 | 日期 | 应用程序 | 格式 | 描述 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 客户历程分析 和 Analytics 的未来 | 太平洋标准时间 2022 年 1 月 18 日上午 8:00 | Adobe Analytics、Customer Journey Analytics、Experience Platform | 论坛问答 | 在 Analytics 社区中向 Adobe Analytics 小组产品经理 Trevor Paulsen 发布您的问题。<br>[详情和注册](https://analyticscommunityqacoffeebrea.splashthat.com/?utm_source=community-thread&amp;utm_campaign=coffee_talk_AA&amp;utm_content=220118) |
| Adobe Target 与 Journey Optimizer、Adobe Target 界面和一般 Target 主题的集成 | 太平洋标准时间 2022 年 1 月 19 日上午 9:00 | Adobe Target、Journey Optimizer | 论坛问答 | 与 Jon Tehero 共度一小时，并在 Adobe Target 社区中提交您的问题。<br>[详情和注册](https://communitycoffeebreakadobetarge.splashthat.com/?utm_source=email&amp;utm_campaign=coffee_talk_AT&amp;utm_content=210119) |

{style=&quot;table-layout:auto&quot;}

### Adobe Developer&#39;s Live{#dev-live}

| 活动 | 日期和时间 | 类型 | 描述 |
| -----------| ---------- | ---------- |---------- |
| [Adobe [!DNL Developers Live]](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2021/oct2021/overview.html?lang=en) | 按需 | 视频 | [!DNL Developers Live] 展示了跨行业推动设计、内容创建工作流、文档服务和客户体验管理的最新技术进步和开发人员工具。查看主题演讲，了解 Analytics API、客户端数据层、Adobe I/O 开源项目等内容。 |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/ec_appicon_24.png) [!DNL Experience Cloud Central UI Components] 和管理 {#ecloud}

上月未进行更新。

**关于 [!DNL Experience Cloud Central UI Components] 和管理**&#x200B;的更多帮助资源

* [中央界面组件](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=zh-Hans)和用户管理的管理帮助
* [地点 — 位置服务](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=zh-Hans)的帮助和发行说明
* [人员 — 客户属性和受众库](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=zh-Hans)的相关帮助

## ![图标](/assets/adobe.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] 提供了关于 Adobe 产品与服务中断和维护活动的详细信息、状态更新以及电子邮件通知。请访问 [status.adobe.com](https://status.adobe.com/) 查看。

阅读 [!DNL Adobe System Status] 的[最新发行说明](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=zh-Hans)。

## ![图标](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Experience Platform 和 [!UICONTROL Mobile SDK] 的发行更新信息和新文档：

* 版本： **2022年1月26日**

请参阅 [Experience Platform发行说明](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=zh-Hans) 来阅读最新。

### Experience Platform 的新教程和课程 {#tutorials-platform}

为 Experience Platform 发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 1 月 | [配置 Customer AI](https://experienceleague.adobe.com/docs/platform-learn/tutorials/intelligent-services/configure-customer-ai.html) | 视频 | 了解如何创建 Customer AI 实例，以便预测客户的行为。 |
| 2022 年 1 月 | [配置 Attribution AI](https://experienceleague.adobe.com/docs/platform-learn/tutorials/intelligent-services/configure-attribution-ai.html) | 视频 | 了解如何创建 Attribution AI 实例，以便分析营销渠道和营销活动带来的影响。 |

{style=&quot;table-layout:auto&quot;}

### Adobe Mobile SDK

请参阅 Adobe Experience Platform Mobile SDK 的[发行说明和更改日志](https://aep-sdks.gitbook.io/docs/release-notes)。

## ![图标](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

发行日期：**2022 年 1 月 19 日**

* [Adobe Analytics 中的新增功能](#aa-features)
* [Customer Journey Analytics 中的新增功能](#cust-journey)
* [Adobe Analytics 中的修复](#aa-fixes)
* [Analytics 管理员的重要注意事项](#aa-notices)
* [Analytics 的课程及教程](#tutorials-analytics)
* [AppMeasurement](#appm)

### Adobe Analytics 中的新增功能 {#aa-features}

| 功能 | 描述 | 目标日期 |
| ----------- | ---------- | ------- |
| 不适用 |  | 参见[正式发布](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=zh-Hans) |

{style=&quot;table-layout:auto&quot;}

### Customer Journey Analytics 中的新增功能 {#cust-journey}

| 功能 | 描述 | 目标日期 |
| ----------- | ---------- | ----- |
| 绑定维度和绑定量度的[!UICONTROL 持久性]选项 | 创建或编辑数据视图时，您可以将维度的持久性绑定到另一个维度或量度。这个概念在 Reports and Analytics 中称为&#x200B;_陈列_，现在 CJA 也支持这个概念。[了解详情](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dataviews/component-settings/persistence.html#binding-dimension) | 2022 年 1 月 19 日 |
| [!UICONTROL 第一个已知]和[!UICONTROL 最后一个已知]分配模型 | 这两个新分配模型采用指定持久性范围（会话、人员或带回溯的自定义时间段）内某个维度的第一个或最后一个观察值。然后它们将分配模型应用于指定范围内的所有事件。[了解详情](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dataviews/component-settings/persistence.html#allocation-settings) | 2022 年 1 月 19 日 |
| [!UICONTROL PersonID] 和 [!UICONTROL PersonID 命名空间]作为维度 | 将 `personID`（或 `customerID` 或任何用于在连接中合并数据集的 ID）公开为数据视图中的维度。此增强功能使您能够从连接拉入 `personID`，更轻松地将其作为维度包含在数据视图中。[了解详情](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dataviews/component-reference.html?lang=en#optional-standard-components) | 2022 年 1 月 19 日 |

{style=&quot;table-layout:auto&quot;}

请参阅[正式发布](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html)，了解发行信息。

### Adobe Analytics 和 Customer Journey Analytics 中的修复 {#aa-fixes}

* 修复了维度项中缺少受众 ID 的 Analysis Workspace 问题。（AN-262038；AN-279315）
* 修复了阻止用户在 Workspace 中加载已保存的 [!DNL Target] 项目的问题。（AN-277461；AN-275825；AN-266397）
* 修复了未启用的功能在 UI 中可见的问题。(AN-262006)
* 修复了使用 Workspace 中的日期字段更改日期时发生的问题。这导致[!UICONTROL 结束时间]从晚上 11:59 更改为中午 12:00。（AN-277269；AN-277481）
* 修复了在将新区段添加到已加载区段时导致区段 UI 中断的问题。(AN-260827)
* 修复了用户无法访问共享的 Workspace 项目的问题。(AN-267529)
* 添加了一条错误消息，显示滚动日期范围的开始日期晚于结束日期。(AN-270488)
* 修复了各种数据馈送问题。（AN-275876；AN-270512；AN-277284；AN-277290；AN-274893；AN-274606；AN-269651）
* 修复了图表中的日期范围忽略表格中的日期过滤器的问题。(AN-263999)
* 修复了由于夏令时而提前发送计划报表的问题。（AN-276410；AN-276305）
* 修复了在 Workspace 中无法将项目下载到 `.csv` 文件的问题。(AN-275834)

#### Adobe Analytics 和 CJA 中的其他修复

AN-253294；AN-254976；AN-255377；AN-255561；AN-258550；AN-259336；AN-263935；AN-265094；AN-269441；AN-269486；AN-269855；AN-271166；AN-271588；AN-272088；AN-272249；AN-272859；AN-272873；AN-272885；AN-273229；AN-273913；AN-274237；AN-274472；AN-274491；AN-274619；AN-274766；AN-275248；AN-275259；AN-275271；AN-275315；AN-275388；AN-275418；AN-275597；AN-275643；AN-275650；AN-275651；AN-275675；AN-275682；AN-275704；AN-275711；AN-275796；AN-275834；AN-275923；AN-275941；AN-276044；AN-276125；AN-276157；AN-276397；AN-276597；AN-276789；AN-276834；AN-276861；AN-276870；AN-276963；AN-276975；AN-277000；AN-277044；AN-277093；AN-277200；AN-277215；AN-277271；AN-277281；AN-277362；AN-277419；AN-277492；AN-277498；AN-277533；AN-277619；AN-277675；AN-277681；AN-277767；AN-277805；AN-277810；AN-277818；AN-277875；AN-277933；AN-277988；AN-278105；AN-278115；AN-278122；AN-278192；AN-278407；AN-278437；AN-278559；AN-278604；AN-278610；AN-278709；AN-278835；AN-278849；AN-278881；AN-279067；AN-279103；AN-279111；AN-279219；AN-279237；AN-279312

### [!DNL Analytics] 管理员的重要注意事项 {#aa-notices}

| 注意事项 | 添加或更新日期 | 描述 |
| ----------- | ---------- | ---------- |
| 旧版 Analytics OAuth/JWT 集成的允许列表 EOL 扩展到期 | 2022 年 1 月 14 日 | 开 **2022年5月25日**, [Analytics 1.3 API、1.4 SOAP API和旧版Analytics OAuth/JWT EOL](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md) 允许列表“延期”将过期。 它旨在为使用旧版 [!DNL Adobe Analytics] 将其客户端集成迁移到的OAuth/JWT凭据需要额外时间 [Adobe IMS凭据](https://developer.adobe.com/console). 该扩展到期会影响（但不限于）尚未完成必需的 IMS 迁移的 [!DNL Adobe Analytics Livestream] 和 [!DNL Adobe Campaign] 客户。如果客户目前正在通过允许列表扩展使用旧版 [!DNL Analytics] OAuth/JWT 凭据，但未在 2022 年 5 月 25 日之前完成向 IMS 凭据迁移，则将失去对 Adobe 服务的访问权限。Livestream 客户可以参考这些关于将客户端应用程序迁移到 IMS 凭据的[说明](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/live-stream-api/getting_started.md)。[!DNL Campaign] 客户可以联系他们的 Adobe 帐户团队，了解如何升级到最新版本的 [!DNL Campaign]。 |
| 终止 [!DNL Reports & Analytics] | 2022 年 1 月 4 日 | 自 **2023 年 12 月 31 日**&#x200B;起，Adobe 决定中断 及其随附的报表和功能。[!DNL Reports & Analytics]报表、可视化图表和基础技术 [!DNL Reports & Analytics] 不再满足Adobe的技术标准。 最多 [!DNL Reports & Analytics] 功能在 [Analysis Workspace](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/home.html). 自2015年Analysis Workspace发布以来， [!DNL Reports & Analytics] 功能和功能已移至Analysis Workspace，并达到了工作流对等性阈值。 [本通知](https://spark.adobe.com/page/6WnF8JK6IRDhf/)解释了生命周期结束的过程。 |
| 安全文件传输协议 (SFTP) 服务升级 | 2022 年 1 月 13 日 | 在 **2022 年 5 月 2 日**， 将升级安全文件传输协议 (SFTP) 服务，以提高文件传输的安全性。[!DNL Adobe Analytics]此更改完成后，某些 SFTP 客户端配置将不再受支持。我们还将增加一些在 **2022 年 3 月 1 日**&#x200B;之前可用的连接选项。这只会影响使用 SFTP 发送到 Adobe Analytics 的数据或从 Adobe Analytics 中检索的数据。FTP 协议将不会受到影响。为避免服务中断，请确保您的 SFTP 客户端（代码、工具、服务）与[此处](https://experienceleague.adobe.com/docs/analytics/export/ftp-and-sftp/secure-file-transfer-protocol/sftp-upgrade.html)详述的更改一致。 |
| _全球 + 中国_ RDC 类型 | 2021 年 11 月 22 日 | _全球 + 中国_ 是一种新的区域数据收集 (RDC) 类型，使用[!UICONTROL 中国性能优化加载项包]为全球客户简化了流量路由。过去，您必须确定是将数据路由到中国收集端点还是全球收集端点之一。现在您可以选择此 RDC *类型*，让 Adobe 根据用户的地理位置确定最佳收集端点。 |
| 数据源中的 Full Processing 生命周期结束 | 2021 年 10 月 18 日 | **2022 年 1 月 31 日**，Adobe 将终止 Full Processing，这使用户能够将离线命中数据提取到 Analytics 中。此功能可通过 [Bulk Data Insertion API](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md) 获得。[了解详情](https://experienceleague.adobe.com/docs/analytics/import/data-sources/data-types-and-categories/datasrc-fullproc-eol.html?lang=zh-Hans?lang=zh-Hans) |

{style=&quot;table-layout:auto&quot;}

### AppMeasurement {#appm}

有关 AppMeasurement 版本（版本 2.22.4）的最新更新，请参阅[适用于 JavaScript 的 AppMeasurement 发行说明](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=zh-Hans)。

### Analytics 的新教程和课程 {#tutorials-analytics}

为 Adobe Analytics 发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 1 月 | [“面向商业用户的 Analytics 基础知识”已停用](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/retire-fundamentals-for-business-users-course.html) | 视频 | 了解原课程停用的原因以及 Adobe 推荐的新替代课程。 |
| 2022 年 1 月 | [“媒体播放耗时”面板](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/media-analytics/measuring-media-analytics/media-playback-time-spent-panel.html?lang=en) | 视频 | 了解“媒体播放耗时”面板如何使媒体用户能够通过一天中所选粒度的观看时间量来了解他们的收视率。 |
| 2022 年 1 月 | [Adobe Analytics 中的客户细分策略和最佳实践](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/customer-segmentation-strategies.html?lang=en) | 视频 | 加入分析业内人士，参加周四的分析活动，重点了解客户细分基础知识、策略和最佳实践。 |
| 2022 年 1 月 | [配置付费搜索检测](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configure-paid-search-detection.html#) | 视频 | 了解如何在 Adobe Analytics Admin Console 中完成“付费搜索检测”部分的配置，包括一些建议。 |
| 2022 年 1 月 | [配置列表变量](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configuring-list-variables.html?lang=en) | 视频 | 了解如何以及为何在 Adobe Analytics 中配置和使用列表变量。列表变量使您可以将多个值放入 eVar。 |
| 2022 年 1 月 | [配置流量变量 (props)](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configuring-traffic-variables-props.html?lang=en) | 视频 | 了解如何在 Analytics Admin Console 中配置流量变量（也称为 _props_）。 |
| 2022 年 1 月 | [使用处理规则处理传入的数据](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/manipulating-incoming-data-with-processing-rules.html?lang=en) | 视频 | 了解 Adobe Analytics 中的处理规则及其用途。获取关于使用处理规则的一些技巧、例子，甚至警告。 |
| 2022 年 1 月 | [在 Analysis Workspace 中将区段用作维度](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/applying-segments/using-segments-as-dimensions-in-analysis-workspace.html?lang=en) | 更新的视频 | 了解如何通过在 Analysis Workspace 中将区段用作维度来比较和可视化区段。 |
| 2022 年 1 月 | [Adobe Analytics 中的区段管理和共享](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/segment-management-and-sharing.html?lang=en) | 更新的视频 | 在这个更新的视频中，了解一些分享和管理区段的技巧。 |
| 2022 年 1 月 | [在 Analysis Workspace 中使用区段限制数据](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/applying-segments/using-segments-to-limit-data-in-analysis-workspace.html?lang=en) | 更新的视频 | 了解如何在 Analysis Workspace 中将项目用户限制到用户使用工具的一个或多个特定区段。 |
| 2022 年 1 月 | [Analysis Workspace 中的区段比较](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/segment-comparison-in-analysis-workspace.html?lang=en) | 更新的视频 | 了解区段 IQ（Adobe Analytics 中的 Analysis Workspace 的一部分）如何通过检查所有维度和量度上的任意两个 Analytics 区段来自动发现它们在统计上最显著的差异，从而简化分析。 |

{style=&quot;table-layout:auto&quot;}

### Analytics 帮助资源

* [Adobe Analytics 产品文档及教程](https://experienceleague.adobe.com/docs/analytics.html?lang=zh-Hans)

## ![图标](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager 中的修复和改进。

* 解决了通过 Swagger 接口执行时导致所有 API 调用返回 `Undocumented` 错误的问题。(AAM-59190)
* 解决了导致在某些情况下将错误的用户角色分配给合作伙伴的问题。(AAM-59451)
* 解决了导致 API 需要区分大小写的身份验证标头的问题。(AAM-58528)

## ![图标](/assets/aem.png) Adobe Experience Manager {#aem}

Adobe 建议访问 [Experience Manager 版本更新和路线图](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=zh-Hans)页面以及时了解版本信息。

### Experience Manager 产品版本

* **Experience Manager as a Cloud Service**

   观看 [2021 年 12 月版概述视频](https://video.tv.adobe.com/v/339278)，大致了解 2021.11.0（2021 年 11 月）版的新增功能。

   * [2021 年 10 月版新增功能概述视频](https://video.tv.adobe.com/v/338253)。
   * [2021 年 9 月版新增功能概述视频](https://video.tv.adobe.com/v/337381)。

   * **Experience Manager Assets as a Cloud Service**

      _新增功能_

      * Dynamic Media [!UICONTROL 图像智能裁切]和[!UICONTROL 色板]功能现在由最新的 Sensei 服务提供支持，可生成改进的裁切和色板。还推出了一项增强功能，可生成宽高比相同但分辨率不同的各种裁切内容。此外，如果图像配置文件中的宽度和高度没有变化，则在重新处理时将保留任何手动编辑内容。

      _Experience Manager Assets 预发行渠道中的新增功能_

      * Dynamic Media - 您现在可以使用 Experience Manager Dynamic Media 界面配置[!UICONTROL 常规设置]和[!UICONTROL 发布设置]，而不必使用 Dynamic Media Classic 桌面应用程序。
      * Dynamic Media 现在支持 MXF 视频的提取、预览、播放和发布。尚不支持 MXF 视频的注释和可购买视频。
      * 在配置远程 DAM 和 Sites 部署之间的连接后，远程 DAM 上的资源即可用于 Sites 部署。您现在可以对远程 DAM 资源或文件夹执行[更新、删除、重命名和移动操作](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/admin/use-assets-across-connected-assets-instances.html?lang=en)。更新会在 Sites 部署中自动提供，但会有一些延迟。
   * **Experience Manager Forms as a Cloud Service**

      _新增功能_

      * **将 Experience Manager 工作流数据外部化以便安全处理**：对于包含敏感个人数据 (SPD) 元素的进程内 Experience Manager 工作流数据（Experience Manager [!UICONTROL 工作流变量]数据），您可以存储在客户管理的存储库中以便安全处理。数据元素和工作流变量没有存储在 Experience Manager 存储库中，而是在处理工作流时按需从客户管理的存储库中提取。

      _Experience Manager Forms 预发行渠道中的新增功能_

      * **AEM Forms as a Cloud Service - 通信**：[通信 API](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/using-communications/aem-forms-cloud-service-communications.html?lang=en) 可帮助您组合模板和 XML 数据以生成各种格式的打印文档。使用该服务，您能够以同步和批处理模式生成文档。这些 API 使您能够创建应用程序来执行以下操作：
         * 使用 XML 数据填充模板文件（PDF 和 XDP）来生成文档。
         * 生成各种格式的输出表单，包括非交互式 PDF 打印流。
      * **使用 Communications API 创建的记录文档和 PDF 文档的自定义字体**：您现在可以在使用 Communications API 生成的 PDF 文档中使用品牌批准的字体，以满足贵企业的要求。
      * **Forms Portal**：您可以使用 [Forms Portal](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/create-an-adaptive-form/configure-forms-portal.html?lang=en) 在 Experience Manager Sites 页面上列出发布的自适应表单。它可以帮助网站访客发现所有可用表单。此外，访客可以使用 [!UICONTROL Forms Portal] 保存和访问自适应表单的草稿，并查看提交的自适应表单的 PDF 版本。
   * **Cloud Manager**

      _新增功能_

      * 用户现在可以使用新的前端管道以加速方式专门部署前端代码。有关更多信息，请参阅 [Cloud Manager 前端管道](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/cicd-pipelines/introduction-ci-cd-pipelines.html?lang=en#front-end)。

         >[!IMPORTANT]
         >
         >您必须使用 Experience Manager 版本 `2021.10.5933.20211012T154732Z` 或更高版本才能使用新的[!UICONTROL 前端管道]。

      * 通过以更有效的方式执行代码分析而无需构建整个 Experience Manager 映像，缩短了代码质量管道持续时间。此更改将在版本发布后的未来几周内逐步推出。
      * Git Commit ID 现在显示在管道运行详细信息中，以便更轻松地跟踪已生成的代码。
      * 现在可通过公开发布的 API [!UICONTROL 创建程序]。
      * 现在可通过公开发布的 API [!UICONTROL 创建环境]。
      * `x-request-id` 响应标头现已在 [www.adobe.io](https://www.adobe.io/) 上的 API Playground 中可见。在提交客户关怀问题以进行疑难解答时，此标头很有用。
      * 提供了一个新的[!UICONTROL 活动]页面，可以在其中查看管道和代码运行等活动及其相关详细信息。随着时间的推移，此页面中列出的活动的范围会随着提供的详细信息而扩大。
      * 现在提供了带状态弹出框的新[!UICONTROL 管道]页面，以便轻松查看详细信息摘要。您可以查看[!UICONTROL 管道]运行及其相关详细信息。
      * [!UICONTROL 编辑管道] API 现在支持更改部署阶段使用的环境。
      * [!DNL OakPal] 扫描过程中的优化现在可用于大型包。
      * 质量问题 CSV 文件现在包含每个质量问题的时间戳。





### 社区

* **Experience Manager GEM 网络研讨会 - Experience Manager as a Cloud Service** | 2021 年回顾和 2022 年展望

   **日期**：2022 年 1 月 25 日星期二
   **时间**：太平洋标准时间上午 8:00、欧洲中部时间下午 5:00 或印度标准时间下午 9:30
   **持续时间**：60 分钟
   **费用**：免费！

   * [请在此处登记](https://adobe.ly/3tAh3OC)
   * [提出问题](https://adobe.ly/3zJrS0f)

* [宣布 2021 年度社区成员](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/announcing-community-members-of-the-year-2021/td-p/436782)

   我们非常感谢 2021 年参与 [Experience Manager 社区](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/ct-p/adobe-experience-manager-community)并帮助他人解决问题的每一个人。

   每年，Experience Cloud 社区都会表彰那些在服务和支持他人方面做出杰出贡献的成员，并授予社区年度成员奖。我们在此宣布 [@Asutosh_Jena_](https://experienceleaguecommunities.adobe.com/t5/user/viewprofilepage/user-id/7532759) 和 [@Vijayalakshmi_S](https://experienceleaguecommunities.adobe.com/t5/user/viewprofilepage/user-id/11077056) 为 2021 年度社区成员，以这种公开的方式对他们的工作表示肯定。

* [2022 年 1 月的 Experience League 内容](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/experience-league-content-for-month-of-january-2022/td-p/437137)

   [Experience League 中发布的所有 Experience Manager 内容列表](https://adobe.ly/3tuGuRH)

### Experience Manager 的新课程和教程 {#tutorials-aem}

过去一个月发布的新视频、教程及课程。

| 发布日期 | 名称 | 类型 | 描述 | 应用程序 |
| -----------| ---------- | ---------- | ---------- | ----- |
| 2022 年 1 月 | [使用 Adobe Developer App Builder 扩展 Adobe Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/configuring-and-extending/app-builder/extending-aem-with-app-builder.html?lang=en) | 视频（多个） | 新的 Adobe Developer App Builder 为开发人员提供了一个可扩展性框架，便于扩展 AEM as a Cloud Service 功能。 | AEM as a Cloud Service |
| 2022 年 1 月 | [AEM as a Cloud Service 的 AEM Headless 快速设置](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/quick-setup/cloud-service.html) | 视频 | 观看 AEM Headless 快速设置。使用 WKND Site 示例项目中的内容以及一个通过 AEM Headless GraphQL API 使用内容的示例 React 应用程序 (SPA)，实际动手操作 AEM Headless。 | AEMas a Cloud Service |
| 2022 年 1 月 | [高级联网](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/networking/advanced-networking.html?lang=en) | 视频（多个） | 了解 AEM as a Cloud Service 如何提供三种用于管理与外部服务的连接的选项：灵活端口出口、专用出口 IP 地址和虚拟专用网络。AEM as a Cloud Service 中的 Cloud Manager 程序和环境一次只能使用一种类型的高级联网配置。 | AEMas a Cloud Service |
| 2022 年 1 月 | [使用关联的 AEM 内容扩充产品数据](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/content-and-commerce/storefront/authoring/enrich-product-associated-content.html?lang=en) | 视频 | 了解营销人员如何使用 Adobe Experience Manager 中的相关内容扩充产品数据。AEM 中的资产、[!UICONTROL 体验片段]和[!UICONTROL 内容片段]等内容可以与商业产品相关联。 | AEMas a Cloud Service |
| 2022 年 1 月 | [电子邮件服务](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/networking/examples/email-service.html?lang=en) | 视频 | 通过将 AEM 的 `DefaultMailService` 配置为使用高级联网出口端口，从 AEM as a Cloud Service 发送电子邮件。 | AEMas a Cloud Service |
| 2022 年 1 月 | [Workfront 增强型连接器基础知识](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/basics.html?lang=en) | 视频 | 了解 Adobe Workfront 和 Experience Manager Assets 增强型连接器的基础知识。还可以了解 [Project 文件夹](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/project-folders.html?lang=en)。 | AEM Assets Service 和 Workfront |
| 2022 年 1 月 | [AEM Sites 快速入门 - 快速网站创建](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-wknd-tutorial-develop/site-template/overview.html?lang=en) | 视频（多个） | 了解如何使用低代码方法通过快速网站创建和预定义网站模板在 Adobe Experience Manager 中创建您的第一个网站。 | AEM Sites |
| 2022 年 1 月 | [非标准端口上的 HTTP/HTTPS 连接，实现灵活端口出口](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/networking/examples/http-on-non-standard-ports-flexible-port-egress.html?lang=en) | 视频（多个） | 了解如何将非标准端口（非 80/443）上的 HTTP/HTTPS 连接代理出 AEM as a Cloud Service。 | AEMas a Cloud Service |
| 2022 年 1 月 | [添加图标以指示活动和已完成的选项卡](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/ui-tips-and-tricks/active-complete.html?lang=en) | 视频 | 了解在使用带有左侧选项卡导航的自适应表单时，如何显示图标来指示选项卡的状态。 | AEM Forms |
| 2022 年 1 月 | [Adobe Asset Link 设置](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/adobe-asset-link/setup.html?lang=en) | 视频 | 通过使创意和营销团队更容易在内容创建过程中协作使用资产，从而迅速对您的组织产生影响。 | AEM Assets |
| 2022 年 1 月 | [AEM Commerce as a Cloud Service 快速入门](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/content-and-commerce/storefront/getting-started.html?lang=en) | 视频 | 了解营销人员如何使用 Adobe Experience Manager 中的相关内容扩充产品数据。AEM 中的资产、体验片段和内容片段等内容可以与商业产品相关联。 | AEMas a Cloud Service |
| 2022 年 1 月 | [AEM Sites 快速入门 - 快速网站创建](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-wknd-tutorial-develop/site-template/overview.html) | 视频 | 了解如何使用低代码方法通过快速网站创建和预定义网站模板在 Adobe Experience Manager 中创建您的第一个网站。 | AEM Sites |
| 2022 年 1 月 | [使用关联的 AEM 内容扩充产品数据](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/content-and-commerce/storefront/authoring/enrich-product-associated-content.html) | 视频 | 了解营销人员如何使用 Adobe Experience Manager 中的相关内容扩充产品数据。AEM 中的资产、体验片段和内容片段等内容可以与商业产品相关联。 | AEMas a Cloud Service |

{style=&quot;table-layout:auto&quot;}

### Experience Manager 发行信息

所有的 Experience Manager 发行说明均保留在以下页面：

* [Experience Manager as a Cloud Service 版本信息](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=en)
* [Experience Manager Cloud Manager 发行说明](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=zh-Hans)
* [Automated Forms Conversion Service 发行说明](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=zh-Hans)
* [Experience Manager 6.5 Service Pack 发行说明](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=en)
* [Experience Manager 6.4 Cumulative Fix Pack 发行说明](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=zh-Hans)
* [Experience Manager Assets Dynamic Media 发行说明](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=zh-Hans)
* [Experience Manager Brand Portal 发行说明](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=zh-Hans)
* [Experience Manager 桌面应用程序发行说明](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=zh-Hans)
* [Experience Manager Dispatcher 发行说明](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=zh-Hans)
* [Adobe Primetime 发行说明](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html?lang=zh-Hans)
* [Livefyre 发行说明](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=zh-Hans)

### Experience Manager 的其他帮助资源

* [Experience Manager Sites as a Cloud Service 指南](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/home.html?lang=en)
* [Cloud Manager 用户指南](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=en)
* [Experience Manager 6.5 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=zh-Hans)
* [Experience Manager 6.4 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=zh-Hans)
* [Experience Manager 6.3 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=zh-Hans)
* [Experience Manager 6.2 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=zh-Hans#previous-updates)
* [Experience Manager 文档的旧版本](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Dynamic Media Classic 帮助主页](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=zh-Hans)
* [Experience Manager 文档：最近的更新](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=zh-Hans#aem-as-a-cloud-service)

## Adobe Experience Manager 的 XML 文档 {#xml-doc}

Adobe Experience Manager 的 XML 文档是部署在 AEM 上的应用程序。这是一个功能强大的企业级组件内容管理解决方案 (CCMS)，可在 Adobe Experience Manager 中启用原生 DITA 支持，使 AEM 能够处理基于 DITA 的内容创建和交付。详细了解 [AEM 的 XML 文档](https://www.adobe.com/products/xml-documentation-for-experience-manager/features.html)。

### Adobe Experience Manager 的 XML 文档的新教程 {#tutorials-xml-doc}

为 Adobe Experience Manager 的 XML 文档发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 1 月 | [XML 文档发布](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/tutorials/release-info/latest-release-info.html?lang=en) | 视频 | 了解 Adobe Experience Manager 的 XML 文档，这是一个功能强大的企业级组件内容管理解决方案 (CCMS)。该解决方案在 Adobe Experience Manager 中启用原生 DITA 支持，使 AEM 能够处理基于 DITA 的内容创建和交付。 |
| 2022 年 1 月 | [使用 AEM 的 XML 文档生成输出](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/videos/output-generation/overview.html?lang=en) | 视频和文章 | 了解地图仪表板、报表、带有基线和条件的发布等内容。 |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/magento.png) [!DNL Adobe Commerce] {#magento}

有关 Adobe Commerce 发行说明，请参阅以下链接：

* [Adobe Commerce 和 Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [适用于 Adobe Commerce 的云套件](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### 新的 Adobe Commerce 教程 {#tutorials-commerce}

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 1 月 | [Business Intelligence](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/getting-started/business-intelligence/1-overview.html) | 视频（多个） | 从概述开始，全面了解 Business Intelligence，这是一个已针对所有 Adobe Commerce 和 Magento Open Source 商家进行优化的完整解决方案。 |
| 2022 年 1 月 | [用户、角色和权限](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/admin/users-roles-permissions.html) | 视频 | 了解如何为每个用户创建单独的用户帐户，并根据他们的业务需求分配受限制的访问权限。 |
| 2022 年 1 月 | [双重身份验证](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/admin/two-factor-authentication.html) | 视频 | 了解双重身份验证 (2FA) 如何防止对您的数据进行未授权访问。Adobe Commerce 和 Magento Open Source 支持来自多个提供商的双重身份验证方法。 |
| 2022 年 1 月 | [添加网站、商店和商店视图](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/admin/add-websites-stores-views.html) | 视频 | 了解每个 Adobe Commerce 和 Magento Open Source 安装如何支持网站、商店和商店视图的层次结构。根据您的业务需求构建和扩展此层次结构。 |
| 2022 年 1 月 | [更改商店 URL](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/admin/change-store-url.html) | 视频 | 了解如何更改商店的基础 URL。（视频中的内容反映了 2.1.0 版本。） |
| 2022 年 1 月 | [设置商店网站地图](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/admin/site-map-setup.html) | 视频 | 了解如何轻松地将网站地图添加到您的 Commerce 商店。 |
| 2022 年 1 月 | [促销价格规则](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/admin/promotions-price-rules.html) | 视频 | 了解如何建立产品关系，并使用价格规则根据各种条件触发折扣。 |
| 2022 年 1 月 | [创建页面](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/frontend-development/create-new-page.html) | 视频 | 了解如何创建一个返回带有一个参数的 JSON 的页面。 |
| 2022 年 1 月 | [添加 JavaScript 模块](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/frontend-development/add-javascript-module.html) | 视频 | 了解如何开发一个提供问候语“Hello World”的简单 JS 模块。 |
| 2022 年 1 月 | [Page Builder 概述](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/admin/page-builder-overview.html) | 视频 | 了解如何通过 Page Builder 轻松使用自定义版面创建内容丰富的页面，以增强您的视觉叙事能力，并提高客户参与度和忠诚度。 |
| 2022 年 1 月 | [向数据库中添加表](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/backend-development/add-new-db-table.html?lang=en) | 视频 | 了解 Commerce 中的特殊机制，该机制使您能够创建数据库表、修改现有表以及向表中添加数据，例如必须在安装模块时添加的设置数据。 |
| 2022 年 1 月 | [创建模块](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/backend-development/create-module.html) | 视频 | 模块是 Commerce 的结构元素 – 整个系统建立在模块之上。通常，创建自定义项的第一步是构建模块。 |
| 2022 年 1 月 | [创建产品属性](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/backend-development/add-product-attribute.html) | 视频 | 了解如何添加产品属性，这是 Commerce 中最常用的操作之一。属性是解决许多与产品相关的实际任务的强大方法。 |
| 2022 年 1 月 | [依赖项注入示例](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/backend-development/dependency-injection.html) | 视频 | 了解依赖项注入，这是一种设计模式，允许对象 A 向外部对象 B 声明其依赖项，而对象 B 则提供这些依赖项。A 声明的依赖项通常是类接口，而 B 提供的依赖项是这些接口的具体实现。 |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/target.png) [!DNL Adobe Target] {#target}

上次更新日期：**2022 年 1 月 10 日**

请参阅 [Target 发行说明](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=en)了解最新发行信息。

## ![图标](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign 提供了一种直观、自动的方式，以通过在线和离线营销渠道来交付一对一的消息。您现在可以利用根据客户习惯和偏好确定的体验，来预测客户的需求。

### 最新营销活动产品版本

详细了解最新发布的功能、改进和修复：

* [Campaign v7.2 发布](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html)

### [!DNL Campaign] 的新教程和课程 {#tutorials-campaign}

为 Adobe Campaign 发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 | 版本 |
| ------| ----- | -----| ------ | --- |
| 2022 年 1 月 | [部署临时电子邮件投放模板](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/using-delivery-templates/deploy-ad-hoc-email-delivery-template.html?lang=en) | 视频 | 了解如何部署临时电子邮件投放模板，并说明电子邮件投放和投放工作流之间的区别。 | Campaign v8 |
| 2022 年 1 月 | [设置投放模板属性](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/using-delivery-templates/set-delivery-template-properties.html?lang=en) | 视频 | 了解如何设置投放模板属性并详细说明每个属性。 | Campaign v8 |
| 2022 年 1 月 | [为营销活动配置批准](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/process-management/create-approvals-and-validation-workflows/configure-approvals-for-campaigns.html?lang=en) | 视频 | 了解如何在营销活动级别配置批准和审阅人。 | Campaign v8 |
| 2022 年 1 月 | [在工作流中创建批准流程](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/process-management/create-approvals-and-validation-workflows/create-approval-process-in-a-workflow.html?lang=en) | 视频 | 了解如何在工作流中创建批准流程，以便在启动投放之前审核并批准定位选择逻辑。 | Campaign v8 |
| 2022 年 1 月 | [为投放配置批准](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/process-management/create-approvals-and-validation-workflows/configure-approvals-for-deliveries.html?lang=en) | 视频 | 了解如何在投放级别配置批准和审阅人。 | Campaign v8 |
| 2022 年 1 月 | [具有 FFDA 的 API 暂存机制](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/data-management/api-staging-mechanism.html?lang=en) | 视频 | 了解具有完全 FDA 的 API 暂存机制如何工作。了解为何使用暂存、Adobe Campaign 中暂存的主要原则以及如何为自定义表激活暂存机制。 | Campaign v8 |

{style=&quot;table-layout:auto&quot;}

### 营销活动帮助资源

* Adobe Campaign v8：[文档](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/whats-new.html?lang=zh-Hans) — [《实施指南》](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=zh-Hans)
* Adobe Campaign Standard：[Campaign Standard 文档](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=zh-Hans) — [操作方法视频](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=zh-Hans) — [发行计划](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=zh-Hans) — [最新文档更新](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=zh-Hans)
* Adobe Campaign Classic：[Campaign Classic v7 文档](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) — [操作方法视频](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=zh-Hans) — [最新文档更新](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=zh-Hans)
* Adobe Campaign 控制面板：[文档](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=zh-Hans) - 有关 [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=zh-Hans)/[Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=zh-Hans) 的操作方法视频

## ![Icon](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

借助 Journey Optimizer，您可以通过单个应用程序为数百万客户管理预定的全渠道营销活动和一对一互动时刻，整个历程都通过智能决策和见解得到了优化。

### 最新 Journey Optimizer 产品版本

有关最新的功能、改进和修复的详细信息，请参见 [Journey Optimizer 发行说明](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=zh-Hans)。

### [!DNL Journey Optimizer] 的更多资源

* [Journey Optimizer 文档](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html) — [发行说明](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) — [操作方法视频](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=zh-Hans)
* [Decision Management 文档](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started/starting-offer-decisioning.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) — [操作方法视频](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/introduction-to-offer-decisioning.html?lang=zh-Hans) — [最新文档更新](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=zh-Hans)

## ![图标](/assets/experience_platform_appicon_24.png) [!DNL Adobe Journey Orchestration] {#journey-orch}

凭借 Experience Platform，可以实时智能化预测每位客户的需求，从而实现跨体验渠道大规模编排客户历程。

### 最新 [!DNL Journey Orchestration] 产品版本

有关最新的功能、改进和修复的详细信息，请参阅[[!DNL Journey Orchestration] 发行说明](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=zh-Hans)。

#### [!DNL Journey Orchestration] 的更多资源

* [Journey Orchestration 文档](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) — [操作方法视频](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=zh-Hans) — [最新文档更新](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=zh-Hans)

## ![图标](/assets/marketo.png) [!DNL Adobe Marketo Engage] {#marketo}

[!DNL Marketo Engage] 是一个全面的应用程序，适用于寻求通过积极参与复杂购买过程的每个阶段而改善客户体验的销售线索管理和 B2B 营销人员。

### 核心 Marketo Engage 更新

有关最新的发布计划信息和发行说明，请参阅[!DNL Marketo Engage] [发布计划](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=zh-Hans)。

## ![图标](/assets/workfront.png) [!DNL Adobe Workfront] {#workfront}

Adobe [!DNL Workfront] 是一个统一的工作管理应用程序，可用于分享创意、创建内容、管理复杂的流程以及将工作做到尽善尽美。

请参阅[[!DNL Workfront] 版本](https://one.workfront.com/s/product-releases)页面，查看所有产品的最新信息综述。

## ![图标](/assets/advertising-cloud.png) Adobe Advertising Cloud {#adcloud}

[!DNL Adobe Advertising Cloud] 的发行说明。

* [ [!DNL Advertising Cloud] 中的新增功能](#adcloud-all)
* [ [!DNL Advertising Cloud DSP] 中的新增功能](#adcloud-dsp)
* [ [!DNL Advertising Cloud Search] 中的新增功能](#adcloud-search)
* [ [!DNL Advertising Cloud] 的新教程](#tutorials-ad-cloud)

### [!DNL Advertising Cloud] 中的新增功能 {#adcloud-all}

上次更新日期：**2021 年 10 月 27 日**

| 功能 | 描述 |
| ------- | ----------- |
| 适用于 Advertising Cloud 的 Analytics | 如果您的组织需要从使用旧版 Adobe Analytics `visitorAPI.js` 库转为使用 Adobe Experience Platform 库 (`alloy.js`) 来收集数据，则您必须进行一些更改来支持 ID 拼接。请参阅[将 [!DNL Last Event Service] JavaScript 库与 Adobe Experience Platform 结合使用 [!DNL Web SDK]](https://experienceleague.adobe.com/docs/advertising-cloud/integrations/analytics/planning/web-sdk.html?lang=zh-Hans)。 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Advertising Cloud DSP] 中的新增功能 {#adcloud-dsp}

上次更新日期：**2021 年 10 月 27 日**

| 功能 | 描述 |
| ------- | ----------- |
| 自定义报表 | 您现在可以为自定义报表创建和管理 [!DNL Amazon S3] 以及不同类型的 FTP 投放位置（称作 *[!DNL report destinations]*）。在配置报表目标后，您可以将每个新的自定义报表设置为发送到单一目标类型的一个或多个位置，或发送给电子邮件收件人。更新 [!DNL Amazon S3] 和 FTP 凭据将不会中断报表投放。<br><br>您现有的报表仍会发送给指定的电子邮件收件人。要配置针对不同报表目标的投放，请创建具有新目标的报表。 |
| [!UICONTROL 包]、[!UICONTROL 投放位置]和[!UICONTROL 广告]视图 | 在查看一天的数据时，趋势图现在包含每小时数据。将光标悬停在任意小时上可查看该小时的数据。 |
| [!UICONTROL 投放位置] | 投放[!UICONTROL 检查器]现在包含[!UICONTROL 库存]选项卡，该选项卡显示投放的所有交易及其关联量度。使用这些信息可快速做出调整或解决问题，而无需生成自定义报表。 |
| [!UICONTROL 广告] | （有权在其广告中包含 Clearcastclock 编号的用户）如果您使用附加到另一个广告的时钟编号，则 DSP 将不再显示错误。**注意：**&#x200B;最佳实践是为每个视频广告使用唯一的时钟编号。否则，发布者不会批准所有广告。 |
| [!UICONTROL 交易 ID] | 用户界面中的[!UICONTROL 交易 ID]设置和其他位置反映了 [!DNL Magnite] SSP 的新品牌化：<br><ul><li>SSP [!DNL Tremor] ([!DNL Telaria]) 现在为 [!DNL Magnite CTV]。</li><li>在接下来的几周内，[!DNL Rubicon] 将更改为 [!DNL Magnite DV+]，其中 [!DNL DV+] 代表显示、视频和其他格式，例如音频。</li></ul> |
| [!DNL Freewheel] 以编程方式保证交易 | 您现在可以从[!UICONTROL 广告]视图中查找 [!DNL Freewheel] 以编程方式保证交易的广告状态。之前，您只能从[!UICONTROL 交易]视图中查看状态。 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Advertising Cloud Search] 中的新增功能 {#adcloud-search}

上次更新日期：**2021 年 10 月 7 日**

| 功能 | 描述 |
| ------- | ----------- |
| [!UICONTROL 报告]、[!UICONTROL 通知中心] | （10 月 9 日版）Advertising Cloud Search 在自定义报告或计划报告完成或失败时发送的所有报告电子邮件通知现在都由[!UICONTROL 通知中心]处理。默认情况下为报告启用电子邮件通知和 Web 通知，但您可以选择更改通知设置。更改后：<ul><li>电子邮件收件人仅限于已注册的、经过身份验证的 Advertising Cloud Search 用户且有权访问广告商帐户的用户。此功能可确保不会将机密数据发送给未经授权的用户。</li><li>电子邮件的格式和内容使用[!UICONTROL 通知中心]模板，其中包括报告的更多详细信息，并包括所有报告格式的直接下载链接。</li><li>报告通知是[!UICONTROL 通知中心]中一种新的通知类型，具有自己的通知偏好设置。</li></ul>如果您使用任何自动化方法从电子邮件通知中提取报告，您可能需要更新筛选逻辑以确保过程的连续性。 |
| 广告见解 | Beta 模式中提供了其他见解。 |

{style=&quot;table-layout:auto&quot;}

### Advertising Cloud 的新教程 {#tutorials-ad-cloud}

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 1 月 | [Advertising Cloud 教程](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/dsp/intro.html?lang=en) | 视频 | 提供了五个有关 Advertising Cloud DSP 的新视频教程。 |

## ![图标](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

为 Adobe Document Cloud 发布的新视频、教程或课程。

### Document Cloud 的新课程和教程 {#tutorials-doc-cloud}

为 Adobe Campaign 发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 1 月 | [增强 PDF](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/enhance.html?lang=en) | 视频 | 在这个实践教程中，学习如何通过添加图形增强功能和自动编号来转换您的 PDF。 |
| 2022 年 1 月 | [使用 Acrobat DC 和 Microsoft® 365 更智能地工作](https://experienceleague.adobe.com/?recommended=Acrobat-U-1-2021.microsoft365) | 课程 | 发现 [!DNL Microsoft® 365] 和 [!DNL Acrobat DC] 内部功能强大的 PDF 工具，以替换过时、损坏的文档工作流。了解如何实现手动文档流程自动化以避免延误和出错，提高安全性和工作效率，并提供卓越的客户和员工体验 — 所有这些都在您已经使用的 Microsoft® 和 Acrobat 工具中。 |

{style=&quot;table-layout:auto&quot;}

有关 Document Cloud 的帮助，请参阅：

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=zh-Hans)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=zh-Hans)
* [Document Cloud 学习与支持](https://helpx.adobe.com/cn/support/document-cloud.html)

## ![图标](/assets/creative-cloud-24.png) Adobe Creative Cloud 企业版 {#creative-cloud}

有关最新教程，请参阅 [Creative Cloud 企业版教程](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=zh-Hans)。
