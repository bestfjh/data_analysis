### 一、描述性统计

#### 1. 基本描述结果

summarize  变量名 

![image-20211006005315908](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006005315908.png)



#### 2. 详细的描述结果

summarize  变量名，detail

![image-20211006010920349](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006010920349.png)



#### 3. 获得指定的统计指标

tabstat 变量名，stats(mean sd min max)

![image-20211006011041390](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006011041390.png)

#### 4. 按另一变量分类列出某变量需要的统计指标

![image-20211006011208037](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006011208037.png)

#### 5. 频率统计

![image-20211006013116389](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006013116389.png)



#### 6. 列联表

![image-20211006013137653](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006013137653.png)

添加百分比

![image-20211006013249094](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006013249094.png)



### 二、参数检验

什么是参数检验？

​	对参数的平均值、方差、比率等特征进行的统计检验。

​	参数检验一般假设统计总体的具体分布是已知的，但是其中的一些参数或者取值范围不确定。

#### 1. 单一样本T检验



![image-20211006014300345](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006014300345.png)

#### 2. 独立样本t检验

![image-20211006014512446](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006014512446.png)

#### 3. 配对样本t检验

![image-20211006014621528](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006014621528.png)

#### 4. 单一样本的假设检验

![image-20211006014826573](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006014826573.png)

#### 5. 双样本方差的假设检验

![image-20211006014928491](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006014928491.png)

（6）



### 三、非参数检验

#### 1. 非参数检验与参数检验的区别

（1）参数检验是针对参数做的假设；非参数检验是针对总体分布情况做的假设，这是区分的一个重要特征；

（2）根本区别在于，参数检验要利用到总体的信息（总体的分布、总体的一些参数特征，如方差），以总体分布和样本信息对总体参数做出推断；非参数检验不需要利用总体信息，以样本信息对总体分布做出推断；

（3）正态分布用参数检验，非正态分布用非参数检验。

#### 2. 单样本正态分布检验 

![1111111](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006015933593.png)

![image-20211006020024619](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006020024619.png)

#### 3. 两独立样本检验

![image-20211006020200790](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006020200790.png)



#### 4. 两相关样本检验

![image-20211006020321379](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006020321379.png)

#### 5. 多独立样本检验

![image-20211006020441024](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006020441024.png)

#### 6. 游程检验

![image-20211006020636337](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006020636337.png)



### 四、方差分析

#### 1. 单因素方差分析

![image-20211006020925412](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006020925412.png)

#### 2. 多因素方差分析

![image-20211006021220919](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006021220919.png)

#### 3. 协方差分析

![image-20211006021708004](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006021708004.png)

因变量：Q5

自变量：Q6、Q7

协变量：Q8



#### 4. 重复测量方差



### 五、相关分析

#### 1. 简单相关分析

![image-20211006022217764](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006022217764.png)

![image-20211006022849935](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006022849935.png)



带显著性值

![image-20211006022408625](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006022408625.png)

![image-20211006022536381](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006022536381.png)

#### 2. 偏相关分析

![image-20211006022653303](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006022653303.png)

### 六、主成分分析

![image-20211006023402145](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006023402145.png)

![image-20211006023413431](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006023413431.png)

![image-20211006023423424](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006023423424.png)



只保留特征值大于1的主成分

![image-20211006023553428](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006023553428.png)

![image-20211006023602711](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006023602711.png)



限定提取主成分的个数

![image-20211006023701504](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006023701504.png)

![image-20211006023711009](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006023711009.png)

### 七、因子分析



### 八、聚类分析

#### 1. 划分聚类分析



#### 2. 层次聚类分析



### 九、线性回归分析

#### 1. 简单线性回归

![image-20211006024500436](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006024500436.png)



#### 2. 多重线性回归分析

![image-20211006024854541](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20211006024854541.png)



![]()



### 十、回归诊断与应对

#### 1. 异方差检验与应对



#### 2. 自相关检验与应对



#### 3. 多重共线性检验与应对



### 十一、非线性回归

#### 1. 非参数回归分析





### 十二、逻辑回归

#### 1. 二元逻辑



#### 2. 多元逻辑



#### 3. 有序多元逻辑



### 十三、因变量受限回归分析





### 十四、面板数据分析

#### 1.  基本概述

##### （1）什么是面板数据？

​    面板数据又称为平行数据，指的是对某变量在一定时间段内持续跟踪观测的结果。

​	面板数据兼具了横截面数据和时间序列数据的特点。

​	横截面维度——在同一时间段内有多个观测样本

​	时间序列维度——同一样本在多个时间段内被观测到

​	根据横截面维度和时间序列维度相对长度的大小，面板数据分为：长面板数据，短面板数据。

##### （2）短面板数据

横截面维度比较大而时间维度相对较小，同一期间内被观测的个体数量较多而被观测的期间较少。

##### （3）短面板数据的主要分析方法

直接最小二乘回归

固定效应回归分析

随机效应回归分析

组间估计量回归分析

##### （4）长面板数据的主要分析方法

#### 2. 短面板数据



#### 3. 长面板数据



















