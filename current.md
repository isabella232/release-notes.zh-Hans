---
title: Adobe Experience Cloud 发行说明
description: Experience Cloud 发行说明模板
doc-type: 发行说明
last-update: 2019 年 11 月
author: mfrei
translation-type: ht
source-git-commit: 72028146219c6244c501e55e30c03de925c54b3c

---


# Adobe Experience Cloud 发行说明 - 2019 年 11 月

Adobe Experience Cloud 的新增功能和修复。

> [!NOTE] 要通过电子邮件接收有关即将发行的版本的通知，请订阅 [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html)。对于在版本发行之后发布的新信息，将使用发布日期进行标记。

**发行日期：2019 年 10 月 31 日**

* [Experience Cloud 界面](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/zh-Hans/target/using/release-notes/target-release-notes.html)（链接到解决方案帮助）
* [!DNL Primetime](https://helpx.adobe.com/cn/primetime/user-guide.html)（链接到解决方案帮助）
* [!DNL Advertising Cloud](#adcloud)（11 月 8 日更新）

在找帮助主页吗？ 请参阅 [Experience Cloud 学习与支持](https://helpx.adobe.com/cn/support/experience-cloud.html)。

## Experience Cloud 界面 {#ecloud}

Experience Cloud 界面和产品管理的发行说明。

* “信息源”页面将在 2019 年 12 月版中被弃用。请查看产品内的弃用通知。(MCUI-10039)
* 更新了应用程序选择器中 Adobe Campaign 所对应的[更多信息](https://www.adobe.com/cn/marketing/campaign.html)链接。(MCUI-10034)
* 改进了 Experience Cloud 界面核心平台的稳定性和响应性。(MCUI-6822)
* 修复了 Experience Cloud UI 中的安全漏洞。(MCUI-9942)
* 修复了“客户属性”中阻止某些客户验证架构的关键问题。（MCUI-10024、MCUI-6479）
* 改进了受众库，在其中删除了实时受众创建不支持的维度。(MCUI-10046)

有关产品文档，请参阅 [Experience Cloud](https://docs.adobe.com/content/help/zh-Hans/core-services/interface/experience-cloud.html)。

## Experience Platform {#platform}

Experience Platform、Experience Platform Launch、Identity Service 和安全公告的发行说明。

* [Experience Platform Launch](#launch)
* [安全公告与建议](https://helpx.adobe.com/cn/security.html)（所有 Adobe 产品）

### Experience Platform Launch {#launch}

有关发行说明和产品文档，请参阅 [Experience Platform Launch](https://docs.adobe.com/content/help/zh-Hans/launch/using/intro/release-notes/current.html)。

## [!DNL Analytics] {#analytics}

Adobe Analytics 中的新增功能和修复：

* [Adobe Analytics 中的新增功能、增强功能和修复](#aa-features)
* [Analytics 管理员的重要注意事项](#aa-notices)
* [AppMeasurement](#appm)

有关产品文档，请参阅 [Adobe Analytics 帮助主页](https://docs.adobe.com/content/help/zh-Hans/analytics/landing/home.html)。

### Adobe Analytics 中的新增功能、增强功能和修复 {#aa-features}

| 功能 | 描述 |
| -----------| ---------- | 
| 客户历程分析 | 2019 年 11 月 21 日，[客户历程分析](https://www.adobe.com/analytics/customer-journey-analytics.html)将作为 Adobe Analytics 的附加组件提供。<br><br/>“客户历程分析”允许您从所选的任何渠道（在线和离线）将客户数据纳入到 Adobe Experience Platform 中，然后像现在使用 Analysis Workspace 分析现有数字数据一样分析这些数据。利用“客户历程分析”中包含的功能，可以控制如何在 Analysis Workspace 中通过任何通用客户 ID 连接在线和离线数据，从而最终在 Adobe Analytics 中对整个客户数据集执行归因和细分并分析客户流向和流失等。<br><br/>Analytics Select、Prime 和 Ultimate 客户有资格购买此附加产品。有关更多详细信息，请与您的 Adobe 客户团队联系。 |
| 隐私服务 API：CCPA | 《加州消费者隐私法案》(CCPA) 加强了对美国加利福尼亚州居民的隐私权和消费者保护。这项法案将于 2020 年 1 月 1 日正式生效。<br><br/>CCPA 为加州居民提供了新的数据隐私权，例如，访问和删除个人数据的权利，知晓其个人数据是否被出售或披露（包括披露给谁）的权利，以及拒绝出售其个人数据的权利。<br><br/>为应对即将生效的 CCPA，我们的“隐私服务”将支持选择退出出售个人数据的请求。<br><br/>“隐私服务”此前称为 GDPR 服务，现在不仅保留了以前的各项功能，而且扩展到可支持 CCPA。<br/><br/>[Analytics 中的 CCPA](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/an-ccpa-overview.html)<br><br/>[隐私服务概述](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |
| 隐私报告：Analytics Admin Console | 启用 Analytics 的隐私报告之后，会为报表包添加一系列保留变量。这些变量旨在协助收集点击层面的消费者同意数据。<br><br/>新维度：<br/><ul><li>同意管理选择退出</li><li>同意管理选择加入</li><li>[同意管理变量](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/consent-variables.html)</li></ul> |
| 音频和视频分析：隐私支持 | 两个新变量已添加到媒体收集 API：<br/><ul><li>analytics.optOutServerSideForwarding</li><li>analytics.optOutShare</li></ul><br/><br/>它们是可选变量，可用于捕获消费者在点击时的同意状态。<br/><br/>[媒体收集 API 文档](https://docs.adobe.com/content/help/zh-Hans/media-analytics/using/media-collection-api/mc-api-overview.html)<br/><br/>新的 Analytics 同意管理上下文数据变量已添加到 Analytics 的联盟合作表单中。现在，可以使用这些变量来标记包括合作伙伴在内的“选择退出共享或销售”点击次数。<br/><br/>[下载联盟合作表单](https://docs.adobe.com/content/help/zh-Hans/media-analytics/using/federated-analytics.html#download-the-federated-analytics-form) |

#### 修复

* 修复了在尝试删除“未知用户”拥有的日期范围时导致错误的问题。(AN-185540)

### [!DNL Analytics] 管理员的重要注意事项 {#aa-notices}

| 注意 | 添加或更新日期 | 描述 |
| -----------| ---------- | ---------- |
| **[!UICONTROL 查看存档]**&#x200B;选项生命周期终止 | 2019 年 10 月 30 日 | 2020 年 1 月，将终止使用功能板管理器（**[!UICONTROL 组件 &gt; 功能板]**）中的&#x200B;**[!UICONTROL 查看存档]**&#x200B;选项。 |
| **[!UICONTROL 强制 IP 登录限制]**&#x200B;选项生命周期终止 | 2019 年 10 月 30 日 | 2020 年 1 月，将终止使用&#x200B;**[!UICONTROL 管理 &gt; 公司设置 &gt; 安全]**&#x200B;菜单下的 IP 登录白名单（**[!UICONTROL 强制 IP 登录限制]**）功能。 |
| 更新了对 Cookie 中的 SameSite 属性的处理 | 2019 年 10 月 15 日 | 2019 年 8 月，Adobe 宣布向由 Analytics 设置的所有 Cookie 中添加 SameSite Cookie 设置。在以下情况下，将应用逻辑中的更新：<ul><li>所有不基于 Webkit 的第三方 Cookie 的 SameSite 属性均设置为 `none`。</li><li>所有其他 Cookie 未设置 SameSite 属性。</li></ul> |
| 停止支持 TLS 1.1 | 2019 年 10 月 3 日 | 我们一直不懈努力，致力于维持最高安全标准并提升客户数据安全。为此，Adobe Analytics 对 TLS 1.1 的支持将持续到 2020 年 3 月 31 日，在这之后将不再支持 TLS 1.1。 |
| 圣何塞 FTP 中转站停止为伦敦和新加坡提供支持 | 2020 年 7 月 | 对于位于伦敦和新加坡的客户，我们将不再提供伦敦或新加坡与圣何塞数据中心 [ftp.omniture.com](ftp://ftp.omniture.com/) 之间的数据中转支持。<br/><ul><li>伦敦客户，请使用 [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>新加坡客户，请使用 [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li> |
| 更新 Analysis Workspace 自由格式表总数 | 2019 年 9 月 12 日 | 从 2019 年 10 月开始，自由格式表总数行在计算时，会将已应用的[报表过滤器](https://docs.adobe.com/content/help/zh-Hans/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html)考虑在内。迄今为止，总数仅计算的是分段数目。根据这项变化，作为从属的可视化图表（例如，链接的[!UICONTROL 概要数字]可视化图表）将会进行相应的更新，导出的 CSV 和 PDF 数据同样也会更新。 |
| 面向 Analytics 用户的 `createDate` 字段即将发生变化 | 2019 年 8 月 30 日 | 在 2019 年 10 月或 11 月，Analytics 用户的 `createDate` 字段将由美国太平洋时间更新为包含时区信息且格式正确的日期/时间值。(AN-183468) |
| 支持历史时区偏移 | 2019 年 8 月 8 日 | Analytics 现在将自动为带有时间戳的点击处理时区偏移。在 8 月 8 日实施此更改后，载入数据以进行历史处理的系统在发送数据之前将不再需要调整时区偏移。 |
| 分类规则生成器限制 | 添加于 2019 年 6 月 5 日 | 这些不是新限制，只是最近已添加到[此处](https://docs.adobe.com/content/help/zh-Hans/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html)的文档。 |
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

请参阅 [AppMeasurement for Javascript 发行说明](https://docs.adobe.com/content/help/zh-Hans/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html)。

## Audience Manager {#aam}

### Audience Manager 中的新增功能、增强功能和修复 {#aam-new-features}

| 功能 | 描述 |
|--- |----|
| [配置文件合并规则增强功能](https://docs.adobe.com/help/zh-Hans/audience-manager/user-guide/features/profile-merge-rules/merge-rules-overview.html) | 我们发布了针对[!UICONTROL 配置文件合并规则]的一系列增强功能： <ul><li>现在，最多支持对 100 个设备进行批量区段评估。</li><li>我们改进了特征和区段人口的报告准确性。</li><li>我们改进了使用跨设备 ID 生成的批处理文件的准确性。</li><li>我们更新了相关文档，以在其中包含每个规则的更详细使用案例。请参阅[配置文件合并规则通用使用案例](https://docs.adobe.com/help/zh-Hans/audience-manager/user-guide/features/profile-merge-rules/merge-rule-targeting-options.html)、[外部设备图形使用案例](https://docs.adobe.com/help/zh-Hans/audience-manager/user-guide/features/profile-merge-rules/external-graph-use-cases.html)以及[配置文件链接设备图形使用案例](https://docs.adobe.com/help/zh-Hans/audience-manager/user-guide/features/profile-merge-rules/profile-link-use-case.html)。</li></ul> |
| [由 Adobe Sensei 提供支持的 Audience Marketplace 数据智能推荐](https://docs.adobe.com/content/help/zh-Hans/audience-manager/user-guide/features/segments/trait-recommendations.html) | 现在，借助“特征推荐”，在[区段生成器](https://docs.adobe.com/content/help/zh-Hans/audience-manager/user-guide/features/segments/segment-builder.html)中构建或编辑区段时，您可以从未订阅的 [!UICONTROL Audience Marketplace] 数据馈送中获得关于可包含的其他特征的推荐。将推荐的特征添加到区段中，可增加目标受众。<br>此外，我们还重新设计了 [!UICONTROL Marketplace] 页面，使您能够更轻松地查找相似特征和过滤数据馈送。 |
| [批量管理工具](https://docs.adobe.com/content/help/zh-Hans/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html) | 我们发布了“批量管理”工作表的新版本，该工作表适用于 MacOS 和 Microsoft Windows 操作系统，并支持 Experience Cloud 登录。 |
| [HTTP Strict-Transport-Security](https://docs.adobe.com/help/zh-Hans/audience-manager/user-guide/overview/data-security-and-privacy/data-security.html#hsts) | 我们增加了对 [!DNL HTTP Strict-Transport-Security] 的支持，该 Web 安全策略可抵御 Cookie 劫持和协议降级攻击。 |

### 增强功能 {#aam-enhancements}

从 2019 年 11 月起，除之前支持的 Cookie、IDFA 和 GAID 设备 ID 外，Audience Manager 还支持将 Roku ID、Amazon Fire TV ID 和 Xbox/Microsoft ID 发送到 Google Ad Manager 和 DV360 目标。您无需更改现有 Google 集成中的任何内容。

在 Audience Manager 中，Roku ID、Amazon Fire TV ID 和 Xbox/Microsoft ID 称为全局设备 ID。您可以在 Audience Manager 产品文档中了解有关这些 ID 及其关联的数据源的更多信息：

* [全局设备 ID](https://docs.adobe.com/content/help/zh-Hans/audience-manager/user-guide/reference/ids-in-aam.html#global-device-ids)
* [全局数据源](https://docs.adobe.com/content/help/zh-Hans/audience-manager/user-guide/features/data-sources/global-data-sources.html)

Roku、Amazon Fire TV 和 Xbox/Microsoft 数据源的数据获取与 IDFA 和 GAID 具有相同的工作方式 - 在获取未与它们关联的数据时，会自动生成 Audience Manager ID 并将其链接到 DAID。新 ID 会自动发送到您帐户中配置的现有和新 Google 目标。

有关更多信息，请联系 Audience Manager 顾问或客户关怀。

### 修复和改进 {#aam-fixes-and-improvements}

* 我们修复了 Audience Marketplace 中的以下错误：当客户提交每月区段使用情况时，UI 会返回错误 409。(AAM-50825)
* 我们修复了“派生的信号”中的以下错误：客户在短时间内无法新建派生的信号。(AAM-50968)
* 我们修复了基于人员的目标中的以下错误：客户无法更改目标的名称。(AAM-51025)
* 我们修复了以下错误：一些用户使用重复的帐户登录到 Audience Manager UI。由于与重复帐户关联的权限，这些用户无法访问 UI 的某些部分和执行操作。(AAM-50818)
* 我们将继续改进 Audience Manager UI 的辅助功能。（AAM-48932、AAM-48997、AAM-49043、AAM-49054、AAM-49371、AAM-49375、AAM-51313）

## Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新增功能、修复和更新。Adobe 建议那些采用内部部署的客户部署最新的修补程序，以便确保获得更高的稳定性、安全性和性能。

### 产品版本

* **Brand Portal 6.4.5**

   Adobe Experience Manager Assets Brand Portal 6.4.5 是一个功能版本，旨在为 Brand Portal 用户（外部代理/团队）提供无需访问创作环境，即可将内容上传到 Brand Portal 和发布到 AEM Assets 的功能。此功能称为 [Brand Portal 中的资产来源](https://docs.adobe.com/content/help/zh-Hans/experience-manager-brand-portal/using/asset-sourcing-in-brand-portal/using-asset-sourcing/brand-portal-overiew-using-asset-sourcing.html)，它通过为用户提供双向机制来贡献资产并与其他分布在全球的 Brand Portal 用户共享资产，从而改善客户体验。

   请参阅 [AEM Assets Brand Portal 的新增功能](https://docs.adobe.com/content/help/zh-Hans/experience-manager-brand-portal/using/introduction/whats-new.html)。

   请参阅[发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)。

* **AEM Forms 自动转换服务**

   自动表单转换服务通过将 PDF 表单自动转换为自适应表单，帮助加快数据捕获体验的数字化和现代化进程。该服务由 Adobe Sensei 提供支持，可自动将您的 PDF 表单转换为设备友好型且基于 HTML5 的响应式自适应表单。在利用 PDF 表单和 XFA 中的现有设置的同时，该服务在转换过程中还会将适当的验证、样式和布局应用于自适应表单字段。

   请参阅 [Adobe Experience Manager Forms 自动转换服务](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/introduction.html)。

* **Cloud Manager 2019.10.0**

   Cloud Manager 2019.10.0 的通用“发行说明”现已发布。发行说明中还列出了对部署步骤和 Maven 项目版本处理的更新。

   请参阅 [Cloud Manager 2019.10.0 发行说明](https://docs.adobe.com/content/help/zh-Hans/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)。

### 自助服务

* **Activity Map**

   由于 Adobe Analytics API 中的安全性更改，无法再使用 AEM 中包含的 Activity Map 版本。请参阅[配置与 Adobe Analytics 的连接](https://helpx.adobe.com/cn/experience-manager/6-5/sites/administering/using/adobeanalytics-connect.html#ConfiguringtheConnectiontoAdobeAnalytics)。

   现在，您应使用 Adobe Analytics 提供的适用于 Chrome、Firefox 或 Internet Explorer 的 [Activity Map 浏览器插件](https://docs.adobe.com/content/help/zh-Hans/analytics/analyze/activity-map/getting-started/get-started-users/activitymap-install.html)。

* **AEM Screens 项目的最佳实践指南**

   新的 _AEM Screens 最佳实践指南_&#x200B;为您的数字标牌实施提供了详尽见解和实用建议，以便构想、设计和引入创意客户体验。该指南还将指导您在 AEM Screens 中部署数字标牌项目时，使用最佳实践对业务产生积极影响。

   请参阅 [AEM Screens 项目的最佳实践指南](https://docs.adobe.com/content/help/zh-Hans/experience-manager-screens/using/about-guide.html)。

* **无外设体验管理**

   现在，文档中介绍了用于在服务器端渲染单页应用程序的[远程内容渲染器](https://helpx.adobe.com/cn/experience-manager/6-5/sites/developing/using/spa-ssr.html#main-pars_header_450130848)功能。

* **SPA 和服务器端渲染**

   您可以根据自己的需求，扩展和自定义由 AEM 驱动的 SPA 用于服务器端渲染的远程内容渲染服务。

   请参阅 [SPA 和服务器端渲染](https://helpx.adobe.com/cn/experience-manager/6-5/sites/developing/using/spa-ssr.html#RemoteContentRenderer)。

* **AEM 项目原型**

   “AEM 项目原型”可创建基于最佳实践的最小 Adobe Experience Manager 项目，作为您自己的 AEM 项目的起点。使用此原型时必须提供的属性允许您指定此项目所有部分的名称，并控制特定可选功能。

   请参阅 [AEM 项目原型](https://docs.adobe.com/content/help/zh-Hans/experience-manager-core-components/using/developing/archetype/overview.html)。

* **AEM 文档更新**

   请阅读有关 Adobe Experience Manager 在最近三个月中的重要文档更改和更新。

   请参阅 [AEM 文档：近期文档更新](https://helpx.adobe.com/cn/experience-manager/documentation-updates.html)。

### 其他资源

* [AEM 6.5 学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-5.html)
* [AEM 6.4 学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-4.html)
* [AEM 6.3 学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-3.html)
* [AEM 6.2 学习和支持主页](https://helpx.adobe.com/cn/support/experience-manager/6-2.html)
* [Cloud Manager 用户指南](https://helpx.adobe.com/cn/experience-manager/cloud-manager/user-guide.html)
* [更早版本的 AEM 文档](https://helpx.adobe.com/cn/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic 帮助主页](https://docs.adobe.com/content/help/zh-Hans/dynamic-media-classic/using/home.html)
* [Dynamic Media 发行说明](https://marketing.adobe.com/resources/help/zh_CN/s7/release_notes/index.html)
* [Livefyre 发行说明](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign 提供了一种直观、自动的方式，以通过在线和离线营销渠道来交付一对一的消息。您现在可以利用根据客户习惯和喜好所决定的体验，来预测客户的需求。

### 文档资源

* Adobe Campaign Standard：[文档](https://helpx.adobe.com/cn/support/campaign/standard.html) - [发行说明](https://docs.adobe.com/content/help/zh-Hans/campaign-standard/using/release-notes/release-notes.html) - [操作方法视频](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [发行计划](https://helpx.adobe.com/cn/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic：[文档](https://helpx.adobe.com/cn/support/campaign/classic.html) - [发行说明](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [操作方法视频](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)

## Advertising Cloud {#adcloud}

更新日期：2019 年 11 月 8 日

| 视图 | 功能 |
|------|---------|
| 转化跟踪 | 基于 JavaScript 的 Advertising Cloud 转化映射标记现在支持跟踪来自 Mozilla Firefox 版本 69 及更高版本的点进次数，默认情况下会阻止第三方 Cookie。该标记已包含对 Apple Safari 的支持。<br><br/>如果您使用 Advertising Cloud 转化跟踪，但尚未部署 Advertising Cloud 转化映射标记，请在所有登陆页面上部署以下代码：<br></br>`<script src="//www.everestjs.net/static/amo-conversion-mapper.js"></script>`<br></br>注意：此标记支持 Advertising Cloud JavaScript v2 和 v3 转化跟踪标记，而不支持图像跟踪标记。 |
| 组合选项 | 现在，启用组合选项“启用促销活动最大支出 % 目标”后，从不会超出最大支出目标。以前，Advertising Cloud 在首选这样做时会超出最大支出目标。 |
| 搜索受众 | 位于“搜索”&gt;“受众”&gt;“库”中的受众库现在将自动包含“受众大小”列，该列每天从 Bing Ads 和 Google Ads 填充。您可以选择将该列用作数据过滤器。 |
| 与 Adobe Analytics 集成 | Analytics 现在包含适用于 Advertising Cloud DSP 促销活动的“登陆类型 (AMO ID)”维度。使用此维度可根据访客登陆网站的方式，对 Analytics 量度进行分段。值包括“点进”和“显示到达”。<br><br/>**注意：** 2019 年 10 月 31 日之前发生的显示到达数据将显示为点进数据。因此，我们建议在 2019 年 11 月中旬之前不要将此维度与数据结合使用。 |
