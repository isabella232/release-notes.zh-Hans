---
title: Adobe Experience Cloud 发行说明
description: Experience Cloud 发行说明模板
doc-type: 发行说明
last-update: 2019年月
author: mfrei
translation-type: tm+mt
source-git-commit: fdcc0f53ea326b9c440e511ca5968749e68861cd

---


# 早期访问-2019年月- Experience Cloud发行说明

Adobe Experience Cloud 的新增功能和修复。

>[!IMPORTANT]
>
>此页面包含预发行内容，并且可能在2019年月12日发布之前进行更改。

>[!NOTE]
>
>Subscribe to the [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. 您将在版本发行前的三到五个工作日收到通知。对于发行之后发布的新信息，将使用发布日期进行标记。

## 发行日期：2019 年 9 月 12 日

* [Experience Cloud 界面](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (链接到解决方案帮助)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (链接到解决方案帮助)

## Experience Cloud 界面 {#ecloud}

Experience Cloud界面和产品管理的发行说明。

* 修复了一个安全漏洞，以包含建议的HTTP头。(MCUI-9942)
* 修复了在Analytics登录公司之间切换的问题。(MCUI-10049)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

## Experience Platform {#platform}

Experience Platform、Experience Platform Launch、Identity Service和安全公告的发行说明。

* [Experience Platform Launch](#launch)
* [Mobile Services 和 Mobile SDK](#mobile)
* [安全公告和建议](https://helpx.adobe.com/security.html) (所有Adobe产品)

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

### Mobile Services 和 Mobile SDK {#mobile}

Release Date: **September 26th**

**iOS(4.18.8)**

* 修复了在每次Analytics调用上将SDK数据同步到成对WatchOS应用程序的错误。
* 修复了推送点进有效负荷无法用作应用程序内消息传递特征的错误。
* 更新至用户通知框架API，而不是UILocalNotification API，从iOS10开始已弃用。
* 更新至WKWebView而不是UIWebView，从iOS12开始已弃用。

**Android4.17.10**

* 增加了对BCP47语言标签的支持。

**Unity**

* 适用于iOS的插件以及适用于Android的4.17.9更新

## [!DNL Analytics] {#analytics}

Adobe Analytics 中的新增功能和修复：

* [Adobe Analytics 中的新增功能、增强功能和修复](#aa-features)
* [Analytics 管理员的重要注意事项](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Adobe Analytics 中的新增功能、增强功能和修复 {#aa-features}

| 功能 | 描述 |
| -----------| ---------- |  
| **旅程IQ：跨设备分析** | Adobe Analytics在2019年月推出了一项称为旅程IQ的强大功能：跨设备分析。(请注意，此功能仅适用于Analytics Ultimate客户。)跨设备分析(CDA)将Adobe Analytics从以设备为中心的设备转变为以人为中心的分析工具。使用CDA，您可以回答诸如以下问题的问题： <ul><li>有多少人与我的品牌互动？他们使用多少种设备？它们如何重叠？</li><li>人们在移动设备上开始任务的频率如何，然后后来移动到桌面PC以完成任务？在一台设备上登陆的营销活动点击是否会导致转换其他位置？</li><li>如果我考虑跨设备旅程，我如何理解营销活动有效性？我的漏斗分析如何改变？</li><li>用户从一台设备到另一台设备的最常用路径是什么？他们在哪里放弃？他们在何处取得成功？</li><li>具有多种设备的用户的行为如何与使用单个设备的用户不同？</li></ul><br/>要了解更多信息，请访问 [adobe.ly/aacda](https://spark.adobe.com/page/8ZpjsX6Lp5XTM/)。 |
| **更新的分类体系结构** | 从九月份开始，对分类架构的更新将在几个月内向客户迁移。月发行版包括少数较早者的迁移。<br/>更新大幅缩短了导入/摄取和提供用于报告的上传(包括规则逻辑)所花费的时间。 |

#### 修复

* 修复 [!UICONTROL 了用户] 和 [!UICONTROL 选件] 核心服务无法从Experience Cloud菜单访问的问题。(AN-184294)
* 修复 [!UICONTROL 了Analysis Workspace中的左边栏] 在有滚动条和没有滚动条的情况下发生摇晃的问题，这造成了一个流畅的效果。(AN-183904)
* 修复了错误报告问题。您将开始看到更多特定的错误消息，而不仅仅是红色错误指示符。更具体而言，它应该帮助您了解问题由重载、错误或创建过于复杂的报告请求造成的。(AN-184135) [更多…](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/optimizing-performance.html)
* 修复了阻止成功下载格式报告 `.pdf/.xls/.rtf` 的问题。(AN-183165)
* 修复了通过Experience Cloud登录并切换到不同Experience Cloud解决方案或切换到其他登录公司的问题。(AN-183376)
* 修复了资产转让无法正常工作的问题。用户组现在在 [!UICONTROL Admin Console] 中进行管理，因此我们不会在用户转移资产时在用户之间复制它们。(AN-183751)
* 修复了删除所有者已被删除的计划报告的问题。从现在起，当计划所有者不再存在时，通知将转至管理员(执行删除操作的人员)。(AN-181000)

### [!DNL Analytics] 管理员的重要注意事项 {#aa-notices}

| 注意 | 添加或更新日期 | 描述 |
| -----------| ---------- | ---------- |
| 更新到Analysis Workspace自由表总数 | 2019年月12日 | 在2019年10月，自由表格总行数将开始计算应用的 [报告过滤器](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) 。迄今为止，总数仅表示分段。在此更改中，依赖可视化将更新(例如，链接 [!UICONTROL 的摘要编号] 可视化)以及导出的CSV和PDF数据。 |
| 针对Analytics用户 `createDate` 领域即将发生的变化 | 2019 年 30 月 8 日 | 在2019年10月或11月，Analytics用户 `createDate` 的字段将从美国太平洋时间更新到包含时区信息的正确格式化的日期/时区。(AN-183468) |
| 支持历史时区偏移 | 2019 年 8 月 8 日 | Analytics 现在将自动为带有时间戳的点击处理时区偏移。在 8 月 8 日实施此更改后，载入数据以进行历史处理的系统在发送数据之前将不再需要调整时区偏移。 |
| 分类规则生成器限制 | 添加于 2019 年 6 月 5 日 | These limits are not new, but have been added to the documentation [here](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html). |
| 新的区段运算符限制 | 添加于 2019 年 5 月 31 日 | 从 2019 年 7 月 18 日开始，区段运算符&#x200B;_包含任意_、_不包含任意_、_包含全部_&#x200B;和&#x200B;_不包含全部_&#x200B;将限制为每个输入字段 100 个词。这项限制将适用于此日期之后的所有新增区段和修改区段。超出此限制的现有区段将继续受到支持，但在缩短输入字段前，将无法进行修改或保存。作为我们持续不断努力的一个组成部分，将应用这些限制以提高查询性能。 |
| Support changes for **[!UICONTROL Date-Enabled]** and **[!UICONTROL Numeric 2 Classifications]** | 更新日期：2019 年 5 月 28 日 | 已从代码库中移除了导入数字 2 分类和启用日期的分类的功能。此更改在2019年月维护版本生效。如果您的导入文件中包含“数字”或“启用日期”列，则这些单元格会被静默忽略，同时该文件中的任何其他数据均会正常导入。<br/>现有的分类仍可以通过标准分类工作流程导出，并将继续在报表中可用。 |
| Change to _Report Total_ calculations | 更新日期：2019 年 7 月 9 日 | On **June 18, 2019**, Adobe Analytics made _Report Total_ calculations consistent across all dimensions and metrics. 这导致部分报告(通常是Prop或客户属性报告)的总数发生更改。在进行此项更改之前，无论 _未指定_ 是否显示在报表中，某些报表总数都会不一致地在总数中包含或排除 _未指定_ 行项目。<br/>自 2019 年 6 月 18 日开始， _未指定_ 将始终显示在报表总数中，即使它在报表中未显示为行项目也是如此。此外，进行此项更改之后，使用&#x200B;_存在_&#x200B;或&#x200B;_不存在_&#x200B;逻辑的区段，对于不同的维度可能会看到不同的结果，尤其是其中的&#x200B;_未指定_&#x200B;具有特殊名称（如推荐人类型维度的“已键入/已添加书签”行项目或设备类型维度的“其他”行项目）的维度。此更改将影响 Analysis Workspace、Reports &amp; Analytics、Ad Hoc Analysis、Report Builder 和报表 API。 |
| 更新从 Analysis Workspace 下载 CSV 时的操作 | 2019 年 4 月 10 日 | Starting on April 11, 2019, several changes were made to **[!UICONTROL CSV downloads]** (and **[!UICONTORL Copy to Clipboard]**) from Analysis Workspace to remove formatting from exported data.  <ul><li>千位分隔符将不再包含在内。小数分隔符将继续包含在内，并将遵循 **[!UICONTROL 组件 &gt; 报表格式 &gt; 千位分隔符]**&#x200B;下定义的格式。注意：使用逗号作为小数分隔符的数值将会继续在导出的 CSV 中引用。</li><li>不会显示任何货币符号。</li><li>不会显示任何百分比符号。百分数将以小数形式显示。例如，75% 将表示为 0.75。</li><li>时间将以秒为单位显示。</li><li>同类群组表将只显示原始值；百分比将被删除。</li><li>如果数字无效，将显示空单元格。</li></ul> |
| Analysis Workspace 调试器命令即将变更 | 2019 年 4 月 4 日 | **2019 年 6 月 13 日**，开启 Analysis Workspace 调试器的控制台命令将变为 adobeTools.debug.includeOberonXml。adobe.tools.debug.includeOberonXml 命令将于该日期之后停止运行。 |
| 移动浏览器版本号 | 2019 年 2 月 7 日 | 从 2019 年 1 月 8 日开始，我们将移动浏览器版本号的截断级别从 2 更改为 1。在该日期之后，版本号将只显示前两个级别（例如 _Firefox 64.0.2_ 现在报告为 _Firefox 64.0_）。 |
| 终止 [!DNL Ad Hoc Analysis] 的生命周期 | 2019 年 1 月 29 日 | 2018 年 8 月 6 日，Adobe 宣布计划终止 [!DNL Ad Hoc Analysis] 的生命周期。确定终止日期后，Adobe 会立即与大家共享此信息。<br/>有关更多信息，包括此期间Java的哪些版本将兼容，请访问 [[！DNL Discover Workspace]](https://adobe.ly/discoverworkspace)。 |
| 简短 [!DNL Analytics] 报表链接 | 2019 年 1 月 14 日 | 系统已从 2019 年 1 月 17 日星期四起开始按照滚动计划表清理和删除任何在一年内未被访问过的简短 [!DNL Analytics] 报表链接。 |
| 数据馈送：post_product_list 列 - 大小更改 | 2019 年 1 月 9 日 | 2019 年 2 月 7 日，Adobe 将 post_product_list 列的大小从 64 KB 扩展到 16 MB。这项更改可确保在处理过程中添加到 post_product_list 的推销 eVar 值不会导致产品和收入值截断。如果您的流程需要提取 post_product_list 值，请确保这些流程可以处理长度最大为 16 MB 的值，否则系统将按照 16 KB 的长度将该值截断，以避免数据获取失败。 |
| 影响不活动的 [!DNL Analytics Live Stream] 端点的管理更改 | 2018 年 12 月 20 日 | 从 2019 年 2 月 1 日开始，可能会禁用持续 90 天没有活动客户连接的 [!DNL Live Stream] 端点。您可以联系客户关怀团队查询您的 [!DNL Live Stream] 端点，并在必要时重新启用它们。此外，请确保您的客户进程按照服务设计要求保持持久连接，并在连接断开或中断时实施重新连接。 |
| 由于对 TLS 1.0 的支持终止而更新 Adobe [!DNL Report Builder] | 2018 年 9 月 7 日 |
| 停止支持 TLS 1.0 | 更新日期：2019 年 1 月 10 日 | 不再支持TLS1.0 |

### [!DNL AppMeasurement] {#appm}

请参阅 [AppMeasurement for Javascript发行说明](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html)。

## Audience Manager {#aam}

Audience Manager中的新增功能、增强和修复。

### 新增功能和增强功能 {#aam-features}

| 功能 | 描述 |
| -----------| ---------- |  
| **[[！基于DNL人员的目标]](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/destinations/people-based/people-based-destinations-overview.html)** | [!DNL People-Based Destinations] 是一款付费Audience Manager插件，可帮助您使用散列标识符(如电子邮件地址)在Facebook等基于人员的环境中激活第一方受众细分。 |
| **[将Twitter定制的受众配置为基于自助服务设备的目标](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/destinations/device-based/twitter-tailored-audiences.html)** | 我们将Twitter目标迁移到自助服务配置模型。本文解释了在迁移后，您需要为现有Twitter集成做什么以继续工作。 |
| **[受众市场帐单示例](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/audience-marketplace/audience-marketplace-for-data-buyers/marketplace-buyer-billing.html#billing-examples)** | 我们添加了一个新示例，案例3，我们详细了解了如何利用激活和建模用例对细分进行计费。 |

**修复和改进功能**

* 我们修复了用户无法手动编辑Adobe Analytics目标以手动映射区段的错误。(AAM-49323)
* 我们修复了重复的Audience Marketplace源来自单一数据源ID的缺陷。数据源和 [!DNL Marketplace] 源之间必须有1：1映射。(AAM-48504)
* 我们对特征和细分创建工作流程进行了增强。现在，您可以过滤数据源以存储特征或区段，以排除任何非Audience Manager数据源(例如，来自Adobe Analytics的报告套件数据源)。(AAM-35899)
* 我们修复了数据源API中的一个问题，该问题导致设置查询参数 `ExcludeReportSuites=true` 不会从Adobe Analytics中排除报告套件数据源。(AAM-48545)
* 我们做了一些与Audience Manager用户界面辅助功能相关的改进。(AAM-49024)和(AAM-49031)

## Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新增功能、修复和更新。Adobe 建议那些采用内部部署的客户部署最新的修补程序，以便确保获得更高的稳定性、安全性和性能。

### 产品版本

**Cloud Manager 2019.8.0**

Cloud Manager2019.8.0修复了各种次要缺陷，提高了构建性能，并增加了对选择性构建内容包的支持。

* [Cloud Manager 2019.8.0 发行说明](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

### 产品维护

**AEM维护发行路线图**

请参阅此处发布 [的AEM维护发行路线图](https://helpx.adobe.com/experience-manager/maintenance-releases-roadmap.html)。

### 自助

**Asset Link1.1预发行版**

* [关于Adobe资产链接预发行](https://helpx.adobe.com/enterprise/using/adobe-asset-link-prerelease.html)
* [为预发布的Adobe Asset Link配置AEM](https://helpx.adobe.com/enterprise/using/configure-aem-for-aal-prerelease.html)

**AEM 桌面版应用程序 2.0**

AEM桌面应用程序2.0for MAC于2019年月30日发布。AEM桌面应用程序2.0将于月初发布。

在此处访问文档和下载 [](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/introduction.html)。

**资产智能标记**

了解在此处过期 [后如何更新证书](https://helpx.adobe.com/experience-manager/6-5/assets/using/config-smart-tagging.html#Obtainpubliccertificate)。

**AEM6.5Screens用户指南**

_网络部署指南的新文档_ 现已推出。请参阅[《 用户指南》](https://helpx.adobe.com/experience-manager/6-5/screens/user-guide.html)。

**自动化表单转换服务**

AEM Forms自动化表单转换服务的文档现已可用。请参阅 [自动化表单转换服务简介](https://helpx.adobe.com/experience-manager/Automated-Forms-Conversion-Service/introduction-to-automated-form-conversion-service.html)。

### 社区

**AEM技能生成器网络研讨会**

* [Adobe Experience Manager Sites](https://forums.adobe.com/thread/2647742)

   | 网络研讨会 | 页面 |
   | -----------| ---------- |  
   | _创作Web体验_ | 2019年月27日 |
   | _搜索和导航内容_ | 2019年月日 |
   | _轻松管理每个不断演变的内容_ | 2019年月10日 |
   | _流畅体验_ | 2017年月17日 |
   | _创建和管理多语言、多国家/地区以设计全球网站结构_ | 2019年月24日 |

* [Adobe Experience Manager Assets](https://forums.adobe.com/thread/2647743)

   | 网络研讨会 | 页面 |
   | -----------| ---------- |  
   | _文件夹结构和搜索_ | 2019年月29日 |
   | _元数据_ | 2019年月日 |
   | _Brand Portal_ | 2019年月12日 |
   | _Dynamic Media_ | 2019年月19日 |
   | _资产链接_ | 2019年月26日 |

* [Adobe Experience Manager Forms](https://forums.adobe.com/thread/2647744)

   | 网络研讨会 | 页面 |
   | -----------| ---------- |  
   | Forms101_ | 2019年月日 |
   | _将表单连接到数据库、构建工作流以及使用电子签名集成表单_ | 2019年月11日 |
   | _创建移动响应式Web和可供打印的交互通信_ | 2019年月25日 |

* [Adobe Experience Manager Cloud Manager](https://forums.adobe.com/thread/2647745)

   | 网络研讨会 | 页面 |
   | -----------| ---------- |  
   | _测试最佳实践-借助Cloud Manager构建执行、监控、审计和洞察_ | 2019年月18日 |
   | _使用云管理器的调度程序配置_ | 2016年10月16日 |
   | _使用Cloud Manager和第三方工具创建工作流_ | 2013年11月13日 |

### 其他资源

* [AEM 6.5 学习和支持主页](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 学习和支持主页](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 学习和支持主页](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 学习和支持主页](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager 用户指南](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [AEM文档旧版本](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Dynamic Media经典帮助主页](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Dynamic Media 发行说明](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre 发行说明](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

### 产品生命周期终止

[!DNL Digital Publishing Suite Classic] (DPCSC)将于2019年月31日终止。For more information, see the [[!DNL Digital Publishing Suite Classic] End-of-Life FAQ](https://helpx.adobe.com/digital-publishing-suite/help/eol-statement-for-dpsc.html).

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

### Adobe Campaign Classic

* [Campaign Classic19.1.4更新](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9032) -构建9032
* [Campaign Classic19.1.5更新](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9033) -构建9033

### Adobe Campaign [!UICONTROL Control Panel]

我们为管理用户添加了新功能，以便在其域的SSL证书过期之前接收通知。有关更多信息，请参阅[详细的文档](https://helpx.adobe.com/campaign/kb/control-panel-subdomains-certificates.html)。

此外，管理员用户现在可以删除添加到访问SFTP服务器的SSH密钥。

请注意，[!UICONTROL 控制面板]对 AWS 上托管的 Adobe Campaign Classic 和 Adobe Campaign Standard 客户都可用。No upgrades are required to access [!UICONTROL Control Panel].

### 其他资源

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
