---
title: Adobe Experience Cloud 发行说明
description: Experience Cloud 发行说明模板
doc-type: 发行说明
last-update: 2019 年 5 月
author: mfrei
translation-type: tm+mt
source-git-commit: 016a4a630f4f26be8322a008bb214db9dba9a49a

---


# Adobe Experience Cloud 发行说明

Adobe Experience Cloud 的新增功能和修复。

>[!NOTE]
>>若要通过电子邮件接收关于即将发布版本的通知，请订阅 [Adobe 产品更新早知道](https://www.adobe.com/subscription/priority-product-update.html)。您将在版本发行前的三到五个工作日收到通知。对于发行之后发布的新信息，将使用发布日期进行标记。


**发布日期：2019年月**

* [Adobe Experience Platform](#platform)
* [Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [Target Standard/Premium 19.5.1](#target)
* [Magento](#magento)
* [Primetime](#primetime)

## Adobe Experience Platform {#platform}

### Adobe Experience Platform发行说明

1.0版本，2019年月15日

* 有关体验平台的最新更新，请参阅 [Adobe. io](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes-20190515.md) 上的Experience Platform发行说明。

### Experience Platform Launch

* 有关最新信息，请参阅 [Experience Platform Launch](https://docs.adobelaunch.com/) 。

### Experience Cloud ID 服务

发行日期：**2019 年 5 月 13 日**

* 支持访客 API 4.3.0
* 支持 ITP 2.1。
* 修复了有关 secureCookie 配置的问题。

## Analytics {#analytics}

Adobe Analytics 的新增功能和修复：

* [Adobe Analytics中的新增功能和修复](#aa-features)
* [Analytics 管理员的重要注意事项](#aa-notices)

有关产品文档，请参阅 [Analytics 帮助主页](https://marketing.adobe.com/resources/help/en_US/reference/)。

### Adobe Analytics中的新增功能和修复 {#aa-features}

| 功能 | 描述 |
| -----------| ---------- |  
| **AppMeasurement版2.14.0** <ul><li>修复了在等待多个点击时，跟踪器参数状态管理的问题。(AN-176931，AN-176629，DTM-12758)</li><li>更新了AppMeasurement以包含访客. js4.3.0(AN-180049)</li></ul> |
| **Analysis Workspace：** 新增 _功能：重复实例_ 流可视化设置 | “包含重复实例”__流量设置使您可以选择包含还是排除重复实例，例如页面重新载入。此外，所有流量可视化图表现在仅基于实例。 |
| **临时分析：** 与Java11的兼容性 | 现在，Ad Hoc Analysis 已与 Java 11 兼容。了解如何在 [Java11上运行Ad Hoc Analysis](https://marketing.adobe.com/resources/help/en_US/dsc/adhoc-java.html)。 |
| **数据收集：** 新的s_ ecid cookie | 新增了第一方服务器 s_ecid Cookie，其中的数据收集用于存储访客的 ECID。 |

**Analysis Workspace 修复**

* 修复了影响网页逗留时间的问题。在计算逗留时间分段时，Workspace 报表将不再使用“页面名称”，从而可以计算粒度和分段统计的网页点击数。(AN-140479)
* 修复了折线可视化图表的性能问题，这是改进 Workspace 性能这项更大工作的一个部分。(AN-174878)
* 修复了下载的 .csv 文件中缺少 UTF-8 编码的问题。(AN-178393)
* 修复了 Workspace 项目性能缓慢的问题。(AN-177710)
* 修复了折线可视化图表由于 Y 轴的粒度范围较小而出现的显示问题。(AN-176467)

**其他 Analytics 修复**

* Audience Analytics：修复了在 Audience Manager (AAM) 中更改受众名称后发生的问题 – 更新的名称未反映在 Audience Analytics 中。(AN-176237)
* 修复了阻止用户在 AAM 中保存 Google Analytics 区段的问题。这个问题是由名称中混有大小写字符的现有 AAM 文件夹引起的。现在，我们按不区分大小写来处理所有文件夹以便进行同步。(AN-177934)
* 修复了用户在通过 Experience Cloud 登录 Analytics 后会话超时情况下发生的问题。恢复会话时，用户被重定向到错误的 URL。(AN-176812)
* 修复了数据仓库请求中时区偏移的问题。(AN-177585)

### Analytics 管理员的重要注意事项 {#aa-notices}

| 注意 | 添加或更新日期 | 描述 |
| -----------| ---------- | ---------- |
| 即将更改“报表总数”计算__ | 2019 年 4 月 16 日 | 在 **2019 年 6 月 13 日**，Adobe Analytics 将以一致的方式处理所有维度和量度中的“报表总数”__计算。这将导致某些报表（通常为 Prop 或客户属性报表）的总数发生更改。在进行此项更改之前，无论“未指定”__是否显示在报表中，某些报表总数都会不一致地在总数中包含或排除“未指定”__行项目。<br/>自 2019 年 6 月 13 日开始，“未指定”__将始终显示在报表总数中，即使它在报表中未显示为行项目也是如此。此外，在进行此项更改之后，对于某些维度，使用“存在”__或“不存在”__逻辑的区段可能会显示不同结果。此更改将影响 Analysis Workspace、Reports &amp; Analytics、Ad Hoc Analysis、Report Builder 和报表 API。 |
| Analysis Workspace 中的 CSV 下载操作更新 | 2019 年 4 月 10 日 | 从 2019 年 4 月 11 日开始，将会对 Analysis Workspace 中的 CSV 下载功能（和复制到剪贴板）进行一些更改，以从导出的数据中删除格式。  <ul><li>千位分隔符将不再包含在内。小数分隔符将继续包含在内，并将遵循**组件** &gt; **报表格式** &gt; **千位分隔符**下定义的格式。注意：使用逗号作为小数分隔符的数值将会继续在导出的 CSV 中引用。</li><li>不会显示任何货币符号。</li><li>不会显示任何百分比符号。百分数将以小数形式显示。例如，75% 将表示为 0.75。</li><li>时间将以秒为单位显示。</li><li>同类群组表将只显示原始值；百分比将被删除。</li><li>如果数字无效，将显示空单元格。</li></ul> |
| Analysis Workspace 调试器命令即将变更 | 2019 年 4 月 4 日 | **2019 年 6 月 13 日**，开启 Analysis Workspace 调试器的控制台命令将变为 adobeTools.debug.includeOberonXml。 |
| 即将更改对启用日期和数字分类的支持 | 2019 年 2 月 28 日 | 已从代码库中移除了导入数字 2 分类和启用日期的分类的功能。这项更改将随 2019 年 6 月维护版本的发布而生效。如果您的导入文件中包含“数字”或“启用日期”列，则这些单元格会被静默忽略，同时该文件中的任何其他数据均会正常导入。<br/>现有的分类仍可以通过标准分类工作流程导出，并将继续在报表中可用。 |
| 显著更新了有关 getPercentPageViewed 插件的文档。 | 2019 年 2 月 12 日 | [https://experiencecloud.adobe.com/resources/help/zh_CN/sc/implement/getPercentPageViewed.html](https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/getPercentPageViewed.html) |
| 管理员 &gt; 一般帐户设置 | 2019 年 2 月 7 日 | * 对于 2019 年 1 月之后在伦敦数据中心创建的任何新报表包，默认情况下会启用“将 IP 地址的最后八位字节替换为 0”__设置，但前提是这些报表包的设置是从 Admin Console 中列出的模板复制的。设置复制自其他报表包的报表包将继承选定报表包的所有设置。<br/> * 对于设置了报表包的所有 EMEA 客户，默认情况下将不再启用“IP 模糊处理”__设置。 |
| 移动浏览器版本号 | 2019 年 2 月 7 日 | 从 2019 年 1 月 8 日开始，我们将移动浏览器版本号的截断级别从 2 更改为 1。在该日期之后，版本号将只显示前两个级别（例如 _Firefox 64.0.2_ 现在报告为 _Firefox 64.0_）。 |
| Ad Hoc Analysis 生命周期终止 | 更新日期：2019 年 1 月 29 日 | 2018 年 8 月 6 日，Adobe 宣布计划终止 Ad Hoc Analysis 生命周期。确定终止日期后，Adobe 会立即与大家共享此信息。<br/>有关更多信息（包括在此期间将兼容的 Java 版本），请访问[探索工作区](https://adobe.ly/discoverworkspace)。 |
| 简短 Analytics 报表链接 | 2019 年 1 月 14 日 | 系统将从 2019 年 1 月 17 日星期四开始按照滚动计划表清理和删除任何在一年内未被访问过的简短 Analytics 报表链接。 |
| 停止对 TLS 1.0 的支持 | 更新日期：2019 年 1 月 10 日 | 2019 年 2 月 11 日，Adobe Analytics 报表将不再支持 TLS（传输层安全性）1.0 加密。这一更改体现了我们为维持最高安全标准和提升客户数据安全性所做的不懈努力。如果您在2019年月11日之后无法连接到Adobe Analytics报告，则应将浏览器升级到 [最新版本](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html)。<br/>从 2019 年 2 月 20 日开始，Adobe Analytics 数据收集将不再支持 TLS 1.0。在实施此次更改后，如果最终用户使用不支持 TLS 1.1 或更高版本的旧设备或 Web 浏览器，Adobe 将不再从这些用户那里收集 Analytics 数据。我们希望这不会对客户数据或报表产生重大影响。（如果您的网站已不支持 TLS 1.0，则不会受到影响。）<br/>从 2019 年 4 月 11 日开始，Adobe Analytics 报表 API 将不再支持 TLS 1.0 加密。访问该 API 的客户应当确认他们不会受到影响。 <ul><li>在默认设置下使用 Java 7 的 API 客户端将需要[做出修改才能支持 TLS 1.2](https://www.java.com/en/configure_crypto.html)。（请参阅“更改客户端端点的默认 TLS 协议版本：将 TLS 1.0 更改为 TLS 1.2”。__） </li><li>使用 Java 8 的 API 客户端应当不会受到影响，因为其默认设置为 TLS 1.2。</li><li> 使用其他框架的 API 客户端将需要联系各自的供应商来获取有关 TLS 1.2 支持的详细信息。</li></ul> |
| 由于对 TLS 1.0 的支持终止而更新 Adobe Report Builder | 2018 年 9 月 7 日 | 由于对 TLS 1.0 的支持即将终止，我们建议 Adobe Report Builder (ARB) 用户在 2019 年 2 月 7 日之前下载 ARB v5.6.21。**在该日期之后，以前版本的 ARB 将无法再正常使用。** |
| Analysis Workspace 中的 CSV 下载操作更新 | 2019 年 1 月 9 日 | 从 2019 年 2 月 7 日开始，从 Analysis Workspace 下载 CSV（以及复制到剪贴板）时将不再包含千位分隔符。注意：Analysis Workspace UI 将继续显示千位分隔符。此外，小数分隔符将继续包含在内，并将遵循**[!UICONTROL 组件]** &gt; **[!UICONTROL 报表设置]** &gt; **[!UICONTROL 千位分隔符]**下定义的格式。 |
| 数据馈送：post_product_list 列 - 大小更改 | 2019 年 1 月 9 日 | Adobe 计划于 2019 年 2 月 7 日将 post_product_list 列的大小从 64 KB 扩展到 16 MB。此更改旨在确保处理过程中添加到 post_product_list 的推销 eVar 值不会导致产品和收入值截断。如果您的流程需要获取 post_product_list 值，请确保这些流程可以处理长度最大为 16 MB 的值，否则会将值截断为 16 KB，以避免数据获取失败。 |
| 影响不活动的 Analytics 实时流端点的管理更改 | 2018 年 12 月 20 日 | 从 2019 年 2 月 1 日开始，可能会禁用持续 90 天没有活动客户连接的实时流端点。您可以联系 客户关怀团队查询您的实时流端点，并在必要时重新启用它们。此外，请确保您的客户进程按照服务设计要求保持持久连接，并在连接断开或中断时实施重新连接。 |
| 达拉斯 FTP 服务器迁移 (ftp2.omniture.com) | 2018 年 10 月 19 日 | 在 2018 年 10 月 23 日，如果您通过 SFTP 协议连接到 ftp2.omniture.com，则可能需要重新接受 SJ1 站点的主机标识符。此问题仅在 10 月 23 日出现。请参阅[升级 Adobe FTP 服务器](https://marketing.adobe.com/resources/help/en_US/whitepapers/ftp/ftp_upgrade.html)。 |
| 更新“移动设备”维度 | 2018 年 10 月 16 日 | 9 月 26 日，Adobe 将其设备查询功能更新为 Device Atlas 的 2.1 API。如此一来，更加详细的设备信息（例如 Apple iPhone 7、Apple iPhone 8 Plus 等）将会显示在某些浏览器的“移动设备”维度中。应该定向使用这种新级别的设备详细信息，因为该项更新目前尚未扩展到所有的设备和浏览器类型。 |
| 停止对 Internet Explorer 11 的支持 | 2018 年 9 月 12 日 | Adobe 将于 2018 年 11 月 13 日，停止在 Adobe Analytics 中支持 Internet Explorer 11。请您尽快切换到 Microsoft Edge 或其他受支持的浏览器。 |
| Ad Hoc Analysis 生命周期终止 | 2018 年 9 月 8 日 | 2018 年 8 月 6 日，Adobe 宣布计划终止 Ad Hoc Analysis 生命周期。确定终止日期后，Adobe 会立即与大家共享此信息。有关更多信息，请参阅[探索工作区](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)。从现在开始，我们将不再修改 [!UICONTROL Ad Hoc Analysis]，进而不支持 Java 9 及以上版本。如果您升级到 Java 9 及以上版本，[!UICONTROL Ad Hoc Analysis] 将停止运行。仅支持 Java 8。 |
| 由于对 TLS 1.0 的支持终止而更新 Adobe [!UICONTROL Report Builder] | 2018 年 9 月 7 日 | 由于对 TLS 1.0 的支持即将终止，我们建议 [!UICONTROL Report Builder] (ARB) 用户在 2019 年 2 月之前下载 ARB v5.6.21。在该日期之后，以前版本的 ARB 将无法再正常使用。 |
| Analytics 用户迁移的新帮助 | 2018 年 5 月 10 日 | 我们更新了 Analytics 用户 ID 迁移帮助中有关将 Enterprise ID 和 Federated ID 迁移到 Admin Console 的信息。请参阅[为 Enterprise ID 和 Federated ID 迁移 Analytics 用户帐户](https://marketing.adobe.com/resources/help/en_US/experience-cloud/admin-console/analytics-migration/migrate-enterprise.html)。 |
| 即将删除帐户活动报表 | 2018 年 5 月 10 日 | 在 Adobe Analytics 夏季版本中，“帐户活动报表”将被替换为“服务器调用使用情况”功能。“帐户活动报表”将于 2018 年 8 月 9 日永久删除。要在 2018 年 8 月 9 日之后查看有关报表包流量的摘要数据，请使用“服务器调用使用情况”功能。 |
| 关于计算量度中线性分配模型的更改 | 生效日期：2018 年 7 月 19 日 | 7 月 19 日，Adobe Analytics 将修改计算量度中分配模型的评估方式。作为此更改的一部分，使用非默认分配模型的计算量度将迁移至改进的新归因模型。[!UICONTROL 营销渠道最近联系]和[!UICONTROL 营销渠道首次联系]分配模型将分别迁移至新的[!UICONTROL 最近联系]和[!UICONTROL 首次联系]归因模型。（并未弃用[!UICONTROL 营销渠道]，仅弃用了计算量度中的上述两个分配模型）。此外，我们将更正线性分配的计算方式。如果您使用计算量度的线性分配模型，则报表可能会稍有变化，反映更正后的新归因模型。计算量度的这一更改将反映在 [!UICONTROL Analysis Workspace]、[!UICONTROL Reports &amp; Analytics]、[!UICONTROL 报表 API]、[!UICONTROL Report Builder] 和 [!UICONTROL Ad Hoc Analysis] 中。有关此更改的详细信息，请参阅 [“计算量度](https://marketing.adobe.com/resources/help/en_US/analytics/calcmetrics/m_metric_type_alloc.html) ”文档。 |
| [!UICONTROL ][!UICONTROL 异常检测和贡献分析功能已从 ]Reports &amp; Analytics 中删除[!UICONTROL ] | 2018 年 4 月 10 日 | 异常检测和贡献分析已从 Reports &amp; Analytics 功能集中删除，现在只能通过 Analysis Workspace 使用。Adobe Analytics Select 和 Foundation 客户只能访问 Workspace 中的“每日粒度”异常检测。 |
| Adobe 不再发布适用于 Safari 的第三方 s_vi Cookie | 2018 年 4 月 5 日 | 2018 年 3 月 20 日，Adobe 停止了发布适用于 Safari 浏览器的第三方 s_vi Cookie。此变更不会影响使用第一方数据收集 Cookie 的客户。此变更也消除了一些客户由于 Safari ITP 而导致出现访问次数和访客数量夸大的问题。 |
| 影响报表的后端变动 | 2018 年 4 月 11 日 | （后端）查找机制的变动将会从多方面影响报表。请注意，以下变动已大约在 2018 年 2 月底生效：不再允许对页面进行重命名。将来，您需要使用分类来重命名页面。在 2018 年 5 月 10 日版本发布之前，系统将继续处理当前已配置的重命名页面。Adobe 将要求所有客户在该日期之前迁移到分类。5 月版本发布后，现有的重命名将不再有效，并且可能会进行逆向更改，恕不另行通知。<br/>URL“替换”方法发生变化。以前，Adobe Analytics 每月存储的（通常）是每个页面名称关联的第一个 URL。将来，我们存储的是每个页面名称的最新 URL。（更新日期：2018 年 4 月 11 日）Reports &amp; Analytics 中不再提供汇总数据和当前数据的类别报表。Web Service API 中的类别汇总报表将在 2018 年 5 月 10 日的 Adobe Analytics 维护版本中弃用。不再支持大约于 2007 年（某些情况下是 2006 年）1 月之前生成的页面/prop 数据。这项措施只影响页面、prop 和页面事件（即，自定义链接、退出链接、下载链接）。注意：此项更改不影响 Analysis Workspace 或 Data Warehouse 中的报表。如果您拥有这些日期之前的数据，预计会出现以下情况：以 2007 年 1 月为分界线，此前的数据与此后的数据将不能正确合并。将无法搜索大约在 2007 年 1 月之前生成的数据。 |
| 即将更改对启用日期和数字分类的支持 | 2018 年 5 月 7 日 | 在 2018 年 5 月 10 日维护版本中，我们将开始限制启用日期和数字分类的功能。这些分类类型将从管理员和分类导入程序界面中删除。从那天起，将无法添加新的启用日期和数字分类。现有的分类仍可以通过标准分类工作流程进行管理（上传、删除），并将继续在报表中可用。 |
| 即将更改对营销渠道成本和预算的支持 | 2018 年 2 月 28 日 | 在 4 月维护版本中，我们将从管理员 &gt; 营销渠道菜单中移除“营销渠道成本和预算”。无法添加新的成本和预算数据。现有的成本和预算数据将可以继续在报表中使用，但无法进行更新。 |
| 在将用户 ID 迁移至 Admin Console 之前更新 Report Builder | 2018 年 3 月 17 日 | **重要：**将安装的 Report Builder 更新至最新版本。此更新是从 2018 年 4 月开始将 Analytics 用户 ID 迁移至 Admin Console 的先决条件。 |
| 代码管理器 - 旧版 H 代码 | 2018 年 2 月 8 日 | 不再支持从代码管理器下载旧版 JavaScript（H 代码）。 |
| 数据保留：检查并设置您的 Adobe Analytics 数据保留策略 | 2018 年 2 月 1 日 | **背景：**欧盟的《通用数据保护条例》(GDPR) 将于 2018 年 5 月 25 日正式生效。根据该条例的规定，Adobe 作为您的数据处理提供商，必须要采取适当的措施来协助客户实现个人请求的访问、删除数据等操作。“运用适当、安全和及时的删除策略”是履行此项职责的重要部分。为此，Adobe 希望与您在 2018 年 5 月 25 日 GDPR 生效之前，共同实施数据保留策略。<br/>**期待完成的任务：**除非您已经实施 Adobe Analytics 数据保留策略，否则在没有其他安排的情况下，Adobe 将按照与客户签署的 Adobe Analytics 合同中的当前规定，开始应用数据保留。在大多数的 Adobe Analytics 合同中，均声明 Adobe 会在 25 个月后删除数据。只要贵公司确立了数据保留策略，那么 Adobe 就会按月逐步实施该策略。如果要将数据保留较长的期限（超出 25 个月），则需支付额外费用。另外，您也可以通过联系客户关怀团队，将数据保留期限配置为较短的时间。您很快就会收到一封电子邮件，其中包含贵组织的其他详细信息。<br/>数据保留会影响所有访问 Adobe Analytics 历史数据的方法，其中包括但不限于 Reports &amp; Analytics、Analysis Workspace、Report Builder、Web 服务报表 API、Data Warehouse 和数据馈送。**后续步骤：**确定贵公司内负责数据保留策略的利益干系人。贵公司最清楚应当保留 Adobe Analytics 数据的适当期限。如果您对 Adobe Analytics 数据保留存在任何疑问，请联系您的 Adobe 客户成功经理。 |
| 用户帐户链接 | 2017 年 10 月 26 日 | Analytics 用户不再需要在 Experience Cloud 和 Analytics 之间手动链接其帐户。用户可以联系 Admin Console 管理员以请求获取 Analytics 访问权限。通过 Analytics 用户 ID 迁移，管理员可以轻松地将用户帐户从 Analytics“用户管理”迁移到 Adobe Admin Console。迁移用户后，他们将能够访问 Experience Cloud 中提供的已购解决方案与核心服务。[进一步了解 Analytics 用户 ID 迁移](https://marketing.adobe.com/resources/help/en_US/experience-cloud/admin-console/analytics-migration/)。 |

## Audience Manager {#aam}

| 功能 | 描述 |
| -----------| ---------- |  
| [IP 地址模糊处理](https://marketing.adobe.com/resources/help/en_US/aam/ip-obfuscation.html) | 由于全球隐私法规，贵公司可能希望在许多国家/地区模糊处理 IP 地址。Audience Manager 允许您在全球范围或者根据具体国家或地区来模糊处理访客 IP 地址。 |
| [自定义合作伙伴集成 - Oracle 数据云](https://marketing.adobe.com/resources/help/en_US/aam/custom-partner-integrations.html) | 此页面列出了 Audience Manager 与数据合作伙伴之间的自定义集成。Audience Manager 通过入站数据文件从 Oracle Data Cloud for Audience Marketplace 中提取 Cookie 和移动 ID 数据。此页面中描述的自定义集成规范仅指包含移动 ID（IDFA 和 Android 设备 ID）的入站数据文件。 |

**修复、增强功能和弃用功能**

* 我们在“目标”的常规报表中新增了两列。您现在可以看到映射到目标的区段具有开始日期和结束日期。(AAM-44781)

## Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新增功能、修复和更新。Adobe 建议那些采用内部部署的客户部署最新的修补程序，以便确保获得更高的稳定性、安全性和性能。

### 产品版本

**AEM 6.5**

2019 年 4 月 8 日开始提供的 AEM 6.5 是 AEM 6.4 代码库的升级版本。我们对 AEM 6.5 的最新更新让您能够即时访问一些令人激动的改进功能，从而更快地推动您的业务发展。

* [Adobe Experience Manager 6.5 中的新增功能](https://www.adobe.com/marketing/experience-manager/new.html)
* [Adobe Experience Manager 6.5 发行说明](https://helpx.adobe.com/experience-manager/6-5/release-notes.html)

**Cloud Manager 2019.4.0**

最新的 Cloud Manager 版本（2019.4.0，2019 年 4 月 18 日发布）添加了法语、德语和日语的本地化用户界面。此外，还改进了部署步骤。

* [Cloud Manager 2019.4.0 发行说明](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

### 产品维护

**AEM 6.4.4.0**

AEM 6.4 Service Pack 4（6.4.4.0，2019 年 4 月 4 日发布）是一项重要的更新，其中包括自 2018 年 4 月全面推出 AEM 6.4 以来发布的面向客户的多项关键修复。

[AEM 6.4 Service Pack 发行说明](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
[AEM Forms 版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM S3 Connector**

2019 年 6 月 24 日停止支持 Signature Version 2 之后，由于 S3 访问失败，使用旧版 S3 Datastore 连接器的 AEM 实例可能无法使用。作为一名 AEM 客户，Adobe 建议您验证正在使用的 S3 Datastore 连接器的版本。如有需要，请更新至最新版本。

请参阅[弃用 AWS Signature Version 2 对 Amazon S3 的影响](https://helpx.adobe.com/experience-manager/kb/the-impact-of-aws-signature-version-2-deprecation-for-amazon-s3.html)

### 自助

**实现您的 AEM 站点代码库现代化**

了解如何利用最新AEM技术使AEM Sites代码库现代化。 [使现有Adobe Experience Manager Sites代码库现代化](https://expleague.azureedge.net/labs/L761/index.html)

**AEM 富文本编辑器 – Deep Dive**

了解有关在 AEM 中使用富文本编辑器和丰富配置的最佳实践。

[AEM 富文本编辑器 (RTE) Deep Dive](https://helpx.adobe.com/experience-manager/kt/eseminars/gems/AEM-Rich-Text-Editor-RTE-Deep-Dive1.html)

### 其他资源

* [AEM 6.5 学习和支持主页](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 学习与支持主页](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 学习与支持主页](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 学习与支持主页](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager 用户指南](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [更早版本的 AEM 文档](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Scene7 发布系统发行说明](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre 发行说明](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## Campaign {#ac}

Adobe Campaign 提供了一种直观、自动的方式，以通过在线和离线营销渠道来交付一对一的消息。您现在可以利用根据客户习惯和喜好所决定的体验，来预测客户的需求。

* Campaign Classic18.10.4-构建8983
* Campaign Classic18.10.5-构建8984

有关修复和改进，请参阅 [Adobe Campaign Classic 发行说明](http://docs.campaign.adobe.com/doc/AC/en/RN.html)。

有关产品文档，请参阅：

* Adobe Campaign Standard：[文档](https://helpx.adobe.com/support/campaign/standard.html) - [发行说明](https://helpx.adobe.com/campaign/standard/rn/using/release-notes.html) - [专题视频](https://helpx.adobe.com/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic：[文档](https://helpx.adobe.com/support/campaign/classic.html) - [发行说明](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [专题视频](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html)

## Advertising Cloud {#adcloud}

| 功能 | 描述 |
| -----------| ---------- |  
| 搜索工具 | （拥有 Google Ads 帐号的广告商）Advertising Cloud 可以选择将其跟踪的所有转化数据上传到 Google Ads，这些数据是使用 Advertising Cloud 转化跟踪服务的 Google Ads 营销活动的跟踪数据。每日上传包含使用广告商级别的归因模型定义的转化值。所有上传的转化都以“Adobe_ACS_”作为前缀（例如，“Adobe_ACS_Subscriptions”表示“Subscriptions”转化）。 <br/> **注意：**上传内容不包含从馈送文件上传到 Advertising Cloud 的转化数据。 |
| 搜索促销活动 | **“搜索”** &gt; **“营销活动** ”&gt; **“营销活动”** 中的菜单现在为层次结构，并通过帐户下的营销活动进行分类；营销活动下的广告组；关键字(带有子菜单)、广告、产品组(仅限实时视图)、占位符(带有子菜单)和广告组下的自动目标。<br/>在实时视图中，受众和扩展与帐户同级，并具有自己的子菜单。 |

## Target Standard/Premium 19.5.1 {#target}

这个版本包括以下功能、变化和增强功能：

（括号中的问题编号供 Adobe 内部使用。）

### 功能更新

| 功能/增强 | 描述 |
| --- | --- |
| 单页应用程序 Visual Experience Composer (SPA VEC) | SPA VEC 包含以下增强功能，可让您更快捷、更高效地完成工作：<ul><li>现在，您可以取消在 VEC 中加载网站，从而取消阻止活动编辑。此增强功能非常有用，例如，如果您要对活动稍作编辑、查看其设置或添加自定义代码，并且您不想等待网站加载，则可以使用此功能。(TGT-33872)</li><li>在 VEC 中加载页面之前，或者即使页面无法完全加载（例如，自定义代码不再可操作），您可以执行许多操。网站加载之前无法编辑的操作会在 Target UI 中禁用。（TGT-33851 和 TGT-34149）</li></ul> |
| 自动个性化 (AP) 活动和自动定位活动 | 在创建 AP 或自动定位活动时，您可以选择要用作控件的体验。通过这项功能，您可以根据活动中配置的流量分配百分比，将整个控制流量路由到特定体验。然后，您可以根据控制体验评估个性化交付的性能。(TGT-26572) |
| 推荐 | 在创建“最近查看的项目”逻辑时，您可以使用“推荐以前购买的项目”切换。(TGT-34030) |

### 增强功能、修复和更改

* 当您在 VEC 中取消载入页面后，系统会正确地显示出工具栏图标。如果某些特定的操作只有在完全载入页面后才能执行，那么相关的工具栏图标将会禁用。(TGT-33811)
* 现在，您可以更轻松地列出并浏览资产选取器中的选件文件夹，而不是浏览平面文件夹层次结构。(TGT-33725)

请参阅 [Adobe Target 发行说明](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html)，了解有关下列产品的最新发行信息：

* Target Standard 和 Premium
* Recommendations Classic

## Magento {#magento}

Magento 是一个电子商务平台，可为在线商家提供灵活方便的购物车系统，并控制其在线商店的外观、内容和功能。Magento 提供有开源版本和功能更全面的商业版本。

Magento Commerce 是 Adobe Commerce Cloud 的一部分，它为 B2C 和 B2B 体验提供了一个具有企业级能力、无限可扩展性和开源灵活性的电子商务解决方案

开源版本和商业版本的发行说明都可以在[版本信息](https://devdocs.magento.com/guides/v2.3/release-notes/bk-release-notes.html)页面上找到。

## Primetime {#primetime}

Adobe Primetime 是一个多屏幕电视平台，可以帮助媒体公司打造一种完美的个性化观看体验，并从中盈利。

[Primetime 发行说明](http://help.adobe.com/en_US/primetime/release_notes/index.html)
[Primetime 帮助主页](http://help.adobe.com/en_US/primetime/)