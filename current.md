---
title: Adobe Experience Cloud 发行说明
description: 2019年月Experience Cloud发行说明
doc-type: 发行说明
last-update: 2019 年 7 月
author: mfrei
translation-type: tm+mt
source-git-commit: b4a91b853cfb5d228fc2195d65b4370e607475f2

---


# 抢先体验 - Adobe Experience Cloud 发行说明

Adobe Experience Cloud 的新增功能和修复。

>[!IMPORTANT]
>
>此页面包含预发行内容，在发行版之前可能会发生更改。

>[!NOTE]
>
>若要通过电子邮件接收关于即将发布版本的通知，请订阅 [Adobe 产品更新早知道](https://www.adobe.com/subscription/priority-product-update.html)。您将在版本发行前的三到五个工作日收到通知。对于发行之后发布的新信息，将使用发布日期进行标记。

**发行日期：2019 年 7 月 18 日**

* [Experience Cloud 核心服务和管理](#experiencecloud)
* [!DNL Analytics](#analytics)**(月15日更新)**
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [Target Standard/Premium 19.6.1](#target)
* [Magento](#magento)

## Core services and administration {#experiencecloud}

Experience Cloud 界面的发行说明，其中包括[!UICONTROL 平台]核心服务和产品管理。

* [Experience Cloud ID 服务](#ecid)
* [Mobile Services 和 Mobile SDK](#mobile)
* [Experience Platform Launch](#launch)
* [安全公告与建议](#security)

### Experience Cloud ID 服务 {#ecid}

**修复和更新**

* `cookieDomain` 配置更新：库将在未设置 `cookieDomain` 时 `initConfig` 自动分配顶级cookie域。(CORE-29223)
* Fixed an issue for `getVisitorValue` in `localVisitor`. (CORE-31287)
* Fixed an inconsistency of `MCOPTOUT` value in parent visitor versus iframe child visitor from `getVisitorValue` method. (CORE-29719)
* 修复了jQuery3.2.1中的漏洞问题。(CORE-31183)
* Opt-in update: added `optIn.off` to unsubscribe from events.
* Fixed an issue related to `setTimeout` function. (CORE-30623)

See [Experience Cloud ID Service](https://marketing.adobe.com/resources/help/en_US/mcvid/mcvid-release-notes.html) for cumulative release notes.

### Mobile Services 和 Mobile SDK {#mobile}

iOS和Android更新如下：

**iOS**

* Adobe Target: All requests now include the client and the `sessionId` in the URL query parameters.
* Adobe Target：修复了内存泄漏。
* Visitor ID Service: The `visitorAppendToURL` and `visitorGetUrlVariablesAsync` APIs no longer double-encode their return values. 双编码导致这些API中的返回值被某些安全审阅标记。

**Android**

* 目标：所有请求现在都包括客户端和URL查询参数中的sessionID。
* 应用程序内消息传递：修复了一个问题，该问题导致当消息用空点进URL触发时，Android应用程序崩溃。
* Visitor ID Service: The `Visitor.appendToURL` and `Visitor.getUrlVariablesAsync` APIs no longer double-encode their return values. 双编码导致这些API中的返回值被某些安全审阅标记。

有关产品文档，请参阅 [Mobile Services](https://docs.adobe.com/content/help/en/mobile-services/using/home.html)。

有关 Mobile SDK 的更多信息，请参阅[适用于 Experience Cloud 解决方案的 Android SDK 4.x ](https://docs.adobe.com/content/help/en/mobile-services/android/overview.html)和[适用于 Experience Cloud 解决方案的 iOS SDK 4.x](https://docs.adobe.com/content/help/en/mobile-services/ios/overview.html)。

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) (links to product help) for release notes and product documentation.

### Security bulletins and advisories {#security}

See [Security bulletins and advisories](https://helpx.adobe.com/security.html) for important information regarding security vulnerabilities that could affect specific versions of Adobe products.

## [!DNL Analytics] {#analytics}

* [Adobe Analytics中的新增功能和修复](#aa-features)**(月15日更新)**
* [Analytics 管理员的重要注意事项](#aa-notices)

###  中的新功能：[!DNL Analytics]{#aa-features}

有关产品文档，请参阅 [Analytics 帮助主页](https://docs.adobe.com/content/help/en/analytics/landing/home.html)。

| 组件 | 描述 |
| -----------| ---------- |   
| Analysis Workspace-群组分析增强功能 | 新增了“群组分析”设置： <ul><li>仅显示%</li><li>四舍五入到最近的整个整数</li><li>在顶部显示平均行</li></ul> |
| Analysis Workspace | In the left rail, users now have the option to _Show items from last 18 months_. 以前，查看期最长为个月。这样，您可以比18个月前的最后一年中的页面或营销活动更轻松地进行比较。 |
| 新的Analysis Workspace模板 | 我们添加了一个名为“杂志：营销和商务”到Analysis Workspace。它专为杂志电子商务客户设计，但任何零售商都可使用它获得有关其商务活动的独特洞察。 |

#### [!DNL Analysis Workspace] 修复

* 修复了在划分尺寸时导致多字节字符向下显示的问题。(AN-180112)
* 修复了可视化错误的问题-当出现可视化错误时，我们现在显示红色错误栏。(AN-175542)
* 修复了在本地化环境中维度名称显示为英语的问题。(AN-178695)

#### [!DNL Analytics] 修复

* 修复了导致实时向下钻取报告中折线图为空的问题。(AN-181690)
* 修复了在某些情况下，数据馈送历史记录的部分未在Admin Console UI中显示的问题。(AN-176219)

### [!DNL Analytics] 管理员的重要注意事项{#aa-notices}

| 注意 | 添加或更新日期 | 描述 |
| -----------| ---------- | ---------- |
| 分类规则生成器限制 | 添加于 2019 年 6 月 5 日 | These limits are not new, but have been added to the documentation [here](https://marketing.adobe.com/resources/help/en_US/reference/classification_rule_builder.html). |
| 新的区段运算符限制 | 添加于 2019 年 5 月 31 日 | 从 2019 年 7 月 18 日开始，区段运算符“包含任意”、“不包含任意”、“包含全部”和“不包含全部”将限制为每个输入字段 100 个词。这项限制将适用于此日期之后的所有新增区段和修改区段。超出此限制的现有区段将继续受到支持，但在缩短输入字段前，将无法进行修改或保存。作为我们持续不断努力的一个组成部分，将应用这些限制以提高查询性能。 |
| 即将更改对 **[!UICONTROL 启用日期]** 和 **[!UICONTROL 数字 2 分类]** 的支持 | 更新日期：2019 年 5 月 28 日 | 已从代码库中移除了导入数字 2 分类和启用日期的分类的功能。这项更改将随 2019 年 6 月维护版本的发布而生效。如果您的导入文件中包含“数字”或“启用日期”列，则这些单元格会被静默忽略，同时该文件中的任何其他数据均会正常导入。<br/>现有的分类仍可以通过标准分类工作流程导出，并将继续在报表中可用。 |
| 即将更改 _报表总数_ 计算 | 更新日期：2019年月日 | 在 **2019 年 6 月 18 日**，Adobe Analytics 将以一致的方式处理所有维度和量度中的 _报表总数_ 计算。这将导致某些报表（通常为 Prop 或客户属性报表）的总数发生更改。在进行此项更改之前，无论 _未指定_ 是否显示在报表中，某些报表总数都会不一致地在总数中包含或排除 _未指定_ 行项目。<br/>自 2019 年 6 月 18 日开始， _未指定_ 将始终显示在报表总数中，即使它在报表中未显示为行项目也是如此。Additionally, segments using _exists_ or _does not exist_ logic may see different results for some dimensions after this change, specifically dimensions where _Unspecified_ has a special name such as the &quot;Typed/Bookmarked&quot; line item for Referrer Type dimension or the &quot;Other&quot; line item for the Device Type dimension. 此更改将影响 Analysis Workspace、Reports &amp; Analytics、Ad Hoc Analysis、Report Builder 和报表 API。 |
| 更新从 [!DNL Analysis Workspace] 下载 CSV 时的操作 | 2019 年 4 月 10 日 | 从 2019 年 4 月 11 日开始，已对 [!DNL Analysis Workspace] 中的 **[!UICONTROL CSV 下载]** （和 **[!UICONTORL 复制到剪切板]**）进行了一些更改，以删除导出数据中的格式。  <ul><li>千位分隔符将不再包含在内。小数分隔符将继续包含在内，并将遵循 **[!UICONTROL 组件 &gt; 报表格式 &gt; 千位分隔符]** 下定义的格式。注意：使用逗号作为小数分隔符的数值将会继续在导出的 CSV 中引用。</li><li>不会显示任何货币符号。</li><li>不会显示任何百分比符号。百分数将以小数形式显示。例如，75% 将表示为 0.75。</li><li>时间将以秒为单位显示。</li><li>同类群组表将只显示原始值；百分比将被删除。</li><li>如果数字无效，将显示空单元格。</li></ul> |
| 即将更改 [!DNL Analysis Workspace] 调试器命令 | 2019 年 4 月 4 日 | 自 **2019 年 6 月 13 日** 起，用于开启 [!DNL Analysis Workspace] 调试器的控制台命令将变为 adobeTools.debug.includeOberonXml。adobe.tools.debug.includeOberonXml 命令将于该日期之后停止运行。 |
| 移动浏览器版本号 | 2019 年 2 月 7 日 | 从 2019 年 1 月 8 日开始，我们将移动浏览器版本号的截断级别从 2 更改为 1。在该日期之后，版本号将只显示前两个级别（例如 _Firefox 64.0.2_ 现在报告为 _Firefox 64.0_）。 |
| 终止 [!DNL Ad Hoc Analysis] 的生命周期 | 2019 年 1 月 29 日 | 2018 年 8 月 6 日，Adobe 宣布计划终止 [!DNL Ad Hoc Analysis] 的生命周期。确定终止日期后，Adobe 会立即与大家共享此信息。<br/>有关更多信息（包括在此期间将兼容的 Java 版本），请访问[探索工作区](https://adobe.ly/discoverworkspace)。 |
| Short [!DNL Analytics] report links | 2019 年 1 月 14 日 | Any short [!DNL Analytics] report links that have not been visited within one year will be cleaned up and deleted starting on Thursday, January 17, 2019, on a rolling schedule. |
| 停止支持 TLS 1.0 | 更新日期：2019 年 1 月 10 日 | 自 2019 年 2 月 11 日起，Adobe Analytics 报表不再支持 TLS（传输层安全性）1.0 加密。这一更改体现了我们为维持最高安全标准和提升客户数据安全性所做的不懈努力。If you are unable to connect to Adobe Analytics reporting after February 11, 2019, you should upgrade your browser to the [latest version](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html).<br/>[!DNL Analytics]自 2019 年 2 月 20 日起，Adobe 数据收集不再支持 TLS 1.0。在实施此次更改后，如果最终用户使用不支持 TLS 1.1 或更高版本的旧设备或 Web 浏览器，Adobe 将不再从这些最终用户那里收集 Analytics 数据。我们希望这不会对客户数据或报表产生重大影响。（如果您的网站已不支持 TLS 1.0，则不会受到影响。）<br/>从 2019 年 4 月 11 日开始，Adobe Analytics 报表 API 不再支持 TLS 1.0 加密。访问该 API 的客户应当确认他们不会受到影响。 <ul><li>在默认设置下使用 Java 7 的 API 客户端将需要[做出修改才能支持 TLS 1.2](https://www.java.com/en/configure_crypto.html)。（请参阅 _更改客户端端点的默认 TLS 协议版本：将 TLS 1.0 更改为 TLS 1.2_。） </li><li>使用 Java 8 的 API 客户端应该不会受到影响，因为其默认设置为 TLS 1.2。</li><li> 使用其他框架的 API 客户端，将需要联系各自的供应商来获取有关 TLS 1.2 支持的详细信息。</li></ul> |
| 数据馈送：post_product_list 列 - 大小更改 | 2019 年 1 月 9 日 | 2019 年 2 月 7 日，Adobe 将 post_product_list 列的大小从 64 KB 扩展到 16 MB。这项更改可确保在处理过程中添加到 post_product_list 的推销 eVar 值不会导致产品和收入值截断。如果您的流程需要提取 post_product_list 值，请确保这些流程可以处理长度最大为 16 MB 的值，否则系统将按照 16 KB 的长度将该值截断，以避免数据获取失败。 |
| 影响不活动的 [!DNL Analytics Live Stream] 端点的管理更改 | 2018 年 12 月 20 日 | 从 2019 年 2 月 1 日开始，可能会禁用持续 90 天没有活动客户连接的 [!DNL Live Stream] 端点。您可以联系客户关怀团队查询您的 [!DNL Live Stream] 端点，并在必要时重新启用它们。此外，请确保您的客户进程按照服务设计要求保持持久连接，并在连接断开或中断时实施重新连接。 |
| 由于对 TLS 1.0 的支持终止而更新 Adobe [!DNL Report Builder] | 2018 年 9 月 7 日 | 由于对 TLS 1.0 的支持即将终止，我们建议 [!DNL Report Builder] 用户在 2019 年 2 月之前下载 v5.6.21 版。在该日期之后，以前版本的 [!DNL Report Builder] 将无法再正常运行。 |

### AppMeasurement {#appm}

发布日期：2019年月15日

**JavaScript 2.15.0**

* 将DIL7.2添加到AppMeasuremMet。(AN-175142)
* 修复了Experience Cloud ID Service optin设置为true且未在s. t()调用上生成MID而无需重新加载页面的问题。(CORE-30890)

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

### Data Workbench {#aa-dwb}

* Updated the help definition for [log (X, B)](https://marketing.adobe.com/resources/help/en_US/insight/client/c_syntx_mtrc_exp.html) metric syntax documentation. (AN-180527)

请参阅 [Data Workbench 发行说明](https://marketing.adobe.com/resources/help/en_US/insight/whatsnew/)，以了解最新信息。

## Audience Manager {#aam}

**修复和增强功能**

* [!UICONTROL 在区段概述] 页面上，区段存储文件夹的宽度现在是灵活的。这允许您区分具有较长名称的区段。(AAM-48400)
* Fixed an issue in [!UICONTROL Algorithmic Models], where moving the **Adjust Reach &amp; Accuracy** slider did not affect the model&#39;s reach or accuracy. (AAM-47996)
* 修复了Analytics目标中的一个问题，该问题导致按钮下载与数据导出控件和/或第三方数据共享策略冲突的区段的. csv文件已断开。(AAM-48100)
* 修复了客户在登录Audience Manager用户界面时看到随机“访问被拒绝”错误的问题。(AAM-47632)

## Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新增功能、修复和更新。Adobe 建议那些采用内部部署的客户部署最新的修补程序，以便确保获得更高的稳定性、安全性和性能。

### 产品版本

以下产品的新增功能信息：

#### Cloud Manager 2019.6.0

The latest Cloud Manager release (2019.6.0) contains a new [Product Update Wizard](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/product-update-wizard/overview-productupdate-wizard.html) to help customers successfully run an AEM update.

* [Cloud Manager 2019.6.0 发行说明](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

#### XML文档3.4

XML文档3.4解决方案现已可用。

***发行说明***

* 为AEM6.5添加了支持。
* 编辑器更改：
   * 地图级别预览。
   * Tables - provided an option to copy an `entry` or a `complete` row within a table using copy and paste.
   * 表-提供一个选项，用于选择列中的多个单元格，并将它们合并或合并。
   * 表-提供了一种在Web编辑器的创作模式下设置表列属性的方法。
   * 表-提供了一种在标准表中调整列比例和大小的方法。
   * 表-在“作者”视图中选择行和列。
   * 表-在Web编辑器中启用样式和属性(对齐、valign)以进行表单元格对齐。
   * 对完整标记视图进行错误修复，包括复制和粘贴和拖放内容的场景。
   * 在编辑器选项卡中显示主题标题。
   * 解决了Web编辑器中的性能问题。
* 翻译过程中将基线传输到译文内容。
* 翻译工作流程期间的传输条件预设。
* 添加了将标签应用于基线的所有依赖项的功能。
* 提供一个按钮，以下载包含所有依赖项的地图作为zip。
* 对以下内容进行XHTML转换改进：
   * 生成的DIAMAP名称现在与上传的zip文件的名称相同。
   * 增加了对其他HTML元素和属性的支持。
   * 支持并发html-zip文件摄取。
   * The sub-folder hierarchy where the zip is uploaded (*under input path as configured in h2d_io.xml*), is retained for the generated output (*under the configured output path*).
* 提供审核日志以查看哪些用户还原到版本以及原因。
* AEM站点重新生成：
   * 禁用子映射的重新生成。
   * 支持生成使用案例的后期生成工作流程。
   * 为分块主题禁用重新生成选项，并使选项可用于应用分块属性的父主题。
* DITA搜索现在适用于AEM资产搜索中的AND逻辑。
* 结果不会显示存储在翻译输出文件夹中的临时文件。
* 基线选项卡：
   * 打开基准时的性能改进。
   * 在客户端时间戳上按日期选择主题。
* 用于删除标签的API。

#### 产品维护

**AEM 6.2 SP1-CFP20**

AEM6.2Service Pack-累积修复包20(6.2.1.20)(发布于2019年月日)是一个重要更新，其中包括自2016年12月日AEM6.2SP1212月日发布以来发布的主要客户修复。

* [发行说明](https://helpx.adobe.com/experience-manager/release-notes--aem-6-2-cumulative-fix-pack.html)
* [AEM 表单 CFP 版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.3.3.5**

AEM6.3.3.5发布于2019年7月3日，它是一个重要更新，其中包括自2017年月日AEM6.3年月发布以来发布的主要客户修复。

* [发行说明](https://helpx.adobe.com/experience-manager/6-3/release-notes/sp3-release-notes.html)
* [AEM 表单 CFP 版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.4.5.0**

AEM6.4.5.0(发布于2019年7月3日)是一项重要更新，其中包含自2018年月AEM6.4一般可用性以来发布的主要客户修复。

* [发行说明](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
* [AEM 表单 CFP 版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.5.1.0**

AEM6.5.1.0(发布于2019年7月3日)是一项重要更新，其中包括自2019年月发布AEM6.5以来发布的主要客户修复。

* [发行说明](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
* [AEM 表单 CFP 版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

### 自助

**AEM缓存失效更新**

[AEM6.5.1.0更新](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html) 或此 [知识库文章可提供AEM6.5clientlibs缓存失效初始化的重要AEM修补](https://helpx.adobe.com/experience-manager/kb/avoid-crx-quickstart-deletion-in-aem-6-5.html)程序。

### 其他资源

* [AEM 6.5 学习和支持主页](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 学习与支持主页](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 学习与支持主页](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 学习与支持主页](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager 用户指南](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [更早版本的 AEM 文档](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Scene7 发布系统发行说明](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre 发行说明](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign 提供了一种直观、自动的方式，以通过在线和离线营销渠道来交付一对一的消息。您现在可以利用根据客户习惯和喜好所决定的体验，来预测客户的需求。

有关发行说明，请参阅：

* Adobe Campaign Classic [19.1.2](https://docs.campaign.adobe.com/doc/AC/en/RN.html) – build 9029
* Adobe Campaign Standard [19.2.3](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-3---june-2019)
* Adobe Campaign Standard [19.2.4](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-4---june-2019)
* Adobe Campaign Standard [19.2.7](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-7---july-2019)

有关产品文档，请参阅：

* Adobe Campaign Standard：[文档](https://helpx.adobe.com/support/campaign/standard.html) - [发行说明](https://helpx.adobe.com/campaign/standard/rn/using/release-notes.html) - [专题视频](https://helpx.adobe.com/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic：[文档](https://helpx.adobe.com/support/campaign/classic.html) - [发行说明](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [专题视频](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html)

## [!DNL Target] {#target}

See [Target release notes (pre-release)](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) for the latest release infomration about Target.

## Magento {#magento}

有关Magento Commerce和Magento Open Source发行说明的信息，请参阅：

* [Magento Open Source2.3.2发行说明](https://devdocs.magento.com/guides/v2.3/release-notes/ReleaseNotes2.3.2OpenSource.html)
* [Magento Commerce2.3.2发行说明](https://devdocs.magento.com/guides/v2.3/release-notes/ReleaseNotes2.3.2Commerce.html)
