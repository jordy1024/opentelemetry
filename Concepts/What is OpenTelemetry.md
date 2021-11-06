[原文](https://opentelemetry.io/docs/concepts/what-is-opentelemetry/)

## What is OpenTelemetry?
OpenTelemetry 是一组 API、SDK、工具和集成，旨在创建和管理遥测数据，例如跟踪、指标和日志。 
该项目提供了一个与供应商无关的实现，可以将其配置为将遥测数据发送到您选择的后端。 
它支持各种流行的开源项目，包括 Jaeger 和 Prometheus。

### Why you need OpenTelemetry and what it can do
在云原生技术栈中，分布式和多语言架构是常态。 
分布式架构带来了各种运营挑战，包括如何快速解决可用性和性能问题（既所谓的缩短MTTR）。 
这些挑战导致了可观测性的兴起。

可观测性的项目（本质）上是基于遥测数据。 
一般情况下，遥测数据由开源项目或商业供应商提供。 
但（这样一来）由于缺乏标准化，最终会导致数据缺乏可移植性并造成用户仪表盘的维护的（更多）负担。

OpenTelemetry 项目通过提供单一的、与供应商无关的解决方案来解决这些问题。 该项目得到了云提供商、供应商和最终用户的广泛行业支持和采用。

OpenTelemetry 为您提供：

- 提供单一的、与供应商无关的多语言仪表库，支持自动和手动两种方式。
- 提供多方式部署的收集器BIN程序，包括作为Agent或网关部署。
- 支持生成、发送、收集、处理和导出遥测数据的端到端实现。
- 数据（操作）自主可控，您能够通过配置将数据并行发送到多个目的地。.
- 开放标准语义规范，以确保的数据收集与供应商无关.
- 能够并行支持多种上下文传播格式，以支持因标准发展或变化而必须的迁移。
- 无论您（的项目）处于可观测性（对接）的哪个阶段，都可以继续向前。 
  可以通过支持OpenTelemetry各种开源和商业协议、格式和上下文传播机制 或者 将 OpenTracing 和 OpenCensus 项目 进一步融合，（这样以来）就很容易采用 OpenTelemetry。

### What OpenTelemetry is not
OpenTelemetry 不是像 Jaeger 或 Prometheus 那样的可观察性后端。 
相反的，它支持将数据导出到各种开源和商业后端。 它提供了可插拔架构，因此可以轻松添加其他技术协议和格式。

上次修改时间为 2021 年 2 月 26 日： [fixed typo found in issue #465 (#466) (0489f71)](https://github.com/open-telemetry/opentelemetry.io/commit/0489f71b02e6cac6df0af74ac3634cf989748bb7)


## 参考资料

[MTBF, MTTR, MTTA, and MTTF](https://www.atlassian.com/incident-management/kpis/common-metrics)

[MTBF & MTTR](https://zhuanlan.zhihu.com/p/84231209)


