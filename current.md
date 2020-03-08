---
title: Adobe Experience Cloud 发行说明
description: Experience Cloud 发行说明模板
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: tm+mt
source-git-commit: dcbcc2fff5026c07898e7887b837767e9a71dbf3

---


# 早期访问- Adobe Experience Cloud发行说明- 2020年3月

Adobe Experience Cloud 的新增功能和修复。

>[!IMPORTANT]
>此页面包含预发行内容，在发行版之前可能会发生更改。

>[!NOTE]
>若要通过电子邮件接收有关即将发行的版本的通知，请订阅 [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html)。对于在版本发行之后发布的新信息，将使用发布日期进行标记。

**发行日期：2020 年 3 月**

（具体产品的发布日期可能有所不同）

* [Adobe 系统状态](#status)
* [Experience Cloud 界面和核心服务](#ecloud)
* [Experience Platform](#platform)
* [Mobile Services 和 Mobile SDK](#mobile)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html)（链接到解决方案帮助）
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html)（链接到解决方案帮助）
* [!DNL Advertising Cloud](#adcloud)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [新文档和教程](#selfhelp)

在找帮助主页吗？请参阅 [Adobe Experience Cloud 文档](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html)。

## Adobe 系统状态 {#status}

[!UICONTROL Adobe 系统状态]提供关于 Adobe 云产品与服务中断和维护事件的详细信息、状态更新以及电子邮件通知。请访问 [status.adobe.com](https://status.adobe.com/) 查看。

**新增功能**

* 使用Adobe ID，您可以订阅粒度更细的活动通知，具体到产品产品和附加级别。 在Experience Cloud产品中查找此新功能，在该功能中，自助订阅流程显示您要订阅的产品和服务的子产品和服务。 此增强功能应会显着减少您收到的通知的数量，并使通知与您使用的产品和功能更相关。  要开始使用，请访问 [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit)。

**当前可用的新增功能和增强功能**

| 功能 | 描述 |
| -----------| ---------- |
| 按产品分项提供的个性化自订 | <ul><li>通过产品或Experience Cloud产品附加组件进行自订。</li><li>收到的活动通知与您的产品和产品提供首选项相关。</li></ul> |
| 基于用户偏好的个性化体验 | <ul><li>电子邮件通知中使用基于浏览器设置的时区首选项。</li><li>在订阅／取消订阅时，使用所有选定的首选项发送电子邮件确认。</li></ul> |
| 更好地交付活动消息 | <ul><li>根据时间顺序的事件更新对事件历史记录进行排序。</li><li>已向“主要／次要”已关闭问题添加的事件解决时间戳。</li></ul> |

## Experience Cloud 界面和核心服务 {#ecloud}

Experience Cloud 界面中的新增功能和修复，包括管理和核心服务（客户属性、受众、触发器、Cookie 等）。

| 功能 | 发布日期 | 描述 |
| ----|----|---- |
| 管理工具 - 查看用户详细信息 | 2020 年 2 月 26 日 | 管理员可以在新的“管理工具”中查看所有 Experience Cloud 用户的可排序、可过滤列表及其详细信息。用户详细信息包括用户的产品访问、角色和上次访问信息。See [Experience Cloud Admin Tool](https://docs.adobe.com/content/help/en/core-services/interface/manage-users-and-products/admin-tool-experience-cloud.html) help for details. |

### 统一的产品域

Adobe 将更新域和界面标题，以统一并改进您在所有 Experience Cloud 应用程序中的体验。这些增强功能旨在以细微而重要的方式简化您的体验。这些增强不会更改您当前的工作流程。

更新包括：

* 新解决方案 URL：`experience.adobe.com/<application name>`：
   * 所有产品最终都将采用此 URL 模式。寻找即将在本月内生效的新 URL。
   * 浏览器支持：支持的浏览器包括 [!DNL Microsoft Edge]、[!DNL Google Chrome]、[!DNL Firefox]、[!DNL Safari] 和 [!DNL Opera]（最新版本）。**注意：**&#x200B;尽管 Experience Cloud 界面支持这些浏览器，但单个解决方案可能不会支持每个浏览器。（例如，[Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) 不支持 [!DNL Opera]，[Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html) 不支持 [!DNL Safari]。）
   * （仅限 [!DNL Safari]）域更改可能导致 [!DNL Safari] 中出现 Cookie 问题。取消选中 [!DNL Safari] 隐私首选项中的&#x200B;_阻止跨站跟踪_，将支持跨域的 Cookie（以及所有跨站点体验），并允许 Experience Cloud 在这个新的域上正常运行。
* 更轻松地在组织之间切换，或切换到其他应用程序。
* 改进了产品帮助：[!UICONTROL Experience League] 已集成到产品中，以便帮助搜索还包括来自社区论坛及视频内容的答案。此更改会简化对更多内容的访问，并有助于您充分利用 Experience Cloud。此外，单击&#x200B;**[!UICONTROL 帮助]** > **[!UICONTROL 反馈]**，可报告问题或与 Adobe 分享您的想法。
* 改进了通知：现在，[!UICONTROL 通知]下拉菜单有两个选项卡，一个用于您自己的产品通知，一个用于全球产品通知。

**注意：** Feed [!UICONTROL 页] 2020年1月已弃用。 请查看产品内的弃用通知。

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html) help.

## Experience Platform {#platform}

Release notes for the [!UICONTROL Experience Platform,] [!UICONTROL Experience Platform Launch,] [!UICONTROL Identity Service,] and security bulletins.

* [Experience Platform 发行说明](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [安全公告与建议](https://helpx.adobe.com/security.html)（所有 Adobe 产品）

### Experience Platform Launch {#launch}

有关发行说明和产品文档，请参阅 [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html)。

## 旅程安排 {#journey}

使用Adobe Experience Platform，通过智能实时预测每位客户的需求（无论其旅程到达何处），跨体验渠道大规模地编排每位客户旅程。

第1季度版本已发布。 [阅读更多](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html#q1-release---march-2020)

### 其他资源

[文档](https://docs.adobe.com/content/help/en/journeys/using/journey-orchestration-home.html)

[发行说明](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html)

[操作方法视频](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

## Mobile Services 和 Mobile SDK {#mobile}

**iOS v4.19.1**

* 常规——解决了在跟踪调用的上下文 [!UICONTROL 数据中包含] Swiftenum时的潜在崩溃问题。
* [!DNL Target] - [!DNL Target] Session ID现在将作为上下文数据参数添加到发送 `a.target.sessionId` 到Adobe Analytics的 [!UICONTROL Analytics-for-Target] 内部点击中。

**Android v4.18.1**

* [!DNL Target] - [!DNL Target] Session ID现在将作为上下文数据参数“a.target.sessionId”添加到发送到Adobe Analytics的内部 [!UICONTROL Analytics-for-Target] hit中。

## [!DNL Analytics] {#analytics}

发行日期：**2020 年 3 月 12 日**

Adobe Analytics 中的新增功能和修复：

* [Adobe Analytics 中的新增功能、增强功能和修复](#aa-features)
* [Analytics 管理员的重要注意事项](#aa-notices)
* [AppMeasurement](#appm)

有关产品文档，请参阅 [Adobe Analytics 帮助主页](https://docs.adobe.com/content/help/en/analytics/landing/home.html)。

### Adobe Analytics 中的新增功能、增强功能和修复 {#aa-features}

* **[!UICONTROL Analysis Workspace中的多个报表包&#x200B;]**:您现在可以将多个报表包中的数据并入一个[!UICONTROL Analysis Workspace项目]，以便并排查看。 此功能将在几周内向所有客户推出。[了解更多...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)
* **Experience Cloud受众优化**:利用此功能，您可以在8小时内（而不是之前的48小时处理时间）将区段发布到Experience Cloud。 [了解更多...](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segmentation-workflow/seg-publish.html)
* **Analysis Workspace —— 培训教程模板**:这个新的标准模板将指导您逐步了解在Workspace中构建第一个分析的常用术语和步骤。 它可用作“新建项目”模式中的标准模板  ，并替换当前存在的示例项目，以供列表中没有其他项目的新用户使用。

#### 修复

* 修复了报告与分 [!UICONTROL 析中阻止下载报告] 的问题 `.xls` 。（AN-206541、AN-204008）
* 新Shell的推出修复了与切换Experience Cloud组织相关的几个客户问题。（AN-200844、AN-186920）
* 修复了在细分的搜索筛选器中不包括“未指定”（无） ____ ，而对“未指定”行项目（或某些其他报告行项目）执行细分时，不会在细分中返回任何结果的问题。
* 修复了在使用分类维度时，进入或退出量度总数与细分时的行项目总数不匹配的问题。
* 修复了归因IQ中的首次接触和最后接触模型无法正确计算某些开箱即用尺寸中某些行项目的信用的问题。
* 修复了按另一个日期维划分一个日期维将返回错误结果的问题。
* 修复了在分类的维度报表中，有时进入或退出量度在应用到“未指定”时会被错误计数的问题。

### [!DNL Analytics] 管理员的重要注意事项 {#aa-notices}

| 注意 | 添加或更新日期 | 描述 |
| -----------| ---------- | ---------- |
| “转化 **[!UICONTROL 级别设置]** ” | 2020 年 3 月 3 日 | 将于2020年3月12 [日从UI中删除](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/general-acct-settings-admin.html) “管理工具 **[!UICONTROL ”]>“报表包”[!UICONTROL >“]** 常规帐户设置”中的“无法正常使用的转换级别”设置。 |
| 仪表板存档 **[!UICONTROL 的EOL]** | 2020 年 3 月 3 日 | 自2020 **[!UICONTROL 年3月]****** 12日起，“报告与分析”中“管理仪表板”下的“查看存档”设置将不再可用。 |
| 停止支持 TLS 1.1 | 2019 年 10 月 3 日 | 我们一直不懈努力，致力于维持最高安全标准并提升客户数据安全。为此，Adobe Analytics 对 TLS 1.1 的支持将持续到 2020 年 3 月 31 日，在这之后将不再支持 TLS 1.1。 |
| 新的 Adobe Analytics 域 | 2019 年 12 月 18 日 | 自 2020 年 1 月 16 日起，Adobe Analytics 将开始转移到新域 - `https://experience.adobe.com/analytics.`<br>**注意：**这项更改适用于使用 Adobe ID 或 Enterprise ID 访问 Analytics 的所有用户。<ul><li>域更改可能会导致在 Safari 中加载 Analytics 时出现 Cookie 问题。取消选中 隐私首选项中的&#x200B;_阻止跨站跟踪_，将支持跨域的 Cookie（以及所有跨站点体验），并允许 Analytics 在这个新的 Adobe Experience Cloud 域上运行。[!DNL Safari]You can use other browsers without issue because this affects only [!DNL Safari] users.</li><li>[在特定情况下](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html)，域更改可能会导致某些客户的 [!UICONTROL Activity Map] 停止工作。</li></ul> |
| 生命周期结束 - Analytics 旧版 API | 2020 年 1 月 9 日 | 2020 年 11 月，以下 Analytics 旧版 API 服务将停止使用并关闭。当前使用这些服务构建的集成将会停止工作。 <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>旧版 OAuth 身份验证（OAuth 和 JWT）</li></ul>我们提供了[旧版 API EOL 常见问题解答](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)，以帮助回答您的问题并提供有关如何继续的指导。使用这些服务的 API 集成可以迁移到 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 或 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。旧版 OAuth 帐户可迁移到 [Adobe IO](https://console.adobe.io/home?mv=email) Analytics 集成帐户，该帐户可用于访问 1.4 Analytics API 和 2.0 Analytics API。 |
| 圣何塞 FTP 中转站停止为伦敦和新加坡提供支持 | 2020 年 7 月 | For customers in London and Singapore, we will no longer support brokering of data between London or Singapore and the San Jose data center [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>For London, use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>For Singapore, use [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |

### [!DNL AppMeasurement] {#appm}

请参阅 [AppMeasurement for Javascript 发行说明](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html)。版本2.20.0已于2020年3月5日发布。

## Audience Manager {#aam}

Audience Manager的新增功能和更新：

### Fixes and improvements {#aam-fixes-and-improvements}

* 修复了由于缺少RBAC权限 [!UICONTROL VIEW_ALL_DESTINATIONS，客户无法更新区段名称的错误]。 更 [!UICONTROL 新区段时不需要VIEW_ALL_DESTINATIONS] 权限。 有关RBAC权限的更多信息，请参 [阅管理（RBAC控制）](https://docs.adobe.com/help/en/audience-manager/user-guide/features/administration/administration-overview.html#wild-card-permissions)。 (AAM-52760)
* 修复了 [Data Explorer](https://docs.adobe.com/help/en/audience-manager/user-guide/features/data-explorer/data-explorer-overview.html) （数据浏览器）中的一个错误，该错误导致某些客户在基于Data Explorer信号创建特征时无法看到基本信息部分的内容以及表达式构建器中的运算符  。 (AAM-53130)
* 修复了某些客户无法加载 [!UICONTROL Audience Marketplace界面的错误] 。 (AAM-52070)
* 修复了区段API中的一个错误  ，该错误导致由于某些区段没有说明，当用户尝试访问这些区段并且用户必须从该页面导航离开时，界面将冻结。 (AAM-53071)
* 整个界面中的多种辅助功能改进。 (AAM-48952、AAM-48969、AAM-48979、AAM-48993、AAM-49048、AAM-49057、AAM-49058、AAM-49058aam-49392)

## Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新增功能、修复和更新。Adobe 建议那些采用内部部署的客户部署最新的修补程序，以便确保获得更高的稳定性、安全性和性能。

### 产品更新

* **AEM 6.5.4.0** AEM 6.5,Service Pack 4.0（2020年3月5日发布）是一项重要更新，其中包括自2019年4月AEM 6.5通用版本发布以来发布的新功能、关键客户增强功能、改进的性能、稳定性和安全性。
   * [Adobe Experience Manager 6.5 Service Pack 4的新增功能](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/new-features-latest-service-pack.html)
   * [发行说明](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [AEM Forms发布的交付内容](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.0**

   AEM 6.4,Service Pack 8.0（2020年3月5日发布的6.4.8.0）是一项重要更新，其中包括自2018年4月AEM 6.4正式发布以来发布的关键客户修复。
   * [发行说明](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [AEM 表单 CFP 版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.3.3.8**

   AEM 6.3, Service Pack 3, Cumulative Fix Pack 8（2019年3月5日发布的6.3.3.8）是一项重要更新，其中包括自2017年4月AEM 6.3通用版本发布以来发布的关键客户修复。
   * [发行说明](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [AEM 表单 CFP 版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM Assets Brand Portal**

   AEM Assets Brand Portal 6.4,Service Pack 6（2020年3月5日发布的6.4.6）更改了AEM Assets配置 [!UICONTROL Brand Portal的方式。] 此外，该版本还包含其他增强和错误修复。
   * [发行说明](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)

### 自助服务

* **AEM作为云服务——基于角色的权限**

   Cloud Manager具有预配置的角色，并具有相应的权限。 每个角色都具有与每个角色关联的特定权限、预配置的任务或权限。 “基 [于角色的权限](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/what-is-required/role-based-permissions.html) ”帮助主题标识了可用的功能以及可以运行这些功能的角色。

* **AEM作为云服务——调度程序**

   更新 [了Dispatcher和CDN](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/dispatcher/overview.html#dispatcher-cdn) ，以及 [Explicit Dispatcher缓存失效部分](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/dispatcher/overview.html#explicit-invalidation) ，以阐明可用的选项及其工作方式。

* **使用Brand Portal配置AEM资产**

   AEM资产现在通过Adobe I/O [!UICONTROL 配置了Brand Portal] ,Adobe I/O为Brand Portal租户购买IMS令牌以授权。 以前，它是通过旧版OAuth网关在经典界面 [!UICONTROL 中配置的。]
请参 [阅配置AEM资产与Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/publish/configure-aem-assets-with-brand-portal.html)。

* **AEM作为云服务- Dynamic Media中的智能裁剪**

   当您在Dynamic Media组件中使用智能裁剪时，AEM中的新选项将作为云服务提供：

   **启用长宽比匹配** -选择此选项可让Dynamic Media选取最匹配原始图像长宽比的智能裁剪再现。
请参 [阅使用智能裁剪时](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/adding-dynamic-media-assets-to-pages.html#when-working-with-smart-crop)。

### 社区

* **AEM Skill Builder网络研讨会**

   * AEM Sites —— 从2020年3月17日开始，了解内容创作的构建基块以及AEM Sites的基本概念和操作。 [立即注册](https://aemskillbuilder-sites.experienceleague.adobeevents.com/register)。
   * AEM Assets —— 从2020年3月19日开始，您可以提高数字资产管理专业知识，并了解品牌门户、 [!UICONTROL Dynamic Media、][!UICONTROL Asset Link] 等基础知识。 [立即注册](https://aemskillbuilder-assets.experienceleague.adobeevents.com/register)。

### 其他资源

* [AEM 作为云服务](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)
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

### 其他资源

* Adobe Campaign Standard：[文档](https://helpx.adobe.com/support/campaign/standard.html) - [发行说明](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [操作方法视频](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [发行计划](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic：[文档](https://helpx.adobe.com/support/campaign/classic.html) - [发行说明](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [操作方法视频](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Adobe Campaign 控制面板：[文档](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [发行说明](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

更新日期：2020 年 2 月 10 日（适用于 2 月 8 日版）：

| 视图 | 功能 |
|------|---------|
| [!UICONTROL 项目组合] | You can now add [!DNL Yahoo!] Japan Display Network (YDN) campaigns to portfolios to optimize the campaign budgets and ad group-level bids. 相同的竞价适用于广告组中的所有广告。Japan Display Network营销活动的数据包含在该产品组合的模拟中。 |
| [!UICONTROL “搜索] ”>“批 [!UICONTROL 单”] | 现在，您可以通过批量工作表来创建、编辑和删除 Google 响应式搜索广告 (RSA)。以前，只能通过&#x200B;**[!UICONTROL 搜索]** > **[!UICONTROL 促销活动]**&#x200B;中的标准促销活动管理界面来提供支持 |
| [!UICONTROL “搜索] ”>“ [!UICONTROL 营销活动”、“报告”] | Google Ad 的突出量度 `Impr. (Abs. Top) %` 和 `Impr. (Top) %` 目前可以应用在所有的基本报表和实体级别的促销活动管理视图（但是，对于那些选购性产品组除外）、[!UICONTROL 促销活动日市场份额]和[!UICONTROL 关键字级别的日市场份额]报表，以及标签和限制性视图中。 |

## [!DNL Magento] {#magento}

有关 Magento 的发行说明，请参阅：

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] 是一个完整的解决方案，面向希望通过参与复杂购买历程的每个阶段来转变客户体验的潜在客户管理人员和 B2B 营销人员。

### 核心 Marketo Engage 更新

发行日期：2020 年 2 月 21 日

* **Microsoft Dynamics _在 Microsoft 中更改所有者_流程操作**：直接从 Marketo Engage 中更改潜在客户或联系所有者
* **对 API 调用的增强：**
   * 用户管理 API
   * 自定义对象架构 API
   * 登陆页面重定向规则 API
* **表单描述符缓存：**&#x200B;对登陆页面和表单的改进。

有关更多信息，请参阅 [!DNL Marketo] [2020 年 2 月版](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720)发行说明

### 即将推出的功能

本季度将发布以下功能：

| 功能 | 描述 |
|------|---------|
| [!DNL Bizible] | <ul><li>新的基于帐户的分段</li><li>保存特定于功能板的过滤器</li><li>将 Bizible 功能板导出为 PDF</li></ul> |
| Sales Connect | 撰写窗口和命令中心更新/增强功能 |

### 公告

**Marketo Engage 成功中心：**&#x200B;于 2020 年 2 月推出。成功中心是一个产品内帮助中心，允许您搜索产品文档和社区、启动操作指南、访问采用内容等。注意：此功能将作为测试版在澳新银行推出，并将在本季度晚些时候推出到北美洲。

### 弃用

* **Asset API“_method”参数：** 2020 年 9 月之后，Asset API 端点将不再接受“_method”在 POST 正文中传递查询参数以绕过 URI 长度限制。
* **弃用 Internet Explorer 支持：**&#x200B;从 2020 年 7 月 31 日发行的 7 月版本开始，Internet Explorer 将不再支持 Marketo Engage 用户界面。

有关累积和历史发行说明，请参阅 [Marketo 发行说明](https://docs.marketo.com/x/CgA6Ag)。

## 新文档和教程 {#selfhelp}

最新和自助文章和视频。 <!--`https://jira.corp.adobe.com/secure/Dashboard.jspa?selectPageId=60327`-->

| 解决方案 | 内容 | 描述 |
|----------| -----------| ---------- |  
| [!UICONTROL AEM Commerce] | 视频——创 [建多个类别和产品页面](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/04-style-cif-component.md) | 了解如何使用CIF核心组件为客户项目创建最低限度的Adobe Experience Manager(AEM)CIF项目作为起点。 将主题和CSS样式应用于组件并检查由原型生成的新AEM CIF项目。 此外，了解CIF核心组件使用的CSS和JavaScript是如何组织的。 |
| [!UICONTROL AEM 表单] | 文章——使 [用OKTA验证AEM作者身份](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/single-sign-on-with-okta.html) | 了解如何在OKTA门户上配置应用程序以及注册新应用程序时通常使用的设置。 |
| [!UICONTROL AEM Commerce] | 教程——自 [定义CIF核心组件](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/05-customize-cif-components.md) | 一般来说，请查看CIF核心组件和AEM提供的几个不同扩展点。 CIF核心组件提供了一套标准的商务组件，可用于加速集成Adobe Experience Manager(AEM)和Magento解决方案的项目。 |
| [!DNL Adobe Campaign] -受众目标 | Video - [Create an audience...](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/creating-audiences-using-segment-builder.html) | 使用Adobe [!UICONTROL Experience Platform Segment Builder在Campaign Standard中创建受众]。 您可以通过“受众”模块直接在Adobe Campaign Standard中访问 [!UICONTROL 此功] 能。 |
| [!DNL Adobe Campaign] -受众目标 | 视频——在 [营销工作流程中激活Adobe Experience Platform受众](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/activating-aep-audiences.html) | 了解如何使用“读 [!UICONTROL 取受众”活动在工作流中激活数据服] 务查询受众  。 |
| [!DNL Adobe Campaign] | 教程- [Android推送通知](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/getting-started-push-notifications/getting-started-with-push-notifications-android.html) | 向iOS和Android移动设备发送个性化的分段推送通知。 本教程将指导您完成从Adobe Campaign发送推送通知和在Android应用程序中接收这些通知时涉及的步骤。 |
| [!DNL Adobe Campaign] | 视频- [创建推送通知](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/creating-a-push-notification.html) | 在Adobe Campaign Standard中创建推送通知。 您可以向iOS和Android移动设备发送个性化的分段推送通知。 |
| [!DNL Adobe Campaign] - AEP Data Connector | 视频- [检查数据获取作业的状态](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/checking-status-of-data-ingestion-jobs.html) | 了解如何检查数据摄取作业的状态以及数据是否已从Adobe Campaign Standard摄取到Adobe Experience Platform中。 |
| [!DNL Adobe Campaign] - AEP Data Connector | 视频——修 [改数据映射](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/modifying-data-mapping.html) | 了解如何检查状态和修改数据映射。 |
| [!DNL Adobe Campaign] - AEP Data Connector | 视频——映 [射体验活动](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-experience-events.html) | 了解如何在Adobe Experience Platform中映射体验活动。 |
| [!DNL Adobe Campaign] - AEP Data Connector | 视频——映射 [自定义资源](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-custom-resources.html) | 了解如何在Adobe Campaign Standard和Adobe Experience Platform之间映射不同的数据类型。 |
| [!DNL Adobe Campaign] - AEP Data Connector | 视频- [了解Adobe Experience Platform Data Connector](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/understanding-the-adobe-experience-platform-data-connector.html) | 了解如何通过将XTK数据（在Campaign中摄取的数据）映射到Adobe Experience Platform上的Experience Data Model(XDM)数据，使您的数据在Adobe Experience Platform上可用。 |
| [!DNL Adobe Campaign] - AEP Data Connector | 视频——映 [射种子表数据](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-seed-table-data.html) | 了解如何使用Adobe Experience Platform映射种子数据／测试配置文件。 |
| [!DNL Adobe Campaign]-受众目标 | 视频- [更改平台受众分发的定位维度](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/changing-targeting-dimension.html) | 了解如何在Adobe Campaign Standard的主配置文件表之外更改平台受众分发的定位维度。 |
| [!DNL Adobe Campaign] | 视频——雪 [花上的大数据管理](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | 在Adobe Campaign Classic中利用雪花连接器。 |
| [!DNL Adobe Campaign] -受众目标 | 文章- [受众目标（测试版）-概述](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/audience-destinations-overview.html) | 了解如何将Adobe Experience Platform中的集中化和整合的档案数据用于Adobe Campaign Standard中的营销活动。 |
| [!DNL Adobe Target] - Mobile SDK | 教程——使 [用Adobe Target个性化应用程序体验](https://docs.adobe.com/content/help/en/target-learn/mobile-sdk-v4-android/overview.html) | 在您自己的Android应用程序中实施Adobe Target。 验证Mobile Services SDK的设置并实 [!DNL Target] 施预取内容、阻止请求等请求。 |
| Adobe Analytics | 视频- [Adobe 2019年超级会议](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-high-tech.html) | 观看2019年峰会上高科技“超级会议”的精选剪辑。 |
| Adobe Analytics | 视频——客 [户旅程分析中的计算指标简介](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/introduction-to-calculated-metrics-in-customer-journey-analytics.html) | 浏览在客户旅程分析中创 [!UICONTROL 建计算][!UICONTROL 量度的基础知识]。 |
| Adobe Analytics | 视频- [Adobe 2019年超级会议](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-travel.html) | 观看2019年峰会旅游和酒店业会议的精选剪辑。 |
| Adobe Analytics | 视频- [Adobe 2019年超级会议](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-retail.html) | 查看2019年峰会上零售会议的精选剪辑。 |
| Adobe Analytics | 视频——客 [户使用案例：Accent Group投资客户体验推动销售](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/accent-group-invests-in-customer-experience-to-drive-sales.html) | 观看Accent Group如何使用Adobe Experience Cloud创建无缝的数字体验。 |
| Adobe Analytics | 视频——客 [户使用案例：ServiceNow获得与潜在客户建立联系的正确洞察](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/servicenow-gets-the-right-insights-to-connect-with-prospects.html) | 了解如何通 [!DNL ServiceNow] 过Adobe Advertising Cloud和Adobe Analytics从其营销渠道中获得可操作的数据并提高付费搜索广告的ROI。 |
| Adobe Analytics | 视频- [Adobe Analytics —— 它不仅仅是数据，还是客户智能](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-analytics-customer-intelligence.html) | 了解数据驱动营销以及如何使您的分析成熟度从数据到洞察再到行动。 |
| Adobe Analytics | 视频- [Adobe Sensei和Adobe Analytics —— 扩展版](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-sensei-and-adobe-analytics.html) | 查看Adobe Analytics中以Adobe为后盾的 [!DNL Sensei,] 主要 [!UICONTROL 功能，包括异常检测] 、贡献分析、智能聚类、 [!UICONTROL 聚类、][!UICONTROL IQ细分、倾向建模等。] |
| Adobe Analytics | 视频- Adobe [Analysis Workspace如何改变您的业务](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/how-adobe-analysis-workspace-can-change-your-business.html) | 了解如何使用 [!UICONTROL Analysis Workspace执行临时分析、灵活分析、同期群分析和流失分析]。 您还可以与公司中的每个人共享分析工作环境，其拖放功能使每个人都能轻松分析数据并快速获得洞察。 |
| Adobe Analytics | 视频——客 [户使用案例：Home Depot利用客户体验管理进行创新](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/the-home-depot-innovates-with-customer-experience-management.html) | 了解如 [!DNL Home Depot] 何使用Adobe解决方案通过个性化、自定义的购物体验创造品牌忠诚度和客户满意度。 |
| Adobe Analytics | 演示——了 [解客户旅程分析](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/understanding-customer-journey-analytics.html) | 了解Adobe的客户旅 [!UICONTROL 程分析]（一项基于Adobe的应用程序服务）如何将 [!DNL Adobe Experience Platform]Analysis Workspace  引入Experience Platform。 此功能支持对任何数据集进行多渠道 [!DNL Adobe Experience Platform] 分析。 |
| Adobe Analytics | 视频- [CJA中的跨渠道归因](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/cross-channel-attribution-in-customer-journey-analytics.html) | 了解如何在客户旅程分析中使用可视化功能跨渠道显示归因( [!UICONTROL 给出评价)]。 |
| Adobe Analytics | 文章- [继续Adobe Analytics学习旅程的客户提示](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/tips-and-tricks/customer-tips-for-continuing-your-adobe-analytics-learning-journey.html) | 会见三位Adobe客户，他们有关如何从Adobe Analytics中获得最大价值的提示和技巧。 |
| Adobe Analytics | 视频- [在CJA中创建跨渠道可视化](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/creating-cross-channel-visualizations-in-customer-journey-analytics.html) | 了解客 [!UICONTROL 户旅程分析如何允许您创建可视化] ，这些可视化包括来自多个渠道的多个数据集的数据，包括合并每位访客的数据。 |
| Adobe Analytics | 视频——将 [您的计算指标从Adobe Analytics移至客户旅程分析](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/moving-your-calculated-metrics-from-adobe-analytics-to-customer-journey-analytics.html) | 在客户旅程分析中查找有关重新创建 [!UICONTROLCAnalytics计算的] Metrics [!UICONTROL 的提示]。 |
