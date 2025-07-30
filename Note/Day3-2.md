## 合成数据驱动的具身VLA 预训练新范式 王鹤

![image-20250730101557674](markdown-img/Day3-2.assets/image-20250730101557674.png)

### 0. 预热 人形机器人浪潮

#### （一）雏形时代

最早人形机器人 1967年 日本 

![image-20250730101854083](markdown-img/Day3-2.assets/image-20250730101854083.png)

1. 特斯拉人形机器人
2. 多模态大模型 

![image-20250730102304953](markdown-img/Day3-2.assets/image-20250730102304953.png)

仅是基于数学模型，不是数据驱动

![image-20250730102609937](markdown-img/Day3-2.assets/image-20250730102609937.png)

波士顿动力 

（仅是提前规划好的，路径已知）

传统控制方法

#### （二）运动时代

![image-20250730103010800](markdown-img/Day3-2.assets/image-20250730103010800.png)

![image-20250730103133727](markdown-img/Day3-2.assets/image-20250730103133727.png)

基于强化学习

![image-20250730103152435](markdown-img/Day3-2.assets/image-20250730103152435.png)

![image-20250730103430187](markdown-img/Day3-2.assets/image-20250730103430187.png)

本体感知

#### （三）生产力时代

![image-20250730104416368](markdown-img/Day3-2.assets/image-20250730104416368.png)

（手眼脑的协调）

![image-20250730104501090](markdown-img/Day3-2.assets/image-20250730104501090.png)

（1. 放到不同地方 一定程度上是多任务 2. 错误恢复 ）

![image-20250730104619264](markdown-img/Day3-2.assets/image-20250730104619264.png)

放歪后可以调整 以视觉为信号输出全身的关节角→具身智能的体现

但也有局限性 ，只能完整分电池

### 具身端到端VLA大模型实现通用

![image-20250730105119717](markdown-img/Day3-2.assets/image-20250730105119717.png)

LLM 听懂让拿瓶子

VLM 识别是瓶子 

能把指令转化成关节角 能够依赖具体身体结构 进行与环境的交互

![image-20250730105614650](markdown-img/Day3-2.assets/image-20250730105614650.png)

![image-20250730105839092](markdown-img/Day3-2.assets/image-20250730105839092.png)

自动驾驶 具身智能最大区别

人无法像开车一样开机器人（从而采数据）

人形机器人的数据采集 遥控操作员  数据量不够 目前具身智能最大的痛点 没有数据集 每个机器人身体都不同 差异化太大

现在都是先用人纯模拟操作计算机的指定动作然后进行训练

![image-20250730110145815](markdown-img/Day3-2.assets/image-20250730110145815.png)

解决→用语言描述

![image-20250730110751565](markdown-img/Day3-2.assets/image-20250730110751565.png)

用计算机图形学 物理渲染解决，虚拟世界仿真

桌面数据集 

![image-20250730110900933](markdown-img/Day3-2.assets/image-20250730110900933.png)

![image-20250730111047890](markdown-img/Day3-2.assets/image-20250730111047890.png)

![image-20250730111054650](markdown-img/Day3-2.assets/image-20250730111054650.png)

3D重建 ![image-20250730111109851](markdown-img/Day3-2.assets/image-20250730111109851.png)

![image-20250730111216790](markdown-img/Day3-2.assets/image-20250730111216790.png)

![image-20250730111326600](markdown-img/Day3-2.assets/image-20250730111326600.png)

抓取大数据 连续视觉输入

![image-20250730111419471](markdown-img/Day3-2.assets/image-20250730111419471.png)

![image-20250730111518878](markdown-img/Day3-2.assets/image-20250730111518878.png)

![image-20250730111534608](markdown-img/Day3-2.assets/image-20250730111534608.png)

![image-20250730111634020](markdown-img/Day3-2.assets/image-20250730111634020.png)

因为有充分量的数据

![image-20250730111907646](markdown-img/Day3-2.assets/image-20250730111907646.png)

![image-20250730112146111](markdown-img/Day3-2.assets/image-20250730112146111.png)

![image-20250730112154315](markdown-img/Day3-2.assets/image-20250730112154315.png)

（互联网混合训练）

![image-20250730112228831](markdown-img/Day3-2.assets/image-20250730112228831.png)

![image-20250730112401589](markdown-img/Day3-2.assets/image-20250730112401589.png)

200个 一人半天（VS 特斯拉 10万次）成本↓

![image-20250730112848735](markdown-img/Day3-2.assets/image-20250730112848735.png)

（没有过拟合 很好泛化到农夫山泉和东方树叶 （4列到3列 不同颜色形状数量））

![image-20250730113059670](markdown-img/Day3-2.assets/image-20250730113059670.png)

![image-20250730113104326](markdown-img/Day3-2.assets/image-20250730113104326.png)

（行为数据中（A）只能看出流程 不知道具体怎么做）

动作数据 纯粹模仿

![image-20250730113632956](markdown-img/Day3-2.assets/image-20250730113632956.png)

![image-20250730113652388](markdown-img/Day3-2.assets/image-20250730113652388.png)

![image-20250730114020253](markdown-img/Day3-2.assets/image-20250730114020253.png)

用合成数据叠衣服

![image-20250730114129921](markdown-img/Day3-2.assets/image-20250730114129921.png)

![image-20250730114134956](markdown-img/Day3-2.assets/image-20250730114134956.png)

![image-20250730114209873](markdown-img/Day3-2.assets/image-20250730114209873.png)

局部商业化

![image-20250730114228948](markdown-img/Day3-2.assets/image-20250730114228948.png)

![image-20250730114411720](markdown-img/Day3-2.assets/image-20250730114411720.png)

每个能力都需要大量数据学习 仿真数据可以解决，互联网更加通用
