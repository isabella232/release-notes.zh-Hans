---
title: 最新发行说明
description: 了解 [!DNL Experience Cloud] 产品和服务的最新发行说明、新增功能和新文档。查找有关  [!DNL Experience Cloud]、 [!DNL Creative Cloud for enterprise] 和  [!DNL Document Cloud] 的新的帮助内容和教程。
doc-type: release notes
last-update: February 2022
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: f4b652db4759a65f38afe0fbd6dca07301875277
workflow-type: tm+mt
source-wordcount: '4963'
ht-degree: 51%

---

# Adobe Experience Cloud 发行说明 - 2022 年 2 月

![横幅](assets/experience-cloud-banner-3.png)

作为一家体验制造商，您的成功之路始于 [Adobe Experience League](https://experienceleague.adobe.com/?lang=en#home). 您可以找到大量的操作说明文档库、自我指导教程、操作方法视频以及适用于所有级别和角色的课程、在线的同行社区，以及需要时的专家支持。

准备好开始了吗？ [参加5分钟的测验并获胜](https://exploreadobe.com/experience-league-quiz/?sdid=4NM897N2&amp;mv=email&amp;mv2=nslsp)!

>[!NOTE]
>
>要收到有关此页面更新的每月电子邮件通知，请订阅 [Adobe 优先产品更新](https://www.adobe.com/cn/subscription/priority-product-update.html)。经常回来查看 Experience League 的最新动态。

**2022 年 2 月**

上次更新时间：**2022 年 2 月 11 日**

* [[!DNL Experience League] 活动](#events)
* [Adobe [!UICONTROL 系统状态]](#status)
* [[!DNL Experience Cloud Central Interface Components] 和管理](#ecloud)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Customer Journey Analytics]](#cust-journey)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL XML Documentation for Adobe Experience Manager]](#xml-doc)
* [[!DNL Adobe Commerce]](#magento)
* [[!DNL Adobe Target]](#target) (更新时间：**2022 年 2 月 3 日**)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Journey Orchestration]](#journey-orch)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Document Cloud]](#doc-cloud)
* [[!DNL Adobe Creative Cloud for enterprise]](#creative-cloud)
* [Digital Experience Blueprint — 教程](#blueprints)

需要帮助？请访问 [Adobe Experience League](https://experienceleague.adobe.com/?lang=zh-Hans/#home)，获取产品和技术文档、Adobe 策划课程、视频教程、快速解答、社区洞察以及由讲师指导的培训。

## ![图标](/assets/experience-league.png) [!DNL Experience League] 活动 {#events}

Experience League 活动是从 Adobe 产品专家处获得答案的好地方。事件的三种类型包括：

| 事件类型 | 描述 |
| -----------|---------- |
| [Experience League LIVE](#exl-live) | 由Experience League团队制作并在YouTube上托管的实时流播放节目。 利用这个机会，您可以与 Adobe 产品专家联系。学习可用于 Adobe Experience Cloud 应用程序的可操作性提示、技巧和策略。<br> 向下滚动以了解有关即将发生的事件的更多信息，并观看在 [Experience League上线](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=zh-Hans). |
| [社区问答喝咖啡休息时间](#coffee) | 与特邀访客共处一小时，并在Experience League社区中提交您的问题！ 在“Adobe”中，获取产品专家的问题解答。在“Experience League社区”中，您可以喝咖啡，并与产品经理聊天。<br>向下滚动以了解我们要涵盖的内容。 不要忘记在为时已晚之前注册！ |
| [Adobe [!DNL Developers Live]](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2021/oct2021/overview.html?lang=en) | 可在Experience League中使用的按需视频事件。 |

{style=&quot;table-layout:auto&quot;}

### Experience League LIVE{#exl-live}

| 活动日期 | 时间 | 活动名称 | 格式 | 描述 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022 年 2 月 3 日 | 按需 | [在 AEM 中引入所有新的参考演示](https://www.youtube.com/watch?v=FEREXV826NQ) | 视频直播活动 | 了解配置、演示和探索 AEM as a Cloud Service 功能的最快方法。 |

{style=&quot;table-layout:auto&quot;}

### 社区问答喝咖啡休息时间{#coffee}

| 活动名称 | 日期 | 应用程序 | 格式 | 描述 |
| -----------| ---------- | ---------- | ---------- |---------- |
| Adobe Target 社区问答喝咖啡休息时间 | 2022年2月23日早8点（太平洋标准时间） | Adobe Target、Experience Platform、RTCDP | 论坛问答 | [立即注册](http://atcommunityqacoffeebreak.splashthat.com/?utm_source=in-product&amp;utm_medium=gainsight&amp;utm_campaign=coffee_talk_AT&amp;utm_content=220223)! 上午8:00至9:00（太平洋时间）与我们一起访问Adobe Target社区，以获取高级产品经理Vishal Chordia的专家回答。 他将回答您所有与Adobe Experience Platform(AEP)、基于受众的个性化、Real-time Customer Data Platform(RTCDP)与Target集成以及Adobe Target一般相关的问题 |

{style=&quot;table-layout:auto&quot;}

### Adobe Developer&#39;s Live{#dev-live}

| 活动 | 日期和时间 | 类型 | 描述 |
| -----------| ---------- | ---------- |---------- |
| [Adobe [!DNL Developers Live]](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2021/oct2021/overview.html?lang=en) | 按需 | 视频 | [!DNL Developers Live] 展示了跨行业推动设计、内容创建工作流、文档服务和客户体验管理的最新技术进步和开发人员工具。查看主题演讲，了解 Analytics API、客户端数据层、Adobe I/O 开源项目等内容。 |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] 提供了关于 Adobe 产品与服务中断和维护活动的详细信息、状态更新以及电子邮件通知。请访问 [status.adobe.com](https://status.adobe.com/) 查看。

发行日期：**2021 年 11 月 16 日**

**新增功能**

* Adobe状态现在报告产品级别的事件。 状态云页面和产品页面根据产品级别的事故报告提供了全新的外观和增强的过滤器。 这样，您便可以更轻松地了解产品在 [status.adobe.com](https://status.adobe.com/) 和电子邮件通知中。 如果您未订阅，请使用此链接设置您的个性化订阅首选项 [https://status.adobe.com/proactive-notifications/manage](https://status.adobe.com/proactive-notifications/manage).

* 现在，状态主页可使用根据您的授权和产品订阅过滤的事件进行个性化。 请在 **status.adobe.com** > **[!UICONTROL 我的事件]** 选项卡。

**当前可用的新增功能和增强功能**

| 功能 | 描述 |
| ------- | -------|
| 事件的产品级报告 | <ul><li>每个产品的横幅都在 [!UICONTROL 状态] 包括产品的最新更新、历史记录和影响属性</li><li>现在，电子邮件遵循与产品级别影响报表相同的格式，而不是事件级别报表</li></ul> |
| 个性化视图 [!UICONTROL 状态] 主页 | <ul><li>引入新视图， **[!UICONTROL 我的事件]** 在 [!UICONTROL 概述] 页面。 此视图根据您的授权和订阅过滤事件</li><li>授权可以适用于组织或个人。 订阅可用于产品或事件</li></ul> |
| 增强的用户体验 | <ul><li>云页面汇总了所有产品的可用性，并能够按产品、区域、日期和事件类型进行过滤</li><li>产品页面汇总了所有功能的可用性，并详细查看了事件和历史记录</li><li>增强的过滤器按功能、数据中心/环境（如果适用）、区域、日期、事件类型和事件/维护状态提供</li></ul> |
| 通过更新产品选项增强了订阅 | <ul><li>Adobe Analytics产品已更新为客户友好视图(现有 [!DNL Analytics] 订阅将迁移到新产品)</li><li>针对 [!DNL Customer Journey Analytics]</li></ul> |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/ec_appicon_24.png) [!DNL Experience Cloud Central UI Components] 和管理 {#ecloud}

| 功能 | 描述 |
| ------- |-------|
| **[!UICONTROL 收件人]** （快捷键）已添加到 [Experience Cloud](https://experience.adobe.com/home) 登陆 | 您可以在新页面的 **[!UICONTROL 收件人]** 标题。 此更新还包括登陆页面的常规布局和响应性改进。 |
| **[!UICONTROL 沙箱]** 移到标题栏 | 沙盒指示器现在集成在所有Experience Platform界面应用程序的标题中。 请参阅 [沙箱](https://experienceleague.adobe.com/docs/experience-platform/sandbox/ui/user-guide.html?lang=zh-Hans) Experience Platform。 |

{style=&quot;table-layout:auto&quot;}

**关于 [!DNL Experience Cloud Central UI Components] 和管理**&#x200B;的更多帮助资源

* [发行说明](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=en) Experience Cloud中心UI组件
* [用户和产品管理](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=zh-Hans) 用于Experience Cloud（管理）
* Places Service [发行说明](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=zh-Hans)
* 的产品文档 [人员 — 客户属性和受众库](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en)

## ![图标](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

有关Experience Platform和 [!UICONTROL Mobile SDK]:

发行日期：**2022 年 1 月 26 日**

* [Experience Platform 发行说明](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=zh-Hans)

### Experience Platform 的新教程和课程 {#tutorials-platform}

为 Experience Platform 发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 2 月 | [利用 Web SDK 实施 Adobe Experience Cloud](https://experienceleague.adobe.com/docs/platform-learn/implement-web-sdk/overview.html) | 多页面教程 | 了解如何使用Adobe Experience Platform Web SDK实施Experience Cloud应用程序。 本教程将向您展示如何使用一个名为 _卢马_. 的 [卢马](https://luma.enablementadobe.com/content/luma/us/en.html) 网站具有丰富的数据层和功能，可让您构建实际可行的实施。 立即开始！ |
| 2022 年 2 月 | [使用实时CDP和Adobe Target实现下一次点击的个性化](https://experienceleague.adobe.com/docs/platform-learn/tutorials/experience-cloud/next-hit-personalization.html) | 视频 | 了解如何在下次点击时使用进行个性化设置 [!UICONTROL Real-time Customer Data Platform] 和Adobe Target。 Real-time CDP中的Adobe Target目标允许您通过管理和隐私支持，将Adobe Target中的Experience Platform区段用于同页和下一页的个性化。 |

{style=&quot;table-layout:auto&quot;}

### Adobe Mobile SDK

请参阅 Adobe Experience Platform Mobile SDK 的[发行说明和更改日志](https://aep-sdks.gitbook.io/docs/release-notes)。

## ![图标](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

发行日期：**2022 年 2 月 16 日**

* Adobe Analytics [发行说明](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=en) (**新位置**)
* Adobe Analytics [产品文档和教程](https://experienceleague.adobe.com/docs/analytics.html?lang=zh-Hans)

### [!DNL Customer Journey Analytics] {#cja}

发行日期：**2022 年 2 月 16 日**

* Customer Journey Analytics [发行说明](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=en)  (**新位置**)
* Customer Journey Analytics [产品文档和教程](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=en)

### AppMeasurement {#appm}

发行版本： **2.22.4**

* [AppMeasurement for JavaScript 发行说明](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=zh-Hans)

### Analytics 的新教程和课程 {#tutorials-analytics}

为 Adobe Analytics 发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 2 月 | [使用处理规则处理传入的数据](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/manipulating-incoming-data-with-processing-rules.html?lang=en) | 视频 | 获取Adobe Analytics中处理规则的概述，并了解它们的用途。 了解一些提示、示例，甚至是警告。 |
| 2022 年 2 月 | [配置列表变量](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configuring-list-variables.html?lang=en) | 视频 | 当一次必须在eVar（转化变量）中放置多个值时，您要执行什么操作？ 列出要取回的变量！ 了解如何以及为何在 Adobe Analytics 中配置和使用列表变量。 |
| 2022 年 2 月 | [配置流量分类](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configure-traffic-classifications.html?lang=en) | 视频 | 了解如何为流量变量配置分类，通常称为 _prop_&#x200B;和 _pagename_，等等。 |
| 2022 年 2 月 | [配置转化分类](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configure-conversion-classifications.html?lang=en) | 视频 | 了解如何为转化变量配置分类，也称为 _eVar_. 此配置还适用于产品和列表变量。 |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager 中的修复和改进。

* 解决了通过 Swagger 接口执行时导致所有 API 调用返回 `Undocumented` 错误的问题。(AAM-59190)
* 解决了导致在某些情况下将错误的用户角色分配给合作伙伴的问题。(AAM-59451)
* 解决了导致 API 需要区分大小写的身份验证标头的问题。(AAM-58528)

有关自助资源，请参阅 [Audience Manager文档和教程](https://experienceleague.adobe.com/docs/audience-manager.html?lang=en) Experience League

## ![图标](/assets/aem.png) Adobe Experience Manager {#aem}

Adobe 建议访问 [Experience Manager 版本更新和路线图](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=zh-Hans)页面以及时了解版本信息。

### Experience Manager 产品版本

* **Experience Manager as a Cloud Service**

   观看 [2022年1月版概述视频](https://video.tv.adobe.com/v/340120) 有关2022.1.0（2022年1月）版本中添加的功能的摘要。

   * [](https://video.tv.adobe.com/v/339278)2021 年 12 月版新增功能概述视频。
   * [2021 年 10 月版新增功能概述视频](https://video.tv.adobe.com/v/338253)。
   * [2021 年 9 月版新增功能概述视频](https://video.tv.adobe.com/v/337381)。

   * **Experience Manager Assets as a Cloud Service**

      _Experience Manager Assets的新增功能_

      * Dynamic Media — 您现在可以使用Experience Manager- Dynamic Media界面配置 [常规设置](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-general-settings.html) 和 [发布设置](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-publish-settings.html) 而无需浏览Dynamic Media Classic桌面应用程序。
      * Dynamic Media 现在支持 MXF 视频的提取、预览、播放和发布。尚不支持 MXF 视频的注释和可购买视频。
      * 在配置远程 DAM 和 Sites 部署之间的连接后，远程 DAM 上的资源即可用于 Sites 部署。您现在可以对远程 DAM 资源或文件夹执行[更新、删除、重命名和移动操作](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/admin/use-assets-across-connected-assets-instances.html?lang=en)。更新会在 Sites 部署中自动提供，但会有一些延迟。

      _Experience Manager Assets 预发行渠道中的新增功能_

      * Dynamic Media现在可以灵活地 [配置一个公司别名帐户](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-alias-account.html?lang=en) ，以便更新现成的Dynamic Media URL和查看器嵌入代码。 此操作会对SEO产生积极影响，以反映对您的业务上下文所做的更新，如品牌重新定位。
      * 您现在可以使用Experience Manager Assets用户界面：

         * 配置对存储库中重复资源的检测。
         * 配置向图像添加数字水印。
      * 管理员现在可以配置电子邮件服务以进行大量下载。 它允许用户 [为大量下载启用电子邮件通知](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/download-assets-from-aem.html?lang=en#enable-email-notifications-for-large-downloads) 从Experience Manager Assets界面。 下载过程完成后，用户会收到电子邮件通知，其中包含已存档 zip 文件夹的下载链接。
      * [管理发布](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=en)功能通过改进的用户界面得到增强。用户可以向选定目标发布或取消发布内容，以及 [添加内容](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=en#add-content) 从DAM存储库中添加到发布列表。 此外， [包含文件夹设置](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=en#include-folder-settings) 发布选定文件夹的内容并应用过滤器，以及 [计划发布](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=en#publish-assets-later) 日期或时间。

      _错误修复_

      * 将资产从内部部署Experience Manager迁移到Asset compute时，不含原始呈现版本的未处理资产会发送到Cloud Services进行处理。
   * **Experience Manager Forms as a Cloud Service**

      _Forms的新增功能_

      * **Experience Manager Formsas a Cloud Service — 通信** — [通信API](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/using-communications/aem-forms-cloud-service-communications.html?lang=en) 帮助您将模板和XML数据结合起来，以生成各种格式的打印文档。 该服务允许您以同步和批处理模式生成文档。 这些API可帮助您创建应用程序，以便您执行以下操作：

         * 使用 XML 数据填充模板文件来生成文档。
         * 生成各种格式的表单，包括非交互式 PDF 打印流。
         * 从 XFA 表单 PDF 生成打印 PDF。
         * 通过将多组数据与源模板合并，批量生成 PDF、PostScript、PCL 和 ZPL 文档。
      * **为使用通信API创建的记录文档和PDF文档自定义字体**  — 现在，您可以在使用通信API生成的PDF文档中使用品牌批准的字体，以符合您的组织要求。

      _Forms预发行渠道中的新增功能_

      * [汇编程序API](https://developer.adobe.com/experience-manager-forms-cloud-service-developer-reference/references/assembler-sync/)  — 汇编程序API，用于组合、重新排列、扩充和获取有关PDF文档的信息。
   * **Cloud Manager**

      _发行日期_

      Cloud Manager在Experience Manageras a Cloud Service中的发布日期为2022.01.0 2022年1月20日。
下一个版本计划于 2022 年 2 月 10 日发布。

      _新增功能_

      * Cloud Manager [当检测到使用了相同的git提交时，避免重建代码库](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/create-application-project/setting-up-project.html?lang=en#build-artifact-reuse) 执行多个全栈管道。
      * 访问Experience Manager环境日志现在需要 **[!UICONTROL 部署管理器]** 产品配置文件。 没有此配置文件的用户会在用户界面中看到一个禁用的按钮。
      * 用户界面不允许为未启用站点作为解决方案的程序进行前端管道配置。
      * 在生成git密码时，将显示过期日期。








### 社区

* **Experience ManagerGEM网络研讨会： _利用Experience Manager无头和应用程序生成器，更快地构建站点_**

   **日期**:2022年3月23日星期三
   **时间**:上午8:00（太平洋标准时间）、下午5:00（太平洋标准时间）或9:00（太平洋标准时间）
   **扬声器**:Duy Nguyen，Adobe软件开发工程师
   [在https://adobe.ly/3oCkEsh注册网络研讨会](https://adobe.ly/3oCkEsh)
   [网络研讨会的常见问题解答](https://adobe.ly/3LkSWdm)

* 播放2022年1月Experience ManagerGEM网络研讨会： [_Experience Manageras a Cloud Service2021年回顾及2022年展望_](https://adobe.ly/3rqbSOz)

### Experience Manager 的新课程和教程 {#tutorials-aem}

过去一个月发布的新视频、教程及课程。

| 发布日期 | 名称 | 类型 | 描述 | 应用程序 |
| ------| ------| ----- | -----| ----|
| 2022 年 2 月 | [创建服务凭据](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-gen-formscs/service-credentials.html) | 视频 | 了解如何创建服务凭据以确保与AEMas a Cloud Service的集成进行安全身份验证。 | AEM Forms CS |
| 2022 年 2 月 | [创建JSON Web令牌(JWT)](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-gen-formscs/create-jwt.html) | 文章 | 了解JSON Web令牌，这是一种开放的行业标准RFC 7519方法，用于在双方之间安全地表示声明。 `JWT.io` 此示例中使用库来生成JWT。 | AEM Forms CS |
| 2022 年 2 月 | [用于访问令牌的Exchange JWT](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-gen-formscs/create-access-token.html) | 文章 | 在 [创建JSON Web令牌(JWT)](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-gen-formscs/create-jwt.html) 步骤与Adobe IMS API交换以获取访问令牌，然后该令牌可用于访问AEMas a Cloud Service。 了解如何请求访问令牌以将包含JWT、client_id、client_secret的POST请求发送到IMS身份验证服务。 | AEM Forms CS |
| 2022 年 2 月 | [在生成的pdf中嵌入字体](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/developing-for-cloud-service/intellij-set-up.html?lang=en#add-the-fonts-module) | 文章 | 了解如何安装 [!DNL IntelliJ] 社区版。 | AEM Forms CS |
| 2022 年 2 月 | [进行POST调用](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-gen-formscs/merge-data-with-template.html) | 视频 | 了解如何使用必需的参数对端点进行HTTPPOST调用。 模板和数据文件将作为资源文件提供。 | Forms CS |
| 2022 年 2 月 | [从旧AEM原型迁移](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/developing-for-cloud-service/updating-project-archetype.html?lang=en) | 视频 | Desc. | Forms CS |
| 2022 年 2 月 | [将工作流数据的存储外部化到AEM Forms CS](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/create-aem-workflow/externalize-workflow.html?lang=en) | 视频 | 了解如何在Azure存储中存储工作流数据。 AEM Forms CS具有将工作流数据（如变量、附件等）存储在外部存储帐户中的新功能。 | AEM Forms CS |
| 2022 年 2 月 | [将Adobe Analytics与Experience Cloud设置自动化集成](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/sites/integrations/adobe-analytics-exc-setup-automation.html) | 视频 | 了解Experience Cloud设置自动化如何提供一种简单、自动的方式，将Experience Manager Sites与Experience Platform Launch和Adobe Analytics集成并设计工具。 | AEM Sites |
| 2022 年 2 月 | [产品推荐](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/content-and-commerce/storefront/authoring/product-recommendations.html) | 视频 | 了解如何在Adobe Experience Manager(AEM)店面中动态插入这些产品推荐。 Adobe Commerce提供由Adobe Sensei提供支持的推荐引擎。 | AEM和Adobe Commerce |

{style=&quot;table-layout:auto&quot;}

### Experience Manager 发行信息

所有的 Experience Manager 发行说明均保留在以下页面：

* [Experience Manager as a Cloud Service 版本信息](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=en)
* [Experience Manager Cloud Manager 发行说明](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=zh-Hans)
* [Automated Forms Conversion Service 发行说明](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=zh-Hans)
* [Experience Manager 6.5 Service Pack 发行说明](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=en)
* [Experience Manager 6.4 Cumulative Fix Pack 发行说明](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=zh-Hans)
* [Experience Manager Assets Dynamic Media 发行说明](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=zh-Hans)
* [Experience Manager Brand Portal 发行说明](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=zh-Hans)
* [Experience Manager 桌面应用程序发行说明](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=zh-Hans)
* [Experience Manager Dispatcher 发行说明](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=zh-Hans)
* [Adobe Primetime 发行说明](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html?lang=zh-Hans)
* [Livefyre 发行说明](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=zh-Hans)

### Experience Manager 的其他帮助资源

* [Experience Manager Sites as a Cloud Service 指南](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/home.html?lang=en)
* [Cloud Manager 用户指南](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=en)
* [Experience Manager 6.5 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=zh-Hans)
* [Experience Manager 6.4 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=zh-Hans)
* [Experience Manager 6.3 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=zh-Hans)
* [Experience Manager 6.2 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=zh-Hans#previous-updates)
* [Experience Manager 文档的旧版本](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Dynamic Media Classic 帮助主页](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=zh-Hans)
* [Experience Manager 文档：最近的更新](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=zh-Hans#aem-as-a-cloud-service)

## ![图标](/assets/ec_appicon_24.png) 适用于Adobe Experience Manager的XML Documentation {#xml-doc}

Adobe Experience Manager 的 XML 文档是部署在 AEM 上的应用程序。这是一个功能强大的企业级组件内容管理解决方案 (CCMS)，可在 Adobe Experience Manager 中启用原生 DITA 支持，使 AEM 能够处理基于 DITA 的内容创建和交付。

详细了解 [AEM 的 XML 文档](https://www.adobe.com/products/xml-documentation-for-experience-manager/features.html)。

### Adobe Experience Manager 的 XML 文档的新教程 {#tutorials-xml-doc}

为 Adobe Experience Manager 的 XML 文档发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 1 月 | [XML 文档发布](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/tutorials/release-info/latest-release-info.html?lang=en) | 视频 | 了解 Adobe Experience Manager 的 XML 文档，这是一个功能强大的企业级组件内容管理解决方案 (CCMS)。该解决方案在 Adobe Experience Manager 中启用原生 DITA 支持，使 AEM 能够处理基于 DITA 的内容创建和交付。 |
| 2022 年 1 月 | [使用 AEM 的 XML 文档生成输出](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/videos/output-generation/overview.html?lang=en) | 视频和文章 | 了解地图仪表板、报表、带有基线和条件的发布等内容。 |

{style=&quot;table-layout:auto&quot;}

### 其他资源

* [适用于Adobe Experience Manager的XML Documentation](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/videos/overview.html?lang=en)  — 关于Experience League的教程
* [Adobe Experience Manager学习与支持的XML文档](https://helpx.adobe.com/support/xml-documentation-for-experience-manager.html)  — 产品文档

## ![图标](/assets/magento.png) [!DNL Adobe Commerce] {#magento}

有关 Adobe Commerce 发行说明，请参阅以下链接：

* [Adobe Commerce 和 Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [适用于 Adobe Commerce 的云套件](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### 新的 Adobe Commerce 教程 {#tutorials-commerce}

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 2 月 | [升级Adobe Commerce/Magento Open Source](https://experienceleague.adobe.com/docs/commerce-operations/upgrade-guide/overview.html) | 用户指南 | 获取完成升级过程所需的所有帮助。 |
| 2022 年 2 月 | [Adobe Commerce 2.4升级研讨会](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/upgrade-workshop.html?lang=en) | 视频 | 了解在为下次升级到2.4.4或更高版本做准备时要遵循的步骤和最佳实践。 |
| 2022 年 2 月 | [使用 PhpStorm 上的升级兼容性工具](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/uct-phpstorm.html?lang=en) | 视频 | 了解如何使用 `PhpStorm` 插件 |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/target.png) [!DNL Adobe Target] {#target}

上次更新时间： **2022年2月1日**

* 有关预发行信息，请参阅 [Adobe Target预发行版](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=en)
* 有关当前信息，请参阅 [Adobe Target发行说明](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=en)

## ![图标](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign 提供了一种直观、自动的方式，以通过在线和离线营销渠道来交付一对一的消息。您现在可以利用根据客户习惯和偏好确定的体验，来预测客户的需求。

### 最新营销活动产品版本

详细了解最新发布的功能、改进和修复：

* (新建!) [Campaign Standard22.1版本](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=zh-Hans)
* [Campaign v8.2.10](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/release-notes.html?lang=zh-Hans)
* [Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=zh-Hans)

### [!DNL Campaign] 的新教程和课程 {#tutorials-campaign}

为 Adobe Campaign 发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 | 版本 |
| ------| ----- | -----| ------ | --- |
| 2022 年 2 月 | [使用Adobe Campaign工作流进行数据管理的基础知识](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/data-management/data-management-fundamentals.html?lang=en) | 视频 | 了解哪些定向维度和工作表，以及Adobe Campaign如何跨不同数据源管理数据。 | Campaign v8 |
| 2022 年 2 月 | [更改数据源](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/data-management/change-data-source.html?lang=en) | 视频 | 了解如何使用更改数据源活动来更改工作流工作表的数据源，以便灵活管理跨不同数据源（如FDA、FFDA和本地数据库）的数据。 | Campaign v8 |

{style=&quot;table-layout:auto&quot;}

### 营销活动帮助资源

* Adobe Campaign v8：[文档](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/whats-new.html?lang=zh-Hans) — [《实施指南》](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=zh-Hans)
* Adobe Campaign Standard：[Campaign Standard 文档](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) — [操作方法视频](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=zh-Hans) — [发行计划](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=zh-Hans) — [最新文档更新](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=zh-Hans)
* Adobe Campaign Classic：[Campaign Classic v7 文档](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) — [操作方法视频](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=zh-Hans) — [最新文档更新](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=zh-Hans)
* Adobe Campaign 控制面板：[文档](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=zh-Hans) - 有关 [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=zh-Hans)/[Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=zh-Hans) 的操作方法视频

## ![Icon](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

借助 Journey Optimizer，您可以通过单个应用程序为数百万客户管理预定的全渠道营销活动和一对一互动时刻，整个历程都通过智能决策和见解得到了优化。

### 最新 Journey Optimizer 产品版本

有关最新的功能、改进和修复的详细信息，请参见 [Journey Optimizer 发行说明](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=zh-Hans)。

### [!DNL Journey Optimizer] 的更多资源

* [Journey Optimizer 文档](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html) — [发行说明](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) — [操作方法视频](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=zh-Hans)
* [Decision Management 文档](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started-decision/starting-offer-decisioning.html) — [发行说明](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) — [操作方法视频](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/introduction-to-offer-decisioning.html?lang=zh-Hans) — [最新文档更新](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=zh-Hans)

## ![图标](/assets/experience_platform_appicon_24.png) [!DNL Adobe Journey Orchestration] {#journey-orch}

凭借 Experience Platform，可以实时智能化预测每位客户的需求，从而实现跨体验渠道大规模编排客户历程。

### 最新 [!DNL Journey Orchestration] 产品版本

有关最新的功能、改进和修复的详细信息，请参阅[[!DNL Journey Orchestration] 发行说明](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=zh-Hans)。

#### [!DNL Journey Orchestration] 的更多资源

* [Journey Orchestration 文档](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) — [操作方法视频](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=zh-Hans) — [最新文档更新](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=zh-Hans)

## ![图标](/assets/marketo.png) [!DNL Adobe Marketo Engage] {#marketo}

[!DNL Marketo Engage] 是一个全面的应用程序，适用于寻求通过积极参与复杂购买过程的每个阶段而改善客户体验的销售线索管理和 B2B 营销人员。

### 核心 Marketo Engage 更新

有关最新的发布计划信息和发行说明，请参阅[!DNL Marketo Engage] [发布计划](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=zh-Hans)。

## ![图标](/assets/workfront.png) [!DNL Adobe Workfront] {#workfront}

Adobe [!DNL Workfront] 是一个统一的工作管理应用程序，可用于分享创意、创建内容、管理复杂的流程以及将工作做到尽善尽美。

请参阅[[!DNL Workfront] 版本](https://one.workfront.com/s/product-releases)页面，查看所有产品的最新信息综述。

## ![图标](/assets/advertising-cloud.png) Adobe Advertising Cloud {#adcloud}

[!DNL Adobe Advertising Cloud] 的发行说明。

* [ [!DNL Advertising Cloud] 中的新增功能](#adcloud-all)
* [ [!DNL Advertising Cloud DSP] 中的新增功能](#adcloud-dsp)
* [ [!DNL Advertising Cloud Search] 中的新增功能](#adcloud-search)
* [ [!DNL Advertising Cloud] 的新教程](#tutorials-ad-cloud)

### [!DNL Advertising Cloud] 中的新增功能 {#adcloud-all}

上次更新日期：**2021 年 10 月 27 日**

| 功能 | 描述 |
| ------- | ----------- |
| 适用于 Advertising Cloud 的 Analytics | 如果贵组织希望从使用旧版Adobe Analytics `visitorAPI.js` 库到Adobe Experience Platform库(`alloy.js`)，则必须进行更改才能启用ID拼合。 请参阅[将 [!DNL Last Event Service] JavaScript 库与 Adobe Experience Platform 结合使用 [!DNL Web SDK]](https://experienceleague.adobe.com/docs/advertising-cloud/integrations/analytics/planning/web-sdk.html?lang=zh-Hans)。 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Advertising Cloud DSP] 中的新增功能 {#adcloud-dsp}

上次更新日期：**2021 年 10 月 27 日**

| 功能 | 描述 |
| ------- | ----------- |
| 自定义报表 | 您现在可以为自定义报表创建和管理 [!DNL Amazon S3] 以及不同类型的 FTP 投放位置（称作 *[!DNL report destinations]*）。在配置报表目标后，您可以将每个新的自定义报表设置为发送到单一目标类型的一个或多个位置，或发送给电子邮件收件人。更新 [!DNL Amazon S3] 和 FTP 凭据将不会中断报表投放。<br><br>您现有的报表仍会发送给指定的电子邮件收件人。要配置针对不同报表目标的投放，请创建具有新目标的报表。 |
| [!UICONTROL 包]、[!UICONTROL 投放位置]和[!UICONTROL 广告]视图 | 在查看一天的数据时，趋势图现在包含每小时数据。将光标悬停在任意小时上可查看该小时的数据。 |
| [!UICONTROL 投放位置] | 投放[!UICONTROL 检查器]现在包含[!UICONTROL 库存]选项卡，该选项卡显示投放的所有交易及其关联量度。使用这些信息可快速做出调整或解决问题，而无需生成自定义报表。 |
| [!UICONTROL 广告] | （有权在其广告中包含 Clearcastclock 编号的用户）如果您使用附加到另一个广告的时钟编号，则 DSP 将不再显示错误。**注意：**&#x200B;最佳实践是为每个视频广告使用唯一的时钟编号。否则，发布者不会批准所有广告。 |
| [!UICONTROL 交易 ID] | 用户界面中的[!UICONTROL 交易 ID]设置和其他位置反映了 [!DNL Magnite] SSP 的新品牌化：<br><ul><li>SSP [!DNL Tremor] ([!DNL Telaria]) 现在为 [!DNL Magnite CTV]。</li><li>在接下来的几周内，[!DNL Rubicon] 将更改为 [!DNL Magnite DV+]，其中 [!DNL DV+] 代表显示、视频和其他格式，例如音频。</li></ul> |
| [!DNL Freewheel] 以编程方式保证交易 | 您现在可以从[!UICONTROL 广告]视图中查找 [!DNL Freewheel] 以编程方式保证交易的广告状态。之前，您只能从[!UICONTROL 交易]视图中查看状态。 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Advertising Cloud Search] 中的新增功能 {#adcloud-search}

上次更新时间： **2022年2月16日**

| 功能 | 描述 |
| ------- | ----------- |
| [!UICONTROL 促销活动], [!UICONTROL 批量处理工作表] | （1月22日发布）([!DNL Microsoft Advertising accounts])您现在可以通过 [!UICONTROL 促销活动] > [!UICONTROL 广告] 查看和从 [!UICONTROL 促销活动] > [!UICONTROL 批量工作表]. |
| [!UICONTROL 批量工作表], [!UICONTROL 通知中心] | （1月22日版）批量工作表的所有电子邮件通知现在由Advertising Cloud Search处理，批量工作表操作完成或失败时，会发送批量工作表 [!UICONTROL 通知中心].<br><br>[!UICONTROL 批量工作表] 是新的通知类型，具有自己的通知首选项，位于 [!UICONTROL 通知中心]. 电子邮件通知和Web通知默认启用，但您可以选择更改通知设置。<br><br>电子邮件通知的格式和内容使用 [!UICONTROL 通知中心] 模板，包括用于关联的批量工作表文件或错误文件的直接下载链接。 |

{style=&quot;table-layout:auto&quot;}

### Advertising Cloud 的新教程 {#tutorials-ad-cloud}

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 1 月 | [Advertising Cloud 教程](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/dsp/intro.html?lang=en) | 视频 | 提供了五个有关 Advertising Cloud DSP 的新视频教程。 |

## ![图标](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

为 Adobe Document Cloud 发布的新视频、教程或课程。

### Document Cloud 的新课程和教程 {#tutorials-doc-cloud}

为 Adobe Document Cloud 发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 2 月 | [使用表单字段](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/workforms.html?lang=en) | 视频 | 了解如何添加各种类型的表单字段、设置表单字段属性以及添加安全性以创建高质量的专业表单。 |
| 2022 年 2 月 | [Optimize PDF以进行SEO（搜索引擎优化）](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/optimizeseo.html) | 视频 | 了解如何优化PDF，以改进Web上的可发现性和搜索引擎排名。 |

{style=&quot;table-layout:auto&quot;}

有关 Document Cloud 的帮助，请参阅：

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=zh-Hans)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=zh-Hans)
* [Document Cloud 学习与支持](https://helpx.adobe.com/support/document-cloud.html)

## ![图标](/assets/creative-cloud-24.png) Adobe Creative Cloud 企业版 {#creative-cloud}

有关最新教程，请参阅 [Creative Cloud 企业版教程](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=zh-Hans)。

## Digital Experience Blueprint — 教程 {#blueprints}

[Digital Experience Blueprint](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=en) 是可重复实施，可让您解决策略并快速解决已建立的业务问题。 每个Blueprint都提供一系列工件，用于解释高价值业务问题、体系结构、实施步骤、技术考虑事项，以及相关文档的链接。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 2 月 | [客户历程](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/customer-journeys/overview.html?lang=en) | 视频 | 客户历程可让品牌通过电子邮件、短信和移动警报等渠道，积极地与其客户互动并与其沟通。 |
| 2022 年 2 月 | [Campaign v7 Blueprint](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/customer-journeys/campaign-v7/campaign-v7.html?lang=en) | 视频 | Adobe Campaign v7是一款针对电子邮件和直邮等传统营销渠道而构建的活动工具。 它提供了强大的ETL和数据管理功能，以帮助策划和策划完美的营销活动。 |

{style=&quot;table-layout:auto&quot;}
