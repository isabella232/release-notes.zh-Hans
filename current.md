---
title: Adobe Experience Cloud 发行说明
description: Experience Cloud 发行说明模板
doc-type: 发行说明
last-update: 2019 年 10 月 日
author: mfrei
translation-type: tm+mt
source-git-commit: 42a453578bc4ce826306b93f893bec47c84329a5

---


# 早期访问- Experience cloud发行说明- 2019年10月

Adobe Experience Cloud 的新增功能和修复。

>[!IMPORTANT]
>
>此页面包含预发行内容，在发行版之前可能会发生更改。

>[!NOTE]
>
>Subscribe to the [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. 对于发行之后发布的新信息，将使用发布日期进行标记。

## 发行日期：2019 年 10 月 10 日

<!-- * [Experience Cloud interface](#ecloud) -->
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) （解决方案帮助的链接）
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) （解决方案帮助的链接）

<!-- ## Experience Cloud interface {#ecloud}

Release notes for Experience Cloud interface and product administration.

* Fixed a security vulnerability to include recommended HTTP headers. (MCUI-9942)
* Fixed an issue in switching between Analytics login companies. (MCUI-10049)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html). -->

## Experience Platform {#platform}

Experience Platform、Experience Platform Launch、Identity Service 和安全公告的发行说明。

* [Experience Platform Launch](#launch)
* [安全公告和通知](https://helpx.adobe.com/security.html) （所有Adobe产品）

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

## [!DNL Analytics] {#analytics}

Adobe Analytics 中的新增功能和修复：

* [Adobe Analytics 中的新增功能、增强功能和修复](#aa-features)
* [Analytics 管理员的重要注意事项](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Adobe Analytics 中的新增功能、增强功能和修复 {#aa-features}

| 功能 | 描述 |
| -----------| ---------- |  
| 隐私服务API:CCPA | 加利福尼亚消费者隐私法(CCPA)增强了美国加利福尼亚州居民的隐私权和消费者保护。 本法定于2020年1月1日生效。<br/><br/>CCPA为加利福尼亚州居民提供了新的数据隐私权，如访问和删除其个人数据、了解其个人数据是被出售还是被披露（以及向谁）以及拒绝销售其个人数据的权利。<br/><br/>根据CCPA的预期，隐私服务将支持拒绝销售个人数据的请求。<br/><br/>隐私服务以前称为GDPR服务，并保留了之前的所有功能，现在扩展为支持CCPA。<br/><br/>[Analytics隐私服务](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/an-ccpa-overview.html)<br/><br/>[概述中的CCPA](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |
| 隐私报告：Analytics Admin Console | 为Analytics启用隐私报告功能可向报表包添加一组保留变量。  这些变量设计为有助于在点击级别收集消费者同意数据。<br/><br/>新维度：<br/><ul><li>同意管理选择退出</li><li>同意管理选择加入</li><li>[同意管理变量](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/consent-variables.html)</li></ul> |
| 音频和视频分析：隐私支持 | Media Collection API中新增了两个变量：<br/><ul><li>analytics.optOutServerSideForwarding</li><li>analytics.optOutShare</li></ul><br/><br/>这些是可选变量，可用于捕获点击时消费者同意的状态。<br/><br/>[Media Collection API文](https://docs.adobe.com/content/help/en/media-analytics/using/media-collection-api/mc-api-overview.html)<br/><br/>档新的Analytics Concent Management上下文数据变量已添加到Federated Analytics表单中。 这些变量现在可用于标记联盟的“选择退出共享”或“销售”点击。<br/><br/>[下载Federated Form](https://docs.adobe.com/content/help/en/media-analytics/using/federated-analytics.html#download-the-federated-analytics-form) |
| Analysis Workspace:更新到自由格式表总计 | 自由格式表现在包括两个总 **[!UICONTROL 计，一个]** “表” **[!UICONTROL 和一个“总计”]**。 已应用报告过滤器的“表 [”总行](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) 。 以前，仅受细分影响的总计。 [了](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/workspace-totals.html)<br/>解更多此 **[!UICONTROL 外，“显]** 示总计”和“显 **[!UICONTROL 示总计]** ”选项已添加到“列 **[!UICONTROL 设置”中]**。<br/>对自由形式总计进行此更改后，将更新相关可视化(例如，链接的 **[!UICONTROL 摘要编号可视化]** )以及导出的CSV和PDF数据。 |
| Analysis Workspace:用于删除“未指定”/“无”的选项 | 轻松删除“未指定（无）”的功能已添加为报告过滤器的选项。 |
| Analysis Workspace:弃用紫色粒度组件 | 已弃用紫色粒度时间组件（分钟、小时、日、周、月、季度、年）。 紫色时间组件的行为一直与橙色尺寸组件完全相同，因此此更改将简化体验。 **如果您之前使用** 紫色时间组件之一，则无需执行任何操作。<br/>通过此更改，紫色 **[!UICONTROL 时间]** (Time)部分也已更名为 **[!UICONTROL 日期范围]**。 |

#### 修复

* Analysis Workspace:修复了在左边栏中搜索维项目时导致搜索结果错误的问题。 (AN-185065)
* 修复了在Adobe Audience Manager(AAM)中无法删除或取消发布共享区段的问题。 如果AAM无响应，则修复不删除段。 (AN-185882、AN-185883、AN-184607)
* 修复了在临时分析中无法加载区段的超时问题。 (AN-184654)
* 修复了您上次使用的报表包随后被隐藏或您不再具有访问此报表包的权限时出现的问题。 在这种情况下，您无法再通过Experience cloud登录。 (AN-181777)
* 修复了区段中的超时问题，该问题导致难以基于区段创建VRS。 (AN-179684)
* 修复了在少数情况下，如果编码不正确，数据会被截断的问题。 (AN-186707)
* Yandex搜索引擎现在按国家／地区正确分类。 (AN-181728)

### [!DNL Analytics] 管理员的重要注意事项 {#aa-notices}

| 注意 | 添加或更新日期 | 描述 |
| -----------| ---------- | ---------- |
| 停止支持 TLS 1.1 | 2019 年 10 月 3 日 | 到2020年3月31日，Adobe Analytics将删除对TLS 1.1的支持。这一变化是我们不断努力维护最高安全标准并促进客户数据安全的一部分。 |
| 圣何塞FTP经纪人结束伦敦和新加坡 | 2020 年 7 月 | 对于伦敦和新加坡的客户，我们将不再支持伦敦或新加坡与圣何塞数据中心 [ftp.omniture.com之间的数据代理](ftp://ftp.omniture.com/)。<br/><ul><li>对于伦敦， [请使用ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>对于新加坡， [请使用ftp4.omniture.com](ftp://ftp4.omniture.com/)</li> |
| 更新 Analysis Workspace 自由格式表总数 | 2019 年 9 月 12 日 | 在2019年10月，自由格式表总行数将开始计入所应用的报 [表过滤器](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) 。 迄今为止，总数仅计算的是分段数目。根据这项变化，作为从属的可视化图表（例如，链接的[!UICONTROL 概要数字]可视化图表）将会进行相应的更新，导出的 CSV 和 PDF 数据同样也会更新。 |
| 面向 Analytics 用户的 `createDate` 字段即将发生变化 | 2019 年 8 月 30 日 | 在 2019 年 10 月或 11 月，Analytics 用户的 `createDate` 字段将由美国太平洋时间更新为包含时区信息且格式正确的日期/时间值。(AN-183468) |
| 支持历史时区偏移 | 2019 年 8 月 8 日 | Analytics 现在将自动为带有时间戳的点击处理时区偏移。在 8 月 8 日实施此更改后，载入数据以进行历史处理的系统在发送数据之前将不再需要调整时区偏移。 |
| 分类规则生成器限制 | 添加于 2019 年 6 月 5 日 | These limits are not new, but have been added to the documentation [here](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html). |
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

请参 [阅AppMeasurement for Javascript发行说明](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html)。

## Audience Manager {#aam}

Audience Manager 中的新增功能、增强功能和修复。

**修复和改进**

* 在2019年7月1日之后创建的所有客户帐户将自动获得一个许 [!DNL Tableau] 可证，允许他们访问其报告。 如果您的帐户是在2019年7月1日之前创建的，并且您仍无权访问报告，请 [!DNL Tableau] 联系客户关怀。
* 我们修复了一个错误，该错误导致生成错误的活动特征并人为地提高匹配率和受众规模。 在此修复之后，您可能会注意到使用自动生成的活动特征创建的区段的大小有所减小。 这是正常的预期行为(AAM-45371)。
* 我们从全局数据源中删除了无效的全局设备ID。 请参 [阅全局数据源](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/data-sources/global-data-sources.html) ，了解Audience Manager应接受哪些有效设备ID(AAM-41259)。
* 修复了在尝试删除受保护的区段时导致“区段”页面停止响应的错误(AAM-49881)。
* 编辑Twitter定制受众的目标时， [!UICONTROL “帐户] ”选择器现在仅在目标未分配帐户时 [!DNL Twitter Ads] 处于活动状态(AAM-49975)。
* 修复了在禁用订阅时阻止用 [!UICONTROL 户禁用Audience Marketplace] 数据源的错误(AAM-49640)。
* 我们执行了一些与 Audience Manager 用户界面辅助功能有关的改进。

## Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新增功能、修复和更新。Adobe 建议那些采用内部部署的客户部署最新的修补程序，以便确保获得更高的稳定性、安全性和性能。

### 产品版本

* **Cloud Manager 2019.9.0**

   * 2019年9月12日发布的Cloud Manager 2019.9.0更新了安全测试标准，添加了可下载的监控图形，并修复了客户报告的一些可用性问题。
   * [发行说明](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

### 产品维护

* **AEM 6.3.3.6**

   AEM 6.3、Service Pack 3、Cumulative Fix Pack 6（2019年9月25日发布的6.3.3.6）是一项重要更新，其中包括自2017年4月AEM 6.3通用版本发布以来发布的关键客户修复。
   * [发行说明](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [AEM 表单 CFP 版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.6.0**

   AEM 6.4,Service Pack 6.0（2019年9月19日发布）是一个重要更新，其中包括自2018年4月AEM 6.4正式发布以来发布的关键客户修复。
   * [发行说明](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [AEM 表单 CFP 版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.5.2.0** AEM 6.5,Service Pack 2.0（2019年9月19日发布）是一项重要更新，其中包括自2019年4月AEM 6.5正式发布以来发布的关键客户修复。
   * [发行说明](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [AEM 表单 CFP 版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

### 自助

* **Scene7:重新处理资产工作流**

   您现在可以重新处理文件夹中的资产，该文件夹中已有您稍后更改的现有处理配置文件。
请参 [阅在编辑文件夹的处理配置文件后重新处理文件夹中的资产](https://helpx.adobe.com/experience-manager/6-5/assets/using/processing-profiles.html#Reprocessingassetsinafolderafteryouhaveediteditsprocessingprofile)。

* **Dynamic Media Viewer与Adobe Analytics和Adobe Launch的集成**

   Adobe Launch的Dynamic Media Viewers扩展以及Dynamic Media Viewer 5.13的发布使Dynamic Media、Adobe Analytics和Adobe Launch的客户能够在其Adobe Launch配置中使用特定于Dynamic Media查看器的事件和数据。
请参 [阅将Dynamic Media Viewer与Adobe Analytics和Adobe Launch集成](https://helpx.adobe.com/experience-manager/6-5/assets/using/launch.html)。

* **AEM桌面应用程序**

   AEM桌面应用程序2.0现在可供创意人员、营销人员和业务线用户使用，以便与AEM资产结合使用。
请参阅 [AEM桌面应用程序发行说明。](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/release-notes.html)

* **核心组件**
   * 了解核心组件的本地化功能及其如何使用AEM模板。
      [请参阅示例](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/get-started/localization.html)。
   * 核心组件2.6.0引入了体验片段组件。 该组件现在可用，还有创作文 [档](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/introduction.html) 、开 [发人员详细信息以及GitHub上提供的项目下载](https://github.com/adobe/aem-core-wcm-components)。

* **AEM Assets**
   * 有关视觉／相似性搜索功能的新文档。
请参 [阅查找类似图像](https://helpx.adobe.com/experience-manager/6-5/assets/using/search-assets.html#visualsearch)。
   * 除了图像文件格式外，连接的资产功能现在还使用远程DAM部署中可用的文档。
请参 [阅使用已连接的资产在AEM站点中共享DAM资产](https://helpx.adobe.com/experience-manager/6-5/assets/using/use-assets-across-connected-assets-instances.html)。
   * 有关资产搜索和发现的最新内容。 AEM __ 中的搜索资产主题是一站式商店，以了解有关使用、配置、疑难解答、限制和提示的信息。
请参阅 [在AEM中搜索资产](https://helpx.adobe.com/experience-manager/6-5/assets/using/search-assets.html)。

### 其他资源

* [AEM 6.5 学习和支持主页](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 学习和支持主页](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 学习和支持主页](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 学习和支持主页](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager 用户指南](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [旧版AEM文档](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic帮助主页](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Dynamic Media 发行说明](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre 发行说明](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign 提供了一种直观、自动的方式，以通过在线和离线营销渠道来交付一对一的消息。您现在可以利用根据客户习惯和喜好所决定的体验，来预测客户的需求。

### Adobe Campaign Classic

* [Campaign Classic 19.1.4更新](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9032) -内部版本9032
* [Campaign Classic 19.1.6更新](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html#release-19-1-6-build-9035) -内部版本9035

### 其他资源

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
