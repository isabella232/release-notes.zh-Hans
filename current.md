---
title: Adobe Experience Cloud 发行说明
description: Experience Cloud 发行说明模板
doc-type: 发行说明
last-update: 2019 年 5 月
author: mfrei
translation-type: tm+mt
source-git-commit: 4dd5facd0c7c7088f177285fe04991254da17ff9

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
| [!DNL AppMeasurement Version 2.14.0] <ul><li>修复了在等待多个点击时，跟踪器参数状态管理的问题。(AN-176931，AN-176629，DTM-12758)</li><li>更新了AppMeasurement以包含访客. js4.3.0(AN-180049)</li></ul> |
| [!DNL Analysis Workspace]: 新增“包含重复实例”__流量可视化图表设置 | “包含重复实例”__流量设置使您可以选择包含还是排除重复实例，例如页面重新载入。此外，所有流量可视化图表现在仅基于实例。 |
| [!DNL Ad Hoc Analysis]: 与 Java 11 兼容 | 现在，Ad Hoc Analysis 已与 Java 11 兼容。了解如何在 [Java11上运行Ad Hoc Analysis](https://marketing.adobe.com/resources/help/en_US/dsc/adhoc-java.html)。 |
| **数据收集：** 新的s_ ecid cookie | 新增了第一方服务器 s_ecid Cookie，其中的数据收集用于存储访客的 ECID。 |

**Analysis Workspace 修复**

* 修复了影响页面逗留 **[!UICONTROL 时间的问题]**。[!DNL Analysis Workspace]在计算逗留时间分段时， 报表将不再使用“页面名称”，从而可以计算粒度和分段统计的网页点击数。**[!UICONTROL ]****[!UICONTROL ]**(AN-140479)
* 固定线可视化性能问题，作为提高 [!DNL Analysis Workspace] 性能的一部分。(AN-174878)
* 修复了下载的 .csv 文件中缺少 UTF-8 编码的问题。(AN-178393)
* 修复了项目性能缓慢 [!DNL Analysis Workspace] 的问题。(AN-177710)
* 修复了折线可视化图表由于 Y 轴的粒度范围较小而出现的显示问题。(AN-176467)

**其他 Analytics 修复**

* [!DNL Audience Analytics]：修复了在受众名称发生更改 [!DNL Audience Manager (AAM)] 后，更新的名称未反映在Audience Analytics中的问题。(AN-176237)
* 修复了阻止用户保存[！DNL Analytics细分 [!DNL Audience Manager]。这个问题是由名称中混有大小写字符的现有 AAM 文件夹引起的。现在，我们按不区分大小写来处理所有文件夹以便进行同步。(AN-177934)
* 修复了在用户登录到 [!DNL Analytics] 然后会话超时 [!DNL Experience Cloud] 时发生的问题。恢复会话时，用户被重定向到错误的 URL。(AN-176812)
* 修复了请求中 [!DNL Data Warehouse] 时区偏移的问题。(AN-177585)

### Analytics 管理员的重要注意事项 {#aa-notices}

| 注意 | 添加或更新日期 | 描述 |
| -----------| ---------- | ---------- |
| 即将支持 **[!UICONTROL 日期和]****[!UICONTROL 数值分类的支持更改]** | 更新日期：2019 年 5 月 28 日 | 已从代码库中移除了导入数字 2 分类和启用日期的分类的功能。此更改将在2019年月维护版本生效。如果您的导入文件中包含“数字”或“启用日期”列，则这些单元格会被静默忽略，同时该文件中的任何其他数据均会正常导入。<br/>现有的分类仍可以通过标准分类工作流程导出，并将继续在报表中可用。 |
| 即将更改“报表总数”计算__ | 更新日期：2019 年 5 月 2 日 | 在 **2019 年 6 月 13 日**，Adobe Analytics 将以一致的方式处理所有维度和量度中的“报表总数”__计算。这将导致某些报表（通常为 Prop 或客户属性报表）的总数发生更改。在进行此项更改之前，无论“未指定”__是否显示在报表中，某些报表总数都会不一致地在总数中包含或排除“未指定”__行项目。<br/>自 2019 年 6 月 13 日开始，“未指定”__将始终显示在报表总数中，即使它在报表中未显示为行项目也是如此。此外，在进行此项更改之后，对于某些维度，使用“存在”__或“不存在”__逻辑的区段可能会显示不同结果。此更改将影响 Analysis Workspace、Reports &amp; Analytics、Ad Hoc Analysis、Report Builder 和报表 API。 |
| 更新到CSV下载 [!DNL Analysis Workspace] | 2019 年 4 月 10 日 | 从2019年月11日开始， **[!UICONTROL 对CSV下载]** (和 **[!UICONTORL 复制到剪贴板]**)进行了多次更改，从 [!DNL Analysis Workspace] 导出的数据中删除格式。  <ul><li>千分分隔符不再包含。小数分隔符将继续包含在内，并将遵循**[!UICONTROL 组件 &gt; 报表格式 &gt; 千位分隔符]**下定义的格式。注意：使用逗号作为小数分隔符的数值将会继续在导出的 CSV 中引用。</li><li>不会显示任何货币符号。</li><li>不会显示任何百分比符号。百分数将以小数形式显示。例如，75% 将表示为 0.75。</li><li>时间将以秒为单位显示。</li><li>同类群组表将只显示原始值；百分比将被删除。</li><li>如果数字无效，将显示空单元格。</li></ul> |
| 即将更改 [!DNL Analysis Workspace] 的调试器命令 | 2019 年 4 月 4 日 | 打开 [!DNL Analysis Workspace] 调试器的控制台命令将于2019年 **月13日更改为** AdobeTools. debug. includeOberXML。adobe.tools.debug.includeOberonXml 命令将于该日期之后停止运行。 |
| 移动浏览器版本号 | 2019 年 2 月 7 日 | 从 2019 年 1 月 8 日开始，我们将移动浏览器版本号的截断级别从 2 更改为 1。在该日期之后，版本号将只显示前两个级别（例如 _Firefox 64.0.2_ 现在报告为 _Firefox 64.0_）。 |
| 生命周期结束 [!DNL Ad Hoc Analysis] | 2019 年 1 月 29 日 | Adobe于2018年月日宣布有意终止生命 [!DNL Ad Hoc Analysis]。确定终止日期后，Adobe 会立即与大家共享此信息。<br/>有关更多信息（包括在此期间将兼容的 Java 版本），请访问[探索工作区](https://adobe.ly/discoverworkspace)。 |
| 简短 Analytics 报表链接 | 2019 年 1 月 14 日 | 系统将从 2019 年 1 月 17 日星期四开始按照滚动计划表清理和删除任何在一年内未被访问过的简短 Analytics 报表链接。 |
| 停止对 TLS 1.0 的支持 | 更新日期：2019 年 1 月 10 日 | 自 2019 年 2 月 11 日起，Adobe Analytics 报表不再支持 TLS（传输层安全性）1.0 加密。这一更改体现了我们为维持最高安全标准和提升客户数据安全性所做的不懈努力。如果您在2019年月11日之后无法连接到Adobe Analytics报告，则应将浏览器升级到 [最新版本](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html)。<br/>自 2019 年 2 月 20 日起，Adobe Analytics 数据收集不再支持 TLS 1.0。在实施此次更改后，如果最终用户使用不支持 TLS 1.1 或更高版本的旧设备或 Web 浏览器，Adobe 将不再从这些用户那里收集 Analytics 数据。我们希望这不会对客户数据或报表产生重大影响。（如果您的网站已不支持 TLS 1.0，则不会受到影响。）<br/>从 2019 年 4 月 11 日开始，Adobe Analytics 报表 API 不再支持 TLS 1.0 加密。访问该 API 的客户应当确认他们不会受到影响。 <ul><li>在默认设置下使用 Java 7 的 API 客户端将需要[做出修改才能支持 TLS 1.2](https://www.java.com/en/configure_crypto.html)。（请参阅“更改客户端端点的默认 TLS 协议版本：将 TLS 1.0 更改为 TLS 1.2”。__） </li><li>使用Java的API客户端不应受到影响，因为默认设置为TLS1.2。</li><li> 使用其他框架的 API 客户端将需要联系各自的供应商来获取有关 TLS 1.2 支持的详细信息。</li></ul> |
| 数据馈送：post_product_list 列 - 大小更改 | 2019 年 1 月 9 日 | 2019 年 2 月 7 日，Adobe 将 post_product_list 列的大小从 64 KB 扩展到 16 MB。此更改可确保在处理过程中添加到post_ product_ list的推销eVar值不会截断产品和收入值。如果您的流程需要获取 post_product_list 值，请确保这些流程可以处理长度最大为 16 MB 的值，否则会将值截断为 16 KB，以避免数据获取失败。 |
| 影响非活动 [!DNL Analytics Live Stream] 端点的管理更改 | 2018 年 12 月 20 日 | 自2019年月日起，可能禁用90天无活动消费者连接的 [!DNL Live Stream] 端点。您可以联系客户服务部门来查询您 [!DNL Live Stream] 的端点，如果有必要，可以重新启用它们。此外，请确保您的客户进程按照服务设计要求保持持久连接，并在连接断开或中断时实施重新连接。 |
| 由于对 TLS 1.0 的支持终止而更新 Adobe [!DNL Report Builder] | 2018 年 9 月 7 日 | 由于TLS1.0支持结束，我们建议 [!DNL Report Builder] 用户在2019年月之前下载版本v5.6.21。在该日期之后，旧版本 [!DNL Report Builder] 将不再起作用。 |

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

* Target Standard和Target Premium
* Recommendations Classic

## Magento {#magento}

Magento 是一个电子商务平台，可为在线商家提供灵活方便的购物车系统，并控制其在线商店的外观、内容和功能。Magento 提供有开源版本和功能更全面的商业版本。

Magento Commerce 是 Adobe Commerce Cloud 的一部分，它为 B2C 和 B2B 体验提供了一个具有企业级能力、无限可扩展性和开源灵活性的电子商务解决方案.

可在 [“发行信息](https://devdocs.magento.com/guides/v2.3/release-notes/bk-release-notes.html) ”页面上找到我们的Open Source和Commerce版本的发行说明。

## Primetime {#primetime}

Adobe Primetime 是一个多屏幕电视平台，可以帮助媒体公司打造一种完美的个性化观看体验，并从中盈利。

[Primetime 发行说明](http://help.adobe.com/en_US/primetime/release_notes/index.html)
[Primetime 帮助主页](http://help.adobe.com/en_US/primetime/)