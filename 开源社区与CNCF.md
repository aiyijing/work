# CNCF 与 kubernetes 开源社区简介

# CNCF
## CNCF 是什么
CNCF，全称Cloud Native Computing Foundation（云原生计算基金会），成立于 2015 年7月21日（于美国波特兰OSCON 2015上宣布），其最初的口号是坚持和整合开源技术来让编排容器作为微服务架构的一部分，其作为致力于云原生应用推广和普及的一支重要力量，不论您是云原生应用的开发者、管理者还是研究人员都有必要了解。

CNCF作为一个厂商中立的基金会，致力于Github上的快速成长的开源技术的推广，如Kubernetes、Prometheus、Envoy等，帮助开发人员更快更好的构建出色的产品。


[](https://jimmysong.io/kubernetes-handbook/images/cncf-org-arch.jpg)

关于CNCF的使命与组织方式请参考CNCF章程，概括的讲CNCF的使命包括以下三点：

* 容器化包装。
* 通过中心编排系统的动态资源管理。
* 面向微服务。

### How to Join

CNCF（云原生计算基金会）是 Linux 基金会旗下的一个基金会，加入 CNCF 等于同时加入 Linux 基金会，总之就是交钱就行。


## CNCF 基本组成

CNCF这个角色的作用是推广技术，形成社区，开源项目管理与推进生态系统健康发展。

另外CNCF组织由以下部分组成：

* 会员：白金、金牌、银牌、最终用户、学术和非赢利成员，不同级别的会员在治理委员会中的投票权不同。
* 理事会：负责事务管理
* TOC（技术监督委员会）：技术管理
* 最终用户社区：推动CNCF技术的采纳并选举最终用户技术咨询委员会
* 最终用户技术咨询委员会：为最终用户会议或向理事会提供咨询
* 营销委员会：市场推广

##  TOC（技术监督委员会）

TOC（Technical Oversight Committee）作为CNCF中的一个重要组织，它的作用是：

* 定义和维护技术视野
* 审批新项目加入组织，为项目设定概念架构
* 接受最终用户的反馈并映射到项目中
* 调整组件间的访问接口，协调组件之间兼容性

TOC成员通过选举产生

## CNCF 孵化器

### 如何成为孵化项目

要想加入 CNCF 必须满足以下条件：

* 项目名称必须在 CNCF 中唯一
* 项目描述（用途、价值、起源、历史）
* 与 CNCF 章程一致的声明
* 来自 TOC 的 sponsor（项目辅导）
* 成熟度模型评估（参考 CNCF Graduation Criteria）
* license（默认为 Apache 2）
* 源码控制（Github）
* 外部依赖（包括 license）
* 创始 committer（贡献项目的时长）
* 基础设施需求（CI/CNCF集群）
* 沟通渠道（slack、irc、邮件列表）
* issue 追踪（GitHub）
* 网站
* 发布方法和机制
* 社交媒体账号
* 社区规模和已有的赞助商
* 用户、使用规模、是否用在生产环境，要有证据说明
* svg 格式的项目 logo

大体流程

https://jimmysong.io/kubernetes-handbook/images/sandbox-process.png

大体流程如下：

通过 GitHub Issue 提交 proposal
TOC 确认项目分类，归类到一个 CNCF SIG 中（两周）
SIG 评估（1到 2 个月）
TOC review
TOC 拉票，至少 3 票（2 个月）
治理和法律问题（CNCF 来处理）


### 孵化项目成熟度

每个CNCF项目都需要有个成熟度等级，申请成为CNCF项目的时候需要确定项目的成熟度级别。

成熟度级别（Maturity Level）包括以下三种：

sandbox（初级）
incubating（孵化中）
graduated（毕业）
是否可以成为CNCF项目需要通过Technical Oversight Committee (技术监督委员会）简称TOC，投票采取fallback策略，即回退策略，先从最高级别（graduated）开始，如果2/3多数投票通过的话则确认为该级别，如果没通过的话，则进行下一低级别的投票，如果一直到inception级别都没得到2/3多数投票通过的话，则拒绝其进入CNCF项目。


### 孵化器项目有什么好处

* CNCF 赞助
* 社区海量的技术贡献
* 扩大公司/团体的社区影响力


## CNCF SIG 
 
CNCF SIG  CNCF Special Interest Groups

为了我们的使命，在扩展CNCF技术版图、增加用户社区贡献的同时保持其完整性和提高贡献质量。

CNCF SIG将监督和协调与最终用户和（或）项目需求的逻辑领域相关的利益。这些领域如安全性、测试、可观察性、存储、网络等。通常由一组CNCF项目来满足SIG监督的领域，也可能是多个项目共享的跨领域特征组（如安全性和可观察性）。 SIG是：

* 是一个长期存在的群体，向技术监督委员会报告
* 主要由相关领域的公认专家领导，并得到其他贡献者的支持

CNCF SIG 以 Kubernetes SIG为模型，旨在最小化差异以避免混淆——此处描述了两者之间不可避免的差异。

# CKA 与 KCSP

## CKA

* 考试说明

考试期间， 除了考试系统界面上的内容和按钮能操作外， 其它的最好不要动。所有考试无关的内容和资料不允许出现， 包括手机， 参考书等等。

考试的时候会提供一个Linux Server Terminal ， 是基于Gateone 的web终端，一些快捷键可能跟一般的linux 终端软件不一样， 请提前了解和体验

考试由31个问题组成， 需要你用命令来解决这些问题

有8套环境， 31个问题在这8套环境里进行操作。

平均每套环境有3~5个问题。

https://jimmysong.io/kubernetes-handbook/images/cka-question.png

FAQ
考试费用？

300美元， 可以重考一次

考试时间长度？

最长4个小时，依赖考生的熟练程度

如何监考？

屏幕共享软件可以让监考官看到考生的屏幕， 所有的音频， 视频和屏幕共享流会被保留一段时间， 用于审查

系统要求？

chrome浏览器， 网络连接， 网络摄像头和麦克风 这个连接可以帮忙检查系统要求 ， 注意Select “Linux Foundation” as the Exam Sponsor and “CKA” as the Exam.

考试期间， 我可以利用什么资源么？

只能打开考试页面以及Kubernetes官网

考试期间是否可以做笔记？

可以做笔记， 但是仅限于在考试控制页面上的工具上

需要什么证件？

包含考生照片的官方认证证件， 比如护照， 身份证， 驾驶证等(注意，需要证件上要有你的英文名称的全名， 对中国居民来讲， 可以使用护照) 需要注册一个Linux Foundation的账号， 到这里注册

考试如何打分？

24小时内会自动打分， 72~75小时内会邮件发送认证结果

认证的有效期？

有效期2年， 在过期之前需要重新考试

取消和重订

在预定考试日期前24小时外，取消或重订， 可以获得完整退费



## KCSP

云原生计算基金会（CNCF）负责维护并整合Kubernetes和Prometheus之类的开源技术，今天它在开源峰会上宣布了22多家Kubernetes认证服务提供商（KCSP）的创始成员名单。KCSP是通过初审的企业组织，它们在帮助企业成功地采用Kubernetes方面有着丰富经验。此外，专业人员个人现在可以注册报名新的认证Kubernetes管理员（CKA）计划和考试。

  KCSP计划的适用对象是通过初审的服务提供商，它们为踏上Kubernetes之旅的公司企业提供Kubernetes支持、咨询、专业服务和培训。KCSP计划确保企业得到它们在寻求的支持，从而比以前更迅速、更高效地部署新的应用程序，同时确保有一家值得信赖、经过审查的合作伙伴可以支持其生产和运营方面的要求。 想成为KCSP，需要至少三名工程师通过认证Kubernetes管理员 CKA 考试，能够证明在Kubernetes社区从事活动（包括积极贡献代码），以及支持企业最终用户的商业模式，包括将工程师派驻客户现场。



# kubernetes 社区

Kubernetes 的社区是以 SIG（Special Interest Group特别兴趣小组）和工作组的形式组织起来的，每个工作组都会定期召开视频会议。所有的SIG和工作组都使用slack和邮件列表沟通。

https://jimmysong.io/kubernetes-handbook/images/kubernetes-sigs.jpg

## Kubernetes社区贡献

贡献指南

KEP 的全称是 Kubernetes Enhancement Proposal，因为 Kubernetes 目前已经是比较成熟的项目了，所有的变更都会影响下游的使用者，对于功能和 API 的修改都需要先在 kubernetes/enhancements 仓库对应 SIG 的目录下提交提案才能实施，所有的提案都必须经过讨论、通过社区 SIG Leader 的批准。

很多不熟悉 Kubernetes 工作流程的开发者会在社区中直接提交一个包含 API 改动的提交，但是这类提交如果没有对应 KEP 是不会被社区合入的。正是因为有了这些机制，我们才可以找到对应功能背后的设计思路以及社区成员对功能的详细讨论，从这些讨论、交流以及最后产出的提案中，我们都能够找到非常多有价值的内容。

https://feisky.gitbooks.io/kubernetes/content/devel/contribute.html

max8899
tossmilestone

https://github.com/kubernetes/community/tree/master/contributors/guide
## 加入  Kubernetes SIG


https://github.com/kubernetes/community/blob/master/community-membership.md