# 项目计划书

## 初衷
对于很多人来说，项目（商业）计划书是不可言说的秘密。作为一名爱折腾的程序员，也有受邀合伙先签保密协议才能透露商业计划的经历。

大多数的商业模式，无非处于买卖中的某个环节。而买卖要想做得长远，无非两件事，一是价钱比别人便宜，二是质量或用户体验比别人好。而商业模式也往往是围绕着怎么把这两件事做好。

如果商业模式真的好，想让这个商业模式变得有意义，最好的办法就是让这个商业模式得以实现。至于是谁来实现，钱是谁赚的，没那么重要，肤浅的商业计划是挣钱，真正的商业计划是成事。

这些年投机主义盛行，很多程序员眼睁睁看到圈子里的朋友炒币走向人生巅峰，能够沉下心来做实事是件不容易的事情。不贩卖鸡汤，也不贩卖焦虑。开源一份商业模式的思考，旨在给更多的同道中人提供参照，实现自己的自由职业。

同时也围绕这套商业计划书，开源我们在技术上的积累。希望能够对社会的进步出些微薄之力，以上便是促进我开源商业计划书的初衷。

## 项目介绍

One Work 是基于多重激励进行人力资源优化的项目管理平台，主要功能如下：

1. 项目管理：基于任务调度和流水线；
2. 灵活雇佣：多种办公协作形式（远程办公、共享办公空间）；
3. 项目周边服务生态：福利咨询、法务咨询；
4. 围绕项目优化资源配置：如股权众筹，薪资转股；

力求尽可能促进项目的成功率，降低项目开展过程中的成本。

One Work 基于其姊妹开源项目 [Work Design](https://github.com/work-design) 所提供的系列开源组件进行组装和开发，Work Design 富有创新性的架构使得其所提供的功能既可以作为 SaaS 系统对外提供，也可以用于企业独立部署使用和二次开发。

除了 One Work 项目本身开源以外，Work Design 提供的组件涵盖了大量的常规需求。诸如：
* [OA / 组织架构 / SaaS](https://github.com/work-design/rails_org)
* [电商及支付](https://github.com/work-design/rails_trade)
* [会员](https://github.com/work-design/rails_vip)
* [预约系统](https://github.com/work-design/rails_event)
* [客户关系(CRM)](https://github.com/work-design/rails_crm)
* [询价系统](https://github.com/work-design/rails_enquiry)

基于这些组件，遵循 Work Design 的[开发指南](https://github.com/work-design/work.design)，自由的添加针对自身企业的个性化需求，即可实现快速开发。

## 商业模式
One Work 首先是一个面向中小型（小微型）企业的管理系统，我们的企业用户会基于 One Work 这套系统向 C端用户提供服务。

[One Work](https://one.work) 站点会尽可能免费提供基础功能给企业用户（B端用户）使用，鼓励 B端用户带来 C端用户，同时我们也将提供部分服务直接给 C端用户使用。

也就是说，我们实践的是一套非常具有普适性的商业思路：通过免费降低用户进入本系统的门槛，从而省去市场费用，然后再提供可供用户选择的收费服务。

目前，互联网行业的用户红利期已过，获取用户的成本变得越来越高昂。作为多租户 SaaS 系统，我们摒弃了传统的收费盈利模式，通过基础功能免费，打造生态，既服务 B端用户，也服务 C端用户。

与 Github 的商业方式类似，属于常规的免费服务获取用户提供增值服务的模式。但是增值服务并非传统的收租模式，而是在生态范围内提供更有价值的服务内容。

## 理念
* [社会价值第一](precept.md#社会价值第一)
* [生态](precept.md#生态)
* [开放](precept.md#开放)

## 其他应用领域

除了 One Work，我们亦会通过开放合作的形式在早教、餐饮、社区、旅游这些领域实践数个标杆项目。这些项目在本项目提供的商业模式框架和理念下进行运行。

## One Work 需求及功能分析

* [技术输出服务](tech.md)
* [新型人力资源服务](partnership.md)