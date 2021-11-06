[原文](https://opentelemetry.io/docs/)

## Documentation

OpenTelemetry 是一组 API、SDK、工具和集成，旨在创建和管理遥测数据，例如链路追踪、指标和日志。 
本文档主要目的是为了最大程度的涵盖了有关如何在您的软件中使用 OpenTelemetry 的关键术语、概念和说明。

![Reference_Architecture](https://raw.githubusercontent.com/jordy1024/opentelemetry/main/docs/images/opentelemetry-Reference_Architecture.svg)

OpenTelemetry provides an implementation of all of its components as well as a reference architecture. The project is flexible and extensible to support a broad range of open-source and commercial solutions as well as end-user needs.

For greenfield environments, the OpenTelemetry Collector should be deployed as an agent on each host within an environment and configured to send telemetry data to the user’s desired back-end(s). OpenTelemetry instrumentation libraries should then be added to each application. By default, these instrumentation libraries are configured to export their data to a locally running Collector. Optionally, a pool of Collector instances can be deployed in a region.

For brownfield environments, the Collector supports many popular open-source wire formats including Jaeger, Prometheus, and Fluent Bit. The Collector can serve as a bridge for end-users who either desire to leverage OpenTelemetry or eventually move to the open standards OpenTelemetry supports.

> For documentation and guides on language-specific instrumentation or the Collector, please follow the links in the navigation bar. 
