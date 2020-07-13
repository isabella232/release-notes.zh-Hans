---
title: Adobe Experience Cloud 发行说明
description: Adobe Experience Cloud 发行说明
doc-type: release notes
last-update: July 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 19591a3d807cd772df0eb20e457d94cc9f7d5cfb
workflow-type: tm+mt
source-wordcount: '4203'
ht-degree: 59%

---


# 提前访问- Adobe Experience Cloud发行说明- 2020年7月

![横幅](/assets/experience-cloud-banner-3.png)

此页面介绍了 [!DNL Adobe Experience Cloud] 中的新增功能、修复和重要声明。此外，还重点提供了可帮助您充分利用 Experience Cloud 的新文档、培训课程和视频教程。

>[!IMPORTANT]
>
>此页面包含预发行内容，在发行版之前可能会发生更改。

>[!NOTE]
>
>若要通过电子邮件接收有关即将发行的版本的通知，请订阅 [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html)。

**发行日期：2020 年 7 月 16 日**

产品发行日期可能有所不同。请定期查看以获取最新信息。

最新更新： **2020年7月10日**

* [Adobe 系统状态](#status)
* [Experience Cloud 界面](#ecloud)
* [Experience Platform](#platform)
* [旅程编排](#journey-orch)
* [Analytics](#analytics) 与 [Customer Journey Analytics](#cust-journey)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/zh-Hans/target/using/release-notes/target-release-notes.html)
* [!DNL Magento](#magento)
* [!DNL Marketo Engage](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/cn/primetime/user-guide.html)（链接到 Primetime 帮助页面）

需要帮助？请访问 [Adobe Experience League](https://experienceleague.adobe.com/#home)，查找产品和技术文档、Adobe 策划课程、视频教程、快速解答、社区洞察以及由讲师指导的培训。

## ![图标](/assets/adobe.png) Adobe 系统状态 {#status}

[!UICONTROL Adobe 系统状态]提供关于 Adobe 云产品与服务中断和维护事件的详细信息、状态更新以及电子邮件通知。请访问 [status.adobe.com](https://status.adobe.com/) 查看。

发布日期：**2020 年 5 月 21 日**

**新增功能**

* 凭借您的 Adobe ID，您可以订阅粒度更细的事件通知，具体可达到产品和加载项级别。为了帮助您更快地设置订阅，现在，自助订阅过程会根据您的产品权利推荐一系列产品和服务。这样应当会减少您收到的电子邮件数量，并向收件箱中发送更多相关的通知。要开始使用，请访问 [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit)。

**当前可用的新增功能和增强功能**

| 功能 | 描述 |
| -----------| ---------- |
| 改进了订阅和通知用户体验 | <ul><li>现在，系统会根据所选产品的列表过滤 [!DNL Marketo Engage] 区域位置。</li><li>[!DNL Marketo Engage] 电子邮件通知与用户的区域、位置和环境首选项相关。</li></ul> |
| 事件订阅确认 | <ul><li>现在，在订阅正在进行的单个事件更新时，您会收到电子邮件确认。</li></ul> |
| 全局导航可用性增强功能 | <ul><li>顶级导航菜单的用户体验与 `Adobe.com` 一致。</li></ul> |

## ![图标](/assets/ec_appicon_24.png) Experience Cloud 界面 {#ecloud}

Experience Cloud 界面的常规更新。

**更新的界面菜单**

在Experience Cloud中， 2020 **年7月16日发布** ，将更新应用程序切换器下拉菜单。 它已得到简化，因此解决方案徽标被删除，并且菜单仅显示您有权访问的应用程序和服务。

有关示例， [请参阅Experience Cloud](https://docs.adobe.com/content/help/zh-Hans/core-services/interface/experience-cloud.html) 界面产品文档。

**统一的产品域**

Adobe 一直在更新域和界面标题，以统一并改进您在所有 Experience Cloud 应用程序中的体验。这些增强功能旨在以细微而重要的方式简化您的体验。这些增强不会更改您当前的工作流程。

更新包括：

* 新应用程序 URL：`experience.adobe.com/<application name>`：
   * 所有产品最终都将采用此 URL 模式。寻找即将在本月内生效的新 URL。
   * 浏览器支持：支持的浏览器包括 [!DNL Microsoft Edge]、[!DNL Google Chrome]、[!DNL Firefox]、[!DNL Safari] 和 [!DNL Opera]（最新版本）。**注意：**&#x200B;尽管 Experience Cloud 界面支持这些浏览器，但单个应用程序可能不支持每个浏览器。（例如，[Analytics](https://docs.adobe.com/content/help/zh-Hans/analytics/admin/sys-reqs.html) 不支持 [!DNL Opera]，[Target](https://docs.adobe.com/help/zh-Hans/target/using/implement-target/before-implement/supported-browsers.html) 不支持 [!DNL Safari]。）
   * （仅限 [!DNL Safari]）域更改可能导致 [!DNL Safari] 中出现 Cookie 问题。取消选中 [!DNL Safari] 隐私首选项中的&#x200B;_阻止跨站跟踪_，将支持跨域的 Cookie（以及所有跨站点体验），并允许 Experience Cloud 在这个新的域上正常运行。
* 更轻松地在组织之间切换，或切换到其他应用程序。
* 改进了产品帮助：[!UICONTROL Experience League] 已集成到产品中，以便帮助搜索还包括来自社区论坛及视频内容的答案。此更改会简化对更多内容的访问，并有助于您充分利用 Experience Cloud。此外，单击&#x200B;**[!UICONTROL 帮助]** > **[!UICONTROL 反馈]**，可报告问题或与 Adobe 分享您的想法。

以下应用程序使用新的 experience.adobe.com 域：

| 应用程序或服务 | Domain |
| -----------| ---------- |
| Experience Cloud 主页 | `experience.adobe.com/home` |
| Adobe Target | `experience.adobe.com/target` |
| Adobe Audience Manager | `experience.adobe.com/audience-manager` |
| Adobe Launch | `experience.adobe.com/launch` |
| Adobe Experience Platform | `experience.adobe.com/platform` |
| 历程管理 | `experience.adobe.com/journeys` |
| Adobe Analytics | `experience.adobe.com/analytics` |
| Customer Journey Analytics | `experience.adobe.com/platform/analytics` |
| Adobe Campaign 控制面板 | `experience.adobe.com/controlpanel` |
| Cloud Manager | `experience.adobe.com/cloud-manager` |
| Places Service | `experience.adobe.com/places` |
| Software Distribution | `experience.adobe.com/downloads` |
| 管理员工具（测试版） | `experience.adobe.com/admin` |

>[!NOTE]
>
>[!UICONTROL Marketing Cloud Assets] 选择器中的旧版过滤器&#x200B;**[!UICONTROL 留言板和收藏集]**&#x200B;即将停用。

## ![图标](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

[!DNL Experience Platform] 和应用程序服务的发行说明，包括 [!DNL Experience Platform Launch,]、[!UICONTROL Offers]、[!UICONTROL People]、[!UICONTROL Places]、[!UICONTROL Mobile Services] 和安全公告。

Latest release date: **June 10, 2020**

有关 [Experience Platform的最](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md) 新信息，请参阅Experience Platform发行说明。

## ![图标](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

凭借 Adobe Experience Platform，可以实时智能化预测每位客户的需求（无论其旅程通达何处），从而实现跨体验渠道大规模编排客户历程。

### Journey Orchestration 的其他资源

[文档](https://docs.adobe.com/content/help/zh-Hans/journeys/using/journey-orchestration-home.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/journeys/using/release-notes/release-notes.html) - [操作方法视频](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

## ![图标](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

发行日期：**2020 年 7 月 16 日**

* [Adobe Analytics 中的新增功能](#aa-features)
* [Customer Journey Analytics 的新增功能](#cust-journey)
* [Media Analytics 的新增功能](#media-aa)
* [Adobe Analytics 中的修复](#aa-fixes)
* [Analytics 管理员的重要注意事项](#aa-notices)
* [Adobe Analytics 的新课程和教程](#tutorials-analytics)
* [AppMeasurement](#appm)

### Adobe Analytics 中的新增功能 {#aa-features}

| 功能 | [正式发布](https://docs.adobe.com/content/help/zh-Hans/analytics/landing/an-releases.html) - 目标日期 | 描述 |
| -----------| ---------- |-------|
| 工作区： 新日期范围预设 | 添加了4个新的日期范&#x200B;_围(本周／月/季度／年_ （不包括今天）)，以便用户可以从不包含今天部分日期数据的日期范围中进行选择。 |
| 数据修复API —— 公共测试版 | 数据修复API为客户提供了一个自助选项，用于删除AdobeAnalytics数据的列。 发布公共测试版后，API将支持删除Activity Map数据。 以后将推出其他功能。 要访问此API，请联系客户关怀。 |

### Customer Journey Analytics 的新增功能 {#cust-journey}

| 功能 | [正式发布](https://docs.adobe.com/content/help/zh-Hans/analytics/landing/an-releases.html) - 目标日期 | 描述 |
| -----------| ---------- |-----|
| 本月没有新增功能 |  |  |

### [!UICONTROL Media Analytics] 的新增功能{#media-aa}

更新日期： **2020年7月16日**

| 功能 | [正式发布](https://docs.adobe.com/content/help/zh-Hans/analytics/landing/an-releases.html) - 目标日期 | 描述 |
| -----------| ---------- | ---------- |
| [支持的设备和平台](https://docs.adobe.com/content/help/zh-Hans/media-analytics/using/supported-devices.html) | 2020 年 6 月 18 日 | Media Launch Extension w/ AEP SDK 现在支持以下 OTT 设备：<ul><li>Apple TV  (tvOS)</li><li>Fire TV (Fire OS)</li><li>Android TV</li></ul> |  | [支持的设备和平台](https://docs.adobe.com/content/help/zh-Hans/media-analytics/using/supported-devices.html) | 2020 年 6 月 18 日 | Media Launch Extension w/ AEP SDK 现在支持以下 OTT 设备：<ul><li>Apple TV  (tvOS)</li><li>Fire TV (Fire OS)</li><li>Android TV</li></ul> |
| [播放器状态跟踪](https://docs.adobe.com/content/help/zh-Hans/media-analytics/using/player-state-tracking/player-state-overview.html) | 2020 年 5 月 29 日 | [!UICONTROL Media Analytics] 客户可以运用一组适用于全屏、隐藏式字幕、静音、画中画和聚焦的标准解决方案变量，捕获视频播放期间观看者的交互信息。您还可以灵活地创建自定义播放器状态。播放器状态跟踪变量现在可以在 [!UICONTROL Analysis Workspace] 中进行报告。此功能需要以下任一项： <ul><li>Media [!DNL JavaScript] SDK 3.0 或更高版本</li><li>与 [!DNL Adobe Experience Platform] (AEP) SDK 一起使用时：</li><li>[!UICONTROL Media Analytics 扩展]（用于 Web）：[!UICONTROL Adobe Media Analytics] (3.x SDK) for Audio and Video v1.0 或更高版本</li><li>[!UICONTROL Media Analytics 扩展]（用于移动设备）：[!UICONTROL Adobe Media Analytics for Audio] and Video v2.0 或更高版本</li><li>[!UICONTROL 媒体收集]</li></ul> |

### Adobe Analytics 中的修复 {#aa-fixes}

* 修复了切换到使用其他货币的报表包后发生的问题。 Workspace [!UICONTROL 折线] 图未反映正确的货币。 (AN-216655)
* 修复了在下载的PDF中无法读取可视化的问题。 (AN-217949)
* 修复了在将层次结构变量添加到报表包时导致错误的问题。 (AN-211974)
* 修复了在编辑与报表包关联的数据源时出现的问题，该报表包的时区与当前选定的报表和Analytics报 [!UICONTROL 表包的时区不] 同。 (AN-222474)
* 修复了分类规则 [!UICONTROL 生成器不工作] 的问题。 (AN-219662)
* 修复了分类和分类规则的多个问题。 (AN-223492、AN-220654、AN-219662、AN-223260)
* 修复了同一区段在虚拟报告套件中返回与父报告套件不同数据的问题。 (AN-201074)
* 修复了阻止下载报告套件设置的问题。 (AN-223690)
* 修复了智能 [!UICONTROL 警报中] ，此 _计划电_ 子邮件链接无法工作的问题。 (AN-223875)
* 修复了虚拟报表包的货币显示不正确的问题。 (AN-224781)
* 修复了虚拟报告 _包中缺少_ 、组件错误的问题。 (AN-224782)

#### 其他 Adobe Analytics 修复

AN-222672、AN-222813; AN-222892; AN-223272、AN-223432; AN-224062; AN-224108; AN-224163; AN-224339; AN-224456; AN-224449; AN-224552; AN-224553; AN-224786

### [!DNL Analytics] 管理员的重要注意事项 {#aa-notices}

| 注意事项 | 添加或更新日期 | 描述 |
| -----------| ---------- | ---------- |
| 报表包映射到IMS组织 | 2020 年 7 月 | 报表包映射工具将于2020年11月停止。 此功能支持集成，如Advertising Booke和Adobe Biolde中的Experience Cloud细分发布。 必须将报表包映射到IMS组织，才能启用这些服务和其他服务。 创建时会自动映射较新的报表包。 但是，必须手动将旧报表包映射到IMS组织。 请参 [阅核心服务用户指南](https://docs.adobe.com/content/help/zh-Hans/core-services/interface/about-core-services/report-suite-mapping.html) ，将报表包映射到组织，以确保所有报表包都属于IMS组织。 |
| 迁移到统一的产品域 | 生效日期：2020 年 5 月 28 日 | 向 Adobe Analytics 统一产品域的迁移从 2020 年 1 月开始，于 2020 年 5 月 28 日完成。虽然 Adobe Analytics 会从其架构中删除所有 `omniture.com` 域引用，但务必要将 `omniture.com` 作为第三方 Cookie 添加到白名单中。（不久）完成整个架构迁移后，我们将通过发行说明通知您，此允许列表步骤将不再需要执行。[此处](https://helpx.adobe.com/cn/analytics/kb/adobe-ip-addresses.html)提供了建议应添加到白名单中的 IP 地址和域的完整列表。<br>如果贵组织阻止第三方 Cookie，请联系客户关怀团队以重新获得 Adobe Analytics 访问权限。 |
| 新的 Adobe Analytics 默认登陆页面 | 生效日期：2020 年 6 月 18 日 | 2020 年 6 月 18 日，Adobe Analytics 的默认登陆页面将从[!UICONTROL 报表]更改为[!UICONTROL 工作区]。之前未设置自定义登陆页面的任何用户都将发生此更改。 |
| 第三方技术允许列表 | 2020 年 3 月 12 日（生效日期） | Adobe Analytics 已开始利用第三方技术进行功能推出管理和提供产品内支持。应将以下 URL 添加到所有必要的网络防火墙允许列表中，以确保能够完全访问功能：<ul><li>Gainsight：https://esp.aptrinsic.com</li><li>LaunchDarkly：https://app.launchdarkly.com</li></ul> |
| 改善了 [!UICONTROL Analysis Workspace] 可用性的冗余 | 2020 年 5 月 21 日 | 为确保 [!UICONTROL Analysis Workspace] 的可用性，我们添加了辅助 CDN（内容交付网络），以改善冗余。应将以下 URL 添加到任何必要的网络防火墙允许列表中：<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| 在[!UICONTROL 工作区]中更改[!UICONTROL 登入/退出]的计算方式 | 2020 年 4 月 7 日 | 在 [!UICONTROL Analysis Workspace] 中，从 2020 年 3 月起，我们更改了&#x200B;_无_&#x200B;值与[!UICONTROL 登入/退出]的交互方式。由于您现在可以在 _Analysis Workspace_ 中打开和关闭[!UICONTROL 无]，因此我们会在登入或退出后应用&#x200B;_无_&#x200B;值，而（对于 eVar）过去是在登入或退出前应用。例如，假定访问的第一次点击没有 eVar 值，但第二次点击有。在 [!UICONTROL Reports &amp; Analytics] 中，第一次点击将针对“登入”显示为&#x200B;_未指定_，但在 [!UICONTROL Analysis Workspace] 中，将显示第二次点击时的值。 |
| **[!UICONTROL 功能板存档]**&#x200B;生命周期终止 | 2020 年 3 月 27 日 | 自 2020 年 10 月起，在 [!UICONTROL Reports &amp; Analytics] 中，位于&#x200B;**[!UICONTROL 管理功能板]**&#x200B;下方的&#x200B;**[!UICONTROL 查看存档]**&#x200B;将不再可用。 |
| 生命周期结束 - Analytics 旧版 API | 2020 年 1 月 9 日 | 2020 年 11 月，以下 Analytics 旧版 API 服务将停止使用并关闭。当前使用这些服务构建的集成将会停止工作。 <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>旧版 OAuth 身份验证（OAuth 和 JWT）</li></ul>我们提供了[旧版 API EOL 常见问题解答](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)，以帮助回答您的问题并提供有关如何继续的指导。使用这些服务的 API 集成可以迁移到 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 或 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。旧版 OAuth 帐户可迁移到 [Adobe IO](https://console.adobe.io/home?mv=email) Analytics 集成帐户，该帐户可用于访问 1.4 Analytics API 和 2.0 Analytics API。 |
| 圣何塞 FTP 中转站停止为伦敦和新加坡提供支持 | 2020 年 7 月 | 对于位于伦敦和新加坡的客户，我们将不再提供伦敦或新加坡与圣何塞数据中心 [ftp.omniture.com](ftp://ftp.omniture.com/) 之间的数据中转支持。<br/><ul><li>伦敦客户，请使用 [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>新加坡客户，请使用 [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Ad Hoc Analysis 生命周期终止 | 2018 年 8 月 6 日 | Adobe 宣布计划终止 Ad Hoc Analysis 生命周期。确定终止日期后，Adobe 会立即与大家共享此信息。有关更多信息，请参阅[探索工作区](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)。 |

#### AppMeasurement

有关 AppMeasurement 版本的最新更新，请参阅[适用于 JavaScript 的 AppMeasurement 发行说明](https://docs.adobe.com/content/help/zh-Hans/analytics/implementation/appmeasurement-updates.html)。

#### Analytics 帮助资源

* [Adobe Analytics 教程](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics 产品文档](https://docs.adobe.com/content/help/zh-Hans/analytics/landing/home.html)

## ![图标](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Audience Manager 中的新增功能、修复、文档和教程。

发行日期：**2020 年 7 月 16 日**

### Adobe Audience Manager 中的新增功能和修复

* 修复了客户无法将某些区段映射到Amazon目标的问题。 (AAM-54373)
* 修复了客户在新选项卡中打开区段时浏览器屏幕冻结的问题。 (AAM-55213)
* 修复了入门状 [态报表中](https://docs.adobe.com/help/en/audience-manager/user-guide/reporting/onboarding-status-report.html)，客户在单击图形中的条和表中的日期时，会看到日期不匹配的问题。 (AAM-55235)
* 修复了“管理”部分的一个错误，该错误导致用户界面在客户尝试删除用户时显示错误图标而不是确认消息。 (AAM-55186)
* 修复了Swagger API的一个问题，该问 `x-api-key` 题导致标题未添加到curl请求中。 (AAM-55392)
* 改进了映射到目标视图中目标的区段的默认排序顺序。 映射的区段现在按区段映射的开始日期，然后按区段ID排序。 (AAM-38494)
* 改进了整个界面的多项辅助功能。(AAM-48956、AAM-49012、AAM-49364、AAM-49363、AAM-49374、AAM-49579、AAM-55037)。

## ![图标](/assets/aem.png) Adobe Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新增功能、修复和更新。Adobe 建议那些采用内部部署的客户部署最新的修补程序，以便确保获得更高的稳定性、安全性和性能。

### 产品更新

* **Dynamic Media Classic**

   Dynamic Media经典用户现在可以获得不再依赖浏览器中的Adobe Flash技术的新桌面应用程序体验。 新应用程序现在可用于Windows和macOS。

   请参 [阅AdobeDynamic Media经典桌面应用程序——现已推出。](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/new-ui-2020.html)

* **为Dynamic Media添加了3D资源支持**

   AEM 6.5和AEM中的Dynamic Media现在可以作为Cloud Service上传、管理、视图和交付3D资产，使其成为令人痴迷的体验。

   * 在AEM中，作为Cloud Service，请 [参阅在Dynamic Media中使用3D资产。](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/assets-3d.html)
   * 在AEM 6.5中，请参阅 [在Dynamic Media中使用3D资产。](https://docs.adobe.com/content/help/en/experience-manager-65/assets/dynamic/assets-3d.html)

### 自助服务

* **AEM 6.5.5表单文档更新**

   * 6.5.5版本的新增功能和改进：

      * [自定义Adobe Experience Manager收件箱列](https://docs.adobe.com/content/help/en/experience-manager-65/authoring/essentials/inbox.html#inbox-admin-control)。
      * [将交互通信另存为草稿。](https://docs.adobe.com/content/help/en/experience-manager-65/forms/interactive-communications/prepare-send-interactive-communication.html#save-as-draft)
      * Oracle WebLogic应用程序服务器支 [持单台服务器](https://helpx.adobe.com/content/dam/help/en/experience-manager/6-5/forms/pdf/prepare-install-single-server.pdf)[和群集安装](https://helpx.adobe.com/content/dam/help/en/experience-manager/6-5/forms/pdf/prepare-install-cluster.pdf) 。
      * [辅助功能改进.](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/new-features-latest-service-pack.html#accessibility-improvements)
      * [表单数据模型中基于X-509证书的SOAP Web服务身份验证。](https://docs.adobe.com/content/help/en/experience-manager-65/forms/form-data-model/configure-data-sources.html#configure-soap-web-services)
      * [Oracle RAC支持。](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/new-features-latest-service-pack.html#other-improvements)
      * [改进了事务报告中的错误记录。](https://docs.adobe.com/content/help/en/experience-manager-65/forms/transaction-reports/viewing-and-understanding-transaction-reports.html#view-transaction-reporting-logs)
   * 6.4.8.1版本的新增功能和改进：
      * [表单数据模型中基于X-509证书的SOAP Web服务身份验证。](https://docs.adobe.com/content/help/en/experience-manager-64/forms/form-data-model/configure-data-sources.html#configure-soap-web-services)
      * [改进了事务报告中的错误记录。](https://docs.adobe.com/content/help/en/experience-manager-64/forms/transaction-reports/viewing-and-understanding-transaction-reports.html#view-transaction-reporting-logs)

### **社区**

* **AEM 社区讨论**

   现在，您可以在一个位置查看所有 AEM 公告以及对内部和外部博客作者的相关引用。请参阅 AEM 社区的[“讨论”部分。](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/bd-p/adobe-experience-manager-discussions)

### Experience Manager 的新课程和教程

过去一个月发布的新视频、教程或课程。

| 已发布 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 6 月 25 日 | [自适应表单入门](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/creating-your-first-adaptive-form/adaptive-forms-getting-started-tutorial-use.html) | 视频 | 这些教程将指导您完成创建多选项卡式自适应表单所涉及的步骤。 了解如何使用表、折叠布局和规则编辑器来创作业务规则。 |
| 2020 年 6 月 25 日 | [在AEM Forms中创建审阅工作流](https://video.tv.adobe.com/v/35821/quality=9?captions=chi_hans) | 视频 | 了解如何创建用于从活动表单提交中审核已提交数据的工作流。 |
| 2020 年 6 月 23 日 | [处理配置文件](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/processing-profiles.html) | 视频 | 处理用户档案将要为AEM中的资产创建的演绎版定义为Cloud Service。 |
| 2020 年 6 月 23 日 | [Dynamic Media经典最佳实践](https://docs.adobe.com/content/help/en/experience-manager-learn/dynamic-media-classic-tutorial/overview.html) | 文章 | 当前和新用户可以了解Dynamic Media经典、其核心功能以及 _创建_、 _创作_&#x200B;和交 _付工作流_ 程。 |
| 2020 年 6 月 23 日 | [将AEM作为Cloud Service构建和部署进行调试](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-as-a-cloud-service/build-and-deployment.html) | 文章 | 了解如何将AEM的构建和部署作为Cloud Service进行调试。 |
| 2020 年 6 月 16 日 | [使用日志将AEM作为Cloud Service进行调试](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-as-a-cloud-service/logs.html) | 文章 | 了解如何使用日志将AEM作为Cloud Service进行调试。 日志充当调试AEM应用程序的前线，但取决于已部署的AEM应用程序中的足够日志记录。 |
| 2020 年 6 月 10 日 | [将Dynamic Media3D与AEM Assets结合使用](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/dynamic-media/dynamic-media-3d-feature-video.html) | 视频 | Dynamic Media对Adobe Experience Manager的3D支持使您能够轻松定制和大规模交付交互式3D驱动体验。 |
| 2020 年 6 月 5 日 | [SPA编辑器项目](https://docs.adobe.com/content/help/en/experience-manager-learn/spa-react-tutorial/create-project.html) | 文章 | 了解如何使用Adobe Experience Manager(AEM)项目原型生成多模块Maven项目，作为与AEM SPA编辑器集成的React应用程序的起点。 |
| 2020 年 6 月 3 日 | [处理HTML5表单提交——教程](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/html5-forms/handle-mobile-form-submission.html) | 文章 | 了解如何在自定义提交处理程序中访问提交的数据。 |

### Experience Manager发布信息

所有Experience Manager发行说明均保留在以下页面：

* [AEM作为Cloud Service发布信息](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/release-notes/home.html)
* [AEM Cloud Manager 发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [自动表单转换服务发行说明](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/using/release-notes.html)
* [AEM 6.5 Service Pack发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
* [AEM 6.4 Cumulative Fix Pack发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-64/release-notes/cfp-release-notes.html)
* [AEM AssetsDynamic Media发行说明](https://docs.adobe.com/content/help/zh-Hans/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [AEM Brand Portal发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)
* [AEM桌面应用程序发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-desktop-app/using/release-notes.html)
* [AEMDispatcher发行说明](https://docs.adobe.com/content/help/en/experience-manager-dispatcher/using/getting-started/release-notes.html)
* [Adobe Primetime发行说明](https://docs.adobe.com/content/help/en/primetime/release-notes/home.html)
* [Livefyre 发行说明](https://docs.adobe.com/content/help/zh-Hans/livefyre/using/release-notes/c-rn.html)

### AEM的其他帮助资源

* [AEM作为Cloud Service用户指南](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-service/landing/home.html)
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

发布Campaign Classic、Campaign Standard和控制面板的信息。

#### Campaign Classic

* 新的金标稳定版本。 [了解更多信息](https://docs.adobe.com/content/help/zh-Hans/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

#### Campaign 控制面板

* 子域交付性审核- [阅读更多](https://docs.adobe.com/content/help/zh-Hans/control-panel/using/subdomains-and-certificates/setting-up-new-subdomain.html)

* GPG密钥管理- [阅读更多](https://docs.adobe.com/content/help/en/control-panel/using/instances-settings/gpg-keys-management.html)

### Campaign 的新课程和教程

过去一个月发布的新视频、教程或课程。

| 已发布 | 名称 | 解决方案 | 描述 |
| ----------- | ----------- | ---------- | ---------- |  
| 2020 年 6 月 26 日 | [浏览Adobe Campaign经典UI](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/exploring-the-adobe-campaign-classic-user-interface.html) | Campaign Classic | 此视频介绍主Adobe Campaign经典用户界面，并向您展示如何导航主功能。 |
| 2020 年 7 月 8 日 | [安装和设置 Adobe Campaign 客户端](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/install-and-setup-the-adobe-campaign-client.html) | Campaign Classic | 了解如何下载和安装 Adobe Campaign 客户端控制台、创建和管理与多个环境的连接，以及验证对 Adobe Campaign 客户端控制台的访问权限。 |
| 2020 年 6 月 19 日 | [Adobe Campaign经典简介](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/introduction-to-adobe-campaign-classic.html) | Campaign Classic | 了解Adobe Campaign经典如何融入Adobe数字体验产品组合以及主要特性和功能。 |
| 2020 年 6 月 12 日 | [部署临时电子邮件投放模板](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/using-delivery-templates/deploying-ad-hoc-email-delivery-template.html) | Campaign Classic | 了解如何部署临时电子邮件模板 |
| 2020 年 6 月 12 日 | [配置投放模板](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/using-delivery-templates/configuring-a-delivery-template.html) | Campaign Classic | 了解如何配置电子邮件模板 |
| 2020 年 6 月 12 日 | [设置投放模板属性](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/using-delivery-templates/setting-delivery-template-properties.html) | Campaign Classic | 了解如何设置电子邮件模板属性 |
| 2020 年 6 月 12 日 | [GPG密钥管理](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/gpg-key-management-overview.html) | Campaign Classic/控制面板 | 了解如何生成和安装用于数据加密的公用／专用GPG密钥对，以及如何导入和安装用于数据解密的公共密钥。 |
| 2020 年 6 月 26 日 | [UI快速入门Adobe Campaign Standard](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/getting-started/getting-started-with-the-ui.html) | Campaign Standard | 此视频为您提供了Adobe Campaign Standard用户界面的概述，并介绍如何导航到主要功能和核心功能。 |
| 2020 年 6 月 26 日 | [GPG密钥管理](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/gpg-key-management/gpg-key-management-overview.html) | Campaign Standard/控制面板 | 了解如何生成和安装用于数据加密的公用／专用GPG密钥对，以及如何导入和安装用于数据解密的公共密钥。 |

### 帮助资源

* Adobe Campaign Standard：[帮助中心](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/campaign-standard-home.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/release-notes/release-notes.html) - [操作方法视频](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [发行计划](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/release-notes/release-planning.html) - [最新文档更新](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic：[帮助中心](https://docs.adobe.com/content/help/zh-Hans/campaign-classic/using/campaign-classic-home.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/campaign-classic/using/release-notes/latest-release.html) - [操作方法视频](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)- [最新文档更新](https://docs.adobe.com/content/help/zh-Hans/campaign-classic/using/documentation-updates.html)
* Adobe Campaign 控制面板：[文档](https://docs.adobe.com/content/help/zh-Hans/control-panel/using/control-panel-home.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/control-panel/using/release-notes.html) - 有关 [Campaign Standard](https://docs.adobe.com/content/help/zh-Hans/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html)/[Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html) 的操作方法视频

## ![图标](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

AdobeAdvertising Cloud的发行说明。

### [!UICONTROL Advertising Cloud Search] 中的新增功能 {#adcloud-search}

2020 **年7月8日** （7月11日版本）更新。

| 功能 | 描述 |
| -----------| ---------- |
| [!UICONTROL 警报（测试版）] | 您现在可以打开一个只读的筛选视图，其中包含任何警报的数据，然后在相关活动管理视图中打开实体的筛选视图，从中可以编辑实体记录。 |
| [!UICONTROL 项目组合] | 限制和组合设置中基于职位的指标的弃用推迟到8月8日。 |

## ![图标](/assets/magento.png) [!DNL Magento] {#magento}

有关 Magento 的发行说明，请参阅：

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![图标](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] 是一个完整的应用程序，面向希望通过参与复杂购买历程的每个阶段来转变客户体验的潜在客户管理人员和 B2B 营销人员。

### 核心 Marketo Engage 更新

请参阅 [!DNL Marketo] [发行说明](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720)了解最新发行信息。

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
