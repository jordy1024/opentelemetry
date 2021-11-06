[原文](https://opentelemetry.io/docs/)

## Documentation

OpenTelemetry 是一组 API、SDK、工具和集成，旨在创建和管理遥测数据，例如链路追踪、指标和日志。 
本文档主要目的是为了最大程度的涵盖了有关如何在您的软件中使用 OpenTelemetry 的关键术语、概念和说明。

![Reference_Architecture](https://raw.githubusercontent.com/jordy1024/opentelemetry/main/docs/images/opentelemetry-Reference_Architecture.svg)

OpenTelemetry 提供其所有组件的实现以及参考架构。 其（设计）较灵活且可扩展，以便支持广泛的开源和商业解决方案以及最终用户的需求。

对于绿地环境，OpenTelemetry Collector 应作为Agent部署在环境中的每个主机上，并配置为将遥测数据发送到用户所需的后端。 
然后应将 OpenTelemetry 仪器库添加到每个应用程序中。 默认情况下，这些检测库配置为将其数据导出到本地运行的收集器。 或者，可以在一个区域中部署一个收集器实例池。

对于棕地环境，Collector 支持许多流行的开源线格式，包括 Jaeger、Prometheus 和 Fluent Bit。 
可以将收集器作为连接 希望利用 OpenTelemetry 或最终转向 OpenTelemetry 支持的开放标准的最终用户的桥梁。

> 有关特定于语言的仪表或收集器的文档指南，请点击导航栏中的链接。


## [Concepts](https://opentelemetry.io/docs/concepts/)
 什么是 OpenTelemetry，它提供什么以及它支持什么？

## [Collector](https://opentelemetry.io/docs/collector/)
 接收、处理和导出遥测数据的供应商无感知方式。

## [C++](https://opentelemetry.io/docs/cpp/)
 OpenTelemetry C++ 实现.

## [.NET](https://opentelemetry.io/docs/net/)
 OpenTelemetry .NET 实现. 

## [Erlang/Elixir](https://opentelemetry.io/docs/erlang/)
 OpenTelemetry Erlang/Elixir 实现. 

## [Go](https://opentelemetry.io/docs/go/)
 OpenTelemetry Go 实现.

## [Java](https://opentelemetry.io/docs/java/)
 OpenTelemetry Java 实现.

## [JavaScript](https://opentelemetry.io/docs/js/)
OpenTelemetry JavaScript (for Node.JS & the browser) 实现.

## [PHP](https://opentelemetry.io/docs/php/)
OpenTelemetry PHP 实现.

## [Python](https://opentelemetry.io/docs/python/)
 OpenTelemetry Python 实现.

## [Ruby](https://opentelemetry.io/docs/ruby/)
 OpenTelemetry Ruby 实现.

## [Rust](https://opentelemetry.io/docs/rust/)
OpenTelemetry Rust 实现.

## [Swift](https://opentelemetry.io/docs/swift/)
OpenTelemetry Swift 实现.

## [Workshop](https://opentelemetry.io/docs/workshop/)
OpenTelemetry 生态运转的一些依赖资源

## [Contribution Guidelines](https://opentelemetry.io/docs/contribution-guidelines/)
如何 贡献 OpenTelemetry 文档



## 参考资料
[Greenfield vs Brownfield
Greenfield vs Brownfield: Understanding the Software Development Differences](https://www.johnadamsit.com/software-development-greenfield-vs-brownfield/)

[Greenfield vs. Brownfield Software Development. What’s the Difference?](https://synoptek.com/insights/it-blogs/greenfield-vs-brownfield-software-development/)

[绿地开发和棕地开发](https://www.jianshu.com/p/8ca541bbf00c)
