eBestMall - B2B2C商城系统
===============================

> eBestMall是基于 Laravel5.5 LTS 企业级PHP框架开发的B2B2C现代一体化电商平台系统。采用最前沿的Web技术和UI界面设计，彰显鸿宇团队的用心。同时是国内电子商务系统及服务解决方案新创品牌。为传统企业及创业者提供零售网店系统、网上商城系统、分销系统、B2B2C商城系统、微信分销系统、行业ERP等产品和解决方案。

[![Latest Stable Version](https://poser.pugx.org/hongyukeji/ebestmall/v/stable.png)](https://packagist.org/packages/hongyukeji/ebestmall)
[![Total Downloads](https://poser.pugx.org/hongyukeji/ebestmall/downloads.png)](https://packagist.org/packages/hongyukeji/ebestmall)


安装与更新
-------------------

```
运营版：
# composer create-project hongyukeji/ebestmall ebestmall

开发版：
# composer create-project hongyukeji/ebestmall ebestmall dev-master
```


运行环境
-------------------

* PHP版本：>= 7.0.0
* MySQL版本：>= 5.1.0
* Laravel版本：>= 5.5 LTS


功能介绍
-------------------

|名称|进度|备注|
|:----|:-----:|-----:|
优惠券 |   进行中 |   无    |
秒杀    |   进行中  |   无    |
拼团    |   进行中  |   无    |
众筹    |   进行中  |   无    |
拍卖    |   进行中  |   无    |
预售    |   进行中  |   无    |
团购    |   进行中  |   无    |
本地生活    |   进行中  |   无    |
商品主图视频    |   进行中  |   无    |
商家地图定位    |   进行中  |   无    |
云采购商品批发  |   进行中  |   无    |


系统开发
-------------------

* 公司名称：鸿宇科技有限公司
* 公司官网：www.hongyuvip.com
* 系统演示：www.ebestmall.com
* 系统框架：Laravel 5.5 LTS
* 核心技术：PHP7、Html5、Css3、JavaScript ES6、jQuery、Ajax、MySQL、VueJS、Bootstrap
* 开发工具：PhpStorm、Navicat for MySQL、PhotoShop CS6、
* 开发成员：Shadow（项目总监）、Spider（代码审计）、Free(数据库建模)、Wind（PHP后端开发）、Flower（前端UI设计）、Boy(Html5前端开发)
* 特别鸣谢：感谢所有支持鸿宇团队的朋友！


系统维护
-------------------

* Author：Shadow
* QQ：[1527200768](http://wpa.qq.com/msgrd?V=1&uin=1527200768&Menu=yes)
* Phone：13952101395
* Email：[admin@hongyuvip.com](mailto:admin@hongyuvip.com)
* QQ交流群：[90664526](http://shang.qq.com/wpa/qunwpa?idkey=a3e498d7d3329615c9b3d1dbbbc50e43fa80b39e93a1ae78f1fb0a268f3a0476)


开发日志
-------------------

|版本|内容|时间|备注|
|:----|:-----:|-----:|-----:|
v1.0.0|完成项目基础应用建设|2017-12-31|本地开发，未提交GitHub|
v1.1.0|完成项目Laravel框架转移|2018-03-05|本地开发，未提交GitHub|


开发文档
-------------------

|名称|内容|
|:----|:-----:|
ebm migrate  |   执行迁移   |
ebm migrate:refresh --seed  |   回滚并重新运行所有迁移和填充文件   |
ebm migrate:rollback  |   回滚上一次的迁移   |
ebm migrate:reset  |   回滚所有迁移   |
ebm make:migration create_example_table --create=example  |   创建迁移文件   |
ebm make:migration add_votes_to_example_table --table=example  |   给example表迁移文件增加votes字段   |
ebm make:migration add_avatar_and_introduction_to_example_table --table=example  |   给example表迁移文件增加avatar和introduction字段   |
ebm make:controller ExampleController  |   创建基础控制器   |
ebm make:controller ExampleController  --resource  |   创建Rest风格资源控制器   |
ebm make:controller make:model Models\Example  |   创建Model模型   |
ebm make:controller make:model Models\Example -m  |   创建Model模型同时生成迁移文件   |
ebm make:seeder DemoTableSeeder  |   创建填充文件   |
ebm db:seed --class=DemoTableSeeder  |   执行单个填充文件   |
ebm db:seed  |   执行所有填充文件   |
ebm make:middleware Example  |   创建中间件（app/Http/Middleware）   |
ebm queue:table  |   创建队列（数据库）的表迁移（需要执行迁移才生效）   |
ebm make:job SendEmail  |   创建队列类（app/jobs）   |
ebm make:request CreateExampleRequest  |   创建请求类（app/Http/Requests）   |