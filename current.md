---
title: Adobe Experience Cloud 发行说明
description: Experience Cloud 发行说明模板
doc-type: 发行说明
last-update: 2019年月
author: mfrei
translation-type: tm+mt
source-git-commit: 626b6b170539ebe54c86f17eec0593bd2decd4e5

---


# 抢先体验 - Adobe Experience Cloud 发行说明

Adobe Experience Cloud 的新增功能和修复。

>[!IMPORTANT]
>
>此页面包含预发行内容，在发行版之前可能会发生更改。

>[!NOTE]
>
>若要通过电子邮件接收关于即将发布版本的通知，请订阅 [Adobe 产品更新早知道](https://www.adobe.com/subscription/priority-product-update.html)。您将在版本发行前的三到五个工作日收到通知。对于发行之后发布的新信息，将使用发布日期进行标记。

**发行日期：2019 年 8 月**

* [体验平台和管理](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (链接到解决方案帮助)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (链接到解决方案帮助)

## [!UICONTROL 体验平台] 和管理 {#platform}

[!UICONTROL Experience Platform]、Experience Cloud界面、产品管理、Experience Platform Launch、Identity Service和安全公告的发行说明。

* [Experience Cloud 界面](#core-services)
* [Experience Platform Launch](#launch)
* [安全公告和通知](https://helpx.adobe.com/security.html)(所有Adobe产品)

### Experience Cloud 界面 {#core-services}

* 修复了Experience Cloud登录中导致某些用户退出会话的关键问题。(MCUI-6908)
* 更新了Experience Cloud登录，以提高性能并减少滞后时间。(MQUI-6854、MUI-6869、MQUI-6883)
* 界面已更新。(MUI-6861、MUI-6911、MQUI-6862)
* Fixed an issue with Experience Cloud [!UICONTROL Triggers] that led to incorrect interpretation of _Like_ clause in the [!UICONTROL Trigger] definition. (MCUI-6611)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

## [!DNL Analytics] {#analytics}

Adobe Analytics 的新增功能和修复：

* [Adobe Analytics中的新增功能、增强和修复](#aa-features)
* [Analytics 管理员的重要注意事项](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### New features, enhancements, and fixes in Adobe Analytics {#aa-features}

| 功能 | 描述 |
| -----------| ---------- |  
| 支持SaveSite cookie设置 | SaveSite cookie设置将被Analytics添加到所有cookies设置。此更改允许您符合需要SameSite cookie字段的Chrome更改。 |
| 工作区：将下拉过滤器的项限制提高50至200 | 我们增加了可放入从50到200的下拉过滤器中的项目限制。此增强功能适用于各种使用案例，例如将所有国家/地区(195)添加到过滤器，或所有美国州和省(52)。 |

#### 修复

* 修复了在全屏模式下时实时报告中显示文本的问题。(AN-183168)

### [!DNL Analytics] 管理员的重要注意事项{#aa-notices}

| 注意 | 添加或更新日期 | 描述 |
| -----------| ---------- | ---------- |
| 分类规则生成器限制 | 添加于 2019 年 6 月 5 日 | These limits are not new, but have been added to the documentation [here](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html). |
| 新的区段运算符限制 | 添加于 2019 年 5 月 31 日 | Starting on July 18, 2019, the segment operators _contains any of_, _does not contain any of_, _contains all of_ and _does not contain all_ of will be limited to 100 words per input field. 这项限制将适用于此日期之后的所有新增区段和修改区段。超出此限制的现有区段将继续受到支持，但在缩短输入字段前，将无法进行修改或保存。作为我们持续不断努力的一个组成部分，将应用这些限制以提高查询性能。 |
| 即将更改对 **[!UICONTROL 启用日期]** 和 **[!UICONTROL 数字 2 分类]**&#x200B;的支持 | 更新日期：2019 年 5 月 28 日 | 已从代码库中移除了导入数字 2 分类和启用日期的分类的功能。这项更改将随 2019 年 6 月维护版本的发布而生效。如果您的导入文件中包含“数字”或“启用日期”列，则这些单元格会被静默忽略，同时该文件中的任何其他数据均会正常导入。<br/>现有的分类仍可以通过标准分类工作流程导出，并将继续在报表中可用。 |
| 即将更改 _报表总数_ 计算 | 更新日期：2019 年 7 月 9 日 | 在 **2019 年 6 月 18 日**，Adobe Analytics 将以一致的方式处理所有维度和量度中的 _报表总数_ 计算。这将导致某些报表（通常为 Prop 或客户属性报表）的总数发生更改。在进行此项更改之前，无论 _未指定_ 是否显示在报表中，某些报表总数都会不一致地在总数中包含或排除 _未指定_ 行项目。<br/>自 2019 年 6 月 18 日开始， _未指定_ 将始终显示在报表总数中，即使它在报表中未显示为行项目也是如此。此外，进行此项更改之后，使用&#x200B;_存在_&#x200B;或&#x200B;_不存在_&#x200B;逻辑的区段，对于不同的维度可能会看到不同的结果，尤其是其中的&#x200B;_未指定_&#x200B;具有特殊名称（如推荐人类型维度的“已键入/已添加书签”行项目或设备类型维度的“其他”行项目）的维度。此更改将影响 Analysis Workspace、Reports &amp; Analytics、Ad Hoc Analysis、Report Builder 和报表 API。 |
| 更新从 [!DNL Analysis Workspace] 下载 CSV 时的操作 | 2019 年 4 月 10 日 | 从 2019 年 4 月 11 日开始，已对 [!DNL Analysis Workspace] 中的 **[!UICONTROL CSV 下载]** （和 **[!UICONTORL 复制到剪切板]**）进行了一些更改，以删除导出数据中的格式。  <ul><li>千位分隔符将不再包含在内。小数分隔符将继续包含在内，并将遵循 **[!UICONTROL 组件 &gt; 报表格式 &gt; 千位分隔符]**&#x200B;下定义的格式。注意：使用逗号作为小数分隔符的数值将会继续在导出的 CSV 中引用。</li><li>不会显示任何货币符号。</li><li>不会显示任何百分比符号。百分数将以小数形式显示。例如，75% 将表示为 0.75。</li><li>时间将以秒为单位显示。</li><li>同类群组表将只显示原始值；百分比将被删除。</li><li>如果数字无效，将显示空单元格。</li></ul> |
| 即将更改 [!DNL Analysis Workspace] 调试器命令 | 2019 年 4 月 4 日 | 自 **2019 年 6 月 13 日**&#x200B;起，用于开启 [!DNL Analysis Workspace] 调试器的控制台命令将变为 adobeTools.debug.includeOberonXml。adobe.tools.debug.includeOberonXml 命令将于该日期之后停止运行。 |
| 移动浏览器版本号 | 2019 年 2 月 7 日 | 从 2019 年 1 月 8 日开始，我们将移动浏览器版本号的截断级别从 2 更改为 1。在该日期之后，版本号将只显示前两个级别（例如 _Firefox 64.0.2_ 现在报告为 _Firefox 64.0_）。 |
| 终止 [!DNL Ad Hoc Analysis] 的生命周期 | 2019 年 1 月 29 日 | 2018 年 8 月 6 日，Adobe 宣布计划终止 [!DNL Ad Hoc Analysis] 的生命周期。确定终止日期后，Adobe 会立即与大家共享此信息。<br/>有关更多信息（包括在此期间将兼容的 Java 版本），请访问[探索工作区](https://adobe.ly/discoverworkspace)。 |
| 简短 [!DNL Analytics] 报表链接 | 2019 年 1 月 14 日 | 系统已从 2019 年 1 月 17 日星期四起开始按照滚动计划表清理和删除任何在一年内未被访问过的简短 [!DNL Analytics] 报表链接。 |
| 停止支持 TLS 1.0 | 更新日期：2019 年 1 月 10 日 | 自 2019 年 2 月 11 日起，Adobe Analytics 报表不再支持 TLS（传输层安全性）1.0 加密。这一更改体现了我们为维持最高安全标准和提升客户数据安全性所做的不懈努力。If you are unable to connect to Adobe Analytics reporting after February 11, 2019, you should upgrade your browser to the [latest version](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/server-side-forwarding/ssf-requirements.html).<br/>[!DNL Analytics]自 2019 年 2 月 20 日起，Adobe 数据收集不再支持 TLS 1.0。在实施此次更改后，如果最终用户使用不支持 TLS 1.1 或更高版本的旧设备或 Web 浏览器，Adobe 将不再从这些最终用户那里收集 Analytics 数据。我们希望这不会对客户数据或报表产生重大影响。（如果您的网站已不支持 TLS 1.0，则不会受到影响。）<br/>从 2019 年 4 月 11 日开始，Adobe Analytics 报表 API 不再支持 TLS 1.0 加密。访问该 API 的客户应当确认他们不会受到影响。 <ul><li>在默认设置下使用 Java 7 的 API 客户端将需要[做出修改才能支持 TLS 1.2](https://www.java.com/en/configure_crypto.html)。（请参阅&#x200B;_更改客户端端点的默认 TLS 协议版本：将 TLS 1.0 更改为 TLS 1.2_。） </li><li>使用 Java 8 的 API 客户端应该不会受到影响，因为其默认设置为 TLS 1.2。</li><li> 使用其他框架的 API 客户端，将需要联系各自的供应商来获取有关 TLS 1.2 支持的详细信息。</li></ul> |
| 数据馈送：post_product_list 列 - 大小更改 | 2019 年 1 月 9 日 | 2019 年 2 月 7 日，Adobe 将 post_product_list 列的大小从 64 KB 扩展到 16 MB。这项更改可确保在处理过程中添加到 post_product_list 的推销 eVar 值不会导致产品和收入值截断。如果您的流程需要提取 post_product_list 值，请确保这些流程可以处理长度最大为 16 MB 的值，否则系统将按照 16 KB 的长度将该值截断，以避免数据获取失败。 |
| 影响不活动的 [!DNL Analytics Live Stream] 端点的管理更改 | 2018 年 12 月 20 日 | 从 2019 年 2 月 1 日开始，可能会禁用持续 90 天没有活动客户连接的 [!DNL Live Stream] 端点。您可以联系客户关怀团队查询您的 [!DNL Live Stream] 端点，并在必要时重新启用它们。此外，请确保您的客户进程按照服务设计要求保持持久连接，并在连接断开或中断时实施重新连接。 |
| 由于对 TLS 1.0 的支持终止而更新 Adobe [!DNL Report Builder] | 2018 年 9 月 7 日 | 由于对 TLS 1.0 的支持即将终止，我们建议 [!DNL Report Builder] 用户在 2019 年 2 月之前下载 v5.6.21 版。在该日期之后，以前版本的 [!DNL Report Builder] 将无法再正常运行。 |

### AppMeasurement {#appm}

[!UICONTROL AppMeasurement] 2.16.0(2018年月日发行)。

| 功能 | 描述 |
| -----------| ---------- |
| `sendBeacon` 支持退出链接 | Implemented `sendBeacon` support in [!UICONTROL AppMeasurement] for exit links. 这将改进退出链接跟踪，并可能会增加流量。 |
| EID/fid值 | 即使optin设置更改，EID/fid值现在第一次点击时缓存。 |
| DIL 9.3 | 将受众管理模块更新到DIL9.3 |
| 滚动到达跟踪 | s. activityMap. trackScrollAccess中的暴露开关可打开或关闭滚动到达跟踪。 |
| 访客ID Service4.4.0 | 升级了AppMeasurement以使用访客ID Service4.4.0。 |

#### 修复

* 修复了在isReadyToTrack为true之前出现的AppMeasurement排队错误。

请参阅 [AppMeasurement 版本历史](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html)，了解下列平台上 AppMeasurement 的版本更新历史：

* JavaScript
* iOS
* Android
* Flash-Flex
* OSX
* Windows Phone、XBOX、Silverlight 和 .NET
* [!DNL BlackBerry]
* Java
* PHP
* Symbian

## Audience Manager {#aam}

**修复和改进功能**

* “管理”选项卡现在仅显示在具有管理权限的用户帐户中(AAM-48557)。
* List Users API现在返回完整的用户详细信息(AAM-48662)。
* 您现在可以调整特征文件夹列表的大小(AAM-48800)。
* 多个UI辅助功能优化(AAM-48865、AAM-48933)。
* 加载“管理”和“数据源”页面的优化(AAM-48514)。

## [!DNL Campaign] {#ac}

Adobe Campaign 提供了一种直观、自动的方式，以通过在线和离线营销渠道来交付一对一的消息。您现在可以利用根据客户习惯和喜好所决定的体验，来预测客户的需求。

### Adobe Campaign Standard

[Campaign Standard19.3版本](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html)

| 功能 | 描述 |
| -----------| ---------- |  
| 外部API活动(公共测试版) | 为实现更深入的个性化，外部API活动允许您通过REST API调用将外部系统中的数据引入工作流。REST端点可以是客户管理系统、Adobe I/Runtime或Adobe Experience Cloud REST端点(例如，Data Platform、Target、Analytics、Campaign)。此功能目前处于公共测试版中。For more information, refer to the [detailed documentation](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) and the [how-to video](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html). |
| 工作流区段报告 | 此功能允许营销人员按细分代码细分投放绩效。创建工作流并使用分段活动将区段分配给交付人群时，这些区段现在可以进入相同的交付。这允许您在单个分发中显示基于多个区段的打开/单击统计数据。For more information, refer to the [detailed documentation](https://docs.adobe.com/content/help/en/campaign-standard/using/reporting/customizing-reports/creating-a-report-workflow-segment.html) and the [how-to video](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/reporting/report-on-workflow-segments.html). |

### Adobe Campaign Classic

[Campaign Classic19.1.3更新](https://docs.campaign.adobe.com/doc/AC/en/RN.html) -构建9031

### Adobe Campaign控制面板

[新的控制面板功能](https://helpx.adobe.com/campaign/kb/control-panel-instance-settings.html) 包括添加Campaign Classic连接用于数据/文件传输的URL的功能。

Please note that [!UICONTROL Control Panel] is available for both Adobe Campaign Classic and Adobe Campaign Standard customers hosted on AWS. 访问控制面板无需升级。

### 其他资源

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)