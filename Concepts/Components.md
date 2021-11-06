[原文](https://opentelemetry.io/docs/concepts/components/)

## 组件
OpenTelemetry 项目由多个组件组成。 
这些组件作为单一实现提供，以简化其利用并确保提供与供应商无关的解决方案。 将来可能会添加更多的组件。


### 协议
Language independent interface types. Defined per data source for instrumentation libraries and the collector as well as for common aspects and resources. Proto files are extensively commented. For more information, see the proto repository.
语言无关的接口类型。 为检测库和收集器以及公共方面和资源定义单独的数据源。 
协议文件被广泛评论。 有关更多信息，请参阅 proto 存储库。

### 规范
描述所有实现的跨语言要求和期望。 除了术语的定义之外，规范还定义了以下内容：

- **API**: （API主要）用来生成遥测数据。 定义各种数据源以及其他方面（包括包和传播器）
- **SDK**: （SDK）是API的（具体）处理和导出功能的具体实现。定义了每种数据源以及其他的方面，包括资源和配置。
- **Data**: (Data)定义了语义约定以提供与供应商无关的实现以及 OpenTelemetry 协议 (OTLP)。有关更多信息，请参阅[规范存储库)(https://github.com/open-telemetry/opentelemetry-specification)。
- **Data**: Defines semantic conventions to provide vendor-agnostic implementations as well as the OpenTelemetry protocol (OTLP).

### 收集器

OpenTelemetry Collector 在 接收、处理和导出遥测数据等方面 提供了与供应商无关的实现。 
（在 OpenTelemetry 出现之前），为了支持将开源可观测性数据格式发送到不同的开源/商业后端，（往往）需要运行，操作和维护各种Agent或collectors。
（而 OpenTelemetry 的出现极大的改观了这种局面）
采集器Collector是导出其遥测数据的默认本地检测库。


有关更多信息，请参阅[数据采集器部分](https://opentelemetry.io/docs/concepts/data-collection/) 


### 检测库

OpenTelemetry 项目的灵感是通过让每个库和应用程序直接调用 OpenTelemetry API 以使其开箱即用。 
在此之前（既在OpenTelemetry未出现之前），（往往）需要（引入）一个单独的库来注入此类（相关）信息。 
（您可以这样理解检测库的定义），既能够让另一个库具有可观察性的库称为检测库。 
OpenTelemetry 项目为多种语言提供了一个检测库。 
所有检测库都支持手动（代码修改）检测（及侵入代码），并且有几个支持自动（字节码）检测。



有关更多信息，请参阅[检测部分](https://opentelemetry.io/docs/concepts/instrumenting/)。

Last modified February 15, 2021: [Cleanup the component docs (#378) (16aff06)](https://github.com/open-telemetry/opentelemetry.io/commit/16aff06510b7c978ae894b7e3b9e23e3c2bffd19)

