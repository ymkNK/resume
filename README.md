### [Resume](https://lllovol.com/resume)
```java [2-3]
public class SimpleInfo {
        private String name="杨茗凯";
        private String job="后端Java工程师";
        private String mobile="15082362189";
        private String wechat="ymknkcs";
        private String email="ymknkcs@163.com";
        private String blog="lllovol.com"
}
```
### 教育背景
- 南开大学 | 软件工程
- 2015 – 2019 本科
- GPA: 3.34/4
- CET: 6级
- 主修课程: 《JAVA语言与应用》、《高级语言编程实训》、《计算机网络》等

### 在校经历
#### 在校经历 2017年
- 5月,参加南开大学软件学院机器人编程比赛,独立自主编程实现小车的自动循迹以及避障,获得三等奖.
- 6月-8月,参加中软国际科技服务公司实习,作为组长和后端开发主要负责人员,实现基于SPRING架构的红包分发系统.
- 11月,参加校外的在线教育视频公式翻译代码工作,将数学公式转化为LETAX代码,通过代码赚到第一桶金.
#### 在校经历 2018年
- 5月,开发安卓系统的应用,基于NODEJS搭建后端,实现安卓客户端的小游戏,名为“STARINGATGHOST”,上架在阿里的应用商城.
- 6月,参加学校的企业应用开发课程学习,作为子模块后端编写成员,实现了基于DJANGO和LAYUI的光电码盘ERP生产系统.
- 7月,作为团队组长和主要开发人员,参加高校微信小程序开发大赛,完成笔记类作品“勿忘简记”,最终获得华北赛区三等奖.


### 工作经验


- 2018年9月-6月 水滴公司 | 后端研发实习生
- 2019年7月至今 水滴公司 | 效能平台后端工程师

#### 新员工培养体系平台后端研发
- 项目时间：2020-11 至 2020-12
- 项目名称：新员工培养体系平台
- 项目描述：每天大量的候选人,从开始面试、offer发放、信息采集、入职信息办理等流程,均有人力同时手工操作维护,并且大量员工成长教育环节仍由文化同学手动维护,急需一个线上流程承接,函待全面提效.新员工培养体系平台作为一个线上产品承载,将串起从入职前到完全融入水滴的整个过程.

1. 用户三要素验证,同时对接内部多个信息验证系统,包括实名验证、人脸识别等,实现用户登录的身份验证与账号注册.
2. 完成待入职员工的信息收集、验证、审核与通知的自动化.
3. 设计与实现了多个成长地图任务模块,在支持了当前系统的同时,支持将来功能地图的可配置化与可扩展性.
4. 设计与实现了在线视频学习的模块,同样支持了学习视频的可配置化.
5. 设计实现了后台管理系统,能够查看注册人员的相关信息,支持新员工办理好入职手续之后,HR能够及时指派同事接待新员工.
6. 设计实现了线上考试模块系统,支持倒入题库,并且能够根据考试配置信息分别配置多选题、单选题、判断题,随机生成试卷,线上实时答题,离线回归考试状态复盘,实时判卷.
7. 接入人力系统的回调,通过回调的消息实时更新用户信息.
8. 实现根据用户状态、条件、入职时间,在各个任务时间节点给用户推送模板消息.

- 我的职责：参与负责该项目的后端设计与实现
- 项目技术：Spring Boot,MySql,企业微信,微信,ScheduleTask



#### 内部平台代码优化与打点监控
- 项目时间：2020-10 至 2020-11
- 项目名称：内部平台代码与优化与打点监控
- 项目描述：将手中所负责的项目代码进行代码重构与优化,同时增加打点与监控

1. HR系统组织架构同步支持推送携程相关组织信息
2. 支持推送审批结果到携程,员工使用携程时不再需要二次审批
3. 提供人员离职的MQ消息,供二方服务使用
4. 关键节点增加数据打点,同时配置提供相关监控图表
5. 代码优化,注重代码功能的高内聚,低耦合

- 我的职责：独自负责该项目的所有后端设计与实现,以及后台管理页面的简单前端实现.
- 项目技术：Spring Boot,MongoDB,企业微信,ScheduleTask,MicroMeter,Grafana

#### 项目经验-OKR工具

- 项目时间：2020-03 至 2020-05
- 项目名称：OKR工具
- 项目描述：制定OKR的小工具,提供给公司内部员工使用.

1. 集成到企业微信,可以通过企业微信或者扫码进行快速的登录.
2. 可以按照季度、半年、年的维度分别制定多个Objective,每个Objective可以制定多个KerResult.
3. 员工可以搜索查看其它同事的OKR,也可以快速查看自己的平级以及上级以及关注的人员.
4. 可以将Objective进行对齐,同时也可以展示出自己的对齐视图.
5. 支持在OKR页面进行评论功能.
6. 支持艾特功能,通过企业微信发送相应的消息通知.
7. 支持设置权限,可以针对Objective和时间季度设置组织和个人的查看权限.

- 我的职责：独自负责该项目的所有后端设计与实现
- 项目技术：Spring Boot,Vault,MongoDB,AOP,企业微信

#### 项目经验-项目管理系统

- 项目时间：2020-02 至 2020-06
- 项目名称：WADAP项目管理平台
- 项目描述：公司自研项目管理平台,支持开发小组业务线设置、需求管理、bug管理、迭代管理、流程管理、看板、报表管理等功能.
- 我的职责：参与整个项目前期的讨论与设计,主要负责迭代管理模块、燃尽图报表的后端开发和部分前端页面的设计与开发
1. 支持按照业务线、小组创建迭代排期,并且设置相关负责人、迭代时间、备注等信息.
2. 可以批量绑定、批量解绑需求到指定的迭代排期当中.
3. 实现迭代矩阵,可以通过拖拽的方式,对需求的各个阶段进行排期.
4. 可以根据迭代、小组、业务线等维度,展示需求的甘特图.
5. 可以根据迭代、小组展示需求的燃尽图.
6. 可以完成关闭迭代排期,配置可选是否继承未完成的需求,自动生成创建下一周期的迭代排期.
7. 每个人的排期更新可以通过企业微信发送相关通知信息.

- 项目技术：Spring Boot,Spring Cloud,MongoDB,AOP,VUE,企业微信


#### 项目经验-IT&HR技术支持

- 项目时间：2019-08 至今
- 项目名称：HR&IT部门技术支持
- 项目描述：主要为公司多个内部系统之间提供技术服务支持
- 我的职责：作为本项目的第一开发人员和现阶段唯一负责人,和IT和HR方面进行需求对接,并且为其提供技术支持
1. 将HR方面购买的SaaS第三方服务中的人员组织数据同步到AD域.
2. 将AD域中的人员组织数据同步到公司内部数个系统当中.
3. 定时执行相关任务,同时发送相应的执行报表给相关人员.
4. 提供手动触发的入口,提前同步相关数据,并且保证同步任务执行的唯一性.
5. 提供部分信息查询接口供业务方面使用.
6. 实现员工在公司出入口闸机刷卡之后自动打卡的功能.
7. 保证服务的稳定、高效、可扩展性,多次重构优化代码,单次任务时间由几十分钟缩短到几分钟.

- 项目技术： Spring Boot,MongoDB,AD,LDAP,AOP,Feign,ScheduleTask,企业微信,HRIS,嵌入式闸机系统


#### 项目经验-流量系统

- 项目时间：2019-04 至今
- 项目名称：流量系统管理
- 项目描述：基于ISTIO的自研流量管理系统,可以实现不同策略的流量控制效果
- 我的职责：作为本项目的第一开发人员和主要后端开发成员,主要负责以下工作

1. 基于百分比的服务流量控制策略实现.
2. 基于人员手机号、UserId的流量策略实现.
3. 基于自定义Header的流量控制实现.
4. Istio中vs和dr的crd的model封装.
5. 基于Kubernetes Service层面的流量策略管理.
6. 基于相同标签的多服务管理（虚拟环境功能）.
7. 故障注入功能,能够实现小部分流量模拟故障的情况.
8. 虚拟环境的统计数据报表,后端+前端.
9. 流量的可视化多泳道,拓扑图展示.

- 项目技术：Spring Boot,MongoDB,Istio,Kubernetes,ScheduleTask,Vue


#### 项目经验-CI/CD自研平台

- 项目时间：2018-09 至今
- 项目名称：内部自研效能平台Nintendo
- 项目描述：公司内部自研效能平台,支持持续集成、持续部署、多环境部署、灾备部署、回归、服务销毁、自动化代码测试等功能
- 我的职责：作为本项目的第一开发人员和主要后端开发成员,拥有从0到1完整工作经验,也是实习和转正至今的主要工作内容.主要负责以下工作

1. 定期同步研发组织架构信息,定期收集更新公司gitlab所有项目信息.
2. 第一版测试环境发布系统的主要后端实现,支持测试环境的一键发布与回滚.
3. 平台用户登录和账号体系建设,后来接入公司统一Cloud系统.
4. 服务编排Chart模板管理,确定设置服务在环境、语言、版本等情况下所需要使用的Chart模板.
5. 服务编排资源模板管理,确定不同类型的服务所需要使用的资源信息管理,包括cpu、内存等信息模板.
6. 参与平台服务拆分的工作,将逐渐庞大的平台根据职能拆分为不同的微服务.
7. 日常运维平台内部工具的权限自动管理,根据新入职员工的职位自动分配服务各种权限,包括浏览器证书和vpn证书的自动发放.
8. 自动化测试结果的文件收集与归档,上传到cos当中,并且提供相关的接口供平台使用.
9. 平台打通企业微信,部署任务的环境、版本、commit、备注等信息能够在任务结束的时候发送给相关人员.

- 项目技术：Spring Boot,Kubernetes,Jenkins,Redis,MongoDB,Istio,ScheduleTask,Vue,Gitlab,LDAP,AD,企业微信

### 其他方面
- 欲讷于言敏于行,少说多做
- 好记性不如烂笔头,工作两年来每天做的事情,遇到的困难,解决困难的方式,都有记录下来
- 善于倾听，但是也会在日常工作中通过正确的方式表达出自己的想法

### 致谢
感谢您花时间阅读我的简历
