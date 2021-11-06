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

OpenTelemetry provides you with:

- A single, vendor-agnostic instrumentation library per language with support for both automatic and manual instrumentation.
- A single collector binary that can be deployed in a variety of ways including as an agent or gateway.
- An end-to-end implementation to generate, emit, collect, process and export telemetry data.
- Full control of your data with the ability to send data to multiple destinations in parallel through configuration.
- Open-standard semantic conventions to ensure vendor-agnostic data collection
- The ability to support multiple context propagation formats in parallel to assist with migrating as standards evolve.
- A path forward no matter where you are on your observability journey. With support for a variety of open-source and commercial protocols, format and context propagation mechanisms as well as providing shims to the OpenTracing and OpenCensus projects, it is easy to adopt OpenTelemetry.
- What OpenTelemetry is not
- OpenTelemetry is not an observability back-end like Jaeger or Prometheus. Instead, it supports exporting data to a variety of open-source and commercial back-ends. It provides a pluggable architecture so additional technology protocols and formats can be easily added.

Last modified February 26, 2021: [fixed typo found in issue #465 (#466) (0489f71)](https://github.com/open-telemetry/opentelemetry.io/commit/0489f71b02e6cac6df0af74ac3634cf989748bb7)


## 参考资料

[MTBF, MTTR, MTTA, and MTTF](https://www.atlassian.com/incident-management/kpis/common-metrics)

[MTBF & MTTR](https://zhuanlan.zhihu.com/p/84231209)


