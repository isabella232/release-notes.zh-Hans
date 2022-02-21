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
ht-degree: 99%

---

# Adobe Experience Cloud 发行说明 - 2022 年 2 月

![横幅](assets/experience-cloud-banner-3.png)

作为体验创造者，您的成功之路始于 [Adobe Experience League](https://experienceleague.adobe.com/?lang=en#home)。查找适用于所有级别和角色的庞大操作文档库、自学教程、操作视频和课程，还有同行网络社区以及需要时的专家支持。

准备好开始了吗？[参加 5 分钟的测验并获胜](https://exploreadobe.com/experience-league-quiz/?sdid=4NM897N2&amp;mv=email&amp;mv2=nslsp)！

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
* [数字体验 Blueprint - 教程](#blueprints)

需要帮助？请访问 [Adobe Experience League](https://experienceleague.adobe.com/?lang=zh-Hans/#home)，获取产品和技术文档、Adobe 策划课程、视频教程、快速解答、社区洞察以及由讲师指导的培训。

## ![图标](/assets/experience-league.png) [!DNL Experience League] 活动 {#events}

Experience League 活动是从 Adobe 产品专家处获得答案的好地方。三种类型的事件包括：

| 事件类型 | 描述 |
| -----------|---------- |
| [Experience League LIVE](#exl-live) | 由 Experience League 团队制作并在 YouTube 上托管的直播节目。利用这个机会，您可以与 Adobe 产品专家联系。学习可用于 Adobe Experience Cloud 应用程序的可操作性提示、技巧和策略。<br> 向下滚动以详细了解即将举行的活动并观看在 [Experience League Live](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=zh-Hans) 上托管的过去事件。 |
| [社区问答喝咖啡休息时间](#coffee) | 与特邀嘉宾共度一小时，并在 Experience League 社区中提交您的问题！从 Adobe 的产品专家那里获得问题的答案。喝杯咖啡，与 Experience League 社区的产品经理聊天。<br>向下滚动以了解我们将介绍的内容。不要忘记在为时已晚之前注册！ |
| [Adobe [!DNL Developers Live]](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2021/oct2021/overview.html?lang=zh-Hans) | Experience League 提供点播视频活动。 |

{style=&quot;table-layout:auto&quot;}

### Experience League LIVE{#exl-live}

| 活动日期 | 时间 | 活动名称 | 格式 | 描述 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022 年 2 月 3 日 | 按需 | [在 AEM 中引入所有新的参考演示](https://www.youtube.com/watch?v=FEREXV826NQ) | 视频直播活动 | 了解配置、演示和探索 AEM as a Cloud Service 功能的最快方法。 |

{style=&quot;table-layout:auto&quot;}

### 社区问答喝咖啡休息时间{#coffee}

| 活动名称 | 日期 | 应用程序 | 格式 | 描述 |
| -----------| ---------- | ---------- | ---------- |---------- |
| Adobe Target 社区问答喝咖啡休息时间 | 2022 年 2 月 23 日，上午 8 点（太平洋标准时间） | Adobe Target，Experience Platform，RTCDP | 论坛问答 | [立即注册](http://atcommunityqacoffeebreak.splashthat.com/?utm_source=in-product&amp;utm_medium=gainsight&amp;utm_campaign=coffee_talk_AT&amp;utm_content=220223)！ 从太平洋时间上午 8 点到上午 9 点加入 Adobe Target 社区，从高级产品经理 Vishal Chordia 那里获得专家解答。他将回答您的所有 Adobe Experience Platform (AEP)、基于受众的个性化、Real-time Customer Data Platform (RTCDP) 和 Target 的集成问题以及与 Adobe Target 相关的一般问题 |

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

* Adobe Status 现在报告产品级别的事件。状态云和产品页面具有新外观和基于产品级事件报告的增强过滤器。这让您更容易地在 [status.adobe.com](https://status.adobe.com/) 和电子邮件通知中了解您的产品受到什么影响。如果您未订阅，请使用此链接设置个性化订阅偏好 [https://status.adobe.com/proactive-notifications/manage](https://status.adobe.com/proactive-notifications/manage)。

* 状态主页现在使用根据您的权利和产品订阅过滤的事件进行个性化。请在 **status.adobe.com** > **[!UICONTROL “我的事件”]**&#x200B;选项卡中查看。

**当前可用的新增功能和增强功能**

| 功能 | 描述 |
| ------- | -------|
| 产品级事件报告 | <ul><li>每个产品都在[!UICONTROL 状态]上有横幅，其中包括产品的最新更新、历史记录和影响属性</li><li>电子邮件现在遵循与产品级影响报告（而不是事件级报告）相同的格式</li></ul> |
| [!UICONTROL “状态”]主页的个性化视图 | <ul><li>在[!UICONTROL “概述”]页面上引入新视图&#x200B;**[!UICONTROL “我的事件”]**。该视图根据您的权利和订阅过滤事件</li><li>权利可以针对组织或个人。订阅可以是产品或事件</li></ul> |
| 增强的用户体验 | <ul><li>云页面汇总了所有产品的可用性，并能够按产品、地区、日期和事件类型进行过滤</li><li>产品页面包含所有功能可用性的摘要以及事件和历史的详细视图</li><li>可按功能、数据中心/环境（如适用）、地区、日期、事件类型和事件/维护状态提供增强的过滤器</li></ul> |
| 包含产品更新的增强订阅 | <ul><li>Adobe Analytics 产品/服务更新为对客户友好的视图（现有 [!DNL Analytics] 订阅迁移到新产品/服务）</li><li>[!DNL Customer Journey Analytics] 的粒度产品/服务</li></ul> |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/ec_appicon_24.png) [!DNL Experience Cloud Central UI Components] 和管理 {#ecloud}

| 功能 | 描述 |
| ------- |-------|
| **[!UICONTROL “最近访问”]**（快捷方式）添加到 [Experience Cloud](https://experience.adobe.com/home) 登陆页 | 您可以在新的&#x200B;**[!UICONTROL “最近访问”]**&#x200B;标题下访问您最近的 Journey Optimizer 和 Experience Platform 活动的快捷方式。该更新还包括登陆页上的总体布局和响应性改进。 |
| **[!UICONTROL “沙盒”]**&#x200B;移动到标题栏 | “沙盒”指示器现在集成在所有 Experience Platform 界面应用程序的标题中。有关详细信息，请参阅 Experience Platform 中的[“沙盒”](https://experienceleague.adobe.com/docs/experience-platform/sandbox/ui/user-guide.html?lang=zh-Hans)。 |

{style=&quot;table-layout:auto&quot;}

**关于 [!DNL Experience Cloud Central UI Components] 和管理**&#x200B;的更多帮助资源

* Experience Cloud 中央 UI 组件的[发行说明](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=zh-Hans)
* Experience Cloud 的[用户和产品管理](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=zh-Hans)（管理）
* 放置服务[发行说明](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=zh-Hans)
* [人员 - 客户属性和受众库](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=zh-Hans)的产品文档

## ![图标](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Experience Platform 和 [!UICONTROL Mobile SDK] 的最新发行信息和新文档：

发行日期：**2022 年 1 月 26 日**

* [Experience Platform 发行说明](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=zh-Hans)

### Experience Platform 的新教程和课程 {#tutorials-platform}

为 Experience Platform 发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 2 月 | [利用 Web SDK 实施 Adobe Experience Cloud](https://experienceleague.adobe.com/docs/platform-learn/implement-web-sdk/overview.html?lang=zh-Hans) | 多页面教程 | 了解如何使用 Adobe Experience Platform Web SDK 实施 Experience Cloud 应用程序。本教程向您展示如何使用名为 _Luma_ 的样品零售网站来实施 Platform Web SDK。[Luma](https://luma.enablementadobe.com/content/luma/us/en.html) 站点具有丰富的数据层和功能，可让您构建现实的实施。现在就开始！ |
| 2022 年 2 月 | [使用实时 CDP 和 Adobe Target 实现下一次点击个性化](https://experienceleague.adobe.com/docs/platform-learn/tutorials/experience-cloud/next-hit-personalization.html?lang=zh-Hans) | 视频 | 了解如何使用 [!UICONTROL Real-time Customer Data Platform] 和 Adobe Target 在下一次点击时个性化Real-time CDP 中的 Adobe Target 目的地允许您使用 Adobe Target 中的 Experience Platform 区段来实现具有治理和隐私支持的同页和下一页个性化。 |

{style=&quot;table-layout:auto&quot;}

### Adobe Mobile SDK

请参阅 Adobe Experience Platform Mobile SDK 的[发行说明和更改日志](https://aep-sdks.gitbook.io/docs/release-notes)。

## ![图标](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

发行日期：**2022 年 2 月 16 日**

* Adobe Analytics [发行说明](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=zh-Hans)（**新位置**）
* Adobe Analytics [产品文档和教程](https://experienceleague.adobe.com/docs/analytics.html?lang=zh-Hans)

### [!DNL Customer Journey Analytics] {#cja}

发行日期：**2022 年 2 月 16 日**

* Customer Journey Analytics [发行说明](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=zh-Hans)（**新位置**）
* Customer Journey Analytics [产品文档和教程](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=zh-Hans)

### AppMeasurement {#appm}

发行版本：**2.22.4**

* [AppMeasurement for JavaScript 发行说明](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=zh-Hans)

### Analytics 的新教程和课程 {#tutorials-analytics}

为 Adobe Analytics 发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 2 月 | [使用处理规则处理传入的数据](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/manipulating-incoming-data-with-processing-rules.html?lang=zh-Hans) | 视频 | 概述 Adobe Analytics 中的处理规则，并了解其用途。 了解一些提示、示例甚至警告。 |
| 2022 年 2 月 | [配置列表变量](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configuring-list-variables.html?lang=zh-Hans) | 视频 | 当您必须一次性将多个值放入 eVar（转化变量）中时，您会怎么做？ 要取回的列表变量！ 了解如何以及为何在 Adobe Analytics 中配置和使用列表变量。 |
| 2022 年 2 月 | [配置流量分类](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configure-traffic-classifications.html?lang=zh-Hans) | 视频 | 了解如何为流量变量（通常称为 _props_），以及为 _pagename_ 等配置分类。 |
| 2022 年 2 月 | [配置转化分类](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configure-conversion-classifications.html?lang=zh-Hans) | 视频 | 了解如何为转化变量（也称为 _eVars_）配置分类。该配置也适用于产品和列表变量。 |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager 中的修复和改进。

* 解决了通过 Swagger 接口执行时导致所有 API 调用返回 `Undocumented` 错误的问题。(AAM-59190)
* 解决了导致在某些情况下将错误的用户角色分配给合作伙伴的问题。(AAM-59451)
* 解决了导致 API 需要区分大小写的身份验证标头的问题。(AAM-58528)

有关自助资源，请参阅 Experience League 上的 [Audience Manager 文档和教程](https://experienceleague.adobe.com/docs/audience-manager.html?lang=zh-Hans)

## ![图标](/assets/aem.png) Adobe Experience Manager {#aem}

Adobe 建议访问 [Experience Manager 版本更新和路线图](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=zh-Hans)页面以及时了解版本信息。

### Experience Manager 产品版本

* **Experience Manager as a Cloud Service**

   观看 [2022 年 1 月发布概述视频](https://video.tv.adobe.com/v/340120)，大致了解 2022.1.0 版（2022 年 1 月）的新增功能。

   * [](https://video.tv.adobe.com/v/339278)2021 年 12 月版新增功能概述视频。
   * [2021 年 10 月版新增功能概述视频](https://video.tv.adobe.com/v/338253)。
   * [2021 年 9 月版新增功能概述视频](https://video.tv.adobe.com/v/337381)。

   * **Experience Manager Assets as a Cloud Service**

      _Experience Manager Assets 的新增功能_

      * Dynamic Media - 您现在可以使用 Experience Manager - Dynamic Media 界面配置[常规设置](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-general-settings.html?lang=zh-Hans)和[发布设置](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-publish-settings.html?lang=zh-Hans)，而不必使用 Dynamic Media Classic 桌面应用程序。
      * Dynamic Media 现在支持 MXF 视频的提取、预览、播放和发布。尚不支持 MXF 视频的注释和可购买视频。
      * 在配置远程 DAM 和 Sites 部署之间的连接后，远程 DAM 上的资源即可用于 Sites 部署。您现在可以对远程 DAM 资源或文件夹执行[更新、删除、重命名和移动操作](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/admin/use-assets-across-connected-assets-instances.html?lang=zh-Hans)。更新会在 Sites 部署中自动提供，但会有一些延迟。

      _Experience Manager Assets 预发行渠道中的新增功能_

      * Dynamic Media 现在提供了灵活性，让您可以在用户界面中[配置一个公司别名账户](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-alias-account.html?lang=zh-Hans)，以便开箱即用的 Dynamic Media URL 和查看器嵌入代码实时更新。该操作会对 SEO 产生积极影响，以反映对您的业务环境（如品牌再造）所做的更新。
      * 您现在可以使用 Experience Manager Assets 用户界面执行以下操作：

         * 配置对存储库中重复资源的检测。
         * 配置向图像添加数字水印。
      * 管理员现在可以为大型下载配置电子邮件服务。它让用户可以从 Experience Manager Assets 界面为[大型下载启用电子邮件通知](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/download-assets-from-aem.html?lang=zh-Hans#enable-email-notifications-for-large-downloads)。下载过程完成后，用户会收到电子邮件通知，其中包含已存档 zip 文件夹的下载链接。
      * [管理发布](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=zh-Hans)功能通过改进的用户界面得到增强。用户可以在所选目的地发布或取消发布内容，以及向 DAM 存储库中的发布列表[添加内容](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=zh-Hans#add-content)。它们还可以[包括文件夹设置](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=zh-Hans#include-folder-settings)以发布所选文件夹的内容并应用过滤器，以及[将发布安排](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=zh-Hans#publish-assets-later)到以后的日期或时间。

      _错误修复_

      * 将资产从 Experience Manager 内部部署迁移到云服务时，没有原始演绎版的未处理资产将被发送到 Asset Compute 进行处理。
   * **Experience Manager Forms as a Cloud Service**

      _Forms 的新增功能_

      * **Experience Manager Forms as a Cloud Service - 通信** — [通信 API](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/using-communications/aem-forms-cloud-service-communications.html?lang=zh-Hans) 可帮助您组合模板和 XML 数据以生成各种格式的打印文档。该服务让您能够以同步和批处理模式生成文档。这些 API 帮助您创建可让您完成以下任务的应用程序：

         * 使用 XML 数据填充模板文件来生成文档。
         * 生成各种格式的表单，包括非交互式 PDF 打印流。
         * 从 XFA 表单 PDF 生成打印 PDF。
         * 通过将多组数据与源模板合并，批量生成 PDF、PostScript、PCL 和 ZPL 文档。
      * **使用 Communications API 创建的记录文档和 PDF 文档的自定义字体** — 您现在可以在使用 Communications API 生成的 PDF 文档中使用品牌批准的字体，以满足贵企业的要求。

      _Forms 预发行渠道中的新增功能_

      * [Assembler API](https://developer.adobe.com/experience-manager-forms-cloud-service-developer-reference/references/assembler-sync/) — Assembler API 用于组合、重新排列、扩充和获取有关 PDF 文档的信息。
   * **Cloud Manager**

      _发行日期_

      Experience Manager as a Cloud Service 2022.01.0 中的 Cloud Manager 的发布日期是 2022 年 1 月 20 日。下一个版本计划于 2022 年 2 月 10 日发布。

      _新增功能_

      * 当检测到在多个全栈管道执行中使用了](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/create-application-project/setting-up-project.html?lang=zh-Hans#build-artifact-reuse)相同的 git commit 时，Cloud Manager [可避免重建代码库。
      * 访问 Experience Manager 环境日志现在需要 **[!UICONTROL Deployment Manager]** 产品配置文件。没有此配置文件的用户会在用户界面中看到一个禁用的按钮。
      * 对于未将站点作为解决方案启用的程序，该用户界面不允许进行前端管道配置。
      * 生成 git 密码后，将会显示到期日期。








### 社区

* **Experience Manager GEM 网络研讨会：_使用 Experience Manager Headless 和 App Builder 更快地构建站点_**

   **日期**：2022 年 3 月 23 日，星期三
   **时间**：上午 8:00（太平洋标准时间）或者 5:00（中欧标准时间）或 9:00（印度时间）
   **发言者**：Adobe 软件开发工程师 Duy Nguyen
   [在以下位置注册网络研讨会：https://adobe.ly/3oCkEsh](https://adobe.ly/3oCkEsh)
   [关于网络研讨会的常见问题](https://adobe.ly/3LkSWdm)

* 播放 2022 年 1 月的 Experience Manager GEM 网络研讨会：[_Experience Manager as a Cloud Service 2021 年回顾和 2022 年展望_](https://adobe.ly/3rqbSOz)

### Experience Manager 的新课程和教程 {#tutorials-aem}

过去一个月发布的新视频、教程及课程。

| 发布日期 | 名称 | 类型 | 描述 | 应用程序 |
| ------| ------| ----- | -----| ----|
| 2022 年 2 月 | [创建服务凭据](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-gen-formscs/service-credentials.html?lang=zh-Hans) | 视频 | 了解如何创建服务凭据以确保您与 AEM as a Cloud Service 集成的安全身份验证。 | AEM Forms CS |
| 2022 年 2 月 | [创建 JSON Web 令牌 (JWT)](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-gen-formscs/create-jwt.html?lang=zh-Hans) | 文章 | 了解 JSON Web 令牌，这是一种开放的行业标准 RFC 7519 方法，用于在两方之间安全地表示声明。此示例中使用 `JWT.io` 库来生成 JWT。 | AEM Forms CS |
| 2022 年 2 月 | [用 JWT 交换访问令牌](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-gen-formscs/create-access-token.html?lang=zh-Hans) | 文章 | 在[创建 JSON Web 令牌 (JWT)](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-gen-formscs/create-jwt.html)步骤中创建的 JWT 与 Adobe IMS API 交换访问令牌，然后该令牌可用于访问 AEM as a Cloud Service。了解如何请求访问令牌以将包含 JWT、client_id、client_secret 的 POST 请求发送到 IMS 身份验证服务。 | AEM Forms CS |
| 2022 年 2 月 | [在生成的 pdf 中嵌入字体](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/developing-for-cloud-service/intellij-set-up.html?lang=zh-Hans#add-the-fonts-module) | 文章 | 了解如何安装 [!DNL IntelliJ] 社区版。 | AEM Forms CS |
| 2022 年 2 月 | [进行 POST 调用](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-gen-formscs/merge-data-with-template.html?lang=zh-Hans) | 视频 | 了解如何使用必要的参数对端点进行 HTTP POST 调用。模板和数据文件作为资源文件提供。 | Forms CS |
| 2022 年 2 月 | [从旧 AEM 原型迁移](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/developing-for-cloud-service/updating-project-archetype.html?lang=zh-Hans) | 视频 | 说明 | Forms CS |
| 2022 年 2 月 | [在 AEM Forms CS 中外部化工作流数据的存储](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/create-aem-workflow/externalize-workflow.html?lang=zh-Hans) | 视频 | 了解如何将工作流数据存储在 Azure 存储中。AEM Forms CS 具有将工作流数据（例如变量、附件等）存储在外部存储帐户中的新功能。 | AEM Forms CS |
| 2022 年 2 月 | [将 Adobe Analytics 与 Experience Cloud 设置自动化集成](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/sites/integrations/adobe-analytics-exc-setup-automation.html?lang=zh-Hans) | 视频 | 了解 Experience Cloud 设置自动化如何提供一种简单且自动化的方式，将 Experience Manager Sites 与 Experience Platform Launch 和 Adobe Analytics 集成和装备到一起。 | AEM Sites |
| 2022 年 2 月 | [产品推荐](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/content-and-commerce/storefront/authoring/product-recommendations.html?lang=zh-Hans) | 视频 | 了解如何在 Adobe Experience Manager (AEM) 店面中动态插入这些产品推荐。Adobe Commerce 具有由 Adobe Sensei 提供支持的推荐引擎。 | AEM 和 Adobe Commerce |

{style=&quot;table-layout:auto&quot;}

### Experience Manager 发行信息

所有的 Experience Manager 发行说明均保留在以下页面：

* [Experience Manager as a Cloud Service 版本信息](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=zh-Hans)
* [Experience Manager Cloud Manager 发行说明](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=zh-Hans)
* [Automated Forms Conversion Service 发行说明](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=zh-Hans)
* [Experience Manager 6.5 Service Pack 发行说明](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=zh-Hans)
* [Experience Manager 6.4 Cumulative Fix Pack 发行说明](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=zh-Hans)
* [Experience Manager Assets Dynamic Media 发行说明](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=zh-Hans)
* [Experience Manager Brand Portal 发行说明](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=zh-Hans)
* [Experience Manager 桌面应用程序发行说明](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=zh-Hans)
* [Experience Manager Dispatcher 发行说明](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=zh-Hans)
* [Adobe Primetime 发行说明](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html?lang=zh-Hans)
* [Livefyre 发行说明](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=zh-Hans)

### Experience Manager 的其他帮助资源

* [Experience Manager Sites as a Cloud Service 指南](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/home.html?lang=zh-Hans)
* [Cloud Manager 用户指南](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=zh-Hans)
* [Experience Manager 6.5 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=zh-Hans)
* [Experience Manager 6.4 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=zh-Hans)
* [Experience Manager 6.3 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=zh-Hans)
* [Experience Manager 6.2 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=zh-Hans#previous-updates)
* [Experience Manager 文档的旧版本](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Dynamic Media Classic 帮助主页](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=zh-Hans)
* [Experience Manager 文档：最近的更新](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=zh-Hans#aem-as-a-cloud-service)

## ![Icon](/assets/ec_appicon_24.png)Adobe Experience Manager 的 XML 文档 {#xml-doc}

Adobe Experience Manager 的 XML 文档是部署在 AEM 上的应用程序。这是一个功能强大的企业级组件内容管理解决方案 (CCMS)，可在 Adobe Experience Manager 中启用原生 DITA 支持，使 AEM 能够处理基于 DITA 的内容创建和交付。

详细了解 [AEM 的 XML 文档](https://www.adobe.com/cn/products/xml-documentation-for-experience-manager/features.html)。

### Adobe Experience Manager 的 XML 文档的新教程 {#tutorials-xml-doc}

为 Adobe Experience Manager 的 XML 文档发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 1 月 | [XML 文档发布](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/tutorials/release-info/latest-release-info.html?lang=zh-Hans) | 视频 | 了解 Adobe Experience Manager 的 XML 文档，这是一个功能强大的企业级组件内容管理解决方案 (CCMS)。该解决方案在 Adobe Experience Manager 中启用原生 DITA 支持，使 AEM 能够处理基于 DITA 的内容创建和交付。 |
| 2022 年 1 月 | [使用 AEM 的 XML 文档生成输出](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/videos/output-generation/overview.html?lang=zh-Hans) | 视频和文章 | 了解地图仪表板、报表、带有基线和条件的发布等内容。 |

{style=&quot;table-layout:auto&quot;}

### 其他资源

* [Adobe Experience Manager 的 XML 文档](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/videos/overview.html?lang=zh-Hans) - Experience League 上的教程
* [Adobe Experience Manager 学习和支持的 XML 文档](https://helpx.adobe.com/cn/support/xml-documentation-for-experience-manager.html) - 产品文档

## ![图标](/assets/magento.png) [!DNL Adobe Commerce] {#magento}

有关 Adobe Commerce 发行说明，请参阅以下链接：

* [Adobe Commerce 和 Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [适用于 Adobe Commerce 的云套件](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### 新的 Adobe Commerce 教程 {#tutorials-commerce}

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 2 月 | [升级 Adobe Commerce/Magento Open Source](https://experienceleague.adobe.com/docs/commerce-operations/upgrade-guide/overview.html?lang=zh-Hans) | 用户指南 | 获得完成升级过程所需的所有帮助。 |
| 2022 年 2 月 | [Adobe Commerce 2.4 升级研讨会](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/upgrade-workshop.html?lang=zh-Hans) | 视频 | 了解在准备下一次升级到 2.4.4 或更高版本时要遵循的步骤和最佳实践。 |
| 2022 年 2 月 | [使用 PhpStorm 上的升级兼容性工具](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/uct-phpstorm.html?lang=zh-Hans) | 视频 | 了解如何使用 `PhpStorm` 插件 |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/target.png) [!DNL Adobe Target] {#target}

上次更新时间：**2022 年 2 月 1 日**

* 有关预发行信息，请参阅 [Adobe Target 预发行](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=zh-Hans)
* 有关最新信息，请参阅 [Adobe Target 发行说明](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=zh-Hans)

## ![图标](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign 提供了一种直观、自动的方式，以通过在线和离线营销渠道来交付一对一的消息。您现在可以利用根据客户习惯和偏好确定的体验，来预测客户的需求。

### 最新营销活动产品版本

详细了解最新发布的功能、改进和修复：

* (新建!) [Campaign Standard 22.1 版](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=zh-Hans)
* [Campaign v8.2.10](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/release-notes.html?lang=zh-Hans)
* [Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=zh-Hans)

### [!DNL Campaign] 的新教程和课程 {#tutorials-campaign}

为 Adobe Campaign 发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 | 版本 |
| ------| ----- | -----| ------ | --- |
| 2022 年 2 月 | [使用 Adobe Campaign 工作流进行数据管理的基础知识](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/data-management/data-management-fundamentals.html?lang=zh-Hans) | 视频 | 了解什么是目标维度和工作表，以及 Adobe Campaign 如何跨不同数据源管理数据。 | Campaign v8 |
| 2022 年 2 月 | [更改数据源](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/data-management/change-data-source.html?lang=zh-Hans) | 视频 | 了解如何使用更改数据源活动来更改工作流工作表的数据源，以灵活管理不同数据源（如 FDA、FFDA 和本地数据库）的数据。 | Campaign v8 |

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

* [Journey Optimizer 文档](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) — [操作方法视频](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=zh-Hans)
* [Decision Management 文档](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started-decision/starting-offer-decisioning.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) — [操作方法视频](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/introduction-to-offer-decisioning.html?lang=zh-Hans) — [最新文档更新](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=zh-Hans)

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
| 适用于 Advertising Cloud 的 Analytics | 如果您的组织需要从使用旧版 Adobe Analytics `visitorAPI.js` 库转为使用 Adobe Experience Platform 库 (`alloy.js`) 来收集数据，则您必须进行更改来支持 ID 拼接。请参阅[将 [!DNL Last Event Service] JavaScript 库与 Adobe Experience Platform 结合使用 [!DNL Web SDK]](https://experienceleague.adobe.com/docs/advertising-cloud/integrations/analytics/planning/web-sdk.html?lang=zh-Hans)。 |

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

上次更新时间：**2022 年 2 月 16 日**

| 功能 | 描述 |
| ------- | ----------- |
| [!UICONTROL 促销活动], [!UICONTROL 批量处理工作表] | （1月22日发布）([!DNL Microsoft Advertising accounts])您现在可以通过 [!UICONTROL 促销活动] > [!UICONTROL 广告] 查看和从 [!UICONTROL 促销活动] > [!UICONTROL 批量工作表]. |
| [!UICONTROL 批量处理工作表]，[!UICONTROL 通知中心] | （1 月 22 日版）Advertising Cloud Search 在批量处理工作表操作完成或失败时发送的所有批量处理工作表电子邮件通知现在都由[!UICONTROL 通知中心]处理。<br><br>[!UICONTROL 批量处理工作表]是通知中心[!UICONTROL 通知中心]中一种新的通知类型，具有自己的通知偏好设置。默认情况下启用电子邮件通知和 Web 通知，但您可以选择更改通知设置。<br><br>电子邮件通知的格式和内容使用[!UICONTROL 通知中心]模板并包含相关批量处理工作表文件或错误文件的直接下载链接。 |

{style=&quot;table-layout:auto&quot;}

### Advertising Cloud 的新教程 {#tutorials-ad-cloud}

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 1 月 | [Advertising Cloud 教程](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/dsp/intro.html?lang=zh-Hans) | 视频 | 提供了五个有关 Advertising Cloud DSP 的新视频教程。 |

## ![图标](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

为 Adobe Document Cloud 发布的新视频、教程或课程。

### Document Cloud 的新课程和教程 {#tutorials-doc-cloud}

为 Adobe Document Cloud 发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 2 月 | [使用表单字段](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/workforms.html?lang=zh-Hans) | 视频 | 了解如何添加各种类型的表单字段、设置表单字段属性以及添加安全性以创建高质量的专业表单。 |
| 2022 年 2 月 | [针对 SEO 优化 PDF（搜索引擎优化）](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/optimizeseo.html?lang=zh-Hans) | 视频 | 了解如何优化 PDF 以提高在网络上的可发现性和搜索引擎排名。 |

{style=&quot;table-layout:auto&quot;}

有关 Document Cloud 的帮助，请参阅：

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=zh-Hans)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=zh-Hans)
* [Document Cloud 学习与支持](https://helpx.adobe.com/cn/support/document-cloud.html)

## ![图标](/assets/creative-cloud-24.png) Adobe Creative Cloud 企业版 {#creative-cloud}

有关最新教程，请参阅 [Creative Cloud 企业版教程](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=zh-Hans)。

## 数字体验 Blueprint - 教程 {#blueprints}

[数字体验 Blueprint](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=zh-Hans) 是可重复的实施，让您可以满足战略需求和解决已确定的业务问题。每个 Blueprint 都提供了一系列构件，这些构件说明了高价值业务问题、体系结构、实施步骤、技术注意事项以及指向相关文档的链接。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 2 月 | [客户历程](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/customer-journeys/overview.html?lang=zh-Hans) | 视频 | 客户历程能让品牌商通过电子邮件、短信和移动提醒等渠道，积极与客户互动和通信。 |
| 2022 年 2 月 | [Campaign v7 Blueprint](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/customer-journeys/campaign-v7/campaign-v7.html?lang=zh-Hans) | 视频 | Adobe Campaign v7 是为传统营销渠道（如电子邮件和直邮）构建的营销工具。它提供强大的 ETL 和数据管理功能，以帮助制作和策划完美的活动。 |

{style=&quot;table-layout:auto&quot;}
