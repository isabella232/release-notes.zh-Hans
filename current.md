---
title: Adobe Experience Cloud 发行说明
description: Experience Cloud 发行说明模板
doc-type: release notes
last-update: May 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 8ed0b98440cd68357d792abaec2a99dccbfa47dc
workflow-type: tm+mt
source-wordcount: '4766'
ht-degree: 38%

---


# 提前访问- Adobe Experience Cloud发行说明- 2020年5月

![横幅](/assets/experience-cloud-banner-3.png)

本页提供中的新功能、修复和重要声明 [!DNL Adobe Experience Cloud]。 解决方案发布日期可能不同。 请经常回访以获取最新更新。

>[!IMPORTANT]
>
>本页包含预发行内容，可能在2020年5月21日之前有所更改。 此后发布的新信息将随添加日期一起记录。

>[!NOTE]
>
>若要通过电子邮件接收有关即将发行的版本的通知，请订阅 [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html)。

**发行日期：2020 年 5 月**

最新更新： **2020年5月16日**

* [Adobe 系统状态](#status)
* [Experience Cloud 界面](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/zh-Hans/target/using/release-notes/target-release-notes.html)（链接到 Target 帮助页面）
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/cn/primetime/user-guide.html)（链接到 Primetime 帮助页面）

需要帮助？ 访 [问[!DNL Adobe Experience League]](https://experienceleague.adobe.com/#home) ，查找Adobe精选的课程、技术文档、快速答案、社区见解和有导师指导的培训。

## ![图标](/assets/adobe.png) Adobe 系统状态 {#status}

[!UICONTROL Adobe 系统状态]提供关于 Adobe 云产品与服务中断和维护事件的详细信息、状态更新以及电子邮件通知。请访问 [status.adobe.com](https://status.adobe.com/) 查看。

发行日期：**2020 年 5 月 21 日**

**新增功能**

* 凭借您的 Adobe ID，您可以订阅粒度更细的事件通知，具体可达到产品和加载项级别。为了帮助您更快地设置订阅，自我订阅流程现在建议根据您的产品权利选择产品和服务。 这应会减少您收到的电子邮件数量，并在您的收件箱中发送更相关的通知。 要开始使用，请访问 [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit)。

**当前可用的新增功能和增强功能**

| 功能 | 描述 |
| -----------| ---------- |
| 改进了订阅和通知用户体验 | <ul><li>[!DNL Marketo Engage] 现在，区域位置会根据所选产品的列表进行筛选。</li><li>[!DNL Marketo Engage] 电子邮件通知与用户的区域、位置和环境首选项相关。</li></ul> |
| 事件订阅确认 | <ul><li>现在，订阅持续的单个事件更新时，您可以收到电子邮件确认。</li></ul> |
| 全局导航可用性增强 | <ul><li>在顶级导航菜 `Adobe.com` 单上提供一致的用户体验。</li></ul> |

## ![图标](/assets/ec_appicon_24.png) Experience Cloud 界面 {#ecloud}

Experience Cloud界面的常规更新。

**统一的产品域**

Adobe一直在更新域和界面头，以统一和改进您在所有Experience Cloud应用程序中的体验。 这些增强功能旨在以细微而重要的方式简化您的体验。这些增强不会更改您当前的工作流。

更新包括：

* 新应用程序URL：`experience.adobe.com/<application name>`：
   * 所有产品最终都将采用此 URL 模式。寻找即将在本月内生效的新 URL。
   * 浏览器支持：支持的浏览器包括 [!DNL Microsoft Edge]、[!DNL Google Chrome]、[!DNL Firefox]、[!DNL Safari] 和 [!DNL Opera]（最新版本）。**注意：**&#x200B;尽管 Experience Cloud 界面支持这些浏览器，但单个应用程序可能不会支持每个浏览器。（例如，[Analytics](https://docs.adobe.com/content/help/zh-Hans/analytics/admin/sys-reqs.html) 不支持 [!DNL Opera]，[Target](https://docs.adobe.com/help/zh-Hans/target/using/implement-target/before-implement/supported-browsers.html) 不支持 [!DNL Safari]。）
   * （仅限 [!DNL Safari]）域更改可能导致 [!DNL Safari] 中出现 Cookie 问题。取消选中 [!DNL Safari] 隐私首选项中的&#x200B;_阻止跨站跟踪_，将支持跨域的 Cookie（以及所有跨站点体验），并允许 Experience Cloud 在这个新的域上正常运行。
* 更轻松地在组织之间切换，或切换到其他应用程序。
* 改进了产品帮助：[!UICONTROL Experience League] 已集成到产品中，以便帮助搜索还包括来自社区论坛及视频内容的答案。此更改会简化对更多内容的访问，并有助于您充分利用 Experience Cloud。此外，单击&#x200B;**[!UICONTROL 帮助]** > **[!UICONTROL 反馈]**，可报告问题或与 Adobe 分享您的想法。

以下应用程序使用新的experience.adobe.com域：

| 应用程序或服务 | Domain |
| -----------| ---------- |
| Experience Cloud主页 | `experience.adobe.com/home` |
| Adobe Target | `experience.adobe.com/target` |
| Adobe Audience Manager | `experience.adobe.com/audience-manager` |
| Adobe Launch | `experience.adobe.com/launch` |
| Adobe Experience Platform | `experience.adobe.com/platform` |
| 旅程管理 | `experience.adobe.com/journeys` |
| 客户历程分析 | `experience.adobe.com/platform/analytics` |
| Adobe Campaign 控制面板 | `experience.adobe.com/controlpanel` |
| Cloud Manager | `experience.adobe.com/cloud-manager` |
| Places Service | `experience.adobe.com/places` |
| Software Distribution | `experience.adobe.com/downloads` |
| Admin Tool（测试版） | `experience.adobe.com/admin` |

## ![图标](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

[!DNL Experience Platform,] 的发行说明，包括 [!DNL Experience Platform Launch,] [!UICONTROL Journey Orchestration]、[!UICONTROL Offers]、[!UICONTROL People]、[!UICONTROL Places]、[!UICONTROL Mobile Services] 和安全公告。

### 界面增强

Updated: **May 15, 2020**

[!DNL Adobe Experience Platform] 将发布对域和标题栏的更新，以改进您的体验并与其他Experience Cloud应用程序统一。 更新包括：

* 更轻松地在组织之间切换，或切换到其他应用程序。
* 改进了用户帮助，包括“帮助”菜单中的特色文章和上下文相关文档。
* 能够提供有关Experience Platform和文件支持票证的反馈。

See [Experience Platform release notes](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md) for more information.

### 客户属性——新文档

Updated: **May 15, 2020**

* [CCPA的客户属性支持](https://docs.adobe.com/content/help/en/core-services/interface/customer-attributes/ccpa.html) (California Consumer Privacy Act)
* [GDPR的客户属性支持](https://docs.adobe.com/content/help/en/core-services/interface/customer-attributes/gdpr.html) （一般数据保护规定）

### Journey Orchestration {#journey}

凭借 Adobe Experience Platform，可以实时智能化预测每位客户的需求（无论其旅程通达何处），从而实现跨体验渠道大规模编排客户历程。

* [文档](https://docs.adobe.com/content/help/zh-Hans/journeys/using/journey-orchestration-home.html)
* [发行说明](https://docs.adobe.com/content/help/zh-Hans/journeys/using/release-notes/release-notes.html)
* [操作方法视频](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### 其他 Experience Platform 发行信息

* [Experience Platform Launch 发行说明](https://docs.adobe.com/content/help/zh-Hans/launch/using/intro/release-notes/current.html)。
* [Experience Platform 发行说明](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [安全公告与建议](https://helpx.adobe.com/cn/security.html)（所有 Adobe 产品）

## ![图标](/assets/analytics.png) [!DNL Analytics] {#analytics}

* [客户旅程分析的新增功能](#cust-journey)
* [Adobe Analytics 中的新增功能](#aa-features)
* [Analytics 管理员的重要注意事项](#aa-notices)
* [AppMeasurement](#appm)
* [新的 Analytics 教程](#tutorials-analytics)

### 客户旅程分析的新增功能 {#cust-journey}

| 功能 | 描述 |
| -----------| ---------- |
| [!UICONTROL 客户旅程分析]: 全球可用性 | 为EMEA [!UICONTROL 和APAC的客户] 提供客户旅程分析。 |
| [!UICONTROL 客户旅程分析]: 支持Adobe [!UICONTROL Experience Platform沙箱] | 允许您选择特定 [!UICONTROL 的Adobe Experience Platform沙箱] ，以从中构建CJA连接。 [了解更多...](https://docs.adobe.com/content/help/zh-Hans/analytics-platform/using/cja-connections/create-connection.html) |

### Adobe Analytics 中的新增功能 {#aa-features}

<!-- Bulk Ingest: Enables you to ingest batches of Analytics data. Useful for server-side and offline data. Learn more...
First-Party Domains Available in China RDC: Enables customers with a cn domain to request a 1st-party domain for use inside of Mainland China. Learn more... -->

| 功能 | 描述 |
| -----------| ---------- |
| 对Adobe Experience Platform Edge [!UICONTROL Network的分析支持] | 允许您使用单个标签将数据发送到多个Adobe解决方案，如Adobe Analytics、Adobe目标、Adobe受众管理器、Adobe Experience Platform Data Lake、统一用户档案和Experience Cloud ID服务。 [了解更多...](https://docs.adobe.com/content/help/zh-Hans/experience-platform/edge/home.html) |
| [!UICONTROL Adobe Analytics仪表板] | [!UICONTROL Adobe Analytics仪表板] 是一款移动应用程序，用户可随时随地访问Adobe Analytics的洞察。 此应用程序面向寻求随时访问关键指标的管理人员。 它允许访问精选的交互式记分卡，并且将可用于iOS和Android操作系统。 [了解更多...](https://docs.adobe.com/content/help/en/analytics/analyze/mobapp/home.html) |
| [!UICONTROL 工作区][!UICONTROL ：从空白状态自动构建“自由格式表”] | Previously, you could not drop components directly into a blank project or blank panel; you had to add a [!UICONTROL Freeform Table] first. You can now drop components directly into a blank project or panel, and a [!UICONTROL Freeform Table] is automatically built for you in a recommended format. 此外，还改进了混合组件类型（如维度和度量）在一起放入空白的自由形式表时的处理方式。 |

#### Adobe Analytics修复

* Fixed an issue that caused missing [!DNL Analytics] segment data in Audience Manager. (AN-206221)
* 修复了[!UICONTROL 数据源]处理显示错误日期的问题。(AN-213604)
* 修复了分类文件无法正确上传到 FTP 的问题。(AN-214102)
* 修复了 API 方法 `Segments.Get` 不返回完整响应的问题。(AN-206210)
* 修复了表格行项目在 [!DNL Workspace] PDF 下载中转换为特殊字符的问题。(AN-196153)
* 修复了 Adobe Analytics API 1.4 调用 `visattrcustomeridcustomerattributes` 无法正常工作的问题。(AN-186873)
* 修复了报表中显示数据，但[!UICONTROL 数据馈送]中缺失数据的问题。(AN-211923)
* 修复了无法复制[!UICONTROL 产品配置文件]权限的问题。(AN-211113)
* Fixed an issue where users with Federated IDs were not able to log in to [!UICONTROL Report Builder]. (AN-207750)
* 修复了 [!UICONTROL AdWords] 数据不在 [!UICONTROL Advertising Analytics] 中显示的问题。(AN-213249)
* 修复了分类数据未在趋势视图中显示的问题。(AN-212761)
* 修复了导致[!UICONTROL 区段管理器]中发布的区段计数不正确的问题。(AN-213374)
* 修复了计算量度 **[!UICONTROL 编辑器中的“显示向上趋势为]** ..” [!UICONTROL 选项存在的问题] -在应用过滤器时该选项不起作用。 (AN-214223)
* 修复了分类导入 [!UICONTROL 和导出] 的多个问题。 (AN-213488、AN-215309、AN-216345、AN-215307、AN-216671)
* 修复了分类规则 [!UICONTROL 生成器的多个问题]。 (AN-213826、AN-213550、AN-213095)
* 修复了数据源 [!UICONTROL 处理的] 问题。 (AN-218083、AN-213604、AN-214102、AN-215485、AN-215339、AN-212911、AN-217551、AN-217947、AN-219018、AN-214691、AN-218401)
* 修复了FTP连接问题。 (AN-115525)
* 修复了多 [!DNL Analytics] 个 [!UICONTROL 数据源问题] 。 (AN-176769、AN-160480、AN-211923、AN-204286、AN-212977、AN-214528、AN-215080、AN-217784、AN-219093、AN-218817、AN-217798、AN-218267、AN-218382)
* 修复了数据 [!UICONTROL 仓库请求] 。 (AN-181836)
* 修复了PDF下载的Workspace [!UICONTROL 项目] （其中值被转换为特殊字符）中的问题。 (AN-196153)
* Fixed an issue with being unable to copy [!UICONTROL Product Profile] permissions in [!UICONTROL Admin Console]. (AN-211113)
* 修复了计算量度中的时间格式为负值时被中断的问题。 (AN-210900)
* 修复了阻止用户更改静态行度 [!UICONTROL 量的归因] 模型的问题。 (AN-207872)
* 修复了导致计划报 [!UICONTROL 表生成器] 卡在排队状态的问题。 (AN-215317)
* 修复了 [!UICONTROL ExactTarget数据连接器]。 (AN-210794)
* 修复了批量摄取 [!UICONTROL API中的延迟问题]。 (AN-210165)
* 修复了用户无法使用Federated ID登录 [!UICONTROL 到Report Builder] 的问题。 (AN-207750)
* 修复了广告分 [!UICONTROL 析中阻止] 数 [!DNL Google AdWords] 据显示的问题。 (AN-213249)
* 修复了阻止“工作 [!UICONTROL 区] ”“ [!UICONTROL 已查看] 的项目”事件显示在日志中的问题。 (AN-214134)
* 修复了在Workspace中更改日期范围并选择“应 [!UICONTROL 用至] 所 **[!UICONTROL 有面板”时发生的问题]**。 某些面板中的日期没有更改。 (AN-214944)
* 修复了无法创建或编辑警报的问题。 (AN-215920)
* 修复了Workspace中所有动态日期范围 [!UICONTROL 显示] 错误日期的问题，该日期范围由于一周的第一天偶尔从星期一切换到星期日。 (AN-218835)

#### 其他Adobe Analytics修复

AN-101871、AN-115525; AN-123869; AN-152580; AN-160480; AN-178128; AN-186907; AN-199299; AN-201342; AN-201397; AN-204286; AN-204518; AN-206045; AN-206948; AN-208607; AN-209486; AN-210743; AN-211550; AN-211539; AN-211826; AN-211943; AN-212130; AN-212151; AN-212653; AN-212673; AN-212709; AN-212833; AN-212961; AN-212977; AN-213095; AN-213422; AN-213450; AN-213490; AN-213752; AN-213827; AN-214094; AN-214153; AN-214214; AN-214234; AN-214253;  AN-214255; AN-214343; AN-214355; AN-214401; AN-214427; AN-214528; AN-214642; AN-214691; AN-214772; AN-214793; AN-214924; AN-215017; AN-215080; AN-215212; AN-215312; AN-215377; AN-215402; AN-215545; AN-215905; AN-215963; AN-216447; AN-216676; AN-216880; AN-216999; AN-217245; AN-218450; AN-218899; AN-219487; AN-219677

### [!DNL Analytics] 管理员的重要注意事项 {#aa-notices}

| 注意事项 | 添加或更新日期 | 描述 |
| -----------| ---------- | ---------- |
| 在[!UICONTROL 工作区]中更改[!UICONTROL 登入/退出]的计算方式 | 2020 年 4 月 7 日 | 在 [!UICONTROL Analysis Workspace] 中，从 2020 年 3 月起，我们更改了&#x200B;_无_&#x200B;值与[!UICONTROL 登入/退出]的交互方式。Because you can now turn _Nones_ on and off in [!UICONTROL Analysis Workspace], we apply the _None_ value after the entry or exit, whereas (for eVars) it used to be applied before entry or exit. 例如，假定访问的第一次点击对eVar没有任何价值，但第二次点击对eVar没有价值。 In [!UICONTROL Reports &amp; Analytics] the first hit will show as _Unspecified_ for the Entry, but in [!UICONTROL Analysis Workspace] it will show up as the value on the second hit. |
| **[!UICONTROL 转化级别]**&#x200B;设置生命周期终止 | 2020 年 3 月 3 日 | **[!UICONTROL 管理工具]** > **[!UICONTROL 报表包]** > **[!UICONTROL 常规帐户设置]**&#x200B;中无法正常运行的[转化级别](https://docs.adobe.com/content/help/zh-Hans/analytics/admin/admin-tools/general-acct-settings-admin.html)，将于 2020 年 3 月 12 日从该界面中删除。 |
| **[!UICONTROL 功能板存档]**&#x200B;生命周期终止 | 2020 年 3 月 27 日 | 自 2020 年 10 月起，在 [!UICONTROL Reports &amp; Analytics] 中，位于&#x200B;**[!UICONTROL 管理功能板]**&#x200B;下方的&#x200B;**[!UICONTROL 查看存档]**&#x200B;将不再可用。 |
| 停止支持 TLS 1.1 | 2019 年 10 月 3 日 | 我们一直不懈努力，致力于维持最高安全标准并提升客户数据安全。为此，Adobe Analytics 对 TLS 1.1 的支持将持续到 2020 年 3 月 31 日，在这之后将不再支持 TLS 1.1。 |
| 新的 Adobe Analytics 域 | 2019 年 12 月 18 日 | 自 2020 年 1 月 16 日起，Adobe Analytics 将开始转移到新域 - `https://experience.adobe.com/analytics.`<br>**注意：**这项更改适用于使用 Adobe ID 或 Enterprise ID 访问 Analytics 的所有用户。<ul><li>域更改可能会导致在 Safari 中加载 Analytics 时出现 Cookie 问题。取消选中 [!DNL Safari] 隐私首选项中的&#x200B;_阻止跨站跟踪_，将支持跨域的 Cookie（以及所有跨站点体验），并允许 Analytics 在这个新的 Adobe Experience Cloud 域上运行。您可以使用其他浏览器而不会出现任何问题，因为这项更改仅影响 [!DNL Safari] 用户。</li><li>[在特定情况下](https://docs.adobe.com/content/help/zh-Hans/analytics/analyze/activity-map/activity-map.html)，域更改可能会导致某些客户的 [!UICONTROL Activity Map] 停止工作。</li></ul> |
| 生命周期结束 - Analytics 旧版 API | 2020 年 1 月 9 日 | 2020 年 11 月，以下 Analytics 旧版 API 服务将停止使用并关闭。当前使用这些服务构建的集成将会停止工作。 <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>旧版 OAuth 身份验证（OAuth 和 JWT）</li></ul>我们提供了[旧版 API EOL 常见问题解答](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)，以帮助回答您的问题并提供有关如何继续的指导。使用这些服务的 API 集成可以迁移到 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 或 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。旧版 OAuth 帐户可迁移到 [Adobe IO](https://console.adobe.io/home?mv=email) Analytics 集成帐户，该帐户可用于访问 1.4 Analytics API 和 2.0 Analytics API。 |
| 圣何塞 FTP 中转站停止为伦敦和新加坡提供支持 | 2020 年 7 月 | 对于位于伦敦和新加坡的客户，我们将不再提供伦敦或新加坡与圣何塞数据中心 [ftp.omniture.com](ftp://ftp.omniture.com/) 之间的数据中转支持。<br/><ul><li>伦敦客户，请使用 [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>新加坡客户，请使用 [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Ad Hoc Analysis 生命周期终止 | 2018 年 8 月 6 日 | Adobe 宣布计划终止 Ad Hoc Analysis 生命周期。确定终止日期后，Adobe 会立即与大家共享此信息。有关更多信息，请参阅[探索工作区](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)。 |

### [!DNL AppMeasurement] {#appm}

请参阅 [AppMeasurement for Javascript 发行说明](https://docs.adobe.com/content/help/zh-Hans/analytics/implementation/appmeasurement-updates.html)。版本 2.20.0 于 2020 年 3 月 5 日发布。

### 新的 Analytics 教程 {#tutorials-analytics}

| 内容 | 描述 |
| -----------| ---------- |
| [分析工作区中的培训教程模板](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/navigating-workspace-projects/training-tutorial-template-in-analysis-workspace.html) | 分析 [!UICONTROL 工作区培训教程] ，将指导您逐步了解在Workspace中构建第一个项目的常用术语和 [!UICONTROL 步骤]。 |
| [将上个月和年度比较添加到趋势中](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/calendar-and-date-ranges/adding-prior-month-and-year-comparisons-to-trends.html) | 了解如何应用自定义日期范围，以在分析工作区中为任何指标创建月度和年度趋 [!UICONTROL 势比较]。 |
| [针对分析工作区的暗模式扩展](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/dark-mode-extension-for-analysis-workspace.html) | 启用Dark Reader Chrome扩展，将分析工作区变暗。 |
| [用于定义自定义调色板的色滴管扩展](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/color-eyedropper-extension-for-defining-custom-palettes.html) | 了解如何使用ColorPick EyeDropper Chrome扩展轻松找到您在Workspace项目中自定义调色板所需的十六进制 [!UICONTROL 值] 。 |

#### Analytics 帮助资源

* [Adobe Analytics教程](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics产品文档](https://docs.adobe.com/content/help/zh-Hans/analytics/landing/home.html)

## ![图标](/assets/audience-manager.png) Audience Manager {#aam}

受众管理器中的新增功能、修复、文档和教程。

### 用户界面更新

受众管理器将发布对域和标题栏的更新，以改进您的体验并与其他Experience Cloud应用程序统一。

* 更轻松地在组织之间切换，或切换到其他应用程序。
* 改进了用户帮助，包括“帮助”菜单中的特色文章和与上下文相关的视频。
* 能够提供有关Experience Platform和文件支持票证的反馈。
* 更简单的新URL模式。 将书签更新到新URL: `experience.adobe.com/audience-manager`.

这些更新仅对使用Adobe ID登录的用户可用。 要切换到Adobe ID登录名，请参阅 [管理Experience Cloud用户和产品](https://docs.adobe.com/content/help/zh-Hans/core-services/interface/manage-users-and-products/admin-getting-started.html)。

### Adobe受众管理器的新增功能和修复

| 功能 | 描述 |
| -----------| ---------- |  
| [批量管理工具(BAAAM)](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html#download) | 我们上传了一个新的批量管理工具工作表，它： <br><br><ul><li>允许您列表特征层次结构中的子文件夹(AAM-51528)</li><li>在提示输入与CRM ID（跨设备ID）关联的特征时检索度量(AAM-52135)</li><li>修复了韩文字符的语言编码问题(AAM-AAM-54006)</li></ul> |

**修复**

* 修复了趋势报告超时显示具有大量特征的文件夹的问题。 (AAM-54457)
* 修复了客户在特征创建／编辑工作流 [!UICONTROL 程中无] 法看到表达式构建器的问题。 (AAM-54255)
* 修复了在客户有机会阅读UI中的错误消息之前，其仅显示很短时间的问题。 例如，在尝试删除映射到目标的区段时会发生这种情况。 (AAM-54031)
* 修复了不再使用受众市场的客户每 [!UICONTROL 月收到] 开具发票电子邮件的问题。 (AAM-54602)
* 修复了客户在UI中从其他位置单击某些特征时，会看到断开的链接而不是特征的问题。 (AAM-54768)
* 修复了在编辑特征表达式模式下，按ENTER将刷新页面并且特征表达式丢失的问题。 (AAM-54210)
* 改进了整个界面的多项辅助功能。(AAM-47781、AAM-49075、AAM-49360、AAM-49361、AAM-49376、AAM-50432、AAM-52550、aam-54660)。

### 新的受众管理器教程 {#tutorials-aam}

| 内容 | 描述 |
| -----------| ---------- |  
| [理解受众经理的基本术语和概念](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-basic-terms-and-concepts-in-audience-manager.html) | 此视频介绍了受众管理器中开始使用的一些基本术语和概念，包括信号、特征、细分等。 |
| [了解受众管理器中的数据流](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-the-data-flow-in-audience-manager.html) | 此视频通过描述数据流入、流入和流出应用程序，帮助您了解Adobe受众管理器。 |
| [受众管理器- DMP概述](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-overview-of-a-dmp.html) | 了解跨渠道个性化的关键挑战，以及Adobe受众经理如何推动客户旅程。 另外，了解哪些数据类型可在受众管理器中载入，并识别与受众管理器集成的广告技术生态系统合作伙伴。 |
| [受众经理使用案例](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-use-cases.html) | 在此视频中，我们确定了四个常见的受众管理器用例，并介绍了与这些用例相关的最佳实践。 |
| [了解受众管理器中的跨设备指标](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/profile-merge/understanding-cross-device-metrics-in-audience-manager.html) | 在此视频中，我们讨论了设备用户档案和跨设备用户档案之间的差异，并显示UI中的数字与这些不同用户档案类型的匹配位置。 |
| [了解受众管理器中的预测受众](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/understanding-predictive-audiences.html) | 在此视频中，我们将讨论受众管理器预测受众是什么，展示其工作方式的详细信息并指出使用案例。 |
| [在受众管理器中配置和报告预测受众](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/configure-and-report-on-predictive-audiences.html) | 在此视频中，我们将演练受众管理器界面中的预测受众配置。 我们还会看到显示模型结果的报告。 |

## ![图标](/assets/aem.png) Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新增功能、修复和更新。Adobe 建议那些采用内部部署的客户部署最新的修补程序，以便确保获得更高的稳定性、安全性和性能。

### 产品更新

* **AEM 作为云服务**

   * 资产处理方面的改进和修复。 资产重新处理对话框为用户提供更多控制权，允许选择特定的处理用户档案，以及是否应触发后处理工作流。
   * Dynamic Media资产摄取性能改进。

### 自助服务

* **自动表单转换服务——发行AFC-2020.03.1**

   安装最新连接器时，将提供新选项：

   **[!UICONTROL 自动检测逻辑部分]**: 可使用“自 [!UICONTROL 动检测逻辑部分] ”选项拖放页面级面板（基于页码的面板）并仅创建逻辑面板。 它还会将不属于前面具有逻辑部分的任何部分的字段和分布在两个相邻页面的逻辑部分的字段归入单个逻辑部分。 例如，如果某个逻辑部分的某些字段位于第1页的末尾，而某些字段位于第2页的开始，则所有此类字段都会汇集到单个逻辑部分中。

* **Dynamic Media中不支持的图像格式**

   有关Dynamic Media不支持的栅格图像文件格式子类型 [!UICONTROL 的信息]。

   请参 [阅Dynamic Media中不支持的栅格图像格式](https://docs.adobe.com/content/help/en/experience-manager-65/assets/administer/assets-formats.html#unsupported-image-formats-dynamic-media)。

* **内容片段**

   有关AEM Assets [HTTP API中内容片段支持的信息](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/admin/assets-api-content-fragments.html)，以及自定 [义和扩展内容片段](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-customizing.html)，以 [及内容片段配置要渲染的组件](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-configuring-components-rendering.html)。

* **AEM Experience League社区**

   与AEM Experience [League社区建立联系](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/ct-p/adobe-experience-manager-community): 向同学和AEM专家提问，浏览线程，分享您的提示和专业知识！

* **AEM新闻稿**

   AEM Newsletter by [!UICONTROL Experience League] 旨在帮助您快速了解AEM，以便您能够立即开始实现价值。 以下是最新的新闻稿：

   * [第30卷](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html): Experience Manager现已作为云服务提供。
   * [订阅](https://adobeeventsonline.com/AEM/2017/NL/Optin/) “Experience Insider Newsletter”。
   * 视图新闻快 [讯存档](https://helpx.adobe.com/cn/support/experience-manager/6-5.html) （位于Adobe Experience Manager 6.5学习和支持页面的AEM资源部分）。

### 新的 Experience Manager 教程

| 内容 | 描述 |
| -----------| ---------- |  
| [设置本地AEM Runtime](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | Adobe Experience Manager (AEM) can be run locally using the [!UICONTROL AEM as a Cloud Service] SDK&#39;s [!UICONTROL Quickstart Jar]. This allows developers to deploy to, and test custom code, configuration, and content prior to committing it to source control, and deploying it to a [!UICONTROL AEM as a Cloud Service] environment. |
| [AEM资产快速入门](https://video.tv.adobe.com/v/33624?captions=chi_hans) | 有关面向商业用户的AEM资产入门的简介视频。 |
| [元数据文件夹模式](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-folder-schemas.html) | 元数据文件夹模式允许用户管理和审阅与资产文件夹本身关联的元数据，而不是直接管理资产。 |
| [标记](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/tagging.html) | 标记是跨资产文件夹层次结构管理资产的必不可少的工具。 建立标记分类对于允许用户在AEM中发现和组织资产至关重要。 |
| [元数据配置文件](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-profiles.html) | 元数据用户档案允许将默认元数据自动应用到资产文件夹内的资产。 这有助于减轻AEM用户的元数据管理负担并提高元数据一致性。 |
| [元数据模式](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-schemas.html) | 元数据模式定义在AEM中显示资产元数据的界面。 此视频探索应用资产时所使用的方法的组合。 |

### Journey Orchestration

* [AEM as Cloud Service发行说明](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)
* [AEM as Cloud Service文档](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-5.html)
* [AEM 6.4 学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-4.html)
* [AEM 6.3 学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-3.html)
* [AEM 6.2 学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-2.html)
* [Cloud Manager 用户指南](https://helpx.adobe.com/cn/experience-manager/cloud-manager/user-guide.html)
* [AEM Cloud Manager发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [更早版本的 AEM 文档](https://helpx.adobe.com/cn/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic 帮助主页](https://docs.adobe.com/content/help/zh-Hans/dynamic-media-classic/using/home.html)
* [Dynamic Media 发行说明](https://marketing.adobe.com/resources/help/zh_CN/s7/release_notes/index.html)
* [Livefyre 发行说明](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## ![图标](/assets/campaign.png) [!DNL Campaign] {#ac}

Adobe Campaign 提供了一种直观、自动的方式，以通过在线和离线营销渠道来交付一对一的消息。您现在可以利用根据客户习惯和喜好所决定的体验，来预测客户的需求。

### Campaign Standard

* [Adobe Campaign标准版20.3](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/release-notes/release-notes.html)

### Campaign Classic

* [Adobe Campaign Classic 20.1.3](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html#release-20-1-3-build-9124)
* [Adobe Campaign Classic 19.1.4](https://docs.adobe.com/content/help/zh-Hans/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### 活动控制面板

| 功能 | 描述 |
| -----------| ---------- |  
| GPG密钥管理 | 在营销实例上安装和／或生成GPG密钥，以加密从活动发送的数据并解密传入数据。 |
| CNAME子域的证书管理 | 控制面板现在允许您续订已使用CNAME方法委派的子域的SSL证书。 |

### 新的Campaign教程

* 新的 Campaign Standard 教程

| 内容 | 描述 |
| -----------| ---------- |  
| [控制面板- Google TXT记录管理](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/google-txt-record-management.html) | 了解如何通过活动控制面板将Google TXT站点验证记录添加到用于向GMAIL地址发送电子邮件的所有子域。 |
| [使用外部API活动配置和运行工作流](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) | 了解如何使用外部API活动调用外部REST API端点。 |
| (ACS) [Android推送通知入门——教程](https://docs.adobe.com/content/help/en/campaign-standard-learn/getting-started-with-push-notifications-android/introduction.html) | 本教程介绍使用Campaign Standard和Android应用程序设置推送通知所需的步骤。 |

* 新的Campaign Classic教程

| 内容 | 描述 |
| -----------| ---------- |  
| [雪花大数据管理](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | 了解如何在Adobe Campaign经典中利用雪花连接器。 |
| [控制面板- Google TXT记录管理](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/google-txt-record-management.html) | 了解如何通过活动控制面板将Google TXT站点验证记录添加到用于向GMAIL地址发送电子邮件的所有子域。 |

### 活动帮助资源

* Adobe Campaign标准： [帮助中心](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/campaign-standard-home.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/release-notes/release-notes.html) -操作 [方法视频——计划发布](https://docs.adobe.com/content/help/zh-Hans/campaign-learn/campaign-standard-tutorials/overview.html) - [发布最新文档更新](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-planning.htmll)[] (https://docs.adobe.com/content/help/en/campaign-standard/using/documentation-updates.html)
* Adobe Campaign经典： [帮助中心](https://docs.adobe.com/content/help/en/campaign-classic/using/campaign-classic-home.html) - [发行说明](https://docs.campaign.adobe.com/doc/AC/en/RN.html) -操 [作方法视频——最新文](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)档 [更新] (https://docs.adobe.com/content/help/en/campaign-classic/using/documentation-updates.html)
* Adobe Campaign 控制面板：[文档](https://docs.adobe.com/content/help/zh-Hans/control-panel/using/control-panel-home.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/control-panel/using/release-notes.html)

## ![图标](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

* [Advertising Cloud DSP的新增功能](#adcloud-dsp)
* [Advertising Cloud Search的新增功能](#adcloud-search)

### Advertising Cloud DSP的新增功能 {#adcloud-dsp}

| 功能 | 描述 |
| -----------| ---------- |
| [!UICONTROL 活动经典] 和 [!UICONTROL 活动测试版] | 针对欺诈和品牌安全的IAS衡量设置(您可以选择为每个活动配置)现在包括用于衡量VAST和VPAID库存的选项。 |
| [!UICONTROL 活动测试版] | 数据可视化和页面加载时间得到了改进。 |
|  | 现在，您可以在所有页面上下载基于当前过滤器和视图的Excel报表。 |
|  | （在5月22日发布）新指标包括所有时间指标、当前时间间隔投放、特定日期OTS。 |
| [!UICONTROL 黑名单] | 预测系统现在自动使用广告商或帐户级别的黑名单。 用户不再需要将黑名单粘贴到放置设置中。 |
| [!UICONTROL 库存交易] | （封闭测试版）利用简化的新表单，您可以快速设置、编辑供应端平台(SSP)交易并对交易ID收件箱中未提供的交易进行疑难解答。 |
|  | 当您在交易ID收件箱中接受一包程序化保证交易时，您现在会收到通知，您需要为每个交易ID创建默认位置。 |

### Advertising Cloud Search [!UICONTROL 的新增功能] {#adcloud-search}

| 功能 | 描述 |
| -----------| ---------- |
| [!UICONTROL 促销活动] | (Google Ads账户； 测试版服务)，从5月下旬开始，Advertising Cloud Search将能够将Google Gmail显示活动和Google Smart Shopping活动的数据与Google转换同步，以便跟踪和报告。 该服务还允许您从活动和广告组视图编辑现有活动的广告组设置和广告组设置。 服务将是可选的。 一旦服务正式可用，将收取额外费用。<br>有关该服务(包括测试版项目和未来范围)的更多信息，请与您的Adobe客户经理联系。 |

## ![图标](/assets/magento.png) [!DNL Magento] {#magento}

有关 Magento 的发行说明，请参阅：

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![图标](/assets/marketo.png) [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] 是一个完整的应用程序，面向希望通过参与复杂购买历程的每个阶段来转变客户体验的潜在客户管理人员和 B2B 营销人员。

### 核心 Marketo Engage 更新

请参 [!DNL Marketo] 阅 [发行说明](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) ，了解最新发行信息。

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
