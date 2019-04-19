# mission-workflow-system 工单任务，工作流系统
> 为公司写了个工单系统
> 缘起：前人写的是一个很简单的表格式，就是 **某某A**[需求方] 提了个任务给 **某某B** [部门领导] 审核 呈交给 **某某C** [程序猿]执行 ，一站式的表格。
> 这个子的简单，它其实算是一个记事本一样的功能，从发起人到审核人再到执行人，给一个状态，很清爽，不过随着需求的复杂，慢慢的满足不了我们的需求，它只能记录一个很简单，很末端的一个任务，当一个任务或者项目变得很大，涉及到各个功能部门的各个环节的时候，而且流程长度不固定，需要分叉，它就无法满足。

# 用心梳理了下新的需求，需要满足以下几点
- 流程长度不固定，不再是A想了个事情，要B去执行，这种一站式只适用于初创小作坊式的组织架构。
- 流程复杂度升级，不再是单线程一流水的处理问题，因为一个项目设计到各个部门，任务下来，往往是各个部门并行协作的完成同一个事情。
- 不止是适用于it程序部门，可以大而化之的应用到公司所有部门
- 计算个人绩效，部门绩效，在一定的规则下，可以评估个人，部门的工作绩效。
- 追踪各个任务的进行情况，判断是哪个环节在拖延进度。

# 设计的原则
> 很简单，就是遵循找人做事的原则
- 找什么人
- 做什么事情
- 指定任务需要完成的时间
