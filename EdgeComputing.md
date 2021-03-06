# Edge Computing

(https://www.markdownguide.org/basic-syntax）

## MEC
MEC 创建一个标准化、开放的环境，允许供应商、服务提供商和第三方的应用程序跨多供应商多访问边缘计算平台进行高效、无缝的集成

MEC计划的工作旨在将电信和云世界联合起来，在RAN（无线接入网络）中提供IT和云计算能力。MECISG指定了在多供应商多访问边缘计算环境中托管应用程序所需的元素。

ISG的工作包括制定规范性规范，以及提供信息的报告、白皮书、标准化API的软件实现以及测试和遵从性框架。ISG还积极致力于通过托管概念验证（PoC）和MEC部署试验（MDT）环境以及支持和运行黑客活动来帮助实现和促进MEC生态系统 

## Open Edge Computing Initiative
开放边缘计算计划通过以下方式推动了围绕边缘计算的生态系统的发展：
提供关键边缘功能的参考实现
提供有吸引力的边缘应用程序的现场演示
创建一个真实的边缘计算测试和试验中心（称为LivingEdge实验室）
推动应用程序提供商、电信和云服务提供商采用开放边缘计算

开放边缘计算倡议已经建立了一个由其成员贡献的生活边缘实验室。LivingEdge实验室是一个真实世界的测试平台，展示了边缘计算的好处。并将电信运营商、技术提供商和不同的合作伙伴聚集在一起，展示和衡量将计算推向边缘的效果。


## OpenFog Consortium



## Akraino Edge Stack
是一个Linux基金会项目，它创建了一个开放源码软件栈，支持为边缘计算系统和应用程序优化的高可用性云服务。Akraino项目的任务是在网络边缘培育一个开放源码社区，使新闻服务、生态系统和应用程序依靠加速处理的能力，使云的边缘更接近最终用户和设备。阿克莱诺项目的范围包括在OSI批准的开源许可下支持任务的软件开发，包括文档、测试、集成和创建其他有助于开发的工件，开源软件项目的部署、操作或采用。



### EdgeX Foundry
是一个独立于供应商的开源项目，由Linux基金会托管，为物联网边缘计算构建一个通用的开放框架。该项目采用的关键方法是一个全面的硬件和操作系统无关的参考软件平台，使即插即用组件的生态系统能够统一市场并加速物联网解决方案的部署。

EdgeX Foundry的目标包括：
建立并推广EdgeX作为统一物联网（IoT）边缘计算的公共开放平台
使并鼓励快速增长的IT解决方案提供商社区围绕EdgeExplatform体系结构创建一个可互操作即插即用组件的生态系统
验证EdgeX组件以确保互操作性和兼容性
提供快速创建基于EdgeX的物联网边缘解决方案的工具，这些解决方案可以轻松适应不断变化的业务需求
与相关的开源项目、标准组和行业联盟协作，以确保物联网的一致性和互操作性 

移动边缘平台为应用程序提供了发布、发现和使用服务的能力。它还接收流量规则（由虚拟化基础设施强制执行）、DNS记录、提供持久存储和每日时间信息。移动边缘平台提供的基本服务可以包括无线网络信息、位置服务和带宽管理器，这些都可以通过标准化的api获得。


## 参考架构
### 移动边缘
移动边缘系统层包括移动边缘管理器和操作支持系统（OSS）。移动边缘管理器负责加载应用程序、执行全局管理器和基础设施选择，并跟踪可用资源的所有视图。此外，移动边缘管理器还负责用于驱动应用程序的实例化和终止，支持时根据需要重新定位源。操作支持系统（OSS是指操作器的OSS）。它接收来自用户设备应用程序的实例化或终止应用程序的请求，并决定这些请求的授予。已授权的请求将转发到移动边缘编排器以进行进一步处理。 

面向客户的服务门户允许运营商的第三方客户（如商业企业）选择和订购一组满足其特定需求的移动边缘应用程序，并从提供的应用程序接收回服务级别信息


### Fog计算
Fog计算是一个系统级的水平架构，它将计算、存储、控制和网络的资源和服务沿着云分布到任何地方。它支持多个行业垂直和应用程序域，使服务和应用程序能够更靠近数据生成源进行分发，并从事物、网络边缘、云和多个协议层进行扩展。 
1. Security
2. Scalability
3. Openness
4. Autonomy
5. Programmability
6. Reliability, Availability, and Serviceability (RAS)
7. Agility
8. Hierarchy

OpenFog参考体系结构深入挖掘了可能涉及硅制造商、系统设计师、系统集成商、软件制造商和移动边缘应用程序开发人员的主题


## Edge Architecture 原理和范式
### 相关工作
开发可扩展的体系结构，从封闭系统向开放系统转变，处理数据感知、存储、处理和操作中涉及的隐私和道德问题，设计交互协议和自动化管理。

#### Cloud-centric Internet of Things (CIoT)
一般来说，通用物联网系统涉及三大技术：嵌入式系统、中间件和云服务，嵌入式系统为前端设备提供智能，中间件将前端设备的异构嵌入式系统与云互联，最终云提供综合存储，处理和管理机制。虽然CIoT模型是实现物联网系统的常用方法，但它在物联网方面面临着越来越大的挑战。具体来说，CIoT面临着挑战，因为它模糊了带宽、延迟、不间断、资源限制和安全性
fog是边缘计算的一部分，cloudlet的最初目标是为移动应用程序提供一个来自远程云的替代品，在远程云中，移动应用程序可以将计算密集型任务卸载到位于同一Wi-Fi子网内的附近cloudlet VM机器上。相比之下，最初引入的fog计算旨在通过将云扩展到网络网关本身来完成云计算。从本质上讲，cloudlet可以被视为当位于同一位置的物理服务器机器可用时进行fog计算的实用方法之一。
其他的一些工作已经将multi-access edge computing(MEC; formerly mobile edge computing) 描述为一个与fog computing可交换的术语，ETSI从通信的角度引入MEC作为标准，其中ETSI指定应用程序编程接口（API）标准，关于电信公司如何基于扩展网络功能虚拟化（NFV）中使用的现有基础设施，向客户提供计算虚拟化服务；已经在现有设备中实现，例如蜂窝基站收发信机（BTSS）。尽管将MEC描述为与fog的可交换项是不准确的，但是根据OpenFog和ETSI最近的合作，MEC将成为一种加速fog计算实现的实用方法
在早期阶段，mist计算是fog的另一个术语。然而，最近的作品将mist描述为fog的一个子集。因此，mist阐述了将计算机制分布到物联网设备所在地的极端边缘的需求，以便以毫秒为单位将物联网设备之间的通信延迟最小化。本质上，mist计算的运动是赋予物联网设备在自组织、自管理和若干自\*机制方面的自感知能力。因此，即使在互联网连接不稳定的情况下，物联网设备也能够持续运行。
一般来说，mist设备听起来可能类似于嵌入式服务或移动Web服务，其中应用程序服务托管在诸如传感器、执行器和移动电话之类的资源受限的固有设备上。然而，mist强调了自我意识和情境意识的能力，在这种能力中，它允许根据情境和情境变化动态和远程（重新）将软件程序代码部署到设备上。这样的特性与FAIR相似，提供了一个允许灵活的软件部署和重新配置的平台。

#### fog and edge computing (FEC)
特别地，fog and edge computing (FEC) 提供了5个主要优势，这些优势可以通过SCALE--安全性（security）、认知性（cognition）、灵活性（agility）、延迟性（latency）和效率（efficiency）来体现 
- 安全性（security）
如果FEC基础设施可用，后端可以通过各种FEC节点在整个网络中配置最佳路由路径，以便快速对无线传感器执行软件安全更新。
- 认知性（cognition）
FEC使客户能够意识到在何时何地部署计算、存储和控制功能方面支持自主决策的目标。从本质上讲，对FEC的认识涉及到许多机制，包括自我适应、自我组织、自我康复、自我表达等等，将物联网设备的角色从被动智能设备转移到主动智能设备，这些设备可以持续运行并响应客户需求，而无需依赖来自遥远云端的决策。
- 灵活性（agility）
FEC增强了大规模物联网系统部署的灵活性。相比之下，现有的实用云服务业务模式依赖于大企业主来建立、部署和管理基础设施，FEC为个体和小型企业提供了机会，它们可以使用公共开放软件接口或开放软件开发工具包（SDK）参与提供FEC服务。
- 延迟性（latency）
FEC的共同理解是为需要超低延迟的应用程序提供快速响应。具体来说，在许多广泛的应用和工业自动化中，系统需要以数据流的形式连续地收集和处理感官数据，以便识别任何事件并及时地执行操作。显然，通过应用FEC，这些系统能够支持时间敏感函数。此外，FEC的软件特性，其中物理设备的行为可以通过软件抽象由远程中央服务器完全配置，提供了一个高度灵活的平台，用于快速重新配置IOT设备。
- 效率（efficiency）
FEC在提高CIoT的性能和降低不必要的成本方面提高了CIoT的效率。例如，通过应用FEC，无处不在的医疗保健或老年护理系统可以将多个任务分发到医疗保健传感器的因特网网关设备，并利用网关设备来执行感官数据分析任务。理想情况下，由于进程发生在数据源附近，系统可以更快地生成结果。此外，由于该系统利用网关设备来执行大部分任务，因此它大大降低了输出通信带宽的不必要成本。 

#### FEC如何实现这些优势：SCANC (Storage, Compute, Acceleration, Networking, and Control)
- Storage
临时数据存储和缓存

- Compute
  - VM/container I/P/Saas
  - 按需预置数据处理，上下文特定的定制化数据处理
- Acceleration
  - **网络加速** 软件定义的网络（SDN），FEC节点的客户端可以为其应用程序配置自定义的路由路径，以实现最佳的网络传输速度。
  - **计算加速度** GPU, FPGA，Smart NIC
  
- Networking
FEC的网络包括垂直和水平连接。垂直网络将事物和云与IP网络互连；而水平网络在网络信号和协议方面可能是异构的，这取决于FEC节点支持的硬件规范。
 - 垂直网络 FEC节点使用基于IPnetwork的标准协议（如基于请求/响应的dtcp/UDP套接字、HTTP、Internet工程任务组（IETF）–约束应用协议（CoAP）或基于发布-订阅的灵活消息和状态协议（XMPP）、OASIS–高级消息队列协议（AMQP）来启用垂直网络；ISO/IEC 19464）、消息队列遥测传输（MQTT；ISO/IEC PRF 20922）等等。具体来说，物联网设备可以操作服务器端功能（如CoAP服务器），允许充当云代理的FEC节点从中收集数据，然后将数据转发到云。此外，FEC节点还可以协作作为基于发布-订阅协议的消息代理，该协议允许物联网设备向FEC节点发布数据流，并使云后端能够从FEC节点订阅数据流。
 -  水平联网  基于能量效率或网络传输效率等各种优化需求，物联网系统往往采用异构的、低成本的组网方式。特别是，智能家庭、智能工厂和联网车辆通常在OT设备上使用蓝牙、ZigBee（基于IEEE802.15.4）和Z-Wave，并将它们连接到IP网络网关，以实现设备和后端云之间的连接。一般来说，IP网络网关设备是承载FEC服务器的理想实体，因为它们在各种信号中与物联网设备具有连接。例如，云可以请求承载在联网汽车上的FEC服务器使用ZigBee与路边物联网设备通信，以收集分析实时交通状况所需的环境信息。 

- Control
FEC支持的控制机制包括四种基本类型：部署、驱动、仲裁和安全
- 部署
部署控制允许客户端动态执行可自定义的软件程序部署。此外，客户机可以配置FEC节点来控制FEC节点应该执行哪个程序以及它应该在何时执行。此外，FEC提供者还可以提供一个完整的FEC网络拓扑作为一种服务，允许客户端将程序从一个FEC节点移动到另一个FEC节点。此外，客户端还可以控制多个FEC节点，以实现应用程序的最佳性能。
- 驱动
驱动控制表示硬件支持的机制，以及FEC节点和连接设备之间的连接。具体来说，云可以将某些决策委托给FEC节点，直接控制物联网设备的行为，而不是在云和设备之间执行直接交互。
- 仲裁
仲裁控制对应于FEC与不同当事方拥有的外部实体进行交互的能力。特别是，由不同服务提供商支持的连接车辆可以相互通信，尽管它们最初可能没有共同的协议。利用FEC节点的软件化特性，车辆可以根据需要进行软件更新，以增强其互操作性。
- 安全
运行时环境的认证、授权、身份和保护

#### 层次结构
三个边缘层部署FEC服务器：内缘（inner-edge）、中缘（middle-edge）和外缘（outer-edge）
- 内缘（inner-edge）
内部边缘（也称为近边缘）对应于企业、ISPs、evolvedpack核心（EPC）数据中心和城域网（MAN）的全国、全州和区域广域网。
- 中缘（middle-edge）
中间边缘响应于FEC最常见的理解环境，FEC由两类网络组成：局域网（lan）和蜂窝网。总而言之，局域网包括以太网、无线局域网和校园网。蜂窝网络由宏蜂窝、微蜂窝、微微蜂窝和微蜂窝组成。显然，中间边缘边缘覆盖了广泛的设备来承载FEC服务器。
  -- 局域网  新兴雾计算架构是利用互联网网关设备提供类似于实用云服务的模式，其中网关设备提供虚拟化技术，允许网关设备支持上述FEC机制以前。此外，利用虚拟化技术使位于局域网同一子网内的服务器计算机或具有FEC节点的CAN（campus area network: 即物联网设备和计算机之间的单跳范围内）也是一个理想的解决方案，通常这种方法也称为本地云、本地数据中心或云。
  -- 蜂窝网络
从现有的网络虚拟化技术中衍生出的FEC机制的思想已经在各种蜂窝网络中得到应用。一般来说，大多数发达城市都有由多种类型的基站提供的蜂窝网络的广泛覆盖，这是为各种移动IOT用例服务路侧FEC主机的理想设施。例如连接车辆、移动医疗和虚拟或增强现实，它们需要对实时数据流进行快速处理和响应。因此，主要通信基础设施和设备供应商已经开始提供支持MEC的硬件和基础设施解决方案。因此，可以预见，在不久的将来，基于蜂窝网络的FEC将在各种相关设备中可用，从宏蜂窝和微蜂窝bts到室内蜂窝扩展设备。

- 外缘（outer-edge）
Outer edge（也称为extreme edge、far edge或mist）表示物联网的前端，物联网由三种类型的设备:资源受限设备、集成设备和IP网关设备组成。
  -- 资源受限设备
  传感器或执行器通常由处理能力和内存非常有限的微控制器操作。通常，物联网管理员不希望将复杂的任务部署到此类设备上。然而，由于当今无线传感器和执行器的现场可编程性，物联网系统可以动态地远程更新或重新配置设备的程序代码。显然，这种机制赋予了具有自我意识特性的资源受限物联网设备，并激励了mist计算规程，它强调物联网设备在物联网设备之间相互作用和协作的自我管理能力，以实现高度自治的机器对机器（M2M）环境，而无需依赖远程云进行所有活动。
  
  -- 集成设备
这些设备由具有相当强大处理能力的处理器操作。此外，集成设备在网络（如Wi-Fi和蓝牙连接）、嵌入式传感器（如陀螺仪、加速器）和适当的存储内存中具有许多嵌入式功能。通常，ARM、基于CPU的智能手机和平板电脑（如Android操作系统、iOS设备）是集成设备中最具成本效益的商业产品。他们可以执行感知任务，也可以通过中间边缘设施与云交互。虽然集成设备可能在OS环境中有约束，降低了部署虚拟化平台的灵活性，但是考虑到集成设备中ARM CPU和嵌入式传感器的快速发展，可以预见，在不久的将来，基于虚拟化的FEC将在集成设备上可用。总的来说，在这个阶段，一些平台，如Apache Edgent（Edgent.Apache.org）或termux（termux.com）是在集成设备上实现FEC的有希望的方法。
  
  -- IP网关设备
HUB或IP网关设备充当约束设备和中间边缘设备之间的中介。通常，由于需要节能的无线通信，许多资源受限设备在IP网络中无法工作，这通常需要高能耗的Wi-Fi（如IEEE 802.11g/n/ac）。相反，约束设备使用消耗较少能量的协议来通信，例如蓝牙低能量、IEEE 802.15.4（例如ZigBee）或Z波。此外，由于低能量通信协议不直接与IP网络连接，系统将使用IP网关设备在约束设备和因特网网关（例如路由器）之间中继通信消息。因此，后端云能够与前端约束设备交互。一般来说，基于Linux操作系统的IP网关设备，如Prota的hub（Prota.info）、Raspberry Pi或ASUS Tinker Board，可以轻松地托管虚拟化环境，如Docker Containers Engine。因此，人们普遍认为，研究项目一直在利用IP网关设备作为FEC节点。
  






参考信息  
[ETSI - Multi-accessEdge Computing](https://www.etsi.org/technologies-clusters/technologies/multi-access-edge-computing)  
[OpenFog Consortium](https://www.openfogconsortium.org/)  
[StarlingX](https://www.starlingx.io/)  
[Airship](https://www.airshipit.org/)  
[Akraino](https://www.akraino.org/)  
[EdgeXFoundry](https://www.edgexfoundry.org/)  












