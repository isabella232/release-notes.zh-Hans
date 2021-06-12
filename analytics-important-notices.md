---
title: Analytics 管理员的重要注意事项
description: Experience Cloud 发行说明
doc-type: release notes
last-update: March 2019
author: mfrei
source-git-commit: 0d8d7c330a0d74768a255e765721b88abcc86a5a
workflow-type: tm+mt
source-wordcount: '2264'
ht-degree: 77%

---


# Analytics 管理员的重要注意事项 {#aa-notices}

| 注意事项 | 添加或更新日期 | 描述 |
| -----------| ---------- | ---------- |
| 即将更改对“启用日期”和“数字”分类的支持 | 2019 年 2 月 28 日 | 已从代码库中移除了导入数字 2 分类和启用日期的分类的功能。此更改将随2019年6月维护版本的发布而生效。 如果您的导入文件中包含“数字”或“启用日期”列，则这些单元格会被静默忽略，同时该文件中的任何其他数据均会正常导入。<br/>现有的分类仍可以通过标准分类工作流程导出，并将继续在报表中可用。 |
| 显著更新了有关 getPercentPageViewed 插件的文档。 | 2019 年 2 月 12 日 | [https://experiencecloud.adobe.com/resources/help/zh_CN/sc/implement/getPercentPageViewed.html](https://experiencecloud.adobe.com/resources/help/zh_CN/sc/implement/getPercentPageViewed.html) |
| 管理员>一般帐户设置 | 2019 年 2 月 7 日 | * 对于 2019 年 1 月之后在伦敦数据中心创建的任何新报表包，默认情况下会启用&#x200B;_将 IP 地址的最后八位字节替换为 0_ 设置，但前提是这些报表包的设置是从 Admin Console 中列出的模板复制的。设置复制自其他报表包的报表包将继承选定报表包的所有设置。<br/> * 对于设置了报表包的所有 EMEA 客户，默认情况下将不再启用 _IP 模糊处理_&#x200B;设置。 |
| 移动设备浏览器版本号 | 2019 年 2 月 7 日 | 从2019年1月8日开始，我们将移动浏览器版本号的截断级别从2更改为1。 从那天起，版本仅显示前两个级别(例如，_Firefox 64.0.2_&#x200B;现在报告为&#x200B;_Firefox 64.0_)。 |
| Ad Hoc Analysis 生命周期终止 | 更新日期： 2019年1月29日 | 2018 年 8 月 6 日，Adobe 宣布计划终止 Ad Hoc Analysis 生命周期。确定终止日期后，Adobe 会立即与大家共享此信息。<br/>有关更多信息（包括在此期间将兼容的 Java 版本），请访问[探索工作区](https://adobe.ly/discoverworkspace)。 |
| 短Analytics报表链接 | 2019 年 1 月 14 日 | 系统将从2019年1月17日星期四开始按照滚动计划表清理和删除任何在一年内未被访问过的简短Analytics报表链接。 |
| 停止支持 TLS 1.0 | 更新日期： 2019年1月10日 | 2019 年 2 月 11 日，Adobe Analytics 报表将不再支持 TLS（传输层安全性）1.0 加密。这一更改体现了我们为维持最高安全标准和提升客户数据安全性所做的不懈努力。如果您在 2019 年 2 月 11 日后无法连接 Adobe Analytics 报表，则应将您的浏览器升级到[最新版本](https://experienceleague.adobe.com/content/help/en/analytics/admin/sys-reqs.html)。<br/>从 2019 年 2 月 20 日开始，Adobe Analytics 数据收集将不再支持 TLS 1.0。在实施此次更改后，如果最终用户使用不支持 TLS 1.1 或更高版本的旧设备或 Web 浏览器，Adobe 将不再从这些用户那里收集 Analytics 数据。我们希望这不会对客户数据或报表产生重大影响。（如果您的网站已不支持 TLS 1.0，则不会受到影响。）<br/>从 2019 年 4 月 11 日开始，Adobe Analytics 报表 API 将不再支持 TLS 1.0 加密。访问该 API 的客户应当确认他们不会受到影响。<br/>* 在默认设置下使用 Java 7 的 API 客户端将需要[做出修改，才能支持 TLS 1.2](https://www.java.com/en/configure_crypto.html)。（请参阅“更改客户端端点的默认 TLS 协议版本：将 TLS 1.0 更改为 TLS 1.2”。__）<br/>* 使用 Java 8 的 API 客户端应当不会受到影响，因为其默认设置为 TLS 1.2。<br/>* 使用其他框架的 API 客户端将需要联系各自的供应商来获取有关 TLS 1.2 支持的详细信息。 |
| 由于对 TLS 1.0 的支持终止而更新 Adobe Report Builder | 2018 年 9 月 7 日 | 由于对 TLS 1.0 的支持即将终止，我们建议 Adobe Report Builder (ARB) 用户在 2019 年 2 月 7 日之前下载 ARB v5.6.21。**在该日期之后，以前版本的 ARB 将无法再正常使用。** |
| 更新从 Analysis Workspace 下载 CSV 时的操作 | 2019 年 1 月 9 日 | 从2019年2月7日开始，从Analysis Workspace下载CSV（和复制到剪贴板）时，将不再包含千位分隔符。 注意：Analysis Workspace UI 将继续显示千位分隔符。此外，小数分隔符将继续包含在内，并将遵循&#x200B;**[!UICONTROL 组件]** > **[!UICONTROL 报表设置]** > **[!UICONTROL 千位分隔符]**&#x200B;下定义的格式。 |
| 数据馈送：post_product_list列 — 大小更改 | 2019 年 1 月 9 日 | 2019年2月7日，Adobe计划将post_product_list列的大小从64 KB扩展到16 MB。 此更改旨在确保处理过程中添加到 post_product_list 的推销 eVar 值不会导致产品和收入值截断。如果您的流程需要提取 post_product_list 值，请确保这些流程可以处理长度最大为 16 MB 的值，否则系统将按照 16 KB 的长度将该值截断，以避免数据获取失败。 |
| 影响不活动Analytics实时流端点的管理更改 | 2018 年 12 月 20 日 | 从 2019 年 2 月 1 日开始，可能会禁用持续 90 天没有活动客户连接的实时流端点。您可以联系 客户关怀团队查询您的实时流端点，并在必要时重新启用它们。此外，请确保您的客户进程按照服务设计要求保持持久连接，并在连接断开或中断时实施重新连接。 |
| 达拉斯 FTP 服务器迁移 (ftp2.omniture.com) | 2018 年 10 月 19 日 | 在 2018 年 10 月 23 日，如果您通过 SFTP 协议连接到 ftp2.omniture.com，则可能需要重新接受 SJ1 站点的主机标识符。此问题仅在 10 月 23 日出现。请参阅[升级 Adobe FTP 服务器](https://experienceleague.adobe.com/content/help/en/analytics/export/ftp-and-sftp/ftp-upgrade.html)。 |
| 更新“移动设备”维度 | 2018 年 10 月 16 日 | 9月26日，Adobe将其设备查找更新为Device Atlas的2.1 API。 这会导致更详细的设备（例如Apple iPhone 7、Apple iPhone 8 Plus等） 显示在某些浏览器的“移动设备”维度中。 此新级别的设备详细信息应当定向使用，因为目前并不扩展到所有设备和浏览器类型。 |
| 停止对 Internet Explorer 11 的支持 | 2018 年 9 月 12 日 | Adobe将于2018年11月13日，停止在Adobe Analytics中支持Internet Explorer 11。 请尽快切换到Microsoft Edge或其他受支持的浏览器。 |
| Ad Hoc Analysis 生命周期终止 | 2018 年 9 月 8 日 | 2018 年 8 月 6 日，Adobe 宣布计划终止 Ad Hoc Analysis 生命周期。确定终止日期后，Adobe 会立即与大家共享此信息。有关更多信息，请参阅[探索工作区](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)。从现在开始，我们将不再修改 [!UICONTROL Ad Hoc Analysis]，进而不支持 Java 9 及以上版本。如果您升级到 Java 9 及以上版本，[!UICONTROL Ad Hoc Analysis] 将停止运行。仅支持 Java 8。 |
| 由于对 TLS 1.0 的支持终止而更新 Adobe [!UICONTROL Report Builder] | 2018 年 9 月 7 日 | 由于对 TLS 1.0 的支持即将终止，我们建议 [!UICONTROL Report Builder] (ARB) 用户在 2019 年 2 月之前下载 ARB v5.6.21。在该日期之后，以前版本的 ARB 将无法再正常使用。 |
| 适合 Analytics 用户迁移的新帮助 | 2018 年 5 月 10 日 | 我们更新了 Analytics 用户 ID 迁移帮助中有关将 Enterprise ID 和 Federated ID 迁移到 Admin Console 的信息。请参阅[为 Enterprise ID 和 Federated ID 迁移 Analytics 用户帐户](https://experienceleague.adobe.com/content/help/en/analytics/admin/user-product-management/user-management/migrate-users/c-migration-tool.html)。 |
| 即将删除“帐户活动报表” | 2018 年 5 月 10 日 | 在Adobe Analytics夏季版本中，“帐户活动报表”将被替换为“服务器调用使用情况”功能。 帐户活动报表将于2018年8月9日永久删除。 要在2018年8月9日之后查看有关报表包流量的概要数据，请使用“服务器调用使用情况”功能。 |
| 关于计算量度中线性分配模型的更改 | 生效日期：2018 年 7 月 19 日 | 7 月 19 日，Adobe Analytics 将修改计算量度中分配模型的评估方式。作为此更改的一部分，使用非默认分配模型的计算量度将迁移至改进的新归因模型。[!UICONTROL 营销渠道最近联系]和[!UICONTROL 营销渠道首次联系]分配模型将分别迁移至新的[!UICONTROL 最近联系]和[!UICONTROL 首次联系]归因模型。（并未弃用[!UICONTROL 营销渠道]，仅弃用了计算量度中的上述两个分配模型）。此外，我们将更正线性分配的计算方式。如果您使用计算量度的线性分配模型，则报表可能会稍有变化，反映更正后的新归因模型。计算量度的这一更改将反映在 [!UICONTROL Analysis Workspace]、[!UICONTROL Reports &amp; Analytics]、[!UICONTROL 报表 API]、[!UICONTROL Report Builder] 和 [!UICONTROL Ad Hoc Analysis] 中。有关此更改的更多信息，请参阅[计算量度](https://experienceleague.adobe.com/content/help/en/analytics/components/calculated-metrics/calcmetric-workflow/m-metric-type-alloc.html)文档。 |
| [!UICONTROL 异常检测]和[!UICONTROL 贡献分析]功能已从 [!UICONTROL Reports &amp; Analytics] 中删除 | 2018 年 4 月 10 日 | 异常检测和贡献分析已从 Reports &amp; Analytics 功能集中删除，现在只能通过 Analysis Workspace 使用。Adobe Analytics Select 和 Foundation 客户只能访问 Workspace 中的“每日粒度”异常检测。 |
| Adobe 不再发布适用于 Safari 的第三方 s_vi Cookie | 2018 年 4 月 5 日 | 2018 年 3 月 20 日，Adobe 停止了发布适用于 Safari 浏览器的第三方 s_vi Cookie。此变更不会影响使用第一方数据收集 Cookie 的客户。此更改还消除了某些客户因Safari ITP而出现的访问和访客虚增的情况。 |
| 在将用户 ID 迁移至 Admin Console 之前更新 Report Builder | 2018 年 3 月 17 日 | **重要：**&#x200B;将安装的 Report Builder 更新至最新版本。此更新是从 2018 年 4 月开始将 Analytics 用户 ID 迁移至 Admin Console 的先决条件。有关迁移信息，请参阅[将 Analytics 用户迁移至 Admin Console]。 |
| 影响报表的后端变动 | 2018 年 4 月 11 日 | （后端）查找机制的变动将会从多方面影响报表。请注意，以下变动已大约在 2018 年 2 月底生效：不再允许对页面进行重命名。将来，您需要使用分类来重命名页面。在2018年5月10日版本发布之前，系统将继续按照当前配置的重命名页面来处理这些页面。 Adobe要求所有客户在该日期之前迁移到分类。 5 月版本发布后，现有的重命名将不再有效，并且可能会进行逆向更改，恕不另行通知。<br> <br>URL“替换”方法发生变化。以前，Adobe Analytics 每月存储的（通常）是每个页面名称关联的第一个 URL。将来，我们存储的是每个页面名称的最新 URL。（更新日期：2018 年 4 月 11 日）Reports &amp; Analytics 中不再提供汇总数据和当前数据的类别报表。Web Service API 中的类别汇总报表将在 2018 年 5 月 10 日的 Adobe Analytics 维护版本中弃用。不再支持大约于 2007 年（某些情况下是 2006 年）1 月之前生成的页面/prop 数据。这项措施只影响页面、prop 和页面事件（即，自定义链接、退出链接、下载链接）。注意：此项更改不影响 Analysis Workspace 或 Data Warehouse 中的报表。如果您拥有这些日期之前的数据，预计会出现以下情况：以 2007 年 1 月为分界线，此前的数据与此后的数据将不能正确合并。将无法搜索大约在 2007 年 1 月之前生成的数据。 |
| 即将更改对“启用日期”和“数字”分类的支持 | 2018 年 5 月 7 日 | 在 2018 年 5 月 10 日维护版本中，我们将开始限制启用日期和数字分类的功能。这些分类类型将从管理员和分类导入程序界面中删除。从那天起，将无法添加新的启用日期和数字分类。现有的分类仍可以通过标准分类工作流程进行管理（上传、删除），并且可以继续在报表中使用。 |
| 即将更改对营销渠道成本和预算的支持 | 2018 年 2 月 28 日 | 在 4 月维护版本中，我们将从管理员 > 营销渠道菜单中移除“营销渠道成本和预算”。无法添加新的成本和预算数据。 现有成本和预算数据将继续在报表中可用，但无法更新。 |
| 代码管理器 - 旧版 H 代码 | 2018 年 2 月 8 日 | 不再支持从代码管理器下载旧版 JavaScript（H 代码）。 |
| 数据保留：检查并设置您的 Adobe Analytics 数据保留策略 | 2018 年 2 月 1 日 | **背景：**&#x200B;欧盟的《通用数据保护条例》(GDPR) 将于 2018 年 5 月 25 日正式生效。根据该条例的规定，Adobe 作为您的数据处理提供商，必须要采取适当的措施来协助客户实现个人请求的访问、删除数据等操作。“运用适当、安全和及时的删除策略”是履行此项职责的重要部分。因此，Adobe希望与您合作，在GDPR于2018年5月25日生效之前，实施数据保留策略。<br> <br>**期待完成的任务：**&#x200B;除非您已经实施 Adobe Analytics 数据保留策略，否则在没有其他安排的情况下，Adobe 将按照与客户签署的 Adobe Analytics 合同中的当前规定，开始应用数据保留。大多数Adobe Analytics合同都声明Adobe在25个月后可能会删除数据。 为贵组织制定数据保留策略后，将按月滚动实施该策略。 如果数据保留时间超过25个月，则需支付额外费用。 此外，还可以通过联系客户关怀团队来配置较短时间的数据保留期。 您很快就会收到一封电子邮件，其中包含贵组织的其他详细信息。<br> <br>数据保留会影响所有访问 Adobe Analytics 历史数据的方法，其中包括但不限于 Reports &amp; Analytics、Analysis Workspace、Report Builder、Web 服务报表 API、Data Warehouse 和数据馈送。**后续步骤：**&#x200B;确定贵公司内负责数据保留策略的利益干系人。贵公司最清楚应当保留 Adobe Analytics 数据的适当期限。如果您对Adobe Analytics的数据保留存有任何疑问，请联系您的Adobe客户成功经理。 |
| 用户帐户链接 | 2017 年 10 月 26 日 | Analytics 用户无需继续在 Experience Cloud 与 Analytics 之间手动链接其帐户。用户可以联系 Admin Console 管理员以请求获取 Analytics 访问权限。通过 Analytics 用户 ID 迁移，管理员可以轻松地将用户帐户从 Analytics“用户管理”迁移到 Adobe Admin Console。迁移用户后，他们将能够访问 Experience Cloud 中提供的已购解决方案与核心服务。[进一步了解 Analytics 用户 ID 迁移](https://experienceleague.adobe.com/content/help/en/analytics/admin/user-product-management/user-management/migrate-users/c-migration-tool.html)。 |