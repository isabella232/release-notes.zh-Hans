---
title: Adobe Experience Cloud 发行说明
description: Experience Cloud 发行说明模板
doc-type: release notes
last-update: January 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 8a895d104abd20910aa37ec2ec3b6eeaccd8c461

---


# 内部评论- Adobe Experience cloud发行说明- 2020年1月

Adobe Experience Cloud 的新增功能和修复。

> [!NOTE] 若要通过电子邮件接收有关即将发行的版本的通知，请订阅 [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html)。对于在版本发行之后发布的新信息，将使用发布日期进行标记。

**发布日期：2020年1月**

* [Experience Cloud 界面](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html)（链接到解决方案帮助）
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html)（链接到解决方案帮助）
* [!DNL Advertising Cloud](#adcloud)（11 月 8 日更新）

在找帮助主页吗？请参阅 [Adobe Experience Cloud 文档](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html)。

## Status.adobe.com

使用Adobe ID，您可以根据您的产品、地区和活动首选项订阅状态活动通知。

| 功能 | 描述 |
| -----------| ---------- |
| 订阅实时电子邮件通知 | <ul><li>支持Experience Cloud、Creative Cloud、Document Cloud、AEP和Adobe服务</li><li>支持区域和活动类型首选项</li><li>对Web、移动和平板电脑表面的UX支持</li></ul> |
| 通知首选项管理 | <ul><li>随时编辑和保存通知首选项</li><li>随时取消订阅通知</li><li>项目</li></ul> |
| 个性化、更快的电子邮件发送 | <ul><li>在打开、更新或关闭CSO和CMR后，会立即发送活动通知</li><li>仅接收与您配置的首选项匹配的相关活动通知</li><li>收到的本地化通知基于帐户首选项中配置的语言</li></ul> |
| 个性化的产品内通知 | 与通知首选项和产品授权匹配的事件显示在“公告”面板中。 |

## Experience Cloud 界面 {#ecloud}

Experience Cloud 界面和产品管理的发行说明。

* 项目
* 项目

有关产品文档，请参阅 [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html)。

## Experience Platform {#platform}

Experience Platform、Experience Platform Launch、Identity Service 和安全公告的发行说明。

* [Experience Platform 发行说明](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [安全公告和通知](https://helpx.adobe.com/security.html)（所有 Adobe 产品）

### Experience Platform Launch {#launch}

有关发行说明和产品文档，请参阅 [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html)。

## [!DNL Analytics] {#analytics}

Adobe Analytics 中的新增功能和修复：

* [Adobe Analytics 中的新增功能、增强功能和修复](#aa-features)
* [Analytics 管理员的重要注意事项](#aa-notices)（**更新日期：2019 年 12 月 18 日**）
* [AppMeasurement](#appm)

有关产品文档，请参阅 [Adobe Analytics 帮助主页](https://docs.adobe.com/content/help/en/analytics/landing/home.html)。

### Adobe Analytics 中的新增功能、增强功能和修复 {#aa-features}

| 功能 | 描述 |
| -----------| ---------- | 
|  |  |

#### 修复

* 修复了“未定义”错误地
* 修复

### [!DNL Analytics] 管理员的重要注意事项 {#aa-notices}

| 注意 | 添加或更新日期 | 描述 |
| -----------| ---------- | ---------- |
| 新的 Adobe Analytics 域 | 2019 年 12 月 18 日 | 2020 年 1 月 16 日，Adobe Analytics 将移至新域 https://experience.adobe.com/analytics 。这项更改可能会导致在 Safari 中加载 Analytics 时出现 Cookie 问题。取消选中 Safari 隐私首选项中的“阻止跨站跟踪”，将支持跨域的 Cookie（以及所有跨站点体验），并允许 Analytics 在这个新的 Adobe Experience Cloud 域上正常运行。用户可以正常使用其他浏览器，因为这项变更只影响 Safari 用户。 |
| **[!UICONTROL 查看存档]**选项生命周期终止 | 2019 年 10 月 30 日 | 2020 年 1 月，将终止使用功能板管理器（**[!UICONTROL 组件 > 功能板]**）中的**[!UICONTROL &#x200B;查看存档]**选项。 |
| **[!UICONTROL 强制 IP 登录限制]**选项生命周期终止 | 2019 年 10 月 30 日 | 2020 年 1 月，将终止使用&#x200B;**[!UICONTROL 管理 > 公司设置 > 安全]**菜单下的 IP 登录白名单（**[!UICONTROL &#x200B;强制 IP 登录限制]**）功能。 |
| 更新了对 Cookie 中的 SameSite 属性的处理 | 2019 年 10 月 15 日 | 2019 年 8 月，Adobe 宣布向由 Analytics 设置的所有 Cookie 中添加 SameSite Cookie 设置。在以下情况下，将应用逻辑中的更新：<ul><li>所有不基于 Webkit 的第三方 Cookie 的 SameSite 属性均设置为 `none`。</li><li>所有其他 Cookie 未设置 SameSite 属性。</li></ul> |
| 停止支持 TLS 1.1 | 2019 年 10 月 3 日 | 我们一直不懈努力，致力于维持最高安全标准并提升客户数据安全。为此，Adobe Analytics 对 TLS 1.1 的支持将持续到 2020 年 3 月 31 日，在这之后将不再支持 TLS 1.1。 |
| 圣何塞 FTP 中转站停止为伦敦和新加坡提供支持 | 2020 年 7 月 | 对于位于伦敦和新加坡的客户，我们将不再提供伦敦或新加坡与圣何塞数据中心 [ftp.omniture.com](ftp://ftp.omniture.com/) 之间的数据中转支持。<br/><ul><li>伦敦客户，请使用 [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>新加坡客户，请使用 [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li> |
| 更新 Analysis Workspace 自由格式表总数 | 2019 年 9 月 12 日 | 从 2019 年 10 月开始，自由格式表总数行在计算时，会将已应用的[报表过滤器](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html)考虑在内。迄今为止，总数仅计算的是分段数目。根据这项变化，作为从属的可视化图表（例如，链接的[!UICONTROL 概要数字]可视化图表）将会进行相应的更新，导出的 CSV 和 PDF 数据同样也会更新。 |
| 面向 Analytics 用户的 `createDate` 字段即将发生变化 | 2019 年 8 月 30 日 | 在 2019 年 10 月或 11 月，Analytics 用户的 `createDate` 字段将由美国太平洋时间更新为包含时区信息且格式正确的日期/时间值。(AN-183468) |
| 支持历史时区偏移 | 2019 年 8 月 8 日 | Analytics 现在将自动为带有时间戳的点击处理时区偏移。在 8 月 8 日实施此更改后，载入数据以进行历史处理的系统在发送数据之前将不再需要调整时区偏移。 |
| 分类规则生成器限制 | 添加于 2019 年 6 月 5 日 | 这些不是新限制，只是最近已添加到[此处](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html)的文档。 |
| 新的区段运算符限制 | 添加于 2019 年 5 月 31 日 | 从 2019 年 7 月 18 日开始，区段运算符&#x200B;_包含任意_、_不包含任意_、_包含全部_&#x200B;和&#x200B;_不包含全部_&#x200B;将限制为每个输入字段 100 个词。这项限制将适用于此日期之后的所有新增区段和修改区段。超出此限制的现有区段将继续受到支持，但在缩短输入字段前，将无法进行修改或保存。作为我们持续不断努力的一个组成部分，将应用这些限制以提高查询性能。 |
| 更改对&#x200B;**[!UICONTROL 启用日期]**和**[!UICONTROL &#x200B;数字 2 分类]**的支持 | 更新日期：2019 年 5 月 28 日 | 已从代码库中移除了导入数字 2 分类和启用日期的分类的功能。这项更改已随 2019 年 7 月维护版本的发布而生效。如果您的导入文件中包含“数字”或“启用日期”列，则这些单元格会被静默忽略，同时该文件中的任何其他数据均会正常导入。<br/>现有的分类仍可以通过标准分类工作流程导出，并将继续在报表中可用。 |
| 更改&#x200B;_报表总数_&#x200B;的计算 | 更新日期：2019 年 7 月 9 日 | 在 **2019 年 6 月 18 日**，Adobe Analytics 采取了统一方式计算所有维度和量度中的&#x200B;_报表总数_。这导致某些报表（通常是 Prop 或客户归因报表）的总数出现变化。进行此项更改之前，在计算总数时，无论&#x200B;_未指定_&#x200B;是否显示在报表中，有些报表总数要么包含要么排除&#x200B;_未指定_&#x200B;行项目，总之处理方式并不一致。<br/>自 2019 年 6 月 18 日开始，_未指定_&#x200B;将始终显示在报表总数中，即使它在报表中未显示为行项目也是如此。此外，进行此项更改之后，使用&#x200B;_存在_&#x200B;或&#x200B;_不存在_&#x200B;逻辑的区段，对于不同的维度可能会看到不同的结果，尤其是其中的&#x200B;_未指定_&#x200B;具有特殊名称（如推荐人类型维度的“已键入/已添加书签”行项目或设备类型维度的“其他”行项目）的维度。此更改将影响 Analysis Workspace、Reports &amp; Analytics、Ad Hoc Analysis、Report Builder 和报表 API。<br>**注意&#x200B;**：此&#x200B;_报表总数_计算已更名为&#x200B;_全部总计_。请参阅上述“Analysis Workspace：更新了自由格式表的总数统计”。 |
| 更新从 Analysis Workspace 下载 CSV 时的操作 | 2019 年 4 月 10 日 | 从 2019 年 4 月 11 日开始，已对 Analysis Workspace 中的 **[!UICONTROL CSV 下载]**功能（和**[!UICONTORL &#x200B;复制到剪贴板]**）进行了一些更改，目的在于从导出的数据中删除格式。  <ul><li>千位分隔符将不再包含在内。小数分隔符将继续包含在内，并将遵循 **[!UICONTROL 组件 > 报表格式 > 千位分隔符]**下定义的格式。注意：使用逗号作为小数分隔符的数值将会继续在导出的 CSV 中引用。</li><li>不会显示任何货币符号。</li><li>不会显示任何百分比符号。百分数将以小数形式显示。例如，75% 将表示为 0.75。</li><li>时间将以秒为单位显示。</li><li>同类群组表将只显示原始值；百分比将被删除。</li><li>如果数字无效，将显示空单元格。</li></ul> |
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

### Audience Manager 中的新增功能、增强功能和修复 {#aam-new-features}

| 功能 | 描述 |
|--- |----|
|  |  |

### 增强功能 {#aam-enhancements}

有关更多信息，请联系 Audience Manager 顾问或客户关怀。

### 修复和改进 {#aam-fixes-and-improvements}

* 修复
* 修复

## Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新增功能、修复和更新。Adobe 建议那些采用内部部署的客户部署最新的修补程序，以便确保获得更高的稳定性、安全性和性能。

### 产品版本

### 自助服务

* **AEM 文档更新**

   请阅读有关 Adobe Experience Manager 在最近三个月中的重要文档更改和更新。

   请参阅 [AEM 文档：近期文档更新](https://helpx.adobe.com/experience-manager/documentation-updates.html)。

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

| 视图 | 功能 |
|------|---------|
|  |  |
