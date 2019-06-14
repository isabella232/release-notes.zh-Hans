---
title: Adobe Experience Cloud 发行说明
description: 2019年月Experience Cloud发行说明
doc-type: 发行说明
last-update: 2019年月
author: mfrei
translation-type: tm+mt
source-git-commit: dbcd180c5fd07abd8a6b8ed9ec47b3b1d996f275

---


# Adobe Experience Cloud 发行说明

Adobe Experience Cloud 的新增功能和修复。

>[!NOTE]
>若要通过电子邮件接收关于即将发布版本的通知，请订阅 [Adobe 产品更新早知道](https://www.adobe.com/subscription/priority-product-update.html)。您将在版本发行前的三到五个工作日收到通知。对于发行之后发布的新信息，将使用发布日期进行标记。

**发布日期：2019 年 6 月 13 日**

* [Adobe Experience Platform](#platform)
* [Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [[！DNL Campaign]](#ac)
* [Mobile Services](#mobile)
* [Advertising Cloud](#adcloud)
* [Target Standard/Premium 19.6.1](#target)
* [Magento](#magento)
* [Primetime](#primetime)

## Adobe Experience Platform {#platform}

### Adobe Experience Platform 发行说明

* 请参阅 [[！Adobe. io上的DNL Experience Platform]发行说明](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes-20190515.md) ，获取最新更新 [!DNL Experience Platform]。

### [!DNL Experience Platform Launch]

* 请参阅 [[！DNL Experience Platform Launch]](https://docs.adobelaunch.com/) 了解最新信息。

## Analytics {#analytics}

Adobe Analytics 的新增功能和修复：

* [Adobe Analytics 的新增功能和修复](#aa-features)
* [Analytics 管理员的重要注意事项](#aa-notices)

有关产品文档，请参阅 [Analytics 帮助主页](https://marketing.adobe.com/resources/help/en_US/reference/)。

### Adobe Analytics 的新增功能和修复{#aa-features}

| 功能 | 描述 |
| -----------| ---------- |  
| **区段** | 细分中维度的新归因模型：<ul><li>重复(默认)：包括实例的实例+持久值。</li><li>实例：包括维度实例。</li><li>非重复实例：包括维度的唯一实例(非重复)。</li></ul> [更多](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segmentation-workflow/seg-build.html) |
| **区段** | 新的细分运营商： **[!UICONTROL 等于任何]** 且 **[!UICONTROL 不]** 等于任何。[更多...](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segment-reference/seg-operators.html) |
| **调试程序** | 使用Adobe ID登录后，您可以选择检索Experience Cloud调试器中的后处理点击。经过后处理的点击是服务器调用完成后的服务器调用，它经过 [!UICONTROL 处理规则] 和VISTA规则，允许您验证 [!UICONTROL 处理规则] 和您的VISTA规则。**注意**：如果您使用的是A4T(ElementalDataHelp)，后期处理数据可能需要几分钟才能返回。 |
| **Analysis Workspace:** | 为左边栏搜索添加了现成的过滤器。除您当前看到的内容(维度、指标、批准等)之外，还包括计算指标、客户属性、eVar、Prop、Video等新筛选器。从而更轻松地查找所需的组件。 |
| **Analysis Workspace** | 我们为将在您添加区段时将显示的流失可视化添加了一条警告-某些无效区段容器组合将导致无效的流失图表，如 <ul><li>在访客上下文流失可视化中使用基于访客的区段作为触点</li><li>在访问上下文流失可视化中使用基于访客的区段作为触点</li><li>在访问上下文流失可视化中使用基于访问的区段作为触点</li></ul> <br> [更多信息...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/visualizations/fallout/compare-segments-fallout.html)</br> |
| **分析文档改进** | 分析文档已重新组织，现在包含可让您改进内容的协作功能！您可以根据文档记录问题并建议编辑。文档集已移至 [新域](https://docs.adobe.com/content/help/en/analytics/landing/home.html)。应重新定向。 |
| **新技术说明用户指南** | [“技术说明”用户指南](https://docs.adobe.com/content/help/en/analytics/technotes/home.html) 现已可用。目前，它致力于帮助用户更熟悉第三方分析工具(如Google Analytics)来更加熟悉Adobe Analytics。技术说明用户指南将在未来几个月内扩展，以包含更多内容。 |

**Analysis Workspace 修复**

* 修复 [!DNL Analysis Workspace] 了可视化中本地化日文日期信息的问题。(AN-180114)
* 修复了复制和粘贴维度项目后出现的问题。随后在项目上进行的搜索导致错误。(AN-177394)
* 修复了自由形式表中区段面板中缺少编辑选项的问题。(AN-171703)
* 修复 **[!UICONTROL 了在与大量收件人共享时设置为登陆页面]** 功能的问题。(AN-163922)
* 修复了在实时报告中垂直剪辑字符串的问题。(AN-175980)

**其他 Analytics 修复**

* 修复了管理员用户无法启用 **[!UICONTROL 成功事件]** 的问题。(AN-176689)
* 修复了在使用 **[!UICONTROL 退出率]** 量度创建警报时发生的问题。(AN-177476)

### Analytics 管理员的重要注意事项 {#aa-notices}

| 注意 | 添加或更新日期 | 描述 |
| -----------| ---------- | ---------- |
| 分类规则构建器限制 | 添加于2019年月日 | 这些限制不是新的，但已添加到此处的文档 [](https://marketing.adobe.com/resources/help/en_US/reference/classification_rule_builder.html)中。 |
| 新的细分运营商限制 | 添加了2019年月31日 | 从2019年月18日开始，区段操作符“包含”，“不包含”，“包含全部”，“不包含全部”将限制为每输入字段100个单词。此限制将应用于此日期之后的所有新和修改的区段。超出限制的现有区段将继续受到支持，但在输入字段减少之前，不能修改或保存。这些限制作为不断努力提高查询性能的一部分加以应用。 |
| 即将更改对 **[!UICONTROL 启用日期]** 和 **[!UICONTROL 数字 2 分类]** 的支持 | 更新日期：2019 年 5 月 28 日 | 已从代码库中移除了导入数字 2 分类和启用日期的分类的功能。这项更改将随 2019 年 6 月维护版本的发布而生效。如果您的导入文件中包含“数字”或“启用日期”列，则这些单元格会被静默忽略，同时该文件中的任何其他数据均会正常导入。<br/>现有的分类仍可以通过标准分类工作流程导出，并将继续在报表中可用。 |
| 即将更改“报表总数”计算__ | 更新日期：2019 年 5 月 2 日 | 在 **2019 年 6 月 13 日**，Adobe Analytics 将以一致的方式处理所有维度和量度中的“报表总数”__计算。这将导致某些报表（通常为 Prop 或客户属性报表）的总数发生更改。在进行此项更改之前，无论“未指定”__是否显示在报表中，某些报表总数都会不一致地在总数中包含或排除“未指定”__行项目。<br/>自 2019 年 6 月 13 日开始，“未指定”__将始终显示在报表总数中，即使它在报表中未显示为行项目也是如此。此外，在进行此项更改之后，对于某些维度，使用“存在”__或“不存在”__逻辑的区段可能会显示不同结果。此更改将影响 Analysis Workspace、Reports &amp; Analytics、Ad Hoc Analysis、Report Builder 和报表 API。 |
| 更新从 [!DNL Analysis Workspace] 下载 CSV 时的操作 | 2019 年 4 月 10 日 | 从 2019 年 4 月 11 日开始，已对 [!DNL Analysis Workspace] 中的 **[!UICONTROL CSV 下载]** （和 **[!UICONTORL 复制到剪切板]**）进行了一些更改，以删除导出数据中的格式。  <ul><li>千位分隔符将不再包含在内。小数分隔符将继续包含在内，并将遵循 **[!UICONTROL 组件 &gt; 报表格式 &gt; 千位分隔符]** 下定义的格式。注意：使用逗号作为小数分隔符的数值将会继续在导出的 CSV 中引用。</li><li>不会显示任何货币符号。</li><li>不会显示任何百分比符号。百分数将以小数形式显示。例如，75% 将表示为 0.75。</li><li>时间将以秒为单位显示。</li><li>同类群组表将只显示原始值；百分比将被删除。</li><li>如果数字无效，将显示空单元格。</li></ul> |
| 即将更改 [!DNL Analysis Workspace] 调试器命令 | 2019 年 4 月 4 日 | 自 **2019 年 6 月 13 日** 起，用于开启 [!DNL Analysis Workspace] 调试器的控制台命令将变为 adobeTools.debug.includeOberonXml。adobe.tools.debug.includeOberonXml 命令将于该日期之后停止运行。 |
| 移动浏览器版本号 | 2019 年 2 月 7 日 | 从 2019 年 1 月 8 日开始，我们将移动浏览器版本号的截断级别从 2 更改为 1。在该日期之后，版本号将只显示前两个级别（例如 _Firefox 64.0.2_ 现在报告为 _Firefox 64.0_）。 |
| 终止 [!DNL Ad Hoc Analysis] 的生命周期 | 2019 年 1 月 29 日 | 2018 年 8 月 6 日，Adobe 宣布计划终止 [!DNL Ad Hoc Analysis] 的生命周期。确定终止日期后，Adobe 会立即与大家共享此信息。<br/>有关更多信息（包括在此期间将兼容的 Java 版本），请访问[探索工作区](https://adobe.ly/discoverworkspace)。 |
| 简短 Analytics 报表链接 | 2019 年 1 月 14 日 | 系统将从 2019 年 1 月 17 日星期四开始按照滚动计划表清理和删除任何在一年内未被访问过的简短 Analytics 报表链接。 |
| 停止支持 TLS 1.0 | 更新日期：2019 年 1 月 10 日 | 自 2019 年 2 月 11 日起，Adobe Analytics 报表不再支持 TLS（传输层安全性）1.0 加密。这一更改体现了我们为维持最高安全标准和提升客户数据安全性所做的不懈努力。如果您在2019年月11日之后无法连接到Adobe Analytics报告，则应将浏览器升级到 [最新版本](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html)。<br/>自 2019 年 2 月 20 日起，Adobe Analytics 数据收集不再支持 TLS 1.0。在实施此次更改后，如果最终用户使用不支持 TLS 1.1 或更高版本的旧设备或 Web 浏览器，Adobe 将不再从这些最终用户那里收集 Analytics 数据。我们希望这不会对客户数据或报表产生重大影响。（如果您的网站已不支持 TLS 1.0，则不会受到影响。）<br/>从 2019 年 4 月 11 日开始，Adobe Analytics 报表 API 不再支持 TLS 1.0 加密。访问该 API 的客户应当确认他们不会受到影响。 <ul><li>在默认设置下使用 Java 7 的 API 客户端将需要[做出修改才能支持 TLS 1.2](https://www.java.com/en/configure_crypto.html)。（请参阅“更改客户端端点的默认 TLS 协议版本：将 TLS 1.0 更改为 TLS 1.2”。__） </li><li>使用 Java 8 的 API 客户端应该不会受到影响，因为其默认设置为 TLS 1.2。</li><li> 使用其他框架的 API 客户端，将需要联系各自的供应商来获取有关 TLS 1.2 支持的详细信息。</li></ul> |
| 数据馈送：post_product_list 列 - 大小更改 | 2019 年 1 月 9 日 | 2019 年 2 月 7 日，Adobe 将 post_product_list 列的大小从 64 KB 扩展到 16 MB。这项更改可确保在处理过程中添加到 post_product_list 的推销 eVar 值不会导致产品和收入值截断。如果您的流程需要提取 post_product_list 值，请确保这些流程可以处理长度最大为 16 MB 的值，否则系统将按照 16 KB 的长度将该值截断，以避免数据获取失败。 |
| 影响不活动的 [!DNL Analytics Live Stream] 端点的管理更改 | 2018 年 12 月 20 日 | 从 2019 年 2 月 1 日开始，可能会禁用持续 90 天没有活动客户连接的 [!DNL Live Stream] 端点。您可以联系客户关怀团队查询您的 [!DNL Live Stream] 端点，并在必要时重新启用它们。此外，请确保您的客户进程按照服务设计要求保持持久连接，并在连接断开或中断时实施重新连接。 |
| 由于对 TLS 1.0 的支持终止而更新 Adobe [!DNL Report Builder] | 2018 年 9 月 7 日 | 由于对 TLS 1.0 的支持即将终止，我们建议 [!DNL Report Builder] 用户在 2019 年 2 月之前下载 v5.6.21 版。在该日期之后，以前版本的 [!DNL Report Builder] 将无法再正常运行。 |

## Audience Manager {#aam}

**修复、增强功能和弃用功能**

* Audience Manager现在只针对使用限制计算有效的算法模型。
* 解决了导致算法模型范围不能为使用相应模型的特征显示的问题。
* 解决了导致特征文件夹内容无法显示的问题，然后文件夹名称包含圆括号和/或括号。
* 解决了在仅选择一种特征类型时导致特征排序失败的问题。
* 解决了一个问题，该问题导致特征文件夹树在您每次创建或更新新子文件夹时折叠到 [!UICONTROL “所有特征] ”视图。
* 解决了在尝试删除合作伙伴时所需 [!DNL VIEW_DATASOURCES] 权限的问题。
* 解决了导致区段页面中的 [!UICONTROL 搜索] 框在 [!UICONTROL 所有] 文件夹而非选定的文件夹中搜索的问题。
* 解决了创建新算法模型时无法通过标题控件对 [!UICONTROL 排除特征] 表进行排序的问题。
* 解决了导致Audience Manager在运行具有空间隔日期的报告时崩溃的问题。

## Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新增功能、修复和更新。Adobe 建议那些采用内部部署的客户部署最新的修补程序，以便确保获得更高的稳定性、安全性和性能。

### 产品版本

**Cloud Manager 2019.5.0**

最新的Cloud Manager版本(2019.5.0)不包含大量功能更改，尽管它提供了若干错误修复。

* [Cloud Manager 2019.5.0 发行说明](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

**适用于 AEM 的 XML Documentation**

XML文档解决方案的3.3发行版现已推出。请参阅以下发行说明：

***高级地图功能***
* 通过使用存储库视图中的拖放操作或使用水平栏和元素目录添加主题引用。
* 在主题参考、区块(如导航标题、格式、范围等)上添加元数据。
* 单击主题引用应在编辑器中打开主题(如果未注销，则预览模式将禁用编辑功能)。
* 添加主题标题和主题组。
* 使用FrontMatter(主题、前言、书籍列表、声明等)添加书签(主题、附录、术语表等)。
* 在创作模式下，将突出显示断开的链接，显示痕迹导航，并提供“完整标记视图”。
* 能够设置映射级别属性。
* 能够设置标题/BookTitle。
* 对重新表的支持可添加rel header、列、将主题从地图和库拖放到rel表、设置链接、范围和其他链接参数，从而重新排序单元格内的链接。
* 工具栏构件之前插入，插入元素后插入元素。
* 在主题上应用条件时突出显示。
* 能够一次编辑多个地图(每个地图在同一浏览器上打开为一个选项卡)。
* 在地图面板和存储库视图中，悬停-显示完整主题标题和文件名。

***完整标记视图***

* 在两个元素之间插入新标记。
* 复制和粘贴标记。
* 在允许的位置拖放标记，而不允许在文件内放置和放置标记。
* 展开和折叠标记。

***特定于DITA的搜索增强功能***

* 提供序列化工具来重新索引选定内容
* 用户可以使用 `contains` 和 `exact match` 搜索。他们还可以使用以下参数进行搜索。：
   * 资产元数据。例如， `file name`客户定义的、或 `title`任何自定义元数据。
   * DITA属性名称及其值。`platform=winOS`例如，
   * DITA元素名称及其值。`author = Joe Smith`例如，
   * DITA元素名称及其应用的属性。例如，具有product= spaceBase属性名称/值对的表。
   * DITA主题和映射元数据。
   * DITA信息类型。考试[示例、地图、主题、概念等)。
   * 根文件夹资产所在的文件夹路径。
   * 文档状态。
   * 注销状态。
   * 修改日期范围。
   * CQ标签。
* 通过组合以上一个或多个搜索参数，可以创建复杂的查询。

***审阅功能变更***

* 审阅者提示：
   * 导入所有注释，并在升级到3.3版本之前合并正在进行的审阅。
   * 确保不为编辑器打开多个选项卡。
   * 确保未启用“完整标记”视图。
   * 在审阅过程中，请勿在创作模式和源代码模式之间切换。
* 能够指定要审核的我的内容版本。
* 能够根据基线、日期、标签或当前活动版本选择所选主题的版本，或在创建审核时指定每个主题的版本。
* 能够发送同一主题/地图以多次进行审阅，作者可以在编辑器审阅面板中访问所有审阅。
* 作为发起人，可以为审阅者推送内容的稍后版本。推送新内容以供审阅时，审阅者将收到通知。
* 作为作者，用户可以在编辑器的审阅面板中查看其所有版本内容的注释注释。作者将能够按版本号筛选注释。
* 作为作者用户，用户可以在审核的编辑器中查看和导入旧版本内容的注释。

***其他***

* 从“存储库”视图中创建新文件夹、主题或映射。
* 在资产UI中查看-为文件夹和主题添加菜单选项-“在资产UI中查看”。此选项打开“资产”UI，用户可在左侧查看左侧的内容树以及右侧的“列表”视图中的所有文件(顶部的所有资产菜单)。
* 现在，审核仪表板可作为DITA项目的一个拼贴提供，该项目跟踪审阅人级别和审核任务级别上的评论。
* 增加了将IDML转换为DITA的功能。
* 提供API，以便在基线中的所有指定版本上应用给定的标签。
* 完成XHTML/DOCX到DITA转换后的活动。您可以使用此事件向转换的内容或要实现的任何其他自定义逻辑添加专用属性。
* 进行了基线性能选项卡改进。用户首先需要在所有现有基准上运行脚本。
* 对XHTML进行了对DITA转换的增强。
* DTA-OT卸载以进行发布优化。
* 修复了列表视图中“类型”列上的排序。
* 能够处理Word到DITA转换中的级联样式。

### 社区

**[Cloud Manager技能生成器网络研讨会系列](https://cloudmanagerskillbuilder.experienceleague.adobeevents.com/)**

有兴趣了解DevOPS流程如何简化Adobe Experience Manager管理在云中的日常活动？Cloud Manager为Adobe Experience Manager提供第一代云原生功能，可实现云敏捷性，无论贵组织开始开发DevOs转换还是寻找用于扩充现有DevOPS流程的战略。

[在此月度系列中](https://cloudmanagerskillbuilder.experienceleague.adobeevents.com/)，您可以直接从Adobe的产品团队那里了解如何入门并使用Cloud Manager功能简化云中的Adobe Experience Manager管理。

您将学习以下内容：
* 如何开始使用Cloud Manager并设置CI/CD管线
* 自动缩放和透明服务交付如何工作，并可简化Adobe Experience Manager环境管理
* 如何使用Cloud Manager API和集成现有DevOPS流程

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

### [!DNL Campaign Classic] 19.1Spring Release

| 功能 | 描述 |
| ------------- | ----------- |
| 控制面板 | 要以管理员用户的身份提高工作效率，可以通过监视存储、白名单IP地址以及为每个实例安装SSH密钥来管理SFTP服务器的设置。请注意，控制面板仅适用于AWS上托管的客户。[通过Experience Cloud登录](https://experiencecloud.adobe.com/campaign/controlpanel/)。<br> 有关详细信息，请参阅 [详细的文档](https://helpx.adobe.com/campaign/kb/control-panel.html) 和 [操作方法视频](https://helpx.adobe.com/campaign/kt/acc/using/acc-control-panel-video-use.html)。 |
| 审计线索 | 作为管理员，通过监视和管理Adobe Campaign Classic实例中所做的更改提高工作效率。审核线索将记录在源架构、工作流和选项上做出的操作。您可以快速查看元素是否已创建、修改或删除。<br>有关详细信息，请参阅 [详细的文档](https://docs.campaign.adobe.com/doc/AC/en/PRO_Production_procedures_Audit_trail.html) 和 [操作方法视频](https://helpx.adobe.com/campaign/kt/acc/using/acc-audit-trail-feature-video-use.html)。 |
| Guardril、稳健性和可伸缩性 | 添加了一系列改进 [!DNL Campaign Classic]。Guardril、稳健性和可伸缩性改进在 [Adobe Campaign Classic发行说明](https://docs.campaign.adobe.com/doc/AC/en/RN.html)中列出。 |
| 安全SMS Messaging(TLS) | 现在，通过扩展通用SMPP连接器支持安全SMS。这允许向提供者提供加密连接。<br>有关更多信息，请参阅[详细的文档](https://helpx.adobe.com/campaign/kb/sms-connector-protocol-and-settings.html)。 |
| 兼容性矩阵更新 | 通过此新版本，Adobe Campaign现在支持以下数据库系统。请参阅 [兼容性矩阵](https://helpx.adobe.com/campaign/kb/compatibility-matrix.html) <ul><li>Oracle18c</li><li>MySQL5.7(FDA)</li><li>SQL Server2017</li><li>Teradata16(FDA)</li><li>postGreQl11</li></ul> |

请参阅 [Adobe Campaign Classic] 发行说明](仅限修复和改进)。

### [!DNL Campaign Standard] 19.2Spring Release

| 功能 | 描述 |
| ------------- | ----------- |
| 控制面板 | 为了帮助您以管理员用户的身份提高工作效率，您可以轻松监控容量和管理实例设置(从SFTP服务器管理开始)。<br> 有关详细信息，请参阅 [详细的文档](https://helpx.adobe.com/campaign/kb/control-panel.html) 和 [操作方法视频](https://helpx.adobe.com/campaign/kt/acs/using/acs-control-panel-video-use.html)。 |
| 本地通知消息 | 本地通知消息允许您在移动应用程序中提供新数据时通知用户，即使没有访问Internet或在前台运行的移动应用程序时也是如此。本地通知由移动应用程序在特定时间触发，具体取决于活动。<br>有关更多信息，请参阅[详细的文档](https://helpx.adobe.com/campaign/standard/channels/using/customizing-an-in-app-message.html#customizing-a-local-notification-message-type)。 |
| 工作流增强-向外部信号活动添加有效负荷 | 在从另一个工作流成功满足定义条件或REST API调用与外部系统集成时，开始使用有效负荷启动工作流。这还包括一个新的测试活动，您可以在此运行测试的测试。<br>有关详细信息，请参阅 [详细的文档](https://helpx.adobe.com/campaign/standard/channels/using/customizing-an-in-app-message.html#customizing-a-local-notification-message-type) 和 [操作方法视频](https://helpx.adobe.com/campaign/kt/acs/using/acs-external-signal-activity-feature-video-use.html)。 |
| 登陆页面增强功能- Google ReCAPTCHA | 利用Google ReCAPTCHA防止登录页面上垃圾邮件，无需客户采取任何行动。<br>有关更多信息，请参阅[详细的文档](https://helpx.adobe.com/campaign/standard/channels/using/designing-a-landing-page.html#setting-google-recaptcha)。 |

有关产品文档，请参阅：

* Adobe Campaign Standard：[文档](https://helpx.adobe.com/support/campaign/standard.html) - [发行说明](https://helpx.adobe.com/campaign/standard/rn/using/release-notes.html) - [专题视频](https://helpx.adobe.com/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic：[文档](https://helpx.adobe.com/support/campaign/classic.html) - [发行说明](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [专题视频](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html)

## Mobile Services {#mobile}

* 所有Adobe服务器上都禁用了TLS1.0。要使Android4.x设备通过SSL连接到Adobe服务，在创建握手时，SDK现在强制TLS1.1/TLS1.2。

## Advertising Cloud {#adcloud}

更新时间：2019 年 5 月 6 日，为 6 月 8 日发布的版本进行更新

| 产品 | 功能 | 描述 |
| -----------| ---------- | ----------  |
| 搜索营销活动、标签分类和限制 | 键盘快捷键 | 现在，您可以使用 <b>Shift+单击</b> 选择多个连续行，并 <b>单击</b> Ctrl并单击以选择多个非连续行。 |
|  | 选择全部与。选择页面上的全部 | 在数据表中，当您选择顶部复选框以选择所有行时，新默认值是选择页面上的所有行(基于您查看25行、50行、100行、200行或连续滚动)。您仍有一个选项可选择所有可用的行。 |
| 默认视图、自定义视图和独立的列自定义设置 | 列重新排序 | 新的“向上”和“向下”按钮允许您重新排序列。您仍然可以拖放列，像以前那样重新排序它们。 |

## Target Standard/Premium 19.6.1（2019 年 6 月 25 日）{#target}

请参阅 Adobe Target 发行说明，了解最新的发布信息。

[Target 发行说明（预发行版本）](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html)

[Target 发行说明（当前版本）](https://docs.adobe.com/content/help/en/target/using/release-notes/release-notes.html)

## Magento {#magento}

Magento 是一个电子商务平台，可为在线商家提供灵活方便的购物车系统，并控制其在线商店的外观、内容和功能。Magento 提供有开源版本和功能更全面的商业版本。

Magento Commerce 是 Adobe Commerce Cloud 的一部分，它为 B2C 和 B2B 体验提供了一个具有企业级能力、无限可扩展性和开源灵活性的电子商务解决方案。

可在 [“发行信息](https://devdocs.magento.com/guides/v2.3/release-notes/bk-release-notes.html) ”页面上找到我们的Open Source和Commerce版本的发行说明。

## Primetime {#primetime}

Adobe Primetime 是一个多屏幕电视平台，可以帮助媒体公司打造一种完美的个性化观看体验，并从中盈利。

[Primetime 发行说明](http://help.adobe.com/en_US/primetime/release_notes/index.html)
[Primetime 帮助主页](http://help.adobe.com/en_US/primetime/)
