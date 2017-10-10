# Awesome Laravel [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://img.shields.io/travis/chiraggude/awesome-laravel/master.svg?style=flat)](https://travis-ci.org/chiraggude/awesome-laravel)

> 来自 Laravel 生态系统的精美书签，包，教程，视频和其他资源清单。

受 [ziadoz/awesome-php](https://github.com/ziadoz/awesome-php) 启发

## 目录

- [要点](#essentials)
- [代码片段](#code-snippets)
- [包](#packages)
- [热门包](#popular-packages)
- [开发环境设置](#development-setup)
- [应用主机](#application-hosting)
- [应用部署](#application-deployment)
- [文章, 教程, 博客等.](#articles-tutorials-blogs-etc)
- [视频](#videos)
- [会议](#conferences)
- [图书](#books)
- [起始项目](#starter-projects)
- [代码参考](#codebases-for-reference)
- [CMS 系统](#content-management-systems)
- [简讯](#newsletters)
- [播客](#podcasts)
- [社区](#community)
- [工作](#jobs)
- [托管开发工具](#hosted-development-tools)
- [其他](#miscellaneous)

## 要点

* [Laravel](https://laravel.com)
* [Laravel 文档](https://d.laravel-china.org/)
* [Laravel API 参考](https://laravel.com/api/master/)
* [Lumen](https://lumen.laravel.com)
* [Lumen 文档](https://lumen.laravel.com/docs)
* [Laracasts](https://laracasts.com)
* [Laravel 新闻](https://laravel-news.com)

## 代码片段

* [Laravel 手册](http://cheats.jesse-obrien.ca)
* [Laravel 5.1 LTS 手册 ](https://summerblue.github.io/laravel5-cheatsheet/) ([Chinese version](https://cs.phphub.org/))
* [Laravel 技巧](http://laravel-tricks.com/)
* [Laravel Recipes](http://laravel-recipes.com/)

## 包

* [Packagist](https://packagist.org/)
* [Laravel Collective](https://laravelcollective.com/)
* [Packalyst](http://packalyst.com/)
* [Cartalyst](https://cartalyst.com/)
* [Spatie](https://spatie.be/en/opensource/laravel)

## 热门包

> 以下是 Laravel 项目中经常使用，文档详尽并经过测试扩展包。 更详尽的 PHP 软件包列表，请从上述的 Package Repositories 中查找。

##### 开发工具

* [Scaffold Interface](https://github.com/amranidev/scaffold-interface) - 一个聪明的 CRUD 生成器
* [IDE Helper](https://github.com/barryvdh/laravel-ide-helper) - 为 IDE 自动完成生成辅助文件
* [Laravel 5 Extended Generators](https://github.com/laracasts/Laravel-5-Generators-Extended) - 扩展内置的文件生成
* [Laravel API/Scaffold/CRUD Generator](http://labs.infyom.com/laravelgenerator/) - APIs, CRUD 生成器
* [Laravel TestTools](https://chrome.google.com/webstore/detail/laravel-testtools/ddieaepnbjhgcbddafciempnibnfnakl) - 在使用应用时生成 Laravel 集成测试的 Chrome 扩展
* [Laravel API Documentation Generator](https://github.com/mpociot/laravel-apidoc-generator) - 自动从现有的 Laravel 路由中生成API 文档
* [Laravel Packager](https://github.com/Jeroen-G/Laravel-Packager) - 创建 Laravel 包的命令行工具
* [Workbench Export to Migrations](https://github.com/beckenrode/mysql-workbench-export-laravel-5-migrations) - 将模型导出到 Laravel 迁移的 Workbench 插件
* [Laravel Decomposer](https://github.com/lubusIN/laravel-decomposer) - 列出所有已安装的包、他们的依赖，App 和 Sevicer 详情=

##### 调试
* [Clockwork](https://github.com/itsgoingd/clockwork) -集成用于调试和分析应用程序的 Clockwork Chrome 扩展
* [Debug Bar](https://github.com/barryvdh/laravel-debugbar) - 集成 PHP Debug Bar 到 Laravel
* [Laravel 5 Log Viewer](https://github.com/rap2hpoutre/laravel-log-viewer) - Log 查看器
* [LogViewer](https://github.com/ARCANEDEV/LogViewer) - 为 Laravel 5 提供已一个日志查看器
* [LERN](https://github.com/tylercd100/lern#lern-laravel-exception-recorder-and-notifier) - LERN是一个 Laravel 5 扩展包，可将异常记录到数据库中，并向您发送通知
* [Mail Preview](https://github.com/themsaid/laravel-mail-preview) - 在浏览器或邮件客户端中预览发送的邮件
* [Laravel Tracy](https://github.com/recca0120/laravel-tracy) - 一个集成 Nette Tracy Debugger 的包
* [Laravel API Tester](https://github.com/asvae/laravel-api-tester) - 使用 Laravel 路由的类似 Postman 的工具

##### 认证授权

* [Bouncer](https://github.com/JosephSilber/bouncer) - 角色和权限
* [Laratrust](https://github.com/santigarcor/laratrust) - 角色、权限和群组
* [Entrust](https://github.com/Zizaco/entrust) - 基于角色的权限
* [JWT Auth](https://github.com/tymondesigns/jwt-auth) - API 使用的 JSON Web 令牌身份验证 
* [Laravel Permission](https://github.com/spatie/laravel-permission) - 将用户于角色和权限相关联
* [Defender](https://github.com/artesaos/defender) - 角色和权限
* [OAuth2 Server Laravel](https://github.com/lucadegasperi/oauth2-server-laravel) - OAuth 2.0 授权和资源服务器
* [Laravel Roles](https://github.com/romanbican/roles) - 角色和权限
* [Sentinel](https://github.com/cartalyst/sentinel) - 框架无关的认证和授权系统
* [Socialite](https://github.com/laravel/socialite) - 使用 Facebook, Google, Twitter 等进行开放授权
* [Socialite Providers 2.0](http://socialiteproviders.github.io/) - Socialite 的 100多个社会化认证提供商，支持 Lumen，支持国内常用的社交平台
* [Google2FA](https://github.com/antonioribeiro/google2fa) - Google 两部验证模块
* [Laravel User Verification](https://github.com/jrean/laravel-user-verification) - 处理用户验证流程并验证 Emai
* [Adldap2 Laravel](https://github.com/Adldap2/Adldap2-Laravel) - LDAP 认证与活动目录管理

##### Utilities

* [Artisan View](https://github.com/svenluijten/artisan-view) - 使用 Artisan 命令管理 Laravel 项目中的视图
* [Bootstrapper](https://github.com/patricktalmadge/bootstrapper/) - 创建 Bootstrap3  标记的类
* [Captcha](https://github.com/mewebstudio/captcha) - Laravel 5 图形验证码 - 防机器人图像验证码系统
* [Charts](https://github.com/ConsoleTVs/Charts) - 多库图表包来创建交互式图表
* [Datatable](https://github.com/Chumper/Datatable) - 集成 jQuery Datatables  插件的服务端和客户端
* [Eloquent Filter](https://github.com/Tucker-Eric/EloquentFilter) - 以 Eloquent 的方式 过滤 Laravel 模型和他们关系
* [Eloquent Sluggable](https://github.com/cviebrock/eloquent-sluggable) - 为 Eloquent 模型创建 Slug
* [Eloquent Sortable](https://github.com/spatie/eloquent-sortable) - 模型的排序行为
* [Presenter](https://github.com/laracasts/Presenter) - 模型的 Presenter
* [HTML](https://github.com/LaravelCollective/html) - Laravel 的 HTML 和 Form 构建工具
* [Hyn/multi-tenant](https://github.com/hyn/multi-tenant) - Flexible multi tenancy with secure separation of a.o. routes, assets and databases
* [Laravel 5 form builder](https://github.com/kristijanhusak/laravel-form-builder) - 受 Symfony 表单构建器启发的Laravel 表单构建器
* [Intervention Image](https://github.com/Intervention/image) - 用于创建、编辑、压缩图像的图像处理库
* [Laravel Activitylog](https://github.com/spatie/laravel-activitylog) - 在 Laravel 应用内记录活动
* [Laravel Auditing](https://github.com/owen-it/laravel-auditing) - Eloquent 模型审计，用于记录模型修改
* [Laravel Blade Javascript](https://github.com/spatie/laravel-blade-javascript) - 可导出变量到 JavaScript 的 Blade
* [Laravel Breadcrumbs](https://github.com/davejamesmiller/laravel-breadcrumbs) - 创建并管理面包屑导航
* [Laravel Collection Macros](https://github.com/spatie/laravel-collection-macros) - 一组方便的 collection 宏
* [Laravel Cookie Consent](https://github.com/spatie/laravel-cookie-consent) - 使 Laravel APP 遵守疯狂的 EU cookie law
* [Laravel Datatables](https://github.com/yajra/laravel-datatables) - Laravel 4|5 的  jQuery DataTables API
* [Laravel Dot Env Generator](https://github.com/mathiasgrimm/laravel-dot-env-gen) - 基于 项目源代码生成 .env.gen 文件
* [Laravel Excel](https://github.com/Maatwebsite/Laravel-Excel) - 导入和导出 Excel 与 CSV 文件
* [Laravel Failed Job Monitor](https://github.com/spatie/laravel-failed-job-monitor) - 队列任务失败时，发送通知
* [Laravel GeoIP](https://github.com/Torann/laravel-geoip) - 根据IP地址确定网站访问者的地理位置
* [Laravel Glide](https://github.com/spatie/laravel-glide) - 使用 Glide 轻松地转换 图像
* [Laravel Hashids](https://github.com/vinkla/laravel-hashids) - 使用 [Hashids](http://hashids.org/php/) 生成唯一的、随机的 id
* [Laravel Impersonate](https://github.com/404labfr/laravel-impersonate) - A package to authenticate as one of your users
* [Laravel Markdown](https://github.com/GrahamCampbell/Laravel-Markdown) - CommonMark markdown parser
* [Laravel MediaLibrary](https://github.com/spatie/laravel-medialibrary) - 关联文件到 Eloquent 模型
* [Laravel Menu](https://github.com/spatie/laravel-menu) -  Laravel Html 菜单生成系统
* [Laravel Talk](https://github.com/nahid/talk) - 实时用户消息系统
* [Laravel Messenger](https://github.com/cmgmyr/laravel-messenger) - 用户消息系统
* [Laravel Moderation](https://github.com/hootlex/laravel-moderation) - A simple Moderation System for Laravel 5.* that allows you to Approve or Reject resources like posts, comments, users, etc.
* [Laravel Paginateroute](https://github.com/spatie/laravel-paginateroute) - 不带查询字符串使用 Laravel 分页的 Laravel router 扩展
* [Laravel Pjax](https://github.com/spatie/laravel-pjax) - Laravel 5  pjax 中间件
* [Laravel Responsecache](https://github.com/spatie/laravel-responsecache) - 通过缓存内容相应加速 Laravel 应用
* [Laravel Snappy](https://github.com/barryvdh/laravel-snappy) - 使用 wkhtmltopdf 实现的 HTML 到 PDF 转换器
* [Laravel Stapler](https://github.com/CodeSleeve/laravel-stapler) - 基于 ORM 的文件上传管理
* [Laravel url signer](https://github.com/spatie/laravel-url-signer) - 创建并验证生命周期有限的签名网址
* [Laravel Tail](https://github.com/spatie/laravel-tail) - The missing tail command
* [Laravel Tags](https://github.com/spatie/laravel-tags) - 为 Laravel app 添加标签和标记行为
* [Laravel Uptime Monitor](https://github.com/spatie/laravel-uptime-monitor) - 一个功能强大且易于配置的正常运行时间和ssl监视器
* [Laravel Stats Tracker](https://github.com/antonioribeiro/tracker) - 从请求中收集信息以识别和存储
* [Listify](https://github.com/lookitsatravis/listify) - 添加排序功能到任何一个 Eloquent 模型
* [noCAPTCHA](https://github.com/ARCANEDEV/noCAPTCHA) - Google's 新 noCAPTCHA (reCAPTCHA) 系统的辅助包
* [Purifier](https://github.com/mewebstudio/purifier) - Laravel5 HTML 净化过滤器
* [Revisionable](https://github.com/VentureCraft/revisionable) - 创建 Eloquent 模型的修订历史记录
* [SEOTools](https://github.com/artesaos/seotools) - 常用 SEO 技术的辅助包
* [Laravel Setting](https://github.com/anlutro/laravel-settings) - 存储在JSON文件中的持久配置设置
* [Friendship](https://github.com/hootlex/laravel-friendships) - 好友管理系统 - 发送，接收，接受，拒绝朋友请求
* [Teamwork](https://github.com/mpociot/teamwork) - 带有邀请系统的用户到组织系统
* [Validating](https://github.com/dwightwatson/validating) - 验证模型的 Trait
* [VAT Calculator](https://github.com/mpociot/vat-calculator) - Handle all the hard stuff related to EU MOSS vat regulations
* [Laravel Uuid](https://github.com/webpatser/laravel-uuid) - 根据 RFC 4122 标准生成 UUID 的 Laravel 包
* [Laravel Installer](https://github.com/RachidLaasri/LaravelInstaller) - 允许用户跟随向导安装应用的 Laravel 包，类似 WordPress
* [Laravel Test Factory Generator](https://github.com/mpociot/laravel-test-factory-helper) - 从现有的模型中生成 Laravel 测试
* [Laravel-modules](https://github.com/nWidart/laravel-modules) - 在 Laravel 中轻松地管理模块
* [Laravel Phone](https://github.com/Propaganistas/Laravel-Phone) - 电话号码验证和格式化
* [Laravel Ban](https://github.com/cybercog/laravel-ban) - Laravel Ban simplify blocking and banning Eloquent models.
* [Laravel Proxy](https://github.com/fideloper/TrustedProxy) - Laravel 代理软件包，用于在负载均衡器或其他代理器背后处理会话。

##### 和 JavaScript 结合使用

* [Laroute](https://github.com/aaronlord/laroute) - 从生成Laravel 路由 URL
* [PHP Vars to JavaScript Transformer](https://github.com/laracasts/PHP-Vars-To-Js-Transformer) - 发送服务端的字符串/数组/集合/或其他任何数据到 JavaScript
* [Javascript Validation](https://github.com/proengsoft/laravel-jsvalidation) - 使用验证规则，消息，表单提交和验证器来验证客户端中的表单，而无需编写任何Javascript代码

##### 数据库, ORM, 迁移 & Seeding

* [Backup Manager](https://github.com/backup-manager/laravel) - Backup and restore databases from S3, Dropbox, SFTP etc.
* [Laravel Nestedset](https://github.com/lazychaser/laravel-nestedset) - 嵌套集合模式实现
* [ClosureTable](https://github.com/franzose/ClosureTable) - Closure table pattern implementation
* [Eloquence](https://github.com/kirkbushell/eloquence) - 模型的附加特性
* [iSeed](https://github.com/orangehill/iseed) - Generate a new seed file from an existing database table
* [Laravel OCI8](https://github.com/yajra/laravel-oci8) - Oracle DB driver for Laravel 4|5 via OCI8
* [Laravel Backup](https://github.com/spatie/laravel-backup) - 备份 app
* [Laravel Doctrine](https://github.com/laravel-doctrine/orm) - Doctrine 2 ORM 实现
* [Laravel MongoDB](https://github.com/jenssegers/laravel-mongodb) - 支持 MongoDB 的 Eloquent 模型和查询构建起
* [Migrations Generator](https://github.com/Xethron/migrations-generator) - 从现有数据库生成数据库迁移
* [Sofa/Eloquence](https://github.com/jarektkaczyk/eloquence) - Eloquent ORM 的扩展
* [Tenanti](https://github.com/orchestral/tenanti) - Multi-tenant database schema manager
* [Laravel Repository](https://github.com/andersao/l5-repository) - Repositories to abstract the database layer for Laravel 5

##### 搜索

* [Algolia Search](https://github.com/algolia/algoliasearch-laravel) - Integrates the Algolia Search API to the Laravel Eloquent ORM
* [Elasticquent](https://github.com/elasticquent/Elasticquent) - Elasticsearch for Eloquent models
* [Plastic](https://github.com/sleimanx2/plastic) - Fluently mapping and searching Elasticsearch
* [Laravel Search](https://github.com/mmanos/laravel-search) - Unified API for Elasticsearch, Algolia, and ZendSearch
* [SearchIndex](https://github.com/spatie/searchindex) - Store and retrieve objects from Algolia or Elasticsearch
* [Searchable](https://github.com/nicolaslopezj/searchable) - Trait that adds a simple search function to Eloquent models
* [TNTSearch](https://github.com/teamtnt/tntsearch) - A fully featured full text search engine written in PHP

##### APIs

* [ApiGuard](https://github.com/chrisbjr/api-guard) - Allow API authentication with API keys
* [Dingo API](https://github.com/dingo/api) - Multi-purpose toolkit for developing RESTful APIs
* [Laravel CORS](https://github.com/barryvdh/laravel-cors) - 添加 CORS (跨域资源共享) 头支持
* [Laravel Fractal](https://github.com/spatie/laravel-fractal) - Output complex, flexible, AJAX/RESTful data structures with Fractal in Laravel and Lumen
* [Laravel GraphQL](https://github.com/Folkloreatelier/laravel-graphql) - Facebook GraphQL for Laravel 5. It supports Relay, eloquent models, validation and GraphiQL.

##### 任务, 命令和调度

* [Dispatcher](https://github.com/indatus/dispatcher) - 命令调度器
* [Elixir](https://github.com/laravel/elixir) - Node(NPM) package to run Gulp tasks that watch files, run tests, minify CSS, concatenate scripts etc.
* [Mix](https://github.com/JeffreyWay/laravel-mix) - Laravel Mix provides a clean, fluent API for defining basic webpack build steps for your Laravel application. Mix supports several common CSS and JavaScript pre-processors.
* [Envoy](https://github.com/laravel/envoy) - SSH任务运行器

##### 支付

* [Cashier](https://github.com/laravel/cashier) - 使用 Stripe 的订阅账单
* [Omnipay for Laravel](https://github.com/ignited/laravel-omnipay) - Integrate the [Omnipay](https://github.com/thephpleague/omnipay) PHP library
* [Omnipay Alipay](https://github.com/lokielse/omnipay-alipay) Omnipay 支付宝支付集成
* [Omnipay Wechat Pay](https://github.com/lokielse/omnipay-wechatpay) Omnipay 微信支付集成
* [Omnipay UnionPay](https://github.com/lokielse/omnipay-unionpay) Omnipay 银联支付集成

##### 优化

* [Intervention Image Cache](https://github.com/Intervention/imagecache) - Intervention Image 类的缓存扩展
* [Laravel HTMLMin](https://github.com/GrahamCampbell/Laravel-HTMLMin) - Blade/HTML/CSS/javascript 压缩器
* [Rememberable](https://github.com/dwightwatson/rememberable) - Laravel 5 (eloquent) 查询缓存吗
* [Widgetize](https://github.com/imanghafoori1/laravel-widgetize) - Laravel 5 的页面部分缓存
* [Widgets for Laravel](https://github.com/arrilot/laravel-widgets) - 视图 composers 的强大替代品。异步小部件，可重新加载的小部件，控制台生成器，缓存以及您可以想到的一切。

##### 本地化

* [Language Files](https://github.com/caouecs/Laravel-lang) - 包含 37 种语言的炎症期、分页器和提醒文字
* [Laravel Localization](https://github.com/mcamara/laravel-localization) - 为路由添加 i18n 支持
* [Laravel Translatable](https://github.com/spatie/laravel-translatable) - Making Eloquent models translatable by storing translations as JSON.
* [Laravel Translatable](https://github.com/dimsav/laravel-translatable) - 获取和保存可翻译的 Eloquent 模型实例
* [Laravel Translator](https://github.com/vinkla/laravel-translator) - 翻译 Eloquent 模型到多种语言
* [Laravel Date](https://github.com/jenssegers/date) - A library to help you work with dates in multiple languages, based on Carbon
* [Laravel Langman](https://github.com/themsaid/laravel-langman) - 从 Artisan 命令行管理语言文件
* [Laravel Translation](https://github.com/waavi/translation) - Allow live edit/caching of translation entries, and localization of urls and Eloquent Model attributes.
* [Linguist](https://github.com/keevitaja/linguist) - i18n localization support for Laravel

##### 第三方服务集成

* [Laravel Algolia](https://github.com/vinkla/laravel-algolia) - Algolia API bridge
* [Laravel Analytics](https://github.com/spatie/laravel-analytics) - An opinionated Laravel 5 package to retrieve pageviews and other data from Google Analytics
* [Laravel DigitalOcean](https://github.com/GrahamCampbell/Laravel-DigitalOcean) - DigitalOceanV2 bridge
* [Laravel Dropbox](https://github.com/GrahamCampbell/Laravel-Dropbox) - Dropbox bridge
* [Laravel Facebook](https://github.com/vinkla/laravel-facebook) - Facebook API bridge
* [Laravel GitHub](https://github.com/GrahamCampbell/Laravel-GitHub) - PHP GitHub API bridge
* [Laravel GitLab](https://github.com/vinkla/laravel-gitlab) - GitLab API bridge
* [Laravel Googletagmanager](https://github.com/spatie/laravel-googletagmanager) - Easily setup and send data to Google Tag Manager
* [Laravel Instagram](https://github.com/vinkla/laravel-instagram) - Instagram API bridge
* [Laravel Newsletter](https://github.com/spatie/laravel-newsletter) - Send newsletters with Mailchimp
* [Laravel Parse](https://github.com/GrahamCampbell/Laravel-Parse) - PHP Parse SDK bridge
* [Laravel Pusher](https://github.com/vinkla/laravel-pusher) - Pusher API bridge
* [Laravel Pushwoosh](https://github.com/hoymultimedia/Laravel-Pushwoosh) - Pushwoosh API bridge
* [Laravel Vimeo](https://github.com/vinkla/laravel-vimeo) - Vimeo API bridge


## 开发设置

* [Homestead](https://laravel.com/docs/5.3/homestead) - Laravel 官方的  Vagrant box
  * [Getting Started with Laravel Homestead](https://scotch.io/tutorials/getting-started-with-laravel-homestead)
  * [Installation on macOS and Linux](https://laracasts.com/series/laravel-5-from-scratch/episodes/3)
  * [Installation on  Windows](http://blog.teamtreehouse.com/laravel-homestead-on-windows)
* [Valet](https://laravel.com/docs/5.3/valet/) - Mac 用户的开发环境
* [Valet Linux](https://github.com/cpriego/valet-linux) - Linux 用户的开发环境
* [LaraDock](https://github.com/LaraDock/laradock) - 在 Docker 上运行 Laravel  (类似 Homestead 但是使用 Docker 替代 Vagrant)
* [LaraEdit Docker](https://github.com/laraedit/laraedit-docker) - 在单个 Docker 容器中运行的 Homestead 环境
* [Laragon](https://laragon.org/) -  Windows 上的隔离开发环境
* [Stacker](https://maxlab.github.io/stacker/) - Docker 上的本地 Web 开发环境

## 应用主机

* [Forge](https://forge.laravel.com/)
  * [Server Management with Forge](https://laracasts.com/series/server-management-with-forge) (Laracasts)
  * [Getting your first site up and running in Laravel Forge](https://mattstauffer.co/blog/getting-your-first-site-up-and-running-in-laravel-forge) (Matt Stauffer)
  * [ForgeRecipes](http://forgerecipes.com/)
* [FortRabbit](https://www.fortrabbit.com/laravel-hosting) ([Video](https://laracasts.com/lessons/from-zero-to-deploy-with-fortrabbit))
* [PagodaBox](https://pagodabox.io/) ([Documentation](https://pagodabox.io/docs/framework_laravel))
* [Heroku](https://www.heroku.com/) ([Tutorial](https://mattstauffer.co/blog/installing-a-laravel-app-on-heroku))
* [IBM BlueMix](https://console.ng.bluemix.net/) ([Tutorial](https://developer.ibm.com/bluemix/2014/06/17/getting-started-laravel-bluemix/))
* [AWS Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/) ([Tutorial](http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/php-laravel-tutorial.html#php-laravel-tutorial-deploy))
* [Cloudways](https://www.cloudways.com/en/laravel-hosting.php)

## 应用部署

* [Envoyer](https://envoyer.io/) - Zero down-time Deployer for PHP & Laravel projects
 * [Deployments with Envoyer](https://laracasts.com/series/envoyer) (Laracasts)
* [Rocketeer](https://github.com/rocketeers/rocketeer) - Task runner and deployment package

## 文章，教程，博客等

* [Tuts+](http://code.tutsplus.com/categories/laravel)
* [SitePoint](https://www.sitepoint.com/php/page/0/?filter[4047]=on)
* [Medium](https://medium.com/tag/laravel/latest)
* [Christopher Pitt](https://medium.com/laravel-4)
* [Culttt](http://culttt.com/tag/cribbb/)
* [Scotch](https://scotch.io/tag/laravel)
* [Fideloper](http://fideloper.com/tag/laravel)
* [Maxoffsky](https://maxoffsky.com/tag/laravel/)
* [KodeInfo](http://kodeinfo.com/main_category/laravel)
* [Taylor Otwell](http://taylorotwell.com/)
* [Digital Ocean](https://www.digitalocean.com/community/search?q=laravel&type=tutorials)
* [Matt Stauffer](https://mattstauffer.co/tags/laravel)
* [Creative Punch](http://creative-punch.net/articles/php-articles/laravel-tutorials/)
* [Ryan Tablada](http://ryantablada.com/tag/Laravel)
* [Mohamed Said](https://themsaid.com/)
* [Mohammad Gufran](http://www.gufran.me/tag/Laravel/)
* [Adam Engebretson](http://blog.enge.me/4)
* [CodeHeaps](http://www.codeheaps.com/)
* [Laravel India](http://blog.laravel.in/)
* [Vegi Bit](http://vegibit.com/tag/laravel/)
* [WSnippets](http://wsnippets.com/category/laravel/)
* [Kirk Bushell](http://kirkbushell.me/)
* [Andrews Ang](http://blog.kongnir.com/category/laravel-2/)
* [DeveloPHP](http://www.develophp.org/category/web/laravel/)
* [Jason Lewis](http://jasonlewis.me/category/laravel)
* [Eric Barnes](https://ericlbarnes.com/tag/laravel/)
* [Jens Segers](https://jenssegers.com/)
* [Neon Tsunami](https://www.neontsunami.com/tags/laravel)
* [Stidges](http://blog.stidges.com/)
* [Scott Wilcox](https://dor.ky/tag/laravel/)
* [Clivern](http://clivern.com/tag/laravel/)
* [Code Gains](http://codegains.com/tag/laravel-2/)
* [Stillat](http://www.stillat.com/blog/category/programming/laravel/)
* [Easy Laravel Book Blog](http://www.easylaravelbook.com/blog/)
* [Bosnadev](https://bosnadev.com/tag/laravel-2/)
* [Vedovelli (PT-BR)](http://www.vedovelli.com.br/tag/laravel/)
* [CodeTutorial](https://www.codetutorial.io/tag/laravel/)
* [Ryan Chenkie](http://ryanchenkie.com/tag/laravel/)
* [Laravel Tips](https://laraveltips.wordpress.com/)
* [Codingo Tuts](https://tuts.codingo.me/category/web-development/laravel)
* [Antonio Carlos Ribeiro](https://antoniocarlosribeiro.com/technology)
* [Laravel Coding](http://laravelcoding.com/blog)
* [Laraveles](http://laraveles.com/blog/) (ES)
* [Styde](https://styde.net/cursos/) (ES)
* [CodigoFacilito](https://codigofacilito.com/courses/laravel)(ES)
* [Laravel Daily](http://laraveldaily.com/)
* [Freek Van der Herten](https://murze.be/tag/laravel/)
* [ForLaravel](https://forlaravel.com/)
* [Good Heads](http://goodheads.io/category/laravel/)
* [Ryan Stelmat](http://ryanstelmat.com/tag/laravel/)
* [Cloudways Laravel Blog](http://cloudways.com/blog/laravel)

## 视频

* [Laracasts](https://laracasts.com/)
* [Coursecode](https://www.codecourse.com/) ([YouTube](https://www.youtube.com/user/phpacademy/playlists))
* [Tuts+](http://code.tutsplus.com/categories/laravel/courses)
* [Udemy](https://www.udemy.com/courses/search/?q=laravel&lang=en)
* [Treehouse](https://teamtreehouse.com/library/q:laravel)
* [Duilio Palacios](https://www.youtube.com/user/silencedsg/videos)
* [DevDojo](https://devdojo.com/search?value=laravel)
* [Amitav Roy](https://www.youtube.com/channel/UC4gijXR8cM4gmEt9Olse-TQ/videos)
* [Lynda](https://www.lynda.com/Laravel-training-tutorials/2779-0.html)
* [Pluralsight](https://www.pluralsight.com/search?q=laravel&categories=course)
* [Laracademy](https://laracademy.co/)
* [Dev Marketer](https://www.youtube.com/channel/UC6kwT7-jjZHHF1s7vCfg2CA/playlists)

## 会议

* [Laracon US](http://laracon.us/)
* [Laracon EU](http://laracon.eu/)
* [Laraconf Brasil](http://laraconfbrasil.com.br/)
* [Laracon Online](https://laracon.net/)

##### 视频

* [Laracon EU 2017](https://www.youtube.com/watch?v=JPxhnRh1Rr8&list=PLMdXHJK-lGoBFZgG2juDXF6LiikpQeLx2)
* [Larcaon US 2017](https://streamacon.com/video/laracon-us-2017)
* [Laracon EU 2016](https://www.youtube.com/playlist?list=PLMdXHJK-lGoCMkOxqe82hOC8tgthqhHCN)
* [Laracon US 2016](https://streamacon.com/video/laracon-us)
* [Laracon EU 2015](https://www.youtube.com/playlist?list=PLMdXHJK-lGoA9SIsuFy0UWL8PZD1G3YFZ)
* [Laracon EU 2014](http://laracon.eu/2014/#schedule)
* [Laracon US 2014](http://userscape.com/laracon/2014/)
* [Laracon EU 2013](http://laracon.eu/2013/talks/)
* [Laracon US 2013](https://www.youtube.com/playlist?list=PLkwAlZpjHQbLcox_S_AgGU24QUfKgXayN)

## 图书

* [Laravel Starter](https://www.packtpub.com/web-development/laravel-starter) by Shawn McCool
* [Laravel: Code Happy](https://leanpub.com/codehappy) by Dayle Rees
* [Laravel: Code Bright](https://leanpub.com/codebright) by Dayle Rees
* [Laravel: Code Smart](https://leanpub.com/codesmart) by Dayle Rees
* [Laravel: From Apprentice To Artisan](https://leanpub.com/laravel) by Taylor Otwell
* [Laravel 4 Cookbook](https://leanpub.com/laravel4cookbook) by Christopher Pitt and Taylor Otwell
* [Laravel Testing Decoded](https://leanpub.com/laravel-testing-decoded) by Jeffrey Way
* [Refactoring to Collections](https://adamwathan.me/refactoring-to-collections/) by Adam Wathan
* [Implementing Laravel](https://leanpub.com/implementinglaravel) by Chris Fidao
* [Getting Stuff Done with Laravel 4](https://leanpub.com/gettingstuffdonelaravel) by Chuck Heintzelman
* [Laravel Application Development Blueprints](https://www.packtpub.com/web-development/laravel-application-development-blueprints) by Arda Kılıçdağı and Halil İbrahim Yılmaz
* [Build APIs You Won't Hate](https://leanpub.com/build-apis-you-wont-hate) by Phil Sturgeon
* [Integrating Front end Components with Web Applications](https://leanpub.com/frontend) by Maksim Surguy
* [Laravel Design Patterns and Best Practices](https://www.packtpub.com/web-development/laravel-design-patterns-and-best-practices) by Arda Kılıçdağı and Halil İbrahim Yılmaz
* [Step by Step Real World Application with Laravel 4](https://leanpub.com/real-world-laravel4) by Ibrahim Yusuf
* [Learning Laravel 4 Application Development](https://www.packtpub.com/web-development/learning-laravel-4-application-development) by Hardik Dangar
* [Getting Started with Laravel 4](https://www.packtpub.com/web-development/getting-started-laravel-4) by Raphaël Saunier
* [Laravel Application Development Cookbook](https://www.packtpub.com/web-development/laravel-application-development-cookbook) by Terry Matula
* [Building Web Applications Using Parse REST API](https://leanpub.com/building-web-applications-using-parse-rest-api) by Mhd Zaher Ghaibeh
* [Laravel - My First Framework](https://leanpub.com/laravel-first-framework) by Maksim Surguy
* [Easy Laravel 5](https://leanpub.com/easylaravel/) by W. Jason Gilmore
* [Laravel 5 Essentials](https://www.packtpub.com/web-development/laravel-5-essentials) by Martin Bean
* [Easy E-Commerce Using Laravel and Stripe](https://leanpub.com/easyecommerce) by W. Jason Gilmore and Eric L. Barnes
* [Laravel 5.1 Beauty](https://leanpub.com/l5-beauty) by Chuck Heintzelman
* [Design Patterns with PHP and Laravel](https://leanpub.com/larasign) by Kelt Dockins
* [Mastering Laravel](https://www.packtpub.com/web-development/mastering-laravel) by Christopher John Pecoraro
* [How to Build Real-Time Laravel Apps with Pusher](http://pusher-community.github.io/real-time-laravel/) by Pusher
* [Learning Laravel's Eloquent](https://www.packtpub.com/web-development/learning-laravel%E2%80%99s-eloquent) by Francesco Malatesta
* [Laravel 5 Learn Easy](https://leanpub.com/laravel5learneasy) by Sanjib Sinha
* [Laravel and AngularJS](https://leanpub.com/laravel-and-angularjs) by Daniel Schmitz and Daniel Pedrinha Georgii
* [Laravel Collections Unraveled](https://leanpub.com/laravelcollectionsunraveled) by Jeff Madsen
* [Writing APIs With Lumen](https://leanpub.com/lumen-apis) by Paul Redmond
* [The Laravel Survival Guide](https://leanpub.com/laravelsurvivalguide) by Tony Lea
* [Laraboot: Laravel 5 For Beginners](https://leanpub.com/laravel-5-for-beginners-laraboot) by Bill Keck
* [Laravel 5.3 For Beginners](https://leanpub.com/laravel-5-3-for-beginners) by Bill Keck
* [Laravel Up & Running](https://laravelupandrunning.com/)

## 起始项目

* [LaraAdmin](http://laraadmin.com/)
* [Laracogs](https://github.com/yabhq/laracogs)
* [Laravel 5.2 Boilerplate](https://github.com/rappasoft/laravel-5-boilerplate)
* [Laravel 5 Angular Material Starter](https://github.com/jadjoubran/laravel5-angular-material-starter)
* [Acacha adminlte-laravel](https://github.com/acacha/adminlte-laravel)
* [Laravel Hackathon Starter](https://github.com/unicodeveloper/laravel-hackathon-starter)
* [Laravel API](https://github.com/joselfonseca/laravel-api)
* [Laravel Angular AdminLTE](https://github.com/silverbux/laravel-angular-admin)
* [Backpack for Laravel](https://backpackforlaravel.com)
* [Starter Someline](https://starter.someline.com)
* [Laravel-admin](https://github.com/z-song/laravel-admin)
* [Voyager](https://the-control-group.github.io/voyager/)
* [Orchid](https://github.com/TheOrchid/Platform)
* [Laravel REST API Boilerplate](https://github.com/francescomalatesta/laravel-api-boilerplate-jwt)
* [Hello API](https://github.com/Porto-SAP/Hello-API)
* [REST API With Lumen 5.4](https://github.com/hasib32/rest-api-with-lumen)
* [Laravel Zero - Console application](https://github.com/laravel-zero/laravel-zero)

## 代码参考

* [92Five](https://github.com/chintanbanugaria/92five) - 项目管理应用
* [Cachet](https://github.com/cachethq/Cachet) - 站点和 API 的状态页系统
* [Deployer](https://github.com/REBELinBLUE/deployer) - 应用部署系统
* [GitScrum](https://github.com/renatomarinho/laravel-gitscrum) - 每日使用的任务管理系统. Git + Scrum = 团队成产力提高
* [Invoice Ninja](https://github.com/invoiceninja/invoiceninja) - 发票，费用和时间跟踪应用程序
* [Koel](https://github.com/phanan/koel) - 个人音乐流服务
* [Laravel Tricks](https://github.com/CodepadME/laravel-tricks) - 站点的源码
* [Laravel.io](https://github.com/laravelio/laravel.io) -  Laravel.io 社区门户源码
* [Paperwork](https://github.com/twostairs/paperwork) - 笔记和存档应用
* [PHPHub](https://github.com/summerblue/phphub) - PHP & Laravel 中国社区的论坛和源码
* [Flarum](https://github.com/flarum/flarum) - 易用并且简单的论坛
* [Laramap](https://github.com/laramap/laramap.com) - Laramap.com 源码
* [Attendize](https://github.com/Attendize/Attendize) - 售票和活动管理平台
* [Katana](https://github.com/themsaid/katana) - 支持 markdown 的静态站点/博客生成器
* [Antvel](https://github.com/ant-vel/App) - 电商平台
* [Jigsaw](http://jigsaw.tighten.co) - 静态站点生成器
* [Canvas](https://github.com/austintoddj/Canvas) - 开发者使用的极简博客应
* [Vuedo](https://github.com/Vuedo/vuedo) - 博客系统，使用 Laravel 和  Vue.js 构建
* [Screeenly](https://github.com/stefanzweifel/screeenly) - 使用 API 创建站点截图
* [Voten](https://github.com/voten-co/voten) - 一个21世纪的实时的社交书签系统

## CMS 系统

* [OctoberCMS](http://octobercms.com/)
* [PyroCMS](https://www.pyrocms.com/)
* [Lavalite](http://www.lavalite.org/)
* [Bootstrap CMS](https://github.com/BootstrapCMS/CMS)
* [TypiCMS](https://github.com/typicms/base)
* [Asgard CMS](https://asgardcms.com/)
* [Microweber](https://microweber.com/)
* [Coaster CMS](https://www.coastercms.org/)
* [Statamic](https://statamic.com/)
* [Quarx](https://github.com/yabhq/quarx)
* [WebEd CMS](https://github.com/sgsoft-studio/webed)
* [Borgert CMS](https://github.com/odirleiborgert/borgert-cms/)
* [PJ Blog](https://github.com/jcc/blog/)
* [Laralum](https://laralum.com/)

## 简讯

* [Laravel News](https://laravel-news.com/) ([archive](https://laravel-news.com/archive/))
* [Laravel Weekly](http://laravelweekly.com/)

## 播客

* [The Laravel Podcast](http://www.laravelpodcast.com/)
* [The Laravel News Podcast](https://laravel-news.com/podcast/ )
* [The Laracasts Snippet](https://laracasts.simplecast.fm/)
* [Hecho en Laravel (Spanish)](http://hechoenlaravel.com)

## 社区

* [Laracasts Forum](https://laracasts.com/discuss)
* [Laracasts Forum](https://laracasts.com/discuss)
* [Laravel.io Forum](http://laravel.io/forum)
* [Larachat Slack](https://larachat.slack.com/) ([Signup](https://larachat.co/slack))
* [Gitter](https://gitter.im/laravel/laravel)
* [IRC Channel](http://laravel.io/chat)
* [StackOverflow](http://stackoverflow.com/questions/tagged/laravel)
* [Twitter](https://twitter.com/laravelphp)
* [Google+](https://plus.google.com/communities/106838454910116161868)
* [Reddit](https://www.reddit.com/r/laravel)
* [Quora](https://www.quora.com/topic/Laravel)
* [Facebook](https://www.facebook.com/LaravelCommunity)
* [LinkedIn](https://www.linkedin.com/groups/4419933/profile)
* [Laraveles Slack](https://laraveles.slack.com) ([Signup](http://laraveles.com/blog/wp-login.php?action=slack-invitation))
* [Laravel UK](https://twitter.com/UKLaravel), [Slack Signup](http://laraveluk.signup.team)

##### 本地用户组

* [Laravel Russia](https://laravel.ru/) ([VK group](http://m.vk.com/laravel_rus))
* [Laravel France](https://laravel.fr/)
* [Laravel Indonesia](http://id-laravel.com/) ([Facebook group](https://www.facebook.com/groups/laravel/))
* [Laravel Brasil](http://www.laravel.com.br/) ([Facebook group](https://www.facebook.com/groups/laravelbrasil/), [Slack](http://slack.laravel.com.br), [Telegram](https://telegram.me/laravelbr), [Google+](https://plus.google.com/communities/116661672628675028624), [GitHub](https://github.com/laravelbrasil))
* [Laravel Turkey](http://www.laravel.gen.tr/) ([Facebook group](https://www.facebook.com/groups/laravelturkiye/))
* [Laravel Nigeria](http://www.laranaija.com/) ([Facebook group](https://www.facebook.com/groups/laravelnigeria/))
* [Laravel China](https://phphub.org/)
* [Laravel Taiwan](https://laravel.tw/) ([Facebook group](https://www.facebook.com/groups/laravel.tw/))
* [Laravel Spanish](http://laraveles.com/foro/)
* [Laravel Korea](https://www.laravel.co.kr/) ([Facebook group](https://www.facebook.com/groups/laravelkorea/))
* [Laravel Japan](http://laravel.jp/) ([Facebook group](https://www.facebook.com/groups/laravel.jp/))
* [Laravel Tokyo](https://laravel.tokyo/) ([Facebook group](https://www.facebook.com/groups/laraveltokyo/))
* [Laravel Malaysia](https://www.facebook.com/groups/laravel.my/)
* [Laravel Algeria Facebook Group](https://www.facebook.com/groups/LaravelAlgeria/)
* [Laravel Greece](http://www.laravel.gr) ([Facebook page](https://www.facebook.com/laravelgr))
* [Laravel Middle East](http://laravelme.com/) ([Facebook page](https://www.facebook.com/laravelme))
* [Laravel Georgia](https://www.facebook.com/groups/laravel.georgia/)
* [Laravel Italy](http://laravel-italia.it)
* [Laravel Viet Nam](https://www.facebook.com/groups/vietnam.laravel/)
* [Laravel Slovenia](https://www.facebook.com/groups/laravelslovenija/)
* [Laravel Hungary](https://laravel.hu)

##### 聚会

* [All Meetups](http://www.meetup.com/topics/laravel/)
* [London Meetup](https://www.meetup.com/London-Laravel/)
* [Buenos Aires, Argentina Meetup](https://www.meetup.com/Laravel-Buenos-Aires/)
* [Morocco Meetup](https://www.meetup.com/moroccophp/)
* [Athens-Greece Meetup](https://www.meetup.com/athens-laravel-meetup/)
* [Copenhagen Meetup](https://www.meetup.com/Copenhagen-Laravel-Meetup/)
* [Detroit Meetup](https://www.meetup.com/Laravel-Detroit/)
* [Paris Meetup](https://www.meetup.com/fr-FR/Paris-Laravel-Meetup/)
* [Melbourne, Australia Meetup](https://www.meetup.com/Melbourne-laravel-Meetup/)
* [Budapest Meetup](https://www.meetup.com/Laravel-Hungary-Meetup/)

## 工作

* [LaraJobs](https://larajobs.com/)
* [Laravel Gurus](https://laravelgurus.com/)

## 托管的开发工具

* [Laravel Shift](https://laravelshift.com/) - Laravel 项目的自动更新工具
* [Laravel Versions {x.y.z}](https://laraver.xyz/) - 监控 Laravel 升级
* [Laragen](http://makzumi.com/laragen/) - View 生成器
* [Laravel Schema Designer](http://laravelsd.com/) - 创建，导出和共享数据库模式
* [Laravel Database Designer](http://biodesignrealworld.github.io/LaravelDatabaseDesigner/) - 用于创建数据库模式的图形工具
* [StyleCI](https://styleci.io) - PHP 代码风格服务
* [DependenCI](https://dependenci.miguelpiedrafita.com) - Composer 的持续集成工具

## 其他

* [CodeCanyon](https://codecanyon.net/tags/laravel?term=laravel) - 付费脚本和插件

## 贡献

Found an awesome package, blog, video etc.? Send me a pull request!

#### Guidelines

* Please make an individual pull request for each suggestion
* Make sure the Travis tests pass on your pull request
* Use the following format for links: \[Resource\]\(URL\)
* Want to suggest a package? Read the [Contribution Guide](https://github.com/chiraggude/awesome-laravel/blob/master/CONTRIBUTING.md)
* New categories or improvements to the existing categorization are welcome

## License

[![CC BY 4.0](https://licensebuttons.net/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

Awesome Laravel is licensed under a  [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
