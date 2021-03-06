3/18/2021 11:18:11 AM 

#3 CT-接入网组成与部署
本课程是面向中国联通智慧网络工程师，通过此次培训学习，可以为客户提供PON方式的组网配置，以满足客户个性化业务需求。课程主要包括三部分，第一部分为PON技术标准，第二部分为PON有源器件，第三部分为PON主流设备与故障案例分析。通过课程深入的分析与讲解，为进一步提升PON业务故障处理水平打下了坚实的基础。
##3.1 有线接入网
###3.1.1 接入网的定义
####3.1.1.1 电信网
电信网按照网络功能分为三个部分，接入网 交换网和传输网。
####3.1.1.2 接入网
* 负责将电信业务透明传输给用户，用户通过网络接口，能灵活的接入到不同的业务节点上。
* 接入网包括业务节点到用户设备之间所有实施设备与线路
####3.1.1.3 接入网的特点
（1）成本敏感：接入网直接面向用户，数据较多，规模庞大，其建设与维护成本与所选技术有很大的相关性。    
（2）业务类型多样化、数据化：可以承载宽带、语音数据、和多媒体接入等多种综合业务。  
（3）业务体现的不对成性和突发性  
（4）接入手段多样化  
####3.1.1.4 有线接入网分类  
（1）铜线接入网  
（2）光纤接入网  
光纤接入网（Optical Access Network，OAN）是指在接入网中采用光纤作为主要传输介质实现信息传送的方式。（**业务节点和用户之间采用光纤通信或者部分光纤通信**）

* Active Optical Network 有源光网络 
AON网络的传输设备采用的是有源器件
* Passive Optical Network 无源光网络
PON网络中的传输设施是无源光器件(**不含光能源的光功能器件的总称**)组成，根据采用的技术不同又分为以下几种。
 * ATM无源光网络（APON）：基于ATM技术的无源光网络，后更名为宽带PON（Broadband Passive Optical Network BPON）。
 * 以太网无源光网络（EPON）：基于以太网技术的无源光网络。
 * 吉比特无源光网络（GPON）：GPON是BPON的一种扩展。
* AON与PON的比较
 * AON比PON传输距离长传输容量大，业务配置灵活，但不足之处是成本高，需要供电系统，维护复杂，而PON结构简单，易于扩展和维护，所以PON得到越来越广泛的应用。   
  
 （3）混合接入网

##3.2 PON网络
###3.2.1 网络组成
无源光网络主要包含如下配置：  
（1）光线路终端（**Optical Line Terminal**）    
提供光纤接入网提供网络侧（**核心网**）与业务节点的接口，并经过一个或者多个ODN与用户侧的ONU通信，OLT与ONU为主从通信关系。  
（2）光网络单元（**Optical Network Unit**）  
光电转换，实现电信号的处理与维护、       
（3）光分配单元（**Optical Distribution Network**）     
接入网中的传输设施，为ONU和OLT提供光传输通道。  
（4）AN系统管理模块  
负责对光纤接入网进行维护管理，包含配置管理，性能管理，故障管理和安全管理和计费管理。
###3.2.2 拓扑结构
* 星型结构
* 树形结构
* 总线型结构
###3.2.3 PON传输技术
####3.2.3.1 双向传输技术（复用技术）
主要技术是波分复用技术（**上下行波长不同**）
####3.2.3.2 多址接入技术
多个ONU与同一个OLT进行通信，多点用户的上行接入需要多址接入技术。主要采用的是**光时分复用**。

##3.3 以太网无源光网络（EPON）
##3.4 吉比特无源光网络(GPON)

