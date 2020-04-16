---
title: Adobe Experience Cloud 发行说明
description: Experience Cloud 发行说明模板
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 6bd8e1af2afa691e6796769ad1f8cb5f29433d8e

---


# 抢先体验 - Adobe Experience Cloud 发行说明 - 2020 年 4 月

![横幅](/assets/experience-cloud-banner-3.png)

[!DNL Adobe Experience Cloud] 的新增功能和修复。

>[!IMPORTANT]
>
>此页面包含预发行内容，在发行版之前可能会发生更改。

>[!NOTE]
>
>若要通过电子邮件接收有关即将发行的版本的通知，请订阅 [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html)。对于在版本发行之后发布的新信息，将使用发布日期进行标记。

**发行日期：2020 年 4 月**

（具体解决方案的发布日期可能有所不同。）

* [Adobe 系统状态](#status)
* [Experience Cloud 界面和核心服务](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) (发 **布日期更改——请参阅4月15日的更新)**
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/zh-Hans/target/using/release-notes/target-release-notes.html)（链接到解决方案帮助页面）
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/cn/primetime/user-guide.html)（链接到解决方案帮助页面）

在找帮助主页吗？请参阅 [Adobe Experience Cloud 文档](https://docs.adobe.com/content/help/zh-Hans/experience-cloud/user-guides/home.html)。

## ![图标](/assets/adobe.png) Adobe 系统状态 {#status}

[!UICONTROL Adobe 系统状态]提供关于 Adobe 云产品与服务中断和维护事件的详细信息、状态更新以及电子邮件通知。请访问 [status.adobe.com](https://status.adobe.com/) 查看。

**新增功能**

* 凭借您的 Adobe ID，您可以订阅粒度更细的事件通知，具体可达到产品和加载项级别。此外，在我们的最新版本中，自订阅流程现在会根据您的产品授权，推荐一组产品和服务供您选择。这样应该可以减少您在订阅过程中需要作出决定的次数或点击次数，从而简化订阅流程，最重要的是，会向您的收件箱中发送更加相关的通知。要开始使用，请访问 [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit)。

**当前可用的新增功能和增强功能**

| 功能 | 描述 |
| -----------| ---------- |
| 基于授权的个性化订阅 | <ul><li>根据用户的 DX 授权，预先选择的推荐订阅产品。</li><li>推荐的订阅在产品列表顶部突出显示，以便快速查看。</li><li>收到的电子邮件通知与用户的产品授权相关。</li></ul> |
| 更轻松地管理订阅 | <ul><li>**[!UICONTROL 管理订阅]**&#x200B;在管理产品和事件订阅方面，提供了全新的用户体验。</li><li>新增了一个选项，可分别查看和编辑产品订阅和事件订阅。</li><li>**[!UICONTROL 删除]**&#x200B;选项使您可以取消产品订阅或事件订阅。</li><li>一键单击&#x200B;**[!UICONTROL 取消所有订阅]**&#x200B;选项适用于产品订阅。</li><li>UX 支持适用于 Web/移动设备/平板电脑界面，并针对 19 种语言进行了本地化。</li></ul> |

## ![图标](/assets/ec_appicon_24.png) Experience Cloud 界面和核心服务 {#ecloud}

Experience Cloud 界面中的新增功能和修复，包括管理和核心服务（客户属性、受众、触发器、Cookie 等）：

* 已弃用 Experience Cloud 的[!UICONTROL 馈送]页面。(EXC-8505)
* Experience Cloud 登录页面已更新，可反映新的品牌元素。(EXC-10747)

有关产品文档，请参阅 [Experience Cloud](https://docs.adobe.com/content/help/zh-Hans/core-services/interface/experience-cloud.html) 帮助。

### 统一的产品域

Adobe 将更新域和界面标题，以统一并改进您在所有 Experience Cloud 应用程序中的体验。这些增强功能旨在以细微而重要的方式简化您的体验。这些增强不会更改您当前的工作流程。

更新包括：

* 新解决方案 URL：`experience.adobe.com/<application name>`：
   * 所有产品最终都将采用此 URL 模式。寻找即将在本月内生效的新 URL。
   * 浏览器支持：支持的浏览器包括 [!DNL Microsoft Edge]、[!DNL Google Chrome]、[!DNL Firefox]、[!DNL Safari] 和 [!DNL Opera]（最新版本）。**注意：**&#x200B;尽管 Experience Cloud 界面支持这些浏览器，但单个解决方案可能不会支持每个浏览器。（例如，[Analytics](https://docs.adobe.com/content/help/zh-Hans/analytics/admin/sys-reqs.html) 不支持 [!DNL Opera]，[Target](https://docs.adobe.com/help/zh-Hans/target/using/implement-target/before-implement/supported-browsers.html) 不支持 [!DNL Safari]。）
   * （仅限 [!DNL Safari]）域更改可能导致 [!DNL Safari] 中出现 Cookie 问题。取消选中 [!DNL Safari] 隐私首选项中的&#x200B;_阻止跨站跟踪_，将支持跨域的 Cookie（以及所有跨站点体验），并允许 Experience Cloud 在这个新的域上正常运行。
* 更轻松地在组织之间切换，或切换到其他应用程序。
* 改进了产品帮助：[!UICONTROL Experience League] 已集成到产品中，以便帮助搜索还包括来自社区论坛及视频内容的答案。此更改会简化对更多内容的访问，并有助于您充分利用 Experience Cloud。此外，单击&#x200B;**[!UICONTROL 帮助]** > **[!UICONTROL 反馈]**，可报告问题或与 Adobe 分享您的想法。

## ![图标](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

[!UICONTROL Experience Platform]、[!UICONTROL Experience Platform Launch]、[!UICONTROL Identity Service]、Journey Orchestration、Mobile Services 的发行说明及安全公告。

### Journey Orchestration {#journey}

凭借 Adobe Experience Platform，可以实时智能化预测每位客户的需求（无论其旅程通达何处），从而实现跨体验渠道大规模编排客户历程。

* [文档](https://docs.adobe.com/content/help/zh-Hans/journeys/using/journey-orchestration-home.html)
* [发行说明](https://docs.adobe.com/content/help/zh-Hans/journeys/using/release-notes/release-notes.html)
* [操作方法视频](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Mobile Services 和 Mobile SDK {#mobile}

Android 4.18.2（2020 年 4 月 3 日）：

* 应用程序内消息：出于安全原因，SDK 创建的 [!UICONTROL WebViews] 现在将 `setAllowFileAccess` 属性设置为 _false_。

iOS 4.19.2（2020 年 3 月 24 日）：

* 常规：修复了 [!DNL Target] 代码中的一些漏洞。

Unity 4.19.0（2020 年 3 月 10 日）：

* 更新了 [!UICONTROL Unity 插件]以使用 iOS 版本 4.19.0、4.18.0 或 [!DNL Android]。
* 公开了 [!DNL Android] 新的获取方法，以允许处理由 [!DNL Google Play] 反向链接 API 提供的 URL。

### 其他 Experience Platform 发行信息

* [Experience Platform Launch 发行说明](https://docs.adobe.com/content/help/zh-Hans/launch/using/intro/release-notes/current.html)。
* [Experience Platform 发行说明](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [安全公告与建议](https://helpx.adobe.com/cn/security.html)（所有 Adobe 产品）

## ![图标](/assets/analytics.png) [!DNL Analytics] {#analytics}

>[!IMPORTANT]
>
>Adobe Analytics 4月维护版本已移至2020年5月21日。 有关最新的Analytics版本信息，请参阅3 [月版本说明](c-legacy-releases/2020/03122020.md)

* [客户历程分析](#cust-journey)
<!--* [New features in Adobe Analytics](#aa-features)-->
* [Analytics管理员的重要注意事项](#aa-notices) （2020年4月7日更新）
* [AppMeasurement](#appm)
* [新的 Analytics 教程](#tutorials-analytics)

### 客户历程分析 {#cust-journey}

| 功能 | 描述 |
| -----------| ---------- |
| [!UICONTROL Customer Journey Analytics]：自动数据集回填 | 这个新的选项允许您在 [!UICONTROL Customer Journey Analytics] 中，导入某个连接的所有历史数据。[了解更多](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-connections/create-connection.html) |

<!--### New features in Adobe Analytics {#aa-features}

| Feature    | Description  |
| -----------| ---------- |
|Analytics support for [!UICONTROL Experience Edge] |You can now forward data that was sent to [!UICONTROL Experience Edge] to Analytics.|
 |[!UICONTROL Workspace]: Automatically build Freeform Tables from a blank state|Previously, you could not drop components directly into a blank project or blank panel; you had to add a freeform table first. You can now drop components directly into a blank project or panel, and a freeform table will automatically be built for you in a recommended format. Additionally, improvements were made to how mixed component types (e.g. dimensions & metrics) are handled when dropped into a blank freeform table together.|

#### Analytics fixes

* Fixed an issue that caused missing Analytics segment data in Audience Manager. (AN-206221)
* Fixed an issue with [!UICONTROL Data Sources] processing showing the wrong dates. (AN-213604)
* Fixed an issue with classification files not getting uploaded to FTP properly. (AN-214102)
* Fixed an issue with the API method `Segments.Get` not returning a full response. (AN-206210)
* Fixed an issue where table line items were converted to special characters in [!DNL Workspace] PDF download. (AN-196153)
* Fixed an issue with Adobe Analytics API 1.4 call `visattrcustomeridcustomerattributes` not working properly. (AN-186873)
* Fixed an issue with data appearing in reports but missing from the [!UICONTROL Data Feed]. (AN-211923)
* Fixed an issue with being unable to copy [!UICONTROL Product Profile] permissions. (AN-211113)
* Fixed an issue where users with Federated IDs were not able to log in to Report Builder. (AN-207750)
* Fixed an issue with [!UICONTROL AdWords] data not showing in [!UICONTROL Advertising Analytics]. (AN-213249)
* Fixed an issue where classification data did not display in the trended view. (AN-212761)
* Fixed an issue that caused an incorrect published segment count in the [!UICONTROL Segment Manager]. (AN-213374)

#### Additional Analytics fixes

AN-212151; AN-214343; AN-215017; AN-115525; AN-123869; AN-101871; AN-152580; AN-160480; AN-199299; AN-209486; AN-212961; AN-211539; AN-213095; AN-212653; AN-211826; AN-206948; AN-208607; AN-204286; AN-214401; AN-212130; AN-211943; AN-212709; AN-212833; AN-211550; AN-212977; AN-213422; AN-213450; AN-214528; AN-213827; AN-214094; AN-214153; AN-214234; AN-214355; AN-214427; AN-214642; AN-214691; AN-214924; AN-215080; AN-215212 -->

### [!DNL Analytics] 管理员的重要注意事项 {#aa-notices}

| 注意事项 | 添加或更新日期 | 描述 |
| -----------| ---------- | ---------- |
| 在[!UICONTROL 工作区]中更改[!UICONTROL 登入/退出]的计算方式 | 2020 年 4 月 7 日 | 在 [!UICONTROL Analysis Workspace] 中，从 2020 年 3 月起，我们更改了&#x200B;_无_&#x200B;值与[!UICONTROL 登入/退出]的交互方式。由于您现在可以在 [!UICONTROL Analysis Workspace] 中打开和关闭&#x200B;_无_，因此我们会在登入或退出后应用&#x200B;_无_&#x200B;值，而（对于 eVar）过去是在登入或退出前应用。例如，假定访问的第一次点击没有 eVar 值，但第二次点击有。在 [!UICONTROL Reports &amp; Analytics] 中，针对“登入”将显示为&#x200B;_未指定_，但在 [!UICONTROL Analysis Workspace] 中，将显示第二次点击时的值。 |
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
| [Adobe Labs（技术预览版）与 Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/analytics-basics/adobe-labs-technology-previews.html) | Adobe Labs（技术预览版）使您能够接触到新兴技术，发现有价值的灵感，并对 [!DNL Analytics] 将来的功能开发和优先事项施加您自己的影响。 |
| [改进了 Experience Cloud 受众发布](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/integrations/experience-cloud/improved-experience-cloud-audience-publishing.html) | [!UICONTROL Experience Cloud 受众发布]功能得到了改进。现在，发布受众（区段）并使其可用的速度将是以前的六倍。这会将延迟时间从目前的 48 小时缩短到大约 8 小时，并且可能更快，具体视流量和区段大小而定。 |
| [Analysis Workspace 中的多个报表包](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/using-panels/multiple-report-suites-in-analysis-workspace.html) | 通过在面板级别选择报表包，可以在一个[!UICONTROL 工作区]项目中分析多个报表包。这样，您就可以跨不同的数据集进行并排面板分析。 |

有关产品文档，请参阅 [Adobe Analytics 帮助主页](https://docs.adobe.com/content/help/zh-Hans/analytics/landing/home.html)。

## ![图标](/assets/audience-manager.png) Audience Manager {#aam}

Adobe Audience Manager 的新增功能和修复。

| 功能 | 描述 |
| -----------| ---------- |  
| [主要客户支持问题](https://docs.adobe.com/content/help/en/audience-manager/user-guide/top-support-issues/support-issues-overview.html) | 我们在文档门户中添加了一个新部分，其中包括对客户支持团队收到的最常见问题的解答。 |

* 修复了导致为包含移动设备 ID 的区段报告的[可寻址受众](https://docs.adobe.com/content/help/zh-Hans/audience-manager/user-guide/features/addressable-audiences.html)不准确的问题。在此更新之后，您可能会看到[可寻址受众](https://docs.adobe.com/content/help/zh-Hans/audience-manager/user-guide/features/addressable-audiences.html)有所增加。
* 修复了导致 [!UICONTROL Audience Lab] 中的[!UICONTROL 重复测试]和[!UICONTROL 重复分配模板]按钮不工作的问题。(AAM-53388)
* 修复了在将目标配置为导出 UUID 时，[!UICONTROL 匹配率]和[!UICONTROL 区段可寻址受众]显示为 0 的问题。[!UICONTROL 匹配率]和[!UICONTROL 区段可寻址受众]现在显示为 100%。(AAM-51615)
* 修复了包含特殊字符的特征名称被 HTML 编码两次的问题。(AAM-54001)
* 修复了致使某些用户无法从 [!DNL Audience Manager] 用户界面切换到其他 Adobe Experience Cloud 解决方案的问题。(AAM-52917)
* 修复了致使某些用户无法为基于人员的目标创建 SHA256 数据源的问题。(AAM-53525)
* 改进了整个界面的多项辅助功能。（AAM-48986、AAM-49009、AAM-48984、AAM-48939、AAM-48940、AAM-48964、AAM-49032、AAM-49360）

## ![图标](/assets/aem.png) Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新增功能、修复和更新。Adobe 建议那些采用内部部署的客户部署最新的修补程序，以便确保获得更高的稳定性、安全性和性能。

### 自助服务

* **AEM 新闻稿**

   请参阅最新的 [Adobe Experience Manager 新闻稿](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html)。

* **AEM 作为云服务 - 配置 Dynamic Media 云服务**

   在配置 Dynamic Media 云服务时，有一个新的选项可供使用：

   **选择性发布** - 选择此选项时，意味着资产的自动发布仅供安全预览，且资产可以明确发布到 AEM 而不是 DMS7 以供在公共域中交付。

   请参阅[配置 Dynamic Media 云服务](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-service/assets/dynamicmedia/config-dm.html#configuring-dynamic-media-cloud-services)。

* **Dynamic Media - 智能成像**

   更新了整个“智能成像”帮助主题，添加了一些新的信息，包括用于对增加的“智能成像”优化功能进行描述的图像资产示例。

   请参阅[智能成像](https://docs.adobe.com/content/help/zh-Hans/experience-manager-65/assets/dynamic/imaging-faq.html)。

* **配置 Dynamic Media - Scene7 模式**

   现在，**[!UICONTROL 工具 > 云服务]**&#x200B;中的“Dynamic Media 配置”页面上提供了新的“同步所有内容”选项。

   请参阅[创建 Dynamic Media 配置](https://docs.adobe.com/content/help/zh-Hans/experience-manager-65/assets/dynamic/config-dms7.html#configuring-dynamic-media-cloud-services)。

* **AEM Assets Brand Portal 支持 AEM Assets 作为云服务**

   现在，您可以将资产从“AEM Assets 作为云服务”发布到 AEM Assets Brand Portal。

   请参阅[配置 AEM Assets 与 Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/configure-aem-assets-with-brand-portal.html)以及[将资产发布到 Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/publish-to-brand-portal.html)。

* **Adobe Asset Link 2.0 已发布**

   Adobe Asset Link 2.0 支持与多个 AEM 环境一起使用，并支持“AEM 作为云服务”。AEM 支持营销人员在使用 Adobe Asset Link 将资产上传到文件夹时，将资产处理工作流程配置为自动运行。

   请参阅 [Adobe Asset Link](https://helpx.adobe.com/cn/enterprise/using/adobe-asset-link.html)。

### 新的 Experience Manager 教程

| 内容 | 描述 |
| -----------| ---------- |  
| [设置本地 Dispatcher 工具](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/dispatcher-tools.html) | 了解如何在本地配置、验证和模拟 [!UICONTROL Dispatcher]。 |
| [为 AEM 项目设置开发工具](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/development-tools.html) | Adobe Experience Manager (AEM) 开发需要在开发人员计算机上，安装和设置一组必不可少的开发工具。这些工具支持 AEM 项目的开发和构建。 |
| [设置本地 AEM 运行时](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | Adobe Experience Manager (AEM) 可以使用“AEM 作为云服务”SDK 的[!UICONTROL 快速入门] Jar 在本地运行。这允许开发人员在将自定义代码、配置和内容提交到源控件之前，先对它们进行部署和测试，然后将其部署到“AEM 作为云服务”环境。 |
| [导航](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/authoring/navigation.html) | 了解 AEM Assets 导航的基础知识。 |
| [版本](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/collaboration/versions.html) | 了解 AEM 如何创建和维护资产版本。 |
| [AEM - [!DNL Magento] 集成使用[!UICONTROL 商务集成框架 (CIF)]](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/getting-started.html) | 此视频将指导您完成 AEM 与 [!DNL Magento] 之间的集成设置。 |
| [AEM 架构堆栈简介](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-architecture.html) | CIF 项目原型会创建一个最小的 Adobe Experience Manager (AEM) CIF 项目，作为使用 CIF 核心组件的客户项目的起点。 |
| [OSGi 简介](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-osgi.html) | 对 OSGi 的简单介绍。OSGi 是一种针对 Java 应用程序的动态模块化架构，是 Adobe Experience Manager 的基础。 |
| [Java 内容存储库 (JCR) 简介](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-jcr.html) | 对 Adobe Experience Manager 使用的 Java 内容存储库 (JCR) 的简单介绍。 |
| [Sling 简介](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-sling.html) | 对 [!DNL Sling] 的简单介绍，它是一种开源 RESTful Web 框架，是 Adobe Experience Manager 底层技术堆栈的一部分。 |
| [作者层和发布层简介](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-author-publish.html) | 简单介绍作为 Adobe Experience Manager 架构一部分的[!UICONTROL 作者层]和[!UICONTROL 发布层]。 |
| [Dispatcher 简介](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-dispatcher.html) | 简单介绍作为 AEM 架构一部分的 Dispatcher 的功能和特性。 |
| [组件开发简介](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/component-development.html) | 使用 Adobe Experience Manager Sites 来开发组件的概述。包括[!UICONTROL 对话框]、[!UICONTROL Sling 模型]、[!UICONTROL HTL 脚本]和[!UICONTROL 客户端库]的简单介绍。 |
| [AEM 项目原型](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/developing/aem-project-archetype.html) | 一个 AEM 项目，包含用于某个实施的所有代码和配置。AEM [!UICONTROL 项目原型]创建了一个基于最佳实践的、最基础的 Adobe Experience Manager 项目，可用作您自己的 AEM 项目的起点。 |
| [了解核心组件](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/core-components-feature-video-understand.html) | AEM [!UICONTROL 核心组件]是与 Adobe Experience Manager 一起使用的一组标准组件。 |
| [使用 AEM 快速入门 Jar](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/developing/quickstart-jar.html) | 了解如何使用 [!UICONTROL AEM 快速入门 Jar]，在几分钟内安装和运行 Adobe Experience Manager 的本地实例。 |

### 其他帮助资源

* [AEM 作为云服务](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-5.html)
* [AEM 6.4 学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-4.html)
* [AEM 6.3 学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-3.html)
* [AEM 6.2 学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-2.html)
* [Cloud Manager 用户指南](https://helpx.adobe.com/cn/experience-manager/cloud-manager/user-guide.html)
* [更早版本的 AEM 文档](https://helpx.adobe.com/cn/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic 帮助主页](https://docs.adobe.com/content/help/zh-Hans/dynamic-media-classic/using/home.html)
* [Dynamic Media 发行说明](https://marketing.adobe.com/resources/help/zh_CN/s7/release_notes/index.html)
* [Livefyre 发行说明](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## ![图标](/assets/campaign.png) [!DNL Campaign] {#ac}

Adobe Campaign 提供了一种直观、自动的方式，以通过在线和离线营销渠道来交付一对一的消息。您现在可以利用根据客户习惯和喜好所决定的体验，来预测客户的需求。

### Campaign Standard

* [Adobe Campaign Standard 20.2](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/release-notes/release-notes.html)

### 新的 Campaign Standard 教程 {#tutorials-acs}

| 内容 | 描述 |
| -----------| ---------- |  
| [配置文件替换 - 使用目标配置文件测试电子邮件](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/communication-channels/email/profile-substitution.html) | 使用“配置文件替换”功能测试电子邮件。 |

### 其他 Campaign 帮助资源

* Adobe Campaign Standard：[文档](https://helpx.adobe.com/cn/support/campaign/standard.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/release-notes/release-notes.html) - [操作方法视频](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [发行计划](https://helpx.adobe.com/cn/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic：[文档](https://helpx.adobe.com/cn/support/campaign/classic.html) - [发行说明](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [操作方法视频](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Adobe Campaign 控制面板：[文档](https://docs.adobe.com/content/help/zh-Hans/control-panel/using/control-panel-home.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/control-panel/using/release-notes.html)

<!-- ## ![Icon](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Advertising Cloud release notes. -->

## ![图标](/assets/magento.png) [!DNL Magento] {#magento}

有关 Magento 的发行说明，请参阅：

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![图标](/assets/marketo.png) [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] 是一个完整的解决方案，面向希望通过参与复杂购买历程的每个阶段来转变客户体验的潜在客户管理人员和 B2B 营销人员。

### 核心 Marketo Engage 更新

有关更多信息，请参阅 [!DNL Marketo] [发行说明](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720)。

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
