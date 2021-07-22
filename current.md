---
title: 最新发行说明
description: 了解 Experience Cloud 产品和服务的最新发行说明、新增功能和新文档。查找关于 Experience Cloud、Creative Cloud 企业版和 Document Cloud 的新帮助和教程。
doc-type: release notes
last-update: July 2021
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: 272c8da44a241b5a8eb5930462cc53b3e6c43297
workflow-type: tm+mt
source-wordcount: '5023'
ht-degree: 45%

---

# Adobe Experience Cloud 发行说明 - 2021 年 7 月

![横幅](assets/experience-cloud-banner-3.png)

Experience Cloud 应用程序和服务每月更新一次。在此页面上可集中查找 [!DNL Experience Cloud] 和 [!DNL Experience Platform] 的最新版本更新、文档和教程。还可查找 [!DNL Creative Cloud for Enterprise] 和 [!DNL Document Cloud] 的新文档。

>[!NOTE]
>
>订阅每月一期的 [Adobe Priority Product Update](https://www.adobe.com/cn/subscription/priority-product-update.html) 即可收到关于此页面更新的电子邮件通知。整月都在维护此页面，因此请定期回来查看 Adobe 企业产品和 Experience League 文档的更新。

最新更新日期：**2021 年 7 月 20 日**

* [Experience Cloud 中央界面组件](#ecloud)
* [Adobe 系统状态](#status)
* [Experience Platform](#platform)
* [Journey Optimizer](#journey-opt)
* [Journey Orchestration](#journey-orch)
* [Offer Decisioning](#offer-decisioning)
* [[!DNL Analytics]](#analytics) 和 [Customer Journey Analytics](#cust-journey)（更新日期：2021 年 7 月 19 日）
* [[!DNL Audience Manager]](#aam)
* [[!DNL Experience Manager]](#aem)
* [[!DNL Campaign]](#ac)
* [[!DNL Advertising]](#adcloud)
* [[!DNL Target]](#target)
* [[!DNL Commerce]](#magento) (Magento)
* [[!DNL Marketo Engage]](#marketo)
* [[!DNL Workfront]](#workfront)
* [Document Cloud](#doc-cloud)
* [Creative Cloud 企业版](#creative-cloud)

需要帮助？请访问 [Adobe Experience League](https://experienceleague.adobe.com/?lang=zh-Hans/#home)，查找产品和技术文档、Adobe 策划课程、视频教程、快速解答、社区洞察以及由讲师指导的培训。

## ![图标](/assets/ec_appicon_24.png) Experience Cloud 中央 UI 组件 {#ecloud}

Experience Cloud中心界面组件包括从统一产品标题访问的更新，例如自助、搜索和用户帐户首选项。 可在此处找到对人员、地点（位置）和产品管理的更新。

| 功能 | 日期 | 描述 |
| ------- | ------- | -------|
| Experience Cloud![全局搜索](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en#globally-search-for-objects-and-entities) | 2021 年 7 月 5 日 | 在此版本中，Experience Cloud全局搜索将Journey Orchestration添加到Experience Cloud中业务对象的搜索中，例如区段、数据集、架构等。 |

{style=&quot;table-layout:auto&quot;}

**更多帮助资源**

* [中央界面组件](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en)和用户管理的管理帮助
* [地点 - 位置服务](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=en)的帮助和发行说明
* [人员 - 客户属性和受众库](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en)的相关帮助。

## ![图标](/assets/adobe.png) Adobe 系统状态 {#status}

[!UICONTROL Adobe 系统状态]提供关于 Adobe 云产品与服务中断和维护事件的详细信息、状态更新以及电子邮件通知。请访问 [status.adobe.com](https://status.adobe.com/) 查看。

可在 [Adobe 系统状态 - 2020 年 5 月 21 日](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=zh-Hans)上找到 Adobe 系统状态的最新更新，了解最新的发行信息。

## ![图标](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

包括 Experience Platform 和 Experience Platform Launch 的发行更新信息和新文档。

* **2021年6月30日** [Experience Platform发行说明](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=zh-Hans)
* **2021年5月17日** [Experience Platform数据收集发行说明](https://experienceleague.adobe.com/docs/experience-platform/tags/release-notes/current.html) (以前称为Experience Platform Launch)

### Experience Platform 教程和课程 {#tutorials-platform}

发布的关于 Experience Platform 和服务的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 7 月 | [使用XDM为您的客户体验数据建模](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-D-1-2021.1.xdm) | 课程 | 了解如何在Adobe Experience Platform中构建数据模型。 本课程将向您讲授Experience Data Model(XDM)以及如何将现有数据模型转换为XDM。 了解如何使用标准类和字段组构建模式，以及如何构建您自己的自定义组件。 |
| 2021 年 7 月 | [面向数据工程师的查询服务快速入门](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-D-1-2021.1.qsvc.gsde) | 课程 | 了解如何验证摄取的数据，从数据湖中存储的数据中获得洞察，以及如何使用查询服务准备数据以做出业务关键型决策。 |
| 2021 年 7 月 | [使用查询服务创建功能板](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-D-1-2021.1.qsvc.dash) | 课程 | 了解如何验证摄取的数据，从数据湖中存储的数据中获得洞察，以及使用Adobe Experience Platform中的查询服务创建功能板。 |
| 2021 年 7 月 | [面向营销人员的Real-time CDP快速入门](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-U-1-2021.1.rtcdp) | 课程 | 在本课程中，您可以学习开始使用实时客户数据平台(Real-time CDP)作为业务从业者所需的一切信息。 |
| 2021 年 7 月 | [面向数据科学家的数据科学工作区快速入门](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-U-1-2021.1.dsw) | 课程 | 了解Adobe Experience Platform中的数据科学工作区。 本课程专为希望了解如何使用[!DNL JupyterLab]笔记本获取分析和查询数据、创建启用了用户档案的数据集、发布自动机学习模型，以及激活Adobe和非Adobe应用程序的机器学习分析的数据科学家而设计。 |
| 2021 年 7 月 | [Adobe Experience Platform数据管理快速入门](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-D-1-2021.1.dgov.gs) | 课程 | 了解如何控制您的数据，从从在数据源收集到整合到Adobe Experience Platform以外的目标。 |

{style=&quot;table-layout:auto&quot;}

## ![](/assets/experience_platform_appicon_24.png) IconJourney Optimizer {#journey-opt}

借助Adobe Journey Optimizer，您可以从单个应用程序为数百万客户管理计划的全方位营销活动和一对一的体验，并且整个历程通过智能决策和分析进行了优化。

### 最新Journey Optimizer产品版本

* **2021年7月：** Journey Optimizer现已推出。[了解更多信息](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=en)。

**更多Journey Optimizer资源**

[文档](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=en)  -  [最新更新](https://experienceleague.adobe.com/docs/journey-optimizer/using/documentation-updates.html?lang=en)  -  [操作方法视频](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=en)

## ![图标](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

凭借 Experience Platform，可以实时智能化预测每位客户的需求，从而实现跨体验渠道大规模编排客户历程。

在 [Journey Orchestration 发行说明](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=zh-Hans)中详细了解最新的功能、改进和修复。

**Journey Orchestration 的更多资源**

[文档](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=zh-Hans) - [发行说明](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=en) - [操作方法视频](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=zh-Hans)

## ![图标](/assets/experience_platform_appicon_24.png) Offer Decisioning {#offer-decisioning}

[!UICONTROL Offer Decisioning] 是与 Adobe Experience Platform 集成的一项应用程序服务。使用 [!UICONTROL Offer Decisioning] 可在适当的时候将优质的产品和体验提供给您在所有接触点上的客户。

* **2021年6月版：** AI排名允许您创建不同的排名策略（基于您的业务目标），经过培训的模型系统将使用这些策略来对符合条件的选件进行排名，以针对给定用户档案显示这些选件。

请参阅[Offer decisioning发行说明](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html?lang=zh-Hans#new)以保持最新。

**Offer Decisioning 的更多资源**

[文档](https://experienceleague.adobe.com/docs/offer-decisioning/using/offer-decisioning-home.html?lang=zh-Hans) - [发行说明](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html?lang=en#new) - [操作方法视频](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html?lang=en)

## ![图标](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

发行日期：**2021 年 7 月 22 日**

* [Adobe Analytics 中的新增功能](#aa-features)
* [Customer Journey Analytics 中的新增功能](#cust-journey)（更新日期：2021 年 7 月 19 日）
* [Adobe Analytics 中的修复](#aa-fixes)
* [Analytics 管理员的重要注意事项](#aa-notices)
* [Analytics 的课程及教程](#tutorials-analytics)
* [AppMeasurement](#appm)

### 适用于Experience League实时 — Analytics实施的事件通知

与我们一起聆听每个Adobe Analytics实施团队应该了解的具体提示 — 并在聊天面板中让Eric Matisoff回答您的问题。 这是个现场活动，因此无需提前注册，但请确保将其放在日历上，这样您就不会错过！

**事件：** [Adobe Analytics实施 — 提示和技巧](https://www.youtube.com/watch?v=lxOvLCzEGBI)

**时间：** 2021年7月29日太平洋夏令时上午9点

**Adobe演示者**

* Eric Matisoff，Adobe分析与数据科学的首席宣传员
* Dasha Fitzpatrick，Adobe首席技术顾问
* Doug Moore，Adobe技术营销工程师

### Adobe Analytics 中的新增功能 {#aa-features}

| 功能 | 描述 | [正式发布](https://experienceleague.adobe.com/docs/analytics/landing/an-releases.html?lang=zh-Hans) - 目标日期 |
| ----------- | ---------- | ------- |
| 新的Adobe Analytics登录页面（开放测试版） | Adobe Analytics的新登陆页面将Analysis Workspace和Reports &amp; Analytics整合到工作区伞下的单个界面和接入点中。 它提供了新的项目管理器主页、更新的报表菜单和现代化的报表，以及可帮助您更有效地入门的新学习部分。 新页面可改进可发现性，并可引导Reports &amp; Analytics用户在工作区中获得更好的报表体验。 [了解详情](https://experienceleague.adobe.com/docs/analytics/landing/an-landing.html) | 2021 年 7 月 26 日 |

{style=&quot;table-layout:auto&quot;}

### Customer Journey Analytics 中的新增功能 {#cust-journey}

| 功能 | 描述 | [正式发布](https://experienceleague.adobe.com/docs/analytics/landing/an-releases.html?lang=en) - 目标日期 |
| ----------- | ---------- | ----- |
| 新的连接信息体验 | 此连接UI增强功能让您能够了解数据是否以及何时准备好用于报表。 它还允许您跟踪处理数据时出现的任何问题。 [了解详情](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-connections/manage-connections.html?lang=en) | 2021 年 8 月 10 日 |

{style=&quot;table-layout:auto&quot;}

### Adobe Analytics 中的修复 {#aa-fixes}

* 修复了在创建警报时未发送警报和显示错误的问题。 (AN-263962)
* 修复了Analysis Workspace中虚拟报表包的问题：已提取指定日期范围以外的数据。 (AN-263121)
* 修复了工作区项目无法打开（超时）的问题。 (AN-247248)
* 修复了无法加载位于[!UICONTROL 服务器调用使用情况]下的报表包使用情况数据的问题。 (AN-264215)

#### Adobe Analytics 或 CJA 中的其他修复

AN-160022;AN-186365;AN-234768(CJA);AN-253041;AN-255098;AN-256319;AN-256566;AN-256903;AN-257111;AN-259614;AN-259960;AN-260422;AN-260926;AN-260962;AN-261310;AN-261442;AN-261483(CJA);AN-261589;AN-261949;AN-262025;AN-262295;AN-262330;AN-262348;AN-262356;AN-262461;AN-262462;AN-262465;AN-262888;AN-262944;AN-262952;AN-262974;AN-263027;AN-263105;AN-263175;AN-263183;AN-263244;AN-263888;AN-263930;AN-263953

### [!DNL Analytics] 管理员的重要注意事项 {#aa-notices}

| 注意事项 | 添加或更新日期 | 描述 |
| ----------- | ---------- | ---------- |
| 三种 Analytics API 服务的生命周期终止 | 2021 年 7 月 15 日 | 2021年8月18日&#x200B;****，以下Analytics旧版API服务将到达其生命周期终止日期并将关闭。 当前任何使用这些服务构建的集成都将在当日停止工作。<ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>旧版 OAuth 身份验证（OAuth 和 JWT）</li></ul>Adobe 已提供[旧版 API EOL 常见问题解答](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)以帮助回答您的问题并提供关于如何继续的指导。使用这些服务的 API 集成可以迁移到 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 或 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。旧版 OAuth 帐户可迁移到 [Adobe I/O](https://console.adobe.io/home?mv=email#) Analytics 集成帐户，该帐户可用于访问 1.4 Analytics API 和 2.0 Analytics API。 |
| Adobe Data Connectors 生命周期终止 | 2020 年 7 月 13 日 | Adobe [!UICONTROL Data Connectors] 由传统技术提供支持，而这些技术不再可行或不再受支持。可在 [Adobe Exchange Partner Program](https://partners.adobe.com/exchangeprogram/experiencecloud) 中找到新标准。可使用该标准继续提供和支持任何集成。正式的生命周期终止日期为&#x200B;**2021年8月1日**。 [了解详情...](https://experienceleague.adobe.com/docs/analytics/import/dataconnectors/data-connectors-eol.html?lang=zh-Hans) |
| 完全处理数据源生命周期终止 | 2021 年 4 月 12 日 | Adobe计划于2021年7月31日&#x200B;**弃用完全处理数据源**。 从 2021 年 3 月 25 日起，无法再创建此类型的新导入。请使用[批量数据插入 API](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md) 来导入此类型的数据。 |
| [!UICONTROL Report Builder] 的登录更新 | 2021 年 4 月 9 日 | 2021 年 1 月 14 日，[!UICONTROL Report Builder] 登录更新移除了对传统技术的依赖，与 Experience Cloud 的登录过程保持一致。Experience Cloud 使用 Enterprise ID（电子邮件和密码）。为确保无中断地访问[!UICONTROL Report Builder]，请在2021年7月22日之前将[!UICONTROL Report Builder]插件更新到版本5.6.47或更高版本&#x200B;**。** Report Builder 的 5.6.47 版本及更新的版本仅支持 Experience Cloud 登录，不再支持单点登录。 |

{style=&quot;table-layout:auto&quot;}

### AppMeasurement {#appm}

有关 AppMeasurement 版本的最新更新，请参阅[适用于 JavaScript 的 AppMeasurement 发行说明](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=zh-Hans)。

### Analytics 的新课程及教程 {#tutorials-analytics}

[!DNL Analytics] 和 [!UICONTROL Customer Journey Analytics] 中的新课程、教程和文章。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 7 月 | [在项目中使用圆环图可视化图表](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/visualizations/using-the-donut-visualization.html?lang=en) | 视频 | 了解如何在Analysis Workspace项目中添加和配置圆环图可视化。 |
| 2021 年 7 月 | [条形图和堆叠的条形图可视化图表](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/visualizations/bar-and-bar-stacked-visualizations.html?lang=en) | 视频 | 在此视频中，我们讨论了在Analysis Workspace中的项目中添加和配置条形图、堆叠的条形图、水平条形图和堆叠的水平条形图可视化。 尽管这些可视化视图被认为是基本的，但它们可以帮助您讲述数据故事，并为分析师提供洞察。 |
| 2021 年 7 月 | [面积图和堆叠面积图](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/visualizations/area-and-area-stacked.html) | 视频 | 了解如何在Analysis Workspace中将面积图和堆叠的面积图可视化添加到您的项目中，并了解一些提示，以帮助根据您的需求自定义可视化。 |

{style=&quot;table-layout:auto&quot;}

### Analytics 帮助资源

* [Adobe Analytics 产品文档及教程](https://experienceleague.adobe.com/docs/analytics.html?lang=zh-Hans)

## ![图标](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager 中的修复和改进。

### 修复和改进 {#aam-fixes-and-improvements}

* 从Admin Console中删除IMS用户帐户时，如果该用户帐户属于用户组，则不会从Audience Manager中删除该用户帐户。 现在，在从Audience Manager中删除IMS用户帐户时，IMS用户帐户会自动从Admin Console用户组取消映射。 (AAM-57633)

## ![图标](/assets/aem.png) Experience Manager {#aem}

Adobe建议您经常访问[Experience Manager版本更新和路线图](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=zh-Hans)以保持最新的发行信息。

* **Experience Manager as a Cloud Service**

   Experience Manager as a Cloud Service 中的新增功能：

   * **Adobe Experience Manager as aCloud Service的XML Documentation**

      * **云原生组件内容管理系统**  — 适用于Adobe Experience Manager的XML Documentation可作为Cloud Service使用。获取可让您大规模创作、管理和交付文档和内容的环境。
      * **AI支持的文档**  — 智能标记功能，可自动从用于元数据标签的文本中识别和提取相关元数据关键字。
      * **Web编辑器的新外观**  - UI更改的新外观使其更直观。底层架构已从珊瑚变为基于反应的光谱。

      有关更多信息，请访问[Adobe Experience Manager的XML文档](https://www.adobe.com/products/xml-documentation-for-experience-manager.html)。

   * **AEM as a Cloud ManagerCloud Service**

      * [!UICONTROL 预] 览服务以滚动方式部署到所有程序。在为[!UICONTROL 预览服务]启用了“计划”后，将在产品中通知客户。 请参阅[访问预览服务](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/manage-environments.html?lang=en#access-preview-service)。
      * 现在，在生成步骤期间下载的Maven依赖项会在管道运行之间缓存。 此功能将在未来几周为客户启用。
      * 您现在可以通过[!UICONTROL 编辑程序]对话框编辑程序的名称。
      * 在项目创建期间和默认的[!UICONTROL 通过管理Git工作流在Push]命令中使用的默认分支名称已更改为`main`。
      * 界面中的编辑程序体验已刷新。
      * 质量规则`ImmutableMutableMixCheck`已更新，可将`/oak:index`节点分类为不可变。
      * 质量规则`CQBP-84andCQBP-84--dependencies`已合并到单个规则中。 作为此整合的一部分，对依赖项的扫描可以更准确地确定部署到Experience Manager运行时的第三方依赖项中的问题。
      * 为避免混淆，“环境详细信息”页面上的“发布Experience Manager”和“发布调度程序”区段行已进行整合。
      * 添加了新的代码质量规则来验证`damAssetLucene`索引的结构。 请参阅[自定义DAM资产Lucene Oak索引](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/test-results/custom-code-quality-rules.html?lang=en#oakpal-damAssetLucene-sanity-check)。
      * 现在，环境详细信息页面会根据需要显示发布和预览服务的多个域名。 请参阅[环境详细信息](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/manage-environments.html?lang=en#viewing-environment)。
   * **Experience Manager Assets as a Cloud Service**

      资产的新增功能：

      * [!UICONTROL 内容] 自动化功能允许Experience Manager资产使用Adobe Creative Cloud API大规模自动化资产生产。它可显着减少创建同一资产变体所需的时间和迭代次数，从而提高内容速度。 该功能不需要任何编程，也可从DAM内工作。 请参阅[使用Adobe Creative Cloud集成生成资产的变体](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/manage/cc-api-integration.html?lang=en)。
      * [提供了适用于Adobe Photoshop、Adobe Illustrator和Adobe InDesign的Adobe资产链接3.0](https://helpx.adobe.com/cn/enterprise/using/adobe-asset-link.html) 和适用于Adobe XD的 [AdobeAdobe资产链接2.0](https://helpx.adobe.com/cn/enterprise/using/adobe-asset-link-for-xd.html) 。它支持Assets Essentials，并能够自动作为Cloud Service或Assets Essentials连接到Experience Manager。
      * 使用[资产批量摄取工具](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/manage/add-assets.html?lang=zh-Hans#asset-bulk-ingestor)可在批量摄取期间添加元数据。

      资产预发行渠道的新增功能：

      * 视图设置经过增强，允许您选择默认视图和默认排序参数。
      * [!UICONTROL 链接共享]下载功能使用异步下载来提高下载速度。 请参阅[下载使用链接共享共享的资产](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/manage/download-assets-from-aem.html?lang=en#link-share-download)。
      * 您可以根据属性谓词搜索和筛选文件夹。
      * Experience Manager资产嵌入PDF查看器以预览支持的文档格式。 它由Adobe Document Cloud提供。 利用此功能，可预览PDF和其他多页文件，而无需进行任何复杂的处理。 它改进了与Experience Manager6.5的功能对等性。预览中提供的控件包括缩放、导航到页面、取消停放控件以及全屏查看。 集成的PDF查看器支持AI、DOCX、INDD、PDF和PSD文件格式。 您可以对资产本身进行注释，但不支持在PDF文件中添加注释和批注。
      * 一项用户体验增强功能显示了文件夹中存在的资源数量。对于文件夹中超过1000个资产，资产显示的资产数量超过1000个。
      * 您可以将元数据架构直接应用到其“属性”中的文件夹。
   * **Experience Manager Sites as a Cloud Service**

      新增功能:

      * “发布到预览层”现在在站点管理UI中显示为页面状态。
      * 现在，发布到预览层会在操作结束时显示预览URL，并在页面属性中保留该URL供以后参考。
   * **Experience Manager Forms as a Cloud Service**

      新增功能:

      * 可将元数据架构直接应用于文件夹属性。
      * 在批量提取期间，可使用资源批量提取器工具添加元数据。
      * 一项用户体验增强功能显示了文件夹中存在的资源数量。如果文件夹中有 1000 多种资源，Experience Manager Assets 将显示 1000+。

      Forms的测试版功能：

      * **Experience ManagerForms作为Cloud Service — 通信**  — 通信API可帮助您结合XDP模板和XML数据以生成各种格式的打印文档。该服务允许您以同步模式生成文档。 利用API，可创建应用程序，以便：
         * 使用XML数据填充模板文件，以生成文档。
         * 以各种格式生成输出表单，包括非交互式PDF打印流。
         * 从XFA表单PDF和Adobe Acrobat表单(AcroForm)生成打印PDF。

      您可以写入[formscsbeta@adobe.com](mailto:formscsbeta@adobe.com)以注册测试版程序。

   * **Experience Manager Screens作为Cloud Service**

      * 批量设备注册管理意味着可以更快、更高效地配置大量播放器设备。
      * 改进了每个设备、显示和渠道清单视图的搜索和过滤选项。
      * 设备健康快照通过提供关键状态一目了然来节省时间。
      * 对象详细信息页面提供了项目中每个对象最相关信息的摘要。








### Experience Manager 的新课程和教程 {#tutorials-aem}

过去一个月发布的新视频、教程及课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 7 月 | [适用于Adobe Experience Manager的XML Documentation](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/tutorials/overview.html?lang=en) | 文章 | 了解[!UICONTROL XML文档解决方案]如何提供所有核心CCMS函数，如协作、审阅、翻译、搜索和报告DITA内容。 这些功能通过高效的内容重用和功能强大的工作流，使作者能够在更短的时间内完成更多工作。 |
| 2021 年 7 月 | [AEM无头GraphQL Postman集合](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/video-series/modeling-basics.html?lang=en) | 视频 | 了解如何在 Adobe Experience Manager (AEM) 中定义和使用内容片段，以便与 GraphQL 一起使用。 |

{style=&quot;table-layout:auto&quot;}

### Experience Manager 发行信息 {#aem-links}

以下是发行说明和其他发行信息链接，可供Experience Manager:

* [Experience Manager为Cloud Service发行说明](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html?lang=en)
* [Experience Manager as a Cloud Service 版本信息](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/home.html?lang=en)
* [Experience Manager Cloud Manager 发行说明](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=en)
* [Automated Forms Conversion Service 发行说明](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=zh-Hans)
* [Experience Manager 6.5 Service Pack 发行说明](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=zh-Hans)
* [Experience Manager 6.4 Cumulative Fix Pack 发行说明](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=zh-Hans)
* [Experience Manager Assets Dynamic Media 发行说明](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=zh-Hans)
* [Experience Manager Brand Portal 发行说明](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=zh-Hans)
* [Experience Manager 桌面应用程序发行说明](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=zh-Hans)
* [Experience Manager Dispatcher 发行说明](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=zh-Hans)
* [Adobe Primetime 发行说明](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html)
* [Livefyre 发行说明](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html)

### 其他帮助资源进行Experience Manager

* [Experience Manager Sites as a Cloud Service 指南](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/landing/home.html?lang=zh-Hans)
* [Experience Manager 6.5 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=zh-Hans)
* [Experience Manager 6.4 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=zh-Hans)
* [Experience Manager 6.3 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html)
* [Experience Manager 6.2 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=zh-Hans#previous-updates)
* [Experience Manager 文档的旧版本](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Cloud Manager 用户指南](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=zh-Hans)
* [Dynamic Media Classic 帮助主页](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=zh-Hans)
* [Experience Manager 文档：最近的更新](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=zh-Hans#aem-as-a-cloud-service)

## ![图标](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign 提供了一种直观、自动的方式，以通过在线和离线营销渠道来交付一对一的消息。您现在可以利用根据客户习惯和喜好所决定的体验，来预测客户的需求。

### 最新产品版本

详细了解最新发布的功能、改进和修复：

* [Campaign v8发行说明](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/whats-new.html?lang=en)
* [Campaign Standard 发行说明](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=zh-Hans)
* [Campaign Classic 发行说明](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=zh-Hans)

### [!UICONTROL Campaign] 的新课程及教程 {#tutorials-campaign}

| 发布日期 | 名称 | 解决方案 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 7 月 | [通过组合查询结果来优化目标](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/process-management/refine-targets-by-combining-query-results.html) | Campaign v8 | 了解如何在工作流程中通过使用交集或并集活动来组合查询结果，进而优化目标。 |
| 2021 年 7 月 | [创建营销计划、项目和活动](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/getting-started/create-a-marketing-plan-programs-and-campaigns.html) | Campaign v8 | 了解如何创建营销计划、项目和促销活动，为促销活动设置属性，并了解如何使用计划。 |
| 2021 年 7 月 | [配置和管理订阅服务](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/configure-and-manage-subscription-services.html) | Campaign v8 | 了解如何设置和管理订阅和定位订阅者。 |

{style=&quot;table-layout:auto&quot;}

### Campaign 帮助资源

* Adobe Campaign v8:[帮助中心](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html) - [发行说明](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/whats-new.html?lang=en) - [实施指南](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=en)
* Adobe Campaign Standard：[帮助中心](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=zh-Hans) - [发行说明](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=en) - [操作方法视频](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=en) - [发行计划](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=zh-Hans) - [最新文档更新](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=en)
* Adobe Campaign Classic：[帮助中心](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=zh-Hans) - [发行说明](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=en) - [操作方法视频](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=en)- [最新文档更新](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=en)
* Adobe Campaign 控制面板：[文档](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en) - [发行说明](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=zh-Hans) - 有关 [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=zh-Hans)/[Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=zh-Hans) 的操作方法视频

## ![Icon](/assets/advertising-cloud.png) 广告 {#adcloud}

[!DNL Adobe Advertising] 的发行说明。

* [Advertising DSP 中的新增功能](#adcloud-dsp)
* [Advertising Search 中的新增功能](#adcloud-search)

### [!DNL Advertising DSP] 中的新增功能 {#adcloud-dsp}

上次更新日期：**2021 年 6 月 10 日，为 6 月 16 日发布的版本进行更新**

| 功能 | 描述 |
| -----------| ---------- |
| 营销活动管理 | （6 月 16 日版）针对标准展示投放位置推出预测功能，并带有投放位置级展示安排和预算。 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Advertising Search] 中的新增功能 {#adcloud-search}

上次更新：**2021 年 5 月 19 日发布 5 月 18 日版**

| 功能 | 描述 |
| -----------| ---------- |
| [!UICONTROL 通知中心 Beta 版] | [!UICONTROL 通知中心 Beta 版]现在向所有用户开放。使用它订阅关于帐户身份验证错误、触发的自定义警报以及完成您生成的 [!UICONTROL Advertising Insights] 的电子邮件和 Web 通知。<br>可从以下任意一项中查看通知：<ul><li>[!UICONTROL “通知”]面板，从任意页面右上角的“通知”链接打开它。</li><li>[!UICONTROL “见解和报表”>“通知中心 Beta 版”]上的[!UICONTROL “通知中心”]。</li></ul><br><b>注意：</b>由于改进了通知的存储方式，因此清除了所有现有的通知。 |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/magento.png) [!DNL Commerce] (Magento) {#magento}

有关Adobe商务发行说明，请参阅以下链接：

* [Magento Commerce和开源](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

## ![图标](/assets/target.png) [!DNL Target] {#target}

请参阅[[!DNL Target] 发行说明](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=zh-Hans)了解最新发行信息。

## ![图标](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] 是一个全面的应用程序，适用于寻求通过积极参与复杂购买过程的每个阶段而改善客户体验的销售线索管理和 B2B 营销人员。

### 核心 Marketo Engage 更新

有关最新的发布计划信息和发行说明，请参阅[!DNL Marketo Engage] [发布计划](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=en)。

## ![图标](/assets/workfront.png) [!DNL Workfront] {#workfront}

Adobe [!DNL Workfront] 是一个统一的工作管理应用程序，可用于分享创意、创建内容、管理复杂的流程以及将工作做到尽善尽美。

请参阅[[!DNL Workfront] 版本](https://one.workfront.com/s/product-releases)页面，查看所有产品的最新信息综述。

## ![图标](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

为 Adobe Document Cloud 发布的新视频、教程或课程。

### Document Cloud 课程和教程 {#tutorials-doc-cloud}

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 7 月 | [液态模式在Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/mobile/mobile-tutorials/liquidmode.html) | 视频 | 了解液态模式如何改善移动设备签名体验。 它减少了捏合和缩放，以便轻松聚焦可填写字段。 |
| 2021 年 7 月 | [Adobe Sign API快速入门](https://experienceleague.adobe.com/docs/document-services/tutorials/usecases/signapi.html) | 文章 | 了解开发人员如何使用Sign API来增强使用Adobe文档服务创建的应用程序和工作流。 |
| 2021 年 7 月 | [使用Adobe PDF嵌入API发布数字文档](https://experienceleague.adobe.com/docs/document-services/tutorials/usecases/ddppdfembedapi.html) | 文章 | 通过在网页中嵌入PDF查看器，用户可以查看文档，而无需重新设计HTML和CSS或阻碍访问您的网站。 |
| 2021 年 7 月 | [使用Adobe文档服务API进行学生 — 教师协作](https://experienceleague.adobe.com/docs/document-services/tutorials/usecases/educationcollab.html) | 文章 | 了解适用于`Node.js`应用程序的官方SDK，以访问PDF服务API。 这样，您就可以将Microsoft® Word或Microsoft® Excel等文档转换为PDF。 |
| 2021 年 7 月 | [使用Adobe文档服务API进行作业发布](https://experienceleague.adobe.com/docs/document-services/tutorials/usecases/jobposting.html?lang=en) | 文章 | 在与多个用户一起操作网站时，设计一个体验以确保每个用户都能获得流畅的体验至关重要。 了解如何自动将所有上传的文档转换为PDF，并在帖子中内嵌这些文档。 |
| 2021 年 7 月 | [使用Adobe文档服务API创建和编辑报表](https://experienceleague.adobe.com/docs/document-services/tutorials/usecases/reportcreation.html?lang=en) | 文章 | PDF使用表格、图形和交互式内容轻松共享富文档，其格式让每个人都能查看。 了解如何与其高管、股东、捐赠者或其他利益相关方共享这些统计数据。 |
| 2021 年 7 月 | [使用Adobe文档服务API进行审阅和批准](https://experienceleague.adobe.com/docs/document-services/tutorials/usecases/reviews.html?lang=en) | 文章 | 了解如何使用多个Adobe文档服务API解决实际操作的审阅和批准用例。 |
| 2021 年 7 月 | [使用Adobe文档服务API进行搜索和索引](https://experienceleague.adobe.com/docs/document-services/tutorials/usecases/searching.html?lang=en) | 文章 | 本教程探讨了Adobe文档服务API的奇妙功能，以及如何轻松使用它们存档和数字化文档。 我们通过构建一个Express NodeJS应用程序，然后集成用于存档、数字化和文档转换的Document Services API来探索这些功能。 |
| 2021 年 7 月 | [使用Adobe文档服务API管理员工优惠信](https://experienceleague.adobe.com/docs/document-services/tutorials/usecases/offer.html) | 文章 | 本教程将指导您设置一个Node Express项目，该项目将显示一个Web表单，供用户使用员工详细信息进行填充。 这些详细信息使用Web上的文档服务来生成优惠信(PDF)，以后可以将该PDF交付给客户，以供其使用Adobe Sign API进行签名。 |
| 2021 年 7 月 | [使用Adobe文档服务API管理法律合同](https://experienceleague.adobe.com/docs/document-services/tutorials/usecases/legal.html) | 文章 | 在本教程中，我们将探索Adobe文档服务API在生成文档中的自定义输入字段方面的功能。 我们还探讨如何轻松地将这些生成的文档转换为受保护的便携式文档格式(PDF)，以防止数据操作。 |
| 2021 年 7 月 | [使用Adobe文档服务API创建NDA](https://experienceleague.adobe.com/docs/document-services/tutorials/usecases/nda.html) | 文章 | 了解如何为您的公司NDA创建Microsoft® Word模板。 Adobe免费的Microsoft® Word加载项，即Adobe文档生成标记，可帮助您插入“标记”以输入动态值。 您还了解如何将JSON数据传递到模板并创建动态PDF。 然后，您可以通过电子邮件发送该PDF，或在浏览器中向协作者显示该PDF，具体取决于您的业务要求和目标。 |
| 2021 年 7 月 | [使用Adobe文档服务API管理销售建议书和合同](https://experienceleague.adobe.com/docs/document-services/tutorials/usecases/sales.html) | 文章 | 了解如何使用动态数据和工作流构建一个创建销售建议的高效流程。 |
| 2021 年 7 月 | [使用Adobe文档生成API处理发票](https://experienceleague.adobe.com/docs/document-services/tutorials/usecases/invoices.html?lang=en) | 文章 | 了解如何使用Adobe文档生成API自动生成发票、对PDF进行密码保护以及向每位客户交付发票。 您只需对Node.js、JavaScript、Express.js、HTML和CSS稍加了解即可。 |

{style=&quot;table-layout:auto&quot;}

有关 Document Cloud 的帮助，请参阅：

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=zh-Hans)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=zh-Hans)
* [Document Cloud 学习与支持](https://helpx.adobe.com/cn/support/document-cloud.html)

## ![图标](/assets/creative-cloud-24.png) Creative Cloud 企业版 {#creative-cloud}

为 Creative Cloud 企业版发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| ----------| --------- | --------- | --------- |
| 2021 年 6 月 | [在 iPad（和 iPhone）上试用 Fresco](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/frescoworkshop.html) | 视频 | 在这个为时 15 分钟的实践研讨会中，借助 Adobe Fresco 探索全新的数字绘图和绘画世界。快速了解如何使用图层和剪贴蒙版来使绘画和纹理与基本形状保持一致。 |
| 2021 年 6 月 | [解码图形格式大杂烩](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/alphabetsoup.html) | 视频 | PG、PNG、SVG、GIF 和 EPS 文件都是设计中常用的格式，一些用于网页，另一些则用于演示文稿、出版物和创意项目。不过… 它们代表什么，而您应该选择哪一种呢？在这个为时 15 分钟的实践研讨会中找到答案。 |

{style=&quot;table-layout:auto&quot;}

有关最新教程，请参阅 [Creative Cloud 企业版教程](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=zh-Hans)。
