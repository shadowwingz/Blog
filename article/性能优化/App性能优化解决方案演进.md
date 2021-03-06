项目初期

- 只关心崩溃率，不采集性能数据。
- 没有性能检测、优化方案
- 没有排查问题手段

项目壮大期

- 指标采集，不够全及深入
- 接入成熟 APM，排查手段单一
- 线下检测、优化，方案不成型

项目成熟期

- 重点关注性能问题，数据丰富，手段多样化
- 线上、线下一整套完善解决方案
- 自建 APM，新产品可快速接入

线上线下

- 误区：对线上不重视
- 侧重点：线下预防，线上监控
- 方案不同：线下可用黑科技

为什么要自建 APM

- 成熟 APM 通用，但不满足个性化需求

比如我们相对 App 的启动速度细化几个阶段，而不是仅仅看一个最终的指标，这种需求外部 APM 肯定是没法满足的。因为可能我们自己想要细化到 3 个阶段，但是外部 APM 只细化到了 2 个阶段。

- 外部 APM 与内部系统难打通，带来的时间成本

- 数据必须掌握在自己手中 

### 为什么要做性能优化

- 体验差影响核心指标
- 线上问题追查困难
- 降低性能优化的长期开销

### 介绍一下你们的性能平台

- 交代背景
- 具体讲解

在项目初期，我们只是利用了 UncaughtExceptionHandler 接口来捕获 Java Crash，后来我们开始采集了性能指标，同时也接入了商业的 APM，在项目成熟之后，我们开始自建 APM 方案。

### 为什么要自建 APM

- 需求层面

现有的商业 APM 不满足我们个性化需求。

- 效率层面

商业 APM 无法和我们现在的系统相结合，比如查看具体某个用户的行为日志。

- 数据安全

