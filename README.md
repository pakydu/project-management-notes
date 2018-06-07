# 项目管理学习笔记与经验教训

最近在参加 PMP 培训，意在能学习一套科学规范的项目管理知识体系，在实际工作中有机会参与到一些相关过程时，作为理论依据来参考、引申。

本仓库会记录我培训过程中认为重要的一些笔记、问答，以后后续在项目实践中的经验教训。

**目录**

<!-- vim-markdown-toc GFM -->

* [概述](#概述)
    * [五大过程组](#五大过程组)
    * [十大知识领域](#十大知识领域)
    * [项目管理过程组与知识领域](#项目管理过程组与知识领域)
* [计算](#计算)
    * [挣值管理](#挣值管理)
* [考试通关秘籍](#考试通关秘籍)

<!-- vim-markdown-toc -->

## 概述

### 五大过程组

* 启动过程组

* 规划过程组

* 执行过程组

* 监控过程组

* 收尾过程组

### 十大知识领域

* 项目整合管理

* 项目范围管理

* 项目进度管理

* 项目成本管理

* 项目质量管理

* 项目资源管理

* 项目沟通管理

* 项目风险管理

* 项目采购管理

* 项目相关方管理

### 项目管理过程组与知识领域

| #                  | 启动过程组       | 规划过程组                                                                                                        | 执行过程组                                       | 监控过程组                                  | 收尾过程组         |
|--------------------|------------------|-------------------------------------------------------------------------------------------------------------------|--------------------------------------------------|---------------------------------------------|--------------------|
| 4. 项目整合管理    | 4.1 制定项目章程 | 4.2 制定项目管理计划                                                                                              | 4.3 指导与管理项目工作<br />4.4 管理项目知识     | 4.5 监控项目工程 <br />4.6 实施整体变更控制 | 4.7 结束项目或阶段 |
| 5. 项目范围管理    |                  | 5.1 规划范围管理<br />5.2 收集需求<br />5.3 定义范围<br />5.4 创建 WBS                                            |                                                  | 5.5 确认范围 <br />5.6 控制范围             |                    |
| 6. 项目进度管理    |                  | 6.1 规划进度管理<br />6.2 定义活动 <br />6.3 排列活动顺序<br />6.4 估算活动持续时间<br />6.5 制定进度计划         |                                                  | 6.6 控制进度                                |                    |
| 7. 项目成本管理    |                  | 7.1 规划成本管理<br />7.2 估算成本<br />7.3 制定预算                                                              |                                                  | 7.4 控制成本                                |                    |
| 8. 项目质量管理    |                  | 8.1 规划质量管理                                                                                                  | 8.2 管理质量                                     | 8.3 控制质量                                |                    |
| 9. 项目资源管理    |                  | 9.1 规划资源管理<br />9.2 估算活动资源                                                                            | 9.3 获取资源<br />9.4 建设团队<br />9.5 管理团队 | 9.6 控制资源                                |                    |
| 10. 项目沟通管理   |                  | 10.1 规划沟通管理                                                                                                 | 10.2 管理沟通                                    | 10.3 监督沟通                               |                    |
| 11. 项目风险管理   |                  | 11.1 规划风险管理<br />11.2 识别风险<br />11.3 实施定性风险分析<br />11.4 实施定量风险分析<br />11.5 控制风险应对 | 11.6 实施风险应对                                | 11.7 监督风险                               |                    |
| 12. 项目采购管理   |                  | 12.1 规划采购管理                                                                                                 | 12.2 实施采购                                    | 12.3 控制采购                               |                    |
| 13. 项目相关方管理 | 13.1 识别相关方  | 13.2 规划相关方参与                                                                                               | 13.3 管理相关方参与                              | 13.4 监督相关方参与                         |                    |

## 计算

### 挣值管理

缩写：

| 缩写 | 含义             | 全称                   |
|------|------------------|------------------------|
| AC   | 实际成本         | Actual Cost            |
| BAC  | 完工预算         | Budget At Completion   |
| CPI  | 成本绩效指数     |                        |
| EAC  | 完工估算         | Estimate at Completion |
| ETC  | 完工尚需估算     | Estimate to Completion |
| EV   | 挣值             | Earned Value           |
| PV   | 计划价值         | Planned Value          |
| SPI  | 进度绩效指数     |                        |
| TCPI | 完工尚需绩效指数 |                        |

公式：

- 成本偏差：CV = EV - AC

- 成本绩效指数：CPI = EV / AC

- 进度偏差：SV = EV - PV

- 进度绩效指数：SPI = EV / PV

- 完工尚需绩效指数：TCPI = (BAC - EV) / (BAC - AC)

    代表要按预算完工，资金的使用效率要求。

    若管理层认为 BAC 无法实现，则 TCPI = (BAC - EV) / (EAC - AC)

- 完工估算：EAC = ETC + AC

- 完工偏差：VAC = BAC - EAC

- ETC

    - 按预算完成剩余工作：ETC = BAC - EV

    - 以当前 CPI 完成剩余工作：ETC = (BAC - EV) / CPI

    - SPI 和 CPI 同时影响剩余工作：ETC = (BAC - EV) / (CPI * SPI)

其它相关知识点：

- 如果有管理储备，BAC = 总预算 - 管理储备

## 考试通关秘籍

1. 组织过程资产包括模板、数据库、经验教训三大类。

    模板、数据库是相对客观资料，经验教训都是主观总结出来的成功与失败之处。

    经验教训必须和主动选择有关，你的选择让你感到得意或者后悔的事情。

    问题一般相对客观，与主动选择无关。

2. 问题和风险的区别：

    1. 问题一般与人的责任、能力、人的主动性有关，不主动、不负责任、缺乏能力；

    2. 风险更偏重于天灾，有不可抗性，与人的责任、主动性、能力关系较弱，或无关。

    3. 问题和风险共通性：风险发生即为问题，问题出现会导致风险发生。

3. 强调统计技术的 4 个工具：问卷调查、实验设计、预期货币价值分析、参数估算。

4. 使用储备分析的 5 个过程：

    * 6.5 活动持续时间估算

    * 7.2 估算成本

    * 7.3 制定预算

    * 7.4 控制预算

    * 11.6 控制风险

5. 规划过程组中唯一在输出中出现变更请求的：规划采购。

6. 4-13 章唯一不出现专家判断工具的：项目质量管理。

7. 监控过程组中，输出没有变更请求的：整体变更控制。

8. 执行过程组中，输出中没有变更请求的 3 个过程：

    * 9.2 组建团队

    * 9.3 建设团队

    * 10.2 管理沟通

9. 收尾过程组的两个过程，输入都有：项目管理计划。

10. 监控过程组的所有过程，输入都有：项目管理计划。

11. 执行过程组的所有过程，输入中都没有项目管理计划的所有部分，只有其中某几个。

    但 4.3 指导与管理项目执行除外。

12. 输出中出现变更请求，都会出现项目管理计划更新。

    但 5.5 确认范围、12.1 规划采购除外。

13. 规划过程组、执行过程组、监控过程组输出中都可以出现“项目文件更新”，几乎也都有，9.2、9.3 除外。

14. 自下而上的估算出现在 2 个过程：

    * 6.3 估算资源

    * 7.2 估算成本

15. 检查作为工具在 5.5 确认范围 和 8.3 质量控制 出现过。

16. ~~制定进度计划过程输出中，没有“变更请求”却有“项目管理计划更新”~~。

17. 滚动式技术：创建 WBS 和定义活动。

18. 范围、进度、成本、质量四个章节最后的组织过程资产更新，强调“偏差原因，所选措施及其理由”，之后的章节，该内容变为“问题原因，所选措施及其理由”。

19. 无 CCB 批准更新的选项，只能选提交客户批准。

20. 过程稳定性，控制上下线 --> 控制图。

21. 如果测量值超出控制线，或出现 7 点法则，意味着过程失控需要找根本原因，以便进程过程改进。

22. 管理团队和管理干系人都需要使用问题日志。

22. 预防冲突的方法：

    * 对管理干系人而言，就是尽早识别干系人，并让干系人尽早参与。

    * 对管理团队而言，包括 采用团队规则、团队规范及成熟的项目管理实践，如沟通规划和角色定义。

23. 时间不够选进度压缩（还可选：模拟技术、调整提前量与滞后量，但很少出现）。

    进度压缩分为（前提是不改变范围）：

    1. 赶工（关键路径上的活动上加资源，有富余成本）

    2. 快速跟进（将关键路径上本来串行的工作并行。关键路径上的活动关系并非都是强制性的，有可选择的。）

24. 赶工要考虑 2 点：

    * 关键路径上活动赶工

    * 选择赶工成本最低的活动

25. 投标人大会

    什么时间召开？空白标书发给潜在干系人后，正式投标之前（实施采购过程），目的是让潜在干系人向买方充分了解需求。

    采购工作说明书（SOW）的作用：详细描述采购的产品、服务或成果，以便潜在卖方确定他们是否有能力提供这些产品、服务或成果。

    原则：公平原则

    修正案方式：更新到采购文件中

26. 验收可交付成果属于确认范围过程（5.5）

    属于监控过程组，不是收尾内容。

    项目或阶段收尾时，客户或发起人也要验收，但验收的不是可交付物，而是最终产品、服务或成果。

    确认范围中所产生的验收文件，是项目或阶段收尾的输入，而非输出。

    验收可交付物成果在前，收尾在后。

27. 资源变化影响资源日历，进度变化影响资源直方图。

    9.1 输出的人力资源计划中，虽然出现了资源日历，实际上是资源直方图，因 9.1 过程人员还未到位。

    9.2 输出中的资源日历是真正的资源日历。

28. 总时差决定了进度表的灵活余地，根据总时差可以确定关键路径（总时差都为 0 或负）

    使用关键路径时，判断进度好坏，仅依据 SPI、SV 不够，还需要另外判断关键路径总时差是否 >= 0。

    调整提前量与滞后量：

    1. 能让进度计划更加切实可行

    2. 设法使进度落后的活动赶上计划

29. 4 种变更类型：预防措施、纠正措施、缺陷补救、更新

    前三种是改变现实情况以符合计划

    第四种是改变原计划以和现实情况一致

    纠正措施和缺陷补救的区别：

    纠正措施偏重于针对进度、成本出现的偏差或问题采取措施，多针对进度、成本，而进度、成本的纠正，多是通过节省后续活动的时间、成本实现。

    缺陷补救强调对可交付成果质量缺陷或问题采取的措施，只针对质量缺陷。
