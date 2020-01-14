---
title: Adobe Experience Cloud 发行说明
description: Experience Cloud 发行说明模板
doc-type: release notes
last-update: January 2020
author: mfrei
translation-type: tm+mt
source-git-commit: b0f2fe07102a20e343f69b1c156f48ca4f284966

---


# 早期访问- Adobe Experience cloud发行说明- 2020年1月

Adobe Experience Cloud 的新增功能和修复。

>[!IMPORTANT]
>本页包含预发行内容，并且在每个产品的计划发行之前可能会发生更改。

>[!NOTE]
>若要通过电子邮件接收有关即将发行的版本的通知，请订阅 [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html)。对于在版本发行之后发布的新信息，将使用发布日期进行标记。

**发布日期：2020年1月16日**

* [Adobe系统状态](#status)
* [Experience cloud界面和核心服务](#ecloud)
* [Experience Platform](#platform)
* [Mobile services和Mobile SDK](#mobile)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html)（链接到解决方案帮助）
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html)（链接到解决方案帮助）
* [!DNL Advertising Cloud](#adcloud)

在找帮助主页吗？请参阅 [Adobe Experience Cloud 文档](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html)。

## Adobe System Status {#status}

[!UICONTROL Adobe System Status提供有关Adobe云产品和服务中断、中断和维护事件的详细信息] 、状态更新和电子邮件通知。 请访问 [status.adobe.com查看](https://status.adobe.com/)。

**新增功能**

* 使用Adobe ID，您可以根据产品、地区和活动首选项订阅活动通知。 配置订阅首选项的用户在打开、更新或关闭时，仅会收到相关产品事件和维护事件的通知。 status.adobe.com/subscriptions快速入 [门](https://status.adobe.com/proactive-notifications/subscriptions/edit)。

**当前提供的新增功能和增强功能**

| 功能 | 描述 |
| -----------| ---------- |
| 订阅主动式电子邮件通知 | <ul><li>支持Experience Cloud、Creative Cloud、Document Cloud、Adobe Experience platform和Adobe服务</li><li>支持地区和事件类型首选项</li></ul> |
| 管理通知首选项 | <ul><li>随时编辑和保存通知首选项</li><li>随时取消订阅通知</li></ul> |
| 获得个性化、更快的电子邮件发送 | <ul><li>在打开、更新或关闭活动后，会立即发送活动通知</li><li>仅接收与您配置的首选项匹配的相关事件通知</li><li>根据帐户首选项中配置的语言接收本地化通知</li></ul> |
| 获取个性化的产品内通知 | <ul><li>与通知首选项和产品授权匹配的事件显示在“公告”面板中</li></ul> |

## Experience Cloud interface and core services {#ecloud}

Experience cloud界面中的新增功能和修复，包括管理和核心服务（客户属性、受众、触发器、Cookie等）。

### 统一的产品域

Adobe将更新域和界面标题，以统一和改进您在所有Experience cloud应用程序中的体验。 这些增强功能旨在以小而重要的方式简化您的体验。 这些增强不会更改您当前的工作流程。

更新包括：

* 新的解决方案URL:所 `experience.adobe.com/<application name>.` 有产品最终都会采用此URL模式。 寻找新的URL以在月内生效。
* 更轻松地在组织之间切换或切换到其他应用程序。
* 改进的产品帮助：Experience League  （体验联盟）已集成到产品中，因此帮助搜索还包括来自社区论坛和视频内容的结果。 此更改简化了对更多内容的访问，并有助于您充分利用Experience Cloud。 此外，单击“ **[!UICONTROL 帮助]**>**[!UICONTROL &#x200B;反馈]** ”，报告问题或与Adobe分享您的想法。
* 改进的通知：“通 [!UICONTROL 知] ”下拉菜单现在有两个选项卡，一个用于您自己的产品通知，一个用于全局产品通知。

**注意：** 源 [!UICONTROL 页面] （2020年1月已弃用）。 请查看产品内的弃用通知。

有关产品文档，请参阅 [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html)。

### Experience Cloud Cookie

Adobe正在调整 `same-site` cookies设置，以准备Chrome将在Chrome 80中进行的更改（将于2020年2月发布）。

除非您使用CNAME收集第一方数据，但在多个域（友好的第三方域）中使用该CNAME，并且您不使用Experience Cloud（访客）ID服务，否则您无需进行更改。 在Chrome 80版本中，Chrome会自动为Analytics访客ID cookies提供SameSite值，以防 `Lax,` 其在您的其他域上使用。 如果要继续跨域使用CNAME，您必须联系Adobe客户服务中心并请求他们将您的CNAME的SameSite值更改为 `None.`

请注意，无论您是否在使用Experience Cloud ID服务，Adobe建议您为每个域使用单独的CNAME。

[更多…](https://medium.com/adobetech/adobe-experience-cloud-cookie-updates-for-google-chrome-19ad67cf1598)

## Experience Platform {#platform}

Experience Platform、Experience Platform Launch、Identity Service 和安全公告的发行说明。

* [Experience Platform 发行说明](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [安全公告与建议](https://helpx.adobe.com/security.html)（所有 Adobe 产品）

### Experience Platform Launch {#launch}

有关发行说明和产品文档，请参阅 [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html)。

## Mobile Services and Mobile SDKs {#mobile}

2020年1月16日：版本4.18.0

* 客户获取——添加了一个新的API, `Analytics.processGooglePlayInstallReferrerUrl(final String url)`用于支持安 [!DNL Google Play] 装引用API。

有关安装引用API的详细信息，请参阅 [Still Using InstallBroadcast? 在2020年3月1日之前切换到Play Referrer API](https://android-developers.googleblog.com/2019/11/still-using-installbroadcast-switch-to.html)。

## [!DNL Analytics] {#analytics}

Adobe Analytics 中的新增功能和修复：

* [Adobe Analytics 中的新增功能、增强功能和修复](#aa-features)
* [Analytics 管理员的重要注意事项](#aa-notices)
* [AppMeasurement](#appm)

有关产品文档，请参阅 [Adobe Analytics 帮助主页](https://docs.adobe.com/content/help/en/analytics/landing/home.html)。

### Adobe Analytics 中的新增功能、增强功能和修复 {#aa-features}

| 功能 | 描述 |
| -----------| ---------- | 
| Analysis Workspace —— 自由格式表生成器 | 启用Table Builder后，您可以拖放许多维度、细分、指标和细分，以构建可解答更复杂业务问题的表。 数据不会立即更新。 相反，在单击“构建” **[!UICONTROL 后会进行更新]**，这样在知道要构建什么表时，可节省时间。 此外，此功能还提供：<ul><li>**预览**:您可以在花费时间渲染真实数据之前预览表的格式。</li><li>**灵活的行和细分设置**:您可以为每个维行设置行和细分级别。 以前，Workspace强加了默认值，这些默认值在返回数据之前无法更改。</li><li>**按职位划分**:您可以将维行设置为始终按位 _置而不是按特_ 定项目 __ （默认值）细分。</li><li>**手动静态行排序**:您可以手动对静态行排序，以使表行完全按需显示。 以前，静态行只能按度量列或字母顺序排序。</li></ul>当该功能在1月晚些时候发布时，将发布相关文档。 |
| 用于 [!UICONTROL 跨设备分析] (CDA)的新的已识别状态维度 | 我们正在向CDA虚拟报表包中添 [!UICONTROL 加一个名为] “已识别状态”的新维度。 维有两个可能的值， _Insigned_ （已识别） _和Unisigned（未识别）_。 _已识别_ ：表示人物已通过设备图表识别。 _未识别_ ，表示设备图表未识别此人。<br>这意味着CDA用户现在可以创建计算度量，如设备图覆盖率 ，它描述了虚拟报告套件中通过设备图了解的人数。 此指标有助于排除CDA压缩率故障。 如果识别出的人数很少，则拼接的级别将较低。 |
| 数据仓库API中的VRS支持 | 虚拟报表包现在可通过数据仓库API使用。 以前，它们只能通过数据仓库UI使用。 使用Data Warehouse API时，您现在可以查看和查询虚拟报表包，但前提是应用于虚拟报表包的区段与数据仓库兼容。 |
| 隐私服务 API：CCPA | 《加州消费者隐私法案》(CCPA) 加强了对美国加利福尼亚州居民的隐私权和消费者保护。本法自2020年1月1日起生效。<br><br/>CCPA 为加州居民提供了新的数据隐私权，例如，访问和删除个人数据的权利，知晓其个人数据是否被出售或披露（包括披露给谁）的权利，以及拒绝出售其个人数据的权利。<br><br/>隐私服务支持拒绝销售个人数据的请求。<br><br/>隐私服务以前是GDPR服务，并保留以前的所有功能，现在扩展为支持CCPA。<br/><br/>[Analytics 中的 CCPA](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/an-ccpa-overview.html)<br><br/>[隐私服务概述](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |

#### 修复

* 修复了警报通知无法发送到埃及电话号码的问题。 (AN-197079)
* 修复了与 [!DNL DFA Data Connector]（AN-193281、AN-193075、AN-193484、AN-193737）
* [!UICONTROL 报告与分析]:修复了“产品转化漏斗”报表断开并显示不明确数字的问题。 (AN-186901)
* 修复了阻止用户在基于具有新“分类”架构的报表包的Workspace项目中切换报表包的问题。 (AN-199076)
* 修复了“计算量度”中的“累 [!UICONTROL 积] ”功能  无法正常工作的问题。 (AN-184257)

### [!DNL Analytics] 管理员的重要注意事项 {#aa-notices}

| 注意 | 添加或更新日期 | 描述 |
| -----------| ---------- | ---------- |
| 新的 Adobe Analytics 域 | 2019 年 12 月 18 日 | 2020年1月16日，Adobe Analytics将开始移至新域——注 `https://experience.adobe.com/analytics.`<br>**意&#x200B;**:此更改适用于使用其Adobe ID或Enterprise ID访问Analytics的所有用户。<ul><li>域更改可能在Safari中加载Analytics时导致Cookie问题。 Unchecking _Prevent cross-site tracking_ in the Safari Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Analytics to function on this new Adobe Experience Cloud domain. 您可以无问题地使用其他浏览器，因为这仅影响Safari用户。</li><li>在特定情况下，域更改可 [!UICONTROL 能会导致Activity Map] （活动图）停 [止为某些客户工作](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html)。</li></ul> |
| 生命结束- Analytics Legacy API | 2020 年 1 月 9 日 | 在2020年11月，以下Analytics Legacy API服务将停止使用并关闭。 使用这些服务构建的当前集成将停止工作。 <ul><li>1.3分析API</li><li>1.4 SOAP分析API</li><li>旧版OAuth身份验证（OAuth和JWT）</li></ul>我们提供了 [Legacy API EOL常见问题解答](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) ，以帮助回答您的问题并提供有关如何继续的指导。 使用这些服务的API集成可以迁移到 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email)[或2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。 旧版OAuth帐户可迁移到 [Adobe IO](https://console.adobe.io/home?mv=email) Analytics集成帐户，该帐户可用于访问1.4 Analytics API和2.0 Analytics API。 |
| **[!UICONTROL 查看存档]** 选项生命周期终止 | 2019 年 10 月 30 日 | 2020 年 1 月，将终止使用功能板管理器（**[!UICONTROL 组件 > 功能板]**）中的 **[!UICONTROL &#x200B;查看存档]** 选项。 |
| **[!UICONTROL 强制 IP 登录限制]** 选项生命周期终止 | 2019 年 10 月 30 日 | 2020 年 1 月，将终止使用&#x200B;**[!UICONTROL 管理 > 公司设置 > 安全]** 菜单下的 IP 登录白名单（**[!UICONTROL &#x200B;强制 IP 登录限制]**）功能。 |
| 停止支持 TLS 1.1 | 2019 年 10 月 3 日 | 我们一直不懈努力，致力于维持最高安全标准并提升客户数据安全。为此，Adobe Analytics 对 TLS 1.1 的支持将持续到 2020 年 3 月 31 日，在这之后将不再支持 TLS 1.1。 |
| 圣何塞 FTP 中转站停止为伦敦和新加坡提供支持 | 2020 年 7 月 | 对于位于伦敦和新加坡的客户，我们将不再提供伦敦或新加坡与圣何塞数据中心 [ftp.omniture.com](ftp://ftp.omniture.com/) 之间的数据中转支持。<br/><ul><li>伦敦客户，请使用 [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>新加坡客户，请使用 [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| 面向 Analytics 用户的 `createDate` 字段即将发生变化 | 2019 年 8 月 30 日 | In October or November 2019, the `createDate` field for Analytics users was updated from US Pacific Time to a correctly formatted date and time value with time zone information.(AN-183468) |

### [!DNL AppMeasurement] {#appm}

请参阅 [AppMeasurement for Javascript 发行说明](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html)。

## Audience Manager {#aam}

Audience manager中添加的修复和功能。

### Audience Manager 中的新增功能、增强功能和修复 {#aam-features}

| 功能 | 描述 |
| -----------| ---------- |
| [加利福尼亚消费者隐私法(CCPA)支持和隐私文档大修](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy.html) | 2020 [年1月1日生效的《加利福尼亚消费者隐私法》(California Consumer Privacy Act, CCPA)](https://www.caprivacy.org/about)(California Consumer Privacy Act, CCPA)为加利福尼亚州居民提供了有关其个人信息的新权利，并对在加利福尼亚从事业务的某些实体强制实施数据保护责任。 <br><br> Audience manager通过 [Adobe Experience Platform Privacy Service](https://www.adobe.io/apis/experienceplatform/home/services/privacy-service.html) （用于数据访问和删除请求）等隐私工具帮助您遵守隐私法规规定的义务。 <br><br> 我们已更新了当 [前的退出管理流程](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy-requests.html#opt-out-requests) ，以包括退出任何声明的ID（例如CRM ID）。 如果由声明的ID选择退出，则声明的ID和最后一个链接的设备将选择退出Audience manager数据收集。 选择退出请求现在还会将取消细分请求发送 [给支持此功能的目标合作伙伴](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy-requests.html#aam-partners-with-unsegmentation) ，无论是批量还是实时。 <br><br> 此外，我们还重新设计了 [Data Security](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-security.html)、 [Data Privacy](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy.html), and [](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-governance.html) Data Governance文档，使您能更轻松地找到符合上述法规要求的信息。 |

### 修复和改进 {#aam-fixes-and-improvements}

* 修复了创建目标工作 [!UICONTROL 流中的一个问题，该问题导致在选择“集成平台] ”作为“类别”后， **[!UICONTROL基本信息]** 部分会消失，而且无法完成该工作流。 (AAM-52397, AAM-52414)
* 我们修复了在Apple Safari和Mozilla Firefox [!UICONTROL 浏览器中不加载“创建／编辑目标] ”页面的错误。 (AAM-51784)

## Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新增功能、修复和更新。Adobe 建议那些采用内部部署的客户部署最新的修补程序，以便确保获得更高的稳定性、安全性和性能。

### 产品维护

* **AEM 6.5.3.0** AEM 6.5,Service Pack 3.0（2019年12月12日发布的6.5.3.0）是一项重要更新，其中包括自2019年4月AEM 6.5正式发布以来发布的关键客户修复。
   * [发行说明](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [AEM 表单 CFP 版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.7.0**

   AEM 6.4,Service Pack 7.0（2019年12月12日发布的6.4.7.0）是一个重要更新，其中包括自2018年4月AEM 6.4正式发布以来发布的关键客户修复。
   * [发行说明](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [AEM 表单 CFP 版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.3.3.7**

   AEM 6.3、Service Pack 3、Cumulative Fix Pack 7（2019年12月12日发布的6.3.3.7）是一项重要更新，其中包括自2017年4月AEM 6.3通用版本发布以来发布的关键客户修复。
   * [发行说明](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [AEM 表单 CFP 版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 桌面应用程序 2.0.1.1**

   AEM桌面应用程序2.0.1.1提供了使用Okta进行单点登录的更新，并能够在“首选项”中指定临时文件的位置。 在此版本中，不再支持桌面应用程序2.x的AEM 6.3.x。
   * [发行说明](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/release-notes.html)

* **Adobe Asset Link 1.1结束对AEM 6.3.x的支持**

   自2019年4月起，Adobe Asset link中已弃用对AEM 6.3.x的支持。 从2020年1月13日起，Adobe Asset Link 1.1将取消对AEM 6.3.x的支持。
   * [Adobe Asset Link](https://helpx.adobe.com/enterprise/using/adobe-asset-link.html)

### 产品版本

* **自动化表单转换服务**

   Automated Forms Conversion Service（自动将PDF表单转换为美观的移动就绪HTML表单的服务）于2019年12月12日正式推出。

   * [简介](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/introduction.html)
   * [配置服务](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/configure-service.html)
   * [将PDF表单转换为自适应表单](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/convert-existing-forms-to-adaptive-forms.html)

### 自助服务

* **预览3D资产**

   AEM 6.5支持在创作过程中上传、交付和交互式预览3D资产。 交互式3D查看器可从AEM的资产详细信息页面访问。 查看器包括一组交互式相机控件，这些控件可让您绕行、缩放和平移3D资产。
请参 [阅预览3D资产](https://docs.adobe.com/content/help/en/experience-manager-65/assets/using/previewing-3d-assets.html)。

* **核心组件**

   Core Components 2.8.0, with numerous fixes, is now available along with [authoring documentation](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/introduction.html) and [developer details and project download available on GitHub](https://github.com/adobe/aem-core-wcm-components).

* **AEM 项目原型**

   [AEM Project Archetype的](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/uifrontend.html)[](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/overview.html) ui.frontend模块是一个实用而灵活的工具，可让AEM项目的前端开发更轻松。

### 其他资源

* [AEM 6.5 学习和支持主页](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 学习和支持主页](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 学习和支持主页](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 学习和支持主页](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager 用户指南](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [更早版本的 AEM 文档](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic 帮助主页](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Dynamic Media 发行说明](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre 发行说明](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign 提供了一种直观、自动的方式，以通过在线和离线营销渠道来交付一对一的消息。您现在可以利用根据客户习惯和喜好所决定的体验，来预测客户的需求。

### Campaign Classic 19.2

| 功能 | 描述 |
| ------------- | ----------- |
| 加利福尼亚消费者隐私法(CCPA) | CCPA是加利福尼亚州新的隐私法，它使2020年1月1日生效的数据保护要求协调并现代化。 CCPA适用于持有居住在加利福尼亚的数据主体数据的Adobe Campaign客户。 <br> 除了现有的隐私权功能（包括同意管理、数据保留设置和用户角色）之外，Adobe Campaign还可帮助您做好CCPA准备： <ul><li>__ 访问权&#x200B;_,_&#x200B;删除权：我们正在利用为GDPR添加的功能。 [了解更多](https://helpx.adobe.com/campaign/kb/acc-privacy.html#righttoaccess) </li><li>您可以跟踪消费者是否已选择退出个人信息的销售。 为此，您需要扩展“配置 [!UICONTROL 文件] ”表，并添 **[!UICONTROL 加“CCPA退出”字段]**。[了解更多](https://helpx.adobe.com/campaign/kb/acc-privacy.html#ccpa)</li></ul> 请参阅 [操作方法视频](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/privacy/privacy-overview.html)。 |
| 工作流实时监视 | 您现在可以使用预定义视图监视实例上所有工作流的执行状态。 <br> 有关详细信息，请参 [阅根据工作流的状态筛选工作流](https://docs.adobe.com/content/help/en/campaign-classic/using/automating-with-workflows/monitoring-workflows/monitoring-workflow-execution.html#filtering-workflows-status)。 |
| 使用AMP的交互式内容 | Adobe Campaign使您能够试用新的交互式 [AMP for Email](https://amp.dev/about/email/) 格式，该格式允许营销人员将AMP组件包含在邮件中，以通过丰富、动态和交互式内容增强电子邮件体验，这些内容在邮件本身中直接具有可操作性。 <br> 此功能作为公共测试版发布。 <br> 有关详细信息，请参阅详细 [文档](https://docs.adobe.com/content/help/en/campaign-classic/using/sending-messages/sending-emails/defining-interactive-content.html) 和教 [程视频](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/sending-messages/email-channel/defining-interactive-email-content-with-amp.html)。 |
| 安全短信 (TLS) | 现在，可通过扩展的通用 SMPP 连接器支持安全短信。这让您能够与提供商之间建立加密连接。<br> **警告**:此功能要求所有服务器上都有最新证书。 无效、已吊销或过期的证书将生成影响整体SMS发送功能的错误。 <br>有关更多信息，请参阅[详细说明](https://helpx.adobe.com/campaign/kb/sms-connector-protocol-and-settings.html)。 |

有关修复和改进，请参阅 [Adobe Campaign Classic 发行说明](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html)。

### Campaign Standard 19.4

| 功能 | 描述 |
| ------------- | ----------- |
| 加利福尼亚消费者隐私法(CCPA) | CCPA是加利福尼亚州新的隐私法，它使2020年1月1日生效的数据保护要求协调并现代化。 CCPA适用于持有居住在加利福尼亚的数据主体数据的Adobe Campaign客户。 <br> 除了Adobe Campaign中已有的隐私权功能（包括同意管理、数据保留设置和用户角色）外，我们还将利用此机会加入其他功能，以帮助您做好CCPA准备工作： <ul><li> 访问权和删除权：我们正在利用为GDPR添加的功能。 [了解更多](https://helpx.adobe.com/content/help/en/campaign/kb/acs-privacy.html#righttoaccess) </li><li> 创建隐私请求时，隐私核心服务中已添加规章类型（GDPR或CCPA）。 此方法是您应用于所有访问和删除请求的方法。 不建议使用Campaign API和界面访问和删除请求。 请参阅已弃 [用和已删除功能文章](https://helpx.adobe.com/campaign/kb/acs-deprecated-and-removed-features.html)。 </li><li> “ **CCPA选择退出** ”字段已添加到配置文件资源中，以允许Adobe Campaign用户跟踪消费者是否选择退出个人信息销售。 [了解更多](https://helpx.adobe.com/content/help/en/campaign/kb/acs-privacy.html#ccpa) </li></ul> 请参阅 [操作方法视频](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/privacy/privacy-overview.html)。 |
| Microsoft Dynamics 365集成(GA) | Adobe Campaign Standard与Microsoft Dynamics 365之间的集成现已可用。 您将能够将联系人和自定义实体记录从Dynamics 365传输到Campaign，并将电子邮件事件数据从Campaign返回到Dynamics 365，以便更好地协调销售／营销。 <br> 请参阅详 [细文档](https://helpx.adobe.com/campaign/kb/acs-ms-dynamics.html) ，以设置此集成并查看操 [作方法视频](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/integrating/microsoft-dynamics365-connector/introduction.html)。 |

See [Adobe Campaign Standard Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) for fixes and improvements.

### Adobe Campaign 控制面板

我们为管理员用户添加了从控制面板委派子域和续订SSL证书的新功能。

有关详细信息，请参阅以下页面：

* 设置新子域——阅 [读更多](https://docs.adobe.com/content/help/en/control-panel/using/subdomains-and-certificates/setting-up-new-subdomain.html)
* 续订子域的SSL证书——阅 [读更多](https://docs.adobe.com/content/help/en/control-panel/using/subdomains-and-certificates/renewing-subdomain-certificate.html)

>[!CAUTION]
>
>这些功能将在1月底之前在测试版中提供，并且可能会频繁更新和修改，恕不另行通知。

### 其他资源

* Adobe Campaign Standard：[文档](https://helpx.adobe.com/support/campaign/standard.html) - [发行说明](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [操作方法视频](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [发行计划](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic：[文档](https://helpx.adobe.com/support/campaign/classic.html) - [发行说明](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [操作方法视频](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Adobe Campaign控制面板：文 [档](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) -发 [行说明](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

更新日期：2020年1月11日，版本

| 视图 | 功能 |
|------|---------|
| 转化跟踪 | 所有Advertising Cloud Cookies均已更新，以满足Google Chrome 80的新cookie控制要求，该要求将于2月4日发布。 这些更改是使用现有Cookie从Adobe服务器实施的，对访客量度没有任何影响。 无需更新广告商。 |
| “洞察”>“警报测试”、“搜索”>“营销活动” | （仅限搜索帐户的测试版功能）新的警报测试版允许您创建警报模板，以识别任何搜索活动、广告组、关键字或广告何时满足特定条件— 例如绩效指标— 然后生成警报。 单个广告商可收到警报。 |
| 报表 | 产品列表广告的数据现在包含在“标签分类”、“标签值”、“竞价规则”和“约束”报告中。 |
