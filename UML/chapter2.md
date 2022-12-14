# 2.4 OOSE方法
## Jacobson于1944年提出了面向对象软件工程--OOSE方法,最大的特点是面向用力(usecase),并在用例的描述中引入了外部角色(actor)的概念
>OOSE采纳了以下三项技术的成果  
>>面向对象编程技术(OOP)  
>>概念建模法:为分析系统建立的各种模型,需求,分析,设计,实现,测试模型  
>>块设计:模块化设计  

## Jacobson博士介绍
>曾任瑞士爱立信公司的首席软件架构师,负责了AXE交换机的研发.  
>他在使用的对象方法设计大型实时系统方面已经有超过25年历史.  
>发明了顺序图和协作图,发明了对整个软件工业影响重大的用例,创造了OOSE软件工程方法,世界上面向对象软件工程方法的领军人物.  
>UML三友之一  

## OOSE方法
>OOSE方法是所谓的用例驱动方法(Use Case Driven Approach),在这个方法中,用例模型充当了导出其他模型的中心模型.  
用例模型以系统外部参与者的角度描述了系统的完整功能,最大的特点是映入了用例的概念
>>用例是系统与系统用户(参与者)之间为了特定目的(或者功能)而产生的特点相互作用.系统的用户可以使人,机器,另一个系统.

## OOSE的三个阶段
>分析阶段(analysis)  (包含着需求阶段)  
>>产生分析模型和子系统描述集  

>构造阶段(construction)  
>>细化分析阶段产生的模型  
成果:模块模型,模块接口,模块规范

>测试阶段(testing)  
>>验证系统的正确性

## 2.4.1 分析阶段
分析阶段产生两种模型,即需求模型和分析模型

>需求模型  
>>从用户的角度描述了系统所有的功能需求,使用方式,位系统定义了便捷,定义了功能,需求模型由以下三部分组成:  
用例模型,描述了参与者和用例  
问题域对象模型,描述了系统的逻辑视图  
接口描述,定义了与外部系统的接口

>分析模型
>>通过为三种类型的对象建模,接口对象,实体对象,控制对象,对应于OOA中的边界类,实体类,控制类.  
需求模型中的用例模型所描述的行为在分析模型中的对象间(3类对象)展开,分析模型为设计奠定了基础.  
OOSE方法没有建立需求模型和分析模型的步骤--不足之处

## 2.4.2 构造阶段
构造阶分为两步,即设计和实现
>设计:由三个阶段组成  
>1. 确定系统的实现环境,设计方案依赖于实现环境,战略性决策与实现环境密切相关  
>2. 建立设计模型,分析对象被转变为适合于实现环境的设计对象  
>3. 描述每个用例中对象间的交互作用(协作关系),产生对象接口  
该阶段,设计模型细化分析模型,使模型适合于实现环境  

>设计阶段还要定义对象的接口和操作的语义,决策使用的数据库管理系统和编程语言,为对象类型引入块,以隐藏实际的实现.  
由交互作用图和状态跃迁途组成

>实现
>>用编程语言实现系统

## 2.4.3 测试阶段
验证系统是否符合开发要求
