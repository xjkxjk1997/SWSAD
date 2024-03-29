# 系统分析第二次作业

1. 简答题
    1. 用简短的语言给出对分析、设计的理解。  

        分析强调的是对问题和需求的调查研究，而不是解决方案。解决的是一个新系统的功能的决定，即do the right thing。  
        设计强调的是满足需求的的概念上的解决方案（在软件方面和硬件方面），而不是其实现，例如数据库模式和软件对象的描述。解决的是正确构建软件系统框架，即do the thing right。  
    2. 用一句话描述面向对象的分析与设计的优势。  

        面向对象的分析与设计是语言无关的，分析与设计师不必精通编程语言。因此可以：
        * 软件人员在分析阶段使用通用符号和软件应用领域的专家进行高效地沟通；
        * 该问题领域的专家和实施领域的专家使用通用符号进行沟通；
        * 在设计阶段继续使用这种符号进行软件概念上的设计。  

    3. 简述 UML（统一建模语言）的作用。考试考哪些图？  

        UML是用于描述分析与设计结果的简单、高效的标准图表语言，用于说明、可视化、构建和编写一个正在开发的、面向对象的、软件密集系统的制品。  
        根据不同的用途的作用也不尽相同：  
        * 作为草图：借助可视化语言的功能，用于探讨问题或解决方案空间的复杂部分；
        * 作为蓝图：用于逆向工程，以UML图的方式对现有代码进行可视化和代码生成；
        * 作为编程语言：用UML完成软件系统可执行规格说明；

        考试考：用例图、静态图、行为图、实现图。

    4. 从软件本质的角度，解释软件范围（需求）控制的可行性。

        计算机软件是于操作有关的程序、以及与之相关的文档集合。软件的本质决定了软件开发的困难，软件的本质特性为：
        * 复杂性 (complexity)
        * 一致性 (conformity)
        * 可变性 (changeability)
        * 不可视性 (invisibility)

        软件可变和不可视的本质特性，导致在实际软件项目中，即使有明确的开发合同，无法先给一个样品参考标准，也无法在项目开发完成前写出完善的软件需求规格书。  
        项目的首要约束是工期、范围、质量和预算四个而基本元素（项目管理三角模型）。一个项目合约，即是关于四个元素在理论上的精确的约定。项目管理的任务就是优化调度资源使得这些约束得以满足，且最低的成本。  
        又因为软件复杂、不一致的本质特性，多数情况，客户与开发者能就项目的 20% 内容给出严格的需求约定，80% 的内容都是相对模糊的。  
        所以软件需求控制就是可行的，只要能很好地细化20%的有效要求，就能满足80%的客户需要。整个团队就能更少的付出，更多的收获。

2. 项目管理实践

    ![avatar](https://github.com/XXXXIEHF/SWSAD/blob/master/HW/kanban-2.PNG)

3. UML绘图工具练习

    《UML与模式应用》P228 图17-27  
    ![avatar](https://github.com/XXXXIEHF/SWSAD/blob/master/HW/UMLet-2.png)