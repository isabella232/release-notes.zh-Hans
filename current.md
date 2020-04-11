---
title: Adobe Experience Cloud 发行说明
description: Experience Cloud 发行说明模板
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 3e124e820e573047298f878cf8cb2bf2a6b7f7dd

---


# 早期访问- Adobe Experience Cloud发行说明- 2020年4月

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
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/zh-Hans/target/using/release-notes/target-release-notes.html) （指向解决方案帮助页面的链接）
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/cn/primetime/user-guide.html) （指向解决方案帮助页面的链接）

在找帮助主页吗？请参阅 [Adobe Experience Cloud 文档](https://docs.adobe.com/content/help/zh-Hans/experience-cloud/user-guides/home.html)。

## ![图标](/assets/adobe.png) Adobe 系统状态 {#status}

[!UICONTROL Adobe 系统状态]提供关于 Adobe 云产品与服务中断和维护事件的详细信息、状态更新以及电子邮件通知。请访问 [status.adobe.com](https://status.adobe.com/) 查看。

**新增功能**

* 凭借您的 Adobe ID，您可以订阅粒度更细的事件通知，具体可达到产品和加载项级别。此外，在我们的最新版本中，自我订阅过程现在建议根据您的产品权利选择产品和服务。 这应会减少创建订阅所需的决策或点击次数，从而简化订阅流程，最重要的是，应在您的收件箱中发送更相关的通知。 要开始使用，请访问 [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit)。

**当前可用的新增功能和增强功能**

| 功能 | 描述 |
| -----------| ---------- |
| 基于授权的个性化订阅 | <ul><li>根据用户的DX授权预选订阅推荐。</li><li>建议的订阅在产品列表顶部突出显示，以便快速可视化。</li><li>收到的电子邮件通知与用户的产品授权相关。</li></ul> |
| 更轻松地管理订阅 | <ul><li>**[!UICONTROL 管理订阅]** ，具有管理产品和事件订阅的全新用户体验。</li><li>新增选项，可分别视图和编辑产品和事件订阅。</li><li>通过 **[!UICONTROL 删除]** ，您可以取消订阅产品或事件订阅。</li><li>产品订阅可 **[!UICONTROL 使用一键]** “取消订阅全部”选项。</li><li>UX支持19种语言的Web/移动／平板电脑界面和本地化。</li></ul> |

## ![图标](/assets/ec_appicon_24.png) Experience Cloud 界面和核心服务 {#ecloud}

Experience Cloud界面中的新增功能和修复，包括管理和核心服务(客户属性、受众、触发器、Cookie等):

* 已弃 [!UICONTROL 用Experience Cloud] Feed页。 (EXC-8505)
* Experience Cloud登录页面已更新以反映新的品牌元素。 (EXC-10747)

有关产品文档，请参阅 [Experience Cloud](https://docs.adobe.com/content/help/zh-Hans/core-services/interface/experience-cloud.html) 帮助。

## ![图标](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

[!UICONTROL Experience Platform]、[!UICONTROL Experience Platform Launch]、[!UICONTROL Identity Service]、Journey Orchestration、Mobile Services 的发行说明及安全公告。

### Journey Orchestration {#journey}

凭借 Adobe Experience Platform，可以实时智能化预测每位客户的需求（无论其旅程通达何处），从而实现跨体验渠道大规模编排客户旅程。

* [文档](https://docs.adobe.com/content/help/zh-Hans/journeys/using/journey-orchestration-home.html)
* [发行说明](https://docs.adobe.com/content/help/zh-Hans/journeys/using/release-notes/release-notes.html)
* [操作方法视频](https://docs.adobe.com/content/help/zh-Hans/platform-learn/tutorials/journey-orchestration/introduction.html)

### Mobile Services 和 Mobile SDK {#mobile}

Android 4.18.2（2020年4月3日）:

* 应用程序内消息传递：出于安全原因， [!UICONTROL SDK创建的WebViews] 现在将属性 `setAllowFileAccess` 设置为 _false_。

iOS 4.19.2（2020年3月24日）:

* 常规：修复了代码中的一些 [!DNL Target] 漏洞。

Unity 4.19.0（2020年3月10日）:

* 更 [!UICONTROL 新了Unity Plugin] ，以使用iOS版本4.19.0和4.18.0或 [!DNL Android]。
* 公开了新的获取方 [!DNL Android] 法，用于允许处理由推荐人API提供的 [!DNL Google Play] URL。

### 其他Experience Platform版本信息

* [Experience Platform Launch发行说明](https://docs.adobe.com/content/help/zh-Hans/launch/using/intro/release-notes/current.html)。
* [Experience Platform发行说明](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [安全公告与建议](https://helpx.adobe.com/cn/security.html)（所有 Adobe 产品）

## ![图标](/assets/analytics.png) [!DNL Analytics] {#analytics}

发行日期：**2020 年 4 月 16 日**

* [Adobe Analytics 中的新增功能、增强功能和修复](#aa-features)
* [Analytics 管理员的重要注意事项](#aa-notices)（更新日期：2020 年 4 月 7 日）
* [AppMeasurement](#appm)
* [新的Analytics教程](#tutorials-analytics)

### Adobe Analytics 中的新增功能、增强功能和修复 {#aa-features}

| 功能 | 描述 |
| -----------| ---------- |
| [!UICONTROL 客户旅程分析]:自动 [!UICONTROL 化数据集回填] | 此新选项允许您在客户旅程分析中导入连接的所 [!UICONTROL 有历史数据]。 （后续文档） |
| 对 [!UICONTROL Experience Edge的分析支持] | 您现在可以将发送到 [!UICONTROL Experience Edge的数据转发] 到Analytics。 |
| [!UICONTROL 工作区]:从空白状态自动构建自由格式表 | 以前，不能将组件直接放入空白项目或空白面板；您必须先添加自由格式表。 您现在可以将组件直接放到空白项目或面板中，并且将自动以推荐的格式为您构建自由格式表。 此外，还改进了将混合组件类型（如维度和度量）一起放入空白自由格式表中时的处理方式。 |

#### 分析修复

* 修复了导致受众管理器中缺少Analytics区段数据的问题。 (AN-206221)
* 修复了数据源处 [!UICONTROL 理显示错误日期] 的问题。 (AN-213604)
* 修复了分类文件无法正确上传到FTP的问题。 (AN-214102)
* 修复了API方法不返回完 `Segments.Get` 整响应的问题。 (AN-206210)
* 修复了表行项目在 [!DNL Workspace] PDF下载中转换为特殊字符的问题。 (AN-196153)
* 修复了Adobe Analytics API 1.4调用无法正常 `visattrcustomeridcustomerattributes` 工作的问题。 (AN-186873)
* 修复了数据显示在报表中但数据馈送中缺失的 [!UICONTROL 问题]。 (AN-211923)
* 修复了无法复制产品用户档案权限 [!UICONTROL 的问题] 。 (AN-211113)
* 修复了具有Federated ID的用户无法登录Report Builder的问题。 (AN-207750)
* 修复了AdWords数 [!UICONTROL 据在][!UICONTROL Advertising Analytics中不显示的]问题。 (AN-213249)
* 修复了分类数据未在趋势视图中显示的问题。 (AN-212761)
* 修复了导致区段管理器中发布的区段计数不 [!UICONTROL 正确的问题]。 (AN-213374)

#### 其他Analytics修复

AN-212151;AN-214343;AN-215017;AN-115525;AN-123869;AN-101871;AN-152580;AN-160480;AN-199299;AN-209486;AN-212961;AN-211539;AN-213095;AN-212653;AN-211826;AN-206948;AN-208607;AN-204286;AN-214401;AN-212130;AN-211943;AN-212709;AN-212833;AN-211550;AN-212977;AN-213422;AN-213450;AN-214528;AN-213827;AN-214094;AN-214153;AN-214234;AN-214355;AN-214427;AN-214642;AN-214691;AN-214924;AN-215080;AN-215212

### [!DNL Analytics] 管理员的重要注意事项 {#aa-notices}

| 注意事项 | 添加或更新日期 | 描述 |
| -----------| ---------- | ---------- |
| Change to how [!UICONTROL Entries/Exits] are calculated in [!UICONTROL Workspace] | 2020 年 4 月 7 日 | In [!UICONTROL Analysis Workspace], as of March 2020, we have changed how the _None_ value interacts with [!UICONTROL Entries/Exits]. Because you can now turn _Nones_ on and off in [!UICONTROL Analysis Workspace], we apply the _None_ value after the entry or exit, whereas (for eVars) it used to be applied before. 例如，假设访问的第一次点击对eVar没有任何值，但第二次点击对eVar没有。 In [!UICONTROL Reports &amp; Analytics] it will show up as _Unspecified_ for the Entry, but in [!UICONTROL Analysis Workspace] it will show up as the value on the second hit. |
| **[!UICONTROL 转化级别]**&#x200B;设置生命周期终止 | 2020 年 3 月 3 日 | The non-functioning [Conversion Level](https://docs.adobe.com/content/help/zh-Hans/analytics/admin/admin-tools/general-acct-settings-admin.html) setting in **[!UICONTROL Admin Tools]** > **[!UICONTROL Report Suites]** > **[!UICONTROL General Account Settings]** will be removed from the interface on March 12, 2020. |
| **[!UICONTROL 功能板存档]**&#x200B;生命周期终止 | 2020 年 3 月 27 日 | 自 2020 年 10 月起，在 [!UICONTROL Reports &amp; Analytics] 中，位于&#x200B;**[!UICONTROL 管理功能板]**&#x200B;下方的&#x200B;**[!UICONTROL 查看存档]**&#x200B;将不再可用。 |
| 停止支持 TLS 1.1 | 2019 年 10 月 3 日 | 我们一直不懈努力，致力于维持最高安全标准并提升客户数据安全。为此，Adobe Analytics 对 TLS 1.1 的支持将持续到 2020 年 3 月 31 日，在这之后将不再支持 TLS 1.1。 |
| 新的 Adobe Analytics 域 | 2019 年 12 月 18 日 | 自 2020 年 1 月 16 日起，Adobe Analytics 将开始转移到新域 - `https://experience.adobe.com/analytics.`<br>**注意：**这项更改适用于使用 Adobe ID 或 Enterprise ID 访问 Analytics 的所有用户。<ul><li>域更改可能会导致在 Safari 中加载 Analytics 时出现 Cookie 问题。取消选中 [!DNL Safari] 隐私首选项中的&#x200B;_阻止跨站跟踪_，将支持跨域的 Cookie（以及所有跨站点体验），并允许 Analytics 在这个新的 Adobe Experience Cloud 域上运行。您可以使用其他浏览器而不会出现任何问题，因为这项更改仅影响 [!DNL Safari] 用户。</li><li>[在特定情况下](https://docs.adobe.com/content/help/zh-Hans/analytics/analyze/activity-map/activity-map.html)，域更改可能会导致某些客户的 [!UICONTROL Activity Map] 停止工作。</li></ul> |
| 生命周期结束 - Analytics 旧版 API | 2020 年 1 月 9 日 | 2020 年 11 月，以下 Analytics 旧版 API 服务将停止使用并关闭。当前使用这些服务构建的集成将会停止工作。 <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>旧版 OAuth 身份验证（OAuth 和 JWT）</li></ul>我们提供了[旧版 API EOL 常见问题解答](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)，以帮助回答您的问题并提供有关如何继续的指导。使用这些服务的 API 集成可以迁移到 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 或 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。旧版 OAuth 帐户可迁移到 [Adobe IO](https://console.adobe.io/home?mv=email) Analytics 集成帐户，该帐户可用于访问 1.4 Analytics API 和 2.0 Analytics API。 |
| 圣何塞 FTP 中转站停止为伦敦和新加坡提供支持 | 2020 年 7 月 | 对于位于伦敦和新加坡的客户，我们将不再提供伦敦或新加坡与圣何塞数据中心 [ftp.omniture.com](ftp://ftp.omniture.com/) 之间的数据中转支持。<br/><ul><li>伦敦客户，请使用 [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>新加坡客户，请使用 [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Ad Hoc Analysis 生命周期终止 | 2018 年 8 月 6 日 | Adobe 宣布计划终止 Ad Hoc Analysis 生命周期。确定终止日期后，Adobe 会立即与大家共享此信息。有关更多信息，请参阅[探索工作区](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)。 |

### [!DNL AppMeasurement] {#appm}

请参阅 [AppMeasurement for Javascript 发行说明](https://docs.adobe.com/content/help/zh-Hans/analytics/implementation/appmeasurement-updates.html)。版本 2.20.0 于 2020 年 3 月 5 日发布。

### 新的Analytics教程 {#tutorials-analytics}

| 内容 | 描述 |
| -----------| ---------- |
| [Adobe Labs(技术预览)与Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/analytics-basics/adobe-labs-technology-previews.html) | Adobe实验室(技术预览)使您能够与新兴技术互动，发现宝贵的洞察，并影响未来的功能开发和 [!DNL Analytics] 优先事项。 |
| [改进的Experience Cloud受众发布](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/integrations/experience-cloud/improved-experience-cloud-audience-publishing.html) | 对 [!UICONTROL Experience Cloud受众发布进行了改进]。 您现在可以发布受众（区段），并将其发布速度提高六倍。 这会根据流量和区段大小将当前延迟时间从48小时缩短到大约8小时，并可能加快。 |
| [分析工作区中的多个报表包](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/using-panels/multiple-report-suites-in-analysis-workspace.html) | 通过在面板级别选择报表包，可以在单  个Workspace项目中分析多个报表包。 这样，您就可以跨不同的数据集进行并排面板分析。 |

有关 [产品文档，请参阅Adobe Analytics帮助主页](https://docs.adobe.com/content/help/zh-Hans/analytics/landing/home.html) 。

## ![图标](/assets/audience-manager.png) Audience Manager {#aam}

Adobe受众管理器的新增功能和修复：

* 修复了导致重复实验 [!UICONTROL 室中的受众测试][!UICONTROL 和重复分配模板] 按钮不工作的问题  。 (AAM-53388)
* 修复了在将目标配 [!UICONTROL 置为导出UUID时] ，匹配率  和段可寻址受众显示为0的问题。 “匹 [!UICONTROL 配率] ”和“ [!UICONTROL 区段可寻址受众] ”现在显示为100%。 (AAM-51615)
* 修复了包含特殊字符的特征名称被HTML编码两次的问题。 (AAM-54001)
* 修复了阻止某些用户从用户界面切换到其他Adobe Experience Cloud解决方案 [!DNL Audience Manager] 的问题。 (AAM-52917)
* 修复了阻止某些用户为基于人员的目标创建SHA256数据源的问题。 (AAM-53525)
* 跨界面的多种辅助功能改进。 （AAM-48986、AAM-49009、AAM-48984、AAM-48939、AAM-48940、AAM-48964、AAM-49032、AAM-49360）

## ![图标](/assets/aem.png) Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新增功能、修复和更新。Adobe 建议那些采用内部部署的客户部署最新的修补程序，以便确保获得更高的稳定性、安全性和性能。

### 自助服务

* **AEM新闻稿**

   请参阅最新 [的Adobe Experience Manager新闻快讯](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html)。

* **AEM作为云服务——配置Dynamic Media Cloud服务**

   在配置Dynamic Media Cloud服务时，可以使用新选项：

   **选择性发布** -当您选择此选项时，这意味着资产仅自动发布以安全预览，并且可以显式发布到AEM，而不发布到DMS7以在公共域中投放。

   请参 [阅配置Dynamic Media Cloud服务](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/config-dm.html#configuring-dynamic-media-cloud-services)。

* **动态媒体——智能成像**

   更新了整个“智能成像帮助”主题中的新信息，包括描述所添加智能成像优化的图像资产示例。

   请参阅 [智能成像](https://docs.adobe.com/content/help/en/experience-manager-65/assets/dynamic/imaging-faq.html)。

* **配置Dynamic Media - Scene7模式**

   现在，“工具”>“云服务”中的“Dynamic Media配置”页面上提供了新的“同步所 **[!UICONTROL 有内容”选项]**。

   请参 [阅创建Dynamic Media配置](https://docs.adobe.com/content/help/en/experience-manager-65/assets/dynamic/config-dms7.html#configuring-dynamic-media-cloud-services)。

* **AEM Assets Brand Portal支持AEM Assets作为云服务**

   您现在可以将资产作为云服务从AEM资产发布到AEM资产品牌门户。

   请参 [阅配置AEM资产与Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/configure-aem-assets-with-brand-portal.html) , [以及将资产发布到Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/publish-to-brand-portal.html)。

* **已发布Adobe Asset Link 2.0**

   Adobe Asset Link 2.0支持与多个AEM环境一起使用，并支持AEM作为云服务。 AEM支持营销人员在使用Adobe资产链接将资产上传到文件夹时，对资产处理工作流程进行自动运行的需要。

   See [Adobe Asset Link](https://helpx.adobe.com/cn/enterprise/using/adobe-asset-link.html).

### 新的Experience Manager教程

| 内容 | 描述 |
| -----------| ---------- |  
| [设置本地调度程序工具](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/dispatcher-tools.html) | 了解如何简化本地配置、验证和模拟 [!UICONTROL Dispatcher] 。 |
| [为AEM项目设置开发工具](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/development-tools.html) | Adobe Experience Manager(AEM)开发需要在开发人员计算机上安装和设置最少的开发工具集。 这些工具支持AEM项目的开发和构建。 |
| [设置本地AEM运行时](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | Adobe Experience Manager(AEM)可以使用AEM作为Cloud Service SDK的QuickStart Jar在本地运 [!UICONTROL 行]。 这允许开发人员在将自定义代码、配置和内容提交到源控件之前，先部署和测试这些代码、配置和内容，然后将其作为云服务环境部署到AEM。 |
| [导航](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/authoring/navigation.html) | 浏览AEM资产导航的基础知识。 |
| [版本](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/collaboration/versions.html) | 了解AEM如何创建和维护资产版本。 |
| [AEM - [!DNL Magento]使用商务集成框 [!UICONTROL 架进行集成]](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/getting-started.html) | 此视频将指导您完成AEM与之间集成的设置 [!DNL Magento]。 |
| [AEM架构堆栈简介](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-architecture.html) | CIF项目原型为使用CIF核心组件的客户项目创建了最小的Adobe Experience Manager(AEM)CIF项目，作为起点。 |
| [OSGi简介](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-osgi.html) | OSGi简介，它是Java应用程序的动态模块化架构，是Adobe Experience Manager的基础。 |
| [Java内容存储库(JCR)简介](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-jcr.html) | Adobe Experience Manager使用的[Java内容存储库(JCR)简介。 |
| [Sling简介](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-sling.html) | 介绍作为Adobe Experience Manager [!DNL Sling]底层技术堆栈的一部分的开源RESTful Web框架。 |
| [作者层和发布层简介](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-author-publish.html) | 作为Adobe Experience Manager体 [!UICONTROL 系结构的一部分] ，介绍作者层和发布层。 |
| [Dispatcher简介](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-dispatcher.html) | 介绍作为AEM体系结构一部分的调度程序的功能和功能。 |
| [组件开发简介](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/component-development.html) | 使用Adobe Experience Manager Sites开发组件的概述。 包括对 [!UICONTROL 话框]、 [!UICONTROL Sling模型]、 [!UICONTROL HTL脚本和]Side Libraries的介绍。 |
| [AEM 项目原型](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/developing/aem-project-archetype.html) | AEM项目包含实施的所有代码和配置。 The AEM [!UICONTROL Project Archetype] creates a minimal, best-practices-based Adobe Experience Manager project as a starting point for your own AEM projects. |
| [了解核心组件](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/core-components-feature-video-understand.html) | AEM核 [!UICONTROL 心组件] ，是与Adobe Experience Manager一起使用的标准集组件。 |
| [使用AEM快速入门Jar](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/developing/quickstart-jar.html) | 了解如何使用 [!UICONTROL AEM Quickstart jar在几分钟内安装和运行Adobe Experience Manager的本地实例]。 |

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

### 新的Campaign Standard教程 {#tutorials-acs}

| 内容 | 描述 |
| -----------| ---------- |  
| [用户档案替代——使用目标用户档案测试电子邮件](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/communication-channels/email/profile-substitution.html) | 使用用户档案替换功能测试电子邮件。 |

### 其他活动帮助资源

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

有关更 [!DNL Marketo] 多信息， [请参阅发行说明](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) 。

### 即将推出的功能

本季度将发布以下功能：

| 功能 | 描述 |
|------|---------|
| [!DNL Bizible] | <ul><li>新的基于帐户的分段</li><li>保存特定于功能板的过滤器</li><li>将 Bizible 功能板导出为 PDF</li></ul> |
| Sales Connect | 撰写窗口和命令中心更新/增强功能 |

### 公告

**Marketo Engage 成功中心：**&#x200B;于 2020 年 2 月推出。成功中心是一个产品内帮助中心，允许您搜索产品文档和社区、启动操作指南、访问采用内容等。注意：此功能将作为测试版在澳新银行推出，并将在本季度晚些时候推出到北美洲。

### 弃用

* **资产API &quot;_method&quot;参数：** 2020年9月之后，资产API端点将不再接受在POST `_method` 主体中通过查询参数以绕过URI长度限制。
* **弃用 Internet Explorer 支持：**&#x200B;从 2020 年 7 月 31 日发行的 7 月版本开始，Internet Explorer 将不再支持 Marketo Engage 用户界面。

有关累积和历史发行说明，请参阅 [Marketo 发行说明](https://docs.marketo.com/x/CgA6Ag)。
