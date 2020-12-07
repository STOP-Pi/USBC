# [USB](https://github.com/Qful/USB)

[![sites](http://182.61.61.133/link/resources/Qful.png)](http://www.Qful.net)
## [USB简介](https://github.com/Qful/USB)

[USB](https://github.com/Qful/USB)项目通过将USB的一些特性单独整理成功能模块，保证相关技术和资源的复用，也便于各种工程集成后的维护和深度开发。

该为type-c接口的各种特性使用，包括PD和视频信号输出，通过DEMUX电路实现更多功能的集成和智能的选择使能，该单元是可编程控制单元，有自己的协议和相应的管理范围。

[![sites](docs/1.png)](http://www.Qful.net)
[![sites](docs/2.png)](http://www.Qful.net)

USB Type-C是一个全新的正反插USB连接器规范，能够支持USB 3.1（Gen1和Gen2）、Display Port和USB PD等一系列新标准，最高速率可达10Gbps，Type-C端口默认最高可支持5V3A。

#### CC(Configuration Channel)

配置通道，这是USB Type-C里新增的关键通道。它的作用有检测正反插，检测USB连接识别可以提供多大的电压和电流，USB设备间数据与VBUS的连接建立与管理等。

#### DFP(Downstream Facing Port)

下行端口，可以理解为Host，DFP提供VBUS，可以提供数据。在协议规范中DFP特指数据的下行传输，笼统意义上指的是数据下行和对外提供电源的设备。典型的DFP设备是电源适配器。

#### UFP(Upstream Facing Port)

上行端口，可以理解为Device，UFP从VBUS中取电，并可提供数据。典型设备是U盘，移动硬盘。

#### DRP(Dual Role Port)

双角色端口，DRP既可以做DFP(Host)，也可以做UFP(Device)，也可以在DFP与UFP间动态切换。典型的DRP设备是笔记本电脑。
