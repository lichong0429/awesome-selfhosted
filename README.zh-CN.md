# 精选自托管软件（Awesome-Selfhosted 中文版） <a id="awesome-selfhosted"></a>

**[English](README.md) · 简体中文**

[![Awesome](_static/awesome.png)](https://github.com/sindresorhus/awesome) [![](https://github.com/awesome-selfhosted/awesome-selfhosted-data/actions/workflows/check-dead-links.yml/badge.svg)](https://github.com/awesome-selfhosted/awesome-selfhosted-data/issues/1) [![](https://github.com/awesome-selfhosted/awesome-selfhosted-data/actions/workflows/check-unmaintained-projects.yml/badge.svg)](https://github.com/awesome-selfhosted/awesome-selfhosted-data/issues/1) [![](https://img.shields.io/liberapay/goal/awesome-selfhosted.svg?logo=liberapay)](https://liberapay.com/awesome-selfhosted/)

自托管（Self-hosting）是指在自己的服务器上托管和管理应用，而不是使用 [SaaSS](https://www.gnu.org/philosophy/who-does-that-server-really-serve.html) 提供商的服务。

本列表收录可托管在你自己服务器上的[自由](https://en.wikipedia.org/wiki/Free_software)软件[网络服务](https://en.wikipedia.org/wiki/Network_service)与[Web 应用](https://en.wikipedia.org/wiki/Web_application)。非自由软件列在[非自由](https://github.com/awesome-selfhosted/awesome-selfhosted/blob/master/non-free.md)页面。

**[HTML 版本](https://awesome-selfhosted.net/)（推荐）**，[Markdown 版本](https://github.com/awesome-selfhosted/awesome-selfhosted)（旧版）。

参见[贡献指南](#contributing)。
--------------------

## 目录 <a id="table-of-contents"></a>

- [软件](#software)
  - [分析统计](#analytics)
  - [归档与数字保存（DP）](#archiving-and-digital-preservation-dp)
  - [自动化](#automation)
  - [备份](#backup)
  - [博客平台](#blogging-platforms)
  - [预约与日程安排](#booking-and-scheduling)
  - [书签与链接分享](#bookmarks-and-link-sharing)
  - [日历与联系人](#calendar--contacts)
  - [通信 - 自定义通信系统](#communication---custom-communication-systems)
  - [通信 - 电子邮件 - 完整解决方案](#communication---email---complete-solutions)
  - [通信 - 电子邮件 - 邮件投递代理](#communication---email---mail-delivery-agents)
  - [通信 - 电子邮件 - 邮件传输代理](#communication---email---mail-transfer-agents)
  - [通信 - 电子邮件 - 邮件列表与通讯](#communication---email---mailing-lists-and-newsletters)
  - [通信 - 电子邮件 - 网页邮件客户端](#communication---email---webmail-clients)
  - [通信 - IRC](#communication---irc)
  - [通信 - SIP](#communication---sip)
  - [通信 - 社交网络与论坛](#communication---social-networks-and-forums)
  - [通信 - 视频会议](#communication---video-conferencing)
  - [通信 - XMPP - 服务器](#communication---xmpp---servers)
  - [通信 - XMPP - 网页客户端](#communication---xmpp---web-clients)
  - [社区支持农业（CSA）](#community-supported-agriculture-csa)
  - [会议管理](#conference-management)
  - [内容管理系统（CMS）](#content-management-systems-cms)
  - [客户关系管理（CRM）](#customer-relationship-management-crm)
  - [数据库管理](#database-management)
  - [DNS](#dns)
  - [文档管理](#document-management)
  - [文档管理 - 电子书](#document-management---e-books)
  - [文档管理 - 机构知识库与数字图书馆软件](#document-management---institutional-repository-and-digital-library-software)
  - [文档管理 - 集成图书馆系统（ILS）](#document-management---integrated-library-systems-ils)
  - [电子商务](#e-commerce)
  - [联合身份与认证](#federated-identity--authentication)
  - [RSS 阅读器](#feed-readers)
  - [文件传输与同步](#file-transfer--synchronization)
  - [文件传输 - 分布式文件系统](#file-transfer---distributed-filesystems)
  - [文件传输 - 对象存储与文件服务器](#file-transfer---object-storage--file-servers)
  - [文件传输 - 点对点文件共享](#file-transfer---peer-to-peer-filesharing)
  - [文件传输 - 单击与拖放上传](#file-transfer---single-click--drag-n-drop-upload)
  - [文件传输 - 基于网页的文件管理器](#file-transfer---web-based-file-managers)
  - [游戏](#games)
  - [游戏 - 管理工具与控制面板](#games---administrative-utilities--control-panels)
  - [家谱](#genealogy)
  - [生成式人工智能（GenAI）](#generative-artificial-intelligence-genai)
  - [群件（协同办公）](#groupware)
  - [健康与健身](#health-and-fitness)
  - [人力资源管理（HRM）](#human-resources-management-hrm)
  - [身份管理](#identity-management)
  - [物联网（IoT）](#internet-of-things-iot)
  - [库存管理](#inventory-management)
  - [知识管理工具](#knowledge-management-tools)
  - [学习与课程](#learning-and-courses)
  - [制造业](#manufacturing)
  - [地图与全球定位系统（GPS）](#maps-and-global-positioning-system-gps)
  - [媒体管理](#media-management)
  - [媒体流](#media-streaming)
  - [媒体流 - 音频流](#media-streaming---audio-streaming)
  - [媒体流 - 多媒体流](#media-streaming---multimedia-streaming)
  - [媒体流 - 视频流](#media-streaming---video-streaming)
  - [杂项](#miscellaneous)
  - [财务、预算与管理](#money-budgeting--management)
  - [监控与状态页面](#monitoring--status-pages)
  - [网络工具](#network-utilities)
  - [笔记与编辑器](#note-taking--editors)
  - [办公套件](#office-suites)
  - [密码管理器](#password-managers)
  - [粘贴板](#pastebins)
  - [个人仪表盘](#personal-dashboards)
  - [相册](#photo-galleries)
  - [投票与活动](#polls-and-events)
  - [代理](#proxy)
  - [食谱管理](#recipe-management)
  - [远程访问](#remote-access)
  - [资源规划](#resource-planning)
  - [搜索引擎](#search-engines)
  - [自托管解决方案](#self-hosting-solutions)
  - [软件开发](#software-development)
  - [软件开发 - API 管理](#software-development---api-management)
  - [软件开发 - 持续集成与部署](#software-development---continuous-integration--deployment)
  - [软件开发 - FaaS 与无服务器](#software-development---faas--serverless)
  - [软件开发 - 功能开关](#software-development---feature-toggle)
  - [软件开发 - IDE 与工具](#software-development---ide--tools)
  - [软件开发 - 本地化](#software-development---localization)
  - [软件开发 - 低代码](#software-development---low-code)
  - [软件开发 - 项目管理](#software-development---project-management)
  - [软件开发 - 测试](#software-development---testing)
  - [静态站点生成器](#static-site-generators)
  - [任务管理与待办清单](#task-management--to-do-lists)
  - [工单系统](#ticketing)
  - [时间追踪](#time-tracking)
  - [旅行组织](#travel-organization)
  - [短链接服务](#url-shorteners)
  - [视频监控](#video-surveillance)
  - [VPN](#vpn)
  - [Web 服务器](#web-servers)
  - [Wiki](#wikis)
- [许可证列表](#list-of-licenses)
- [反特性](#anti-features)
- [外部链接](#external-links)
- [贡献指南](#contributing)
- [许可证](#license)

--------------------

## 软件 <a id="software"></a>

### 分析统计 <a id="analytics"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[分析统计](https://en.wikipedia.org/wiki/Analytics)是对数据或统计信息进行系统化的计算分析，用于发现、解读并传达数据中有意义的模式。

_相关：[数据库管理](#database-management)、[个人仪表盘](#personal-dashboards)_

- [ANALOG](https://github.com/orangecoloured/analog) - 一款极简的分析工具。可在 10-30 天的跨度内追踪事件。 `MIT` `Nodejs/Docker`
- [Aptabase](https://aptabase.com/) - 面向移动端和桌面应用、隐私优先的简洁分析工具。([源代码](https://github.com/aptabase/aptabase)) `AGPL-3.0` `Docker`
- [AWStats](http://www.awstats.org/) - 从 Web、流媒体、FTP 或邮件服务器的日志文件中生成统计数据。([演示](https://www.awstats.org/#DEMO)、[源代码](https://github.com/eldy/awstats)) `GPL-3.0` `Perl`
- [Countly Community Edition](https://count.ly) - 实时移动端与 Web 分析、崩溃报告与推送通知平台。([源代码](https://github.com/Countly/countly-server)) `AGPL-3.0` `Nodejs/Docker`
- [d8a.tech](https://d8a.tech) - 一种数据采集服务，可配合你现有的 Google Analytics 配置捕获用户活动，并将其直接发送到你自己的私有数据库。([演示](https://lookerstudio.google.com/u/0/reporting/0e4102b6-c38b-4f55-aa25-c1fe91d1c1e9)、[源代码](https://github.com/d8a-tech/d8a)) `MIT` `Go/Docker`
- [Daily Stars Explorer](https://emanuelef.github.io/daily-stars-explorer) `⚠` - 通过每日 Star 数据洞察来追踪 GitHub 仓库趋势，了解其增长与社区关注度随时间的变化。([演示](https://emanuelef.github.io/daily-stars-explorer)、[源代码](https://github.com/emanuelef/daily-stars-explorer)) `MIT` `Go/Nodejs/Docker`
- [Druid](https://druid.apache.org) - 分布式、面向列的实时分析数据存储。([源代码](https://github.com/apache/druid)) `Apache-2.0` `Java/Docker`
- [EDA](https://github.com/jortilles/EDA) - 用于数据分析与可视化的 Web 应用。 `AGPL-3.0` `Nodejs/Docker`
- [GoAccess](http://goaccess.io/) - 在终端中运行的实时 Web 日志分析器与交互式查看器。([源代码](https://github.com/allinurl/goaccess)) `GPL-2.0` `C`
- [GoatCounter](https://www.goatcounter.com) - 简单易用的网站统计，不追踪个人数据。([源代码](https://github.com/arp242/goatcounter)) `EUPL-1.2` `Go`
- [HitKeep](https://hitkeep.com/) - 隐私优先的 Web 分析，在单个二进制文件中内置 DuckDB，支持目标转化、漏斗、电商追踪与团队管理（Google Analytics、Plausible、Umami 的替代方案）。([源代码](https://github.com/pascalebeier/hitkeep)) `MIT` `Go/Docker`
- [Litlyx](https://litlyx.com) - 一体化分析解决方案。30 秒即可完成设置，在 AI 驱动的仪表盘上展示你的全部数据，完全可自托管并符合 GDPR。([源代码](https://github.com/Litlyx/litlyx)) `Apache-2.0` `Docker`
- [Liwan](https://liwan.dev/) - 隐私优先的 Web 分析。([演示](https://demo.liwan.dev/p/liwan.dev)、[源代码](https://github.com/explodingcamera/liwan)) `Apache-2.0` `Rust/Docker`
- [Matomo](https://matomo.org/) - 保护你自身及客户隐私的 Web 分析（Google Analytics 的替代方案）。([源代码](https://github.com/matomo-org/matomo)) `GPL-3.0` `PHP`
- [Medama Analytics](https://oss.medama.io) - 隐私优先的网站分析。体积小、简单且无需 Cookie。([演示](https://demo.medama.io)、[源代码](https://github.com/medama-io/medama)) `Apache-2.0/MIT` `Docker/Go`
- [Metabase](https://metabase.com/) - 让公司每个人都能轻松提问并从数据中学习。([源代码](https://github.com/metabase/metabase)) `AGPL-3.0` `Java/Docker`
- [Middleware](https://middlewarehq.com/) - 旨在帮助工程负责人使用 DORA 指标衡量和分析团队效能的工具。([源代码](https://github.com/middlewarehq/middleware)) `Apache-2.0` `Docker/Python/Nodejs`
- [Netron](https://netron.app/) - 神经网络与机器学习模型的可视化工具。([源代码](https://github.com/lutzroeder/netron)) `MIT` `Python/Nodejs`
- [Offen](https://www.offen.dev/) - 公平、轻量、开放的 Web 分析工具。让你获得洞察的同时，用户也能完全访问自己的数据。([演示](https://www.offen.dev/try-demo/)、[源代码](https://github.com/offen/offen)) `Apache-2.0` `Go/Docker`
- [Plausible Analytics](https://plausible.io/) - 简单、轻量（< 1 KB）且隐私友好的 Web 分析。([源代码](https://github.com/plausible/analytics/)) `AGPL-3.0` `Elixir`
- [PostHog](https://posthog.com) - 可自托管的产品分析、会话录制、功能开关与 A/B 测试（Mixpanel、Amplitude、Heap、HotJar、Optimizely 的替代方案）。([源代码](https://github.com/posthog/posthog)) `MIT` `Python`
- [Postiz](https://postiz.com) `⚠` - 在一处即可安排发布、追踪内容表现并管理所有社交媒体账号（Buffer、Hootsuite、Sprout Social 的替代方案）。([源代码](https://github.com/gitroomhq/postiz-app)) `AGPL-3.0` `Docker`
- [Prisme Analytics](https://www.prismeanalytics.com) - 基于 Grafana、注重隐私的渐进式分析服务。([源代码](https://github.com/prismelabs/analytics)) `AGPL-3.0/MIT` `Docker`
- [Redash](http://redash.io) - 连接并查询你的数据源，构建仪表盘以可视化数据并与公司同事分享。([源代码](https://github.com/getredash/redash)) `BSD-2-Clause` `Docker`
- [Rybbit](https://rybbit.com/) - 易于配置且更直观的网站与产品分析（Google Analytics 的替代方案）。([演示](https://demo.rybbit.com/1)、[源代码](https://github.com/rybbit-io/rybbit)) `AGPL-3.0` `Docker`
- [Shaper](https://taleshape.com/shaper/docs) - 全部用 SQL 构建数据仪表盘，由 DuckDB 提供支持。([演示](https://demo.taleshape.com/view/pvggvdpiwb9wlyppuqbyx0nt)、[源代码](https://github.com/taleshape-com/shaper)) `MPL-2.0` `Docker/Nodejs/Python/Go`
- [Socioboard](https://github.com/Socioboard-developers/Socioboard-5.0) `⚠` - 支持开箱即用九个社交网络的社交媒体管理、分析与报告平台。 `GPL-3.0` `Nodejs`
- [Statistics for Strava](https://github.com/robiningelbrecht/statistics-for-strava) `⚠` - 根据 Strava 数据生成的统计仪表盘。([演示](https://statistics-for-strava.robiningelbrecht.be/)) `AGPL-3.0` `Docker`
- [Superset](http://superset.apache.org/) - 现代化的数据探索与可视化平台。([源代码](https://github.com/apache/superset)) `Apache-2.0` `Python`
- [Swetrix](https://swetrix.com/) - Web 分析工具，可追踪网站流量、监控网站速度、分析用户会话与页面流、查看用户路径等（Google Analytics 的替代方案）。([演示](https://swetrix.com/projects/STEzHcB1rALV)、[源代码](https://github.com/Swetrix/selfhosting)) `AGPL-3.0` `Docker`
- [Umami](https://umami.is/) - 简单、快速、注重隐私的 Google Analytics 替代方案。([演示](https://cloud.umami.is/share/LGazGOecbDtaIwDr)、[源代码](https://github.com/umami-software/umami)) `MIT` `Nodejs/Docker`


### 归档与数字保存（DP） <a id="archiving-and-digital-preservation-dp"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

数字[归档](https://en.wikipedia.org/wiki/Archival_science)与[保存](https://en.wikipedia.org/wiki/Digital_preservation)软件。

_相关：[备份](#backup)、[内容管理系统（CMS）](#content-management-systems-cms)_

_另见：[awesome-web-archiving](https://github.com/iipc/awesome-web-archiving)_

- [ArchiveBox](https://archivebox.io/) - 根据你的书签、浏览历史、RSS 订阅或其他来源，为网站创建 HTML 与截图存档（Wayback Machine 的替代方案）。([源代码](https://github.com/ArchiveBox/ArchiveBox)) `MIT` `Python/Docker`
- [ArchivesSpace](https://archivesspace.org/) - 档案信息管理应用，用于管理档案、手稿与数字对象并提供 Web 访问。([演示](https://archivesspace.org/application/sandbox)、[源代码](https://github.com/archivesspace/archivesspace)) `ECL-2.0` `Ruby`
- [Bichon](https://github.com/rustmailer/bichon) - 邮件归档服务器，可从 IMAP 账号同步邮件、为全文检索建立索引，并提供 REST API。无需外部数据库，内置支持多账号的 Web 界面。 `AGPL-3.0` `Rust/Docker`
- [bitmagnet](https://bitmagnet.io) - BitTorrent 索引器、DHT 爬虫、内容分类器与种子搜索引擎，带 Web 界面、GraphQL API 及 Servarr 套件集成。([源代码](https://github.com/bitmagnet-io/bitmagnet)) `MIT` `Go/Docker`
- [CKAN](https://ckan.org) - 构建开放数据网站。([源代码](https://github.com/ckan/ckan)) `AGPL-3.0` `Python`
- [Collective Access - Providence](https://collectiveaccess.org/) - 高度可配置的基于 Web 的框架，用于管理、描述和检索数字与实体收藏，支持多种元数据标准、数据类型和媒体格式。([源代码](https://github.com/collectiveaccess/providence)) `GPL-3.0` `PHP`
- [Eonvelope](https://dacid99.gitlab.io/eonvelope) - 邮件归档软件，可将你的邮件保存无限长的时间。([源代码](https://gitlab.com/dacid99/eonvelope)) `AGPL-3.0` `K8S/Docker`
- [Ganymede](https://github.com/Zibbp/ganymede) `⚠` - Twitch VOD 与直播流归档平台。为每个存档包含渲染后的聊天记录。 `GPL-3.0` `Docker`
- [mail-archiver](https://github.com/s1t5/mail-archiver) - 用于归档、搜索和导出多个账号（IMAP、M365 或导入）邮件的 Web 应用。具备文件夹同步、附件支持、邮箱迁移和仪表盘功能。 `GPL-3.0` `Docker`
- [Omeka S](https://omeka.org/s/) - 面向有兴趣将数字文化遗产收藏与其他在线资源关联的机构的下一代 Web 发布平台。([源代码](https://github.com/omeka/omeka-s)) `GPL-3.0` `Nodejs`
- [Open Archiver](https://openarchiver.com/) - 具备全文检索和电子取证检索功能的邮件归档解决方案。([演示](https://github.com/LogicLabs-OU/OpenArchiver?tab=readme-ov-file#-live-demo)、[源代码](https://github.com/LogicLabs-OU/OpenArchiver)) `AGPL-3.0` `Docker`
- [Piler](https://www.mailpiler.org/) - 功能丰富的邮件归档解决方案。([源代码](https://github.com/jsuto/piler/)) `GPL-3.0` `C/Docker/deb`
- [Wallabag](https://www.wallabag.org) - Wallabag（原名 Poche）是一款 Web 应用，可让你保存文章以便日后再读，并提升阅读体验。([源代码](https://github.com/wallabag/wallabag)) `MIT` `PHP`
- [Wayback](https://github.com/wabarc/wayback) - 自托管工具集，可将网页归档到 Internet Archive、archive.today、IPFS 和本地文件系统。 `GPL-3.0` `Go`


### 自动化 <a id="automation"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

旨在减少流程中人工干预的[自动化](https://en.wikipedia.org/wiki/Automation)软件。

_相关：[物联网（IoT）](#internet-of-things-iot)、[软件开发 - 持续集成与部署](#software-development---continuous-integration--deployment)、[媒体管理](#media-management)_

- [Activepieces](https://www.activepieces.com) - 类似 Zapier 或 Tray 的无代码业务自动化工具。例如，你可以为每张新建的 Trello 卡片发送 Slack 通知。([源代码](https://github.com/activepieces/activepieces)) `MIT` `Docker`
- [Apache Airflow](https://airflow.apache.org/) - 以编程方式编写、调度和监控工作流的平台。([源代码](https://github.com/apache/airflow/)) `Apache-2.0` `Python/Docker`
- [Automatisch](https://automatisch.io) - 业务自动化工具，可连接 Twitter、Slack 等不同服务来自动化你的业务流程（Zapier 的替代方案）。([源代码](https://github.com/automatisch/automatisch)) `AGPL-3.0` `Docker`
- [BookBounty](https://github.com/TheWicklowWolf/BookBounty) `⚠` - 从 Library Genesis 获取 Readarr 缺失的书籍。 `MPL-2.0` `Docker`
- [changedetection.io](https://changedetection.io/) - 及时掌握网站内容的变化。([源代码](https://github.com/dgtlmoon/changedetection.io)) `Apache-2.0` `Python/Docker`
- [ChiefOnboarding](https://chiefonboarding.com) - 员工入职平台，可开通用户账号，并创建包含待办事项、资源、文字/邮件/Slack 消息等的入职流程！提供 Web 门户和 Slack 机器人两种形式。([源代码](https://github.com/chiefonboarding/ChiefOnboarding)) `AGPL-3.0` `Docker`
- [Cronicle](https://cronicle.net/) - 简单、分布式的任务调度与执行器，带 Web 界面。([源代码](https://github.com/jhuckaby/Cronicle)) `MIT` `Nodejs`
- [Cronmaster](https://github.com/fccview/cronmaster) - 定时任务管理界面，为你提供人类可读的语法、实时日志和日志历史。 `AGPL-3.0` `Docker`
- [Dagu](https://docs.dagu.cloud/) - 功能强大的 Cron 替代方案，带 Web 界面。可用声明式 YAML 格式将命令之间的依赖关系定义为有向无环图（DAG）。([源代码](https://github.com/dagucloud/dagu)) `GPL-3.0` `Go/Docker`
- [Discount Bandit](https://discount-bandit.cybrarist.com/) `⚠` - 追踪 Amazon、eBay、Walmart 等多个商店中商品的价格与库存状态。([源代码](https://github.com/Cybrarist/Discount-Bandit)) `GPL-3.0` `PHP/Docker`
- [Dittofeed](https://www.dittofeed.com) - 全渠道客户互动与消息自动化平台（Braze、Customer.io、Iterable 的替代方案）。([演示](https://demo.dittofeed.com/dashboard/journeys)、[源代码](https://github.com/dittofeed/dittofeed)) `MIT` `Docker`
- [flowctl](https://flowctl.net) - 自助式工作流执行平台，支持审批、远程执行和调度。([演示](https://demo.flowctl.net)、[源代码](https://github.com/cvhariharan/flowctl)) `Apache-2.0` `Go/Docker`
- [Fredy](https://fredy.orange-coding.net/) `⚠` - 在 ImmoScout24、Immowelt 等平台上搜索德国的新公寓、住宅和套房，并通过 Slack、Telegram 等即时推送结果给你。([演示](https://fredy-demo.orange-coding.net)、[源代码](https://github.com/orangecoding/fredy)) `Apache-2.0` `Nodejs/Docker`
- [gocron](https://github.com/flohoss/gocron) - 任务调度器，允许用户通过简单的 YAML 配置文件指定重复性任务。 `MIT` `Docker`
- [HandBrake Web](https://github.com/TheNickOfTime/handbrake-web) - 通过 Web 界面在无头设备上使用一个或多个 HandBrake 视频转码器实例。 `AGPL-3.0` `Docker`
- [Healthchecks](https://healthchecks.io/) - 监听心跳信号，并在信号延迟时发送告警。([源代码](https://github.com/healthchecks/healthchecks)) `BSD-3-Clause` `Python/Docker`
- [Huginn](https://github.com/huginn/huginn) - 构建可替你监控并采取行动的代理（Agent）。 `MIT` `Ruby`
- [Kestra](https://kestra.io) - 事件驱动、与语言无关的平台，可用代码创建、调度和监控工作流，协调数据管道以及 ETL、ELT 等任务。([源代码](https://github.com/kestra-io/kestra)) `Apache-2.0` `Docker`
- [Kibitzr](https://kibitzr.github.io) - 轻量级个人 Web 助手，拥有强大的集成能力。([源代码](https://github.com/kibitzr/kibitzr)) `MIT` `Python`
- [LazyLibrarian](https://gitlab.com/LazyLibrarian/LazyLibrarian) `⚠` - 关注作者并抓取元数据，满足你所有数字阅读需求。它组合使用 Goodreads、Librarything 以及可选的 GoogleBooks 作为作者信息和书籍信息来源。 `GPL-3.0` `Python`
- [Leon](https://getleon.ai) - 可以住进你服务器的个人助理。([源代码](https://github.com/leon-ai/leon)) `MIT` `Nodejs`
- [Matchering](https://github.com/sergree/matchering) - 自动化音乐母带处理（LANDR、eMastered 与 MajorDecibel 的替代方案）。 `GPL-3.0` `Docker`
- [Mylar3](https://mylar.nerdfirehurricane.com/) - 配合 NZB 和种子使用的自动化漫画书（cbr/cbz）下载程序。([源代码](https://github.com/MylarComics/mylar3)) `GPL-3.0` `Python/Docker`
- [OliveTin](https://www.olivetin.app/) - 用于运行 Linux Shell 命令的 Web 界面。([源代码](https://github.com/OliveTin/OliveTin)) `AGPL-3.0` `Go`
- [pyLoad](https://pyload.net/) - 轻量、可定制且可远程管理的下载器，适用于 rapidshare.com、uploaded.to 等一键网盘站点。([源代码](https://github.com/pyload/pyload)) `AGPL-3.0` `Python`
- [StackStorm](https://stackstorm.com) - StackStorm（又称“运维版 IFTTT”）是事件驱动的自动化工具，用于自动修复、安全响应、故障排查、部署等。包含规则引擎、工作流、160 个集成包（含 6000+ 操作）以及 ChatOps。([源代码](https://github.com/StackStorm/st2)) `Apache-2.0` `Python`
- [µTask](https://github.com/ovh/utask) - 自动化引擎，可对以 YAML 声明的业务流程进行建模与执行。 `BSD-3-Clause` `Go/Docker`


### 备份 <a id="backup"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[备份](https://en.wikipedia.org/wiki/Backup)软件。

**请访问 [awesome-sysadmin/Backups](https://github.com/awesome-foss/awesome-sysadmin#backups)**

_相关：[归档与数字保存（DP）](#archiving-and-digital-preservation-dp)_



### 博客平台 <a id="blogging-platforms"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[博客](https://en.wikipedia.org/wiki/Blog)是由离散的、日记式文字条目（文章）构成的讨论或信息类网站。

_相关：[静态站点生成器](#static-site-generators)、[内容管理系统（CMS）](#content-management-systems-cms)_

_另见：[WeblogMatrix](https://www.weblogmatrix.org/)_

- [Antville](https://antville.org) - 免费开源项目，旨在开发高性能、功能丰富的博客托管软件。([源代码](https://github.com/antville/antville)) `Apache-2.0` `Javascript`
- [Chyrp Lite](https://chyrplite.net) - 超级棒、超轻量的博客引擎。([源代码](https://github.com/xenocrat/chyrp-lite)) `BSD-3-Clause` `PHP`
- [Dotclear](https://git.dotclear.org/dev/dotclear) - 掌控你自己的博客。 `GPL-2.0` `PHP`
- [Ech0](https://ech0.app/) - 专注于个人想法分享的轻量级联邦式发布平台（文档为中文）。([演示](https://memo.vaaat.com/)、[源代码](https://github.com/lin-snow/Ech0)) `AGPL-3.0` `Docker/K8S`
- [FlatPress](https://flatpress.org/) - 轻量、易于搭建的扁平文件博客引擎。([源代码](https://github.com/flatpressblog/flatpress)) `GPL-2.0` `PHP`
- [fx](https://github.com/rikhuijzer/fx) - 微博客工具，内置语法高亮、移动端发布等功能（Twitter、Bluesky 的替代方案）。 `MIT` `Docker`
- [Ghost](https://ghost.org/) - 就是一个博客平台。([源代码](https://github.com/TryGhost/Ghost)) `MIT` `Nodejs`
- [Haven](https://havenweb.org/) - 私有博客系统，支持 Markdown 编辑并内置 RSS 阅读器。([演示](https://havenweb.org/demo.html)、[源代码](https://github.com/havenweb/haven)) `MIT` `Ruby`
- [HTMLy](https://www.htmly.com/) - 无需数据库的 PHP 博客平台。一种扁平文件 CMS，可让你在几秒内创建快速、安全且强大的网站或博客。([演示](http://demo.htmly.com/)、[源代码](https://github.com/danpros/htmly)) `GPL-2.0` `PHP`
- [Known](https://withknown.com/) - 协作式社交发布平台。([源代码](https://github.com/idno/idno)) `Apache-2.0` `PHP`
- [Mataroa](https://mataroa.blog/) - 面向极简主义者的纯粹博客平台。([源代码](https://github.com/mataroablog/mataroa)) `MIT` `Python`
- [PluXml](https://pluxml.org) - 基于 XML 的博客/CMS 平台。([源代码](https://github.com/pluxml/PluXml)) `GPL-3.0` `PHP`
- [Serendipity](https://docs.s9y.org/) - Serendipity（s9y）是使用 Smarty 模板、高度可扩展且可定制的 PHP 博客引擎。([源代码](https://github.com/s9y/serendipity)) `BSD-3-Clause` `PHP`
- [WriteFreely](https://writefreely.org) - 用于创建极简、联邦式博客——或整个社区——的写作软件。([源代码](https://github.com/writefreely/writefreely)) `AGPL-3.0` `Go`


### 预约与日程安排 <a id="booking-and-scheduling"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

活动排期、预订与预约管理软件。

_相关：[投票与活动](#polls-and-events)、[群件（协同办公）](#groupware)_

- [Alf.io](https://alf.io/) - 票务预订系统。([演示](https://demo.alf.io/authentication)、[源代码](https://github.com/alfio-event/alf.io)) `GPL-3.0` `Java`
- [Cal.diy](https://cal.diy/) - 在线预约排期系统。([源代码](https://github.com/calcom/cal.diy)) `MIT` `Nodejs`
- [Easy!Appointments](https://easyappointments.org/) - 让你的客户通过网络与你预约。([演示](https://demo.easyappointments.org/)、[源代码](https://github.com/alextselegidis/easyappointments)) `GPL-3.0` `PHP`
- [Hi.Events](https://hi.events) - 面向会议、演唱会等的活动管理与票务平台。提供可自定义的活动页面和可嵌入的售票组件。([演示](https://demo.hi.events/event/1/dog-conf-2030)、[源代码](https://github.com/HiEventsDev/hi.events)) `AGPL-3.0` `Docker`
- [LibreBooking](https://librebooking.readthedocs.io/) - 资源排期解决方案，为组织提供灵活、移动友好且可扩展的界面来管理资源预订。([演示](https://librebooking-demo.fly.dev/)、[源代码](https://github.com/LibreBooking/librebooking)) `GPL-3.0` `PHP/Docker`
- [QloApps](https://qloapps.com/) - 可定制、直观的基于 Web 的酒店预订系统与预订引擎。([演示](https://demo.qloapps.com/)、[源代码](https://github.com/Qloapps/QloApps)) `OSL-3.0` `PHP/Nodejs`
- [Rallly](https://rallly.co) - 创建投票来对日期和时间进行表决（Doodle 的替代方案）。([演示](https://app.rallly.co)、[源代码](https://github.com/lukevella/rallly)) `AGPL-3.0` `Nodejs/Docker`
- [Seatsurfing](https://seatsurfing.app/) - 基于 Web 的应用，用于预订办公室的座位、工位和会议室。([源代码](https://github.com/seatsurfing/seatsurfing)) `GPL-3.0` `Docker`


### 书签与链接分享 <a id="bookmarks-and-link-sharing"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

允许用户添加、批注、编辑和分享网页文档[书签](https://en.wikipedia.org/wiki/Bookmark_(digital))的软件。

_相关：[个人仪表盘](#personal-dashboards)_

- [Betula](https://joinbetula.org) - 单用户的联邦式书签管理器，支持 Fediverse 与存档功能。([源代码](https://codeberg.org/bouncepaw/betula)) `AGPL-3.0` `Go`
- [Buku](https://github.com/jarun/Buku) - 强大的书签管理器，也是个人的文本小网络。 `GPL-3.0` `Python/deb`
- [Digibunch](https://ladigitale.dev/digibunch/#/) - 创建链接合集，分享给你的学员或同事。([演示](https://ladigitale.dev/digibunch/#/b/5f67b12092b60)、[源代码](https://codeberg.org/ladigitale/digibunch)) `AGPL-3.0` `Nodejs/PHP`
- [Espial](https://github.com/jonschoning/espial) - 基于 Web 的书签服务器，支持多用户账号。 `AGPL-3.0` `Haskell`
- [Faved](https://faved.to/) - 精心打造的书签管理器，融合强大的标签、即时搜索和简洁无干扰的界面。专为大型收藏与高级工作流构建，兼顾效率与易用性。([演示](https://demo.faved.to/)、[源代码](https://github.com/denho/faved)) `MIT` `Docker`
- [Firefox Account Server](https://mozilla-services.readthedocs.io/en/latest/howtos/run-fxa.html) - 托管你自己的 Firefox 账号服务器。([源代码](https://github.com/mozilla/fxa)) `MPL-2.0` `Nodejs/Java`
- [Karakeep](https://karakeep.app/) - 为数据囤积者打造、带一点 AI 的“收藏一切”应用。([演示](https://try.karakeep.app/signin)、[源代码](https://github.com/karakeep-app/karakeep)) `AGPL-3.0` `Docker`
- [LinkAce](https://www.linkace.org/) - 书签存档工具，可自动备份到 Internet Archive，支持链接监控和完整的 REST API。可通过 Docker 或作为简单的 PHP 应用安装。([演示](https://demo.linkace.org/guest/links)、[源代码](https://github.com/Kovah/LinkAce/)) `GPL-3.0` `Docker/PHP`
- [linkding](https://linkding.link/) - 极简的书签管理，界面快速清爽。通过 Docker 简单安装，可在树莓派上运行。([演示](https://demo.linkding.link/login/)、[源代码](https://github.com/sissbruecker/linkding)) `MIT` `Docker`
- [LinkWarden](https://linkwarden.app/) - 用于保存有用链接的书签与存档管理器。([源代码](https://github.com/linkwarden/linkwarden)) `MIT` `Docker/Nodejs`
- [NeonLink](https://github.com/AlexSciFier/neonlink) - 设计独特的书签服务，可通过 Docker 简单安装。 `MIT` `Docker`
- [Readeck](https://readeck.org/en/) - 保存你喜欢并希望永久留存的网页中珍贵的可读内容。可将其视为书签管理器与稍后阅读工具。([源代码](https://codeberg.org/readeck/readeck)、[客户端](https://codeberg.org/readeck/browser-extension)) `AGPL-3.0` `Go/Docker`
- [Servas](https://github.com/beromir/Servas) - 一款自托管书签管理工具，可通过标签、分组以及专门用于稍后访问的列表进行整理，支持带 2FA 的多用户。提供 Firefox 和 Chrome 的配套浏览器扩展。([客户端](https://github.com/beromir/Servas#browser-extensions)) `GPL-3.0` `Docker/Nodejs/PHP`
- [Shaarli](https://github.com/shaarli/Shaarli) - 个人化的极简、超快、无需数据库的书签与链接分享平台。([演示](https://demo.shaarli.org)) `Zlib` `PHP/deb`
- [Shiori](https://github.com/go-shiori/shiori) - 用 Go 构建的简单书签管理器。 `MIT` `Go/Docker`
- [Slash](https://github.com/yourselfhosted/slash) - 开源、可自托管的书签与链接分享平台。 `GPL-3.0` `Docker`
- [SyncMarks](https://codeberg.org/Offerel/SyncMarks-Webapp) - 同步和管理来自 Edge、Firefox 和 Chromium 的浏览器书签。([客户端](https://codeberg.org/Offerel/SyncMarks-Extension)) `AGPL-3.0` `PHP`


### 日历与联系人 <a id="calendar--contacts"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[CalDAV](https://en.wikipedia.org/wiki/CalDAV) 与 [CardDAV](https://en.wikipedia.org/wiki/CardDAV) 协议服务器，以及用于[电子日历](https://en.wikipedia.org/wiki/Calendaring_software)、[通讯录](https://en.wikipedia.org/wiki/Address_book)和[联系人管理](https://en.wikipedia.org/wiki/Contact_manager)的网页客户端/界面。

_相关：[群件（协同办公）](#groupware)_

- [Baïkal](https://sabre.io/baikal/) - 基于 sabre/dav 的轻量级 CalDAV 与 CardDAV 服务器。([源代码](https://github.com/sabre-io/Baikal)) `GPL-3.0` `PHP`
- [DAViCal](https://www.davical.org/) - 日历共享（CalDAV）服务器，使用 PostgreSQL 数据库作为数据存储。([源代码](https://gitlab.com/davical-project/davical)) `GPL-2.0` `PHP/deb`
- [Davis](https://github.com/tchapi/davis) - 基于 Symfony 5 和 Bootstrap 4、简单易用、可 Docker 化且完全可翻译的 sabre/dav 管理界面，很大程度上受 Baïkal 启发。 `MIT` `PHP`
- [Keeper.sh](https://keeper.sh/) - 日历同步工具，通过 iCal/ICS 或 OAuth 在日历来源与目标之间拉取和推送事件，支持匿名的忙碌/空闲事件。([源代码](https://github.com/ridafkih/keeper.sh)) `AGPL-3.0` `Docker`
- [Manage My Damn Life](https://intri.in/manage-my-damn-life/) - Manage my Damn Life（MMDL）是一个自托管前端，用于管理你的 CalDAV 任务与日历。([源代码](https://github.com/intri-in/manage-my-damn-life-nextjs)) `GPL-3.0` `Nodejs/Docker`
- [Radicale](https://radicale.org/) - 简单且管理开销极低的日历与联系人服务器。([源代码](https://github.com/Kozea/Radicale)) `GPL-3.0` `Python/deb`
- [SabreDAV](https://sabre.io/) - 开源的 CardDAV、CalDAV 和 WebDAV 框架及服务器。([源代码](https://github.com/sabre-io/dav)) `MIT` `PHP`
- [Xandikos](https://github.com/jelmer/xandikos) - 开源 CardDAV 与 CalDAV 服务器，管理开销极低，由 Git 仓库作为后端。 `GPL-3.0` `Python/deb`


### 通信 - 自定义通信系统 <a id="communication---custom-communication-systems"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

使用自定义协议在计算机或用户之间提供系统远程访问，并交换文本、音频和/或视频格式文件与消息的[通信软件](https://en.wikipedia.org/wiki/Communication_software)。

- [AnyCable](https://anycable.io/) - 实时服务器，可通过 WebSocket、服务器推送事件（SSE）等实现可靠的双向通信。([演示](https://demo.anycable.io)、[源代码](https://github.com/anycable/anycable)) `MIT` `Go/Docker`
- [Apprise](https://github.com/caronc/apprise) - Apprise 可让你向几乎所有当今流行的通知服务发送通知，例如：Telegram、Discord、Slack、Amazon SNS、Gotify 等。 `MIT` `Python/Docker/deb`
- [Centrifugo](https://centrifugal.dev/) - 与语言无关的实时消息（WebSocket 或 SockJS）服务器。([演示](https://github.com/centrifugal/centrifugo#demo)、[源代码](https://github.com/centrifugal/centrifugo)) `MIT` `Go/Docker/K8S`
- [Chitchatter](https://chitchatter.im/) - 点对点的聊天应用，无服务器、去中心化且阅后即焚。([源代码](https://github.com/jeremyckahn/chitchatter)) `GPL-2.0` `Nodejs`
- [Conduit](https://conduit.rs/) - 基于 Matrix、简单、快速且可靠的聊天服务器。([源代码](https://gitlab.com/famedly/conduit)) `Apache-2.0` `Rust`
- [Continuwuity](https://continuwuity.org/) - 社区驱动的 Matrix 主服务器，是 conduwuit 的延续，专注于用户体验和新功能（Conduit 的分支）。([源代码](https://forgejo.ellis.link/continuwuation/continuwuity)) `Apache-2.0` `Rust/Docker/K8S/deb`
- [Databag](https://github.com/balzack/databag) - 面向 Web、iOS 和 Android 的联邦式端到端加密通讯服务，支持文字、照片、视频以及 WebRTC 音视频通话。 `Apache-2.0` `Docker`
- [Element](https://element.io) - 功能完整的 Matrix 客户端，支持 Web、iOS 和 Android。([源代码](https://github.com/element-hq/element-web)) `Apache-2.0` `Nodejs`
- [Fluxer](https://fluxer.app) - 为朋友、群组和社区打造的即时通讯与 VoIP 平台（Discord 的替代方案）。([演示](https://fluxer.app)、[源代码](https://github.com/fluxerapp/fluxer)、[客户端](https://github.com/awesome-fluxer/awesome-fluxer)) `AGPL-3.0` `Docker`
- [GlobaLeaks](https://www.globaleaks.org/) - 举报软件，让任何人都能轻松搭建和维护安全的举报平台。([演示](https://demo.globaleaks.org)、[源代码](https://github.com/globaleaks/globaleaks-whistleblowing-software)) `AGPL-3.0` `Python/deb/Docker`
- [GNUnet](https://gnunet.org/) - 用于去中心化点对点网络的软件框架。([源代码](https://gnunet.org/git/)) `GPL-3.0` `C`
- [Gotify](https://gotify.net/) - 带 Android 和 CLI 客户端的通知服务器（PushBullet 的替代方案）。([源代码](https://github.com/gotify/server)、[客户端](https://github.com/gotify/android)) `MIT` `Go/Docker`
- [Hyphanet](https://hyphanet.org/) - 匿名共享文件、浏览和发布 _自由站点_（仅可通过 Hyphanet 访问的网站），并在论坛中聊天。([源代码](https://github.com/hyphanet/fred)) `GPL-2.0` `Java`
- [Jami](https://jami.net/) - 通用的通信平台，保护用户隐私与自由。([源代码](https://git.jami.net/savoirfairelinux?sort=latest_activity_desc&filter=jami)) `GPL-3.0` `C++`
- [Live Helper Chat](https://livehelperchat.com/) - 为你的网站提供实时客服聊天。([源代码](https://github.com/LiveHelperChat/livehelperchat)) `Apache-2.0` `PHP`
- [Mumble](https://wiki.mumble.info/wiki/Main_Page) - 低延迟、高质量的语音/文字聊天软件。([源代码](https://github.com/mumble-voip/mumble)、[客户端](https://wiki.mumble.info/wiki/3rd_Party_Applications)) `BSD-3-Clause` `C++/deb`
- [Notifo](https://github.com/notifo-io/notifo) - 多渠道通知服务器，支持邮件、移动推送、Web 推送、短信、消息推送以及一个 JavaScript 插件。 `MIT` `C#`
- [Novu](https://novu.co/) - 面向开发者的通知基础设施。([源代码](https://github.com/novuhq/novu/)) `MIT` `Docker/Nodejs`
- [ntfy](https://ntfy.sh/) - 通过 HTTP PUT/POST 向手机或桌面推送通知，提供 Android 应用、CLI 和 Web 应用，类似 Pushover 和 Gotify。([演示](https://ntfy.sh/app)、[源代码](https://github.com/binwiederhier/ntfy)、[客户端](https://github.com/binwiederhier/ntfy-android)) `Apache-2.0/GPL-2.0` `Go/Docker/K8S`
- [One Time Secret](https://docs.onetimesecret.com) - 通过只能查看一次的自销毁链接安全地分享敏感信息。([演示](https://onetimesecret.com)、[源代码](https://github.com/onetimesecret/onetimesecret)) `MIT` `Docker/Ruby/Nodejs`
- [OpenWA](https://www.open-wa.org) `⚠` - WhatsApp API 网关，将消息功能以 REST 端点形式暴露，带 Web 仪表盘、多账号会话和 Webhook 事件（WhatsApp Business API 服务商的替代方案）。([源代码](https://github.com/rmyndharis/OpenWA)、[客户端](https://github.com/rmyndharis/OpenWA-plugins)) `MIT` `Docker`
- [OTS](https://ots.fyi/) - 一次性密钥分享平台，在浏览器中使用 256 位对称 AES 加密。([源代码](https://github.com/Luzifer/ots)) `Apache-2.0` `Go`
- [PushBits](https://github.com/pushbits/server) - 通过 Matrix 转发推送通知的通知服务器，类似 PushBullet 和 Gotify。 `ISC` `Go`
- [RetroShare](https://retroshare.cc) - 安全且去中心化的通信系统。提供去中心化聊天、论坛、消息收发、文件传输。([源代码](https://github.com/RetroShare/RetroShare)) `GPL-2.0` `C++`
- [Rocket.Chat](https://rocket.chat/) - 把数据保护放在首位的通信平台（Gitter.im 和 Slack 的替代方案）。([源代码](https://github.com/RocketChat/Rocket.Chat)) `MIT` `Nodejs/Docker/K8S`
- [SAMA](https://samacloud.io) - 新一代自托管聊天服务器与客户端。([演示](https://app.samacloud.io/demo)、[源代码](https://github.com/SAMA-Communications/sama-server)、[客户端](https://github.com/SAMA-Communications/sama-client)) `GPL-3.0` `Nodejs/Docker`
- [Screego](https://screego.net) - Screego 是一个简单工具，可通过网页浏览器快速将你的屏幕分享给一人或多人。([演示](https://app.screego.net/)、[源代码](https://github.com/screego/server)) `GPL-3.0` `Docker/Go`
- [Shhh](https://github.com/smallwat3r/shhh) - 让机密远离邮件或聊天记录，使用带密码短语和有效期的安全链接分享它们。 `MIT` `Python`
- [SimpleX Chat](https://github.com/simplex-chat/simplex-chat) - 最私密、最安全的聊天与应用平台——现已支持双棘轮端到端加密。 `AGPL-3.0` `Haskell`
- [Spectrum 2](https://spectrum.im/) - Spectrum 2 是一款开源即时通讯传输工具。即使用户使用不同的即时通讯网络，也能彼此聊天。([源代码](https://github.com/SpectrumIM/spectrum2)) `GPL-3.0` `C++`
- [Stoat](https://stoat.chat/) - Stoat 是一个用现代 Web 技术构建、以用户为先的聊天平台。([源代码](https://github.com/stoatchat/self-hosted)) `AGPL-3.0/MIT` `Rust`
- [Synapse](https://element-hq.github.io/synapse/latest/index.html) - [Matrix](https://matrix.org/) 服务器，Matrix 是去中心化持久通信的开放标准。([源代码](https://github.com/element-hq/synapse)) `Apache-2.0` `Python/deb`
- [Tiledesk](https://tiledesk.com) - 一体化客户互动平台，覆盖从获客到售后，从 WhatsApp 到你的网站。带全渠道人工客服和 AI 驱动的聊天机器人（Intercom、Zendesk、Tawk.to 和 Tidio 的替代方案）。([源代码](https://github.com/Tiledesk/tiledesk)) `MIT` `Docker/K8S`
- [Tinode](https://github.com/tinode) - 即时通讯平台。后端用 Go，客户端包括：Swift iOS、Java Android、JS Web 应用、可脚本化的命令行；支持聊天机器人。([演示](https://sandbox.tinode.co/)、[源代码](https://github.com/tinode/chat)、[客户端](https://github.com/tinode/webapp)) `GPL-3.0` `Go`
- [Tox](https://tox.chat/) - 分布式、安全的通讯工具，具备音视频聊天能力。([源代码](https://github.com/TokTok/c-toxcore)) `GPL-3.0` `C`
- [Tuwunel](https://tuwunel.chat) - 面向 Matrix 的高性能、功能丰富的聊天服务器，是 conduwuit 的继任者（Conduit 的分支）。([演示](https://try.tuwunel.chat/)、[源代码](https://github.com/matrix-construct/tuwunel)) `Apache-2.0` `deb/Docker/Nix/Rust`
- [Typebot](https://typebot.io) - 对话式应用构建器（Typeform 和 Landbot 的替代方案）。([源代码](https://github.com/baptisteArno/typebot.io)) `AGPL-3.0` `Docker`
- [WBO](https://github.com/lovasoa/whitebophir) - Web 白板，可实时协作绘制图表、图画和笔记。([演示](https://wbo.ophir.dev/)) `AGPL-3.0` `Nodejs/Docker`
- [Zulip](https://zulip.org) - Zulip 是一款功能强大、开源的群组聊天应用。([源代码](https://github.com/zulip/zulip)) `Apache-2.0` `Python`


### 通信 - 电子邮件 - 完整解决方案 <a id="communication---email---complete-solutions"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[电子邮件](https://en.wikipedia.org/wiki/Email)服务器的简化部署方案，适合经验不足或缺乏耐心的管理员。

- [AnonAddy](https://anonaddy.com) - 用于创建别名的邮件转发服务。([源代码](https://github.com/anonaddy/anonaddy)) `MIT` `PHP/Docker`
- [b1gMail](https://www.b1gmail.eu) - 可在任何支持 PHP 和 MariaDB 的网站上运行的完整邮件解决方案。它支持 POP3 全收邮箱，若你自建服务器，还可与 Postfix 或 b1gMailServer 集成。([源代码](https://codeberg.org/b1gMail/b1gMail)、[客户端](https://www.b1gmail.eu/en/start/addon-b1gmailserver/)) `GPL-2.0` `PHP`
- [DebOps](https://docs.debops.org/) - 开箱即用的 Debian 数据中心。一组通用 Ansible 角色，可用于管理 Debian 或 Ubuntu 主机。([源代码](https://github.com/debops/debops)) `GPL-3.0` `Ansible/Python`
- [docker-mailserver](https://docker-mailserver.github.io/docker-mailserver/edge/) - 生产就绪、全栈但简单的邮件服务器（SMTP、IMAP、LDAP、反垃圾邮件、反病毒等），在容器中运行。只需配置文件，无需 SQL 数据库。([源代码](https://github.com/docker-mailserver/docker-mailserver)) `MIT` `Docker`
- [Inboxen](https://inboxen.org) - 让你拥有无限个唯一收件箱。([源代码](https://codeberg.org/Inboxen/Inboxen)) `GPL-3.0` `Python`
- [iRedMail](https://www.iredmail.org/) - 基于 Postfix 和 Dovecot 的功能完整的邮件服务器解决方案。([源代码](https://github.com/iredmail/iRedMail)) `GPL-3.0` `Shell`
- [Maddy Mail Server](https://maddy.email/) - 一体化邮件服务器，实现 SMTP（同时支持 MTA 和 MX）与 IMAP。以单个守护进程替代 Postfix、Dovecot、OpenDKIM、OpenSPF、OpenDMARC。([源代码](https://github.com/foxcpp/maddy)) `GPL-3.0` `Go`
- [Mail-in-a-Box](https://mailinabox.email/) - 一条命令即可将任意 Ubuntu 服务器变成功能完整的邮件服务器。([源代码](https://github.com/mail-in-a-box/mailinabox)) `CC0-1.0` `Shell`
- [Mailcow](https://mailcow.email/) - 基于 Dovecot、Postfix 等开源软件的邮件服务器套件，提供现代化的 Web 管理界面。([源代码](https://github.com/mailcow/mailcow-dockerized)) `GPL-3.0` `Docker/PHP`
- [Mailu](https://mailu.io/) - 简单但功能齐全的邮件服务器，以一组 Docker 镜像形式提供。([源代码](https://github.com/Mailu/Mailu)) `MIT` `Docker/Python`
- [Modoboa](https://modoboa.org/en/) - 邮件托管与管理平台，包含现代化、简化的 Web 用户界面。([源代码](https://github.com/modoboa/modoboa)) `ISC` `Python`
- [Mox](https://www.xmox.nl/) - 完整的电子邮件解决方案，支持 IMAP4、SMTP、SPF、DKIM、DMARC、MTA-STS、DANE 和 DNSSEC，基于信誉与内容的垃圾邮件过滤，国际化（IDNA），通过 ACME 和 Let's Encrypt 自动配置 TLS，账号自动配置，以及网页邮件。([源代码](https://github.com/mjl-/mox)) `MIT` `Go`
- [Postal](https://docs.postalserver.io/) - 供网站和 Web 服务器使用的完整、功能齐全的邮件服务器。([源代码](https://github.com/postalserver/postal)) `MIT` `Docker/Ruby`
- [Simple NixOS Mailserver](https://gitlab.com/simple-nixos-mailserver/nixos-mailserver) - 利用 Nix 生态系统的完整邮件服务器解决方案。 `GPL-3.0` `Nix`
- [SimpleLogin](https://simplelogin.io) - 开源邮件别名解决方案，保护你的邮箱地址。附带浏览器扩展和移动应用。([源代码](https://github.com/simple-login/app)) `MIT` `Docker/Python`
- [Stalwart Mail Server](https://stalw.art) - 一体化邮件服务器，支持 JMAP、IMAP4 和 SMTP，并具备广泛的现代特性。([源代码](https://github.com/stalwartlabs/stalwart)) `AGPL-3.0` `Rust/Docker`
- [wildduck](https://wildduck.email/) - 可扩展、无单点故障的 IMAP/POP3 邮件服务器。([源代码](https://github.com/zone-eu/wildduck)) `EUPL-1.2` `Nodejs/Docker`


### 通信 - 电子邮件 - 邮件投递代理 <a id="communication---email---mail-delivery-agents"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[邮件投递代理](https://en.wikipedia.org/wiki/Message_delivery_agent)（MDA）—— [IMAP](https://en.wikipedia.org/wiki/Internet_Message_Access_Protocol)/[POP3](https://en.wikipedia.org/wiki/Post_Office_Protocol) 服务器软件。

- [Cyrus IMAP](https://www.cyrusimap.org/) - 电子邮件（IMAP/POP3）、联系人与日历服务器。([源代码](https://github.com/cyrusimap/cyrus-imapd)) `BSD-3-Clause-Attribution` `C`
- [DavMail](https://davmail.sourceforge.net/) `⚠` - POP/IMAP/SMTP/CalDAV/CardDAV/LDAP 的 Exchange 网关，让用户可将任意邮件/日历客户端用于 Exchange 服务器，即使来自互联网或通过 Outlook Web Access 穿透防火墙。([源代码](https://github.com/mguessan/davmail)) `GPL-2.0` `Java`
- [Dovecot](https://www.dovecot.org/) - 以安全为首要考量编写的 IMAP 与 POP3 服务器。([源代码](https://github.com/dovecot/core)) `MIT/LGPL-2.1` `C/deb`


### 通信 - 电子邮件 - 邮件传输代理 <a id="communication---email---mail-transfer-agents"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[邮件传输代理](https://en.wikipedia.org/wiki/Message_transfer_agent)（MTA）—— [SMTP](https://en.wikipedia.org/wiki/Simple_Mail_Transfer_Protocol) 服务器。

- [chasquid](https://blitiri.com.ar/p/chasquid/) - SMTP（邮件）服务器，注重简洁、安全与易于运维。([源代码](https://blitiri.com.ar/git/r/chasquid/)) `Apache-2.0` `Go`
- [Courier MTA](https://www.courier-mta.org/) - 快速、可扩展的企业级邮件/群件服务器，提供 ESMTP、IMAP、POP3、网页邮件、邮件列表、基本的基于 Web 的日历与排期服务。([源代码](https://www.courier-mta.org/repo.html)) `GPL-3.0` `C/deb`
- [DragonFly](https://github.com/corecode/dma) - 供家庭和办公使用的小型 MTA。可在 Linux 和 FreeBSD 上运行。 `BSD-3-Clause` `C`
- [EmailRelay](https://emailrelay.sourceforge.net/) - 面向 Windows 和 Linux、小巧且易于配置的 SMTP 与 POP3 服务器。([源代码](https://sourceforge.net/p/emailrelay/code/HEAD/tree/)) `GPL-3.0` `C++`
- [Exim](https://www.exim.org/) - 由剑桥大学开发的邮件传输代理（MTA）。([源代码](https://git.exim.org/exim.git)) `GPL-3.0` `C/deb`
- [Haraka](https://haraka.github.io/) - 快速、高度可扩展、事件驱动的 SMTP 服务器。([源代码](https://github.com/haraka/Haraka)) `MIT` `Nodejs`
- [OpenSMTPD](https://opensmtpd.org/) - 来自 OpenBSD 项目的安全 SMTP 服务器实现。([源代码](https://github.com/OpenSMTPD/OpenSMTPD/)) `ISC` `C/deb`
- [Postfix](http://www.postfix.org/) - 快速、易于管理且安全的 Sendmail 替代品。 `IPL-1.0` `C/deb`
- [Sendmail](https://www.proofpoint.com/us/products/email-protection/open-source-email-solution) - 邮件传输代理（MTA）。 `Sendmail` `C/deb`


### 通信 - 电子邮件 - 邮件列表与通讯 <a id="communication---email---mailing-lists-and-newsletters"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[邮件列表](https://en.wikipedia.org/wiki/Mailing_list)服务器与群发软件 —— 一封消息发送给众多收件人。

_相关：[客户关系管理（CRM）](#customer-relationship-management-crm)_

- [HyperKitty](https://wiki.list.org/HyperKitty) - 访问 GNU Mailman v3 的归档。([演示](https://lists.mailman3.org/)、[源代码](https://gitlab.com/mailman/hyperkitty)) `GPL-3.0` `Python`
- [Keila](https://www.keila.io) - 可靠且易用的通讯简报工具（Mailchimp 和 Sendinblue 的替代方案）。([演示](https://app.keila.io)、[源代码](https://github.com/pentacent/keila)) `AGPL-3.0` `Docker`
- [Listmonk](https://listmonk.app/) - 高性能、自托管的通讯简报与邮件列表管理器，带现代化仪表盘。([演示](https://demo.listmonk.app/)、[源代码](https://github.com/knadh/listmonk)) `AGPL-3.0` `Go/Docker`
- [Mailman](https://www.list.org/) - 管理电子邮件讨论与电子通讯简报列表。([源代码](https://gitlab.com/mailman/)) `GPL-3.0` `Python`
- [Mautic](https://www.mautic.org/) - 营销自动化软件（邮件、社交等）。([源代码](https://github.com/mautic/mautic)) `GPL-3.0` `PHP`
- [mlmmj](https://mlmmj.org/) - 让邮件列表管理变得愉快。([源代码](https://codeberg.org/mlmmj/mlmmj)) `MIT` `C`
- [phpList](https://www.phplist.org) - 通讯简报与邮件营销，具备订阅者、退信和插件的高级管理功能。([源代码](https://github.com/phpList/phplist3)) `AGPL-3.0` `PHP`
- [Postorius](https://docs.mailman3.org/projects/postorius/en/latest/) - 用于访问 GNU Mailman 的 Web 用户界面。([源代码](https://gitlab.com/mailman/postorius/)) `GPL-3.0` `Python`
- [Schleuder](https://schleuder.nadir.org/) - 支持 GPG 的邮件列表管理器，具备重发功能。([源代码](https://0xacab.org/schleuder/schleuder/tree/master)) `GPL-3.0` `Ruby`
- [Sympa](https://www.sympa.community/) - 邮件列表管理器。([源代码](https://github.com/sympa-community/sympa)) `GPL-2.0` `Perl`


### 通信 - 电子邮件 - 网页邮件客户端 <a id="communication---email---webmail-clients"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[网页邮件](https://en.wikipedia.org/wiki/Webmail)客户端。

- [Cypht](https://cypht.org) - 为你的邮件账号提供的订阅阅读器。([源代码](https://github.com/cypht-org/cypht)) `LGPL-2.1` `PHP`
- [Roundcube](https://roundcube.net) - 基于浏览器的 IMAP 客户端，拥有类似应用的界面。([源代码](https://github.com/roundcube/roundcubemail)) `GPL-3.0` `PHP/deb`
- [SnappyMail](https://github.com/the-djmaze/snappymail) - 简单、现代、轻量且快速的基于 Web 的邮件客户端（RainLoop 的分支）。 `AGPL-3.0` `PHP`
- [SquirrelMail](https://squirrelmail.org) - 另一款基于浏览器的 IMAP 客户端。([源代码](https://sourceforge.net/p/squirrelmail/code/HEAD/tree/)) `GPL-2.0` `PHP`


### 通信 - IRC <a id="communication---irc"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[IRC](https://en.wikipedia.org/wiki/Internet_Relay_Chat) 通信软件。

- [Ergo](https://ergo.chat/) - 用 Go 编写的现代 IRCv3 服务器，融合了 ircd、服务框架和 bouncer 的功能。([源代码](https://github.com/ergochat/ergo)) `MIT` `Go/Docker`
- [Glowing Bear](https://github.com/glowing-bear/glowing-bear) - WeeChat 的 Web 前端。([演示](https://www.glowing-bear.org)) `GPL-3.0` `Nodejs`
- [InspIRCd](https://www.inspircd.org/) - 用 C++ 编写、面向 Linux、BSD、Windows 和 macOS 的模块化 IRC 服务器。([源代码](https://github.com/inspircd/inspircd)) `GPL-2.0` `C++/Docker`
- [Kiwi IRC](https://kiwiirc.com/) - 响应式 Web IRC 客户端，支持主题定制。([演示](https://kiwiirc.com/nextclient/)、[源代码](https://github.com/kiwiirc/kiwiirc)) `Apache-2.0` `Nodejs`
- [ngircd](https://ngircd.barton.de/) - 面向小型或私有网络的可移植、轻量级 Internet Relay Chat 服务器。([源代码](https://github.com/ngircd/ngircd)) `GPL-2.0` `C/deb`
- [Quassel IRC](https://quassel-irc.org/) - 分布式 IRC 客户端，即一个（或多个）客户端可以连接到中央核心并从中分离。([源代码](https://github.com/quassel/quassel)) `GPL-2.0` `C++`
- [Robust IRC](https://robustirc.net/) - 不会发生网络分裂（netsplit）的 IRC。基于 RobustSession 协议的分布式 IRC 服务器。([源代码](https://github.com/robustirc/robustirc)) `BSD-3-Clause` `Go`
- [The Lounge](https://thelounge.chat/) - 自托管的 Web IRC 客户端。([演示](https://demo.thelounge.chat/)、[源代码](https://github.com/thelounge/thelounge)) `MIT` `Nodejs/Docker`
- [UnrealIRCd](https://www.unrealircd.org/) - 用 C 编写、面向 Linux、BSD、Windows 和 macOS 的模块化、高级且高度可配置的 IRC 服务器。([源代码](https://github.com/unrealircd/unrealircd)) `GPL-2.0` `C`
- [Weechat](https://weechat.org/) - 快速、轻量且可扩展的聊天客户端。([源代码](https://github.com/weechat/weechat)) `GPL-3.0` `C/Docker/deb`
- [ZNC](https://wiki.znc.in/ZNC) - 高级 IRC bouncer。([源代码](https://github.com/znc/znc)) `Apache-2.0` `C++/deb`


### 通信 - SIP <a id="communication---sip"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[SIP](https://en.wikipedia.org/wiki/Session_Initiation_Protocol)/[IPBX](https://en.wikipedia.org/wiki/IP_PBX) 电话通信软件。

- [Asterisk](https://www.asterisk.org/) - 易于使用但功能先进的 IP PBX 系统、VoIP 网关和会议服务器。([源代码](https://github.com/asterisk/asterisk)) `GPL-2.0` `C/deb`
- [Flexisip](https://www.linphone.org/en/flexisip-sip-server/) - 完整、模块化且可扩展的 SIP 服务器，包含推送网关，可在应用未在前台运行时需要推送通知接收信息的移动平台上投递 SIP 来电或短信。([源代码](https://github.com/BelledonneCommunications/flexisip)) `AGPL-3.0` `C/Docker`
- [Freepbx](https://www.freepbx.org) - 基于 Web 的开源 GUI，用于控制和管理 Asterisk。([源代码](https://git.freepbx.org/projects/FREEPBX)) `GPL-2.0` `PHP`
- [FreeSWITCH](https://freeswitch.org/) - 可扩展的开源跨平台电话通信平台。([源代码](https://github.com/signalwire/freeswitch)) `MPL-2.0` `C`
- [FusionPBX](https://www.fusionpbx.com/) - 面向名为 FreeSWITCH 的多平台语音交换机的 Web 界面。([源代码](https://github.com/fusionpbx/fusionpbx)) `MPL-1.1` `PHP`
- [Kamailio](https://www.kamailio.org/w/) - 模块化 SIP 服务器（注册/代理/路由等）。([源代码](https://github.com/kamailio/kamailio)) `GPL-2.0` `C/deb`
- [openSIPS](https://opensips.org/) - 用于语音、视频、即时通讯、在线状态及任何其他 SIP 扩展的 SIP 代理/服务器。([源代码](https://github.com/OpenSIPS/opensips)) `GPL-2.0` `C`
- [Routr](https://routr.io) - 轻量级 SIP 代理、位置服务器和注册服务器，用于构建可靠且可扩展的 SIP 基础设施。([源代码](https://github.com/fonoster/routr)) `MIT` `Docker/K8S`
- [SIP3](https://sip3.io/) - VoIP 故障排查与监控平台。([演示](https://demo.sip3.io)、[源代码](https://github.com/sip3io/)) `Apache-2.0` `Java`
- [SIPCAPTURE Homer](https://www.sipcapture.org/) - VoIP 通话的故障排查与监控。([源代码](https://github.com/sipcapture/homer)) `AGPL-3.0` `Nodejs/Go/Docker`
- [Wazo](https://wazo-platform.org/) - 基于 Asterisk 构建的功能齐全的 IPBX 解决方案，集成 Web 管理界面和 REST 风格 API。([源代码](https://github.com/wazo-platform)) `GPL-3.0` `Python`
- [Yeti-Switch](https://yeti-switch.org/) - 具有集成计费与路由引擎以及 REST API 的转接级 4 类软交换机（SBC）。([演示](https://demo.yeti-switch.org/)、[源代码](https://github.com/yeti-switch)) `GPL-2.0` `C++/Ruby`


### 通信 - 社交网络与论坛 <a id="communication---social-networks-and-forums"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[社交网络](https://en.wikipedia.org/wiki/Social_networking_service)与[论坛](https://en.wikipedia.org/wiki/Internet_forum)软件。

- [Akkoma](https://akkoma.social/) - 联邦式微博客服务器，兼容 Mastodon、GNU social 和 ActivityPub。([源代码](https://akkoma.dev/AkkomaGang/akkoma)) `AGPL-3.0` `Elixir/Docker`
- [Answer](https://answer.apache.org) - 基于知识的社区软件。你可以用它快速搭建用于产品技术支持、客户支持、用户交流等的问答社区。([源代码](https://github.com/apache/answer)) `Apache-2.0` `Docker/Go`
- [Artalk](https://artalk.js.org/) - 用 Golang 构建的评论系统，为你的网站添加评论提供轻量且高度可定制的方案。([源代码](https://github.com/ArtalkJS/Artalk)) `MIT` `Go/Docker`
- [AsmBB](https://board.asm32.info) - 用汇编语言编写、由 SQLite 驱动的高速论坛引擎。([源代码](https://asm32.info/fossil/asmbb/index)) `EUPL-1.2` `Assembly`
- [BuddyPress](https://buddypress.org/about/) - 强大的插件，让你的 WordPress.org 站点超越博客，具备用户资料、动态流、用户群组等社交网络功能。([源代码](https://github.com/buddypress/BuddyPress)) `GPL-2.0` `PHP`
- [Coral](https://coralproject.net/) - 来自 Vox Media 的更好评论体验。([源代码](https://github.com/coralproject/talk)) `Apache-2.0` `Docker/Nodejs`
- [diaspora*](https://diasporafoundation.org/) - 分布式社交网络服务器。([源代码](https://github.com/diaspora/diaspora)) `AGPL-3.0` `Ruby`
- [Discourse](https://www.discourse.org/) - 基于 Ruby 和 JS 的高级论坛/社区解决方案。([演示](https://try.discourse.org/)、[源代码](https://github.com/discourse/discourse)) `GPL-2.0` `Docker`
- [Elgg](https://elgg.org/) - 功能强大的开源社交网络引擎。([源代码](https://github.com/Elgg/Elgg)) `GPL-2.0` `PHP`
- [Enigma 1/2 BBS](https://nuskooler.github.io/enigma-bbs/) - Enigma 1/2 是一款现代、多平台的 BBS 引擎，支持无限“访问者”以及传统 DOS 门游戏。([源代码](https://github.com/NuSkooler/enigma-bbs)) `BSD-2-Clause` `Shell/Docker/Nodejs`
- [Flarum](https://flarum.org) - 令人愉悦的简洁论坛。Flarum 是新一代论坛软件，让在线讨论重新变得有趣。([源代码](https://github.com/flarum/flarum)) `MIT` `PHP`
- [Friendica](https://friendi.ca/) - 社交通信服务器。([源代码](https://github.com/friendica/friendica)) `AGPL-3.0` `PHP`
- [GoToSocial](https://docs.gotosocial.org/en/latest/) - 实现 Mastodon 客户端 API 的 ActivityPub 联邦社交网络服务器。([源代码](https://codeberg.org/superseriousbusiness/gotosocial)) `AGPL-3.0` `Docker/Go`
- [Habitat](https://gethabitat.org/) - 面向本地社区的平台。([源代码](https://github.com/carlnewton/habitat)) `AGPL-3.0` `Docker`
- [Hatsu](https://hatsu.cli.rs/) - 代表你的静态站点与 Fediverse 交互的桥接工具。([源代码](https://github.com/importantimport/hatsu)) `AGPL-3.0` `Docker/Rust`
- [Hubzilla](https://hubzilla.org) - 去中心化的身份、隐私、发布、分享、云存储以及通信/社交平台。([源代码](https://framagit.org/hubzilla/core)) `MIT` `PHP`
- [HumHub](https://www.humhub.org/) - 用于私有社交网络的灵活套件。([源代码](https://github.com/humhub/humhub)) `AGPL-3.0` `PHP`
- [Iceshrimp.NET](https://iceshrimp.net) - 通过 ActivityPub 通信的联邦式微博客服务器。([源代码](https://iceshrimp.dev/iceshrimp/iceshrimp.net)) `EUPL-1.2` `.NET/C#/Docker`
- [Isso](https://isso-comments.de/) - 用 Python 和 JavaScript 编写的轻量级评论服务器。目标是成为 Disqus 的即插即用替代品。([源代码](https://github.com/isso-comments/isso)) `MIT` `Python/Docker`
- [Lemmy](https://join-lemmy.org/) - 面向 fediverse 的链接聚合器（Reddit 的替代方案）。([源代码](https://github.com/LemmyNet/lemmy)) `AGPL-3.0` `Docker/Rust`
- [Loomio](https://www.loomio.org/) - 协作式决策工具，让任何人都能轻松参与影响自身的决策。([源代码](https://github.com/loomio/loomio)) `AGPL-3.0` `Docker`
- [Mastodon](https://joinmastodon.org/) - 联邦式微博客服务器。([源代码](https://github.com/mastodon/mastodon)、[客户端](https://github.com/hyperupcall/awesome-mastodon)) `AGPL-3.0` `Ruby`
- [Misago](https://misago-project.org/) - 功能齐全的现代论坛应用，快速、可扩展且响应式。([源代码](https://github.com/rafalp/Misago)) `GPL-2.0` `Docker`
- [Misskey](https://misskey.io/) - 面向 Fediverse 的去中心化、类应用式微博客服务器/社交网络，像 GNU social 和 Mastodon 一样使用 ActivityPub 协议。([源代码](https://github.com/misskey-dev/misskey)) `AGPL-3.0` `Nodejs/Docker`
- [Movim](https://movim.eu/) - 基于 XMPP 的现代联邦式社交网络，具备功能齐全的群聊、订阅和微博客功能。([源代码](https://github.com/movim/movim)) `AGPL-3.0` `PHP/Docker`
- [MyBB](https://mybb.com/) - 免费、可扩展的论坛软件包。([源代码](https://github.com/mybb/mybb)) `LGPL-3.0` `PHP`
- [NodeBB](https://nodebb.org/) - 为现代 Web 打造的论坛软件。([演示](https://try.nodebb.org/)、[源代码](https://github.com/NodeBB/NodeBB)) `GPL-3.0` `Nodejs/Docker`
- [OSSN](https://www.opensource-socialnetwork.org/) - 社交网络软件，可让你搭建社交网站，帮助成员与有相似职业或个人兴趣的人建立社交关系。([源代码](https://github.com/opensource-socialnetwork/opensource-socialnetwork)) `CAL-1.0` `PHP`
- [phpBB](https://www.phpbb.com/) - 扁平式论坛公告板软件解决方案，可用于与一群人保持联系，也可支撑你的整个网站。([源代码](https://github.com/phpbb/phpbb)) `GPL-2.0` `PHP`
- [PieFed](https://join.piefed.social) - 面向 fediverse 的链接聚合器/Reddit 克隆（Reddit 的替代方案）。([演示](https://piefed.social)、[源代码](https://codeberg.org/rimu/pyfedi)) `AGPL-3.0` `Python/Docker`
- [PixelFed](https://pixelfed.social) - 合乎伦理的照片分享平台，由 ActivityPub 联邦驱动（Instagram 的替代方案）。([源代码](https://github.com/pixelfed/pixelfed)) `AGPL-3.0` `PHP`
- [Pleroma](https://pleroma.social) - 联邦式微博客服务器，兼容 Mastodon、GNU social 和 ActivityPub。([源代码](https://git.pleroma.social/pleroma/pleroma)) `AGPL-3.0` `Elixir`
- [qpixel](https://codidact.com/) - 基于问答的社区知识分享软件。([源代码](https://github.com/codidact/qpixel)) `AGPL-3.0` `Ruby`
- [Redlib](https://github.com/redlib-org/redlib) `⚠` - Reddit 的注重隐私的替代前端，源自 Libreddit。 `AGPL-3.0` `Rust`
- [remark42](https://remark42.com/) - 轻量简单的评论引擎，不窥探用户。可嵌入博客、文章或任何读者可添加评论的地方。([演示](https://remark42.com/demo/)、[源代码](https://github.com/umputun/remark42)) `MIT` `Docker/Go`
- [Scoold](https://scoold.com) - 装在 JAR 里的 Stack Overflow。面向企业的问答平台，支持全文检索、SAML、LDAP 集成和社交登录。([演示](https://live.scoold.com)、[源代码](https://github.com/Erudika/scoold)) `Apache-2.0` `Java/Docker/K8S`
- [Simple Machines Forum](https://www.simplemachines.org/) - 免费的专业级软件包，让你在几分钟内搭建自己的在线社区。([源代码](https://github.com/SimpleMachines/SMF)) `BSD-3-Clause` `PHP`
- [Socialhome](https://socialhome.network) - 联邦式、去中心化的个人资料页构建器与社交网络引擎。([演示](https://socialhome.network/)、[源代码](https://github.com/jaywink/socialhome)) `AGPL-3.0` `Docker/Python`
- [Talkyard](https://www.talkyard.io/) - 创建一个社区，让用户提出想法并获得解答，并进行友好、开放的讨论与聊天（Slack/StackOverflow/Discourse/Reddit/Disqus 的混合体）。([演示](https://www.talkyard.io/forum/latest)、[源代码](https://github.com/debiki/talkyard)) `AGPL-3.0` `Docker/Scala`
- [yarn.social](https://yarn.social) - 自托管、类 Twitter™ 的去中心化微博客平台。无广告、无追踪，你的内容、你的数据。([源代码](https://git.mills.io/yarnsocial/yarn)) `MIT` `Go`


### 通信 - 视频会议 <a id="communication---video-conferencing"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[视频/网络会议](https://en.wikipedia.org/wiki/Web_conferencing)工具与软件。

_相关：[会议管理](#conference-management)_

- [BigBlueButton](https://bigbluebutton.org/) - 支持实时分享音频、视频、幻灯片（带白板控制）、聊天和屏幕。讲师可以通过投票、表情符号和分组讨论室与远程学生互动。([源代码](https://github.com/bigbluebutton/bigbluebutton)) `LGPL-3.0` `Java`
- [Galene](https://galene.org/) - 易于部署且服务器资源需求适中的视频会议服务器。([源代码](https://github.com/jech/galene)) `MIT` `Go`
- [Janus](https://janus.conf.meetecho.com/) - 通用、轻量、极简的 WebRTC 服务器。([演示](https://janus.conf.meetecho.com/demos/)、[源代码](https://github.com/meetecho/janus-gateway)) `GPL-3.0` `C`
- [Jitsi Meet](https://jitsi.org/Projects/JitsiMeet) - 使用 Jitsi Videobridge 提供高质量、可扩展视频会议的 WebRTC 应用。([演示](https://meet.jit.si)、[源代码](https://github.com/jitsi/jitsi-meet)) `Apache-2.0` `Nodejs/Docker/deb`
- [Jitsi Video Bridge](https://jitsi.org/Projects/JitsiVideobridge) - 兼容 WebRTC 的选择性转发单元（SFU），支持多用户视频通信。([源代码](https://github.com/jitsi/jitsi-videobridge)) `Apache-2.0` `Java/deb`
- [MiroTalk C2C](https://c2c.mirotalk.com) - 实时摄像头对摄像头视频通话与屏幕共享，端到端加密，可通过简单的 iframe 嵌入任何网站。([源代码](https://github.com/miroslavpejic85/mirotalkc2c)) `AGPL-3.0` `Nodejs/Docker`
- [MiroTalk P2P](https://p2p.mirotalk.com) - 简单、安全、快速的实时视频会议，最高支持 4K 和 60fps，兼容所有浏览器和平台。([演示](https://p2p.mirotalk.com/newcall)、[源代码](https://github.com/miroslavpejic85/mirotalk)) `AGPL-3.0` `Nodejs/Docker`
- [MiroTalk SFU](https://sfu.mirotalk.com) - 简单、安全、可扩展的实时视频会议，最高支持 4K，兼容所有浏览器和平台。([演示](https://sfu.mirotalk.com/newroom)、[源代码](https://github.com/miroslavpejic85/mirotalksfu)) `AGPL-3.0` `Nodejs/Docker`
- [plugNmeet](https://www.plugnmeet.org/) - 可扩展、高性能的 Web 会议系统。([演示](https://demo.plugnmeet.com/login.html)、[源代码](https://github.com/mynaparrot/plugNmeet-server)) `MIT` `Docker/Go`


### 通信 - XMPP - 服务器 <a id="communication---xmpp---servers"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[可扩展消息与存在协议（XMPP）](https://en.wikipedia.org/wiki/XMPP)服务器。

- [ejabberd](https://www.ejabberd.im/) - XMPP 即时通讯服务器。([源代码](https://github.com/processone/ejabberd)) `GPL-2.0` `Erlang/Docker`
- [MongooseIM](https://www.erlang-solutions.com/products/mongooseim.html) - 注重性能与可扩展性的移动消息平台。([源代码](https://github.com/esl/MongooseIM)) `GPL-2.0` `Erlang/Docker/K8S`
- [Openfire](https://www.igniterealtime.org/projects/openfire/) - 实时协作（RTC）服务器。([源代码](https://github.com/igniterealtime/Openfire)) `Apache-2.0` `Java`
- [Prosody IM](https://prosody.im/) - 功能丰富且易于配置的 XMPP 服务器。([源代码](https://hg.prosody.im/)) `MIT` `Lua`
- [Snikket](https://snikket.org/) - 一体化 Docker 化的简易 XMPP 方案，包含 Web 管理和客户端。([源代码](https://github.com/snikket-im/snikket-server)、[客户端](https://snikket.org/app/)) `Apache-2.0` `Docker`
- [Tigase](https://tigase.net/xmpp-server) - 用 Java 实现的 XMPP 服务器。([源代码](https://github.com/tigase/tigase-server)) `GPL-3.0` `Java`


### 通信 - XMPP - 网页客户端 <a id="communication---xmpp---web-clients"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[可扩展消息与存在协议（XMPP）](https://en.wikipedia.org/wiki/XMPP)网页客户端/界面。

- [Converse.js](https://conversejs.org/) - 在浏览器中使用的 XMPP 聊天客户端。([源代码](https://github.com/conversejs/converse.js)) `MPL-2.0` `Javascript`
- [Libervia](https://repos.goffi.org/libervia-web) - Salut à Toi 的 Web 前端。 `AGPL-3.0` `Python`
- [Salut à Toi](https://www.salut-a-toi.org/) - 多用途、多前端、自由且去中心化的通信工具。([源代码](https://repos.goffi.org/libervia-backend)) `AGPL-3.0` `Python`


### 社区支持农业（CSA） <a id="community-supported-agriculture-csa"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

社区支持农业与食品合作社的管理与行政工具。

_相关：[电子商务](#e-commerce)_

- [ACP Admin](https://acp-admin.ch/) - 社区支持农业（CSA）管理。管理会员、订阅、配送、投放点、会员参与、发票和邮件（文档为法语）。([源代码](https://github.com/csa-admin-org/csa-admin)) `MIT` `Ruby`
- [FoodCoopShop](https://www.foodcoopshop.com/) - 面向食品合作社的用户友好型软件。([源代码](https://github.com/foodcoopshop/foodcoopshop)) `AGPL-3.0` `PHP/Docker`
- [Foodsoft](https://foodcoops.net/) - 管理非营利食品合作社（产品目录、订购、记账、工作排班）。([源代码](https://github.com/foodcoops/foodsoft)) `AGPL-3.0` `Docker/Ruby`
- [Hive-Pal](https://hivepal.app) - 移动优先的养蜂管理应用，用于追踪蜂箱、检查记录、蜂王记录和设备，针对现场使用优化了数据录入流程。([演示](https://hivepal.app)、[源代码](https://github.com/martinhrvn/hive-pal)) `MIT` `Nodejs/Docker`
- [juntagrico](https://juntagrico.org/) - 面向社区菜园和蔬菜合作社的管理平台。([源代码](https://github.com/juntagrico/juntagrico)) `LGPL-3.0` `Python`
- [Open Food Network](https://www.openfoodnetwork.org/) - 面向本地食物的在线市场。它构建了一个由独立在线食品商店组成的网络，将农民和食品中心与个人及本地商家连接起来。([源代码](https://github.com/openfoodfoundation/openfoodnetwork)) `AGPL-3.0` `Ruby`
- [OpenOlitor](https://openolitor.org/) - 面向社区支持农业团体的管理平台。([源代码](https://github.com/OpenOlitor/openolitor-server)) `AGPL-3.0` `Scala`
- [teikei](https://github.com/teikei/teikei) - 一款基于众包数据绘制社区支持农业地图的 Web 应用。([演示](https://ernte-teilen.org/karte/#/)) `AGPL-3.0` `Nodejs`


### 会议管理 <a id="conference-management"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

用于[摘要](https://en.wikipedia.org/wiki/Abstract_management)提交以及学术会议筹备/管理的软件。

_相关：[通信 - 视频会议](#communication---video-conferencing)_

- [indico](https://getindico.io/) - 功能丰富的活动管理系统，由 CERN（万维网诞生之地）打造。([演示](https://sandbox.getindico.io/)、[源代码](https://github.com/indico/indico)) `MIT` `Python`
- [motion.tools (Antragsgrün)](https://motion.tools/) - 管理（政治）大会的动议与修正案。([演示](https://sandbox.motion.tools/createsite)、[源代码](https://github.com/CatoTH/antragsgruen)) `AGPL-3.0` `PHP/Docker`
- [OpenSlides](https://openslides.com/) - 用于管理和投影大会议程、动议与选举的演示与会议系统。([演示](https://demo.openslides.org/login)、[源代码](https://github.com/OpenSlides/OpenSlides)) `MIT` `Docker`
- [osem](https://osem.io/) - 面向自由软件会议的活动管理。([源代码](https://github.com/openSUSE/osem)) `MIT` `Ruby/Docker`
- [pretalx](https://pretalx.org) - 基于 Web 的活动管理，包括运营征稿（Call for Papers）、审阅投稿和安排演讲。支持与各种相关工具的导出与导入。([源代码](https://github.com/pretalx/pretalx)) `Apache-2.0` `Python`


### 内容管理系统（CMS） <a id="content-management-systems-cms"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[内容管理系统](https://en.wikipedia.org/wiki/Content_management_system)提供了一种实用的建站方式，可通过第三方插件、主题和功能来快速添加与定制丰富特性。

_相关：[博客平台](#blogging-platforms)、[静态站点生成器](#static-site-generators)、[相册](#photo-galleries)_

- [Alfresco Community Edition](https://www.alfresco.com/products/community/download) - 开源的企业内容管理软件，可处理任何类型的内容，让用户轻松分享和协作。([源代码](https://github.com/Alfresco/alfresco-community-repo)) `LGPL-3.0` `Java`
- [Apostrophe](https://apostrophecms.com/) - 注重可扩展的上下文内编辑工具的 CMS。([演示](https://demo.apostrophecms.com/)、[源代码](https://github.com/apostrophecms/apostrophe)) `MIT` `Nodejs`
- [Automad](https://automad.org/) - 扁平文件内容管理系统与模板引擎。([演示](https://try.automad.org/)、[源代码](https://github.com/marcantondahmen/automad)) `MIT` `PHP/Docker`
- [Backdrop CMS](https://backdropcms.org/) - 面向中小企业与非营利组织的综合性 CMS。([源代码](https://github.com/backdrop/backdrop)) `GPL-2.0` `PHP`
- [Bludit](https://www.bludit.com/) `⚠` - 几秒内即可搭建站点或博客。Bludit 使用扁平文件（JSON 格式的文本文件）存储文章和页面。([源代码](https://github.com/bludit/bludit)) `MIT` `PHP`
- [Bolt CMS](https://boltcms.io/) - 内容管理工具，力求尽可能简单直观。([源代码](https://github.com/bolt/core)) `MIT` `PHP`
- [CMS Made Simple](https://www.cmsmadesimple.org/) - 更快速、更轻松地管理网站内容，可从小型企业扩展到大型公司。([源代码](http://svn.cmsmadesimple.org/svn/cmsmadesimple/trunk/)) `GPL-2.0` `PHP`
- [Cockpit](https://getcockpit.com) - 用于管理任何结构化内容的简单内容平台。([源代码](https://github.com/Cockpit-HQ/Cockpit)) `MIT` `PHP`
- [Concrete 5 CMS](https://www.concretecms.com) - 开源内容管理系统。([源代码](https://github.com/concretecms/concretecms)) `MIT` `PHP`
- [Contao](https://contao.org/) - 功能强大的 CMS，可让你创建专业网站和可扩展的 Web 应用。([演示](https://demo.contao.org/contao)、[源代码](https://github.com/contao/contao/)) `LGPL-3.0` `PHP`
- [CouchCMS](https://www.couchcms.com/) - 为设计师打造的 CMS。([源代码](https://github.com/CouchCMS/CouchCMS)) `CPAL-1.0` `PHP`
- [Drupal](https://www.drupal.org/) - 高级开源内容管理平台。([源代码](https://git.drupalcode.org/project/drupal)) `GPL-2.0` `PHP`
- [eLabFTW](https://www.elabftw.net) - 面向科研实验室的在线实验记录本。存储实验、使用数据库查找试剂或实验方案、使用可信时间戳为实验合法打时间戳、导出为 PDF 或 zip 归档、与协作者分享……([演示](https://demo.elabftw.net)、[源代码](https://github.com/elabftw/elabftw)) `AGPL-3.0` `PHP`
- [Expressa](https://github.com/thomas4019/expressa) - 内容管理系统，使用 JSON schema 驱动数据库型网站。提供权限管理和自动 REST API。 `MIT` `Nodejs`
- [Joomla!](https://www.joomla.org/) - 高级内容管理系统（CMS）。([源代码](https://github.com/joomla/joomla-cms)) `GPL-2.0` `PHP`
- [KeystoneJS](https://keystonejs.com/) - CMS 与 Web 应用平台。([源代码](https://github.com/keystonejs/keystone)) `MIT` `Nodejs`
- [Localess](https://localess.org/home) `⚠` - 功能强大的翻译管理与内容管理系统。管理网站或应用内容并翻译成多种语言，使用 AI 加速翻译。([源代码](https://github.com/Lessify/localess)) `MIT` `Docker`
- [MODX](https://modx.com/) - 高级内容管理与发布平台。当前版本称为“Revolution”。([源代码](https://github.com/modxcms/revolution)) `GPL-2.0` `PHP`
- [Neos](https://www.neos.io) - Neos 或 TYPO3 Neos（1 版本）是一款现代开源 CMS。([源代码](https://github.com/neos)) `GPL-3.0` `PHP`
- [Noosfero](https://gitlab.com/noosfero/noosfero) - 面向社会与团结经济网络的平台，在同一系统中集成了博客、电子作品集、CMS、RSS、主题讨论、活动日程以及团结经济的集体智慧。 `AGPL-3.0` `Ruby`
- [Omeka](https://omeka.org) - 在你的服务器上使用 Omeka 创建复杂的叙事并分享丰富的收藏，遵循都柏林核心标准，专为学者、博物馆、图书馆、档案馆和爱好者设计。([演示](https://omeka.org/classic/showcase/)、[源代码](https://github.com/omeka/Omeka)) `GPL-3.0` `PHP`
- [Payload CMS](https://payloadcms.com/) - 开发者优先的无头 CMS 与应用框架。([源代码](https://github.com/payloadcms/payload)) `MIT` `Nodejs`
- [Pimcore](http://www.pimcore.com/) - 多渠道体验与互动管理平台。([源代码](https://github.com/pimcore/pimcore)) `GPL-3.0` `PHP/Docker`
- [Plone](https://plone.org/) - 用于创建、编辑和管理数字内容（如网站、内网和定制解决方案）的 CMS 系统。([源代码](https://github.com/plone)) `ZPL-2.0` `Python/Docker`
- [Publify](https://publify.github.io/) - 简单但功能齐全的 Web 发布软件。([源代码](https://github.com/publify/publify)) `MIT` `Ruby`
- [Pushword](https://pushword.piedweb.com) - 基于 Symfony 构建的内容管理系统，页面用 Markdown、主题用 Twig，并可选基于 Git 的扁平文件存储。([源代码](https://github.com/Pushword/Pushword)、[客户端](https://pushword.piedweb.com/extensions)) `MIT` `PHP`
- [REDAXO](https://www.redaxo.org) - 简单、灵活且实用的内容管理系统（文档为德语）。([源代码](https://github.com/redaxo/core)) `MIT` `PHP/Docker`
- [SilverStripe](https://www.silverstripe.org) - 易用的 CMS，底层是强大的 MVC 框架。([演示](https://demo.silverstripe.org/)、[源代码](https://github.com/silverstripe)) `BSD-3-Clause` `PHP`
- [SPIP](https://www.spip.net/fr) - 面向互联网的发布系统，旨在支持协作工作、多语言环境，并让网页作者易于使用。([源代码](https://git.spip.net/)) `GPL-3.0` `PHP`
- [Squidex](https://squidex.io) - 无头 CMS，基于 MongoDB、CQRS 和事件溯源。([演示](https://cloud.squidex.io)、[源代码](https://github.com/Squidex/squidex)) `MIT` `.NET`
- [Strapi](https://strapi.io/) - 无头 CMS，让开发者快速构建内容 API，同时为内容创作者提供友好的编辑界面。([源代码](https://github.com/strapi/strapi)) `MIT` `Nodejs`
- [Superdesk](https://superdesk.org/) `⚠` - 端到端的新闻创作、生产、策划、分发和发布平台。([源代码](https://github.com/superdesk/superdesk)) `AGPL-3.0` `Docker/Python/PHP`
- [Textpattern](https://textpattern.com/) - 灵活、优雅且易于使用的 CMS。([演示](https://textpattern.co/demo)、[源代码](https://github.com/textpattern/textpattern)) `GPL-2.0` `PHP`
- [Typemill](https://typemill.net/) - 对作者友好的扁平文件 CMS，带基于 Vue.js 的可视化 Markdown 编辑器。([源代码](https://github.com/typemill/typemill)) `MIT` `PHP`
- [TYPO3](https://typo3.org/) - 功能强大、先进且拥有庞大社区的 CMS。([源代码](https://github.com/TYPO3/typo3)) `GPL-2.0` `PHP`
- [Umbraco](https://umbraco.com/) - 友好的 CMS。免费开源，拥有出色的社区。([源代码](https://github.com/umbraco/Umbraco-CMS)) `MIT` `.NET`
- [Vvveb CMS](https://www.vvveb.com) - 功能强大且易于使用，可用于搭建网站、博客或电商商店的 CMS。([演示](https://demo.vvveb.com)、[源代码](https://github.com/givanz/Vvveb)) `AGPL-3.0` `PHP/Docker`
- [Wagtail](https://wagtail.io/) - 注重灵活性与用户体验的 Django 内容管理系统。([源代码](https://github.com/wagtail/wagtail)) `BSD-3-Clause` `Python`
- [WinterCMS](https://wintercms.com/) - 基于 Laravel PHP 框架构建的快速、安全的内容管理系统。([源代码](https://github.com/wintercms/winter)) `MIT` `PHP`
- [WonderCMS](https://www.wondercms.com) - WonderCMS 是自 2008 年以来最小的扁平文件 CMS。([演示](https://www.wondercms.com/demo)、[源代码](https://github.com/WonderCMS/wondercms)) `MIT` `PHP`
- [WordPress](https://wordpress.org/) - 世界上使用最广泛的博客与 CMS 引擎。([源代码](https://github.com/WordPress/WordPress)) `GPL-2.0` `PHP`


### 客户关系管理（CRM） <a id="customer-relationship-management-crm"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[客户关系管理（CRM）](https://en.wikipedia.org/wiki/Customer_relationship_management)是组织用来管理、分析并改善与客户互动的战略流程。

_相关：[通信 - 电子邮件 - 邮件列表与通讯](#communication---email---mailing-lists-and-newsletters)、[分析统计](#analytics)、[日历与联系人](#calendar--contacts)_

- [Corteza](https://docs.cortezaproject.org) - CRM，包含统一工作区、企业消息传递以及低代码环境，可快速、安全地交付基于记录的管理解决方案。([演示](https://latest.cortezaproject.org)、[源代码](https://github.com/cortezaproject/corteza)) `Apache-2.0` `Go`
- [Django-CRM](https://DjangoCRM.github.io/info/) - 具备任务管理、邮件营销等功能的分析型 CRM。Django CRM 面向个人、各种规模的企业或自由职业者，便于定制和快速开发。([源代码](https://github.com/DjangoCRM/django-crm)) `AGPL-3.0` `Python`
- [EspoCRM](https://www.espocrm.com/) - 前端设计为单页应用的 CRM，并带 REST API。([演示](https://demo.espocrm.com/)、[源代码](https://github.com/espocrm/espocrm)) `AGPL-3.0` `PHP`
- [Krayin](https://krayincrm.com/) - 面向中小企业和大型企业的 CRM 解决方案，用于完整的客户生命周期管理。([演示](https://demo.krayincrm.com/)、[源代码](https://github.com/krayin/laravel-crm)) `MIT` `PHP`
- [Relaticle](https://relaticle.com) - 带 MCP 服务器、需人工批准变更的 AI 助手、REST API、自定义字段和看板的 CRM。([源代码](https://github.com/relaticle/relaticle)) `AGPL-3.0` `PHP/Docker`
- [SuiteCRM](https://suitecrm.com) - 屡获殊荣的企业级开源 CRM。([源代码](https://github.com/SuiteCRM/SuiteCRM)) `AGPL-3.0` `PHP`
- [Twenty](https://twenty.com) - 现代 CRM，兼具开源的灵活性、先进的功能和时尚的设计。([源代码](https://github.com/twentyhq/twenty)) `AGPL-3.0` `Docker`


### 数据库管理 <a id="database-management"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

用于[数据库](https://en.wikipedia.org/wiki/Database)管理的 Web 界面，包含数据库分析与可视化工具。

_相关：[分析统计](#analytics)、[自动化](#automation)_

_另见：[dbdb.io - Database of Databases](https://dbdb.io/)_

- [Adminer](https://www.adminer.org/) - 单个 PHP 文件实现的数据库管理工具。适用于 MySQL、MariaDB、PostgreSQL、SQLite、MS SQL、Oracle、Elasticsearch、MongoDB 等。([源代码](https://github.com/vrana/adminer)) `Apache-2.0/GPL-2.0` `PHP`
- [Azimutt](https://azimutt.app) - 为真实世界（庞大且杂乱）的数据库打造的可视化数据库探索工具。可探索数据库结构与数据、为其编写文档、扩展它们，甚至获取分析和指导建议。([演示](https://azimutt.app/gallery/gospeak)、[源代码](https://github.com/azimuttapp/azimutt)) `MIT` `Elixir/Nodejs/Docker`
- [Baserow](https://baserow.io/) - 无需技术经验即可创建自己的数据库（Airtable 的替代方案）。([源代码](https://gitlab.com/baserow/baserow)) `MIT` `Docker`
- [Bytebase](https://www.bytebase.com/) - 面向 DevOps 团队的安全数据库架构变更与版本控制工具，支持 MySQL、PostgreSQL、TiDB、ClickHouse 和 Snowflake。([源代码](https://github.com/bytebase/bytebase)) `MIT` `Docker/K8S/Go`
- [Chartbrew](https://chartbrew.com) - 直接连接数据库和 API，并使用数据创建精美的图表。([演示](https://app.chartbrew.com/live-demo)、[源代码](https://github.com/chartbrew/chartbrew)) `MIT` `Nodejs/Docker`
- [ChartDB](https://chartdb.io/) - 数据库图表编辑器，只需一条查询即可可视化并设计你的数据库。([演示](https://app.chartdb.io)、[源代码](https://github.com/chartdb/chartdb)) `AGPL-3.0` `Nodejs/Docker`
- [CloudBeaver](https://dbeaver.com/) - 管理数据库，支持 PostgreSQL、MySQL、SQLite 等。DBeaver 的 Web/托管版本。([源代码](https://github.com/dbeaver/cloudbeaver)) `Apache-2.0` `Docker`
- [d9](https://d9.webcapsule.io) - 通过直观的管理界面将 SQL 数据库转为安全的 API。数据平台与无头 CMS（Directus 的分支）。([源代码](https://github.com/LaWebcapsule/d9)) `GPL-3.0` `Nodejs`
- [Databunker](https://databunker.org/) - 基于网络的、自托管的、符合 GDPR 的、用于个人数据或 PII 的安全数据库。([源代码](https://github.com/securitybunker/databunker)) `MIT` `Docker`
- [datannur](https://datannur.com) - 轻量级数据目录，用于记录和探索结构化数据文件与数据库。([演示](https://dev.datannur.com/)、[源代码](https://github.com/datannur/datannur)) `MIT` `Python`
- [Datasette](https://datasette.io/) - 通过便捷的导入导出和数据库管理来探索和发布数据。([源代码](https://github.com/simonw/datasette)) `Apache-2.0` `Python/Docker`
- [Evidence](https://evidence.dev) - 基于代码的 BI 工具。用 SQL 和 Markdown 编写报告，渲染为网站。([源代码](https://github.com/evidence-dev/evidence)) `MIT` `Nodejs`
- [LibreDB Studio](https://libredb.org) - 基于浏览器的 SQL IDE，支持 PostgreSQL、MySQL、Oracle、SQL Server、MongoDB、Redis、ClickHouse、DuckDB 等，具备 SSO、审计轨迹、ER 图和可选的按自有模型密钥的 AI 辅助（DataGrip、DBeaver、CloudBeaver 的替代方案）。([源代码](https://github.com/libredb/libredb-studio)) `MIT` `Docker/K8S`
- [Limbas](https://www.limbas.com/en/) - 用于创建数据库驱动业务应用的数据库框架。作为图形化数据库前端，它支持高效处理数据存量，并灵活开发舒适的数据库应用。([源代码](https://github.com/limbas/limbas)) `GPL-2.0` `PHP`
- [Mathesar](https://mathesar.org/) - 直观的 UI，面向所有技术水平用户协作管理数据。基于 Postgres 构建——可连接现有数据库或新建一个。([源代码](https://github.com/mathesar-foundation/mathesar)) `GPL-3.0` `Docker/Python`
- [OrcaQ](https://orca-q.com) - 现代数据库客户端与 IDE，用于管理、查询和探索多种数据库类型，内置 AI 助手。([源代码](https://github.com/cin12211/orca-q)) `MIT` `Nodejs/deb/Docker`
- [StackRender](https://stackrender.io/) - 数据库架构设计与 SQL 迁移生成器，支持 PostgreSQL、MySQL、MariaDB、SQLite、SQL Server 和 Oracle。([演示](https://app.stackrender.io/)、[源代码](https://github.com/stackrender/stackrender)) `AGPL-3.0` `Nodejs/Docker`


### DNS <a id="dns"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

具备广告拦截功能的[DNS](https://en.wikipedia.org/wiki/Domain_Name_System)服务器与管理工具，主要面向家庭或小型网络。

_另见：[awesome-sysadmin/DNS - Servers](https://github.com/awesome-foss/awesome-sysadmin#dns---servers)、[awesome-sysadmin/DNS - Control Panels & Domain Management](https://github.com/awesome-foss/awesome-sysadmin#dns---control-panels--domain-management)_

- [AdGuard Home](https://adguard.com/en/adguard-home/overview.html) - 用户友好的广告与追踪器拦截 DNS 服务器。([源代码](https://github.com/AdguardTeam/AdGuardHome)) `GPL-3.0` `Docker`
- [blocky](https://0xerr0r.github.io/blocky/latest/) - 快速、轻量的 DNS 代理，作为本地网络的广告拦截器，功能繁多（Pi-hole 的替代方案）。([源代码](https://github.com/0xERR0R/blocky)) `Apache-2.0` `Go/Docker`
- [Maza ad blocking](https://maza-ad-blocking.andros.dev/) - 本地广告拦截器。类似 Pi-hole，但更本地化并使用你的操作系统。([源代码](https://github.com/tanrax/maza-ad-blocking)) `Apache-2.0` `Shell`
- [Numa](https://numa.rs/) - 带广告拦截功能的 DNS 解析器，支持 DNSSEC 验证的递归解析、DoH/DoT/Oblivious DoH、临时覆盖和本地服务域名，以单个 Rust 二进制文件运行（Pi-hole、AdGuard Home、NextDNS 的替代方案）。([源代码](https://github.com/razvandimescu/numa)) `MIT` `Rust/Docker/Nix`
- [Pi-hole](https://pi-hole.net/) - 互联网广告黑洞，带管理与监控 GUI。([源代码](https://github.com/pi-hole/pi-hole)) `EUPL-1.2` `Shell/PHP/Docker`
- [Technitium DNS Server](https://technitium.com/dns/) - 带广告拦截功能的权威/递归 DNS 服务器。([源代码](https://github.com/TechnitiumSoftware/DnsServer)) `GPL-3.0` `Docker/C#`


### 文档管理 <a id="document-management"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[文档管理系统](https://en.wikipedia.org/wiki/Document_management_system)（DMS）是用于接收、跟踪、管理和存储文档并减少纸张使用的系统。

- [BentoPDF](https://bentopdf.com) `⚠` - 功能强大、隐私优先的客户端 PDF 工具包，可直接在浏览器中操作、编辑、合并和处理 PDF 文件。([演示](https://bentopdf.com)、[源代码](https://github.com/alam00000/bentopdf)) `AGPL-3.0` `Nodejs/Docker`
- [Docspell](https://docspell.org) - 自动打标签的文档整理与归档工具。([源代码](https://github.com/eikek/docspell)) `GPL-3.0` `Scala/Java/Docker`
- [Documenso](https://documenso.com) - 数字文档签署平台（DocuSign 的替代方案）。([源代码](https://github.com/documenso/documenso)) `AGPL-3.0` `Nodejs/Docker`
- [Docuseal](https://www.docuseal.co) - 创建、填写和签署数字文档（DocuSign 的替代方案）。([演示](https://demo.docuseal.tech/)、[源代码](https://github.com/docusealco/docuseal)) `AGPL-3.0` `Docker`
- [EveryDocs](https://github.com/jonashellmann/everydocs-core) - 面向私人使用的简单文档管理系统，具备数字化整理文档的基本功能。 `GPL-3.0` `Docker/Ruby`
- [Gotenberg](https://gotenberg.dev) - 对开发者友好的 API，可对接 Chromium 和 LibreOffice 等强大工具，将多种文档格式（HTML、Markdown、Word、Excel 等）转换为 PDF 文件等。([源代码](https://github.com/gotenberg/gotenberg)) `MIT` `Docker`
- [I, Librarian](https://i-librarian.net) - 整理 PDF 论文和办公文档。为学生以及产业界和学术界的科研团队提供大量额外功能。([演示](https://eu1.i-librarian.net/demo)、[源代码](https://github.com/mkucej/i-librarian-free)) `GPL-3.0` `PHP`
- [Mayan EDMS](https://www.mayan-edms.com) - 面向你文档的电子文档管理系统，具备预览生成、OCR 和自动分类等功能。([源代码](https://gitlab.com/mayan-edms/mayan-edms)) `GPL-2.0` `Docker/K8S`
- [OpenSign](https://www.opensignlabs.com) `⚠` - 文档签署软件（DocuSign 的替代方案）。([源代码](https://github.com/opensignlabs/opensign)) `AGPL-3.0` `Nodejs/Docker`
- [Paperless-ngx](https://docs.paperless-ngx.com/) - 用改进后的界面扫描、索引和归档你所有的纸质文档（Paperless 的分支）。([演示](https://demo.paperless-ngx.com/)、[源代码](https://github.com/paperless-ngx/paperless-ngx)) `GPL-3.0` `Python/Docker`
- [Papermerge](https://papermerge.com) - 专注于扫描文档的文档管理系统（电子档案）。具备类似 Dropbox/Google Drive 的文件浏览方式。支持 OCR、全文检索、文本叠加/选取。([源代码](https://github.com/papermerge/papermerge-core)) `Apache-2.0` `Docker/K8S`
- [Papra](https://papra.app) - 极简的文档存储、管理与归档平台，设计简洁易用，人人可用。([演示](https://demo.papra.app/)、[源代码](https://github.com/papra-hq/papra/)) `AGPL-3.0` `Docker`
- [PdfDing](https://www.pdfding.com) - PDF 管理器、查看器和编辑器，在多设备上提供无缝体验。设计极简、快速，且易于通过 Docker 部署。([演示](https://demo.pdfding.com)、[源代码](https://codeberg.org/mrmn/PdfDing)) `AGPL-3.0` `Docker/K8S`
- [SeedDMS](https://www.seeddms.org) - 文档管理系统，具备工作流、访问权限、全文检索等功能。([演示](https://www.seeddms.org/about/)、[源代码](https://sourceforge.net/p/seeddms/code/ci/master/tree/)) `GPL-2.0` `PHP`
- [Signature PDF](https://github.com/24eme/signaturepdf) - 签署和处理 PDF，支持协作、整理、压缩和元数据编辑。([演示](https://pdf.24eme.fr/)) `AGPL-3.0` `PHP/deb/Docker`
- [SimpleDMS](https://simpledms.eu) - 面向小型企业、易用且由元数据驱动的文档管理系统（DMS），几乎能自行整理文档。([源代码](https://github.com/simpledms/simpledms)、[客户端](https://simpledms.eu/en/product/integrations)) `AGPL-3.0` `Docker`
- [SnapOtter](https://snapotter.com) - 200 多个 Web 工具套件，用于转换和编辑图像、视频、音频和 PDF，包括基于图层的图像编辑器、OCR、转录、背景移除和批处理流水线（SmallPDF、iLovePDF、CloudConvert 的替代方案）。([演示](https://demo.snapotter.com)、[源代码](https://github.com/snapotter-hq/SnapOtter)) `AGPL-3.0` `Docker`
- [Stirling-PDF](https://github.com/Stirling-Tools/Stirling-PDF) - 本地托管的 Web 应用，可对 PDF 文件执行多种操作，如合并、拆分、文件转换和 OCR。 `Apache-2.0` `Docker/Java`


### 文档管理 - 电子书 <a id="document-management---e-books"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[电子书](https://en.wikipedia.org/wiki/Ebook)库管理软件。

- [Atsumeru](https://atsumeru.xyz) - 漫画/连环画/轻小说媒体服务器，提供 Windows、Linux、macOS 和 Android 客户端。([源代码](https://github.com/Atsumeru-xyz/Atsumeru)、[客户端](https://atsumeru.xyz/guides/#how-does-it-work)) `MIT` `Java/Docker`
- [Bindery](https://github.com/jarynclouatre/bindery) - 监控文件夹的电子书与漫画转换器。通过 kepubify 将 EPUB 转为 Kobo KEPUB，通过 Kindle Comic Converter 处理 CBZ/CBR/PDF，具备按设备配置、ComicInfo.xml 命名、章节合并成卷以及 Web 界面。 `MIT` `Docker`
- [BookLogr](https://github.com/Mozzo1000/booklogr) - 轻松管理你的个人图书库。([演示](https://demo.booklogr.app/)) `Apache-2.0` `Docker`
- [Calibre Web Automated](https://github.com/crocodilestick/Calibre-Web-Automated) - 一体化解决方案，将 Calibre-Web 现代轻量的 Web 界面与 Calibre 强大而多才的功能集相结合（Calibre Web 的分支）。 `GPL-3.0` `Docker`
- [Calibre Web](https://github.com/janeczku/calibre-web) - 使用现有 Calibre 数据库浏览、阅读和下载电子书。 `GPL-3.0` `Python`
- [Calibre](https://calibre-ebook.com/) - 电子书库管理器，可查看、转换和编目绝大多数主流电子书格式的电子书，并为远程客户端提供内置 Web 服务器。([演示](https://calibre-ebook.com/demo)、[源代码](https://github.com/kovidgoyal/calibre)) `GPL-3.0` `Python/deb`
- [Inkheart](https://gitlab.com/Nystik/inkheart) - 轻量级 PDF 书库与阅读器。 `Apache-2.0` `Docker`
- [Kapowarr](https://casvt.github.io/Kapowarr/) - 构建和管理漫画书库。可按你的喜好下载、重命名、移动和转换该卷的期刊。([源代码](https://github.com/Casvt/Kapowarr)) `GPL-3.0` `Docker/Python`
- [Kavita](https://www.kavitareader.com/) - 跨平台的电子书/漫画/连环画/PDF 服务器与 Web 阅读器，具备用户管理、评分与评论以及元数据支持。([演示](https://www.kavitareader.com/#demo)、[源代码](https://github.com/Kareadita/Kavita)) `GPL-3.0` `.NET/Docker`
- [kiwix-serve](https://github.com/kiwix/kiwix-tools) - 用于从 ZIM 文件提供 wiki 服务的 HTTP 守护进程。 `GPL-3.0` `C++`
- [Komga](https://komga.org) - 面向漫画/日式漫画/欧漫的媒体服务器，支持 API 和 OPDS，提供用于浏览书库的现代 Web 界面以及 Web 阅读器。([源代码](https://github.com/gotson/komga)) `MIT` `Java/Docker`
- [MyMangaDB](https://github.com/FabianRolfMatthiasNoll/MyMangaDB) `⚠` - 漫画收藏管理器，具备自动元数据、MyAnimeList 导入和详细的收藏统计。 `GPL-3.0` `Docker`
- [Stump](https://www.stumpapp.dev) - 快速、免费开源的漫画、日式漫画与数字图书服务器，支持 OPDS。([源代码](https://github.com/stumpapp/stump)) `MIT` `Rust`


### 文档管理 - 机构知识库与数字图书馆软件 <a id="document-management---institutional-repository-and-digital-library-software"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[机构知识库](https://en.wikipedia.org/wiki/Institutional_repository)与[数字图书馆](https://en.wikipedia.org/wiki/Digital_library)管理软件。

- [DSpace](http://www.dspace.org/) - 交钥匙式知识库应用，提供对数字资源的持久访问。([源代码](https://github.com/DSpace/DSpace)) `BSD-3-Clause` `Java`
- [EPrints](https://www.eprints.org/) - 数字文档管理系统，具备灵活的元数据与工作流模型，主要面向学术机构。([演示](http://tryme.demo.eprints-hosting.org/)、[源代码](https://github.com/eprints/eprints3.4)) `GPL-3.0` `Perl`
- [Fedora Commons Repository](https://wiki.lyrasis.org/display/FF/Fedora+Repository+Home) - 健壮且模块化的知识库系统，用于管理和传播数字内容，特别适合数字图书馆和档案馆的访问与保存。([源代码](https://github.com/fcrepo/fcrepo)) `Apache-2.0` `Java`
- [InvenioRDM](https://inveniordm.docs.cern.ch/) - 高度可扩展的交钥匙式研究数据管理平台，用户体验出色。([演示](https://inveniordm.web.cern.ch/)、[源代码](https://github.com/inveniosoftware/invenio-app-rdm)、[客户端](https://inveniosoftware.org/products/rdm/)) `MIT` `Python`
- [Islandora](https://www.islandora.ca/) - Drupal 模块，用于浏览和管理基于 Fedora 的数字知识库。([演示](https://sandbox.islandora.ca/)、[源代码](https://github.com/Islandora/islandora)) `GPL-3.0` `PHP`
- [Samvera Hyrax](https://samvera.org/) - Samvera 框架的前端，后者本身是一个用于浏览和管理基于 Fedora 的数字知识库的 Ruby on Rails 应用。([源代码](https://github.com/samvera/hyrax)) `Apache-2.0` `Ruby`


### 文档管理 - 集成图书馆系统（ILS） <a id="document-management---integrated-library-systems-ils"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[集成图书馆系统](https://en.wikipedia.org/wiki/Integrated_library_system)是面向图书馆的企业资源规划系统，用于跟踪馆藏物品、订单、账单支付以及借阅者信息。

_相关：[内容管理系统（CMS）](#content-management-systems-cms)、[归档与数字保存（DP）](#archiving-and-digital-preservation-dp)_

- [Evergreen](https://evergreen-ils.org) - 高度可扩展的图书馆软件，帮助图书馆读者查找馆藏资料，并帮助图书馆管理、编目和流通这些资料。([源代码](https://github.com/evergreen-library-system/Evergreen)) `GPL-2.0` `PLpgSQL`
- [Koha](https://koha-community.org/) - 企业级 ILS，具备采购、流通、编目、标签打印、无网络时的离线流通等模块，以及更多功能。([演示](https://koha-community.org/demo/)、[源代码](https://github.com/Koha-Community/Koha)) `GPL-3.0` `Perl`
- [RERO ILS](https://rero21.ch/) - 可作为一种服务运行、带联盟功能的大型 ILS，主要面向图书馆网络。包含大多数标准模块（流通、采购、编目……）以及基于 Web 的公众与专业人员界面。([演示](https://ils.test.rero.ch/)、[源代码](https://github.com/rero/rero-ils)) `AGPL-3.0` `Python/Docker`


### 电子商务 <a id="e-commerce"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[电子商务](https://en.wikipedia.org/wiki/E-commerce)软件。

_相关：[社区支持农业（CSA）](#community-supported-agriculture-csa)_

- [Aimeos](https://aimeos.org/) - 电商框架，可基于 Laravel 构建定制的在线商店、市场以及可扩展到数十亿商品的复杂 B2B 应用。([演示](https://demo.aimeos.org/)、[源代码](https://github.com/aimeos/aimeos)) `LGPL-3.0/MIT` `PHP`
- [Bagisto](https://bagisto.com/en/) - 领先的 Laravel 开源电商框架，具备多库存来源、税务、本地化、代发货等众多令人兴奋的功能。([演示](https://demo.bagisto.com/)、[源代码](https://github.com/bagisto/bagisto)) `MIT` `PHP`
- [CoreShop](https://www.coreshop.org) - Pimcore 的电商插件。([源代码](https://github.com/coreshop/CoreShop)) `GPL-3.0` `PHP`
- [Drupal Commerce](https://drupalcommerce.org) - Drupal CMS 的热门电商模块，支持数十个支付、配送和购物相关模块。([源代码](https://git.drupalcode.org/project/commerce)) `GPL-2.0` `PHP`
- [EverShop](https://evershop.io/) `⚠` - 具备核心电商功能的电商平台。模块化架构且完全可定制。([演示](https://demo.evershop.io/)、[源代码](https://github.com/evershopcommerce/evershop)) `GPL-3.0` `Docker/Nodejs`
- [Magento Open Source](https://business.adobe.com/products/magento/magento-commerce.html) - 领先的开放式全渠道创新提供商。([源代码](https://github.com/magento/magento2)) `OSL-3.0` `PHP`
- [MedusaJs](https://medusajs.com/) - 无头电商引擎，让开发者能创建出色的数字商业体验。([演示](https://next.medusajs.com/)、[源代码](https://github.com/medusajs/medusa)) `MIT` `Nodejs`
- [myCart](https://github.com/shurco/mycart) `⚠` - 单文件购物车（支持银行卡或加密货币支付）。 `MIT` `Go/Docker`
- [Open Source POS](https://github.com/opensourcepos/opensourcepos) - 开源销售点（Open Source Point of Sale）是一个基于 Web 的销售点系统。 `MIT` `PHP`
- [OpenCart](https://www.opencart.com) - 购物车解决方案。([源代码](https://github.com/opencart/opencart)) `GPL-3.0` `PHP`
- [PrestaShop](https://www.prestashop.com/) - 完全可扩展的电商解决方案。([演示](https://demo.prestashop.com/)、[源代码](https://github.com/PrestaShop/PrestaShop)) `OSL-3.0` `PHP`
- [Pretix](https://pretix.eu/) - 面向活动的售票平台。([源代码](https://github.com/pretix/pretix)) `AGPL-3.0` `Python/Docker`
- [s-cart](https://s-cart.org/) - 面向个人和企业的电商网站，基于 Laravel 框架构建。([演示](https://demo.s-cart.org/)、[源代码](https://github.com/gp247net/s-cart)) `MIT` `PHP`
- [Saleor](https://saleor.io) - 原生 GraphQL、仅 API 的平台，用于构建可扩展的组合式电商店面。([演示](https://demo.saleor.io/)、[源代码](https://github.com/saleor/saleor)) `BSD-3-Clause` `Docker/Python`
- [Shopware Community Edition](https://www.shopware.com/en/community/community-edition/) - 德国制造的基于 PHP 的开源电商软件。([演示](https://www.shopware.com/en/test-demo/)、[源代码](https://github.com/shopware/shopware)) `MIT` `PHP`
- [Solidus](https://solidus.io/) - 让你完全掌控自己店铺的电商平台。([源代码](https://github.com/solidusio/solidus)) `BSD-3-Clause` `Ruby/Docker`
- [Spree Commerce](https://spreecommerce.org) - Spree 是面向 Ruby on Rails 的完整、模块化且 API 驱动的开源电商解决方案。([演示](https://demo.spreecommerce.org/)、[源代码](https://github.com/spree/spree)) `BSD-3-Clause` `Ruby`
- [Sylius](https://sylius.com) - 由 Symfony2 驱动的开源全栈电商平台。([演示](https://sylius.com/try/)、[源代码](https://github.com/Sylius/Sylius)) `MIT` `PHP`
- [Thelia](https://thelia.net/) - Thelia 是一款开源且灵活的电商解决方案。([演示](https://demo.thelia.net/)、[源代码](https://github.com/thelia/thelia)) `LGPL-3.0` `PHP`
- [Vendure](https://www.vendure.io) - 无头电商框架。([演示](https://demo.vendure.io)、[源代码](https://github.com/vendurehq/vendure)) `MIT` `Nodejs`
- [WooCommerce](https://woocommerce.com/) - 基于 WordPress 的电商解决方案。([源代码](https://github.com/woocommerce/woocommerce)) `GPL-3.0` `PHP`


### 联合身份与认证 <a id="federated-identity--authentication"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[联合身份](https://en.wikipedia.org/wiki/Federated_identity)与[认证](https://en.wikipedia.org/wiki/Electronic_authentication)软件。

**请访问 [awesome-sysadmin/Identity Management](https://github.com/awesome-foss/awesome-sysadmin#identity-management)**



### RSS 阅读器 <a id="feed-readers"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[新闻聚合器](https://en.wikipedia.org/wiki/News_aggregator)（又称订阅聚合器、订阅阅读器、新闻阅读器、[RSS](https://en.wikipedia.org/wiki/RSS) 阅读器）是一种将新闻/博客/视频博客/播客等网页内容汇聚到一处以便浏览的应用。

- [Bubo Reader](https://github.com/georgemandis/bubo-rss) - 极端极简的 RSS 阅读器。([演示](https://bubo-rss-demo.netlify.app/)) `MIT` `Nodejs`
- [CommaFeed](https://www.commafeed.com/) - 受 Google Reader 启发的自托管 RSS 阅读器。([演示](https://www.commafeed.com/#/app/category/all)、[源代码](https://github.com/Athou/commafeed)) `Apache-2.0` `Java/Docker`
- [Feeds Fun](https://feeds.fun/) - 带标签、评分和 AI 的新闻阅读器。([源代码](https://github.com/Tiendil/feeds.fun)) `BSD-3-Clause` `Python`
- [FreshRSS](https://freshrss.org/) - 可自托管的 RSS 订阅聚合器。([演示](https://demo.freshrss.org/i/)、[源代码](https://github.com/FreshRSS/FreshRSS)) `AGPL-3.0` `PHP/Docker`
- [Fusion](https://github.com/0x2E/fusion) - 轻量级 RSS 聚合器与阅读器。 `MIT` `Go/Docker`
- [Goeland](https://github.com/slurdge/goeland) - 将任意 RSS/Atom 订阅转换为精美的邮件摘要。 `MIT` `Go/Docker`
- [JARR](https://1pxsolidblack.pl/jarr-en.html) - JARR（Just Another RSS Reader）是一个基于 Web 的新闻聚合器与阅读器（Newspipe 的分支）。([演示](https://www.jarr.info/)、[源代码](https://github.com/jaesivsm/JARR)) `AGPL-3.0` `Docker/Python`
- [Kriss Feed](https://github.com/tontof/kriss_feed) - 简单且智能（或愚蠢）的订阅阅读器。 `CC0-1.0` `PHP`
- [Leed](https://github.com/LeedRSS/Leed) - Leed（意为 Light Feed）是一款自由且极简的 RSS 聚合器。 `AGPL-3.0` `PHP`
- [Miniflux](https://miniflux.app/) - 极简的新闻阅读器。([源代码](https://github.com/miniflux/v2)) `Apache-2.0` `Go/deb/Docker`
- [NewsBlur](https://www.newsblur.com/) - 个人新闻阅读器，让人们聚在一起讨论世界。老乐器发出的新声音。([源代码](https://github.com/samuelclay/NewsBlur)) `MIT` `Python`
- [Newspipe](https://git.sr.ht/~cedric/newspipe) - Web 新闻阅读器。([演示](https://www.newspipe.org/signup)) `AGPL-3.0` `Python`
- [reader](https://github.com/lemon24/reader) - 订阅阅读器 Web 应用及库（可用于构建你自己的阅读器），仅依赖标准库和纯 Python 依赖。 `BSD-3-Clause` `Python`
- [Readflow](https://readflow.app) - 轻量级新闻阅读器，具备现代界面与功能：全文检索、自动分类、归档、离线支持、通知。([源代码](https://github.com/ncarlier/readflow)) `AGPL-3.0` `Go/Docker`
- [RSS-Bridge](https://github.com/RSS-Bridge/rss-bridge) - 为没有 RSS 订阅的网站生成 RSS/ATOM 订阅。 `Unlicense` `PHP/Docker`
- [RSS Monster](https://github.com/pietheinstrengholt/rssmonster) - 易于使用的基于 Web 的 RSS 聚合器与阅读器，兼容 Fever API（Google Reader 的替代方案）。 `MIT` `PHP`
- [RSS2EMail](https://github.com/rss2email/rss2email) - 抓取 RSS/Atom 订阅并将新内容推送到任意邮件接收方，支持 OPML。 `GPL-2.0` `Python/deb`
- [RSSHub](https://docs.rsshub.app) - 易于使用且可扩展的 RSS 订阅聚合器，几乎能从任何来源生成 RSS 订阅，从社交媒体到大学院系应有尽有。([演示](https://rsshub.app)、[源代码](https://github.com/DIYgod/RSSHub)) `MIT` `Nodejs/Docker`
- [Selfoss](https://selfoss.aditu.de/) - 新型多用途 RSS 阅读器、实时流、聚合（mashup）、聚合类 Web 应用。([源代码](https://github.com/fossar/selfoss)) `GPL-3.0` `PHP`
- [Stringer](https://github.com/stringer-rss/stringer) - 仍在开发中的自托管、反社交 RSS 阅读器。 `MIT` `Ruby`
- [Tiny Tiny RSS](https://tt-rss.org) - 基于 Web 的新闻订阅（RSS/Atom）阅读器与聚合器。([源代码](https://github.com/tt-rss/tt-rss)) `GPL-3.0` `Docker/PHP`
- [TinyFeed](https://feed.lovergne.dev/) - 通过简单的 CLI 从一组订阅生成静态 HTML 页面。([演示](https://feed.lovergne.dev/demo)、[源代码](https://github.com/TheBigRoomXXL/tinyfeed)) `MIT` `Go/Docker`
- [Upvote RSS](https://www.upvote-rss.com/) `⚠` - 从 Reddit、Hacker News、Lemmy、Mbin 等生成丰富的 RSS 订阅。([演示](https://www.upvote-rss.com/)、[源代码](https://github.com/johnwarne/upvote-rss)) `MIT` `Docker/PHP`
- [Yarr](https://github.com/nkanaev/yarr) - Yarr（yet another rss reader）是一个基于 Web 的订阅聚合器，既可作为桌面应用，也可作为个人自托管服务器使用。 `MIT` `Go`


### 文件传输与同步 <a id="file-transfer--synchronization"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[文件传输](https://en.wikipedia.org/wiki/File_transfer)、[共享](https://en.wikipedia.org/wiki/File_sharing)与[同步软件](https://en.wikipedia.org/wiki/File_synchronization)。

_相关：[群件（协同办公）](#groupware)_

- [bewCloud](https://bewcloud.com) - 文件分享 + 同步、笔记和照片（Nextcloud 与 ownCloud RSS 阅读器的替代方案）。([源代码](https://github.com/bewcloud/bewcloud)、[客户端](https://github.com/bewcloud)) `AGPL-3.0` `Docker`
- [Cloudreve](https://cloudreve.org/) - 文件管理与分享系统，支持多种存储提供商。([演示](https://demo.cloudreve.org)、[源代码](https://github.com/cloudreve/cloudreve)) `GPL-3.0` `Docker/Go`
- [Git Annex](https://git-annex.branchable.com/) - 在计算机、服务器、外部驱动器之间进行文件同步。([源代码](https://git.joeyh.name/index.cgi/git-annex.git/)) `GPL-3.0` `Haskell`
- [Kinto](https://kinto.readthedocs.org) - 极简的 JSON 存储服务，具备同步与分享能力。([源代码](https://github.com/Kinto/kinto)) `Apache-2.0` `Python`
- [Nextcloud](https://nextcloud.com/) - 从任意设备按你的方式访问和分享文件、日历、联系人、邮件[等](https://apps.nextcloud.com/)。([演示](https://try.nextcloud.com/)、[源代码](https://github.com/nextcloud/server)) `AGPL-3.0` `PHP/deb`
- [OpenCloud](https://docs.opencloud.eu/) - 文件分享与协作平台。([源代码](https://github.com/opencloud-eu/opencloud)) `Apache-2.0` `Docker/Go/Nodejs`
- [OpenSSH SFTP server](https://www.openssh.com/) - 安全文件传输程序。([源代码](https://cvsweb.openbsd.org/src/usr.bin/ssh?sort=File)) `BSD-2-Clause` `C/deb`
- [ownCloud](https://owncloud.org/) - 用于保存、同步、查看、编辑和分享文件、日历、通讯录等的一体化解决方案。([源代码](https://github.com/owncloud/core)、[客户端](https://github.com/owncloud/core/wiki/Apps)) `AGPL-3.0` `PHP/Docker/deb`
- [Peergos](https://peergos.org) - 安全私密的在线空间，可存储、分享和查看你的照片、视频、音乐与文档。还包含日历、新闻订阅、任务清单、聊天和邮件客户端。([源代码](https://github.com/Peergos/Peergos)) `AGPL-3.0` `Java`
- [Puter](https://puter.com/) - 基于 Web 的操作系统，旨在功能丰富、极其快速且高度可扩展。([演示](https://puter.com/)、[源代码](https://github.com/heyputer/puter)) `AGPL-3.0` `Nodejs/Docker`
- [Pydio](https://pydio.com/) - 将任意 Web 服务器变成强大的文件管理系统，以及主流云存储服务商的替代方案。([演示](https://pydio.com/en/demo)、[源代码](https://github.com/pydio/cells)) `AGPL-3.0` `Go`
- [Samba](https://www.samba.org/) - Samba 是面向 Linux 和 Unix 的标准 Windows 互操作程序套件。为所有使用 SMB/CIFS 协议的客户端提供安全、稳定且快速的文件与打印服务。([源代码](https://git.samba.org/samba.git/)) `GPL-3.0` `C`
- [Seafile](https://www.seafile.com/en/home/) - 主要面向团队和组织的文件托管与分享解决方案。([源代码](https://github.com/haiwen/seafile)) `GPL-2.0/GPL-3.0/AGPL-3.0/Apache-2.0` `C`
- [Sync-in](https://sync-in.com) - 文件存储、同步、分享与协作，支持实时编辑、权限管理和桌面/CLI 客户端。([演示](https://sync-in.com/docs/demo)、[源代码](https://github.com/Sync-in/server)、[客户端](https://github.com/Sync-in/desktop)) `AGPL-3.0` `Nodejs/Docker`
- [Syncthing](https://syncthing.net/) - Syncthing 是一款开源的点对点文件同步工具。([源代码](https://github.com/syncthing/syncthing)) `MPL-2.0` `Go/Docker/deb`
- [Unison](https://www.cis.upenn.edu/~bcpierce/unison/) - Unison 是面向 OSX、Unix 和 Windows 的文件同步工具。([源代码](https://github.com/bcpierce00/unison)) `GPL-3.0` `deb/OCaml`


### 文件传输 - 分布式文件系统 <a id="file-transfer---distributed-filesystems"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

网络分布式文件系统。

**请访问 [awesome-sysadmin/Distributed Filesystems](https://github.com/awesome-foss/awesome-sysadmin#distributed-filesystems)**



### 文件传输 - 对象存储与文件服务器 <a id="file-transfer---object-storage--file-servers"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[对象存储](https://en.wikipedia.org/wiki/Object_storage)是一种将数据作为对象管理的数据存储方式，区别于按文件层级管理数据的文件系统和按扇区/磁道中的块管理数据的块存储。

- [GarageHQ](https://garagehq.deuxfleurs.fr/) - 地理分布式的 S3 兼容存储服务，可满足多种需求。([源代码](https://git.deuxfleurs.fr/Deuxfleurs/garage)) `AGPL-3.0` `Docker/Rust`
- [Harbor](https://goharbor.io/) - 云原生镜像仓库，可存储、签名和扫描内容。([源代码](https://github.com/goharbor/harbor)) `Apache-2.0` `Docker/K8S`
- [SeaweedFS](https://github.com/seaweedfs/seaweedfs) - SeaweedFS 是一款开源分布式文件系统，支持 WebDAV、S3 API、FUSE 挂载、HDFS 等，针对大量小文件进行了优化，且易于扩容。 `Apache-2.0` `Go`
- [Zenko CloudServer](https://www.zenko.io/cloudserver) - 前端实现 Amazon S3 协议，后端具备面向多云（含 Azure 和 Google）的存储能力。([源代码](https://github.com/scality/cloudserver)) `Apache-2.0` `Docker/Nodejs`
- [ZOT OCI Registry](https://zotregistry.dev) - 生产就绪、厂商中立的 OCI 原生容器镜像仓库。([演示](https://zothub.io)、[源代码](https://github.com/project-zot/zot)) `Apache-2.0` `Go/Docker`


### 文件传输 - 点对点文件共享 <a id="file-transfer---peer-to-peer-filesharing"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[点对点文件共享](https://en.wikipedia.org/wiki/Peer-to-peer_file_sharing)是利用[点对点](https://en.wikipedia.org/wiki/Peer-to-peer)（P2P）网络技术对数字媒体进行分发与[共享](https://en.wikipedia.org/wiki/File_sharing)。

- [bittorrent-tracker](https://webtorrent.io/) - 简单、健壮的 BitTorrent tracker（客户端与服务器）实现。([源代码](https://github.com/webtorrent/bittorrent-tracker)) `MIT` `Nodejs`
- [Deluge](https://deluge-torrent.org/) - 轻量、跨平台的 BitTorrent 客户端。([源代码](https://git.deluge-torrent.org/deluge/tree/?h=develop)) `GPL-3.0` `Python/deb`
- [PrivyDrop](https://www.privydrop.app) - 简单易用的、基于 WebRTC 的断点续传点对点文本、图片和文件传输工具。([源代码](https://github.com/david-bai00/PrivyDrop)) `MIT` `Docker/Nodejs`
- [qBittorrent](https://www.qbittorrent.org/) - 免费、跨平台的 BitTorrent 客户端，具备功能丰富的 Web 界面以便远程访问。([源代码](https://github.com/qbittorrent/qBittorrent)) `GPL-2.0` `C++`
- [slskd](https://github.com/slskd/slskd) `⚠` - 面向 Soulseek 文件共享网络的现代客户端-服务器应用。 `AGPL-3.0` `Docker/C#`
- [Transmission](https://transmissionbt.com/) - 快速、简单、免费的 BitTorrent 客户端。([源代码](https://github.com/transmission/transmission)) `GPL-3.0` `C++/deb`
- [Webtor](https://github.com/webtor-io/self-hosted) - 基于 Web 的种子客户端，支持即时音视频流。([演示](https://webtor.io)) `MIT` `Docker`


### 文件传输 - 单击与拖放上传 <a id="file-transfer---single-click--drag-n-drop-upload"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

用于分享一次性/短期/临时文件的简化文件服务器，提供单击或[拖放](https://en.wikipedia.org/wiki/Drag_and_drop)上传功能。

- [015](https://send.fudaoyuan.icu) - 临时文件分享平台。专注于提供一次性的临时文件与文本上传、处理和分享服务。([源代码](https://github.com/keven1024/015)) `AGPL-3.0` `Docker`
- [Chibisafe](https://chibisafe.app) - 文件上传服务，力求易于使用和搭建。它接受文件、照片、文档以及你能想象的一切，并返回一个可分享给他人的链接。([源代码](https://github.com/chibisafe/chibisafe)) `MIT` `Docker/Nodejs`
- [Digirecord](https://ladigitale.dev/digirecord/) - 录制和分享音频文件（文档为法语）。([源代码](https://codeberg.org/ladigitale/digirecord)) `AGPL-3.0` `Nodejs/PHP`
- [elixire](https://gitlab.com/elixire/elixire) - 简单却先进的截图上传与链接缩短服务。([客户端](https://gitlab.com/elixire/elixiremanager)) `AGPL-3.0` `Python`
- [Files Sharing](https://github.com/axeloz/filesharing) - 基于唯一且临时链接的文件分享应用。 `GPL-3.0` `PHP/Docker`
- [Flare](https://github.com/FlintSH/Flare) - 一款不臃肿、现代且高度可配置文件/截图保管服务器，支持 ShareX、Flameshot 和 Spectacle。提供 OCR 搜索等功能。 `MIT` `Docker/Nodejs`
- [Gokapi](https://github.com/Forceu/gokapi) - 轻量级文件分享服务器，文件在达到设定的下载次数或天数后过期。类似已停运的 Firefox Send，区别在于仅管理员才允许上传文件。 `GPL-3.0` `Go/Docker`
- [goploader](https://depado.github.io/goploader/) - 易于使用的文件分享，带服务端加密，兼容 curl/httpie/wget。([源代码](https://github.com/Depado/goploader)) `MIT` `Go`
- [GoSƐ](https://codeberg.org/stv0g/gose) - 现代化的文件上传器，注重可扩展性与简洁性。它仅依赖 S3 存储后端，因此可水平扩展，无需额外的数据库或缓存。 `Apache-2.0` `Go/Docker`
- [Jirafeau](https://gitlab.com/jirafeau/Jirafeau) - 一键文件分享项目。选择你的文件、上传、分享链接。就这么简单。 `AGPL-3.0` `PHP/Docker`
- [OnionShare](https://github.com/onionshare/onionshare) - 安全、匿名地分享任意大小的文件。 `GPL-3.0` `Python/deb`
- [PicoShare](https://github.com/mtlynch/picoshare) - 极简、易于托管的图片及其他文件分享服务。([客户端](https://github.com/mtlynch/picoshare#third-party-clients)) `AGPL-3.0` `Go/Docker`
- [Picsur](https://github.com/CaramelFur/Picsur) - 简单的图片托管平台，让你轻松托管、编辑和分享图片。 `AGPL-3.0` `Docker`
- [PictShare](https://www.pictshare.net/) - 多语言图片托管服务，带简单的缩放与上传 API。([源代码](https://github.com/HaschekSolutions/pictshare)) `Apache-2.0` `PHP/Docker`
- [Pingvin Share X](https://github.com/smp46/pingvin-share-x) - 文件分享平台，支持登录、反向分享、分享过期、S3 存储桶、高级认证、ClamAV 安全扫描等（Pingvin Share 的分支）。 `BSD-2-Clause` `Docker/Nodejs`
- [Plik](https://github.com/root-gg/plik) - 可扩展且友好的临时文件上传系统。([演示](https://plik.root.gg/)) `MIT` `Go/Docker`
- [ProjectSend](https://www.projectsend.org/) - 上传文件并将其分配给由你创建的特定客户，并向这些客户授予文件访问权限。([源代码](https://github.com/projectsend/projectsend)) `GPL-2.0` `PHP`
- [PsiTransfer](https://github.com/psi-4ward/psitransfer) - 简单的文件分享方案，具备健壮的上传/下载断点续传和密码保护。 `BSD-2-Clause` `Nodejs`
- [QuickShare](https://ihexxa.github.io/quickshare.site/) - 在不同设备之间快速简单地进行文件分享。([源代码](https://github.com/ihexxa/quickshare)) `LGPL-3.0` `Docker/Go`
- [Safebucket](https://docs.safebucket.io/) - 带可插拔基础设施的文件分享平台，上传和下载直接在客户端与 S3 兼容存储之间进行。([源代码](https://github.com/safebucket/safebucket)) `Apache-2.0` `Go/Docker`
- [sE2EEnd](https://github.com/sE2EEnd/sE2EEnd) - 端到端加密的文件分享，支持密码保护、下载次数限制和自动过期，并集成 Keycloak 进行认证。 `AGPL-3.0` `Docker`
- [Sharry](https://github.com/eikek/sharry) - 在互联网上轻松地在已认证和匿名用户之间（双向）分享文件，支持断点续传的上传和下载。 `GPL-3.0` `Scala/Java/deb/Docker`
- [Shifter](https://github.com/TobySuch/Shifter) - 一款由 Django 驱动的简单自托管文件分享 Web 应用。 `MIT` `Docker`
- [Slink](https://docs.slinkapp.io/) - 图片分享平台，旨在让用户完全掌控自己的媒体分享体验。([源代码](https://github.com/andrii-kryvoviaz/slink)) `AGPL-3.0` `Docker`
- [snowshare](https://github.com/TuroYT/snowshare) - 文件与链接分享平台，支持 URL 缩短、代码片段分享和文件上传，具备可自定义的过期时间、隐私设置和二维码。([演示](https://s.romain-pinsolle.fr)) `CC0-1.0` `Nodejs/Docker`
- [transfer.sh](https://github.com/dutchcoders/transfer.sh) - 从命令行轻松分享文件。 `MIT` `Go`
- [Uguu](https://github.com/nokonoko/uguu) - 存储文件并在 X 时间后删除。 `MIT` `PHP`
- [XBackBone](https://xbackbone.app/) - 简单、快速且轻量的文件管理器，集成 ShareX 等即时分享工具。([源代码](https://github.com/SergiX44/XBackBone)) `AGPL-3.0` `PHP/Docker`
- [Zipline](https://github.com/diced/zipline) - 轻量、快速且可靠的文件分享服务器，常与 ShareX 配合使用，提供基于 React 的 Web 界面和快速 API。 `MIT` `Docker/Nodejs`


### 文件传输 - 基于网页的文件管理器 <a id="file-transfer---web-based-file-managers"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

基于网页的[文件管理器](https://en.wikipedia.org/wiki/File_manager)。

_相关：[群件（协同办公）](#groupware)_

- [Apaxy](https://oupala.github.io/apaxy/) - 用于增强浏览 Web 目录体验的主题，使用 Apache 的 mod_autoindex 模块和一些 CSS 来覆盖目录列表的默认样式。([源代码](https://github.com/oupala/apaxy)) `GPL-3.0` `Javascript`
- [ClyoCloud](https://clyo.cloud/) - 为隐私、效率和美观而构建的个人自托管云存储与媒体管理应用。([源代码](https://code.weexnes.dev/ClyoCloud)) `AGPL-3.0` `Nodejs`
- [copyparty](https://github.com/9001/copyparty) - 便携式文件服务器，具备加速的断点续传上传、去重、WebDAV、FTP、zeroconf、媒体索引、视频缩略图、音频转码和只写文件夹，单文件且无强制依赖。([演示](https://a.ocv.me/pub/demo/)) `MIT` `Python`
- [Directory Lister](https://www.directorylister.com/) - 基于 PHP 的简单目录列表器，可列出目录及其所有子目录，并让你在其中的导航。([源代码](https://github.com/DirectoryLister/DirectoryLister)) `MIT` `PHP/Docker`
- [FileGator](https://filegator.io/) - FileGator 是一款功能强大的多用户文件管理器，拥有单页前端。([演示](https://demo.filegator.io)、[源代码](https://github.com/filegator/filegator)) `MIT` `PHP/Docker`
- [FileRise](https://github.com/error311/FileRise) - Web 文件管理器，支持上传、打标签、分享链接、画廊/表格视图和浏览器内编辑器。([演示](https://github.com/error311/FileRise?tab=readme-ov-file#live-demo)) `MIT` `Docker/PHP`
- [Filestash](https://www.filestash.app/) - Web 文件管理器，可管理位于任何位置的数据：FTP、SFTP、WebDAV、Git、S3、Minio、Dropbox 或 Google Drive。([演示](https://demo.filestash.app/)、[源代码](https://github.com/mickael-kerjean/filestash)) `AGPL-3.0` `Docker`
- [IFM](https://github.com/misterunknown/ifm) - 单脚本文件管理器。 `MIT` `PHP`
- [mikochi](https://github.com/zer0tonin/Mikochi) - 浏览远程文件夹，上传文件，删除、重命名、下载文件并将其流式传输到 VLC/mpv。 `MIT` `Go/Docker/K8S`
- [miniserve](https://github.com/svenstaro/miniserve) - 通过 HTTP 提供文件和目录服务的 CLI 工具。 `MIT` `Rust`
- [ResourceSpace](https://www.resourcespace.com) - 简单、快速且免费的数字资产管理方式。([演示](https://www.resourcespace.com/trial)、[源代码](https://www.resourcespace.com/svn)) `BSD-4-Clause` `PHP`
- [slcl](https://codeberg.org/xavidcr/slcl) - 简单轻量的 Web 云存储。 `AGPL-3.0` `C`
- [Surfer](https://git.cloudron.io/cloudron/surfer) - 带 Web 界面管理文件的简单静态文件服务器。 `MIT` `Nodejs`
- [TagSpaces](https://www.tagspaces.org/) - TagSpaces 是一款离线、跨平台的文件管理器与整理工具，也可作为笔记应用使用。该应用的 WebDAV 版本可安装在 Nextcloud 或 ownCloud 等 WebDAV 服务器之上。([演示](https://demo.tagspaces.com)、[源代码](https://github.com/tagspaces/tagspaces)) `AGPL-3.0` `Nodejs`
- [Tiny File Manager](https://tinyfilemanager.github.io) - 基于 PHP 的 Web 文件管理器，单文件的简单、快速且小巧的文件管理器。([演示](https://tinyfilemanager.github.io/demo/)、[源代码](https://github.com/prasathmani/tinyfilemanager)) `GPL-3.0` `PHP`


### 游戏 <a id="games"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

多人游戏服务器与[浏览器游戏](https://en.wikipedia.org/wiki/Browser_game)。

_相关：[游戏 - 管理工具与控制面板](#games---administrative-utilities--control-panels)_

- [0 A.D.](https://play0ad.com/) - 跨平台、以古代战争为背景的即时战略游戏。([源代码](https://gitea.wildfiregames.com/0ad/0ad)) `MIT/GPL-2.0/Zlib` `C++/C/deb`
- [A Dark Room](https://github.com/doublespeakgames/adarkroom) - 面向浏览器的极简文字冒险游戏。([演示](https://adarkroom.doublespeakgames.com/)) `MPL-2.0` `Javascript`
- [DDraceNetwork](https://ddnet.org/) - DDRace 的协作平台跳跃版本，是 Teeworlds 的一个模组，具有独特的合作玩法。([源代码](https://github.com/ddnet/ddnet)) `Zlib` `C++`
- [Digibuzzer](https://digibuzzer.app/) - 围绕已连接的抢答器创建虚拟游戏房间（文档为法语）。([演示](https://digibuzzer.app/)、[源代码](https://codeberg.org/ladigitale/digibuzzer)) `AGPL-3.0` `Nodejs`
- [Hypersomnia](https://github.com/TeamHypersomnia/Hypersomnia) - 竞技性俯视角射击游戏，融合了 Counter-Strike 与 Hotline Miami。可在 Linux、Windows、macOS 和 Web 上运行。([演示](https://hypersomnia.io)) `AGPL-3.0` `C++/Docker`
- [Lila](https://lichess.org/) - 驱动 lichess.org 的无广告国际象棋服务器，带官方 iOS 和 Android 客户端应用。([源代码](https://github.com/lichess-org/lila)) `AGPL-3.0` `Scala`
- [Luanti](https://www.luanti.org/) - 体素游戏引擎（原名 Minetest）。玩我们众多游戏中的一款，按你的喜好模改游戏，制作你自己的游戏，或在多人服务器上游玩。([源代码](https://github.com/luanti-org/luanti)) `LGPL-2.1/MIT/Zlib` `C++/Lua/deb`
- [Mindustry](https://mindustrygame.github.io/) - 类似 Factorio 的塔防游戏。建立生产链以收集更多资源，并建造复杂的设施。([源代码](https://github.com/Anuken/Mindustry)) `GPL-3.0` `Java`
- [MTA:SA](https://multitheftauto.com/) `⚠` - 为 Rockstar North 的《侠盗猎车手》系列游戏添加网络联机功能，而该功能原本并不具备。([源代码](https://github.com/multitheftauto/mtasa-blue)) `GPL-3.0` `C++`
- [OpenTTD](https://www.openttd.org/) - 运输大亨模拟游戏。([源代码](https://github.com/OpenTTD/OpenTTD)、[客户端](https://bananas.openttd.org/)) `GPL-2.0` `C++/Docker`
- [piqueserver](https://github.com/piqueserver/piqueserver) - openspades 的服务器，后者是一款在可破坏体素世界中的第一人称射击游戏。([客户端](https://github.com/yvt/openspades)) `GPL-3.0` `Python/C++`
- [Posio](https://github.com/abrenaut/posio) - 地理多人游戏。 `MIT` `Python`
- [Razzia](https://github.com/Ralex91/Razzia) - 问答游戏平台，为较小型自托管活动设计（Kahoot! 的替代方案）。 `MIT` `Nodejs/Docker`
- [Red Eclipse 2](https://www.redeclipse.net/) - 类似 Unreal Tournament 的竞技场第一人称射击游戏。([源代码](https://github.com/redeclipse/base)) `Zlib/MIT/CC-BY-SA-4.0` `C/C++/deb`
- [Scribble.rs](https://github.com/scribble-rs/scribble.rs) - 一款基于 Web 的猜词画画游戏。([演示](https://scribblers.fly.dev)) `BSD-3-Clause` `Go/Docker`
- [Suroi](https://suroi.io/) - 受 surviv.io 启发的 2D 大逃杀游戏。([演示](https://suroi.io/)、[源代码](https://github.com/HasangerGames/suroi)) `GPL-3.0` `Nodejs`
- [The Battle for Wesnoth](https://github.com/wesnoth/wesnoth) - 《韦诺之战》是一款开源、回合制战术策略游戏，以高度奇幻为主题，同时具备单人和在线/同屏多人对战。 `GPL-2.0` `C++/deb`
- [Veloren](https://veloren.net/) - 多人 RPG。灵感来自 Cube World、塞尔达传说、矮人要塞和 Minecraft。([源代码](https://gitlab.com/veloren/veloren)) `GPL-3.0` `Rust`
- [Zero-K](https://zero-k.info/) - 基于 Springrts 引擎的开源游戏。Zero-K 是一款传统即时战略游戏，强调玩家通过地形改造、物理效果和大量独特单位所展现的创造力——同时在平衡性上支持竞技对战。([源代码](https://github.com/ZeroK-RTS/Zero-K)) `GPL-2.0` `Lua`


### 游戏 - 管理工具与控制面板 <a id="games---administrative-utilities--control-panels"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

用于管理游戏服务器与游戏库的实用工具。

_相关：[游戏](#games)_

- [auto-mcs](https://www.auto-mcs.com) - 跨平台的 Minecraft 服务器管理器。([源代码](https://github.com/macarooni-man/auto-mcs)) `AGPL-3.0` `Python`
- [Calagopus](https://calagopus.com) - 现代游戏服务器管理面板。以业界领先的性能部署、监控和管理 Minecraft、Hytale 及其他游戏服务器。([源代码](https://github.com/calagopus/panel)) `MIT` `Rust/Docker/deb`
- [Crafty Controller](https://craftycontrol.com/) - Minecraft 启动器与管理器，让用户可通过友好的界面启动和管理 Minecraft 服务器。([源代码](https://gitlab.com/crafty-controller/crafty-4)) `GPL-3.0` `Docker/Python`
- [Drop](https://droposs.org) - 游戏分发平台，旨在高效地分发和分享无 DRM 的游戏（Steam、GameVault 的替代方案）。([源代码](https://github.com/Drop-OSS/drop)、[客户端](https://github.com/Drop-OSS/drop-app)) `AGPL-3.0` `Docker`
- [EasyWI](https://easy-wi.com) - Easy-Wi 是一个 Web 界面，可让你管理游戏服务器等服务守护进程。此外它还提供一个 CMS，包含全自动的游戏与语音服务器租借服务。([源代码](https://github.com/easy-wi/developer/)) `GPL-3.0` `PHP/Shell`
- [GameAP](https://gameap.com/) - 用于在 Linux 和 Windows 上管理游戏服务器的游戏管理面板。([演示](https://demo.gameap.com/)、[源代码](https://github.com/gameap/gameap)、[客户端](https://plugins.gameap.dev/)) `MIT` `Go/Docker`
- [Gameyfin](https://gameyfin.org) - 视频游戏库管理器，具备自动扫描、Web 访问、下载和插件支持。([源代码](https://github.com/gameyfin/gameyfin)) `AGPL-3.0` `Docker`
- [Gaseous Server](https://github.com/gaseous-project/gaseous-server) `⚠` - 游戏 ROM 管理器，内置基于 Web 的模拟器，使用多个来源识别并提供元数据。 `AGPL-3.0` `Docker/.NET`
- [Lancache](https://lancache.net) `⚠` - 让局域网聚会游戏缓存变得简单。([源代码](https://github.com/lancachenet/monolithic)) `MIT` `Docker/Shell`
- [LinuxGSM](https://linuxgsm.com/) - 用于在 Linux 上部署和管理专用游戏服务器的 CLI 工具：支持 120 多款游戏。([源代码](https://github.com/GameServerManagers/LinuxGSM)) `MIT` `Shell`
- [Minus Games](https://accessory.github.io/minus_games_user_guide) - 在多台设备之间同步游戏和存档文件。([源代码](https://github.com/Accessory/minus_games)) `MIT` `Rust`
- [Ownfoil](https://github.com/a1ex4/ownfoil) - Nintendo Switch 游戏库管理器，具备自动化管理任务（文件识别与整理、缺失更新/DLC），可将你的游戏库提供给 Switch 上多个受支持的客户端，并支持商店定制和多用户认证。 `AGPL-3.0` `Docker/Python`
- [Pelican Panel](https://pelican.dev/) - 用于轻松管理游戏服务器的 Web 应用，提供友好的界面来部署、配置和管理服务器、服务器监控工具，以及大量定制选项（Pterodactyl 的分支）。([源代码](https://github.com/pelican/panel)) `AGPL-3.0` `PHP/Docker`
- [PKVault](https://github.com/Chnapy/PKVault) - 集中式宝可梦存储管理与图鉴应用（Pokémon Home 的替代方案）。([演示](https://pkvault-demo.chnapy.dev)) `GPL-3.0` `Docker`
- [Pterodactyl](https://pterodactyl.io/) - 游戏服务器管理面板，为终端用户提供直观的 UI。([源代码](https://github.com/pterodactyl/panel)) `MIT` `PHP`
- [PufferPanel](https://www.pufferpanel.com/) - 面向小型网络和游戏服务器提供商设计的游戏服务器管理面板。([源代码](https://github.com/pufferpanel/pufferpanel)) `Apache-2.0` `Go`
- [RetroArr](https://retroarr.app) `⚠` - 面向 PC 和复古主机的游戏库管理器，具备元数据抓取、索引器搜索、下载自动化和基于浏览器的模拟（RomM 的替代方案）。([源代码](https://github.com/RiDDiX/RetroArr)) `MIT` `Docker/.NET`
- [Retrom](https://github.com/JMBeresford/retrom) - 私有云游戏库分发服务器 + 前端/启动器。 `GPL-3.0` `Docker/Rust`
- [RomM](https://romm.app/) `⚠` - 用于整理、丰富和游玩复古游戏的 ROM 管理器，支持 400 多个平台。([演示](https://demo.romm.app/)、[源代码](https://github.com/rommapp/romm)) `AGPL-3.0` `Docker`
- [SourceBans++](https://sbpp.github.io/) - 面向运行在 Source 引擎上的游戏的管理员、封禁和通信管理系统。([源代码](https://github.com/sbpp/sourcebans-pp)) `CC-BY-SA-4.0` `PHP`
- [Sunshine](https://app.lizardbyte.dev/Sunshine/) - 面向 Moonlight 的远程游戏串流主机，支持最高 120 帧和 4K 分辨率。([源代码](https://github.com/LizardByte/Sunshine)) `GPL-3.0` `C++/deb/Docker`


### 家谱 <a id="genealogy"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

用于记录、整理和发布家谱数据的[家谱软件](https://en.wikipedia.org/wiki/Genealogy_software)。

- [Genea.app](https://www.genea.app/) - 注重隐私设计的家谱工具，任何人都可用它编写或编辑自己的家谱。数据以 GEDCOM 格式存储，所有处理都在浏览器中完成。([源代码](https://github.com/genea-app/genea-app)) `MIT` `Javascript`
- [Genealogy](https://genealogy.kreaweb.be/) - 记录家庭成员及其关系并构建家谱。([演示](https://genealogy.kreaweb.be/)、[源代码](https://github.com/MGeurts/genealogy)) `MIT` `PHP`
- [GeneWeb](https://github.com/geneweb/geneweb/wiki) - 可离线使用或作为 Web 服务使用的家谱软件。([源代码](https://github.com/geneweb/geneweb)) `GPL-2.0` `OCaml`
- [Gramps Web](https://www.grampsweb.org/) - 用于协作家谱研究的 Web 应用，基于开源家谱桌面应用 Gramps 并与之互操作。([演示](https://gramps-project.github.io/gramps-web-api/)、[源代码](https://github.com/gramps-project/gramps-web-api)) `AGPL-3.0` `Docker`
- [webtrees](https://www.webtrees.net) - Webtrees 是网络上领先的在线协作家谱应用。([演示](https://dev.webtrees.net/demo-stable/index.php?ctype=gedcom&ged=demo)、[源代码](https://github.com/fisharebest/webtrees)) `GPL-3.0` `PHP`


### 生成式人工智能（GenAI） <a id="generative-artificial-intelligence-genai"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[生成式人工智能（GenAI）](https://en.wikipedia.org/wiki/Generative_artificial_intelligence)是[人工智能](https://en.wikipedia.org/wiki/Artificial_intelligence)的一个子集，使用生成模型来产生文本、图像、视频或其他形式的数据。

- [Agenta](https://agenta.ai/) - LLMOps 平台，用于提示词管理、LLM 评估和可观测性。通过协作式提示词工程来构建、评估和监控生产级 LLM 应用。([源代码](https://github.com/agenta-ai/agenta)) `MIT` `Docker`
- [AnythingLLM](https://anythingllm.com/) - 一体化桌面及 Docker AI 应用，内置 RAG、AI 代理、无代码代理构建器、MCP 兼容性等。([源代码](https://github.com/Mintplex-Labs/anything-llm)) `MIT` `Nodejs/Docker`
- [GoModel](https://gomodel.enterpilot.io/) - 用 Go 编写的 AI 网关，为多个 LLM 提供商提供统一的 OpenAI 兼容 API，支持美元成本追踪、预算、用量分析、护栏、缓存和管理仪表盘。([源代码](https://github.com/ENTERPILOT/GoModel)) `MIT` `Go/Docker`
- [Khoj](https://khoj.dev/) - 你的 AI 第二大脑。从网络或你的文档中获取答案。构建自定义代理、安排自动化、进行深度研究。将任何在线或本地 LLM 变成你个人的自主 AI。([演示](https://app.khoj.dev/)、[源代码](https://github.com/khoj-ai/khoj)) `AGPL-3.0` `Python/Docker`
- [LibreChat](https://www.librechat.ai) `⚠` - 增强的 ChatGPT 兼容 AI 聊天界面，支持多个 AI 提供商，具备多用户认证、消息搜索和插件支持。([演示](https://chat.librechat.ai)、[源代码](https://github.com/LibreChat-AI/LibreChat)) `MIT` `Nodejs/Docker`
- [LLM Harbor](https://github.com/av/harbor) - 容器化的 LLM 工具包。通过简洁的 CLI 运行 LLM 后端、API、前端及附加服务。 `Apache-2.0` `Docker/Shell`
- [LLMKube](https://llmkube.com) - 用于自托管 LLM 推理的 Kubernetes operator，具备可插拔运行时（llama.cpp、vLLM、TGI、Ollama、vllm-swift）、多 GPU 分片、NVIDIA CUDA + Apple Silicon Metal 支持以及 OpenAI 兼容 API。([源代码](https://github.com/defilantech/LLMKube)) `Apache-2.0` `Go/Docker/K8S`
- [Local Deep Research](https://github.com/LearningCircuit/local-deep-research) - AI 驱动的深度研究工具，具备多源搜索（arXiv、PubMed、网络）、PDF 文本提取和加密本地存储。 `MIT` `Docker/Python`
- [LocalAI](https://localai.io/) - 在本地运行你的 AI 模型并生成图像和音频（OpenAI 和 Claude 的替代方案）。([源代码](https://github.com/mudler/LocalAI)、[客户端](https://localai.io/gallery.html)) `MIT` `Docker/K8S`
- [Ollama](https://ollama.com/) - 快速上手运行 Llama 3.3、DeepSeek-R1、Phi-4、Gemma 3 及其他大语言模型。([源代码](https://github.com/ollama/ollama)) `MIT` `Docker/Python`
- [Onyx Community Edition](https://onyx.app) - 可与任何 LLM 配合使用的聊天 UI。内置代理、网络搜索、RAG、MCP、深度研究、连接 40 多个知识来源的连接器等高级功能。([源代码](https://github.com/onyx-dot-app/onyx)) `MIT` `Docker/K8S`
- [Open-WebUI](https://openwebui.com) - 用户友好的 AI 界面，支持 Ollama、OpenAI API。([源代码](https://github.com/open-webui/open-webui)) `BSD-3-Clause` `Docker/Python`
- [Vane](https://github.com/ItzCrazyKns/Vane) - AI 驱动的搜索引擎（Perplexity AI 的替代方案）。 `MIT` `Docker`


### 群件（协同办公） <a id="groupware"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

协同软件或[群件](https://en.wikipedia.org/wiki/Collaborative_software)旨在帮助人们围绕共同任务协作以达成目标。群件通常将文件共享、日历/活动管理、预约排期、通讯录等多个服务整合到单个集成应用中。

_相关：[预约与日程安排](#booking-and-scheduling)_

- [Citadel](https://www.citadel.org/) - 群件，包括邮件、日历/排期、通讯录、论坛、邮件列表、即时通讯、wiki 与博客引擎、RSS 聚合等。([源代码](https://www.citadel.org/source.html)) `GPL-3.0` `C/Docker/Shell`
- [Colanode](https://colanode.com) - 协作套件，具备实时消息、富文本页面、文件管理和动态数据库——为离线工作而构建（Slack、Notion 的替代方案）。([源代码](https://github.com/colanode/colanode)) `Apache-2.0` `K8S/Docker`
- [Cozy Cloud](https://cozy.io/) - 个人云，可管理和同步你的文件、笔记、联系人、密码和文档。([源代码](https://github.com/cozy/)、[客户端](https://github.com/cozy/cozy-store)) `GPL-3.0` `Nodejs`
- [Digipad](https://digipad.app/) - 用于创建协作式数字记事本的在线自托管应用（文档为法语）。([源代码](https://codeberg.org/ladigitale/digipad)) `AGPL-3.0` `Nodejs`
- [Digistorm](https://digistorm.app/) - 创建协作式调查、测验、头脑风暴和词云（文档为法语）。([演示](https://digistorm.app/)、[源代码](https://codeberg.org/ladigitale/digistorm)) `AGPL-3.0` `Nodejs`
- [Digiwall](https://digiwall.app/) - 为线下或远程工作创建多媒体协作墙（文档为法语）。([源代码](https://codeberg.org/ladigitale/digiwall)) `AGPL-3.0` `Nodejs`
- [egroupware](https://www.egroupware.org/) - 软件套件，包括日历、通讯录、记事本、项目管理工具、客户关系管理工具（CRM）、知识管理工具、wiki 和 CMS。([源代码](https://github.com/EGroupware/egroupware)) `GPL-2.0` `PHP`
- [Group Office](https://www.group-office.com) - 企业 CRM 与群件工具。与同事和客户在线分享项目、日历、文件和电子邮件。([源代码](https://github.com/Intermesh/groupoffice/)) `AGPL-3.0` `PHP`
- [Openmeetings](https://openmeetings.apache.org/index.html) - 视频会议、即时通讯、白板、协作文档编辑及其他群件工具，使用 Red5 流媒体服务器的 API 功能进行远程调用和流传输。([源代码](https://github.com/apache/openmeetings)) `Apache-2.0` `Java`
- [SOGo](https://www.sogo.nu/) - SOGo 提供多种方式访问日历和消息数据。支持 CalDAV、CardDAV、GroupDAV 以及 ActiveSync，包括原生 Outlook 兼容性和 Web 界面。([演示](https://demo.sogo.nu/SOGo/)、[源代码](https://github.com/Alinto/sogo)) `LGPL-2.1` `Objective-C`
- [Tine](https://www.tine-groupware.de/) - 用于公司和组织数字化协作的软件。从强大的群件功能到巧妙的附加组件，tine 集一切于一身，让日常团队协作更轻松。([源代码](https://github.com/tine-groupware/tine)) `AGPL-3.0` `Docker`
- [Tracim](https://github.com/tracim/tracim) - 用于团队协作的协作平台：文件、讨论串、笔记、日程等。 `AGPL-3.0/LGPL-3.0/MIT` `Python`
- [Zimbra Collaboration](https://www.zimbra.com/) - 邮件、日历、协作服务器，带 Web 界面和大量集成。([源代码](https://github.com/zimbra)) `GPL-2.0/CPAL-1.0` `Java`


### 健康与健身 <a id="health-and-fitness"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[医疗](https://en.wikipedia.org/wiki/Medical_software)、[健康](https://en.wikipedia.org/wiki/Health_information_technology)与[健身](https://en.wikipedia.org/wiki/Fitness_tracker)软件。

- [Endurain](https://docs.endurain.com/) - 健身追踪服务，旨在让用户完全掌控自己的数据和托管环境。([源代码](https://codeberg.org/endurain-project/endurain)) `AGPL-3.0` `Docker`
- [FitTrackee](https://docs.fittrackee.org/) - 简单锻炼/活动追踪器。([源代码](https://github.com/SamR1/FitTrackee)) `AGPL-3.0` `Python/Docker`
- [Mere Medical](https://meremedical.co/) `⚠` - 在一处管理来自 Epic MyChart、Cerner 和 OnPatient 患者门户的所有医疗记录。注重隐私、自托管且离线优先。([演示](https://demo.meremedical.co)、[源代码](https://github.com/cfu288/mere-medical)) `GPL-3.0` `Docker/Nodejs`
- [NutriTrace](https://traceapps.github.io/docs/) - 营养与饮食追踪器，支持条形码扫描、可穿戴设备集成（Fitbit、Withings、Garmin、Health Connect）、自适应卡路里目标、多用户共享以及内置 AI 助手（MyFitnessPal、Cronometer 的替代方案）。([源代码](https://github.com/TraceApps/nutritrace)) `AGPL-3.0` `Docker`
- [OpenELIS Global](https://openelis-global.org) - 面向临床、公共卫生、环境和媒介监测实验室的实验室信息系统（LIS/LIMS）。原生支持 FHIR，具备分析仪集成（ASTM/HL7）、质量控制和国家级报告。([演示](https://openelis-global.org/getting-started/demo/)、[源代码](https://github.com/DIGI-UW/OpenELIS-Global-2)) `MPL-2.0` `Java/Docker`
- [OpenEMR](https://www.open-emr.org/) - 电子健康记录与医疗实践管理解决方案。([演示](https://www.open-emr.org/demo/)、[源代码](https://github.com/openemr/openemr)) `GPL-3.0` `PHP/Docker`
- [wger](https://wger.de/) - 基于 Web 的个人锻炼、健身与体重记录/追踪工具。也可作为简单的健身房管理工具，并提供完整的 REST API。([演示](https://wger.de/en/dashboard)、[源代码](https://github.com/wger-project/wger)) `AGPL-3.0` `Python/Docker`


### 人力资源管理（HRM） <a id="human-resources-management-hrm"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[人力资源管理系统](https://en.wikipedia.org/wiki/Human_resource_management_system)整合了多个系统与流程，以确保便捷地管理[人力资源](https://en.wikipedia.org/wiki/Human_resources)、业务流程与数据。

- [admidio](https://www.admidio.org/) - 面向组织与团体网站的用户管理系统。系统具备灵活的角色模型，可反映你组织的结构与权限。([演示](https://www.admidio.org/demo/)、[源代码](https://github.com/Admidio/admidio)) `GPL-2.0` `PHP/Docker`
- [Frappe HR](https://frappe.io/hr) - 完整的 HRMS 解决方案，拥有 13 个以上不同模块，涵盖员工管理、入职、休假到薪酬、税务等。([源代码](https://github.com/frappe/hrms)) `GPL-3.0` `Docker/Python/Nodejs`
- [MintHCM](https://minthcm.org/) - 基于两款知名热门商业应用 SugarCRM Community Edition 和 SuiteCRM 构建的人力资本管理工具。([源代码](https://github.com/minthcm/minthcm)) `AGPL-3.0` `PHP`


### 身份管理 <a id="identity-management"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[身份管理](https://en.wikipedia.org/wiki/Identity_management)（IdM），又称身份与访问管理（IAM 或 IdAM），是一套确保合适用户对技术资源拥有适当访问权限的策略与技术框架。

**请访问 [awesome-sysadmin/Identity Management](https://github.com/awesome-foss/awesome-sysadmin#identity-management)**



### 物联网（IoT） <a id="internet-of-things-iot"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[物联网](https://en.wikipedia.org/wiki/Internet_of_things)描述的是带有传感器、处理能力、软件及其他技术，能够通过互联网与其他设备连接并交换数据的物理对象。

_相关：[自动化](#automation)_

- [Domoticz](https://www.domoticz.com/) - 家庭自动化系统，可监控和配置各种设备，如：灯、开关、各种传感器/仪表（温度、雨量、风速、紫外线、电、燃气、水等）。([源代码](https://github.com/domoticz/domoticz)、[客户端](https://github.com/domoticz/domoticz-android)) `GPL-3.0` `C/C++/Docker/Shell`
- [EMQX](https://www.emqx.com/) - 可扩展的 MQTT broker。在单个集群中连接 1 亿+ IoT 设备，以 1ms 延迟、1M msg/s 吞吐量移动和处理实时 IoT 数据。([演示](https://www.emqx.com/en/mqtt/public-mqtt5-broker)、[源代码](https://github.com/emqx/emqx)) `Apache-2.0` `Docker/Erlang`
- [evcc](https://evcc.io/) - 可扩展的电动汽车充电控制器与家庭能源管理系统。([源代码](https://github.com/evcc-io/evcc)) `MIT` `deb/Docker/Go`
- [FHEM](https://fhem.de/fhem.html) - 自动化家庭中的常见任务，如开关灯和供暖。它也可用于记录温度或功耗等事件。你可以通过网页或智能手机前端、telnet 或 TCP/IP 直接控制它。([源代码](https://svn.fhem.de/trac)) `GPL-3.0` `Perl`
- [FlowForge](https://flowforge.com/) - 以可靠、可扩展且安全的方式部署 Node-RED 应用。FlowForge 平台为 Node-RED 开发团队提供 DevOps 能力。([源代码](https://github.com/FlowFuse/flowfuse)) `Apache-2.0` `Nodejs/Docker/K8S`
- [FMD Server](https://fmd-foss.org) - 与 FMD（Find My Device）Android 应用通信的服务器，用于定位和控制你的设备。([源代码](https://gitlab.com/fmd-foss/fmd-server)、[客户端](https://gitlab.com/fmd-foss/fmd-android)) `GPL-3.0` `Docker/Go`
- [Gladys](https://gladysassistant.com/) - 隐私优先的家庭助手。([源代码](https://github.com/GladysAssistant/Gladys)) `Apache-2.0` `Nodejs/Docker`
- [Home Assistant](https://home-assistant.io/) - 家庭自动化平台。([演示](https://home-assistant.io/demo/)、[源代码](https://github.com/home-assistant/core)) `Apache-2.0` `Python/Docker`
- [ioBroker](https://www.iobroker.net/) - 面向物联网的集成平台，专注于楼宇自动化、智能计量、环境辅助生活、流程自动化、可视化和数据记录。([源代码](https://github.com/ioBroker/ioBroker)) `MIT` `Nodejs`
- [LHA](https://github.com/javalikescript/lha) - 轻量家庭自动化应用，可通过 Blockly、HTML 或 Lua 完全扩展。它包含 ConBee、Philips Hue 或 Z-Wave JS 等扩展。 `MIT` `Lua`
- [Node RED](https://nodered.org/) - 基于浏览器的流程编辑器，帮助你将硬件设备、API 和在线服务连接起来，创建 IoT 解决方案。([源代码](https://github.com/node-red/node-red)) `Apache-2.0` `Nodejs/Docker`
- [Onloc](https://onloc.app) - 实时追踪和分享你的位置。控制和锁定被盗或丢失的手机。([源代码](https://github.com/onloc-app/onloc-api)、[客户端](https://github.com/onloc-app/onloc-android)) `AGPL-3.0` `Docker`
- [openHAB](https://www.openhab.org) - 与厂商和技术无关的家庭自动化开源软件。([源代码](https://github.com/openhab/openhab-core)) `EPL-2.0` `Java`
- [OpenRemote](https://openremote.io) - IoT 资产管理、流程规则与 WHEN-THEN 规则、数据可视化、边缘网关。([演示](https://demo.openremote.io/)、[源代码](https://github.com/openremote/openremote)) `AGPL-3.0` `Java`
- [polluSensWeb](https://wespeakenglish.github.io/polluSensWeb/) - 基于 Web 的串口接口与图表工具，用于可视化和记录 UART 污染传感器（PM2.5、VOC 等）的数据。具备实时数据采集、动态图表、CSV 导出和 Webhook 集成。([演示](https://wespeakenglish.github.io/polluSensWeb/)、[源代码](https://github.com/WeSpeakEnglish/polluSensWeb)、[客户端](https://github.com/WeSpeakEnglish/polluSensWeb/releases)) `MIT` `Javascript`
- [SIP Irrigation Control](https://dan-in-ca.github.io/SIP/) - 用于喷灌/灌溉控制的开源软件。([源代码](https://github.com/Dan-in-CA/SIP)) `GPL-3.0` `Python`
- [SOLECTRUS](https://solectrus.de) - 光伏仪表盘，展示能源生产与消耗，并计算成本与节省。([演示](https://demo.solectrus.de)、[源代码](https://github.com/solectrus/solectrus)) `AGPL-3.0` `Docker`
- [Tasmota](https://tasmota.com) - 面向 ESP 设备的开源固件。完全本地控制，设置和更新快速。可通过 MQTT、Web UI、HTTP 或串口控制。使用定时器、规则或脚本自动化。与家庭自动化解决方案集成。([源代码](https://github.com/arendst/Tasmota)) `GPL-3.0` `C/C++`
- [Thingsboard](https://thingsboard.io/) - IoT 平台——设备管理、数据采集、处理与可视化。([演示](https://demo.thingsboard.io/signup)、[源代码](https://github.com/thingsboard/thingsboard)) `Apache-2.0` `Java/Docker/K8S`
- [WebThings Gateway](https://webthings.io/gateway/) - WebThings 是 Web of Things 的开源实现，包括 WebThings Gateway 和 WebThings Framework。([源代码](https://github.com/WebThingsIO/gateway)) `MPL-2.0` `Nodejs`


### 库存管理 <a id="inventory-management"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[库存管理软件](https://en.wikipedia.org/wiki/Inventory_management_software)。

_相关：[财务、预算与管理](#money-budgeting--management)、[资源规划](#resource-planning)_

_另见：[awesome-sysadmin/IT Asset Management](https://github.com/awesome-foss/awesome-sysadmin#it-asset-management)_

- [Cannery](https://cannery.app) - 枪械与弹药追踪应用。([源代码](https://gitlab.com/shibaobun/cannery)) `AGPL-3.0` `Docker`
- [DVinyl](https://github.com/Kyonew/DVinyl) `⚠` - 面向实体媒介（黑胶、CD、磁带、书籍、电影和电子游戏）的现代收藏管理器。 `MIT` `Nodejs/Docker`
- [HomeBox (SysAdminsMedia)](https://homebox.software/) - 为家庭用户构建的库存与整理系统。([演示](https://demo.homebox.software/)、[源代码](https://github.com/sysadminsmedia/homebox)) `AGPL-3.0` `Docker/Go`
- [Inventaire](https://inventaire.io/welcome) - 协作式资源映射项目，目前仅专注于结合 wikidata 和 ISBN 探索图书映射。([源代码](https://codeberg.org/inventaire/inventaire)) `AGPL-3.0` `Nodejs`
- [Inventree](https://docs.inventree.org/en/latest/) - 库存管理系统，提供直观的零件管理与库存控制。([演示](https://inventree.org/demo)、[源代码](https://github.com/inventree/InvenTree)) `MIT` `Python`
- [Open QuarterMaster](https://openquartermaster.com/) - 功能强大的库存管理系统，设计灵活且可扩展。([源代码](https://github.com/Epic-Breakfast-Productions/OpenQuarterMaster)) `GPL-3.0` `deb/Docker`
- [Part-DB](https://docs.part-db.de/) - 面向电子元器件的库存管理系统。([演示](https://demo.part-db.de/en/)、[源代码](https://github.com/Part-DB/Part-DB-server)) `AGPL-3.0` `Docker/PHP/Nodejs`
- [Spoolman](https://github.com/Donkie/Spoolman) - 追踪你的 3D 打印耗材卷库存。 `MIT` `Docker/Python`


### 知识管理工具 <a id="knowledge-management-tools"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[知识管理](https://en.wikipedia.org/wiki/Knowledge_management)是与创建、共享、使用和管理知识与信息相关的方法集合。

_相关：[笔记与编辑器](#note-taking--editors)、[Wiki](#wikis)、[数据库管理](#database-management)_

- [Atomic Server](https://atomicserver.eu/) - 带文档（类似 Notion）、表格、搜索和强大关联数据 API 的知识图谱数据库。轻量、极快且无运行时依赖。([演示](https://atomicdata.dev/)、[源代码](https://github.com/ontola/atomic-server)) `MIT` `Docker/Rust`
- [Digimindmap](https://ladigitale.dev/digimindmap/#/) - 创建简单的思维导图（文档为法语）。([演示](https://ladigitale.dev/digimindmap/#/)、[源代码](https://codeberg.org/ladigitale/digimindmap)) `AGPL-3.0` `Nodejs/PHP`
- [LibreKB](https://librekb.com/) - 基于 Web 的知识库解决方案。一个简单的 Web 应用，几乎可在任何支持 PHP 和 MySQL 的 Web 服务器或托管服务商上运行。([源代码](https://github.com/michaelstaake/LibreKB/)) `GPL-3.0` `PHP`
- [Marmot](https://marmotdata.io) - 数据目录，用于发现和整理你整个技术栈中的数据资产，包括数据库、API、消息队列和管道。([演示](https://demo.marmotdata.io)、[源代码](https://github.com/marmotdata/marmot)) `MIT` `Docker`
- [memEx](https://gitlab.com/shibaobun/memex) - 结构化的个人知识库，灵感来自 zettelkasten 和 org-mode。 `AGPL-3.0` `Docker`
- [SiYuan](https://b3log.org/siyuan/) - 隐私优先的个人知识管理软件，使用 TypeScript 和 Golang 编写。([源代码](https://github.com/siyuan-note/siyuan)) `AGPL-3.0` `Docker/Go`
- [TeamMapper](https://github.com/b310-digital/teammapper) - 托管并创建你自己的思维导图。与团队分享你的思维导图会话并实时协作编辑。([演示](https://map.kits.blog)) `MIT` `Docker/Nodejs`


### 学习与课程 <a id="learning-and-courses"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

用于辅助教育与学习的工具和软件。

- [Canvas LMS](https://www.instructure.com/canvas/) - 学习管理系统（LMS），正在革新我们教育的方式。([源代码](https://github.com/instructure/canvas-lms)) `AGPL-3.0` `Ruby`
- [Chamilo LMS](https://chamilo.org/) - 创建虚拟校园以提供在线或半在线培训。([源代码](https://github.com/chamilo/chamilo-lms)) `GPL-3.0` `PHP`
- [Digiscreen](https://ladigitale.dev/digiscreen/) - 面向课堂的交互式白板/壁纸，支持线下或远程（文档为法语）。([演示](https://ladigitale.dev/digiscreen/)、[源代码](https://codeberg.org/ladigitale/digiscreen)) `AGPL-3.0` `Nodejs/PHP`
- [Digitools](https://ladigitale.dev/digitools) - 一套简单工具，配合课程教学（线下或远程）使用（文档为法语）。([演示](https://ladigitale.dev/digitools/)、[源代码](https://codeberg.org/ladigitale/digitools)) `AGPL-3.0` `PHP`
- [edX](https://www.edx.org/) - 驱动 edX.org 网站的在线学习平台。([源代码](https://github.com/edx/)) `AGPL-3.0` `Python`
- [Gibbon](https://gibbonedu.org/) - 灵活的学校管理平台，旨在让教师、学生、家长和管理者的生活更美好。([源代码](https://github.com/GibbonEdu/core)) `GPL-3.0` `PHP`
- [Helium](https://www.heliumedu.com) - 用颜色区分的面向学生的规划工具，涵盖课程、作业、成绩和笔记，具备智能通知和多设备同步。([演示](https://app.heliumedu.com)、[源代码](https://github.com/HeliumEdu/platform)) `MIT` `Python/Docker`
- [ILIAS](https://www.ilias.de) - 学习管理系统，能应对你抛给它的一切。([演示](https://demo.ilias.de)、[源代码](https://github.com/ILIAS-eLearning/ILIAS)) `GPL-3.0` `PHP`
- [INGInious](https://inginious.org/?lang=en) - 智能评分器，可对学生编写的代码进行安全、自动化的测试。([源代码](https://github.com/INGInious/INGInious)、[客户端](https://github.com/INGInious/plugins)) `AGPL-3.0` `Python/Docker`
- [Moodle](https://moodle.org/) - 学习与课程平台，拥有全球最大的开源社区之一。([演示](https://moodle.org/demo/)、[源代码](https://git.moodle.org/gw)) `GPL-3.0` `PHP`
- [Open eClass](https://www.openeclass.org/) - Open eClass 是一个先进的电子学习解决方案，可提升教与学的过程。([演示](https://demo.openeclass.org/)、[源代码](https://github.com/gunet/openeclass)) `GPL-2.0` `PHP`
- [OpenOLAT](https://www.openolat.com/?lang=en) - 用于教学、教育、评估和沟通的学习管理系统。([演示](https://learn.olat.com)、[源代码](https://github.com/OpenOLAT/OpenOLAT)) `Apache-2.0` `Java`
- [QST](https://qstonline.org) - 在线测评软件。从手机上的快速测验到大规模、高利害、有监考的桌面测试，简单、安全且经济。([演示](https://qstonline.org/free_account.htm)、[源代码](https://sourceforge.net/projects/qstonline/)) `GPL-2.0` `Perl`
- [RELATE](https://documen.tician.de/relate/) - 课件包，包含灵活规则、统计、多课程支持、班级日历等功能。([源代码](https://github.com/inducer/relate)) `MIT` `Python`
- [RosarioSIS](https://www.rosariosis.org/) - 面向学校管理的学生信息系统。具备学生人口统计、成绩、排课、出勤、学生账单、纪律与餐饮服务等模块。([演示](https://www.rosariosis.org/demo/)、[源代码](https://gitlab.com/francoisjacquet/rosariosis/)) `GPL-2.0` `PHP`


### 制造业 <a id="manufacturing"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

用于管理[3D 打印机](https://en.wikipedia.org/wiki/3D_printing)、[CNC 机床](https://en.wikipedia.org/wiki/Numerical_control)及其他物理制造工具的软件。

- [CNCjs](https://cnc.js.org/) - 面向运行 Grbl、Smoothieware 或 TinyG 的 CNC 铣削控制器的 Web 界面。([源代码](https://github.com/cncjs/cncjs/)) `MIT` `Nodejs`
- [Fluidd](https://docs.fluidd.xyz/) - 面向 Klipper（3D 打印机固件）的轻量且响应式用户界面。([源代码](https://github.com/fluidd-core/fluidd)) `GPL-3.0` `Docker/Nodejs`
- [LinuxCNC](https://www.linuxcnc.org/) - 基于 Linux 的 CNC 机床控制器。可驱动铣床、车床、3D 打印机、激光切割机、等离子切割机、机械臂、六足机器人等。([源代码](https://github.com/LinuxCNC/linuxcnc)) `GPL-2.0/LGPL-3.0` `C/deb`
- [Mainsail](https://docs.mainsail.xyz/) - 面向 Klipper 3D 打印机固件的现代且响应式用户界面。可从任何地方、任何设备控制和监控你的打印机。([源代码](https://github.com/mainsail-crew/mainsail)) `GPL-3.0` `Docker/Python`
- [Manyfold](https://manyfold.app) - 面向 3D 打印文件（STL、OBJ、3MF 等）的数字资产管理器。([源代码](https://github.com/manyfold3d/manyfold)) `MIT` `Docker`
- [Octoprint](https://octoprint.org/) - 用于控制消费级 3D 打印机的灵敏 Web 界面。([源代码](https://github.com/OctoPrint/OctoPrint)) `AGPL-3.0` `Docker/Python`


### 地图与全球定位系统（GPS） <a id="maps-and-global-positioning-system-gps"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[地图](https://en.wikipedia.org/wiki/Map)、[制图](https://en.wikipedia.org/wiki/Cartography)、[GIS](https://en.wikipedia.org/wiki/Geographic_information_system) 与 [GPS](https://en.wikipedia.org/wiki/Global_Positioning_System) 软件。

_相关：[旅行组织](#travel-organization)_

_另见：[awesome-openstreetmap](https://github.com/osmlab/awesome-openstreetmap)、[awesome-gis](https://github.com/sshuair/awesome-gis)_

- [AdventureLog](https://adventurelog.app) - 旅行追踪器与行程规划工具。([演示](https://demo.adventurelog.app/signup)、[源代码](https://github.com/seanmorley15/AdventureLog)) `GPL-3.0` `Docker`
- [AirTrail](https://airtrail.johan.ohly.dk) - 个人飞行追踪系统。([源代码](https://github.com/johanohly/AirTrail)) `GPL-3.0` `Docker/Nodejs`
- [Bicimon](https://github.com/knrdl/bicimon) - 作为渐进式 Web 应用（PWA）的自行车速度计。([演示](https://knrdl.github.io/bicimon/)) `MIT` `Javascript`
- [Dawarich](https://dawarich.app/) - 在完全隐私和掌控的前提下可视化你的位置历史、追踪你的移动并分析你的出行规律（Google Timeline 即 Google Location History 的替代方案）。([源代码](https://github.com/Freika/dawarich)) `AGPL-3.0` `Docker`
- [Geo2tz](https://github.com/noandrea/geo2tz) - 根据地理坐标（纬度、经度）获取时区。 `MIT` `Go/Docker`
- [GraphHopper](https://graphhopper.com/) - 使用 OpenStreetMap 数据的快速路径规划库与服务器。([源代码](https://github.com/graphhopper/graphhopper)) `Apache-2.0` `Java`
- [NextGIS Web](https://nextgis.com/nextgis-web/) - 用于地理空间数据管理、Web 地图发布和以 QGIS 为中心的协作工作流的 Web GIS 服务器。([演示](https://sandbox.nextgis.com)、[源代码](https://github.com/nextgis/nextgisweb)) `GPL-3.0` `Docker`
- [Nominatim](https://nominatim.org/) - 在 OpenStreetMap 数据上进行地理编码（地址 → 坐标）和逆地理编码（坐标 → 地址）的服务器应用。([源代码](https://github.com/osm-search/Nominatim)) `GPL-2.0` `C`
- [Open Source Routing Machine (OSRM)](http://project-osrm.org/) - 高性能路径规划引擎，设计用于 OpenStreetMap 数据，提供 HTTP API、C++ 库接口和 Nodejs 封装。([演示](https://map.project-osrm.org/)、[源代码](https://github.com/Project-OSRM/osrm-backend)) `BSD-2-Clause` `C++`
- [OpenRouteService](https://openrouteservice.org/) - 路线服务，具备导航、等时圈、时间-距离矩阵、路线优化等。([演示](https://openrouteservice.org/dev/#/api-docs/introduction)、[源代码](https://github.com/GIScience/openrouteservice)) `GPL-3.0` `Docker/Java`
- [OpenStreetMap](https://www.openstreetmap.org/) - 创建免费可编辑世界地图的协作项目。([源代码](https://github.com/openstreetmap/openstreetmap-website)、[客户端](https://wiki.openstreetmap.org/wiki/Software)) `GPL-2.0` `Ruby`
- [OpenTripPlanner](https://www.opentripplanner.org/) - 基于 OpenStreetMap 数据并消费已发布的 GTFS 格式数据的多模式出行规划软件，可利用本地公共交通系统推荐路线。([源代码](https://github.com/opentripplanner/OpenTripPlanner)) `LGPL-3.0` `Java/Javascript`
- [OwnTracks Recorder](https://github.com/owntracks/recorder) `⚠` - 存储和访问由 [OwnTracks](https://owntracks.org/) 位置追踪应用发布的数据。 `GPL-2.0` `C/Lua/deb/Docker`
- [TileServer GL](https://tileserver.readthedocs.io/) - 带 GL 样式的矢量与栅格地图。通过 Mapbox GL Native 进行服务端渲染。面向 Mapbox GL JS、Android、iOS、Leaflet、OpenLayers 以及通过 WMTS 的 GIS 等地提供地图瓦片服务。([源代码](https://github.com/maptiler/tileserver-gl)) `BSD-2-Clause` `Nodejs/Docker`
- [Traccar](https://www.traccar.org/) - 用于追踪 GPS 位置的 Java 应用。支持大量追踪设备与协议，拥有 Android 和 iOS 应用。具备查看行程的 Web 界面。([演示](https://demo.traccar.org/)、[源代码](https://github.com/traccar)) `Apache-2.0` `Java`
- [TRIP](https://itskovacs-trip.netlify.app/) - 极简的兴趣点（POI）地图追踪器与行程规划工具。([演示](https://itskovacs-trip.netlify.app/home)、[源代码](https://github.com/itskovacs/trip)) `MIT` `Docker`
- [wanderer](https://github.com/open-wanderer/wanderer) - 轨迹数据库，你可上传已记录的轨迹或创建新轨迹，并添加各种元数据以构建易于检索的目录。([演示](https://demo.wanderer.to)) `AGPL-3.0` `Docker/Go/Nodejs`


### 媒体管理 <a id="media-management"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[数字媒体](https://en.wikipedia.org/wiki/Digital_media)管理工具与软件。

_相关：[自动化](#automation)、[媒体流](#media-streaming)、[媒体流 - 音频流](#media-streaming---audio-streaming)、[媒体流 - 多媒体流](#media-streaming---multimedia-streaming)、[媒体流 - 视频流](#media-streaming---video-streaming)、[媒体管理](#media-management)_

- [ChannelTube](https://github.com/TheWicklowWolf/ChannelTube) `⚠` - 通过 yt-dlp 按计划从 YouTube 频道下载视频或音频。 `AGPL-3.0` `Docker`
- [Deleterr](https://github.com/rfsbraz/deleterr) - 自动化媒体清理工具，根据可配置的规则从 Plex、Sonarr 和 Radarr 中移除已观看和过期的内容。 `MIT` `Docker`
- [Downtify](https://downtify.henriquesebastiao.com) `⚠` - 下载带专辑封面和元数据的 Spotify 音乐。([源代码](https://github.com/henriquesebastiao/downtify)) `GPL-3.0` `Docker`
- [Elengrab](https://github.com/neosy/elengrab) - 快速的跨平台音视频下载器与媒体查看器，具备灵活的格式和质量选项。支持 1000 多个网站，包括 YouTube、Instagram、TikTok、Twitch 等。([演示](https://elengrab.n-hub.ru)) `AGPL-3.0` `Go/Docker`
- [HomeTube](https://hometube.latentnoise.dev) `⚠` - Web UI，可从 1700 多个站点下载视频和播放列表到 Plex 或 Jellyfin 媒体库，支持质量选择、SponsorBlock 赞助片段移除、字幕、片段裁剪和健壮的播放列表同步。([源代码](https://github.com/EgalitarianMonkey/hometube)) `AGPL-3.0` `Python/Docker`
- [Houndarr](https://av1155.github.io/houndarr/) - 为 Radarr、Sonarr、Lidarr、Readarr 和 Whisparr 进行计划性的积压搜索。以小型、限速的批次处理缺失和未达标项目，具备单项冷却与每小时上限，以避免压垮索引器。([源代码](https://github.com/av1155/houndarr)) `AGPL-3.0` `Python/Docker`
- [Lidarr](https://lidarr.audio/) - 面向 Usenet 和 BitTorrent 用户的音乐收藏管理器。([源代码](https://github.com/Lidarr/Lidarr)) `GPL-3.0` `C#/Docker`
- [LidaTube](https://github.com/TheWicklowWolf/LidaTube) `⚠` - 通过 yt-dlp 查找并获取 Lidarr 缺失的专辑。 `GPL-3.0` `Docker`
- [Lidify](https://github.com/TheWicklowWolf/Lidify) `⚠` - 音乐发现工具，基于选定的 Lidarr 艺术家，使用 Spotify 或 LastFM 提供推荐。 `MIT` `Docker`
- [Lingarr](https://lingarr.com) - 使用 LibreTranslate、本地 AI 模型或 SaaS 翻译服务，自动翻译 Radarr 和 Sonarr 媒体库中的字幕文件。([源代码](https://github.com/lingarr-translate/lingarr)) `AGPL-3.0` `Docker`
- [Medusa](https://github.com/pymedusa/Medusa) - 面向电视剧的自动视频库管理器。它会监控你喜爱剧集的新集数，一旦发布便施展魔法。([客户端](https://github.com/medusajs/nextjs-starter-medusa)) `GPL-3.0` `Python`
- [MeTube](https://github.com/alexta69/metube) - youtube-dl 的 Web GUI，支持播放列表。可下载数十个网站的视频。 `AGPL-3.0` `Python/Nodejs/Docker`
- [MKVPriority](https://github.com/kennethsible/mkvpriority) - 使用可配置的优先级评分选择首选的音频和字幕轨道，并设置相应的默认与强制标志。 `MIT` `Python/Docker`
- [MyTube](https://github.com/franklioxygen/MyTube) `⚠` - 面向 yt-dlp 支持站点的下载器与播放器，支持频道订阅、云上传支持和本地库整理。([演示](https://mytube-demo.vercel.app)) `MIT` `Nodejs/Docker`
- [nefarious](https://lardbit.github.io/nefarious/) - 自动化下载电影和电视剧。([源代码](https://github.com/lardbit/nefarious)) `GPL-3.0` `Python`
- [Ombi](https://ombi.io/) - 面向 Plex/Emby 的内容请求系统，可连接 SickRage、CouchPotato、Sonarr，功能集不断增长。([演示](https://app.ombi.io/)、[源代码](https://github.com/Ombi-app/Ombi)) `GPL-2.0` `C#/deb`
- [Pinchflat](https://github.com/kieraneglin/pinchflat) `⚠` - 使用 yt-dlp 构建的 YouTube 内容下载器。 `AGPL-3.0` `Docker`
- [PodFetch](https://samtv12345.github.io/PodFetch) - 简洁高效的播客下载器。([源代码](https://github.com/SamTV12345/PodFetch)) `Apache-2.0` `Docker/Rust`
- [Radarr](https://radarr.video/) - 通过 Usenet 和 BitTorrent 自动下载电影（Sonarr 的分支）。([源代码](https://github.com/Radarr/Radarr)) `GPL-3.0` `C#/Docker`
- [Ratelog](https://ratelog.org) - 电影追踪与评分应用（Letterboxd 的替代方案）。([源代码](https://github.com/golmenero/ratelog)) `AGPL-3.0` `Docker`
- [Reaparr](https://www.reaparr.rocks/) `⚠` - 跨平台 Plex 媒体下载器，可将其他 Plex 服务器上的媒体无缝添加到你自己的服务器。([源代码](https://github.com/Reaparr/Reaparr)) `GPL-3.0` `Docker`
- [Seerr](https://github.com/seerr-team/seerr) - 管理媒体库的请求，支持 Plex、Jellyfin 和 Emby 媒体服务器（Overseerr 的分支）。 `MIT` `Docker/Nodejs`
- [Sonarr](https://sonarr.tv/) - 面向 Usenet 和 BitTorrent 的自动电视剧下载器与管理器。可抓取、排序并重命名新剧集，并在出现更高质量格式时自动升级已下载文件的质量。([源代码](https://github.com/Sonarr/Sonarr)) `GPL-3.0` `C#/Docker`
- [TrackWatch](https://trackwatch.emlopezr.com) `⚠` - 面向 Spotify 的自动化音乐发行追踪器，具备邮件通知、音乐作品目录生成器和幽灵曲目清理（Release Radar 的替代方案）。([源代码](https://github.com/emlopezr/trackwatch)) `MIT` `Docker`
- [tubesync](https://github.com/meeb/tubesync) `⚠` - 将 YouTube 频道和播放列表同步到本地托管的媒体服务器。 `AGPL-3.0` `Docker/Python`
- [Watcharr](https://github.com/sbondCo/Watcharr) - 添加并追踪你正在观看的所有剧集和电影。具备用户认证、现代简洁的 UI 和非常简单的设置。 `MIT` `Docker`
- [ydl_api_ng](https://github.com/Totonyus/ydl_api_ng) - 简单的 youtube-dl REST API，可在远程服务器上启动下载。 `GPL-3.0` `Python`
- [Youtarr](https://github.com/DialmasterOrg/Youtarr) `⚠` - 通过 yt-dlp 按计划从 YouTube 频道下载视频，带 Web UI 浏览和有选择地下载视频。与 Plex Media Server 集成，并为 Jellyfin、Kodi 和 Emby 生成 NFO 元数据。 `ISC` `Docker`
- [youtube-dl-nas](https://hyeonsangjeon.github.io/youtube-dl-nas/) `⚠` - 带认证的 yt-dlp 视频、音频和字幕下载队列，具备历史记录、移动分享和 NAS 文件管理（youtube-dl-server 的分支）。([源代码](https://github.com/hyeonsangjeon/youtube-dl-nas)) `MIT` `Python/Docker`
- [YoutubeDL-Server](https://github.com/nbr23/youtube-dl-server) - Youtube-DL 的 Web 和 REST 接口，用于将视频下载到服务器上。 `MIT` `Python/Docker`
- [yt-dlp Web UI](https://github.com/marcopiovanello/yt-dlp-web-ui) - yt-dlp 的 Web GUI。 `MPL-2.0` `Docker/Go/Nodejs`


### 媒体流 <a id="media-streaming"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[流媒体](https://en.wikipedia.org/wiki/Streaming_media)是以连续方式从来源传输和消费、在网络节点中几乎或完全不做中间存储的多媒体。

**请访问[媒体流 - 音频流](#media-streaming---audio-streaming)、[媒体流 - 多媒体流](#media-streaming---multimedia-streaming)、[媒体流 - 视频流](#media-streaming---video-streaming)、[媒体管理](#media-management)**

_相关：[媒体流](#media-streaming)_

_另见：[List of streaming media systems - Wikipedia](https://en.wikipedia.org/wiki/List_of_streaming_media_systems)、[Comparison of streaming media systems - Wikipedia](https://en.wikipedia.org/wiki/Comparison_of_streaming_media_systems)_



### 媒体流 - 音频流 <a id="media-streaming---audio-streaming"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[音频](https://en.wikipedia.org/wiki/Audio)流工具与软件。

_相关：[媒体管理](#media-management)_

- [Ampache](https://ampache.org/) - 基于 Web 的音视频流应用。([演示](https://play.dogmazic.net/)、[源代码](https://github.com/ampache/ampache)) `AGPL-3.0` `PHP`
- [Audiobookshelf](https://www.audiobookshelf.org/) - 有声书与播客服务器。可流式传输所有音频格式，跨设备保存并同步进度。附带 Android 和 iOS 应用。([源代码](https://github.com/advplyr/audiobookshelf)、[客户端](https://github.com/advplyr/audiobookshelf-app)) `GPL-3.0` `Docker/deb/Nodejs`
- [Audioserve](https://github.com/izderadicka/audioserve) - 简单的个人服务器，用于从目录提供音频文件（有声书、音乐、播客……）。注重简洁，支持客户端之间播放位置同步。 `MIT` `Rust`
- [AzuraCast](https://www.azuracast.com/) - 现代且易用的网络电台管理套件。([源代码](https://github.com/AzuraCast/AzuraCast)) `Apache-2.0` `Docker`
- [Beets](https://beets.io/) - 音乐库管理器与 MusicBrainz 标签工具（命令行和 Web 界面）。([源代码](https://github.com/beetbox/beets)) `MIT` `Python/deb`
- [Black Candy](https://github.com/blackcandy-org/blackcandy) - 音乐流媒体服务器。 `MIT` `Docker/Ruby`
- [BotWave](https://botwave.dpip.lol) - FM 广播系统，采用客户端-服务器架构，可远程管理多个树莓派发射机。([源代码](https://github.com/dpipstudio/botwave)) `GPL-3.0` `Python`
- [Funkwhale](https://dev.funkwhale.audio/funkwhale) - 现代、基于 Web、友好、多用户且自由的音乐服务器。 `BSD-3-Clause` `Python`
- [gonic](https://github.com/sentriz/gonic) - 轻量级音乐流媒体服务器。兼容 Subsonic。 `GPL-3.0` `Go/Docker`
- [koel](https://koel.dev/) - 真的能用的个人音乐流媒体服务器。([演示](https://demo.koel.dev/)、[源代码](https://github.com/koel/koel)) `MIT` `PHP`
- [LibreTime](https://libretime.org) - 在网络上进行广播流媒体电台（[Airtime](https://github.com/sourcefabric/Airtime) 的分支）。([源代码](https://github.com/LibreTime/libretime)) `AGPL-3.0` `Docker/PHP`
- [LMS](https://github.com/epoupon/lms) - 通过 Web 界面访问你自托管的音乐。 `GPL-3.0` `Docker/deb/C++`
- [Lyrion Music Server](https://lyrion.org/) - 服务器软件，可控制多种 Squeezebox/Slim Devices 音频播放器及兼容硬件（原名 Logitech Media Server）。([源代码](https://github.com/lms-community/slimserver)、[客户端](https://lyrion.org/extensions/applications/)) `GPL-2.0` `deb/Docker/Perl`
- [moOde Audio](https://moodeaudio.org/) - 面向出色的树莓派系列单板计算机的发烧级音乐播放。([源代码](https://github.com/moode-player/moode)) `GPL-3.0` `PHP`
- [Mopidy](https://docs.mopidy.com/) `⚠` - 可扩展的音乐服务器。提供 mpd API 的超集，并与 Spotify、SoundCloud 等第三方服务集成。([源代码](https://github.com/mopidy/mopidy)) `Apache-2.0` `Python/deb`
- [mpd](https://www.musicpd.org/) - 用于远程播放音乐、流式传输音乐、处理和整理播放列表的守护进程。有大量可用客户端。([源代码](https://github.com/MusicPlayerDaemon/MPD)、[客户端](https://www.musicpd.org/clients/)) `GPL-2.0` `C++`
- [mStream](https://mstream.io/) - 带 GUI 管理工具的音乐流媒体服务器。可在 Mac、Windows 和 Linux 上运行。([源代码](https://github.com/IrosTheBeggar/mStream)) `GPL-3.0` `Nodejs`
- [multi-scrobbler](https://foxxmd.github.io/multi-scrobbler) - 将来自多个来源的播放记录 scrobble 到多个 scrobble 服务。([源代码](https://github.com/FoxxMD/multi-scrobbler)) `MIT` `Nodejs/Docker`
- [musikcube](https://github.com/clangen/musikcube) - 流式音频服务器，提供 Linux/macOS/Windows/Android 客户端。 `BSD-3-Clause` `C++/deb`
- [Navidrome Music Server](https://www.navidrome.org) - 现代音乐服务器与流媒体播放器，兼容 Subsonic/Airsonic。([演示](https://www.navidrome.org/demo)、[源代码](https://github.com/navidrome/navidrome)、[客户端](https://www.navidrome.org/docs/overview/#apps)) `GPL-3.0` `Docker/Go`
- [Pinepods](https://www.pinepods.online/) - 支持多用户的播客管理系统。Pinepods 使用中央数据库，因此收听时间和主题等设置可在各设备间延续。([演示](https://try.pinepods.online)、[源代码](https://github.com/madeofpendletonwool/PinePods)) `GPL-3.0` `Docker`
- [Polaris](https://github.com/agersant/polaris) - 音乐浏览与流媒体应用，针对大型音乐收藏、易用性和高性能进行了优化。 `MIT` `Rust/Docker`
- [Snapcast](https://github.com/snapcast/snapcast) - 同步的多房间音频服务器。 `GPL-3.0` `C++/deb`
- [Stretto](https://github.com/benkaiser/stretto) `⚠` - 带 Youtube/Soundcloud 导入和 iTunes/Spotify 发现的音乐播放器。([演示](https://next.kaiserapps.com)、[客户端](https://github.com/benkaiser/stretto-mobile-next)) `MIT` `Nodejs`
- [Supysonic](https://github.com/spl0k/supysonic) - Subsonic 服务器 API 的 Python 实现。 `AGPL-3.0` `Python/deb`
- [SwingMusic](https://swingmusic.vercel.app/) - Swing Music 是一款美观的自托管音乐播放器与流媒体服务器，面向你的本地音频文件。就像更酷的 Spotify……但音乐是你自己的。([源代码](https://github.com/swingmx/swingmusic)) `MIT` `Python/Docker`
- [vod2pod-rss](https://github.com/madiele/vod2pod-rss) `⚠` - 将 YouTube 和 Twitch 频道转换为播客，无需存储。即时将 VOD 转码为 192k 的 MP3，并生成可在播客客户端中使用的 RSS 订阅。 `MIT` `Docker`


### 媒体流 - 多媒体流 <a id="media-streaming---multimedia-streaming"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[多媒体](https://en.wikipedia.org/wiki/Multimedia)流工具与软件。

_相关：[媒体流 - 视频流](#media-streaming---video-streaming)、[媒体流 - 音频流](#media-streaming---audio-streaming)、[媒体管理](#media-management)_

- [ClipBucket](https://clipbucket.fr/) - 几分钟内即可启动你自己的视频分享网站（YouTube/Netflix 克隆）。([演示](https://demo.clipbucket.oxygenz.fr/)、[源代码](https://github.com/MacWarrior/clipbucket-v5)) `AAL` `Docker/PHP`
- [cmyflix](https://github.com/farfalleflickan/cmyflix) - 极简的 Plex/Jellyfin 替代方案，用于流式传输视频。 `AGPL-3.0` `C/deb`
- [Gerbera](https://gerbera.io/) - UPnP 媒体服务器，可让你在整个家庭网络中流式传输数字媒体，并在各种 UPnP 兼容设备上收听/观看。([源代码](https://github.com/gerbera/gerbera)) `GPL-2.0` `Docker/deb/C++`
- [Icecast 2](https://icecast.org) - 流式音视频服务器，可用于创建互联网电台或私人点唱机，以及介于两者之间的许多用途。([源代码](https://gitlab.xiph.org/xiph/icecast-server)、[客户端](https://icecast.org/apps/)) `GPL-2.0` `C`
- [Jellyfin](https://jellyfin.org) - 面向音频、视频、图书、漫画和照片的媒体服务器，界面美观，转码能力强劲。几乎所有现代平台都有客户端，包括 Roku、Android TV、iOS 和 Kodi。([演示](https://demo.jellyfin.org/stable)、[源代码](https://github.com/jellyfin/jellyfin)、[客户端](https://github.com/awesome-jellyfin/awesome-jellyfin)) `GPL-2.0` `C#/deb/Docker`
- [Karaoke Eternal](https://www.karaoke-eternal.com) - 举办超棒的卡拉 OK 派对，每个人都能轻松地用手机浏览器找到并点歌。播放器也完全基于浏览器，支持 MP3+G、MP4 和 WebGL 可视化。([源代码](https://github.com/bhj/KaraokeEternal)) `ISC` `Docker/Nodejs`
- [Kodi](https://kodi.tv/) - 多媒体/娱乐中心，原名 XBMC。可在 Android、BSD、Linux、macOS、iOS 和 Windows 上运行。([源代码](https://github.com/xbmc/xbmc)) `GPL-2.0` `C++/deb`
- [Kyoo](https://github.com/zoriya/kyoo) - 创新媒体浏览器，专为无缝流式播放动漫、剧集和电影而设计，提供动态转码、自动观看历史和智能元数据检索等高级功能。([演示](https://kyoo.zoriya.dev)) `GPL-3.0` `Docker`
- [MediaMTX](https://mediamtx.org) - 开箱即用、零依赖的实时媒体服务器与代理，可通过 SRT、WebRTC、RTSP、RTMP、HLS、MPEG-TS、RTP 发布、读取、录制、回放和路由音视频流。([源代码](https://github.com/bluenviron/mediamtx)、[客户端](https://mediamtx.org/docs/kickoff/introduction)) `MIT` `Go/Docker`
- [Meelo](https://github.com/Arthi-chaud/Meelo) - 个人音乐服务器，专为收藏家和音乐狂热者设计。 `GPL-3.0` `Docker`
- [MistServer](https://mistserver.org/) - 公有领域的流媒体服务器，兼容任何设备和任何格式。([源代码](https://github.com/DDVTECH/mistserver)) `Unlicense` `C++`
- [NymphCast](http://nyanko.ws/nymphcast.php) - 将你选择的支持 Linux 的硬件变成电视或有源音箱的音视频来源（Chromecast 的替代方案）。([源代码](https://github.com/MayaPosch/NymphCast)) `BSD-3-Clause` `C++`
- [Rygel](https://gnome.pages.gitlab.gnome.org/rygel/) - UPnP AV MediaServer，可让你轻松分享音频、视频和图片。媒体播放器软件可使用 Rygel 成为可由 UPnP 或 DLNA 控制器远程控制的 MediaRenderer。([源代码](https://gitlab.gnome.org/GNOME/rygel/)) `LGPL-2.1` `C`
- [Stash](https://stashapp.cc) - 面向你成人媒体收藏的基于 Web 的媒体库整理工具与播放器，支持自动打标签和元数据抓取。([源代码](https://github.com/stashapp/stash)) `AGPL-3.0` `Docker/Go`
- [µStreamer](https://github.com/pikvm/ustreamer) - 轻量且极快的服务器，可将来自任何 V4L2 设备的 MJPEG 视频流式传输到网络。 `GPL-3.0` `C/deb`
- [üWave](https://u-wave.net/) `⚠` - 自托管协作收听平台。用户轮流播放来自 YouTube 和 SoundCloud 等多种媒体源的媒体——歌曲、演讲、游戏视频或其他任何内容。([演示](https://wlk.yt/)、[源代码](https://github.com/u-wave)) `MIT` `Nodejs`


### 媒体流 - 视频流 <a id="media-streaming---video-streaming"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[视频](https://en.wikipedia.org/wiki/Video)流工具与软件。

_相关：[视频监控](#video-surveillance)、[媒体流 - 多媒体流](#media-streaming---multimedia-streaming)、[相册](#photo-galleries)、[媒体管理](#media-management)_

- [CyTube](https://github.com/calzoneman/sync) - 为任意数量的频道同步媒体、聊天等。([演示](https://cytu.be)) `MIT` `Nodejs`
- [Invidious](https://github.com/iv-org/invidious) `⚠` - YouTube 的替代前端。([演示](https://docs.invidious.io/instances/)) `AGPL-3.0` `Docker/Crystal`
- [MediaCMS](https://mediacms.io) - 现代、功能齐全的开源视频与媒体 CMS，使用 Python/Django/React 编写，具备 REST API。([源代码](https://github.com/mediacms-io/mediacms)) `AGPL-3.0` `Python/Docker`
- [OvenMediaEngine](https://github.com/OvenMediaLabs/OvenMediaEngine) - 亚秒级延迟的流媒体服务器。([演示](https://demo.ovenplayer.com)) `AGPL-3.0` `C++/Docker`
- [Owncast](https://owncast.online/) - 去中心化的单用户直播与聊天服务器，可运行你自己的直播，风格类似大型主流平台。([源代码](https://github.com/owncast/owncast)) `MIT` `Go`
- [PeerTube](https://joinpeertube.org/en/) - 去中心化视频流平台，直接在网页浏览器中使用 P2P（BitTorrent）。([源代码](https://github.com/Chocobozzz/PeerTube)) `AGPL-3.0` `Nodejs`
- [Rapidbay](https://github.com/hauxir/rapidbay/) - 视频流服务/种子客户端，可让你在浏览器中或通过 Chromecast/AppleTV/智能电视搜索和播放来自种子的视频。 `MIT` `Python/Docker`
- [Restreamer](https://datarhei.github.io/restreamer/) - 无需流媒体服务商，即可在你的网站上访问 H.264 实时视频流。([源代码](https://github.com/datarhei/restreamer)) `Apache-2.0` `Nodejs/Docker`
- [SRS](https://ossrs.io/) - 简单、高效且实时的视频服务器，支持 RTMP、WebRTC、HLS、HTTP-FLV 和 SRT。([源代码](https://github.com/ossrs/srs)) `MIT` `Docker/C++`
- [SyncTube](https://github.com/RblSb/SyncTube) - 轻量且极易搭建的 CyTube 替代方案，可与朋友一起看视频并聊天。 `MIT` `Nodejs/Haxe`
- [Tiramisu](https://github.com/MrRobotoGit/tiramisu) - BitTorrent 引擎，带 FUSE 虚拟文件系统，可在不下载的情况下将种子实时流式传输到 Plex/Jellyfin（Real-Debrid 的替代方案）。 `GPL-2.0` `Go/Docker`
- [Tube Archivist](https://tubearchivist.com/) `⚠` - 整理、搜索并享受你的 YouTube 收藏。订阅、下载并追踪已观看内容，具备元数据索引和友好的界面。([源代码](https://github.com/tubearchivist/tubearchivist)、[客户端](https://docs.tubearchivist.com/faq/#how-do-i-import-my-videos-to-emby-plex-jellyfin-kodi)) `GPL-3.0` `Docker`
- [Tube](https://git.mills.io/prologic/tube) - 类似 YouTube（_没有审查，也没有你不需要的功能！_）的视频分享应用，用 Go 编写，还支持自动转码为 MP4 H.265 AAC、多个收藏集和 RSS 订阅。 `MIT` `Go`
- [VideoLAN Client (VLC)](https://www.videolan.org/) - 跨平台多媒体播放器客户端与服务器，支持大多数多媒体文件以及 DVD、音频 CD、VCD 和各种流媒体协议。([源代码](https://code.videolan.org/videolan/vlc)) `GPL-2.0` `C/deb`


### 杂项 <a id="miscellaneous"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

不属于其他分类的软件。

- [2FAuth](https://github.com/Bubka/2FAuth) - 管理你的双因素认证（2FA）账号并生成其安全码。([演示](https://demo.2fauth.app/)) `AGPL-3.0` `PHP/Docker`
- [Anchr](https://anchr.io) - 互联网小任务工具箱，包括书签收集、URL 缩短和（加密）图片上传。([源代码](https://github.com/muety/anchr)) `GPL-3.0` `Nodejs`
- [Anubis](https://anubis.techaro.lol/) - Web AI 防火墙工具，可保护上游资源免受抓取机器人侵扰。([源代码](https://github.com/TecharoHQ/anubis)) `MIT` `Docker/deb/Go`
- [asciinema](https://asciinema.org/) - 用于托管终端录制（asciicast）的 Web 应用。([演示](https://asciinema.org/explore)、[源代码](https://github.com/asciinema/asciinema-server)) `Apache-2.0` `Elixir/Docker`
- [Baby Buddy](https://github.com/babybuddy/babybuddy) - 帮助照护者追踪婴儿睡眠、喂食、换尿布和趴卧时间。([演示](https://github.com/babybuddy/babybuddy#-demo)) `BSD-2-Clause` `Python`
- [ClipCascade](https://github.com/Sathvik-Rao/ClipCascade) - 无需按任何按键即可在多台设备间即时同步剪贴板。适用于 Windows、macOS、Linux 和 Android，通过端到端数据加密提供无缝且安全的剪贴板共享。 `GPL-3.0` `Java/Docker`
- [Cloudlog](https://magicbug.co.uk/cloudlog/) - 在任何地方记录你的业余无线电通联。([源代码](https://github.com/magicbug/cloudlog)) `MIT` `PHP/Docker`
- [ConvertX](https://github.com/C4illin/ConvertX) - 在线文件转换器，支持上千种不同格式。 `AGPL-3.0` `Docker`
- [CUPS](https://www.cups.org/) - 通用 Unix 打印系统使用互联网打印协议（IPP）来支持打印到本地和网络打印机。([源代码](https://github.com/OpenPrinting/cups)) `GPL-2.0` `C`
- [CyberChef](https://github.com/gchq/CyberChef) - 在网页浏览器中执行各种操作，如 AES、DES 和 Blowfish 加密解密、生成十六进制转储、计算哈希等。([演示](https://gchq.github.io/CyberChef)) `Apache-2.0` `Javascript`
- [Digiboard](https://digiboard.app/) - 创建协作式白板（文档为法语）。([源代码](https://codeberg.org/ladigitale/digiboard)) `AGPL-3.0` `Nodejs`
- [Digicard](https://codeberg.org/ladigitale/digicard) - 创建简单的图形构图（文档为法语）。([演示](https://ladigitale.dev/digicard/)) `AGPL-3.0` `Nodejs`
- [Digicut](https://ladigitale.dev/digicut/) - 使用 FFMPEG.wasm 剪切音频和视频文件（文档为法语）。([源代码](https://codeberg.org/ladigitale/digicut)) `AGPL-3.0` `Nodejs`
- [Digiface](https://ladigitale.dev/digiface/) - 使用 Avataaars 库创建头像（文档为法语）。([演示](https://ladigitale.dev/digiface/)、[源代码](https://codeberg.org/ladigitale/digiface)) `AGPL-3.0` `Nodejs`
- [Digiflashcards](https://ladigitale.dev/digiflashcards/) - 用于创建抽认卡的在线应用（文档为法语）。([源代码](https://codeberg.org/ladigitale/digiflashcards)) `AGPL-3.0` `Nodejs/PHP`
- [Digimerge](https://ladigitale.dev/digimerge/) - 直接在浏览器中合成音频和视频文件（文档为法语）。([演示](https://ladigitale.dev/digimerge/)、[源代码](https://codeberg.org/ladigitale/Digimerge)) `AGPL-3.0` `Nodejs`
- [Digiquiz](https://ladigitale.dev/digiquiz/) - 用于发布用 H5P 创建的内容的在线应用（文档为法语）。([源代码](https://codeberg.org/ladigitale/digiquiz)) `AGPL-3.0` `Nodejs`
- [Digiread](https://ladigitale.dev/digiread/) `⚠` - 使用 Mozilla 的 Readability 清理在线页面和文章（文档为法语）。([源代码](https://codeberg.org/ladigitale/digiread)) `AGPL-3.0` `Nodejs/PHP`
- [Digisteps](https://ladigitale.dev/digisteps/) - 用于创建在线学习路径的简单应用（文档为法语）。([源代码](https://codeberg.org/ladigitale/digisteps)) `AGPL-3.0` `Nodejs/PHP`
- [Digitranscode](https://ladigitale.dev/digitranscode) - 直接在浏览器中转换音频文件和视频（文档为法语）。([演示](https://ladigitale.dev/digitranscode)、[源代码](https://codeberg.org/ladigitale/digitranscode)) `AGPL-3.0` `Nodejs`
- [Digiview](https://ladigitale.dev/digiview/) `⚠` - 在无干扰界面中观看 YouTube 视频（文档为法语）。([演示](https://ladigitale.dev/digiview/)、[源代码](https://codeberg.org/ladigitale/digiview)) `AGPL-3.0` `Nodejs/PHP`
- [Digiwords](https://ladigitale.dev/digiwords/) - 用于创建词云的简单在线应用（文档为法语）。([源代码](https://codeberg.org/ladigitale/digiwords)) `AGPL-3.0` `Nodejs/PHP`
- [DOCAT](https://github.com/docat-org/docat) - 托管你的文档。简单。带版本。好看。 `MIT` `Python/Docker`
- [Domain Locker](https://domain-locker.com) - 域名资产组合管理与追踪。([演示](https://demo.domain-locker.com)、[源代码](https://github.com/lissy93/domain-locker)) `MIT` `Deno/Docker`
- [DOMJudge](https://www.domjudge.org/) - 用于举办编程竞赛的系统，如 ICPC 区域赛和世界总决赛编程竞赛。([演示](https://www.domjudge.org/demo)、[源代码](https://github.com/DOMjudge/domjudge)) `GPL-2.0/BSD-3-Clause/MIT` `PHP`
- [ESMira](https://esmira.kl.ac.at) - 开展纵向研究（ESM、AA、EMA），数据采集和与参与者的沟通完全匿名。([演示](https://demo-esmira.kl.ac.at/#admin,username:demo,password:demodemodemo)、[源代码](https://github.com/KL-Psychological-Methodology/ESMira)) `AGPL-3.0` `PHP`
- [F-Droid](https://f-droid.org) - 用于维护 F-Droid 仓库系统的服务器工具。([源代码](https://gitlab.com/fdroid/fdroidserver)) `AGPL-3.0` `Python/Docker/deb`
- [Flyimg](https://flyimg.io) - 即时缩放和裁剪图片。使用 ImageMagick 通过 MozJPEG、WebP 或 PNG 获得优化后的图片，并具备高效的缓存系统。([演示](https://demo.flyimg.io)、[源代码](https://github.com/flyimg/flyimg)) `MIT` `Docker`
- [Garlic-Hub](https://garlic-signage.com/garlic-hub/) - 数字标牌设备与内容管理系统，支持 SMIL 播放列表和排期。([源代码](https://github.com/garlic-signage/garlic-hub)) `AGPL-3.0` `Docker`
- [Geeftlist](https://codeberg.org/nanawel/geeftlist) - 用于在亲友之间管理、分享和预留礼物的协作平台。`GPL-3.0` `Docker`
- [google-webfonts-helper](https://github.com/majodev/google-webfonts-helper) `⚠` - 自托管 Google Fonts 的省心方案。可获取 eot、ttf、svg、woff 和 woff2 文件以及 CSS 代码片段。([演示](https://gwfh.mranftl.com/fonts)) `MIT` `Nodejs`
- [Habitica](https://habitica.com/) - 习惯追踪应用，将你的目标当作角色扮演游戏来对待。([源代码](https://github.com/HabitRPG/habitica)) `GPL-3.0/CC-BY-SA-3.0` `Nodejs/Docker`
- [HortusFox](https://hortusfox.github.io) - 面向植物爱好者的协作式植物管理与追踪系统。([源代码](https://github.com/danielbrendel/hortusfox-web)) `MIT` `PHP/Docker`
- [ImgCompress](https://imgcompress.karimzouine.com) - 完全在 Docker 中运行的图像处理工具。可压缩、转换、调整尺寸、批量处理图像，并使用本地 AI 去除背景，无需依赖云服务。([源代码](https://github.com/karimz1/imgcompress)) `GPL-3.0` `Docker`
- [Infisical Community Edition](https://infisical.com/) - 用于密钥、证书和特权访问管理的平台。([源代码](https://github.com/Infisical/infisical)) `MIT` `Docker/K8S/deb`
- [iSponsorBlockTV](https://github.com/dmunozv04/iSponsorBlockTV) `⚠` - 屏蔽并跳过赞助商片段，同时静音并跳过 YouTube 广告。`GPL-3.0` `Docker/Python`
- [IT-Tools by sharevb](https://github.com/sharevb/it-tools) - 面向开发者的实用在线工具集（[it-tools](https://github.com/CorentinTh/it-tools) 的分支）。([演示](https://sharevb-it-tools.vercel.app/)) `GPL-3.0` `Docker`
- [Jelu](https://bayang.github.io/jelu-web) - 已读与想读书籍清单追踪器。([源代码](https://github.com/bayang/jelu)) `MIT` `Java/Docker`
- [jetlog](https://github.com/pbogre/jetlog) - 个人航班追踪与查看工具。`GPL-2.0` `Docker`
- [Kasm Workspaces](https://kasmweb.com/) - 向终端用户流式传输容器化应用和桌面。示例包括浏览器中的 Ubuntu，或 Chrome、OpenOffice、Gimp、Filezilla 等单个应用。([演示](https://www.kasmweb.com/#demo)、[源代码](https://github.com/kasmtech)) `GPL-3.0` `Docker`
- [Koillection](https://koillection.github.io/) - Koillection 是一项允许用户管理任何类型收藏的服务。([源代码](https://github.com/benjaminjonard/koillection)) `MIT` `Docker/PHP`
- [LanguageTool](https://languagetool.org/) - 校对 20 多种语言。它能发现许多简单拼写检查器无法检测到的错误。([源代码](https://github.com/languagetool-org/languagetool)、[客户端](https://languagetool.org/insights/post/product-windows-app/)) `LGPL-2.1` `Java/Docker`
- [Libre Translate](https://libretranslate.com/) - 机器翻译 API。([源代码](https://github.com/LibreTranslate/LibreTranslate)) `AGPL-3.0` `Docker/Python`
- [LubeLogger](https://lubelogger.com) - 基于 Web 的车辆保养和油耗追踪器。([演示](https://github.com/hargata/lubelog?tab=readme-ov-file#demo)、[源代码](https://github.com/hargata/lubelog)) `MIT` `Docker/K8S/C#`
- [Mirumoji](https://svdc1.github.io/mirumoji/docs) - 日语沉浸式学习工具包，提供可点击的分词字幕、词典查询和转写生成。([演示](https://svdc1.github.io/mirumoji/)、[源代码](https://github.com/svdC1/mirumoji)) `MIT` `Docker/Python`
- [mosparo](https://mosparo.io/) - 现代垃圾信息防护工具。它用简单易用的垃圾信息防护方案替代其他验证码方法。([源代码](https://github.com/mosparo/mosparo)) `MIT` `PHP`
- [Movary](https://github.com/leepeuker/movary) `⚠` - 用于追踪和评价已观看电影的 Web 应用。([演示](https://github.com/leepeuker/movary?tab=readme-ov-file#demo)) `MIT` `Docker/PHP`
- [Neko](https://neko.m1k1o.net) - 在 Docker 中运行并使用 WebRTC 的虚拟浏览器。([源代码](https://github.com/m1k1o/neko)) `Apache-2.0` `Docker/Go`
- [OmniTools](https://omnitools.app/) - 面向日常任务的强大在线工具集（编码、处理图像/视频、PDF 或数据计算等）。([源代码](https://github.com/iib0011/omni-tools)) `MIT` `Docker`
- [Open-Meteo](https://open-meteo.com/) - 天气 API，提供来自所有主要国家气象机构的开放数据预报、历史数据和气候数据。([演示](https://open-meteo.com/en/docs)、[源代码](https://github.com/open-meteo/open-meteo)) `AGPL-3.0` `Docker`
- [OpenReader](https://docs.openreader.richardr.dev/) - 将 EPUB、PDF、DOCX、MD 和 TXT 文件文本转为语音的文档阅读器。可实时以高质量 TTS 朗读文档，或提取有声书。([源代码](https://github.com/richardr1126/openreader)) `MIT` `Docker`
- [OpenZiti](https://openziti.io/) - 功能齐全的零信任全网格覆盖网络。开箱即支持 2FA，并提供适用于所有主流桌面/移动操作系统的客户端。([源代码](https://github.com/openziti/ziti)) `Apache-2.0` `Go`
- [Operational.co](https://operational.co) - 以实时时间线接收来自你的产品的告警。([演示](https://app.operational.co/?signinas=kevin)、[源代码](https://github.com/operational-co/operational.co)) `AGPL-3.0` `Nodejs/Docker`
- [penpot](https://penpot.app/) - 面向跨领域团队的基于 Web 的设计与原型平台。([源代码](https://github.com/penpot/penpot)) `MPL-2.0` `Docker`
- [POMjs](https://password.oppetmoln.se/) - 随机密码生成器。([源代码](https://github.com/joho1968/POMjs)) `GPL-2.0` `Javascript`
- [Pønskelisten](https://github.com/aunefyren/poenskelisten) - 分享心愿清单并协作挑选礼物。`GPL-3.0` `Docker/Go`
- [re:Director](https://re-director.github.io/) - 简易域名重定向管理工具。([源代码](https://github.com/re-Director/re-director)) `Apache-2.0` `Java/Docker`
- [Reactive Resume](https://rxresu.me/) - 独一无二的简历生成器，注重保护你的隐私。完全安全、可自定义且便于携带。([演示](https://rxresu.me/)、[源代码](https://github.com/reactive-resume/reactive-resume)) `MIT` `Docker/Nodejs`
- [revealjs](https://revealjs.com) - 使用 HTML 轻松创建精美演示文稿的框架。([演示](https://revealjs.com/)、[源代码](https://github.com/hakimel/reveal.js)) `MIT` `Javascript`
- [Revive Adserver](https://www.revive-adserver.com/) - 广告投放系统。曾名为 OpenX Adserver 和 phpAdsNew。([源代码](https://github.com/revive-adserver/revive-adserver)) `GPL-2.0` `PHP`
- [SANE Network Scanning](http://sane-project.org/) - 允许远程客户端访问本地主机上的图像采集设备（扫描仪）。([源代码](http://www.sane-project.org/cvs.html)) `GPL-2.0` `C`
- [string.is](https://string.is/) - 面向开发者的在线字符串工具箱。([源代码](https://github.com/recurser/string-is)) `AGPL-3.0` `Nodejs`
- [Teleport](https://goteleport.com/) - 用于 SSH、Kubernetes、Web 应用和数据库的证书颁发机构与访问平面。([源代码](https://github.com/gravitational/teleport)) `Apache-2.0` `Go/Docker/K8S`
- [TeslaMate](https://github.com/teslamate-org/teslamate) - 功能强大的特斯拉车辆数据记录器。`MIT` `Elixir/Docker`
- [Transmute](https://transmute.sh) - 面向图像、视频、音频、json、excel 等的文件转换器。支持 2000 多种转换！([源代码](https://github.com/transmute-app/transmute)) `MIT` `Docker`
- [URL-to-PNG](https://github.com/jasonraimondi/url-to-png) - URL 转 PNG 工具，使用 Playwright 并行渲染截图，并通过 Local、S3 或 CouchDB 进行存储缓存。`MIT` `Nodejs/Docker`
- [Usertour](https://www.usertour.io/) - 用户引导平台，让你能在几分钟内轻松创建应用内产品导览、检查清单和问卷。([源代码](https://github.com/usertour/usertour/)) `AGPL-3.0` `Docker`
- [Warracker](https://warracker.com) - 保修追踪器，可监控到期日期、上传收据/文件，并在保修到期前收到提醒。([源代码](https://github.com/sassanix/Warracker)) `AGPL-3.0` `Docker`
- [Wavelog](https://www.wavelog.org) - 面向业余无线电爱好者的基于 Web 的日志软件。在浏览器中提供增强的 QSO 日志记录、统计和地图。([演示](https://demo.wavelog.org)、[源代码](https://github.com/wavelog/wavelog)) `MIT` `PHP/Docker`
- [WeeWX](https://weewx.com/) - 用于气象站的开源软件。([演示](https://weewx.com/showcase.html)、[源代码](https://github.com/weewx/weewx)) `GPL-3.0` `Python/deb`
- [WeTTY](https://butlerx.github.io/wetty/#/) - 通过 http/https 在浏览器中使用终端。([源代码](https://github.com/butlerx/wetty)) `MIT` `Docker/Nodejs`
- [Wishlist](https://github.com/cmintey/wishlist) - 可与亲友分享的心愿清单应用。`MIT` `Docker/K8S`
- [Yamtrack](https://github.com/FuzzyGrim/Yamtrack) `⚠` - 用于电影、电视剧、动漫、漫画、电子游戏和书籍的媒体追踪器。([演示](https://github.com/FuzzyGrim/Yamtrack?tab=readme-ov-file#demo)) `AGPL-3.0` `Docker/Python`
- [Zero-TOTP](https://zero-totp.com) - 基于零知识加密的完整、可靠、安全的零信任 Web 应用，用于存储你的 TOTP 验证码。([源代码](https://github.com/SeaweedbrainCY/zero-totp)) `GPL-3.0` `Docker`


### 财务、预算与管理 <a id="money-budgeting--management"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[资金管理](https://en.wikipedia.org/wiki/Money_management)与预算软件。

_相关：[库存管理](#inventory-management)、[资源规划](#resource-planning)_

- [Actual](https://actualbudget.org) - 基于零和预算的本地优先个人理财工具，支持跨设备同步、自定义规则、手动导入交易（来自 QIF、OFX 和 QFX 文件），并可选与多家银行自动同步。([源代码](https://github.com/actualbudget/actual)) `MIT` `Nodejs/Docker`
- [Bigcapital](https://bigcapital.app/) - 面向中小企业的财务会计与库存管理软件。([源代码](https://github.com/bigcapitalhq/bigcapital)) `AGPL-3.0` `Docker`
- [Bitcart](https://bitcart.ai) - 加密货币支付处理与开发平台。([演示](https://admin.bitcart.ai)、[源代码](https://github.com/bitcart/bitcart)) `MIT` `Docker/Python/Nodejs`
- [BTCPay Server](https://btcpayserver.org/) - 比特币及其他加密货币支付处理器。([演示](https://mainnet.demo.btcpayserver.org/)、[源代码](https://github.com/btcpayserver/btcpayserver)) `MIT` `C#`
- [Budget Board](https://budgetboard.net/) - 用于追踪每月开支并努力实现财务目标的简易应用。([源代码](https://github.com/teelur/budget-board)) `GPL-3.0` `Docker`
- [DePay](https://depay.com) - 以点对点方式直接向你的钱包接受 Web3 支付。([演示](https://depay.com/products/payments)、[源代码](https://github.com/depayfi/widgets)) `MIT` `Nodejs`
- [Econumo](https://econumo.com) - 用于管理个人和家庭财务的预算应用，支持多种货币、共同账户和预算。([演示](https://demo.econumo.com)、[源代码](https://github.com/econumo/econumo)) `MIT` `Docker`
- [Expensave](https://github.com/algirdasc/expensave) - 用于个人和家庭预算管理的开支追踪器。在共享日历上追踪开支、导入银行对账单，并通过报表监控财务状况。`GPL-3.0` `Docker`
- [ExpenseOwl](https://github.com/tanq16/expenseowl) - 极其简单且界面美观的开支追踪器。`MIT` `Go/Docker/K8S`
- [ezbookkeeping](https://ezbookkeeping.mayswind.net/) - 自托管的轻量级个人记账应用。([演示](https://ezbookkeeping-demo.mayswind.net/)、[源代码](https://github.com/mayswind/ezbookkeeping)) `MIT` `Go/Docker`
- [Family Accounting Tool](https://github.com/nymanjens/facto) - 面向共同承担部分开支的伴侣的基于 Web 的财务管理工作。`Apache-2.0` `Scala`
- [Fava](https://beancount.github.io/fava/) - Beancount 的 Web 前端，Beancount 是一个基于文本的复式记账系统。([演示](https://fava.pythonanywhere.com/example-with-budgets/income_statement/)、[源代码](https://github.com/beancount/fava)) `MIT` `Python`
- [Firefly III](https://firefly-iii.org/) - Firefly III 是一款现代财务管理工具。它帮助你追踪资金并进行预算预测。它支持信用卡，拥有高级规则引擎，并可从多家银行导入数据。([演示](https://demo.firefly-iii.org/)、[源代码](https://github.com/firefly-iii/firefly-iii)) `AGPL-3.0` `PHP/Docker`
- [FOSSBilling](https://fossbilling.org/) - 主机托管与计费自动化。可与 WHM、CWP、cPanel 和 HestiaCP 集成。提供完整 API 且易于扩展。([演示](https://fossbilling.org/demo)、[源代码](https://github.com/FOSSBilling/FOSSBilling)) `Apache-2.0` `PHP/Docker`
- [Galette](https://galette.eu/) - 面向非营利组织的会员管理 Web 应用。([源代码](https://github.com/galette/galette)) `GPL-3.0` `PHP`
- [Ghostfolio](https://ghostfol.io/) - 用于追踪股票、ETF 和加密货币的财富管理软件。([源代码](https://github.com/ghostfolio/ghostfolio)) `AGPL-3.0` `Docker/Nodejs`
- [GRR](https://grr.devome.com/?lang=en) - 面向中小企业的资产管理与预约。([源代码](https://github.com/JeromeDevome/GRR)) `GPL-2.0` `PHP`
- [HyperSwitch](https://hyperswitch.io/) `⚠` - 让支付更快速、可靠且低成本的支付交换机。通过单次 API 集成即可连接多个支付处理商并轻松路由流量。([源代码](https://github.com/juspay/hyperswitch)) `Apache-2.0` `Docker/Rust`
- [IHateMoney](https://ihatemoney.org/) - 轻松管理你们的共同开支。([演示](https://ihatemoney.org/demo/)、[源代码](https://github.com/spiral-project/ihatemoney)) `BSD-3-Clause` `Docker/Python`
- [InvoicePlane](https://www.invoiceplane.com/) - 为你的小型企业管理报价单、发票、付款和客户。([源代码](https://github.com/InvoicePlane/InvoicePlane)) `MIT` `PHP`
- [InvoiceShelf](https://invoiceshelf.com/) - 追踪开支和付款，并创建专业的发票和估价单（Crater 的分支）。([源代码](https://github.com/InvoiceShelf/InvoiceShelf)) `AGPL-3.0` `PHP/Docker`
- [Kill Bill](https://killbill.io/) - 订阅计费与支付平台。可访问实时分析和财务报告。([源代码](https://github.com/killbill/killbill)) `Apache-2.0` `Java/Docker`
- [Kresus](https://kresus.org/) - 个人财务管理器。([演示](https://kresus.org/en/demo.html)、[源代码](https://github.com/kresusapp/kresus)) `AGPL-3.0` `Nodejs/Docker`
- [Lago](https://www.getlago.com/) - 计量与基于用量的计费。([源代码](https://github.com/getlago/lago)) `AGPL-3.0` `Docker`
- [Mybucks.online](https://mybucks.online) - 安全、基于浏览器的纯密码自托管加密货币钱包。([演示](https://app.mybucks.online)、[源代码](https://github.com/mybucks-online/app)) `MIT` `Nodejs`
- [MyFin Budget](https://myfinbudget.com) - 个人财务平台（Web + REST API + Android），帮助你制定预算、追踪收入/支出并预测财务未来。([演示](https://github.com/afaneca/myfin?tab=readme-ov-file#demo-account---try-it-for-yourself)、[源代码](https://github.com/afaneca/myfin)、[客户端](https://github.com/afaneca/myfin-api)) `GPL-3.0` `Nodejs/Docker`
- [OctoBot](https://www.octobot.cloud/) - 加密货币交易机器人。([源代码](https://github.com/Drakkar-Software/OctoBot)) `GPL-3.0` `Python/Docker`
- [Ocular](https://simonwep.github.io/ocular/) - 简洁明了的预算应用，可跨月和跨年追踪你的预算。([演示](https://simonwep.github.io/ocular/demo/#demo)、[源代码](https://github.com/simonwep/ocular)) `MIT` `Docker`
- [OpenBudgeteer](https://github.com/TheAxelander/OpenBudgeteer) - 基于桶式预算原则的预算应用。`AGPL-3.0` `Docker/C#`
- [Receipt Wrangler](https://receiptwrangler.io) `⚠` - 由 AI 驱动的易用收据管理器。让用户轻松快速地创建收据、分类等。([演示](https://demo.receiptwrangler.io)、[源代码](https://github.com/Receipt-Wrangler/receipt-wrangler)) `AGPL-3.0` `Docker`
- [REI3](https://rei3.de/home_en/) - 在你的企业内管理任务、时间、资产等。([演示](https://rei3.de/demo_en/)、[源代码](https://github.com/r3-team/r3)) `MIT` `Go`
- [SHKeeper](https://shkeeper.io/) - 加密货币支付处理器，独特地结合了网关与商户功能，让你无需手续费和中间商即可接受多种加密货币支付。([演示](https://github.com/vsys-host/shkeeper.io?tab=readme-ov-file#11-demo)、[源代码](https://github.com/vsys-host/shkeeper.io)) `GPL-3.0` `Python`
- [SolidInvoice](https://solidinvoice.co) - 开源的发票和报价应用。([源代码](https://github.com/SolidInvoice/SolidInvoice)) `MIT` `PHP`
- [Sure](https://github.com/we-promise/sure) - 面向所有人的个人财务应用（Maybe 的分支）。`AGPL-3.0` `Docker`
- [VoucherVault](https://github.com/l4rm4nd/VoucherVault) - 数字化存储和管理代金券、优惠券、积分卡和礼品卡。支持到期通知、交易历史、文件上传和 OIDC 单点登录。`GPL-3.0` `Docker`
- [Wallos](https://wallosapp.com) - 轻量级个人订阅追踪器，带统计数据和可选通知。([演示](https://github.com/ellite/wallos?tab=readme-ov-file#demo)、[源代码](https://github.com/ellite/wallos)) `GPL-3.0` `PHP/Docker`
- [WYGIWYH](https://github.com/eitchtee/WYGIWYH) - 简单而强大的财务追踪器。([演示](https://wygiwyh-demo.herculino.com/)) `AGPL-3.0` `Docker/Python`
- [YAFFA](https://www.yaffa.cc) - 个人财务 Web 应用，可用于追踪资金、支出、预算和投资。它也有助于长期财务规划。([演示](https://sandbox.yaffa.cc)、[源代码](https://github.com/kantorge/yaffa)) `MIT` `PHP`


### 监控与状态页面 <a id="monitoring--status-pages"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

用于[监控](https://en.wikipedia.org/wiki/Monitoring#Computing)系统、网络、应用和网站的软件。

**请访问 [awesome-sysadmin/Monitoring](https://github.com/awesome-foss/awesome-sysadmin#monitoring--status-pages)、[awesome-sysadmin/Metrics and Metric Collection](https://github.com/awesome-foss/awesome-sysadmin#metrics--metric-collection)**

_相关：[个人仪表盘](#personal-dashboards)_



### 网络工具 <a id="network-utilities"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

网络工具是帮助管理、监控和排查计算机网络的工具与软件。

_另见：[awesome-sysadmin/Monitoring](https://github.com/awesome-foss/awesome-sysadmin#monitoring)_

- [beelzebub](https://beelzebub-honeypot.com/) `⚠` - 蜜罐框架，旨在提供高度安全的环境，用于检测和分析网络攻击。([源代码](https://github.com/beelzebub-labs/beelzebub)) `MIT` `Docker/K8S/Go`
- [Canary Tokens](https://canarytokens.org) - 生成轻量级、可嵌入的蜜罐触发器（称为金丝雀令牌），用于检测未经授权的访问。([源代码](https://github.com/thinkst/opencanary)) `BSD-3-Clause` `Docker/Python`
- [MyIP](https://ipcheck.ing) `⚠` - 一站式 IP 工具箱。轻松查看你的 IP、IP 地理位置、检测 DNS 泄漏、检查 WebRTC 连接、速度测试、ping 测试、MTR 测试、检查网站可用性等。([演示](https://ipcheck.ing)、[源代码](https://github.com/jason5ng32/MyIP)) `MIT` `Nodejs/Docker`
- [MySpeed](https://myspeed.dev/) - 速度测试分析软件，可显示长达 30 天的网速。([源代码](https://github.com/gnmyt/myspeed)) `MIT` `Docker/Nodejs`
- [NetAlertX](https://netalertx.com/) - 网络入侵与存在检测器。扫描连接到你的网络的设备，并在发现新的未知设备时发出告警。([源代码](https://github.com/netalertx/NetAlertX)) `GPL-3.0` `Docker`
- [PlugNPiN](https://deepspace2.github.io/PlugNPiN) - 自动抓取带有特定标签的容器，并在 Pi-Hole/AdGuard Home 中创建本地 DNS/CNAME 记录，在 Nginx Proxy Manager 中创建代理主机。([源代码](https://github.com/deepspace2/plugnpin)) `GPL-3.0` `Docker`
- [Speed Test by OpenSpeedTest™](https://openspeedtest.com/) - HTML5 网络性能评估工具。([源代码](https://github.com/openspeedtest/Speed-Test)) `MIT` `Docker`
- [Speedtest Tracker](https://docs.speedtest-tracker.dev/) - 监控你的互联网连接的性能和正常运行时间。([源代码](https://github.com/alexjustesen/speedtest-tracker)) `MIT` `Docker/K8S`
- [Upsnap](https://github.com/seriousm4x/UpSnap) - 简单的局域网唤醒（WOL）仪表盘应用。唤醒你网络中的设备并查看当前状态。`MIT` `Go/Docker`
- [Wakupator](https://github.com/Gibus21250/Wakupator) - 基于网络流量的局域网唤醒机器管理器。`MIT` `C`
- [whois](https://github.com/KincaidYang/whois) - 面向域名、IP 地址、CIDR 前缀和 ASN 的 WHOIS/RDAP 查询 API，提供统一的 JSON 输出、缓存、API 密钥认证、批量查询以及面向 AI 助手的 MCP 支持。([演示](https://whois.ddnsip.cn/example.com)) `MIT` `Go/Docker`


### 笔记与编辑器 <a id="note-taking--editors"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[笔记](https://en.wikipedia.org/wiki/Note-taking)编辑器。

_相关：[Wiki](#wikis)_

- [Blinko](https://blinko.space/) - 带 AI 功能的个人笔记工具。([源代码](https://github.com/blinkospace/blinko)) `AGPL-3.0` `Docker`
- [DailyTxT](https://github.com/PhiTux/DailyTxT) - 加密日记 Web 应用，用于保存你每天的个人回忆。包含搜索功能和加密文件上传。([演示](https://dailytxt.phitux.de)) `MIT` `Docker`
- [Docs](https://docs.numerique.gouv.fr/) - 可扩展的协作式笔记、wiki 和文档平台。([源代码](https://github.com/suitenumerique/docs)) `MIT` `K8S`
- [draw.io](https://draw.io) - 用于制作流程图、过程图、组织结构图、UML、ER 图和网络图的绘图软件。([源代码](https://github.com/jgraph/drawio)) `Apache-2.0` `Javascript/Docker`
- [flatnotes](https://github.com/dullage/flatnotes) - 无数据库的笔记 Web 应用，使用扁平化的 markdown 文件文件夹进行存储。([演示](https://demo.flatnotes.io)) `MIT` `Docker`
- [HedgeDoc](https://hedgedoc.org/) - 跨平台的实时协作 markdown 笔记，曾名为 CodiMD 和 HackMD CE。([演示](https://demo.hedgedoc.org/)、[源代码](https://github.com/hedgedoc/hedgedoc)) `AGPL-3.0` `Docker/Nodejs`
- [Joplin](https://joplinapp.org/) - 支持 markdown 编辑器和加密的笔记应用，适用于移动和桌面平台。客户端运行并通过自托管的 Nextcloud 实例或类似服务同步（Evernote 的替代品）。([源代码](https://github.com/laurent22/joplin)) `MIT` `Nodejs`
- [Jotty](https://jotty.page) - 轻量却强大的个人文件式笔记和清单管理替代方案。([源代码](https://github.com/fccview/jotty)) `AGPL-3.0` `Docker`
- [Livebook](https://livebook.dev) - 基于 Markdown 的实时协作笔记本应用，支持运行 Elixir 代码片段、TeX 和 Mermaid 图表。可通过 Docker 或 Elixir 轻松部署。([源代码](https://github.com/livebook-dev/livebook)) `Apache-2.0` `Elixir/Docker`
- [Many Notes](https://github.com/brufdev/many-notes) - 为简洁而设计的 Markdown 笔记 Web 应用。`MIT` `Docker`
- [Memos](https://usememos.com/) - 使用 SQLite 数据库文件的知识库。([演示](https://demo.usememos.com/explore)、[源代码](https://github.com/usememos/memos)) `MIT` `Docker/Go`
- [Neverkin](https://neverkin.com/) - 协作写作、世界构建和 D&D 跑团规划应用。用于整理你的笔记和故事的工具。([演示](https://app.neverkin.com/guest-login)、[源代码](https://github.com/Tenebrie/neverkin/)) `GPL-3.0` `Nodejs/Docker`
- [Note Mark](https://notemark.docs.enchantedcode.co.uk/) - 极简的基于 Web 的 Markdown 笔记应用。([源代码](https://github.com/enchant97/note-mark)) `AGPL-3.0` `Docker`
- [NoteDiscovery](https://www.notediscovery.com/) - 采用纯文件存储的 Markdown 笔记应用，具有图谱视图和 MCP 集成（Obsidian、Notion 的替代品）。([演示](https://gamosoft-notediscovery-demo.hf.space)、[源代码](https://github.com/gamosoft/NoteDiscovery)) `MIT` `Docker/Python`
- [Overleaf](https://www.overleaf.com/) - 基于 Web 的协作式 LaTeX 编辑器。([源代码](https://github.com/overleaf/overleaf)) `AGPL-3.0` `Ruby`
- [Plainpad](https://plainpad.org) - 面向云端的现代笔记应用，充分利用渐进式 Web 应用技术的优势。([演示](https://demo.plainpad.org)、[源代码](https://github.com/alextselegidis/plainpad)) `GPL-3.0` `PHP`
- [plumio](https://plumio.app/) - 支持实时预览、文档加密、多用户支持、多组织能力等的 Markdown 笔记应用。([演示](https://demo.plumio.app/homepage)、[源代码](https://github.com/albertasaftei/plumio)) `AGPL-3.0` `Nodejs/Docker`
- [SilverBullet](https://silverbullet.md/) - 为具有黑客思维的人优化的笔记应用。([演示](https://play.silverbullet.md/)、[源代码](https://github.com/silverbulletmd/silverbullet)、[客户端](https://silverbullet.md/Libraries)) `MIT` `Docker/Deno`
- [Standard Notes](https://docs.standardnotes.com/self-hosting/getting-started) - 简单且私密的笔记应用。在保护隐私的同时完成更多事情。这就是 Standard Notes。([演示](https://app.standardnotes.com/)、[源代码](https://github.com/standardnotes/app)) `GPL-3.0` `Ruby`
- [TriliumNext Notes](https://github.com/TriliumNext/Trilium) - 跨平台的分层笔记应用，专注于构建大型个人知识库（Trilium Notes 的分支）。`AGPL-3.0` `Nodejs/Docker/K8S`
- [Turtl](https://turtl.it/) - 完全私密的个人数据库和笔记应用。([源代码](https://github.com/turtl)) `GPL-3.0` `CommonLisp`
- [Writing](https://josephernest.github.io/writing/) - 浏览器中的轻量级免打扰文本编辑器（支持 Markdown 和 LaTeX）。书写时无延迟。([源代码](https://github.com/josephernest/writing)) `MIT` `Javascript`


### 办公套件 <a id="office-suites"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[办公套件](https://en.wikipedia.org/wiki/List_of_office_suites)是一组生产力软件的集合，通常至少包含文字处理、电子表格和演示程序。

- [Collabora Online Development Edition](https://www.collaboraoffice.com/code) - Collabora Online Development Edition（CODE）是一款功能强大的基于 LibreOffice 的在线办公套件，支持所有主流文档、电子表格和演示文稿文件格式，可集成到你自己的基础设施中。([源代码](https://gerrit.collaboraoffice.com/plugins/gitiles/online)) `MPL-2.0` `C++`
- [CryptPad](https://cryptpad.org) - 为支持协作而构建的协作套件，实时同步文档更改。([源代码](https://github.com/cryptpad/cryptpad)) `AGPL-3.0` `Nodejs/Docker`
- [Digislides](https://ladigitale.dev/digislides/) - 快速轻松地创建多媒体演示文稿。（文档为法语）。([演示](https://ladigitale.dev/digislides/)、[源代码](https://codeberg.org/ladigitale/Digislides)) `AGPL-3.0` `Nodejs/PHP`
- [Etherpad](https://etherpad.org/) - 高度可定制的在线编辑器，提供实时协作编辑功能。([演示](https://demo.sandstorm.io/appdemo/h37dm17aa89yrd8zuqpdn36p6zntumtv08fjpu8a8zrte7q1cn60)、[源代码](https://github.com/ether/etherpad)) `Apache-2.0` `Nodejs/Docker`
- [Grist](https://getgrist.com/) - 新一代电子表格，具有关系型结构、基于公式的访问控制和便携自包含的格式（Airtable 的替代品）。([演示](https://docs.getgrist.com)、[源代码](https://github.com/gristlabs/grist-core)) `Apache-2.0` `Nodejs/Python/Docker`
- [ONLYOFFICE](https://helpcenter.onlyoffice.com/faq/server-opensource.aspx) - 办公套件，让你能在一处管理文档、项目、团队和客户关系。([源代码](https://github.com/ONLYOFFICE/DocumentServer)) `AGPL-3.0` `Nodejs/Docker`


### 密码管理器 <a id="password-managers"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[密码管理器](https://en.wikipedia.org/wiki/Password_manager)允许用户存储、生成和管理本地应用及在线服务的密码。

- [AliasVault](https://www.aliasvault.net) - 端到端加密的密码管理器，内置电子邮件别名生成器和服务器。([源代码](https://github.com/aliasvault/aliasvault)) `MIT` `Docker`
- [Bitwarden](https://bitwarden.com/) `⚠` - 密码管理器，带 Web 应用、浏览器扩展和移动应用。([源代码](https://github.com/bitwarden/server)) `AGPL-3.0` `Docker/C#`
- [Passbolt](https://www.passbolt.com/) - 协作式密码管理器。([源代码](https://github.com/passbolt/passbolt_api)) `AGPL-3.0` `PHP/deb/K8S/Docker`
- [PassIt](https://passit.io/) - 简单的密码管理工具，支持按组和用户共享，但没有管理界面。([演示](https://app.passit.io/)、[源代码](https://gitlab.com/passit)) `AGPL-3.0` `Docker/Python`
- [Psono](https://psono.com/) - 面向企业的密码管理器。([演示](https://www.psono.pw)、[源代码](https://gitlab.com/esaqa/psono/psono-fileserver)) `Apache-2.0` `Python`
- [Teampass](https://teampass.net/) - 专用于协作式管理密码的密码管理器。使用一个对称密钥加密所有共享/团队密码，并在服务端存储在文件和数据库中。可运行于任何 Apache、MySQL 和 PHP 服务器。([源代码](https://github.com/nilsteampassnet/TeamPass)) `GPL-3.0` `PHP`
- [Vaultwarden](https://github.com/dani-garcia/vaultwarden) - 用 Rust 编写的轻量级 Bitwarden 服务端 API 实现。`GPL-3.0` `Rust/Docker`


### 粘贴板 <a id="pastebins"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[粘贴板](https://en.wikipedia.org/wiki/Pastebin)是一种用于分享和存储代码与文本的在线内容托管服务。

- [1time](https://1time.io) - 零知识的一次性密钥分享。为密码、API 密钥或文件创建一次性链接。在浏览器中客户端加密，明文永不触达服务器，在允许的查看次数（默认为一次）后自毁。([演示](https://1time.io)、[源代码](https://github.com/shingrus/1time.io)) `MIT` `Docker`
- [BinPastes](https://github.com/querwurzel/BinPastes) - 极简粘贴板，支持客户端加密、全文搜索、一次性消息。适合寻求简单粘贴板部署的一人或少数用户。`Apache-2.0` `Java`
- [ByteStash](https://github.com/jordan-dalby/ByteStash) - 带简洁 Web 界面的粘贴板与文件存储服务。支持语法高亮、可选的用户认证和公开分享。([演示](https://github.com/jordan-dalby/ByteStash?tab=readme-ov-file#demo)) `GPL-3.0` `Docker`
- [Chiyogami](https://github.com/rhee876527/chiyogami) - 带 API、客户端加密、用户账户、语法高亮、markdown 渲染等的粘贴板。([演示](https://chiyogami.myaddr.dev/)) `BSD-3-Clause` `Docker`
- [dpaste](https://dpaste.org/) - 简单的粘贴板，提供多种文本和代码选项，生成易于记忆的短链接。([源代码](https://github.com/DarrenOfficial/dpaste)) `MIT` `Docker/Python`
- [Hemmelig](https://hemmelig.app) - 跨组织或以私人身份分享加密密钥。([源代码](https://github.com/HemmeligOrg/Hemmelig.app)) `MIT` `Docker/Nodejs`
- [lesma](https://lesma.eu) - 对浏览器和命令行都友好的简易粘贴应用。([演示](https://lesma.eu)、[源代码](https://gitlab.com/ogarcia/lesma)) `GPL-3.0` `Rust/Docker`
- [Local Content Share](https://github.com/Tanq16/local-content-share) - 在局域网内存储和分享文本片段和文件。`MIT` `Docker/Go`
- [not-th.re](https://not-th.re) - 简单的粘贴分享平台，具有客户端加密，配备基于浏览器的 monaco 代码编辑器。([演示](https://not-th.re)、[源代码](https://github.com/not-three/main)) `AGPL-3.0` `Nodejs/Docker`
- [Opengist](https://opengist.io) - 由 Git 驱动的粘贴板。([演示](https://demo.opengist.io)、[源代码](https://github.com/thomiceli/opengist)) `AGPL-3.0` `Docker/Go/Nodejs`
- [paaster](https://paaster.io) - 端到端加密的粘贴板，以简洁为目标构建。([源代码](https://github.com/WardPearce/paaster)) `AGPL-3.0` `Docker`
- [pacebin](https://git.crueter.xyz/crueter/pacebin) - 超极简粘贴板和文件上传服务，专注于小巧的可执行文件体积、可移植性和易于配置。([演示](https://paste.crueter.xyz)) `AGPL-3.0` `C`
- [Password Pusher](https://pwpush.com) - 极其简单的应用，用于在网络上安全地传递密码（或文本）。密码在达到一定查看次数和/或经过一定时间后自动过期。([源代码](https://github.com/pglombardo/PasswordPusher)) `Apache-2.0` `Docker/K8S/Ruby`
- [Pastefy](https://pastefy.app/) - 美观、简单且易于部署的粘贴板，可选客户端加密、多标签粘贴、API、高亮编辑器等。([源代码](https://github.com/interaapps/pastefy)、[客户端](https://github.com/topics/pastefy-addon)) `MIT` `Docker/K8S/Java`
- [PrivateBin](https://privatebin.info/) - 极简的粘贴板/讨论板，服务器对托管数据零知识。([演示](https://privatebin.net/)、[源代码](https://github.com/PrivateBin/PrivateBin)) `Zlib` `PHP`
- [rustypaste](https://github.com/orhun/rustypaste) - 极简的文件上传/粘贴板服务。`MIT` `Rust`
- [Snipo](https://github.com/MohamedElashri/snipo) - 轻量级自托管代码片段管理器，可通过文件夹、标签、API 和 GitHub Gist 同步来保存和整理代码与文本片段。([演示](https://snipo.melashri.dev/)) `AGPL-3.0` `Go/Docker`
- [SnyPy](https://snypy.com) - 开源本地部署的代码片段管理器。([演示](https://app.snypy.com)、[源代码](https://github.com/snypy)) `MIT` `Docker`
- [Sup3rS3cretMes5age](https://github.com/algolia/sup3rS3cretMes5age) - 极其简单（部署和使用都很简单）的密文消息服务，使用 Hashicorp Vault 作为密钥存储。`MIT` `Go`
- [Wastebin](https://github.com/matze/wastebin) - 轻量、极简且快速的粘贴板，使用 SQLite 后端。([演示](https://bin.bloerg.net)) `MIT` `Rust/Docker`
- [Yopass](https://github.com/jhaals/yopass) - 安全地分享密钥、密码和文件。([演示](https://yopass.se/)) `Apache-2.0` `Go/Docker`


### 个人仪表盘 <a id="personal-dashboards"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

用于访问信息和应用的仪表盘。

_相关：[监控与状态页面](#monitoring--status-pages)、[书签与链接分享](#bookmarks-and-link-sharing)_

- [Compass](https://adinhodovic.github.io/compass/) - 服务、仪表盘和文档的落地页，可从 Docker、Kubernetes 和 Tailscale 等来源自动发现。([源代码](https://github.com/adinhodovic/compass)) `Apache-2.0` `Go/Docker/K8S`
- [Dashy](https://dashy.to/) - 功能丰富的家用实验室主页，具有简单的 YAML 配置。([演示](https://demo.dashy.to/)、[源代码](https://github.com/lissy93/dashy)) `MIT` `Nodejs/Docker`
- [Glance](https://github.com/glanceapp/glance) - 高度可定制的仪表盘，将所有信息源汇聚一处。`AGPL-3.0` `Docker/Go`
- [gobookmarks](https://github.com/arran4/gobookmarks) - 展示存储在 GitHub、GitLab 或本地 Git 中书签的落地页。`AGPL-3.0` `Go/Docker`
- [Heimdall](https://heimdall.site/) - 整理所有 Web 应用的优雅方案。([源代码](https://github.com/linuxserver/Heimdall)) `MIT` `PHP`
- [Homarr](https://homarr.dev) - 时尚现代的仪表盘，具有众多集成和基于 Web 的配置。([源代码](https://github.com/homarr-labs/homarr)) `MIT` `Docker/Nodejs`
- [Homepage by gethomepage](https://github.com/gethomepage/homepage) - 高度可定制的主页（或起始页/应用仪表盘），与 Docker 和服务 API 集成。`GPL-3.0` `Docker/Nodejs`
- [Homepage by tomershvueli](https://github.com/tomershvueli/homepage) - 简单、独立、自托管的 PHP 页面，是你通向服务器和网络的窗口。`MIT` `PHP`
- [Homer](https://github.com/bastienwirtz/homer) - 极其简单的静态主页，用于展示你的服务器服务，具有简单的 yaml 配置和连通性检查。([演示](https://homer-demo.netlify.app)) `Apache-2.0` `Docker/K8S/Nodejs`
- [Hubleys](https://github.com/knrdl/hubleys-dashboard) - 通过中央 yaml 配置为多个用户整理链接的个人仪表盘。`MIT` `Docker`
- [LinkStack](https://linkstack.org/) - 在一页上轻松访问你所有的社交媒体平台链接，通过直观易用的用户/管理界面进行自定义（Linktree 和 Manylink 的替代品）。([演示](https://linksta.cc/)、[源代码](https://github.com/LinkStackOrg/LinkStack)) `AGPL-3.0` `PHP/Docker`
- [LittleLink](https://littlelink.io/) - 个人简介链接的极简方案，提供 100 多个品牌按钮（Linktree 的替代品）。([演示](https://littlelink.io/)、[源代码](https://github.com/sethcottle/littlelink)) `MIT` `Javascript`
- [Mafl](https://mafl.hywax.space/) - 极简灵活的主页。([源代码](https://github.com/hywax/mafl)) `MIT` `Docker/Nodejs`
- [Nimbus](https://nimbus.turboot.com/) - 现代拖拽式家用实验室仪表盘，具有可视化编辑器和简单配置。([演示](https://nimbus.turboot.com/)、[源代码](https://github.com/Turbootzz/Nimbus)) `AGPL-3.0` `Docker`
- [Personal Management System](https://volmarg.github.io/) - 整理日常生活中的要点，从简单的待办事项和笔记到付款和日程安排，应有尽有。([演示](https://github.com/Volmarg/personal-management-system#documentation--demo)、[源代码](https://github.com/Volmarg/personal-management-system)) `MIT` `Docker`
- [portkey](https://portkey.page) - 简单的 Web 门户，用作起始页，展示链接和 URL 的汇编，同时允许添加自定义页面，全部通过单个配置文件管理。([演示](https://demo.portkey.page)、[源代码](https://github.com/kodehat/portkey)) `AGPL-3.0` `Go/Docker`
- [ryot](https://github.com/ignisda/ryot) - 追踪你生活的各个方面——媒体、健身等。([演示](https://github.com/IgnisDa/ryot?tab=readme-ov-file#-demo)) `GPL-3.0` `Docker`
- [Starbase 80](https://github.com/notclickable-jordan/starbase-80) - 具有 iPad 风格应用网格的简易主页，适用于移动端和桌面端。一个 JSON 配置文件。`MIT` `Docker`
- [Your Spotify](https://github.com/Yooooomi/your_spotify) `⚠` - 允许你记录 Spotify 收听活动，并通过 Web 应用提供相关统计。`MIT` `Nodejs/Docker`


### 相册 <a id="photo-galleries"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[相册](https://en.wikipedia.org/wiki/Gallery_Software)软件帮助用户发布或分享照片、图片、视频或其他数字媒体。

_相关：[静态站点生成器](#static-site-generators)、[媒体流 - 视频流](#media-streaming---video-streaming)、[内容管理系统（CMS）](#content-management-systems-cms)_

- [Chevereto](https://chevereto.com/) - 终极图像分享软件。几分钟内即可创建你自己的个人图床网站。([源代码](https://github.com/chevereto/chevereto)) `AGPL-3.0` `PHP/Docker`
- [ChronoFrame](https://chronoframe.bh8.ga/) - 个人画廊应用，具有在线照片管理功能，支持动态照片（Live/Motion Photos）和探索地图。([演示](https://lens.bh8.ga/)、[源代码](https://github.com/HoshinoSuzumi/chronoframe)) `MIT` `Nodejs/Docker`
- [Damselfly](https://damselfly.info) - 面向大型图像集合的快速服务器端照片管理系统。包含人脸检测、人脸与物体识别、强大的搜索和 EXIF 关键词标记。可运行于 Linux、MacOS 和 Windows。([源代码](https://github.com/webreaper/damselfly)) `GPL-3.0` `Docker/C#/.NET`
- [Ente](https://ente.com/) - 端到端加密的照片分享平台（Google Photos、Apple Photos 的替代品）。([源代码](https://github.com/ente/ente)) `AGPL-3.0` `Docker/Nodejs/Go`
- [HomeGallery](https://home-gallery.org) - 浏览个人照片和视频，具有标记、移动端友好和 AI 驱动的图像发现功能。([演示](https://demo.home-gallery.org)、[源代码](https://github.com/xemle/home-gallery)) `MIT` `Nodejs/Docker`
- [Immich Kiosk](https://github.com/damongolding/immich-kiosk) - 轻量级幻灯片，可在自助终端设备和浏览器上运行，使用 Immich 作为数据源。([客户端](https://github.com/immich-app/immich)) `GPL-3.0` `Docker/Go`
- [Immich](https://immich.app/) - 直接从你的手机备份照片和视频的解决方案（Google Photos 的替代品）。([演示](https://github.com/immich-app/immich#demo)、[源代码](https://github.com/immich-app/immich)) `AGPL-3.0` `Docker`
- [LibrePhotos](https://github.com/LibrePhotos/librephotos) - 照片管理服务，稍侧重于炫酷的图表（Google Photos 的替代品）。([客户端](https://docs.librephotos.com/docs/user-guide/mobile/)) `MIT` `Python/Docker`
- [Lychee](https://lycheeorg.github.io/) - 基于网格和相册的照片管理系统。([源代码](https://github.com/LycheeOrg/Lychee)) `MIT` `PHP/Docker`
- [Mediagoblin](https://mediagoblin.org) - 任何人都可以运行的媒体发布平台（Flickr、YouTube、SoundCloud 的替代品）。([源代码](https://git.savannah.gnu.org/cgit/mediagoblin.git/tree/)) `AGPL-3.0` `Python`
- [Memtly](https://docs.memtly.com/) - 活动照片分享平台和带幻灯片的画廊，让宾客可通过二维码查看和分享回忆。([演示](https://demo.memtly.com/)、[源代码](https://github.com/Memtly/Memtly.Community)) `GPL-3.0` `C#/Docker`
- [Nextcloud Memories](https://memories.gallery/) - 快速、现代且高级的照片管理套件。作为 Nextcloud 应用运行。([演示](https://demo.memories.gallery/apps/memories/)、[源代码](https://github.com/pulsejet/memories)) `AGPL-3.0` `PHP`
- [Photofield](https://github.com/SmilyOrg/photofield) - 实验性的快速照片查看器。`MIT` `Docker/Go`
- [PhotoPrism](https://photoprism.org) - 由 Go 和 Google TensorFlow 驱动的个人照片管理。使用最新技术自动标记和查找图片，浏览、整理和分享你的个人照片集。([演示](https://demo.photoprism.app/library/browse)、[源代码](https://github.com/photoprism/photoprism)) `AGPL-3.0` `Go/Docker`
- [Photoview](https://photoview.github.io/) - 面向个人服务器的简单易用的照片画廊。它为摄影师而打造，旨在提供轻松快速地浏览目录的方式，支持数千张高分辨率照片。([演示](https://photoview.github.io/)、[源代码](https://github.com/photoview/photoview)) `GPL-3.0` `Go/Docker`
- [PiGallery 2](https://bpatrik.github.io/pigallery2/) - 目录优先的照片画廊网站，具有丰富的 UI，针对在低资源服务器上运行进行了优化。([源代码](https://github.com/bpatrik/pigallery2)) `MIT` `Docker/Nodejs`
- [Piwigo](https://piwigo.org/) - 面向 Web 的照片画廊软件，由活跃的用户和开发者社区构建。([源代码](https://github.com/Piwigo/Piwigo)) `GPL-2.0` `PHP`
- [SPIS](https://github.com/gbbirkisson/spis) - 简单、轻量且快速的媒体服务器，具有良好的移动端支持。`GPL-3.0` `Docker/Rust`
- [This week in past](https://github.com/RouHim/this-week-in-past) - 汇总往年本周拍摄的照片，并以简单的幻灯片形式呈现在网页上。`MIT` `Docker/Rust`
- [Thumbor](http://thumbor.org/) - 智能图像服务，可实现按需裁剪、调整尺寸、应用滤镜和优化图像。([源代码](https://github.com/thumbor/thumbor)) `MIT` `Python/Docker`
- [Zenphoto](https://www.zenphoto.org/) - 画廊和 CMS 项目。([源代码](https://github.com/zenphoto/zenphoto)) `GPL-2.0` `PHP`


### 投票与活动 <a id="polls-and-events"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

用于组织[投票](https://en.wikipedia.org/wiki/Opinion_poll)与[活动](https://en.wikipedia.org/wiki/Event)的软件。

_相关：[预约与日程安排](#booking-and-scheduling)_

- [Bitpoll](https://github.com/fsinfuhh/Bitpoll) - 就日期、时间或一般问题进行投票。([演示](https://bitpoll.de/)) `GPL-3.0` `Docker/Python`
- [Bracket](https://docs.bracketapp.nl/) - 灵活的锦标赛系统，可构建锦标赛设置、添加队伍、安排比赛、追踪比分并向公众实时呈现排名。([演示](https://www.bracketapp.nl/demo)、[源代码](https://github.com/evroon/bracket)) `AGPL-3.0` `Docker/Nodejs`
- [Christmas Community](https://github.com/Wingysam/Christmas-Community) - 为你的整个家庭创建一个简单的场所，用于查找大家想要的礼物并避免重复送礼。`AGPL-3.0` `Docker/Nodejs`
- [Claper](https://claper.co/) - 与观众互动的终极工具（Slido、AhaSlides 和 Mentimeter 的替代品）。([源代码](https://github.com/ClaperCo/Claper)) `GPL-3.0` `Elixir/Docker`
- [ClearFlask](https://clearflask.com) - 社区反馈工具，用于管理收到的反馈并优先处理公开路线图（Canny、UserVoice、Upvoty 的替代品）。([演示](https://product.clearflask.com)、[源代码](https://github.com/clearflask/clearflask)) `AGPL-3.0` `Docker`
- [docassemble](https://docassemble.org/) - 基于 Python、YAML 和 Markdown 的引导式访谈和文档组装系统。([演示](https://demo.docassemble.org/run/legal)、[源代码](https://github.com/jhpyle/docassemble)) `MIT` `Docker/Python`
- [EventSchedule](https://eventschedule.com/) - 分享活动、售票并凝聚社区。([源代码](https://github.com/eventschedule/eventschedule)) `AAL` `PHP/Docker`
- [Fider](https://fider.io) - 收集并优先处理反馈的开放平台（UserVoice 的替代品）。([演示](https://demo.fider.io)、[源代码](https://github.com/getfider/fider)) `MIT` `Docker`
- [Formbricks](https://formbricks.com) - 基于全球最大的开源问卷技术栈构建的体验管理套件。在客户旅程的每一步优雅地收集反馈，了解你的客户需要什么。([演示](https://app.formbricks.com)、[源代码](https://github.com/formbricks/formbricks)) `AGPL-3.0` `Nodejs/Docker`
- [Framadate](https://framadate.org/abc/) - 用于快速轻松地安排约会或做出决定的在线服务：发起投票、定义可选日期或主题、将投票链接发送给朋友或同事、讨论并做出决定。([演示](https://framadate.org/aqg259dth55iuhwm)、[源代码](https://framagit.org/framasoft/framadate?)) `CECILL-B` `PHP`
- [Gancio](https://gancio.org/) - 本地社区活动与日程分享。([演示](https://demo.gancio.org/)、[源代码](https://framagit.org/les/gancio)) `AGPL-3.0` `Nodejs`
- [gathio](https://docs.gath.io/) - 自毁式、可分享、无需注册的活动页面。([演示](https://gath.io/)、[源代码](https://github.com/lowercasename/gathio)) `GPL-3.0` `Nodejs/Docker`
- [HeyForm](https://heyform.net) - 表单生成器，任何人都可以创建引人入胜的对话式表单，用于调查、问卷、测验和投票。([源代码](https://github.com/heyform/heyform)) `AGPL-3.0` `Docker`
- [hitobito](https://hitobito.com) - 管理带有成员、活动等内容的复杂群组层级。([演示](https://demo.hitobito.com/en/users/sign_in)、[源代码](https://github.com/hitobito/hitobito)) `AGPL-3.0` `Ruby`
- [LimeSurvey](https://www.limesurvey.org) - 功能丰富的基于 Web 的问卷调查软件。支持丰富的调查逻辑。([演示](https://demo.limesurvey.org)、[源代码](https://github.com/LimeSurvey/LimeSurvey)) `GPL-2.0` `PHP`
- [Meetable](https://events.indieweb.org) - 极简的活动聚合器。([源代码](https://github.com/aaronpk/Meetable)) `MIT` `PHP`
- [Mobilizon](https://mobilizon.org) - 帮助你发现、创建和组织活动与群组的联邦式工具。([源代码](https://framagit.org/framasoft/mobilizon/)) `AGPL-3.0` `Elixir/Docker`
- [OpnForm](https://opnform.com) - 美观的表单生成器。([演示](https://opnform.com/forms/create/guest)、[源代码](https://github.com/OpnForm/OpnForm)) `AGPL-3.0` `PHP/Nodejs/Docker`
- [Revel](https://www.letsrevel.io) `⚠` - 面向社区的活动管理和售票平台。([演示](https://demo.letsrevel.io)、[源代码](https://github.com/letsrevel/revel-backend)、[客户端](https://github.com/letsrevel)) `MIT` `Python/Docker`


### 代理 <a id="proxy"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[代理](https://en.wikipedia.org/wiki/Proxy_server)是作为请求资源的客户端与提供资源的服务器之间中介的服务器应用。本节介绍正向（即出站）代理；反向代理请参见 Web 服务器一节。

_相关：[Web 服务器](#web-servers)_

- [g3proxy](https://g3-project.readthedocs.io/projects/g3proxy/en/latest/) - 正向代理服务器，支持代理链、协议检测、MITM 拦截、ICAP 适配和透明代理。([源代码](https://github.com/bytedance/g3/tree/master/g3proxy)) `Apache-2.0` `Rust/deb`
- [GitProxy](https://git-proxy.finos.org/) - Git 代理，对所有出站的 git push 操作应用规则和工作流并确保其合规。它支持 HTTP/HTTPS 和 SSH 协议，具有安全扫描和验证功能。([源代码](https://github.com/finos/git-proxy)) `Apache-2.0` `Nodejs/Docker`
- [imagor](https://github.com/cshum/imagor) - 快速、安全的图像处理服务器和基于 libvips 的 Go 库，支持按需调整尺寸、裁剪、滤镜、格式转换和图像合成、签名 URL 以及用于高并发吞吐的流式管道。`Apache-2.0` `Docker`
- [imgproxy](https://imgproxy.net/) - 用于调整尺寸和转换远程图像的快速、安全的独立服务器。([源代码](https://github.com/imgproxy/imgproxy)) `MIT` `Go/Docker/K8S`
- [Outline Server](https://getoutline.org/) - 代理服务器，为每个访问密钥运行一个 Shadowsocks 实例，并提供用于管理访问密钥的 REST API。([源代码](https://github.com/OutlineFoundation/outline-server)) `Apache-2.0` `Docker/Nodejs`
- [Privoxy](https://www.privoxy.org) - 非缓存 Web 代理，具有高级过滤功能，可增强隐私、修改网页数据和 HTTP 标头、控制访问，并移除广告和其他令人讨厌的互联网垃圾。`GPL-2.0` `C/deb`
- [sish](https://github.com/antoniomika/sish) - 仅使用 SSH 即可建立到 localhost 的 HTTP(S)/WS(S)/TCP 隧道（serveo/ngrok 的替代品）。`MIT` `Go/Docker`
- [socks5-proxy-server](https://github.com/nskondratev/socks5-proxy-server) - 内置身份验证的 SOCKS5 代理服务器，附带用于用户管理和数据用量统计的 Telegram 机器人（按 GB 计费时很方便）。它已容器化，安装简单。`Apache-2.0` `Docker`
- [Squid](http://www.squid-cache.org/) - 面向 Web 的缓存代理，支持 HTTP、HTTPS、FTP 等。它通过缓存和复用频繁请求的网页来减少带宽并改善响应时间。([源代码](https://code.launchpad.net/squid)) `GPL-2.0` `C/deb`
- [Tinyproxy](https://tinyproxy.github.io/) - 轻量级 HTTP/HTTPS 代理守护进程。([源代码](https://github.com/tinyproxy/tinyproxy)) `GPL-2.0` `C/deb`


### 食谱管理 <a id="recipe-management"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

用于管理[食谱](https://en.wikipedia.org/wiki/Recipe)的软件与工具。

- [Bar Assistant](https://barassistant.app/) - 管理你的家庭酒吧，可添加原料、搜索鸡尾酒并创建自定义鸡尾酒配方。([演示](https://demo.barassistant.app/)、[源代码](https://github.com/karlomikus/bar-assistant)) `MIT` `PHP/Docker`
- [CookCLI](https://cooklang.org) - 使用 Cooklang 菜谱自动化备餐和购物的命令行工具，可为 UNIX 工作流编写脚本，包含 Web 服务器。([源代码](https://github.com/cooklang/CookCLI)) `MIT` `Rust`
- [Fork Recipes](https://mikebgrep.github.io/forkapi/latest/clients/) - 简单轻松地管理你的美食菜谱。([源代码](https://github.com/mikebgrep/fork.recipes)) `BSD-3-Clause` `Docker`
- [ManageMeals](https://managemeals.com/) - 管理菜谱，通过 URL 导入菜谱并整理它们，没有任何广告或多余文字。([源代码](https://github.com/managemeals/manage-meals-web)) `GPL-3.0` `Docker`
- [Mealie](https://nightly.mealie.io/) - 受 Material Design 启发的菜谱管理器，具有分类和标签管理、购物清单、备餐计划和站点自定义功能。Mealie 专注于简单的用户交互，让全家人都愿意使用。([演示](https://demo.mealie.io)、[源代码](https://github.com/mealie-recipes/mealie)) `MIT` `Python`
- [RecipeSage](https://github.com/julianpoy/recipesage) - 菜谱保管、备餐计划整理和购物清单管理器，可直接从任意 URL 导入菜谱。([演示](https://recipesage.com)) `AGPL-3.0` `Nodejs`
- [Recipya](https://recipes.musicavis.ca) - 简洁、简单且强大的菜谱管理器，你全家都会喜欢。([演示](https://recipes.musicavis.ca/guide/login)、[源代码](https://github.com/reaper47/recipya)) `GPL-3.0` `Docker/Go`
- [Tamari](https://tamariapp.com) - 带内置菜谱集的菜谱管理 Web 应用。可按收藏夹和分类整理、创建购物清单并规划餐食。([演示](https://app.tamariapp.com)、[源代码](https://github.com/alexbates/Tamari)) `GPL-3.0` `Docker/Python`
- [Vanilla Cookbook](https://vanilla-cookbook.readthedocs.io/en/) - 内部复杂而用户体验尽可能简洁纯粹的菜谱管理器。([源代码](https://github.com/jt196/vanilla-cookbook)) `GPL-3.0` `Docker/Nodejs`
- [What To Cook?](https://github.com/kassner/whattocook) - 根据你家里现有的食材，获取今天要做的菜谱。`AGPL-3.0` `Docker`


### 远程访问 <a id="remote-access"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[远程桌面](https://en.wikipedia.org/wiki/Remote_desktop_software)与 [SSH](https://en.wikipedia.org/wiki/Secure_Shell) 服务器，以及用于远程管理计算机系统的 Web 界面。

- [Cardea](https://github.com/hectorm/cardea) - SSH 堡垒服务器，具有访问控制、会话记录和可选的 TPM 支持的密钥保护。`EUPL-1.2` `Go/Docker`
- [Engity's Bifröst](https://bifroest.engity.org/) - 高度可定制的 SSH 服务器，提供多种用户授权方式，以及选择在何处和如何执行用户会话的选项。([源代码](https://github.com/engity-com/bifroest)) `Apache-2.0` `Go/Docker`
- [Firezone](https://www.firezone.dev/) - 支持 WireGuard 协议的安全远程访问网关。它提供 Web GUI、一行安装脚本、多因素认证（MFA）和 SSO。([源代码](https://github.com/firezone/firezone)) `Apache-2.0` `Elixir/Docker`
- [Guacamole](https://guacamole.apache.org) - 无客户端远程桌面网关，支持 VNC 和 RDP 等标准协议。([源代码](https://github.com/apache/guacamole-server)) `Apache-2.0` `Java/C`
- [MeshCentral](https://meshcentral.com/) - 运行你自己的 Web 服务器，以远程管理和控制局域网或互联网上任何位置的计算机。([源代码](https://github.com/Ylianst/MeshCentral)) `Apache-2.0` `Nodejs`
- [ShellHub](https://www.shellhub.io) - 现代 SSH 服务器，可通过命令行（使用任意 SSH 客户端）或基于 Web 的用户界面远程访问 Linux 设备（sshd 的替代品）。([源代码](https://github.com/shellhub-io/shellhub)) `Apache-2.0` `Docker`
- [Sshwifty](https://github.com/nirui/sshwifty) - Sshwifty 是为 Web 打造的 SSH 和 Telnet 连接器。([演示](https://sshwifty-demo.nirui.org)) `AGPL-3.0` `Go/Docker`
- [Termix](https://docs.termix.site/) - 无客户端、基于 Web 的服务器管理平台，具有 SSH 终端、隧道和文件编辑功能。([源代码](https://github.com/Termix-SSH/Termix)) `Apache-2.0` `Docker`
- [Warpgate](https://github.com/warp-tech/warpgate) - 完全透明的 SSH、HTTPS、Kubernetes、MySQL 和 Postgres 堡垒机/PAM，无需额外的客户端软件。`Apache-2.0` `Rust/Docker`


### 资源规划 <a id="resource-planning"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

用于辅助[资源与供应规划](https://en.wikipedia.org/wiki/Resource_planning)的软件与工具，包括[企业资源与供应规划（ERP）](https://en.wikipedia.org/wiki/Enterprise_resource_planning)。

_相关：[财务、预算与管理](#money-budgeting--management)、[库存管理](#inventory-management)_

- [Dolibarr](https://www.dolibarr.org/) - 现代 CRM 软件包，用于管理你的公司或基金会活动（联系人、供应商、发票、订单、库存、日程、会计……）。([演示](https://www.dolibarr.org/onlinedemo.php)、[源代码](https://github.com/Dolibarr/dolibarr)) `GPL-3.0` `PHP/deb`
- [ERPNext](https://frappe.io/erpnext) - 帮助你经营企业的 ERP 系统。([源代码](https://github.com/frappe/erpnext)) `GPL-3.0` `Python/Docker`
- [farmOS](https://farmos.org/) - 基于 Web 的农场记录保存应用。([演示](https://farmos-demo.rootedsolutions.io/)、[源代码](https://github.com/farmOS/farmOS)) `GPL-2.0` `PHP/Docker`
- [grocy](https://grocy.info/) - 超越冰箱的 ERP。面向你家庭的食物与家庭管理方案。([演示](https://en.demo.grocy.info/)、[源代码](https://github.com/grocy/grocy)) `MIT` `PHP/Docker`
- [LedgerSMB](https://ledgersmb.org/) - 面向中小企业的集成会计和 ERP 系统，具有复式记账、预算、发票、报价、项目、订单和库存管理、发货等功能。([源代码](https://github.com/ledgersmb/LedgerSMB)) `GPL-2.0` `Docker/Perl`
- [Odoo](https://www.odoo.com) - 免费开源 ERP 系统。([演示](https://demo.odoo.com/)、[源代码](https://github.com/odoo/odoo)) `LGPL-3.0` `Python/deb/Docker`
- [OFBiz](https://ofbiz.apache.org/) - 企业资源计划系统，附带一套灵活到可用于任何行业的业务应用。([源代码](https://github.com/apache/ofbiz-framework)) `Apache-2.0` `Java`
- [Tryton](https://www.tryton.org/) - 免费开源的业务解决方案。([演示](https://www.tryton.org/demo)、[源代码](https://foss.heptapod.net/tryton/tryton)) `GPL-3.0` `Python`


### 搜索引擎 <a id="search-engines"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[搜索引擎](https://en.wikipedia.org/wiki/Search_engine_(computing))是旨在帮助查找存储在计算机系统中的信息的[信息检索系统](https://en.wikipedia.org/wiki/Information_retrieval)，其中包括[网页搜索引擎](https://en.wikipedia.org/wiki/Web_search_engine)。

- [Aleph](https://aleph.occrp.org/) - 用于为大量文档（PDF、Word、HTML）和结构化（CSV、XLS、SQL）数据建立索引以便轻松浏览和搜索的工具。它以调查性报道为主要用例构建。([演示](https://aleph.occrp.org/)、[源代码](https://github.com/alephdata/aleph)) `MIT` `Docker/K8S`
- [Amgix](https://amgix.io) - 为灵活部署和真实世界的杂乱数据构建的混合搜索引擎。([演示](https://findgovdata.org)、[源代码](https://github.com/amgix/amgix-server)、[客户端](https://github.com/orgs/amgix/repositories)) `AGPL-3.0` `Docker/K8S`
- [Apache Solr](https://lucene.apache.org/solr/) - 企业级搜索平台，具有全文搜索、命中高亮、分面搜索、实时索引、动态聚类以及处理丰富文档（如 Word、PDF）的能力。([源代码](https://github.com/apache/solr)) `Apache-2.0` `Java/Docker/K8S`
- [Fess](https://fess.codelibs.org/) - 强大且易于部署的企业级搜索服务器。([演示](https://search.n2sm.co.jp/)、[源代码](https://github.com/codelibs/fess)) `Apache-2.0` `Java/Docker`
- [Hister](https://hister.org/) - 个人 Web 搜索引擎，自动索引访问过的网站。支持离线本地结果预览、本地文件、多用户处理和可选的语义搜索。([演示](https://demo.hister.org/)、[源代码](https://github.com/asciimoo/hister)) `AGPL-3.0` `Go/Docker`
- [Manticore Search](https://github.com/manticoresoftware/manticoresearch/) - 全文搜索和数据分析，对小型、中型和大型数据均具有快速响应时间（Elasticsearch 的替代品）。`GPL-3.0` `Docker/deb/C++/K8S`
- [MeiliSearch](https://www.meilisearch.com) - 极度相关、即时且容忍拼写错误的全文搜索 API。([源代码](https://github.com/meilisearch/MeiliSearch)) `MIT` `Rust/Docker/deb`
- [Meme Search](https://github.com/neonwatty/meme-search) - AI 驱动的表情包搜索引擎。使用视觉语言模型自动从图像中提取描述，然后用向量嵌入建立索引以进行语义和关键词搜索。([源代码](https://github.com/meme-search/meme-search)) `Apache-2.0` `Docker`
- [OpenSearch](https://opensearch.org) - 分布式 RESTful 搜索引擎。([源代码](https://github.com/opensearch-project/OpenSearch)) `Apache-2.0` `Java/Docker/K8S/deb`
- [SearXNG](https://docs.searxng.org/) `⚠` - 互联网元搜索引擎，聚合来自各种搜索服务和数据库的结果（Searx 的分支）。([源代码](https://github.com/searxng/searxng/)) `AGPL-3.0` `Python/Docker`
- [Sosse](https://sosse.readthedocs.io/en/stable/) - 基于 Selenium 的搜索引擎和爬虫，具有离线归档功能。([源代码](https://gitlab.com/biolds1/sosse)) `AGPL-3.0` `Python/Docker`
- [Typesense](https://typesense.org) - 极快、容忍拼写错误的开源搜索引擎，为开发者幸福感和易用性而优化。([源代码](https://github.com/typesense/typesense)) `GPL-3.0` `C++/Docker/K8S/deb`
- [Websurfx](https://github.com/neon-mmd/websurfx) `⚠` - 聚合来自其他搜索引擎的结果（元搜索引擎），无广告，同时兼顾隐私和安全。它极其快速并提供高度可定制性（SearX 的替代品）。`AGPL-3.0` `Rust/Docker`
- [Yacy](https://yacy.net/en/index.html) - 基于对等网络的去中心化搜索引擎服务器。([源代码](https://github.com/yacy/yacy_search_server)) `GPL-2.0` `Java/Docker/K8S`


### 自托管解决方案 <a id="self-hosting-solutions"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

用于便捷安装、管理和配置自托管服务与应用程序的软件。

- [DietPi](https://dietpi.com/) - 为单板计算机优化的极简 Debian 操作系统，让你可以轻松安装和管理多个用于家庭自托管的服务。([源代码](https://github.com/MichaIng/DietPi)) `GPL-2.0` `Shell`
- [DockSTARTer](https://dockstarter.com/) - DockSTARTer 帮助你开始运行 Docker 中的家庭服务器应用。([源代码](https://github.com/GhostWriters/DockSTARTer)) `MIT` `Shell`
- [Dropserver](https://dropserver.org) - 面向你个人 Web 服务的应用平台。([源代码](https://github.com/teleclimber/Dropserver/)) `Apache-2.0` `Go/Deno`
- [FreedomBox](https://freedombox.org/) - 开发、设计和推广运行自由软件的个人服务器的社区项目，用于私人和个人通信。([源代码](https://salsa.debian.org/freedombox-team/freedombox)) `AGPL-3.0` `Python/deb`
- [HomeButler](https://homebutler.dev) - 通过 Docker Compose 安装和管理精选应用目录，映射容器和暴露端口，验证备份可恢复，并报告自上次运行以来的变更，提供 CLI、JSON、Web 和 MCP 接口。([源代码](https://github.com/Higangssh/homebutler)) `MIT` `Docker/Go`
- [HomelabOS](https://homelabos.com) - 离线隐私优先的数据中心。用几条命令即可部署 100 多个服务。([源代码](https://gitlab.com/NickBusey/HomelabOS)) `MIT` `Docker`
- [HomeServerHQ](https://www.homeserverhq.com/) - 一体化家庭服务器基础设施和安装程序。不到一小时即可搭建完全配置好的电子邮件服务器、VPN 和公共网站，即使在 CGNAT 之后也可以。([源代码](https://github.com/homeserverhq/hshq)) `GPL-3.0` `Shell`
- [LibreServer](https://libreserver.org/) - 基于 Debian 的家庭服务器配置。([源代码](https://github.com/bashrc2/libreserver)) `AGPL-3.0` `Shell`
- [NextCloudPi](https://github.com/nextcloud/nextcloudpi) - 预装并预配置的 Nextcloud，带文本和 Web 管理界面以及自托管私人数据所需的所有工具。提供适用于 Raspberry Pi、Odroid、Rock64、Docker 的安装镜像，以及适用于 Armbian/Debian 的 curl 安装脚本。`GPL-2.0` `Shell/PHP`
- [Nirvati](https://nirvati.org) - 通过便捷的 Web 界面轻松一键启动流行的自托管应用。([源代码](https://gitlab.com/nirvati-ug/nirvati/backend)) `AGPL-3.0` `Rust/K8S`
- [OpenMediaVault](https://www.openmediavault.org/) - 基于 Debian Linux 的网络附加存储（NAS）解决方案。它包含 SSH、(S)FTP、SMB/CIFS、DAAP 媒体服务器、RSync、BitTorrent 客户端等服务。([源代码](https://github.com/openmediavault/openmediavault)) `GPL-3.0` `PHP`
- [Sandstorm](https://sandstorm.io/) - 用于轻松安全地运行自托管应用的个人服务器。([演示](https://demo.sandstorm.io/)、[源代码](https://github.com/sandstorm-io/sandstorm)) `Apache-2.0` `C++/Shell`
- [Self Host Blocks](https://github.com/ibizaman/selfhostblocks) `⚠` - 基于 NixOS 模块的模块化服务器管理，专注于最佳实践。`AGPL-3.0` `Nix`
- [StartOS](https://start9.com) - 基于浏览器的图形化操作系统（OS），让运行个人服务器像运行个人电脑一样简单。([源代码](https://github.com/Start9Labs/start-technologies)) `MIT` `Rust`
- [Syncloud](https://syncloud.org/) - 带应用商店和自动更新的操作系统，适用于 Nextcloud、Jellyfin、Bitwarden 和 Paperless 等应用，包含 HTTPS、域名和无需公网 IP 的远程访问。([源代码](https://github.com/syncloud/platform)) `GPL-3.0` `Go/Shell`
- [Tipi](https://runtipi.io/) - 家庭服务器管理器。一条命令完成设置，一键安装你最喜欢的自托管应用。([源代码](https://github.com/runtipi/runtipi)) `GPL-3.0` `Shell`
- [UBOS](https://ubos.net/) - 运行在独立设备（个人服务器和物联网设备）上的 Linux 发行版。单条命令即可安装和管理应用——Jenkins、Mediawiki、Owncloud、WordPress 等，以及其他功能。`GPL-3.0` `Perl`
- [Websoft9](https://www.websoft9.com) `⚠` - GitOps 驱动、面向云服务器和家庭服务器的多应用托管，一键部署 200 多个开源应用。([演示](https://www.websoft9.com/demo)、[源代码](https://github.com/websoft9/websoft9)、[客户端](https://www.websoft9.com/apps)) `LGPL-3.0` `Shell/Python`
- [WikiSuite](https://wikisuite.org) - 最全面、最集成的自由/开源企业软件套件。([源代码](https://wikisuite.org/Source-Code)) `GPL-3.0/LGPL-2.1/Apache-2.0/MPL-2.0/MPL-1.1/MIT/AGPL-3.0` `Shell/Perl/deb`
- [xsrv](https://xsrv.readthedocs.io/) - 在你自己的服务器上安装和管理自托管服务/应用。([源代码](https://github.com/nodiscc/xsrv)) `GPL-3.0` `Ansible/Shell`
- [YunoHost](https://yunohost.org/) - 旨在让每个人都能使用自托管的服务器操作系统。([演示](https://yunohost.org/#/try)、[源代码](https://github.com/YunoHost)) `AGPL-3.0` `Python/Shell`


### 软件开发 <a id="software-development"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[软件开发](https://en.wikipedia.org/wiki/Software_development)是创建和维护应用、框架或其他软件组件所涉及的构思、规格、设计、编程、文档、测试与缺陷修复过程。

**请访问[软件开发 - API 管理](#software-development---api-management)、[软件开发 - 持续集成与部署](#software-development---continuous-integration--deployment)、[软件开发 - FaaS 与无服务器](#software-development---faas--serverless)、[软件开发 - IDE 与工具](#software-development---ide--tools)、[软件开发 - 本地化](#software-development---localization)、[软件开发 - 低代码](#software-development---low-code)、[软件开发 - 项目管理](#software-development---project-management)、[软件开发 - 测试](#software-development---testing)、[软件开发 - 功能开关](#software-development---feature-toggle)**



### 软件开发 - API 管理 <a id="software-development---api-management"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[API 管理](https://en.wikipedia.org/wiki/API_management)是创建和发布[应用程序编程接口（API）](https://en.wikipedia.org/wiki/API)、执行其使用策略、控制访问、培育订阅者社区、收集与分析使用统计并报告性能的过程。

- [Aastro](https://starwalkn.github.io/aastro-docs) - 用 Go 编写的可扩展 API 网关。([源代码](https://github.com/starwalkn/aastro)) `Apache-2.0` `Go/Docker`
- [DreamFactory](https://www.dreamfactory.com/) - 将任何 SQL/NoSQL/结构化数据转化为 RESTful API。([源代码](https://github.com/dreamfactorysoftware/dreamfactory)) `Apache-2.0` `PHP/Docker/K8S`
- [form.io](https://form.io) - REST API 构建平台，利用拖拽式表单生成器，且与应用框架无关。包含开源版和企业版。([演示](https://portal.form.io)、[源代码](https://github.com/formio)) `MIT` `Nodejs/Docker`
- [Fusio](https://www.fusio-project.org/) - API 管理平台，帮助构建和管理 REST API。([演示](https://fusio-project.org/demo)、[源代码](https://github.com/apioo/fusio)) `AGPL-3.0` `PHP/Docker`
- [Graphweaver](https://graphweaver.com/) - 将多个数据源转化为单个 GraphQL API。([源代码](https://github.com/exogee-technology/graphweaver)) `MIT` `Nodejs`
- [Hasura](https://hasura.io) - 在 Postgres 上快速、即时地提供实时 GraphQL API，具有细粒度访问控制，还可基于数据库事件触发 webhook。([源代码](https://github.com/hasura/graphql-engine)) `Apache-2.0` `Haskell/Docker/K8S`
- [Hoppscotch Community Edition](https://hoppscotch.io) - 快速且美观的 API 请求构建器。([源代码](https://github.com/hoppscotch/hoppscotch)) `MIT` `Nodejs/Docker`
- [Kong](https://konghq.com/kong/) - 微服务 API 网关和平台。([源代码](https://github.com/Kong/kong)) `Apache-2.0` `Lua/Docker/K8S/deb`
- [Lura](https://luraproject.org/) - 高性能 API 网关。([源代码](https://github.com/luraproject/lura)) `Apache-2.0` `Go`
- [Opik](https://www.comet.com/site/products/opik/) `⚠` - 使用一套可观测性工具来评估、测试和交付 LLM 应用，以在你的开发和生产生命周期中校准语言模型输出。([源代码](https://github.com/comet-ml/opik)) `Apache-2.0` `Docker/Python`
- [Para](https://paraio.org) - 灵活且模块化的后端框架/服务器，用于对象持久化、API 开发和身份验证。([源代码](https://github.com/erudika/para)) `Apache-2.0` `Java/Docker`
- [Svix](https://svix.com) - 将 Webhook 作为服务，让 API 提供方发送 webhook 变得极其简单。([源代码](https://github.com/svix/svix-webhooks)) `MIT` `Docker/Rust`
- [Tyk](https://tyk.io) - 快速且可扩展的开源 API 网关。开箱即用的 Tyk 提供包含 API 网关、API 分析、开发者门户和 API 管理仪表盘的 API 管理平台。([源代码](https://github.com/TykTechnologies/tyk)) `MPL-2.0` `Go/Docker/K8S`


### 软件开发 - 持续集成与部署 <a id="software-development---continuous-integration--deployment"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[持续集成](https://en.wikipedia.org/wiki/Continuous_integration)与[持续部署](https://en.wikipedia.org/wiki/Continuous_deployment)软件与工具。

**请访问 [awesome-sysadmin/Continuous Integration & Continuous Deployment](https://github.com/awesome-foss/awesome-sysadmin#continuous-integration--continuous-deployment)**

_相关：[自动化](#automation)_



### 软件开发 - FaaS 与无服务器 <a id="software-development---faas--serverless"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[无服务器计算](https://en.wikipedia.org/wiki/Serverless_computing)、[函数即服务（FaaS）](https://en.wikipedia.org/wiki/Function_as_a_service)与[平台即服务（PaaS）](https://en.wikipedia.org/wiki/Platform_as_a_service)管理软件。

**请访问 [awesome-sysadmin/PaaS](https://github.com/awesome-foss/awesome-sysadmin#paas)**



### 软件开发 - 功能开关 <a id="software-development---feature-toggle"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

软件开发中的[功能开关](https://en.wikipedia.org/wiki/Feature_toggle)提供了在源码中维护多个功能分支之外的另一种选择。

_相关：[软件开发 - IDE 与工具](#software-development---ide--tools)_

- [Featbit](https://www.featbit.co/) - 企业级功能标志平台，可自行托管。([源代码](https://github.com/featbit/featbit)) `MIT` `Docker/K8S`
- [Flagsmith](https://flagsmith.com) - 用于向你的应用添加功能标志的仪表盘、API 和 SDK（LaunchDarkly 的替代品）。([源代码](https://github.com/flagsmith/flagsmith)) `BSD-3-Clause` `Docker/K8S`
- [Flipt](https://flipt.io) - 功能标志解决方案，支持多种数据后端（LaunchDarkly 的替代品）。([源代码](https://github.com/flipt-io/flipt)) `GPL-3.0` `Docker/K8S/Go`
- [GO Feature Flag](https://gofeatureflag.org) - 简单、完整且轻量的功能标志解决方案（LaunchDarkly 的替代品）。([源代码](https://github.com/thomaspoignant/go-feature-flag)) `MIT` `Go`
- [Nona](https://nonaconfig.com) - 远程配置和功能标志服务，提供单个 REST API、多个环境以及官方的 JavaScript 和 .NET 客户端（Firebase Remote Config 的替代品）。([源代码](https://github.com/Ryware/nona-config)) `Apache-2.0` `Docker`


### 软件开发 - IDE 与工具 <a id="software-development---ide--tools"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[集成开发环境（IDE）](https://en.wikipedia.org/wiki/Integrated_development_environment)为程序员提供用于软件开发的综合设施。

_相关：[软件开发 - 低代码](#software-development---low-code)_

- [Atheos](https://www.atheos.io) - 基于 Web 的 IDE 框架，占用小、要求极低，由 Codiad 延续而来。([源代码](https://github.com/Atheos/Atheos)) `MIT` `PHP/Docker`
- [code-server](https://github.com/coder/code-server) - 在浏览器中运行的 VS Code，托管在远程服务器上。`MIT` `Nodejs/Docker`
- [Coder](https://coder.com/) - 在你自己的基础设施上运行远程开发机器。([源代码](https://github.com/coder/coder)) `AGPL-3.0` `Go/Docker/K8S/deb`
- [Eclipse Che](https://www.eclipse.org/che/) - 开源工作空间服务器和云 IDE。([源代码](https://github.com/eclipse-che/che)) `EPL-1.0` `Docker/Java`
- [Hopp](https://gethopp.app) - 远程结对编程应用，具有低延迟 4K 屏幕共享、绘图和远程控制功能，提供 macOS 和 Windows 客户端（Tuple、Pop、Drovio、Coscreen 的替代品）。([源代码](https://github.com/gethopp/hopp)) `AGPL-3.0` `Docker`
- [Judge0 CE](https://judge0.com) - 用于编译和运行源代码的 API。([源代码](https://github.com/judge0/judge0)) `GPL-3.0` `Docker`
- [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/) - 用于交互式可重复计算的基于 Web 的环境。([演示](https://mybinder.org/v2/gh/jupyterlab/jupyterlab-demo/try.jupyter.org?urlpath=lab)、[源代码](https://github.com/jupyterlab/jupyterlab/)) `BSD-3-Clause` `Python/Docker`
- [Langfuse](https://langfuse.com) - LLM 工程平台，用于模型追踪、提示词管理和应用评估。Langfuse 帮助团队协作调试、分析并迭代他们的 LLM 应用，如聊天机器人或 AI 智能体。([演示](https://langfuse.com/docs/demo)、[源代码](https://github.com/langfuse/langfuse)、[客户端](https://langfuse.com/docs/integrations/overview)) `MIT` `Docker`
- [LiveCodes](https://livecodes.io/docs/features/self-hosting) `⚠` - 功能丰富的客户端代码演练场，支持 React、Vue、Svelte、Solid、Typescript、Python、Go、Ruby、PHP 及 90 多种其他语言。([演示](https://livecodes.io)、[源代码](https://github.com/live-codes/livecodes)) `MIT` `Nodejs`
- [Lowdefy](https://www.lowdefy.com/) - 使用 YAML / JSON 在几分钟内构建内部工具、BI 仪表盘、管理面板、CRUD 应用和工作流。([源代码](https://github.com/lowdefy/lowdefy)) `Apache-2.0` `Nodejs/Docker`
- [RapidForge](https://rapidforge.io/) - 用于构建 webhook、定时任务和页面的轻量级平台。用 Bash 或 Lua 实现你的逻辑。([源代码](https://github.com/rapidforge-io/rapidforge)) `Apache-2.0` `Go/Nodejs`
- [RStudio Server](https://www.rstudio.com/products/rstudio/#Server) - 基于 Web 浏览器的 R 语言 IDE。([源代码](https://github.com/rstudio/rstudio)) `AGPL-3.0` `Java/C++`


### 软件开发 - 本地化 <a id="software-development---localization"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[本地化](https://en.wikipedia.org/wiki/Internationalization_and_localization)是将代码和软件适配到其他语言的过程。

- [Accent](https://www.accent.reviews/) - 面向开发者的翻译工具。([源代码](https://github.com/mirego/accent)) `BSD-3-Clause` `Elixir/Docker`
- [Tolgee](https://tolgee.io) - 对开发者和译者都友好的基于 Web 的本地化平台，让用户可直接在他们开发的应用中进行翻译。([源代码](https://github.com/tolgee/tolgee-platform)) `Apache-2.0` `Docker/Java`
- [Traduora](https://traduora.co) - 面向团队的翻译管理平台。([源代码](https://github.com/ever-co/ever-traduora)) `AGPL-3.0` `Docker/K8S/Nodejs`
- [Weblate](https://weblate.org) - 基于 Web 的翻译工具，与版本控制紧密集成。([源代码](https://github.com/WeblateOrg/weblate)) `GPL-3.0` `Python/Docker/K8S`


### 软件开发 - 低代码 <a id="software-development---low-code"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[低代码](https://en.wikipedia.org/wiki/Low-code_development_platform)开发平台（LCDP）提供了一种通过图形用户界面创建应用软件的开发环境。

_相关：[软件开发 - IDE 与工具](#software-development---ide--tools)_

- [Appsmith](https://www.appsmith.com/) - 构建管理面板、CRUD 应用和工作流。以快 10 倍的速度构建你需要的一切。([源代码](https://github.com/appsmithorg/appsmith)) `Apache-2.0` `Java/Docker/K8S`
- [Appwrite](https://appwrite.io) - 面向 Web、原生和移动开发者的端到端后端服务器 🚀。([源代码](https://github.com/appwrite/appwrite)) `BSD-3-Clause` `Docker`
- [Halo](https://www.halo.run) - 强大且易用的网站建设工具（文档为中文）。([演示](https://docs.halo.run/#%E5%9C%A8%E7%BA%BF%E4%BD%93%E9%AA%8C)、[源代码](https://github.com/halo-dev/halo)、[客户端](https://github.com/halo-sigs/awesome-halo)) `GPL-3.0` `Java/Docker`
- [Manifest](https://manifest.build) - 装进 1 个 YAML 文件的完整后端。([演示](https://manifest.new)、[源代码](https://github.com/mnfst/llm-gateway)) `MIT` `Nodejs`
- [PocketBase](https://pocketbase.io/) - 用单个文件为你的下一个 SaaS 和移动应用提供后端。([源代码](https://github.com/pocketbase/pocketbase)) `MIT` `Go/Docker`
- [Saltcorn](https://saltcorn.com/) - 面向 Web 和移动应用的无代码数据库应用构建器。一个平台涵盖用户界面、数据后端、持久化工作流、电子邮件、PDF 生成和 AI 应用。([源代码](https://github.com/saltcorn/saltcorn)) `MIT` `Docker/Nodejs`
- [SQLPage](https://sql-page.com) - 仅用 SQL 的动态网站构建器。([源代码](https://github.com/sqlpage/SQLPage)) `MIT` `Rust/Docker`
- [ToolJet](https://tooljet.io/) - 低代码框架，以最小的工程投入构建和部署内部工具（Retool 和 Mendix 的替代品）。([源代码](https://github.com/ToolJet/ToolJet)) `GPL-3.0` `Nodejs/Docker/K8S`
- [TrailBase](https://trailbase.io/) - 开放、亚毫秒级、单可执行文件的 FireBase 替代品，具有类型安全的 REST 和实时 API、内置 JS/TS 运行时、认证和管理 UI。([演示](https://demo.trailbase.io)、[源代码](https://github.com/trailbaseio/trailbase)) `OSL-3.0` `Rust/Docker`


### 软件开发 - 项目管理 <a id="software-development---project-management"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

用于[软件项目管理](https://en.wikipedia.org/wiki/Software_project_management)的工具与软件。

_相关：[工单系统](#ticketing)、[任务管理与待办清单](#task-management--to-do-lists)_

- [Cgit](https://git.zx2c4.com/cgit/about/) - 面向 git 仓库的快速轻量级 Web 界面。([源代码](https://git.zx2c4.com/cgit/tree/)) `GPL-2.0` `C`
- [Forgejo](https://forgejo.org) - 专注于扩展性、联邦和隐私的轻量级软件托管平台（Gitea 的分支）。([演示](https://next.forgejo.org)、[源代码](https://codeberg.org/forgejo/forgejo/)、[客户端](https://codeberg.org/forgejo-contrib/delightful-forgejo)) `MIT` `Docker/Go`
- [Fossil](https://www.fossil-scm.org/index.html/doc/trunk/www/index.wiki) - 分布式版本控制系统，具有 wiki 和缺陷跟踪功能。`BSD-2-Clause-FreeBSD` `C`
- [Gerrit](https://www.gerritcodereview.com/) - 面向基于 Git 项目的代码审查和项目管理工具。([源代码](https://github.com/GerritCodeReview/gerrit)) `Apache-2.0` `Java/Docker`
- [gitbucket](https://gitbucket.github.io/) - 易于安装、高度可扩展且兼容 GitHub API 的 Git 平台（GitHub 的替代品）。([源代码](https://github.com/gitbucket/gitbucket)) `Apache-2.0` `Scala/Java`
- [Gitea](https://gitea.com) - 一杯茶的 Git！无痛自托管的一体化软件开发服务，包括 Git 托管、代码审查、团队协作、包注册表和 CI/CD。([演示](https://gitea.com/explore/repos)、[源代码](https://github.com/go-gitea/gitea)) `MIT` `Go/Docker/K8S`
- [GitLab](https://about.gitlab.com) - 自托管的 Git 仓库管理、代码审查、问题跟踪、活动信息流和 wiki。([演示](https://gitlab.com/)、[源代码](https://gitlab.com/gitlab-org/gitlab-foss)) `MIT` `Ruby/deb/Docker/K8S`
- [Gogs](https://gogs.io/) - 用 Go 编写的无痛自托管 Git 服务。([源代码](https://github.com/gogs/gogs)) `MIT` `Go`
- [Huly](https://huly.io) - 一体化项目管理平台（Linear、Jira、Slack、Notion、Motion 的替代品）。([演示](https://app.huly.io)、[源代码](https://github.com/hcengineering/platform)) `EPL-2.0` `Docker/K8S/Nodejs`
- [Ideon](https://www.theideon.com) - 围绕无限画布构建的项目工作空间；可将 GitHub、GitLab、Gitea 和 Forgejo 仓库与笔记、链接和任务一同嵌入，支持实时协作。([源代码](https://github.com/3xpyth0n/ideon)) `AGPL-3.0` `Docker`
- [Kaneo](https://kaneo.app/) - 专注于简洁和高效的项目管理平台。([演示](https://demo.kaneo.app/)、[源代码](https://github.com/usekaneo/kaneo)) `MIT` `K8S/Docker`
- [Leantime](https://leantime.io) - 面向小团队和初创企业的精益项目管理系统，帮助管理从构思到交付的项目。([源代码](https://github.com/leantime/leantime)) `AGPL-3.0` `PHP/Docker`
- [Mindwendel](https://www.mindwendel.com/) - 在团队内进行头脑风暴并为想法和思路投票。([演示](https://www.mindwendel.com)、[源代码](https://github.com/b310-digital/mindwendel)) `AGPL-3.0` `Docker/Elixir`
- [minimal-git-server](https://github.com/mcarbonne/minimal-git-server) - 带基础 CLI 的轻量级 git 服务器，用于管理仓库，支持多个账户并在容器中运行。`MIT` `Docker`
- [Octobox](https://octobox.io/) `⚠` - 夺回对你 GitHub 通知的控制权。([源代码](https://github.com/octobox/octobox)) `AGPL-3.0` `Ruby/Docker`
- [OneDev](https://onedev.io/) - 一体化 DevOps 平台。具有 Git 管理、问题跟踪和 CI/CD。简单而强大。([源代码](https://github.com/theonedev/onedev)) `MIT` `Java/Docker/K8S`
- [OpenProject](https://www.openproject.org) - 管理你的项目、任务和目标。通过工作包协作，并将它们链接到你在 Github 上的拉取请求。([源代码](https://github.com/opf/openproject)) `GPL-3.0` `Ruby/deb/Docker`
- [Paca](https://paca-ai.org) - AI 原生项目管理平台，AI 智能体与人类作为 Scrum 队友在同一看板和冲刺中协作。可通过配置文件和 WASM 插件配置（Jira、Trello、ClickUp 和 Monday 的替代品）。([源代码](https://github.com/Paca-AI/paca)) `Apache-2.0` `Docker/K8S`
- [Pagure](https://pagure.io/pagure) - 轻量、强大且灵活的以 git 为核心的托管平台，其功能为联邦式和去中心化开发奠定了基础。([演示](https://pagure.io/)) `GPL-2.0` `Docker/Python/deb`
- [Phorge](https://we.phorge.it/) - 社区驱动的平台，用于协作、管理、组织和审查软件开发项目。([源代码](https://we.phorge.it/source/phorge/)) `Apache-2.0` `PHP`
- [Plane](https://plane.so) - 以尽可能简单的方式追踪问题、史诗和产品路线图（JIRA、Linear 和 Height 的替代品）。([演示](https://app.plane.so)、[源代码](https://github.com/makeplane/plane)) `AGPL-3.0` `Docker`
- [ProjeQtOr](https://www.projeqtor.org/) - 完整、成熟的多用户项目管理系统，为项目各个阶段提供丰富的功能。([演示](https://demo.projeqtor.org/)、[源代码](https://sourceforge.net/p/projectorria/code/HEAD/tree/branches/)) `AGPL-3.0` `PHP`
- [Redmine](https://www.redmine.org/) - 灵活的项目管理 Web 应用。([源代码](https://svn.redmine.org/redmine/)) `GPL-2.0` `Ruby`
- [Review Board](https://www.reviewboard.org/) - 可扩展且友好的代码审查工具，适用于各种规模的项目和公司。([演示](https://demo.reviewboard.org/)、[源代码](https://github.com/reviewboard/reviewboard)) `MIT` `Python/Docker`
- [RhodeCode](https://rhodecode.com/) - 统一并简化 Git、Subversion 和 Mercurial 的仓库管理。([源代码](https://code.rhodecode.com/)) `AGPL-3.0` `Python`
- [Rukovoditel](https://www.rukovoditel.net/) - 可配置的开源项目管理 Web 应用。([源代码](https://www.rukovoditel.net/download.php)) `GPL-2.0` `PHP`
- [SCM Manager](https://www.scm-manager.org/) - 通过 http 分享和管理 Git、Mercurial 和 Subversion 仓库的最简单方式。([源代码](https://github.com/scm-manager/scm-manager)) `BSD-3-Clause` `Java/deb/Docker/K8S`
- [Smederee](https://smeder.ee) - 一个节俭的平台，致力于帮助人们利用 Darcs 版本控制系统的力量共同构建出色的软件。([源代码](https://smeder.ee/~jan0sch/smederee)) `AGPL-3.0` `Scala`
- [Sourcehut](https://sourcehut.org/) - 不带 javascript 的完整 Web git 界面。([演示](https://sr.ht/)、[源代码](https://git.sr.ht/~sircmpwn/git.sr.ht/tree)) `GPL-2.0` `Go`
- [Taiga](https://www.taiga.io/) - 基于看板和 Scrum 方法的敏捷项目管理工具。([源代码](https://github.com/kaleidos-ventures)) `MPL-2.0` `Docker/Python/Nodejs`
- [Titra](https://titra.io/) - 面向自由职业者和小团队的时间追踪方案。([源代码](https://github.com/titraio/titra)) `GPL-3.0` `Javascript/Docker`
- [Trac](https://trac.edgewall.org/) - Trac 是面向软件开发项目的增强型 wiki 和问题跟踪系统。`BSD-3-Clause` `Python/deb`
- [Traq](https://traq.io/) - 用 PHP 编写的项目管理和问题跟踪系统。([源代码](https://github.com/nirix/traq)) `GPL-3.0` `PHP/Nodejs`
- [Tuleap](https://www.tuleap.org/) - Tuleap 是一套用于规划、跟踪、编码和协作软件项目的自由套件。([源代码](https://tuleap.net/plugins/git/tuleap/tuleap/stable?p=tuleap%2Fstable.git&a=tree)) `GPL-2.0` `PHP`
- [UVDesk](https://www.uvdesk.com/) - UVDesk 社区版是一个面向服务、事件驱动、可扩展的开源工单系统，你的组织可以用它以你能想象的任何方式高效地为客户提供支持。([演示](https://demo.uvdesk.com/)、[源代码](https://github.com/uvdesk/community-skeleton)) `MIT` `PHP`
- [ZenTao](https://www.zentao.pm/) - 一个敏捷（scrum）项目管理系统/工具。([源代码](https://github.com/easysoft/zentaopms)) `AGPL-3.0` `PHP`


### 软件开发 - 测试 <a id="software-development---testing"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

用于[软件测试](https://en.wikipedia.org/wiki/Software_testing)的工具与软件。

- [Bencher](https://bencher.dev/) - 一套持续基准测试工具，旨在捕获 CI 中的性能退化。([源代码](https://github.com/bencherdev/bencher)) `MIT/Apache-2.0` `Rust`
- [Request Inbox](https://request-inbox.com/) - 收集并检查 HTTP 请求以进行测试和调试。创建和管理收件箱、捕获详细的请求数据、配置自定义响应。([演示](https://request-inbox.com/)、[源代码](https://github.com/jesusnoseq/request-inbox)) `Apache-2.0` `Docker`
- [WebHook Tester](https://github.com/tarampampam/webhook-tester) - 用于测试 WebHook 等的强大工具。`MIT` `Docker/Go/deb/K8S`


### 静态站点生成器 <a id="static-site-generators"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[静态站点生成器](https://en.wikipedia.org/wiki/Web_template_system#Static_site_generators)基于原始数据、纯文本文件和一组模板生成完整的静态 HTML 网站。

**请访问 [staticsitegenerators.bevry.me](https://staticsitegenerators.bevry.me)、[staticgen.com](https://www.staticgen.com)**

_相关：[博客平台](#blogging-platforms)、[相册](#photo-galleries)、[内容管理系统（CMS）](#content-management-systems-cms)_



### 任务管理与待办清单 <a id="task-management--to-do-lists"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[任务管理](https://en.wikipedia.org/wiki/Task_management#Task_management_software)软件。

_相关：[软件开发 - 项目管理](#software-development---project-management)、[工单系统](#ticketing)_

- [4ga Boards](https://4gaboards.com) - 直观明了的实时看板管理，用于直观的任务跟踪。具有优雅的深色模式、可折叠的待办清单和多任务工具，为你的团队生产力提速。([演示](https://demo.4gaboards.com)、[源代码](https://github.com/RARgames/4gaBoards)) `MIT` `Nodejs/Docker/K8S`
- [AppFlowy](https://appflowy.io/) - 为不同项目建立详细的待办清单，同时追踪每一项的状态。开源 Notion 替代品。([源代码](https://github.com/AppFlowy-IO/appflowy)) `AGPL-3.0` `Rust/Dart/Docker`
- [dayGLANCE](https://dayglance.app) - 日程规划器，具有拖拽式时间块、收件箱、重复任务、习惯、例程、目标、项目和番茄钟专注模式，以及 iCal 和 CalDAV 日历同步。数据留在浏览器中，可选 WebDAV 或 GLANCEvault 同步。([源代码](https://github.com/krelltunez/dayGLANCE)、[客户端](https://github.com/glance-apps/glance-vault)) `MIT` `Javascript/Docker`
- [Donetick](https://donetick.com) - 面向个人和家庭使用的任务和家务管理工具，具有高级调度、灵活分配和群组共享能力、详细历史、通过 API 实现自动化，设计简洁现代。([演示](https://app.donetick.com/)、[源代码](https://github.com/donetick/donetick)) `AGPL-3.0` `Go/Docker`
- [Focus Flow](https://github.com/francesco-gaglione/focus_flow_cloud) - 使用番茄工作法进行时间管理的完整生态。`MIT` `Docker/K8S`
- [HamsterBase Tasks](https://tasks.hamsterbase.com) - 帮助整理想法并构建出色成果的工具。规划、组织、构建并交付。([演示](https://tasks-app.hamsterbase.com)、[源代码](https://github.com/hamsterbase/tasks)) `AGPL-3.0` `Docker`
- [Kan](https://kan.bn/) - 灵活的看板应用，帮助你组织工作、追踪进度并交付成果（Trello 的替代品）。([源代码](https://github.com/kanbn/kan)) `AGPL-3.0` `Docker`
- [Kanboard](https://kanboard.org/) - 简单的可视化任务看板。([源代码](https://github.com/kanboard/kanboard)) `MIT` `PHP`
- [Listaway](https://github.com/jeffrpowell/listaway/) - 用于创建和公开分享条目清单的清单管理应用。支持认证、管理工具、条目备注和优先级，以及可选加入的、使用随机 URL 的公开只读链接（Amazon Lists 的替代品）。([源代码](https://github.com/jeffrpowell/listaway)) `MIT` `Docker`
- [myTinyTodo](https://www.mytinytodo.net/) - 以 AJAX 风格管理待办清单的简单方式。使用 PHP、jQuery、SQLite/MySQL。符合 GTD 规范。([演示](https://www.mytinytodo.net/demo/)、[源代码](https://github.com/maxpozdeev/mytinytodo/)) `GPL-2.0` `PHP`
- [Nullboard](https://github.com/apankrat/nullboard) - 单页极简看板；紧凑、高度可读且使用快捷。([演示](https://nullboard.io/preview)) `BSD-2-Clause` `Javascript`
- [OpenHabitTracker](https://openhabittracker.net) - 追踪习惯、任务和笔记，具有时间追踪、日历视图和完成统计。([演示](https://pwa.openhabittracker.net)、[源代码](https://github.com/Jinjinov/OpenHabitTracker)) `GPL-3.0` `Docker`
- [Our Shopping List](https://codeberg.org/nanawel/our-shopping-list) - 简单的共享清单应用，包括购物清单和任何其他需要协作使用的小型待办清单。([演示](https://osl.lanterne-rouge.info/)) `AGPL-3.0` `Docker`
- [Super Productivity](https://super-productivity.com) - 高级待办清单应用，集成时间盒和时间追踪功能。可与 Jira、GitHub、GitLab、Redmine 和 OpenProject 集成。([源代码](https://github.com/super-productivity/super-productivity)) `MIT` `Docker`
- [Task Keeper](https://github.com/nymanjens/piga) - 面向高级用户的清单编辑器，由自托管服务器支持。`Apache-2.0` `Scala`
- [Tasks.md](https://github.com/BaldissaraMatheus/Tasks.md) - 自托管、基于文件的任务管理看板，支持 Markdown 语法。`MIT` `Docker`
- [Taskwarrior](https://taskwarrior.org/) - Taskwarrior 是一款自由开源软件，可从命令行管理你的 TODO 清单。它灵活、快速、高效且不打扰。它完成工作后就自动让开。([源代码](https://taskwarrior.org/download/#git)) `MIT` `C++`
- [Tellor](https://tellor.cc/) - 极简单用户看板待办应用。UI 干净、简化且紧凑。可从 Trello 导入看板。([演示](https://tellor.cc/demo/?b=18486f63be6bb5f2)、[源代码](https://github.com/Voldrix/Tellor)) `MIT` `PHP`
- [Tracks](https://www.getontracks.org/) - 基于 Web 的应用，帮助你实践 David Allen 的 [Getting Things Done™](https://en.wikipedia.org/wiki/Getting_Things_Done) 方法。([源代码](https://github.com/TracksApp/tracks)) `GPL-2.0` `Ruby`
- [tududi](https://tududi.com/) - 具有层级结构、智能重复任务和无缝 Telegram 集成的任务管理工具。([源代码](https://github.com/chrisvel/tududi)) `MIT` `Docker`
- [Vikunja](https://vikunja.io/) - 用来整理生活的待办应用。([演示](https://try.vikunja.io/login)、[源代码](https://github.com/go-vikunja/vikunja)) `AGPL-3.0/GPL-3.0` `Go`
- [Wekan](https://wekan.github.io/) - 类似 Trello 的看板。([源代码](https://github.com/wekan/wekan)) `MIT` `Nodejs`
- [Will Be Done](https://will-be-done.app/) - 离线优先的任务管理器，具有每周规划、项目看板、实时同步、Vim 快捷键、桌面快速添加，以及从流行任务管理器导入功能（TickTick、Todoist 的替代品）。([演示](https://demo.will-be-done.app/)、[源代码](https://github.com/will-be-done/will-be-done)) `AGPL-3.0` `Docker/Nodejs`


### 工单系统 <a id="ticketing"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

用于帮助跟踪用户请求、缺陷与缺失功能的[服务台](https://en.wikipedia.org/wiki/Help_desk_software)、[缺陷](https://en.wikipedia.org/wiki/Bug_tracking_system)与[问题](https://en.wikipedia.org/wiki/Issue_tracking_system)跟踪软件。

_相关：[任务管理与待办清单](#task-management--to-do-lists)、[软件开发 - 项目管理](#software-development---project-management)_

- [BugPin](https://bugpin.io) - 面向 Web 应用的可视化缺陷上报和工单工具。([源代码](https://github.com/aranticlabs/bugpin)) `AGPL-3.0/MIT` `Docker`
- [Bugzilla](https://www.bugzilla.org/) - 通用缺陷跟踪和测试工具，最初由 Mozilla 项目开发和使用的。([源代码](https://github.com/bugzilla/bugzilla)) `MPL-2.0` `Perl`
- [Frappe Helpdesk](https://frappe.io/helpdesk) - 帮助台软件，帮助你简化公司的支持工作，提供简易设置、干净的界面和高效解决客户查询的自动化工具。([源代码](https://github.com/frappe/helpdesk)) `AGPL-3.0` `Docker`
- [FreeScout](https://freescout.net/) - 基于电子邮件的客户支持应用、帮助台和共享邮箱（Zendesk 和 Help Scout 的替代品）。([演示](https://demo.freescout.net/login)、[源代码](https://github.com/freescout-help-desk/freescout)) `AGPL-3.0` `PHP/Docker`
- [GlitchTip](https://glitchtip.com) - 错误跟踪应用，用于收集你的应用报告的错误。([源代码](https://gitlab.com/glitchtip/glitchtip)) `MIT` `Python/Docker/K8S`
- [ITFlow](https://itflow.org) - 面向 MSP（托管服务提供商）的客户 IT 文档、工单、发票和会计。([演示](https://demo.itflow.org)、[源代码](https://github.com/itflow-org/itflow)) `GPL-3.0` `PHP`
- [Libredesk](https://libredesk.io/) - 现代全渠道客户支持台。在单个二进制文件中提供实时聊天、电子邮件等。([演示](https://demo.libredesk.io)、[源代码](https://github.com/abhinavxd/libredesk)) `AGPL-3.0` `Docker/Go/Nodejs`
- [MantisBT](https://www.mantisbt.org/) - 缺陷跟踪器，最适合软件开发。([演示](https://www.mantisbt.org/bugs/my_view_page.php)、[源代码](https://github.com/mantisbt/mantisbt)) `GPL-2.0` `PHP`
- [OTOBO](https://otobo.io/en/) - 基于 Web 的灵活工单系统，用于客户服务、帮助台、IT 服务管理。([演示](https://otobo.io/en/service-management-plattform/otobo-demo/)、[源代码](https://github.com/RotherOSS/otobo)) `GPL-3.0` `Perl/Docker`
- [Request Tracker](https://www.bestpractical.com/rt/) - 企业级问题跟踪系统。([源代码](https://github.com/bestpractical/rt)) `GPL-2.0` `Perl`
- [Roundup Issue Tracker](https://www.roundup-tracker.org/) - 易于使用和安装的问题跟踪系统，具有命令行、Web、REST、XML-RPC 和电子邮件界面。以灵活为设计理念——不仅仅是另一个缺陷跟踪器。([源代码](https://www.roundup-tracker.org/code.html)) `MIT/ZPL-2.0` `Python/Docker`
- [Rustrak](https://rustrak.github.io/rustrak/) - 兼容 Sentry SDK 的错误跟踪服务器，空闲时使用 32 MB 内存，采用 SQLite 存储。([源代码](https://github.com/rustrak/rustrak)) `GPL-3.0` `Rust/Docker`
- [Zammad](https://zammad.org/) - 易于使用但功能强大的支持和工单系统。([源代码](https://github.com/zammad/zammad)) `AGPL-3.0` `Ruby/deb`


### 时间追踪 <a id="time-tracking"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[时间追踪软件](https://en.wikipedia.org/wiki/Time-tracking_software)是一类允许用户记录在任务或项目上所花费时间的计算机软件。

- [ActivityWatch](https://activitywatch.net) - 自动追踪你在设备上花费时间的方式。([源代码](https://github.com/ActivityWatch/activitywatch)) `MPL-2.0` `Python`
- [Beaver Habit Tracker](https://github.com/daya0576/beaverhabits) - 习惯追踪应用，在稍纵即逝的人生中留住珍贵时刻。([演示](https://beaverhabits.com/demo)) `BSD-3-Clause` `Docker`
- [Ever Gauzy](https://gauzy.co) - 面向协作、按需和共享经济的开放业务管理平台（ERP/CRM/HRM/ATS/PM）。([演示](https://demo.gauzy.co)、[源代码](https://github.com/ever-co/ever-gauzy)) `AGPL-3.0` `Docker/Nodejs`
- [Kimai](https://www.kimai.org/) - 追踪工作时间并按需打印你的活动摘要。([演示](https://www.kimai.org/demo/)、[源代码](https://github.com/kimai/kimai)) `AGPL-3.0` `PHP`
- [solidtime](https://www.solidtime.io) - 面向自由职业者和机构的现代时间追踪应用。([源代码](https://github.com/solidtime-io/solidtime)) `AGPL-3.0` `Docker`
- [TimeTagger](https://timetagger.app) - 基于交互式时间线和强大报表的开源时间追踪器。([演示](https://timetagger.app/app/demo)、[源代码](https://github.com/almarklein/timetagger)) `GPL-3.0` `Python`
- [TimeTracker](https://timetracker.drytrix.com/) - 跨项目和客户追踪时间，具有计时器、看板任务、CRM、开支追踪、多币种发票（PDF、Peppol/ZugFerd 电子发票）、报表、OIDC/SSO 和 REST API。([源代码](https://github.com/drytrix/TimeTracker)) `GPL-3.0` `Docker`
- [Traggo](https://traggo.net/) - Traggo 是一个基于标签的时间追踪工具。在 Traggo 中没有任务，只有带标签的时间段。([源代码](https://github.com/traggo/server)) `GPL-3.0` `Docker/Go`
- [Wakapi](https://wakapi.dev/) - 用于统计编码的追踪工具，与 WakaTime 兼容。([源代码](https://github.com/muety/wakapi)) `GPL-3.0` `Go/Docker`
- [Ziit](https://ziit.app) - 代码时间追踪的瑞士军刀（WakaTime 的替代品）。([源代码](https://github.com/0pandadev/ziit)) `AGPL-3.0` `Docker`


### 旅行组织 <a id="travel-organization"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

用于记录预订、查看行程、规划活动并追踪费用的旅行组织软件。

_相关：[预约与日程安排](#booking-and-scheduling)、[地图与全球定位系统（GPS）](#maps-and-global-positioning-system-gps)_

- [Surmai](https://surmai.app/) - 协作式个人和家庭旅行组织工具。([演示](https://demo.surmai.app)、[源代码](https://github.com/rohitkumbhar/surmai)) `MIT` `Docker`


### 短链接服务 <a id="url-shorteners"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[短链接](https://en.wikipedia.org/wiki/URL_shortening)是指将 [URL](https://en.wikipedia.org/wiki/Uniform_Resource_Locator) 大幅缩短，同时仍能指向目标页面。在搭建短链接服务之前，请先了解短链接的[缺点](https://en.wikipedia.org/wiki/URL_shortening#Disadvantages)。

- [bit](https://github.com/sjdonado/bit) - 快速、轻量、资源高效的编译型 URL 短链服务。`MIT` `Docker/Crystal`
- [Chhoto URL](https://chhoto.link) - 简单、闪电般快速且无冗余的 URL 短链服务（simply-shorten 的分支）。([演示](https://github.com/SinTan1729/chhoto-url?tab=readme-ov-file#demo)、[源代码](https://github.com/SinTan1729/chhoto-url)、[客户端](https://github.com/SinTan1729/chhoto-url/blob/main/TOOLS.md)) `MIT` `Rust/Docker`
- [clink](https://git.crueter.xyz/crueter/clink) - 用纯 C 编写的超极简短链服务，专注于小巧的可执行文件体积、可移植性和易于配置。([演示](https://short.crueter.xyz)) `AGPL-3.0` `C`
- [Flink](https://gitlab.com/rtraceio/web/flink) - 创建二维码、为你的网站生成可嵌入的链接预览，并抓取/爬取元数据。([演示](https://flink.is)) `MIT` `Docker`
- [Kutt](https://kutt.to) - 现代 URL 短链服务，支持自定义域名和自定义 URL。([演示](https://kutt.to)、[源代码](https://github.com/thedevs-network/kutt)) `MIT` `Nodejs/Docker`
- [rs-short](https://git.42l.fr/42l/rs-short) - 用 Rust 编写的轻量级短链服务，具有缓存、垃圾机器人防护和钓鱼检测等功能。([演示](https://s.42l.fr/)) `MPL-2.0` `Rust`
- [Shlink](https://shlink.io) - 带 REST API 和命令行界面的 URL 短链服务。包含官方渐进式 Web 应用和 Docker 镜像。([源代码](https://github.com/shlinkio/shlink)、[客户端](https://shlink.io/apps)) `MIT` `PHP/Docker`
- [Simple-URL-Shortener](https://github.com/azlux/Simple-URL-Shortener) - KISS 原则的 URL 短链服务，公开或私有（带账户）。极简且轻量。无依赖。([演示](https://u.azlux.fr)) `MIT` `PHP`
- [YOURLS](https://yourls.org/) - YOURLS 是一组 PHP 脚本，让你运行自己的 URL 短链服务。功能包括密码保护、URL 自定义、书签小工具、统计、API、插件、jsonp。([源代码](https://github.com/YOURLS/YOURLS)) `MIT` `PHP`


### 视频监控 <a id="video-surveillance"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

视频监控，又称[闭路电视（CCTV）](https://en.wikipedia.org/wiki/Closed-circuit_television)，是在需要额外安全防护或持续监控的区域使用摄像头进行监视。

_相关：[媒体流 - 视频流](#media-streaming---video-streaming)_

- [Bluecherry](https://github.com/bluecherrydvr/bluecherry-apps) - 闭路电视（CCTV）软件应用，支持 IP 和模拟摄像头。`GPL-2.0` `PHP`
- [Frigate](https://frigate.video/) - 使用本地处理的 AI 监控你的安防摄像头。([源代码](https://github.com/blakeblackshear/frigate)) `MIT` `Docker/Python/Nodejs`
- [motionEye](https://github.com/motioneye-project/motioneye) - 软件 Motion 的在线界面，Motion 是一个带运动检测的视频监控程序。`GPL-3.0` `Python/Docker`
- [Secluso](https://secluso.com) - 面向 Raspberry Pi 的私人 DIY 家庭安防摄像头系统，具有端到端加密的远程访问和用于实时视频、告警和录像回放的移动应用。([源代码](https://github.com/secluso/core)) `GPL-3.0` `Rust`
- [SentryShot](https://codeberg.org/SentryShot/sentryshot) - 视频监控管理系统。`GPL-2.0` `Docker/Rust`
- [Strix](https://github.com/eduard256/Strix) - 自动发现 IP 摄像头可用的流地址，并生成可直接使用的 Frigate 和 go2rtc 配置。`MIT` `Go/Docker`
- [Viseron](https://viseron.netlify.app/) - 自托管、纯本地的 NVR 和 AI 计算机视觉软件。具有物体检测、运动检测、人脸识别等功能，让你能够照看你的家、办公室或任何你想监控的地方。([源代码](https://github.com/roflcoopter/viseron)) `MIT` `Docker`
- [Zoneminder](https://www.zoneminder.com/) - 闭路电视（CCTV）软件应用，支持 IP、USB 和模拟摄像头。([源代码](https://github.com/ZoneMinder/ZoneMinder)) `GPL-2.0` `PHP/deb`


### VPN <a id="vpn"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[虚拟专用网络（VPN）](https://en.wikipedia.org/wiki/Virtual_private_network)将专用网络扩展到公共网络之上，使用户能够跨共享或公共网络发送和接收数据，如同其计算设备直接连接到该专用网络一样。

**请访问 [awesome-sysadmin/VPN](https://github.com/awesome-foss/awesome-sysadmin#vpn)**

_另见：[Awesome-Tunneling](https://github.com/anderspitman/awesome-tunneling)_



### Web 服务器 <a id="web-servers"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

Web 服务器与反向代理。[Web 服务器](https://en.wikipedia.org/wiki/Web_server)是一种软件及底层硬件，通过 [HTTP](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol)（为分发网页内容而创建的网络协议）或其安全变体 [HTTPS](https://en.wikipedia.org/wiki/HTTPS) 接受请求。[反向代理](https://en.wikipedia.org/wiki/Reverse_proxy)是一种代理服务器，对任何客户端而言看起来都是普通的 Web 服务器，但实际上仅充当中介，将请求转发给一个或多个普通 Web 服务器。

_相关：[代理](#proxy)_

- [Algernon](https://algernon.roboticoverlords.org/) - 小型自包含的纯 Go Web 服务器，支持 Lua、Markdown、HTTP/2、QUIC、Redis 和 PostgreSQL。([源代码](https://github.com/xyproto/algernon)) `BSD-3-Clause` `Go/Docker`
- [Apache HTTP Server](https://httpd.apache.org/) - 安全、高效且可扩展的服务器，按当前 HTTP 标准提供 HTTP 服务。([源代码](https://svn.apache.org/repos/asf/httpd/httpd/trunk/)) `Apache-2.0` `C/deb/Docker`
- [BunkerWeb](https://www.bunkerweb.io) - 下一代 Web 应用防火墙（WAF），将保护你的 Web 服务。([演示](https://demo.bunkerweb.io)、[源代码](https://github.com/bunkerity/bunkerweb)、[客户端](https://docs.bunkerweb.io/latest/plugins/)) `AGPL-3.0` `deb/Docker/K8S/Python`
- [Caddy](https://caddyserver.com/) - 强大、企业级就绪的开源 Web 服务器，具有自动 HTTPS。([源代码](https://github.com/caddyserver/caddy)) `Apache-2.0` `Go/deb/Docker`
- [Ferron](https://ferron.sh/) - 用 Rust 编写的快速、内存安全的 Web 服务器。([源代码](https://github.com/ferronweb/ferron)) `MIT` `Rust/Docker/deb`
- [go-doxy](https://github.com/yusing/godoxy) - 轻量、简单且高性能的反向代理，具有 WebUI、Docker 集成、基于流量自动关闭/启动容器。`MIT` `Docker/Go`
- [HAProxy](https://www.haproxy.org/) - 非常快速且可靠的反向代理，为基于 TCP 和 HTTP 的应用提供高可用性、负载均衡和代理。([源代码](https://git.haproxy.org/?p=haproxy.git;a=tree)) `GPL-2.0` `C/deb/Docker`
- [Lighttpd](https://www.lighttpd.net/) - 安全、快速、合规且非常灵活的 Web 服务器，已针对高性能环境优化。([源代码](https://git.lighttpd.net/lighttpd/lighttpd1.4)) `BSD-3-Clause` `C/deb/Docker`
- [Nginx Proxy Manager](https://nginxproxymanager.com/) - 用于管理 Nginx 代理主机的 Docker 容器，具有简单而强大的界面。([源代码](https://github.com/NginxProxyManager/nginx-proxy-manager)) `MIT` `Docker`
- [NGINX](https://nginx.org/en/) - HTTP 和反向代理服务器、邮件代理服务器以及通用 TCP/UDP 代理服务器。([源代码](https://github.com/nginx/nginx)) `BSD-2-Clause` `C/deb/Docker`
- [Pangolin](https://digpangolin.com/) - 身份感知的隧道反向代理，具有仪表盘 UI、访问控制和基于 WireGuard 的隧道（Cloudflare Tunnel、Tailscale 的替代品）。([源代码](https://github.com/fosrl/pangolin)) `AGPL-3.0` `Docker`
- [Pomerium](https://www.pomerium.io) - 身份感知的反向代理，是现已过时的 oauth_proxy 的继任者。它在将你的请求代理到后端之前插入一个 OAuth 步骤，以便你可以安全地将自托管网站暴露到公共互联网。([源代码](https://github.com/pomerium/pomerium)) `Apache-2.0` `Go/Docker`
- [SafeLine](https://waf.chaitin.com/) - Web 应用防火墙/反向代理，保护你的 Web 应用免受攻击和漏洞利用。([演示](https://demo.waf.chaitin.com/)、[源代码](https://github.com/chaitin/SafeLine)) `GPL-3.0` `Docker`
- [Static Web Server](https://static-web-server.net/) - 跨平台、高性能且异步的静态文件服务 Web 服务器。([源代码](https://github.com/static-web-server/static-web-server)) `Apache-2.0/MIT` `Rust/Docker`
- [SWAG (Secure Web Application Gateway)](https://github.com/linuxserver/docker-swag) - 带 PHP 支持的 Nginx Web 服务器和反向代理，内置 Certbot（Let's Encrypt）客户端和 fail2ban 集成。`GPL-3.0` `Docker`
- [Traefik](https://traefik.io/) - HTTP 反向代理和负载均衡器，让部署微服务变得简单。([源代码](https://github.com/traefik/traefik)) `MIT` `Go/Docker`
- [UUSEC WAF](https://waf.uusec.com/) - 业界领先的高性能、AI 和语义技术 Web 应用防火墙及 API 安全网关（nginx 的分支）。([源代码](https://github.com/Safe3/uusec-waf)) `GPL-3.0` `C/Lua/Docker`
- [Vinyl Cache](https://vinyl-cache.org/) - Web 应用加速器/缓存 HTTP 反向代理（前身为 Varnish）。([源代码](https://code.vinyl-cache.org/vinyl-cache/vinyl-cache)) `BSD-2-Clause` `Go/deb/Docker`
- [Zoraxy](https://zoraxy.aroz.org/) - 通用 HTTP 反向代理和转发工具。([源代码](https://github.com/tobychui/zoraxy)) `AGPL-3.0` `Go/Docker`


### Wiki <a id="wikis"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[Wiki](https://en.wikipedia.org/wiki/Wiki)是由其受众通过网页浏览器直接协作编辑和管理的出版物。

_相关：[笔记与编辑器](#note-taking--editors)、[静态站点生成器](#static-site-generators)、[知识管理工具](#knowledge-management-tools)_

_另见：[Wikimatrix](https://www.wikimatrix.org/)、[List of wiki software - Wikipedia](https://en.wikipedia.org/wiki/List_of_wiki_software)、[Comparison of wiki software - Wikipedia](https://en.wikipedia.org/wiki/Comparison_of_wiki_software)_

- [AmuseWiki](https://amusewiki.org/) - Amusewiki 基于 Emacs Muse 标记，与原始实现大体兼容。它可作为只读站点、受审核的 wiki、完全开放的 wiki，甚至私人站点运行。([源代码](https://github.com/melmothx/amusewiki)) `GPL-1.0` `Perl/Docker`
- [BookStack](https://www.bookstackapp.com/) - 组织并存储信息。以书籍的形式存储文档。([演示](https://www.bookstackapp.com/#demo)、[源代码](https://codeberg.org/bookstack/bookstack)) `MIT` `PHP/Docker`
- [django-wiki](https://github.com/django-wiki/django-wiki) - 具有复杂功能的 wiki 系统，便于简单集成且界面出色。有风格地存储你的知识：使用 django 模型。([演示](https://demo.django-wiki.org/)) `GPL-3.0` `Python`
- [docmost Community Edition](https://docmost.com/) - 协作式 wiki 和文档软件（Confluence、Notion 的替代品）。([源代码](https://github.com/docmost/docmost)) `AGPL-3.0` `Docker/Nodejs`
- [Documize](https://documize.com) - 现代文档 + wiki 软件，内置工作流，单一二进制可执行文件，只需自备 MySQL/Percona。([源代码](https://github.com/documize/community)) `AGPL-3.0` `Go`
- [Dokuwiki](https://www.dokuwiki.org/DokuWiki) - 易于使用、轻量、符合标准的 wiki 引擎，语法简单，允许在 wiki 之外读取数据。所有数据以纯文本文件存储，因此无需数据库。([源代码](https://github.com/dokuwiki/dokuwiki)) `GPL-2.0` `PHP`
- [Feather Wiki](https://feather.wiki) - 一个闪电般快速且可无限扩展的工具，用于创建个人非线性笔记本、数据库和 wiki，完全自包含、在浏览器中运行，体积仅 58 KB。([演示](https://feather.wiki/?page=gallery#wikis)、[源代码](https://codeberg.org/Alamantus/FeatherWiki)、[客户端](https://feather.wiki/?page=gallery#extensions)) `AGPL-3.0` `Javascript`
- [Gitit](https://github.com/jgm/gitit) - wiki 程序，将页面和上传的文件存储在 git 仓库中，之后可使用 VCS 命令行工具或 wiki 的 Web 界面进行修改。`GPL-2.0` `Haskell`
- [LeafWiki](https://github.com/perber/leafwiki) - 为以文件夹而非信息流思考的人打造的快速 wiki。编辑快速。树形导航。磁盘上的 Markdown。([演示](https://demo.leafwiki.com)) `MIT` `Docker/Go`
- [Mediawiki](https://www.mediawiki.org/wiki/MediaWiki) - 为 Wikipedia 及所有其他维基媒体项目提供支持的 wiki 软件包，每月服务数亿用户。([演示](https://en.wikipedia.org/wiki/Main_Page)、[源代码](https://phabricator.wikimedia.org/source/mediawiki/)) `GPL-2.0` `PHP`
- [Otter Wiki](https://otterwiki.com/) - 使用 markdown 的简单易用 wiki 软件。([源代码](https://github.com/redimp/otterwiki)) `MIT` `Docker`
- [PmWiki](https://www.pmwiki.org) - 基于 wiki 的协作创建和维护网站的系统。`GPL-3.0` `PHP`
- [Raneto](https://raneto.com/) - 使用静态 Markdown 文件的知识库平台。([源代码](https://github.com/ryanlelek/Raneto)) `MIT` `Nodejs`
- [TiddlyWiki](https://tiddlywiki.com/) - 可复用的非线性个人 Web 笔记本。([源代码](https://github.com/TiddlyWiki/TiddlyWiki5)) `BSD-3-Clause` `Nodejs`
- [Tiki](https://tiki.org/HomePage) - 内置功能最丰富的 Wiki CMS Groupware。([演示](https://tiki.org/Try-Tiki)、[源代码](https://gitlab.com/tikiwiki/tiki)) `LGPL-2.1` `PHP`
- [W](https://w.club1.fr) - 轻量级、多用户、扁平文件数据库的 Wiki 引擎。快速创建页面并在你的 Web 浏览器中使用 Mardown/HTML/CSS/JS 编辑它们。与其他 wiki 的主要区别在于鼓励你单独自定义每个页面的样式。([源代码](https://github.com/vincent-peugnet/wcms)) `AGPL-3.0` `PHP`
- [WackoWiki](https://wackowiki.org/) - WackoWiki 是一个轻量且易于安装的多语言 Wiki 引擎。([源代码](https://github.com/WackoWiki/wackowiki)) `BSD-3-Clause` `PHP`
- [Wiki-Go](https://leomoon.com/downloads/web-apps/wiki-go/) - 现代、功能丰富的无数据库扁平文件 wiki 平台。([演示](https://wikigo.leomoon.com)、[源代码](https://github.com/leomoon-studios/wiki-go)) `GPL-3.0` `Go/Docker`
- [Wiki.js](https://js.wiki/) - 使用 Git 和 Markdown 的现代、轻量且强大的 wiki 应用。([演示](https://docs.requarks.io)、[源代码](https://github.com/Requarks/wiki)) `AGPL-3.0` `Nodejs/Docker/K8S`
- [WikiDocs](https://www.wikidocs.app/) - 无数据库的 markdown 扁平文件 wiki 引擎。([源代码](https://github.com/Zavy86/WikiDocs)) `MIT` `PHP/Docker`
- [WiKiss](https://wikiss.tuxfamily.org/) - Wiki，易于使用和安装。([源代码](https://svnweb.tuxfamily.org/listing.php?repname=wikiss/svn&path=%2F&sc=0)) `GPL-2.0` `PHP`
- [XWiki](https://www.xwiki.org) - 第二代 wiki，允许用户通过强大的基于扩展的架构来扩展其功能。([演示](https://www.xwikiplayground.org/xwiki/bin/view/Main/)、[源代码](https://github.com/xwiki/xwiki-platform)) `LGPL-2.1` `Java/Docker/deb`
- [Zim](https://zim-wiki.org/) - 图形化文本编辑器，用于维护 wiki 页面的集合。每个页面都可以包含指向其他页面的链接、简单格式和图像。([源代码](https://github.com/zim-desktop-wiki/zim-desktop-wiki)) `GPL-2.0` `Python/deb`


--------------------

## 许可证列表 <a id="list-of-licenses"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

- `0BSD` - [BSD 零条款许可](https://spdx.org/licenses/0BSD.html)
- `AAL` - [署名保证许可](https://spdx.org/licenses/AAL.html)
- `AGPL-3.0` - [GNU Affero 通用公共许可证 3.0](https://spdx.org/licenses/AGPL-3.0.html)
- `Apache-2.0` - [Apache 许可证 2.0 版](https://spdx.org/licenses/Apache-2.0.html)
- `APSL-2.0` - [苹果公共源代码许可证 2.0 版](https://spdx.org/licenses/APSL-2.0.html)
- `Artistic-2.0` - [Artistic 许可证 2.0 版](https://spdx.org/licenses/Artistic-2.0.html)
- `Beerware` - [啤酒软件许可](https://spdx.org/licenses/Beerware.html)
- `BSD-2-Clause` - [BSD 2 条款“简化版”](https://spdx.org/licenses/BSD-2-Clause.html)
- `BSD-2-Clause-FreeBSD` - [BSD 2 条款 FreeBSD 许可](https://spdx.org/licenses/BSD-2-Clause-FreeBSD.html)
- `BSD-3-Clause` - [BSD 3 条款“新版”或“修订版”](https://spdx.org/licenses/BSD-3-Clause.html)
- `BSD-3-Clause-Attribution` - [带署名的 BSD 许可](https://spdx.org/licenses/BSD-3-Clause-Attribution.html)
- `BSD-4-Clause` - [BSD 4 条款“原始版”](https://spdx.org/licenses/BSD-4-Clause.html)
- `CAL-1.0` - [密码自主许可 1.0](https://spdx.org/licenses/CAL-1.0.html)
- `CC-BY-SA-3.0` - [知识共享 署名-相同方式共享 3.0 许可](https://spdx.org/licenses/CC-BY-SA-3.0.html)
- `CC-BY-SA-4.0` - [知识共享 署名-相同方式共享 4.0 许可](https://spdx.org/licenses/CC-BY-SA-4.0.html)
- `CC0-1.0` - [公有领域/知识共享 CC0 1.0](https://spdx.org/licenses/CC0-1.0.html)
- `CDDL-1.0` - [通用开发与发行许可](https://spdx.org/licenses/CDDL-1.0.html)
- `CECILL-B` - [CEA CNRS INRIA 自由软件许可](https://spdx.org/licenses/CECILL-B.html)
- `CPAL-1.0` - [通用公共署名许可 1.0 版](https://spdx.org/licenses/CPAL-1.0.html)
- `ECL-2.0` - [教育社区许可 2.0 版](https://spdx.org/licenses/ECL-2.0.html)
- `EPL-1.0` - [Eclipse 公共许可 1.0 版](https://spdx.org/licenses/EPL-1.0.html)
- `EPL-2.0` - [Eclipse 公共许可 2.0 版](https://spdx.org/licenses/EPL-2.0.html)
- `EUPL-1.2` - [欧盟公共许可 1.2](https://spdx.org/licenses/EUPL-1.2.html)
- `GPL-1.0` - [GNU 通用公共许可证 1.0](https://spdx.org/licenses/GPL-1.0.html)
- `GPL-2.0` - [GNU 通用公共许可证 2.0](https://spdx.org/licenses/GPL-2.0.html)
- `GPL-3.0` - [GNU 通用公共许可证 3.0](https://spdx.org/licenses/GPL-3.0.html)
- `IPL-1.0` - [IBM 公共许可](https://spdx.org/licenses/IPL-1.0.html)
- `ISC` - [互联网系统协会许可](https://spdx.org/licenses/ISC.html)
- `LGPL-2.1` - [GNU 宽通用公共许可证 2.1](https://spdx.org/licenses/LGPL-2.1.html)
- `LGPL-3.0` - [GNU 宽通用公共许可证 3.0](https://spdx.org/licenses/LGPL-3.0.html)
- `MIT` - [MIT 许可](https://spdx.org/licenses/MIT.html)
- `MPL-1.1` - [Mozilla 公共许可 1.1 版](https://spdx.org/licenses/MPL-1.1.html)
- `MPL-2.0` - [Mozilla 公共许可](https://spdx.org/licenses/MPL-2.0.html)
- `OSL-3.0` - [开放软件许可 3.0](https://spdx.org/licenses/OSL-3.0.html)
- `Sendmail` - [Sendmail 许可](https://spdx.org/licenses/Sendmail.html)
- `Ruby` - [Ruby 许可](https://spdx.org/licenses/Ruby.html)
- `Unlicense` - [The Unlicense（无许可证）](https://spdx.org/licenses/Unlicense.html)
- `WTFPL` - [随你怎么用公共许可（WTFPL）](https://spdx.org/licenses/WTFPL.html)
- `Zlib` - [Zlib/libpng 许可](https://spdx.org/licenses/Zlib.html)
- `ZPL-2.0` - [Zope 公共许可 2.0](https://spdx.org/licenses/ZPL-2.0.html)


--------------------

## 反特性 <a id="anti-features"></a>

- `⚠ ` - 依赖用户无法控制的专有服务

--------------------

## 外部链接 <a id="external-links"></a>

**[`^        返回顶部        ^`](#awesome-selfhosted)**

- 用于发现/筛选 awesome-selfhosted 应用的替代前端/门户：[awweso.me](https://awweso.me/)、[awesome-web.theravenhub](https://awesome-web.theravenhub.com/browse.html)、[awesomehub.web.app](https://awesomehub.js.org/list/selfhosted)
- [Awesome Sysadmin](https://github.com/awesome-foss/awesome-sysadmin) - 精选的优质开源系统管理资源列表。
- 各种以隐私与去中心化为目标的软件列表：[PRISM Break](https://prism-break.org/en/)、[privacytools.io](https://www.privacytools.io/)、[Alternative Internet](https://redecentralize.github.io/alternative-internet/)、[Libre Projects](https://libreprojects.net/)、[Easy Indie App](https://easyindie.app)
- 其他 Awesome 列表：[Awesome Big Data](https://github.com/0xnr/awesome-bigdata)、[Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets)
- 动态域名服务：[Afraid.org](https://freedns.afraid.org/domain/registry/)、[Pagekite](https://pagekite.net/)
- 社区/论坛：[lemmy.world 上的 /c/selfhosted](https://lemmy.world/c/selfhosted)、[lemmy.ml 上的 /c/selfhost](https://lemmy.ml/c/selfhost)、[reddit 上的 /r/selfhosted](https://old.reddit.com/r/selfhosted/)、[/r/selfhosted Matrix 频道](https://matrix.to/#/#selfhosted:selfhosted.chat)、[reddit 上的 /r/homelab](https://old.reddit.com/r/homelab/)、[IndieWeb](https://indieweb.org/)
- [theme.park](https://theme-park.dev/) - 为 50 个自托管应用提供的主题/皮肤集合！([源代码](https://github.com/GilbN/theme.park/)) `MIT` `CSS`

--------------------

## 贡献指南 <a id="contributing"></a>

贡献指南见[此处](https://github.com/awesome-selfhosted/awesome-selfhosted-data/blob/master/CONTRIBUTING.md)。

## 许可证 <a id="license"></a>

本列表采用 [Creative Commons Attribution-ShareAlike 3.0 Unported](https://github.com/awesome-selfhosted/awesome-selfhosted/blob/master/LICENSE) 许可协议。
该许可协议的条款摘要见[此处](https://creativecommons.org/licenses/by-sa/3.0/)。
作者名单见 [AUTHORS](https://github.com/awesome-selfhosted/awesome-selfhosted-data/blob/master/AUTHORS) 文件。
