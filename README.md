# DB Observer

## 简介

![](pic/observer128.png)数据库观察者项目，致力于提供一套开源地全面解决混合云数据库日常监控告警的功能。

* 多种采集器：提供了30+的数据库相关的采集器，2800+的重要指标
* 多种云平台：提供了多种云平台数据库产品，包含 关系型、文档形、KV型等100+的数据库产品。例如 `aliyun`、`Amazon`、`Tencent`、`Azure`等云数据库产品。
* 数据库包括：MySQL、SQLServer、Oracle、PostgreSQL、Redis、MongoDB等单实例、复制、集群架构。
* 特性齐全：提供了全面、美观的文档。你能在这里找到关于 数据库产品采集器、视图模版、告警规则等方面的所有详细文档。

让数据库监控更快速、简单。所有用户都能快速上手、所有数据库都可以适配、所有项目都适用。

可以帮助所有使用数据库的企业提升工作效率，降低故障时间，提升数据安全。


## 技术栈

本项目使用的是
1. [Influxdata](https://www.influxdata.com/)公司的开源TICK技术栈；
2. Python开发拓展的采集器，完成telegraf不支持的采集，类似Oracle的指标采集、云上数据库指标的采集；
3. 根据实际运维场景设计的数据洞察模版；
4. 根据实际运维场景设计的告警规则；
5. 自定义开发接口实现从kapacitor到钉钉机器人的自动告警调度


TICK是Telegraf、InfluxDB、Chronograf和Kapacitor四个软件的首字母缩写。它是Influxdata公司推出的监控套件，承包指标采集、分析、画图等时序数据库上下游的工作，有点模仿日志分析系统ELK套件的意思。

目前企业级解决方案提供商有（收费）：

1. [Influxdata](https://www.influxdata.com/)的企业版。*开源版和企业版的主要区别就是企业版的InfluxDB和Kapacitor软件支持集群，而开源版不支持，此外企业版提供了先进的备份/恢复功能，而开源版本没有。这是开源软件常见的运作模式，通过代码开源吸引更多的人使用和参与开发，通过增值功能和服务支持获取商业利益。*
2. [DataDog](https://www.datadoghq.com/)提供了一个实时指标监视和流分析平台，是一项云托管服务，属于SaaS。
3. [wavefront](https://www.wavefront.com/) 2017年5月，VMware收购了位于加利福尼亚帕洛阿尔托的私有公司Wavefront。Wavefront提供了一个实时指标监视和流分析平台，是一项云托管服务，属于SaaS。
4. [DataFlux](https://www.dataflux.cn/) 阿里投资的驻云科技旗下的一款实时指标监视和流分析平台，提供PaaS和SaaS两种方式。

## 项目迭代

### 第一个迭代

|计划|时间|内容|
|:--|:--|:--|
|第一期|`2020-04-20`~`2020-07-20`|采集器22|
|第二期|`2020-07-20`~`2020-07-30`|数据洞察-采集器维度22|
|第三期|`2020-08-01`~`2020-08-30`|数据洞察-数据库维度223|
|第四期|`2020-09-01`~`2020-09-31`|告警规则-？|

### 第二个迭代

在第一个迭代基础上进行优化

## 快速入门

待补充

# 关于我们

![](pic/solar.png)SuperCloudDBA 我们一直致力于为小伙伴们提供更多的优质技术文档和数据库自动化运维管理工具！
