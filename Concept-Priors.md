## 概念


#### Memory

##### Context

Context表示在一个局部定义的环境，例如在一个环境中的张三就代指一个局部为张三的人，那么如果有重名的情况，一般会通过别名区分，如大张三或者小张三区分代指。

Context中的别名代指为概念别名。

##### 概念别名

概念别名是一种概念实现方式。

## 概念先验 Concept Priors

Priors of Concept Model，在概念模型推断过程中，用于推理的先验内容。  

基于Concept Priors可以形成决策行动的系列指令，或者一系列的指令序列，形成指令链路（Series of Instructions）。

 - 内生指令序列，用于处理Concept Model建立的指令序列  
 - 动作指令序列，用于和Env交互的指令序列  

