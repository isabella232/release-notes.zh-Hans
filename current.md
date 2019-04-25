---
title: Adobe Experience Cloud 发行说明
description: Experience Cloud发行说明
doc-type: 发行说明
last-update: 2019 年 4 月
author: mfrei
translation-type: tm+mt
source-git-commit: 147b01562e6c8d579a2bec0e4fa2841d1791a671

---


# Adobe Experience Cloud发行说明

Adobe Experience Cloud 的新增功能和修复。

>[!NOTE]
>若要通过电子邮件接收关于即将发布版本的通知，请订阅 [Adobe 产品更新早知道](https://www.adobe.com/subscription/priority-product-update.html)。您将在版本发行前的三到五个工作日收到通知。对于发行之后发布的新信息，将使用发布日期进行标记。

**发布日期：2019年月**

* [Experience Cloud核心服务和管理](#experiencecloud)
* [Analytics](#analytics)
* [Audience Manager](#aam)
* [Advertising Cloud](#adcloud)
* [Target](#target)
* [Experience Manager](#aem)
* [Primetime](https://helpx.adobe.com/primetime/user-guide.html) (指向解决方案帮助的链接)

## Experience Cloud核心服务和管理 {#experiencecloud}

Experience Cloud界面的发行说明，包括 [!UICONTROL 平台] 核心服务和产品管理。

* [Experience Cloud核心服务](#core-services)
* [Experience Cloud ID 服务](#ecid)
* [Mobile Services和Mobile SDK](#mobile)
* [Launch，by Adobe](https://docs.adobelaunch.com/) (链接到产品帮助)

### Experience Cloud核心服务 {#core-services}

Experience Cloud 界面和核心服务的发行说明。

* 更新了应用程序切换器，以便在 Experience Cloud 解决方案套件中包含 Marketo，同时将品牌更新为“Experience Platform”。(MCUI-6529)
* 更新了 Experience Cloud 主页，以包含指向“馈送”和“管理”页面的导航链接。(MCUI-6682)
* 修复 [!UICONTROL 了触发器] 定义中的一个问题，用于正确使用“类似”子句。(MCUI-6611)
* 改进了客户属性，让登录“订阅”服务的过程为此变得更加顺畅。(MCUI-6519)

有关产品文档，请参阅 [Experience Cloud和核心服务](https://marketing.adobe.com/resources/help/en_US/mcloud/)

### Experience Cloud ID服务 {#ecid}

* 更新到版本 4.2.0。
* 增加了对适用于 IAB TCF 的 Audience Manager 插件的支持，该插件可通过 ECID Opt-in 对象获取。

有关产品文档，请参阅 [Experience Cloud ID 服务](https://marketing.adobe.com/resources/help/en_US/mcvid/)。

### Mobile Services和Mobile SDK {#mobile}

Adobe Mobile Services中的功能和修复：

**iOS 版本 4.18.2**

* 目标：修复了导致 _purchasedProductIds_ 无法正确表示为视图通知数组的问题。

**Android 版本 4.17.4**

* 常规：改进了对 Android Instant Apps 的支持，具体方法是：通过使用根 JSON 对象上的 _reachabilityChecksEnabled_ 布尔属性，执行可访问性检查（可在 _ADBMobileConfig.json_ 文件中进行配置）。

有关产品文档，请参阅 [Mobile Services](https://marketing.adobe.com/resources/help/en_US/mobile/)。

有关 Mobile SDK 的更多信息，请参阅[适用于 Experience Cloud 解决方案的 Android SDK 4.x ](https://marketing.adobe.com/resources/help/en_US/mobile/android/)和[适用于 Experience Cloud 解决方案的 iOS SDK 4.x](https://marketing.adobe.com/resources/help/en_US/mobile/ios/)。

## Analytics {#analytics}

* [Adobe Analytics中的新增功能和修复](#aa-features)
* [Analytics管理员的重要声明](#aa-notices)

有关产品文档，请参阅 [Analytics 帮助主页](https://marketing.adobe.com/resources/help/en_US/reference/)。

### Adobe Analytics 中的新增功能 {#aa-features}

| 功能 | 描述 |
| -----------| ---------- |  
| 按非重复计数分段 | 现在，您可以按维度中项目的非重复计数进行分段。例如，“查看超过 5 个不同产品的访客数量”或“查看了 5 个以上不同页面的访问数量”。(请注意，如果您想要创建一个维度的明显计数(例如客户#. of products，etc of products等)，则在计算Metrics中仍可使用近似计数差异化函数。 |
| 对Java11的临时分析支持 | 现在，Ad Hoc Analysis 已与 Java 11 兼容。以下是使用Java11的一些警告。 |
| Advertising Analytics 更新 | 我们即将发布一系列关于 Advertising Analytics 的更新： <ul><li>Microsoft Bing（必应）于 3 月 31 日收购了 Yahoo Gemini。为此，Yahoo Gemini 广告帐户选项不再可用。 </li><li>Google 已实施新的跟踪模式，我们如今不再使用_跟踪模板_，而是改用_最终 URL 后辍_。</li></ul> |
| Analysis Workspace | 优化最佳实践更新. |

**修复**

* (Workspace) 修复了导致无法从流失可视化图表创建区段的问题。（AN-177042、AN-176876）
* (Workspace) 修复了导致无法从流量可视化图表创建区段的问题。(AN-176681)
* (Workspace) 修复了表格中的错位问题。(AN-176919)
* (Workspace) 修复了日语 UI 中折叠/展开可视化图表面板时出现的问题。(AN-170601)
* 修复了尝试在功能板缩图报表中切换区段时出现的问题。(AN-177056)
* (Reports &amp; Analytics) 修复了无法在“渠道概览”报表中选择量度的问题。(AN-176786)
* （区段管理器）修复了在尝试编辑与多个 Audience Manager 数据源共享的区段时导致出现错误消息的问题。(AN-175353)
* (Workspace) 修复了导致非管理员用户无法查看其拥有的未在虚拟报表包中策划的组件（例如，区段）。(AN-175616)
* （管理员）修复了在尝试编辑多个报表包中的 eVar 时出现的问题。(AN-168150)
* （管理员）修复了无法在旧版的用户管理 UI 中，将资产转移给其他用户的问题。（AN-176630、AN-173974）
* (Workspace) 修复了过早地显示异常检测数据的问题。该修复应该会大幅减少误报的现象。(AN-176724)

### Analytics管理员的重要声明 {#aa-notices}

| 注意 | 添加或更新日期 | 描述 |
| -----------| ---------- | ---------- |
| 即将更改“报表总数”计算__ | 2019 年 4 月 16 日 | 在 2019 年 6 月 13 日，Adobe Analytics 将以一致的方式处理所有维度和量度中的“报表总数”__计算。这将导致某些报表（通常为 Prop 或客户属性报表）的总数发生更改。在进行此项更改之前，无论“未指定”__是否显示在报表中，某些报表总数都会不一致地在总数中包含或排除“未指定”__行项目。<br/>从 2019 年 6 月 13 日开始，“未指定”__将始终显示在报表总数中，即使它在报表中未显示为行项目也是如此。此更改将影响 Analysis Workspace、Reports &amp; Analytics、Ad Hoc Analysis、Report Builder 和报表 API。 |
| Analysis Workspace 中的 CSV 下载操作更新 | 2019 年 4 月 10 日 | 从 2019 年 4 月 11 日开始，将会对 Analysis Workspace 中的 CSV 下载功能（和复制到剪贴板）进行一些更改，以从导出的数据中删除格式。  <ul><li>千位分隔符将不再包含在内。小数分隔符将继续包含在内，并将遵循**组件** &gt; **报表格式** &gt; **千位分隔符**下定义的格式。注意：使用逗号作为小数分隔符的数值将会继续在导出的 CSV 中引用。</li><li>不会显示任何货币符号。</li><li>不会显示任何百分比符号。百分数将以小数形式显示。例如，75% 将表示为 0.75。</li><li>时间将以秒为单位显示。</li><li>同期表将仅显示原始值；将删除百分比。</li><li>如果数字无效，将显示空单元格。</li></ul> |
| Analysis Workspace 调试器命令即将变更 | 2019 年 4 月 4 日 | 打开Analysis Workspace调试器的控制台命令将于2019年 **月13日更改为AdobeTools. debug. includeOberonXML**。 |
| 即将更改对启用日期和数字分类的支持 | 2019 年 2 月 28 日 | 已从代码库中移除了导入数字 2 分类和启用日期的分类的功能。这项更改将随 2019 年 6 月维护版本的发布而生效。如果您的导入文件中包含“数字”或“启用日期”列，则这些单元格会被静默忽略，同时该文件中的任何其他数据均会正常导入。<br/>现有的分类仍可以通过标准分类工作流程导出，并将继续在报表中可用。 |
| 显著更新了有关 getPercentPageViewed 插件的文档。 | 2019 年 2 月 12 日 | [https://experiencecloud.adobe.com/resources/help/zh_CN/sc/implement/getPercentPageViewed.html](https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/getPercentPageViewed.html) |
| 管理员 &gt; 一般帐户设置 | 2019 年 2 月 7 日 | *对于在2019年月之后在伦敦数据中心创建的任何新报表包，设置 _将默认为对在伦敦数据中心创建的任何新报表包启用，但仅当这些报告包的设置从Admin_ Console中列出的模板复制时。设置复制自其他报表包的报表包将继承选定报表包的所有设置。<br/> *对于在EMEA中设置报告套件的所有客户，设置 _IP模糊处理_ 不再启用。 |
| 移动浏览器版本号 | 2019 年 2 月 7 日 | 从 2019 年 1 月 8 日开始，我们将移动浏览器版本号的截断级别从 2 更改为 1。在该日期之后，版本号将只显示前两个级别（例如 _Firefox 64.0.2_ 现在报告为 _Firefox 64.0_）。 |
| Ad Hoc Analysis 生命周期终止 | 更新日期：2019 年 1 月 29 日 | 2018 年 8 月 6 日，Adobe 宣布计划终止 Ad Hoc Analysis 生命周期。确定终止日期后，Adobe 会立即与大家共享此信息。<br/>有关更多信息（包括在此期间将兼容哪些版本的 Java），请访问[发现工作区](https://adobe.ly/discoverworkspace)。 |
| 简短 Analytics 报表链接 | 2019 年 1 月 14 日 | 系统将从 2019 年 1 月 17 日星期四开始按照滚动计划表清理和删除任何在一年内未被访问过的简短 Analytics 报表链接。 |
| 停止对 TLS 1.0 的支持 | 更新日期：2019 年 1 月 10 日 | 2019 年 2 月 11 日，Adobe Analytics 报表将不再支持 TLS（传输层安全性）1.0 加密。这一更改体现了我们为维持最高安全标准和提升客户数据安全性所做的不懈努力。如果您在2019年月11日之后无法连接到Adobe Analytics报告，则应将浏览器升级到 [最新版本](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html)。<br/>从 2019 年 2 月 20 日开始，Adobe Analytics 数据收集将不再支持 TLS 1.0。在实施此次更改后，如果最终用户使用不支持 TLS 1.1 或更高版本的旧设备或 Web 浏览器，Adobe 将不再从这些用户那里收集 Analytics 数据。我们希望这不会对客户数据或报表产生重大影响。（如果您的网站已不支持 TLS 1.0，则不会受到影响。）<br/>从 2019 年 4 月 11 日开始，Adobe Analytics 报表 API 将不再支持 TLS 1.0 加密。访问该 API 的客户应当确认他们不会受到影响。 <ul><li>使用具有默认设置的 Java 7 的 API 客户端将需要[做出修改才能支持 TLS 1.2](https://www.java.com/en/configure_crypto.html)。（请参阅“更改客户端端点的默认 TLS 协议版本：将 TLS 1.0 更改为 TLS 1.2”。__） </li><li>使用 Java 8 的 API 客户端应当不会受到影响，因为其默认设置为 TLS 1.2。</li><li> 使用其他框架的 API 客户端将需要联系各自的供应商来获取有关 TLS 1.2 支持的详细信息。</li></ul> |
| 由于对 TLS 1.0 的支持终止而更新 Adobe Report Builder | 2018 年 9 月 7 日 | 由于对 TLS 1.0 的支持即将终止，我们建议 Adobe Report Builder (ARB) 用户在 2019 年 2 月 7 日之前下载 ARB v5.6.21。**在该日期之后，ARB的先前版本不再起作用。** |
| Analysis Workspace 中的 CSV 下载操作更新 | 2019 年 1 月 9 日 | 从 2019 年 2 月 7 日开始，从 Analysis Workspace 下载 CSV（以及复制到剪贴板）时将不再包含千位分隔符。注意：Analysis Workspace UI 将继续显示千位分隔符。此外，小数点分隔符将继续包含在内，并将遵守 **[!UICONTROL “组件]** ”&gt; **[!UICONTROL “报表设置]** ”&gt; **[!UICONTROL “几千分隔符]**”下定义的格式。 |
| 数据馈送：post_product_list 列 - 大小更改 | 2019 年 1 月 9 日 | Adobe 计划于 2019 年 2 月 7 日将 post_product_list 列的大小从 64 KB 扩展到 16 MB。此更改旨在确保处理过程中添加到 post_product_list 的推销 eVar 值不会导致产品和收入值截断。如果您的流程需要获取 post_product_list 值，请确保这些流程可以处理长度最大为 16 MB 的值，否则会将值截断为 16 KB，以避免数据获取失败。 |
| 影响不活动的 Analytics 实时流端点的管理更改 | 2018 年 12 月 20 日 | 从 2019 年 2 月 1 日开始，可能会禁用持续 90 天没有活动客户连接的实时流端点。您可以联系 客户关怀团队查询您的实时流端点，并在必要时重新启用它们。此外，请确保您的客户进程按照服务设计要求保持持久连接，并在连接断开或中断时实施重新连接。 |
| 达拉斯 FTP 服务器迁移 (ftp2.omniture.com) | 2018 年 10 月 19 日 | 在 2018 年 10 月 23 日，如果您通过 SFTP 协议连接到 ftp2.omniture.com，则可能需要重新接受 SJ1 站点的主机标识符。此问题仅在 10 月 23 日出现。请参阅[升级 Adobe FTP 服务器](https://marketing.adobe.com/resources/help/en_US/whitepapers/ftp/ftp_upgrade.html)。 |
| 更新“移动设备”维度 | 2018 年 10 月 16 日 | 9 月 26 日，Adobe 将其设备查询功能更新为 Device Atlas 的 2.1 API。如此一来，更加详细的设备信息（例如 Apple iPhone 7、Apple iPhone 8 Plus 等）将会显示在某些浏览器的“移动设备”维度中。应该定向使用这种新级别的设备详细信息，因为该项更新目前尚未扩展到所有的设备和浏览器类型。 |
| 停止对 Internet Explorer 11 的支持 | 2018 年 9 月 12 日 | Adobe 将于 2018 年 11 月 13 日，停止在 Adobe Analytics 中支持 Internet Explorer 11。请您尽快切换到 Microsoft Edge 或其他受支持的浏览器。 |
| Ad Hoc Analysis 生命周期终止 | 2018 年 9 月 8 日 | 2018 年 8 月 6 日，Adobe 宣布计划终止 Ad Hoc Analysis 生命周期。确定终止日期后，Adobe 会立即与大家共享此信息。有关更多信息，请参阅[探索工作区](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)。我们今后不会修改 [!UICONTROL 临时分析] 以支持Java+。如果升级到Java9+ [!UICONTROL ，临时分析] 将停止运行。仅支持 Java 8。 |
| 由于对 TLS 1.0 的支持终止而更新 Adobe [!UICONTROL Report Builder] | 2018 年 9 月 7 日 | 由于对 TLS 1.0 的支持即将终止，我们建议 [!UICONTROL Report Builder] (ARB) 用户在 2019 年 2 月之前下载 ARB v5.6.21。在该日期之后，以前版本的 ARB 将无法再正常使用。 |
| Analytics 用户迁移的新帮助 | 2018 年 5 月 10 日 | 我们更新了 Analytics 用户 ID 迁移帮助中有关将 Enterprise ID 和 Federated ID 迁移到 Admin Console 的信息。请参阅[为 Enterprise ID 和 Federated ID 迁移 Analytics 用户帐户](https://marketing.adobe.com/resources/help/en_US/experience-cloud/admin-console/analytics-migration/migrate-enterprise.html)。 |
| 即将删除帐户活动报表 | 2018 年 5 月 10 日 | 在 Adobe Analytics 夏季版本中，“帐户活动报表”将被替换为“服务器调用使用情况”功能。“帐户活动报表”将于 2018 年 8 月 9 日永久删除。要在 2018 年 8 月 9 日之后查看有关报表包流量的摘要数据，请使用“服务器调用使用情况”功能。 |
| 关于计算量度中线性分配模型的更改 | 生效日期：2018 年 7 月 19 日 | 7 月 19 日，Adobe Analytics 将修改计算量度中分配模型的评估方式。作为此更改的一部分，使用非默认分配模型的计算量度将迁移至改进的新归因模型。[!UICONTROL 营销渠道上次接触] 和 [!UICONTROL 营销渠道首次接触] 分配模型将专门迁移到新 [!UICONTROL 的最近接触] 和 [!UICONTROL 首次接触] 归因模型。([!UICONTROL 营销渠道] 尚未弃用，只有在计算指标中显示的两个分配模型)。此外，我们将更正线性分配的计算方式。如果您使用计算量度的线性分配模型，则报表可能会稍有变化，反映更正后的新归因模型。对计算指标的此项更改将反映在 [!UICONTROL Analysis Workspace]、 [!UICONTROL Reports&amp; Analytics]、 [!UICONTROL Reporting API]、 [!UICONTROL Report Builder]和Ad Hoc [!UICONTROL Analysis]中。有关此更改的详细信息，请参阅 [“计算量度](https://marketing.adobe.com/resources/help/en_US/analytics/calcmetrics/m_metric_type_alloc.html) ”文档。 |
| [!UICONTROL ][!UICONTROL 异常检测和贡献分析功能已从 ]Reports &amp; Analytics 中删除[!UICONTROL ] | 2018 年 4 月 10 日 | 异常检测和贡献分析已从 Reports &amp; Analytics 功能集中删除，现在只能通过 Analysis Workspace 使用。Adobe Analytics Select 和 Foundation 客户只能访问 Workspace 中的“每日粒度”异常检测。 |
| Adobe 不再发布适用于 Safari 的第三方 s_vi Cookie | 2018 年 4 月 5 日 | 2018 年 3 月 20 日，Adobe 停止了发布适用于 Safari 浏览器的第三方 s_vi Cookie。此变更不会影响使用第一方数据收集 Cookie 的客户。此变更也消除了一些客户由于 Safari ITP 而导致出现访问次数和访客数量夸大的问题。 |
| 影响报表的后端变动 | 2018 年 4 月 11 日 | （后端）查找机制的变动将会从多方面影响报表。请注意，以下变动已大约在 2018 年 2 月底生效：不再允许对页面进行重命名。将来，您需要使用分类来重命名页面。在 2018 年 5 月 10 日版本发布之前，系统将继续处理当前已配置的重命名页面。Adobe 将要求所有客户在该日期之前迁移到分类。5 月版本发布后，现有的重命名将不再有效，并且可能会进行逆向更改，恕不另行通知。 <br> <br>URL“替换”方法发生变化。以前，Adobe Analytics 每月存储的（通常）是每个页面名称关联的第一个 URL。将来，我们存储的是每个页面名称的最新 URL。（更新日期：2018 年 4 月 11 日）Reports &amp; Analytics 中不再提供汇总数据和当前数据的类别报表。Web Service API 中的类别汇总报表将在 2018 年 5 月 10 日的 Adobe Analytics 维护版本中弃用。不再支持大约于 2007 年（某些情况下是 2006 年）1 月之前生成的页面/prop 数据。这项措施只影响页面、prop 和页面事件（即，自定义链接、退出链接、下载链接）。注意：此项更改不影响 Analysis Workspace 或 Data Warehouse 中的报表。如果您在这些日期之前有数据，请期待以下各项：在2007年月之前/之后，数据将无法正确组合。将无法搜索大约在 2007 年 1 月之前生成的数据。 |
| 即将更改对启用日期和数字分类的支持 | 2018 年 5 月 7 日 | 在 2018 年 5 月 10 日维护版本中，我们将开始限制启用日期和数字分类的功能。这些分类类型将从管理员和分类导入程序界面中删除。从那天起，将无法添加新的启用日期和数字分类。现有的分类仍可以通过标准分类工作流程进行管理（上传、删除），并将继续在报表中可用。 |
| 即将更改对营销渠道成本和预算的支持 | 2018 年 2 月 28 日 | 在 4 月维护版本中，我们将从管理员 &gt; 营销渠道菜单中移除“营销渠道成本和预算”。无法添加新的成本和预算数据。现有的成本和预算数据将可以继续在报表中使用，但无法进行更新。 |
| 在将用户 ID 迁移至 Admin Console 之前更新 Report Builder | 2018 年 3 月 17 日 | **重要：**将安装的 Report Builder 更新至最新版本。此更新是从 2018 年 4 月开始将 Analytics 用户 ID 迁移至 Admin Console 的先决条件。 |
| 代码管理器 - 旧版 H 代码 | 2018 年 2 月 8 日 | 不再支持从代码管理器下载旧版 JavaScript（H 代码）。 |
| 数据保留：检查并设置您的 Adobe Analytics 数据保留策略 | 2018 年 2 月 1 日 | **背景：** 欧盟的一般数据保护规定(GDPR)自2018年月25日起生效，它规定Adobe作为您的数据处理者，必须采取适当措施以协助其客户执行访问、删除和其他来自个人的请求。“运用适当、安全和及时的删除策略”是履行此项职责的重要部分。为此，Adobe 希望与您在 2018 年 5 月 25 日 GDPR 生效之前，共同实施数据保留策略。<br> <br>**期望的内容：** 除非您已准备好Adobe Analytics数据保留策略，否则Adobe将开始应用Adobe Analytics客户合同中指定的数据保留，除非进行其他安排。在大多数的 Adobe Analytics 合同中，均声明 Adobe 会在 25 个月后删除数据。只要贵公司确立了数据保留策略，那么 Adobe 就会按月逐步实施该策略。如果要将数据保留较长的期限（超出 25 个月），则需支付额外费用。另外，您也可以通过联系客户关怀团队，将数据保留期限配置为较短的时间。不久，您将收到一封电子邮件，其中包含组织的其他详细信息。 <br> <br>数据保留会影响所有访问 Adobe Analytics 历史数据的方法，其中包括但不限于 Reports &amp; Analytics、Analysis Workspace、Report Builder、Web 服务报表 API、Data Warehouse 和数据馈送。**后续步骤：** 确定负责数据保留的组织内的利益相关者。贵公司最清楚应当保留 Adobe Analytics 数据的适当期限。如果您对 Adobe Analytics 数据保留存在任何疑问，请联系您的 Adobe 客户成功经理。 |
| 用户帐户链接 | 2017 年 10 月 26 日 | Analytics 用户不再需要在 Experience Cloud 和 Analytics 之间手动链接其帐户。用户可以联系 Admin Console 管理员以请求 Analytics 访问权限。通过 Analytics 用户 ID 迁移，管理员可以轻松地将用户帐户从 Analytics“用户管理”迁移到 Adobe Admin Console。迁移用户后，他们将能够访问 Experience Cloud 中提供的已购解决方案与核心服务。[进一步了解 Analytics 用户 ID 迁移](https://marketing.adobe.com/resources/help/en_US/experience-cloud/admin-console/analytics-migration/)。 |

## Audience Manager {#aam}

| 功能 | 描述 |
| -----------| ---------- |  
| [特征推荐](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/segments/trait-recommendations.html) | 由 [Adobe Sensei](https://www.adobe.com/sensei.html) 提供支持的“特征推荐”功能可将数据科学纳入您的 Audience Manager 日常工作流程中。<br>使用“特征推荐”，在[区段生成器](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/segments/segment-builder.html)中构建或编辑区段时，您能够获得可包含的其他推荐特征（与区段规则中的特征类似）。将推荐的特征添加到区段中，可增加目标受众。 |
| [全局数据源](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/data-sources/global-data-sources.html) | 所有的 Audience Manager 客户都可以访问全局数据源，这些数据源包含由多家设备制造商（例如，Apple、Samsung、Microsoft、Roku，以及 Android 设备制造商）生成的设备广告 ID。这些 ID 是设备制造商出于广告宣传的目的而提供的。您可以使用全局数据源来同步设备 ID，并导入或导出这些映射中断开映射的数据。Audience Manager 将根据其格式，验证由客户导入的设备广告 ID (DAID)，以确保这些 ID 符合设备制造商列出的标准格式。 |
| [ID 映射限制](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/administration/usage-limits.html#id-mapping-limits) | 通过限制与设备 ID 关联的跨设备 ID 映射数量，我们改进了分段、报告和导出区段的过程。新近推行的限制有助于我们缓解错误集成和不准确的数据集可能对引入和下游处理造成的影响。<br/>新的限制包括： <ul><li>每个跨设备 ID 最多可关联 100 个设备 ID</li><li>每个设备 ID 最多可关联 10 个跨设备 ID</li><li>1 个设备 ID 最多可关联 1000 个设备 ID</li></ul> |

### 改进

* 当用户尝试使用与基于规则、区段或载入的特征类型不同的基线创建 [!UICONTROL 算法模型] 时，用户现在会看到错误消息。错误消息是：“只能将基于规则的特征、载入的特征和区段用作基准”。(AAM-45235).
* [!UICONTROL 从][!UICONTROL “属性”] 和 [!UICONTROL “文件夹特征”] 页面中删除了终身量度。
* 目前，区段映射开始日期和结束日期包含在[!UICONTROL 目标常规报表]中 (AAM-44997)。

### 修复

* 修复了 [!UICONTROL 导致出站文件历史记录报告] 在某些情况下无法加载(AAM-45713)的问题。
* 修复了在单击空字段(AAM-45599)中的“添加特征”时，将之前选定的特征添加到 [!UICONTROL 区段生成器][!UICONTROL ] 的问题。
* 修复了导致用户无法编辑或停用那些含有已排除特征的“算法模型”的问题 (AAM-45552)。

## Advertising Cloud {#adcloud}

更新于2019年月15日，星期四发布

| 功能 | 描述 |
| -----------| ---------- | 
| 搜索促销活动 | 在日期范围选择器中，日历现在安排从星期日到星期六。以前，它安排从星期日到星期六。 |
| 报表 | Portfolio报表现在包括可选的列 _包支出策略_。 |

可以在产品中通过单击帮助**？** 菜单目录访问 Advertising Cloud 帮助。

## Target {#target}

即将发布的Adobe Target版本发行说明：

### Target Standard/Premium 19.4.1（2019 年 4 月 15 日）

这个版本属于维护版本，它包括以下变更：

（括号中的问题编号供 Adobe 内部使用。）

* 更新了 Adobe Experience Cloud UI，以体现品牌和产品变化。（TGT-33546、TGT-33272 和 TGT-33331）

### Target Standard/Premium 19.4.2（2019 年 4 月 29 日）

这个版本包括以下功能、变化和增强功能：

（括号中的问题编号供 Adobe 内部使用。）

| 功能 | 描述 |
| -----------| ---------- |  
| 移动设备可视化体验编辑器 | 使用本机移动设备应用程序的可视化体验编辑器 (VEC)，您能够以 DIY（自己动手）方式创建活动并对本机移动设备应用程序上的内容进行个性化，而无需持续依赖开发和应用程序发布循环。 |
| 可视化体验编辑器 | 可视化体验编辑器 (VEC) 包含以下增强功能，可让您更快捷、更高效地完成工作： <ul><li>您可以在 VEC 中编辑元素的样式，包括编辑背景图像。(TGT-15001)</li><li>Target 通过 v4.5.1 或更高版本中的配置来支持 HTML5。(TGT-33618)</li></ul> |

**增强功能、修复和变更**

* 我们改进了您在使用 VEC 删除资产时的工作流程。删除的资产现在从选件库和Scene7(如果适用)删除，删除的资产不再显示在搜索结果中。(TGT-31981)
* 我们改进了“资产”选取器中图像选件的呈现方式。现在可以更加快捷、高效地显示和选择图像选件。(TGT-32897)
* 我们改进了当您在 VEC 中取消载入页面时，对 URL 重定向的处理。(TGT-33815)
* 当您在 VEC 中取消载入页面后，系统会正确地显示出工具栏图标。如果某些特定的操作只有在完全载入页面后才能执行，那么相关的工具栏图标将会禁用。(TGT-33811)
* 现在，在您从“收藏集”选取器中选择建议收藏项后，必须单击“保存”按钮。这种工作流程与 Target 中的其他工作流程保持一致。(TGT-33205)

请参阅 [Adobe Target 发行说明](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html)，了解有关下列产品的最新发行信息：

* Target Standard 和 Premium
* Recommendations Classic

## Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新增功能、修复和更新。Adobe 建议那些采用内部部署的客户部署最新的修补程序，以便确保获得更高的稳定性、安全性和性能。

### 产品版本

**Cloud Manager 2019.3.0**

在这个月的 Cloud Manager 版本（即 2019.3.0）中，为上一版本交付的“系统监控”功能增加了 SLA 报表功能。另外，还增加了一些关键屏幕的可视化刷新效果。

* [发行说明](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

### 产品维护

**AEM 6.2 Service Pack 1 - 累计修复包 19**

2019 年 3 月 07 日发布的 AEM 6.2 SP1-CFP19 (6.2.1.19) 是一项重要更新，其中包括自 2016 年 12 月推出 AEM 6.2 SP1 通用版本以来发布的多项关键客户修复。

* [发行说明](https://helpx.adobe.com/experience-manager/release-notes--aem-6-2-cumulative-fix-pack.html)
* [AEM 表单 CFP 版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.3 Service Pack 3 - 累计修复包 3**

AEM6.3SP3-CFP3(6.3.3.3)发布于2019年月14日，它是包括自AEM6.3月20日的一般可用性以来已发布的重要客户的重要更新。

* [发行说明](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
* [AEM 表单 CFP 版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

### 其他资源

* [AEM 6.4 学习与支持主页](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 学习与支持主页](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 学习与支持主页](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager 用户指南](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [更早版本的 AEM 文档](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Scene7 发布系统发行说明](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre 发行说明](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)
