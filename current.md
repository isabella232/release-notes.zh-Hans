---
title: Adobe Experience Cloud 发行说明
description: Experience Cloud 发行说明模板
doc-type: 发行说明
last-update: 2019 年 11 月 日
author: mfrei
translation-type: tm+mt
source-git-commit: 2c6076aa0af7b9a273e31b1f8919e006ff48e6b4

---


# 早期访问- Adobe Experience cloud发行说明- 2019年11月

> [!IMPORTANT]此页面包含预发行内容，在发行版之前可能会发生更改。

Adobe Experience Cloud 的新增功能和修复。

> [!NOTE]若要通过电子邮件接收有关即将发行的版本的通知，请订阅 [[!DNL Adobe 产品更新早知道]](https://www.adobe.com/subscription/priority-product-update.html)。对于发行之后发布的新信息，将使用发布日期进行标记。

**发行日期：2019 年 30 月 10 日**

* [Experience Cloud 界面](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html)（链接到解决方案帮助）
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html)（链接到解决方案帮助）
* [!DNL Advertising Cloud](#adcloud)

## Experience Cloud 界面 {#ecloud}

Experience Cloud 界面和产品管理的发行说明。

* 源页面在2019年12月已弃用。 查找产品内弃用通知。 (MCUI-10039)
* 更新了应 [用程序选择器中](https://www.adobe.com/marketing/campaign.html) “了解更多”链接。 (MCUI-10034)
* 改进了Experience cloud界面核心平台的稳定性和响应性。 (MCUI-6822)
* 修复了Experience Cloud UI中的安全漏洞。 (MCUI-9942)
* 修复了客户属性中阻止某些客户架构验证的关键问题。 (MCUI-10024, MCUI-6479)
* 改进了受众库以删除实时受众创建不支持的维度。 (MCUI-10046)

有关产品文档，请参阅 [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html)。

## Experience Platform {#platform}

Experience Platform、Experience Platform Launch、Identity Service 和安全公告的发行说明。

* [Experience Platform Launch](#launch)
* [安全公告与建议](https://helpx.adobe.com/security.html)（所有 Adobe 产品）

### Experience Platform Launch {#launch}

有关发行说明和产品文档，请参阅 [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html)。

## [!DNL Analytics] {#analytics}

Adobe Analytics 中的新增功能和修复：

* [Adobe Analytics 中的新增功能、增强功能和修复](#aa-features)
* [Analytics 管理员的重要注意事项](#aa-notices)
* [AppMeasurement](#appm)

有关产品文档，请参阅 [Adobe Analytics 帮助主页](https://docs.adobe.com/content/help/en/analytics/landing/home.html)。

### Adobe Analytics 中的新增功能、增强功能和修复 {#aa-features}

| 功能 | 描述 |
| -----------| ---------- | 
| 客户旅程分析 | 2019年11月21日，Adobe将作为 [Adobe Analytics的附加工具提供客户旅程分析](https://www.adobe.com/analytics/customer-journey-analytics.html) 。<br><br/>客户旅程分析允许您从任何渠道获取所有客户数据— 线上及线下均可— Adobe Experience Platform中，然后像现在使用Analysis Workspace分析现有数字数据一样分析这些数据。 客户旅程分析功能允许您控制如何在Analysis Workspace中通过任何常见客户ID连接线上和线下数据，最后允许您进行归因、细分、流程、流失等。 Adobe Analytics中的所有客户数据集。<br><br/>Analytics Select、Prime和Ultimate客户有资格购买此附加产品。 有关更多详细信息，请与您的Adobe客户团队联系。 |
| 隐私服务 API：CCPA | 《加州消费者隐私法案》(CCPA) 加强了对美国加利福尼亚州居民的隐私权和消费者保护。这项法案将于 2020 年 1 月 1 日正式生效。<br><br/>CCPA 为加州居民提供了新的数据隐私权，例如，访问和删除个人数据的权利，知晓其个人数据是否被出售或披露（包括披露给谁）的权利，以及拒绝出售其个人数据的权利。<br><br/>为应对即将生效的 CCPA，我们的“隐私服务”将支持选择退出出售个人数据的请求。<br><br/>“隐私服务”此前称为 GDPR 服务，现在不仅保留了以前的各项功能，而且扩展到可支持 CCPA。<br/><br/>[Analytics 中的 CCPA](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/an-ccpa-overview.html)<br><br/>[隐私服务概述](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |
| 隐私报告：Analytics Admin Console | 启用 Analytics 的隐私报告之后，会为报表包添加一系列保留变量。这些变量旨在协助收集点击层面的消费者同意数据。<br><br/>新维度：<br/><ul><li>同意管理选择退出</li><li>同意管理选择加入</li><li>[同意管理变量](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/consent-variables.html)</li></ul> |
| 音频和视频分析：隐私支持 | 两个新变量已添加到媒体收集 API：<br/><ul><li>analytics.optOutServerSideForwarding</li><li>analytics.optOutShare</li></ul><br/><br/>它们是可选变量，可用于捕获消费者在点击时的同意状态。<br/><br/>[媒体收集 API 文档](https://docs.adobe.com/content/help/en/media-analytics/using/media-collection-api/mc-api-overview.html)<br/><br/>新的 Analytics 同意管理上下文数据变量已添加到 Analytics 的联盟合作表单中。现在，可以使用这些变量来标记包括合作伙伴在内的“选择退出共享或销售”点击次数。<br/><br/>[下载联盟合作表单](https://docs.adobe.com/content/help/en/media-analytics/using/federated-analytics.html#download-the-federated-analytics-form) |

#### 修复

* 修复了在尝试删除“未知用户”拥有的日期范围时导致错误的问题。(AN-185540)

### [!DNL Analytics] 管理员的重要注意事项 {#aa-notices}

| 注意 | 添加或更新日期 | 描述 |
| -----------| ---------- | ---------- |
| “查看存档 **[!UICONTROL 的EOL]** ”选项 | 2019年10月30日 | 宣布2020年1月，功能板管理器（“组件”&gt;“功能板”）中的“查 **[!UICONTROL 看存档]** ”选项的寿&#x200B;**[!UICONTROL 命结束日期]**。 |
| EOL of **[!UICONTROL Enforce IP Login Restrictions（强制IP登录限制）选项]** | 2019年10月30日 | 宣布2020年1月IP登录白名(**[!UICONTROL Enforce IP Login Restrictions]**)功能的终止日期(位于 **[!UICONTROL Admin &gt; Company Settings &gt; Security]** menu下)。 |
| 更新了对Cookies上SameSite属性的处理 | 2019 年 10 月 15 日 | 2019年8月，Adobe宣布向Analytics设置的所有Cookie添加SameSite Cookie设置。 在以下情况下应用逻辑中的更新：<ul><li>所有不基于Webkit的第三方Cookie的SameSite属性均设置为 `none`。</li><li>所有其他Cookie没有设置SameSite属性。</li></ul> |
| 停止支持 TLS 1.1 | 2019 年 10 月 3 日 | 我们一直不懈努力，致力于维持最高安全标准并提升客户数据安全。为此，Adobe Analytics 对 TLS 1.1 的支持将持续到 2020 年 3 月 31 日，在这之后将不再支持 TLS 1.1。 |
| 圣何塞 FTP 中转站停止为伦敦和新加坡提供支持 | 2020 年 7 月 | 对于位于伦敦和新加坡的客户，我们将不再提供伦敦或新加坡与圣何塞数据中心 [ftp.omniture.com](ftp://ftp.omniture.com/) 之间的数据中转支持。<br/><ul><li>伦敦客户，请使用 [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>新加坡客户，请使用 [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li> |
| 更新 Analysis Workspace 自由格式表总数 | 2019 年 9 月 12 日 | 从 2019 年 10 月开始，自由格式表总数行在计算时，会将已应用的[报表过滤器](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html)考虑在内。迄今为止，总数仅计算的是分段数目。根据这项变化，作为从属的可视化图表（例如，链接的[!UICONTROL 概要数字]可视化图表）将会进行相应的更新，导出的 CSV 和 PDF 数据同样也会更新。 |
| 面向 Analytics 用户的 `createDate` 字段即将发生变化 | 2019 年 8 月 30 日 | 在 2019 年 10 月或 11 月，Analytics 用户的 `createDate` 字段将由美国太平洋时间更新为包含时区信息且格式正确的日期/时间值。(AN-183468) |
| 支持历史时区偏移 | 2019 年 8 月 8 日 | Analytics 现在将自动为带有时间戳的点击处理时区偏移。在 8 月 8 日实施此更改后，载入数据以进行历史处理的系统在发送数据之前将不再需要调整时区偏移。 |
| 分类规则生成器限制 | 添加于 2019 年 6 月 5 日 | 这些不是新限制，只是最近已添加到[此处](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html)的文档。 |
| 新的区段运算符限制 | 添加于 2019 年 5 月 31 日 | 从 2019 年 7 月 18 日开始，区段运算符&#x200B;_包含任意_、_不包含任意_、_包含全部_&#x200B;和&#x200B;_不包含全部_&#x200B;将限制为每个输入字段 100 个词。这项限制将适用于此日期之后的所有新增区段和修改区段。超出此限制的现有区段将继续受到支持，但在缩短输入字段前，将无法进行修改或保存。作为我们持续不断努力的一个组成部分，将应用这些限制以提高查询性能。 |
| 更改对&#x200B;**[!UICONTROL 启用日期]**&#x200B;和&#x200B;**[!UICONTROL 数字 2 分类]**&#x200B;的支持 | 更新日期：2019 年 5 月 28 日 | 已从代码库中移除了导入数字 2 分类和启用日期的分类的功能。这项更改已随 2019 年 7 月维护版本的发布而生效。如果您的导入文件中包含“数字”或“启用日期”列，则这些单元格会被静默忽略，同时该文件中的任何其他数据均会正常导入。<br/>现有的分类仍可以通过标准分类工作流程导出，并将继续在报表中可用。 |
| 更改&#x200B;_报表总数_&#x200B;的计算 | 更新日期：2019 年 7 月 9 日 | 在 **2019 年 6 月 18 日**，Adobe Analytics 采取了统一方式计算所有维度和量度中的&#x200B;_报表总数_。这导致某些报表（通常是 Prop 或客户归因报表）的总数出现变化。进行此项更改之前，在计算总数时，无论&#x200B;_未指定_&#x200B;是否显示在报表中，有些报表总数要么包含要么排除&#x200B;_未指定_&#x200B;行项目，总之处理方式并不一致。<br/>自 2019 年 6 月 18 日开始，_未指定_&#x200B;将始终显示在报表总数中，即使它在报表中未显示为行项目也是如此。此外，进行此项更改之后，使用&#x200B;_存在_&#x200B;或&#x200B;_不存在_&#x200B;逻辑的区段，对于不同的维度可能会看到不同的结果，尤其是其中的&#x200B;_未指定_&#x200B;具有特殊名称（如推荐人类型维度的“已键入/已添加书签”行项目或设备类型维度的“其他”行项目）的维度。此更改将影响 Analysis Workspace、Reports &amp; Analytics、Ad Hoc Analysis、Report Builder 和报表 API。 |
| 更新从 Analysis Workspace 下载 CSV 时的操作 | 2019 年 4 月 10 日 | 从 2019 年 4 月 11 日开始，已对 Analysis Workspace 中的 **[!UICONTROL CSV 下载]**&#x200B;功能（和&#x200B;**[!UICONTORL 复制到剪贴板]**）进行了一些更改，目的在于从导出的数据中删除格式。  <ul><li>千位分隔符将不再包含在内。小数分隔符将继续包含在内，并将遵循 **[!UICONTROL 组件 &gt; 报表格式 &gt; 千位分隔符]**&#x200B;下定义的格式。注意：使用逗号作为小数分隔符的数值将会继续在导出的 CSV 中引用。</li><li>不会显示任何货币符号。</li><li>不会显示任何百分比符号。百分数将以小数形式显示。例如，75% 将表示为 0.75。</li><li>时间将以秒为单位显示。</li><li>同类群组表将只显示原始值；百分比将被删除。</li><li>如果数字无效，将显示空单元格。</li></ul> |
| Analysis Workspace 调试器命令即将变更 | 2019 年 4 月 4 日 | **2019 年 6 月 13 日**，开启 Analysis Workspace 调试器的控制台命令变为 adobeTools.debug.includeOberonXml。adobe.tools.debug.includeOberonXml 命令将于该日期之后停止运行。 |
| 移动浏览器版本号 | 2019 年 2 月 7 日 | 从 2019 年 1 月 8 日开始，我们将移动浏览器版本号的截断级别从 2 更改为 1。在该日期之后，版本号将只显示前两个级别（例如 _Firefox 64.0.2_ 现在报告为 _Firefox 64.0_）。 |
| 终止 [!DNL Ad Hoc Analysis] 的生命周期 | 2019 年 1 月 29 日 | 2018 年 8 月 6 日，Adobe 宣布计划终止 [!DNL Ad Hoc Analysis] 的生命周期。确定终止日期后，Adobe 会立即与大家共享此信息。<br/>有关更多信息（包括在此期间，将兼容哪个 Java 版本），请访问 [[!DNL Discover Workspace]](https://adobe.ly/discoverworkspace)。 |
| 简短 [!DNL Analytics] 报表链接 | 2019 年 1 月 14 日 | 系统已从 2019 年 1 月 17 日星期四起开始按照滚动计划表清理和删除任何在一年内未被访问过的简短 [!DNL Analytics] 报表链接。 |
| 数据馈送：post_product_list 列 - 大小更改 | 2019 年 1 月 9 日 | 2019 年 2 月 7 日，Adobe 将 post_product_list 列的大小从 64 KB 扩展到 16 MB。这项更改可确保在处理过程中添加到 post_product_list 的推销 eVar 值不会导致产品和收入值截断。如果您的流程需要提取 post_product_list 值，请确保这些流程可以处理长度最大为 16 MB 的值，否则系统将按照 16 KB 的长度将该值截断，以避免数据获取失败。 |
| 影响不活动的 [!DNL Analytics Live Stream] 端点的管理更改 | 2018 年 12 月 20 日 | 从 2019 年 2 月 1 日开始，可能会禁用持续 90 天没有活动客户连接的 [!DNL Live Stream] 端点。您可以联系客户关怀团队查询您的 [!DNL Live Stream] 端点，并在必要时重新启用它们。此外，请确保您的客户进程按照服务设计要求保持持久连接，并在连接断开或中断时实施重新连接。 |
| 由于对 TLS 1.0 的支持终止而更新 Adobe [!DNL Report Builder] | 2018 年 9 月 7 日 | 由于对 TLS 1.0 的支持即将终止，我们建议 [!DNL Report Builder] 用户在 2019 年 2 月之前下载 v5.6.21 版。在该日期之后，以前版本的 [!DNL Report Builder] 将无法再正常运行。 |

### [!DNL AppMeasurement] {#appm}

请参阅 [AppMeasurement for Javascript 发行说明](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html)。

## Audience Manager {#aam}

Audience Manager 中的新增功能、增强功能和修复。

| 功能 | 描述 |
|--- |----|
| [配置文件合并规则增强功能](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/merge-rules-overview.html) | 我们发布了针对配置文件合并规则 [!UICONTROL 的一系列增强功能]: <ul><li>现在，最多100台设备支持批量细分评估。</li><li>我们提高了特征和细分群体的报告准确性。</li><li>我们提高了使用跨设备ID生成的批文件的准确性。</li><li>我们更新了文档，其中包含每个规则的更详细的使用案例。 请参 [阅配置文件合并规则](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/merge-rule-targeting-options.html)、外部设备 [图使用案例和配置文件链](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/external-graph-use-cases.html)接设备图使用案例的一般用例 [](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/profile-link-use-case.html)。</li></ul> |
| [批量管理工具](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html) | 我们发布了新版本的批量管理工作表，该工作表适用于MacOS和Microsoft windows操作系统，并支持Experience cloud登录。 |
| [HTTP Strict-Transport-Security](https://docs.adobe.com/help/en/audience-manager/user-guide/overview/data-security-and-privacy/data-security.html#hsts) | 我们增加了对Web安 [!DNL HTTP Strict-Transport-Security]全策略的支持，该策略可防止cookie拦截和协议降级攻击。 |

**修复和改进**

* 我们修复了Audience Marketplace中的一个错误，在该错误中，当客户提交每月细分使用情况时，UI返回错误409。 (AAM-50825)
* 我们修复了派生信号中的一个错误，该错误导致客户在很短的时间内无法创建新的派生信号。 (AAM-50968)
* 我们修复了基于人员的目标中的一个错误，该错误导致客户无法更改目标的名称。 (AAM-51025)
* 我们修复了一个错误，该错误导致一些用户拥有重复的帐户以登录Audience Manager UI。 由于与重复帐户关联的权限，这些用户无法访问UI的某些部分并执行操作。 (AAM-50818)
* 我们继续改进Audience Manager UI的辅助功能。 (AAM-48932、AAM-49043、AAM-49054、AAM-49371、AAM-49375)

## Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新增功能、修复和更新。Adobe 建议那些采用内部部署的客户部署最新的修补程序，以便确保获得更高的稳定性、安全性和性能。

### 产品版本

* **Brand Portal 6.4.5**

   Adobe Experience Manager Assets Brand Portal 6.4.5是一个功能版本，它侧重于为Brand Portal用户（外部代理／团队）提供将内容上传到Brand Portal和发布到AEM Assets的能力，而无需访问创作环境。 此功能在Brand Portal中称为 [Asset Sourcing](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/asset-sourcing-in-brand-portal/using-asset-sourcing/brand-portal-overiew-using-asset-sourcing.html)，它通过为用户提供双向机制来贡献资产并与其他全球分布的Brand Portal用户共享资产，从而改善客户体验。

   请参 [阅AEM Assets Brand Portal中的新增功能](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/whats-new.html)。

   See [Release notes](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html).

* **AEM Forms Automated Conversion Service**

   自动表单转换服务通过将PDF表单自动转换为自适应表单，帮助加快数据捕获体验的数字化和现代化。 此服务由Adobe Sensei提供支持，可自动将您的PDF表单转换为设备友好型、响应式和基于HTML5的自适应表单。 在利用PDF表单和XFA中的现有投资的同时，该服务在转换过程中还将适当的验证、样式和布局应用于自适应表单字段。

   请参 [阅Adobe Experience Manager Forms自动转化服务](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/introduction.html)。

* **Cloud Manager 2019.10.0**

   Cloud Manager 2019.10.0的一般发行说明现已发布。 注释还列出了部署步骤的更新，并使项目版本得以处理。

   请参 [阅Cloud Manager 2019.10.0发行说明](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)。

### 自助

* **Activity Map**

   由于Adobe Analytics API中的安全性更改，无法再使用AEM中包含的Activity Map版本。 请参 [阅配置与Adobe Analytics的连接](https://helpx.adobe.com/experience-manager/6-5/sites/administering/using/adobeanalytics-connect.html#ConfiguringtheConnectiontoAdobeAnalytics)。

   您现在应按照 [Adobe Analytics提供的](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/getting-started/get-started-users/activitymap-install.html) Chrome、Firefox或Internet explorer使用Activity Map浏览器插件。

* **AEM Screens项目的最佳实践指南**

   新的AEM Screens _最佳实践指南提供全面的洞察和实用建议_ ，以便在数字标牌实施中想象、设计和引入有意的客户体验。 它还指导您如何使用最佳实践对业务产生积极影响，同时在AEM Screens中部署数字标牌项目。

   请参 [阅AEM Screens项目的最佳实践指南](https://docs.adobe.com/content/help/en/experience-manager-screens/using/about-guide.html)。

* **无外设体验管理**

   现在介绍了 [](https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/spa-ssr.html#main-pars_header_450130848) 用于单页应用程序的服务器端渲染的Remote Content Renderer的功能。

* **SPA和服务器端渲染**

   您可以扩展和自定义AEM驱动的SPA用于服务器端渲染的远程内容渲染服务，以满足您的需求。

   请参 [阅SPA和服务器端渲染](https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/spa-ssr.html#RemoteContentRenderer)。

* **AEM Project Archetype**

   AEM Project Archetype可创建基于最小、最佳实践的Adobe Experience manager项目，作为您自己的AEM项目的起点。 使用此原型时必须提供的属性允许您指定此项目所有部分的名称，并控制某些可选特征。

   请参 [阅AEM Project Archetype](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/overview.html)。

* **AEM文档更新**

   阅读有关Adobe Experience Manager过去三个月中的重要文档更改和更新。

   请参阅 [AEM文档：近期文档更新](https://helpx.adobe.com/experience-manager/documentation-updates.html)。

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

### 文档资源

* Adobe Campaign Standard：[文档](https://helpx.adobe.com/support/campaign/standard.html) - [发行说明](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [操作方法视频](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [发行计划](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic：[文档](https://helpx.adobe.com/support/campaign/classic.html) - [发行说明](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [操作方法视频](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)

## Advertising Cloud {#adcloud}

更新日期：2019 年 10 月 12 日

| 视图 | 功能 |
|------|---------|
| 搜索促销活动 | Advertising Cloud 现在可以同步 Yahoo! Japan Display Network 上的帐户，同时，还可为其提供广告级别的跟踪。如果您提供某个帐户的登录详细信息，则该帐户中的所有现有促销活动、广告组和广告在促销活动管理视图中均以只读形式提供。点击次数、成本、转化次数和其他性能数据可在促销活动管理视图以及基本报表和高级报表中可用。 |
|  | （使用 Google Analytics 的广告商）Advertising Cloud Search 可以为特定 Google Analytics 帐户、资产和视图组合同步转化量度，以进行优化和报告。页面查看次数、会话数、跳出率（计算公式为跳出次数/会话数）和会话持续时间会自动包含在内。每个数据源最多可以包含 16 个其他量度。 |
|  | （使用 Advertising Cloud-Adobe Analytics 集成的广告商的现有 Google Ads 帐户）s_kwcid 跟踪代码提供了一种新格式，通过该格式，Advertising Cloud 可以使用 Adobe Analytics 报告和分析功能共享该帐户的相关数据。最新格式包括促销活动 ID 和广告组 ID 的参数。要在 Analytics 中准确报告促销活动级别和广告组级别的 Google Drafts and Experiments 促销活动，这些参数必不可少。如果您现有的 Google 帐户包括 Google Drafts and Experiments 促销活动，则请编辑每个帐户的“帐户跟踪”设置，以迁移到新的 s_kwcid。如果您没有 Google Drafts and Experiments 促销活动，则可以选择迁移到新格式。注意：所有新的 Google 帐户都会自动使用新格式。 |
| 搜索高级促销活动管理 (ACM) | （Google Ads 促销活动）现在，您可以为 Google 文本广告和购物广告模板配置促销活动级别的最终 URL 后缀。 |
|  | （Google Ads 促销活动）可选的“标题 3”和“描述 2”字段可用于 Google 扩展的文本广告。 |
| 报表 | 以下 Bing Ads 展示份额量度已在最新的 Bing Ads API 中停用，且在 10 月 11 日之后不会再收集这些量度数据：搜索排名丢失 IS%，搜索出价丢失 IS% (Bing)，搜索页面相关性丢失 IS% (Bing)，以及搜索关键字相关性丢失 IS% (Bing)。以前收集的量度仍可用于报告。 |
| Adobe Analytics 集成 | （仅限使用 Adobe Analytics 的广告商）在 Analysis Workspace 中，从未收集过数据的“设备 (AMO ID)”维度不再可用。要报告在线 Analytics 数据，请使用“移动设备类型”维度。要报告按设备类型划分的搜索引擎流量量度（例如点击次数、成本和展示次数），请继续使用 Advertising Cloud Search 中的报告功能。 |
