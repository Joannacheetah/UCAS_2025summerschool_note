## AI：无限维问题VS有限维技术——浅析大模型架构的设计基础与评估原理 徐宗本

![image-20250730140907764](markdown-img/Day3-3.assets/image-20250730140907764.png)

现有评估方法——测试；什么架构承载，架构设计，怎样做；评价AI技术需要回到无限维 方法论

![image-20250730140823814](markdown-img/Day3-3.assets/image-20250730140823814.png)

### 一、智能问题：本质上的无限维VS技术上的有限维

![image-20250730141019346](markdown-img/Day3-3.assets/image-20250730141019346.png)

人工智能：对于可观测的现实世界规律做总结。可观测+现实世界

观测到的规律为数据（时间+空间）；数据建模

多模态（多个观测角度数据）



#### 1.机器学习问题

![image-20250730141707494](markdown-img/Day3-3.assets/image-20250730141707494.png)

#### 2.数据生成和传输问题

![image-20250730141846574](markdown-img/Day3-3.assets/image-20250730141846574.png)

#### 3.方法论学习

![image-20250730142349505](markdown-img/Day3-3.assets/image-20250730142349505.png)

#### 4. 具身智能

![image-20250730142609947](markdown-img/Day3-3.assets/image-20250730142609947.png)

![image-20250730142916082](markdown-img/Day3-3.assets/image-20250730142916082.png)

架构和评测部分

### 二、如何设计有限维AI系统？架构设计的数学基础

![image-20250730143138645](markdown-img/Day3-3.assets/image-20250730143138645.png)

主要聚焦架构设计

![image-20250730143210811](markdown-img/Day3-3.assets/image-20250730143210811.png)

含有很多参数的函数

逼近论解决 定义？仅浅层架构设计问题

深层架构？

![image-20250730144339085](markdown-img/Day3-3.assets/image-20250730144339085.png)

(马尔可夫性质)

![image-20250730144611086](markdown-img/Day3-3.assets/image-20250730144611086.png)

初始架构 极限架构 可行架构

定义在函数空间上的算子

性能稳定

![image-20250730145341330](markdown-img/Day3-3.assets/image-20250730145341330.png)

不动点集上趋向于1

深度架构设计问题是一个算子族的公共不动点存在问题

怎么判断无穷架构是否存在？

![image-20250730150113106](markdown-img/Day3-3.assets/image-20250730150113106.png)

伸缩是有限度的（算子的基本性质）

拓扑无关量

线性谱半径

![image-20250730150415418](markdown-img/Day3-3.assets/image-20250730150415418.png)

![image-20250730150617169](markdown-img/Day3-3.assets/image-20250730150617169.png)

![image-20250730150703026](markdown-img/Day3-3.assets/image-20250730150703026.png)



![image-20250730151001579](markdown-img/Day3-3.assets/image-20250730151001579.png)

![image-20250730151402367](markdown-img/Day3-3.assets/image-20250730151402367.png)

![image-20250730151427265](markdown-img/Day3-3.assets/image-20250730151427265.png)

![image-20250730151804015](markdown-img/Day3-3.assets/image-20250730151804015.png)

![image-20250730152335025](markdown-img/Day3-3.assets/image-20250730152335025.png)

![image-20250730152500332](markdown-img/Day3-3.assets/image-20250730152500332.png)

总结：

1. 逼近论只解决浅层架构
2. 深度架构设计问题是一个算子族的公共不动点存在问题
3. 真正可用的架构：伸缩性不能大于1；在不动点处趋于饱和
4. 基于极小化序列修饰形成架构

### 三、评估AI系统必须回到无限维：极限理论

![image-20250730152821817](markdown-img/Day3-3.assets/image-20250730152821817.png)

![image-20250730152913676](markdown-img/Day3-3.assets/image-20250730152913676.png)

智能是由有限知识走向无限知识所引起的认知改变。

极限是开拓认知边界的工具。

![image-20250730153843224](markdown-img/Day3-3.assets/image-20250730153843224.png)

![image-20250730153931363](markdown-img/Day3-3.assets/image-20250730153931363.png)

![image-20250730154040695](markdown-img/Day3-3.assets/image-20250730154040695.png)

![image-20250730154119567](markdown-img/Day3-3.assets/image-20250730154119567.png)

![image-20250730154225699](markdown-img/Day3-3.assets/image-20250730154225699.png)

![image-20250730154518359](markdown-img/Day3-3.assets/image-20250730154518359.png)

### 结语

![image-20250730154728540](markdown-img/Day3-3.assets/image-20250730154728540.png)

![image-20250730154734004](markdown-img/Day3-3.assets/image-20250730154734004.png)

要崩溃了 好困好累

