量子医疗专家系统 
======
Quantum Medical Expert System，简称Q-MES，是一个应用在医疗咨询场景中专家系统框架。

该框架将患者在咨询中的问题转化成为结构化的患者主诉后，通过触发建造在三元特征组之上的规则引擎，形成给用户智能化的建议。

核心功能
-----
* 基于Drools的更实用的规则引擎，支持模糊化，支持在非执行状态下的匹配，支持错误检查。
* 对于时序化的指标进行处理，形成定量的指标特征。
* 将特征进行三元组方式的编辑，支持模糊的查找和匹配。
* 支持结构化案例的编写。

程序特性
-----
* 在JAVA 8下编译通过。
* 独立的GUI应用，非Client/Server架构。
* 跨平台，在Windows/Mac/Linux均能运行。

工程特性
-----
* 本Maven工程在Eclipse 4.7.2下运行。

其他说明
-----
* 程序第一次启动的时候，需要设置一个文件夹的路径作为启动参数。

联系作者
-----
在Github的readme.md上可以找到创作团队。
需要获得更多的已经成型的测试数据，可以和创作团队交流。
