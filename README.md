# newbee
start a new point in my option
#baby's name
*maomujing*
##baby's sex

## 整体架构
TITAN整体由如下5部分子系统构成：
- **Manager**：管理控制台，负责链路、场景等相关信息管理，以及获取压测的业务指标数据与监控指标数据；
- **TaskService**：负责具体的压测任务编排工作，并将压测任务信息下发给空闲Agent；
- **Agent**：压测引擎，向ZK注册心跳、获取压测任务并执行；
- **Monitor**：负责收集压测引擎、目标机器的CPU、内存、磁盘IOPS等监控指标数据；
- **DataCollect**：负责收集压测数据并实施上报。
==to be honesty i don't know and care==
