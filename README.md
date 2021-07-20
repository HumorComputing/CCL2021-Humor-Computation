# CCL2021-Humor-Computation

### CCL2021第二阶段已经结束，第二次成绩和获奖情况已经公布。由于复核成绩花费了一定时间，第二次结果公布较晚，对给您造成的不便深感歉意。

### 7.8日晚公布二阶段第一周测试集排名及分数信息，7.15公布二阶段最终结果，结果取两周中最好成绩作为参赛队伍的最终成绩

CCL2021，“小牛杯”幽默计算任务数据发布

任务说明参见CCL2021官方网站：http://cips-cl.org/static/CCL2021/cclEval/humorcomputation/index.html

任务每个阶段的排名在该项目公布。

本次评测分为两个阶段。

* 第一阶段：持续8周（2021.5.7-2021.6.30）。

比赛训练集、验证集将于5月7日发布。

在该阶段，参赛队伍可在每周提交一次验证集结果。

组织方会根据参赛队伍在验证集上的得分进行排名，并每周在GitHub上公布该周各个队伍的排名及分数信息。

第一阶段成绩不作为最终成绩，仅为参赛队伍迭代模型提供参考。

* 第二阶段：持续2周（2021.7.1-2020.7.15）。

比赛完整测试集将于7月1日发布，参赛队伍需在最终截止日期前（含7月15日）提交完整测试集结果。

同第一阶段，每个队伍每周有一次提交机会，组织方每周在Github上公布该周各个队伍的排名及分数信息，取两周中最好成绩作为参赛队伍的最终成绩。

组织方将根据完整测试集上的得分对参赛队伍进行排名，同时该排名结果将会在**CCL2021**官方网站公布。

**每个队伍只有两次机会提交最终结果。**

提交方式：

比赛的两个阶段都使用邮箱进行结果提交。参赛队伍需要将包含结果文件的邮件发送至邮箱humorcomputing@163.com，

邮件的标题为“CCL2021-参赛队名”，邮件附件为结果文件。

邮件附件为结果文件。结果文件为无BOM的以utf-8为编码格式的csv文件，两个任务分两个结果文件。文件命名格式为：参赛队名_1.csv与参赛队名_2.csv

如：参赛队名为“CCL2021”，提交的文件名为“CCL2021_1.csv”和“CCL2021_1.csv”。csv文件分隔符使用逗号“,”，每行结尾的换行符为“\n”。

提交的结果文件其格式不正确不予计算成绩。样例格式如下：

| id    | label | 
| ----------- | -------- |
| id1    | label1    | 
| id2 | label2    | 
| ... | ...    | 
## 第一阶段第一次结果
 第一阶段本次接收到验证集结果提交4份。
 以下是第一次结果排名
| **参赛队名**    | **任务一的F1** | **任务2的F1**| **队伍总分** | 
| ----------- | -------- |-------- |-------- |
| 多模多多模    | 0.689    | 0.400    | 1.089    | 
| 新大小分队 | 0.605   | 0.359    | 0.965  | 
| 躺着屠龙 | 0.608   | 0.329    | 0.937    | 
| hit20S    | 0.667   | 0.190   | 0.857    | 

## 第一阶段第二次结果
 第一阶段本次接收到验证集结果提交7份。
 以下是第二次结果排名
| **参赛队名**    | **任务一的F1** | **任务2的F1**| **队伍总分** | 
| ----------- | -------- |-------- |-------- |
| 多模多多模    | 0.689    | 0.400    | 1.089    | 
| hit20S    | 0.605  | 0.400   | 1.006    | 
| 新大小分队 | 0.605   | 0.359    | 0.965  | 
| new | 0.566   | 0.383    | 0.949    | 
| 躺着屠龙 | 0.666   | 0.257   | 0.924    | 
| TaiNan | 0.558   | 0.331   | 0.888    | 
| IMUT1506 | 0.592  | 0.281    | 0.873    | 
| 清博AI | 0.308   | 0.263    | 0.570    | 
## 第一阶段第三次结果
 第一阶段本次接收到验证集结果提交10份。
 以下是第三次结果排名
| **参赛队名**    | **任务一的F1** | **任务2的F1**| **队伍总分** | 
| ----------- | -------- |-------- |-------- |
| 多模多多模    | 0.677    | 0.445    | 1.122    | 
| hit20S    | 0.619  | 0.370   | 0.989    | 
| 新大小分队 | 0.605   | 0.359    | 0.965  | 
| new | 0.568   | 0.358    | 0.926    | 
| 躺着屠龙 | 0.666   | 0.257   | 0.924    | 
| YXW | 0.536   | 0.362    | 0.898    | 
| TaiNan | 0.558   | 0.331   | 0.888    | 
| IMUT1506 | 0.581  | 0.263    | 0.844    | 
| 稽查大队 | 0.481  | 0.305    | 0.786    | 
| 清博AI | 0.308   | 0.263    | 0.570    | 
## 第一阶段第四次结果
 第一阶段本次接收到验证集结果提交11份。
 以下是第四次结果排名
| **参赛队名**    | **任务一的F1** | **任务2的F1**| **队伍总分** | 
| ----------- | -------- |-------- |-------- |
| TAL_AL_NLP    | 0.720    | 0.499    | 1.219    | 
| 多模多多模    | 0.677    | 0.445    | 1.122    | 
| hit20S    | 0.598  | 0.409  | 1.007    | 
| 新大小分队 | 0.605   | 0.359    | 0.965  | 
| IMUT1506 | 0.549  | 0.410    | 0.959    | 
| new | 0.552   | 0.396    | 0.947    | 
| YXW | 0.568   | 0.362    | 0.930   | 
| 躺着屠龙 | 0.666   | 0.257   | 0.924    | 
| TaiNan | 0.558   | 0.331   | 0.888    | 
| 稽查大队 | 0.481  | 0.305    | 0.786    | 
| 清博AI | 0.308   | 0.263    | 0.570    | 
## 第一阶段第五次结果
 第一阶段本次接收到验证集结果提交13份。
 以下是第五次结果排名
| **参赛队名**    | **任务一的F1** | **任务2的F1**| **队伍总分** | 
| ----------- | -------- |-------- |-------- |
| TAL_AL_NLP    | 0.727    | 0.513    | 1.239    | 
| 多模多多模    | 0.677    | 0.445    | 1.122    | 
| hit20S    | 0.598  | 0.409  | 1.007    | 
| Pale Blue Dot| 0.594   | 0.377    | 0.971    |    
| 新大小分队 | 0.605   | 0.359    | 0.965  | 
| FPM | 0.573   | 0.375    | 0.948   | 
| YXW | 0.568   | 0.362    | 0.930   | 
| TaiNan | 0.558   | 0.331   | 0.888    | 
| new | 0.555   | 0.310    | 0.865    | 
| 躺着屠龙 | 0.667   | 0.152   | 0.818   | 
| 稽查大队 | 0.481  | 0.305    | 0.786    | 
| IMUT1506 | 0.549  | 0.111    | 0.660    | 
| 清博AI | 0.308   | 0.263    | 0.570    | 
## 第一阶段第六次结果
 第一阶段本次接收到验证集结果提交13份。
 以下是第六次结果排名
| **参赛队名**    | **任务一的F1** | **任务2的F1**| **队伍总分** | 
| ----------- | -------- |-------- |-------- |
| TaiNan| 0.840   | 0.570    | 1.410   | 
| Pale Blue Dot| 0.765   | 0.546    | 1.310    |   
| TAL_AL_NLP    | 0.762    | 0.480    | 1.242   | 
| 多模多多模    | 0.677    | 0.445    | 1.122    | 
| FPM | 0.637   | 0.377   | 1.014   | 
| hit20S    | 0.598  | 0.409  | 1.007    | 
| 躺着屠龙 | 0.614  | 0.360  |0.974  | 
| 新大小分队 | 0.605   | 0.359    | 0.965  | 
| new | 0.531   | 0.379   | 0.909   | 
| YXW | 0.529  | 0.333   | 0.861   | 
| 稽查大队 | 0.499 | 0.310  | 0.809   | 
| IMUT1506 | 0.588  | 0.139    | 0.727    | 
| 清博AI | 0.308   | 0.263    | 0.570    | 
## 第一阶段第七次结果
 第一阶段本次接收到验证集结果提交14份。
 以下是第七次结果排名
| **参赛队名**    | **任务一的F1** | **任务2的F1**| **队伍总分** | 
| ----------- | -------- |-------- |-------- |
| TaiNan| 0.831   | 0.571    | 1.402  | 
| TAL_AL_NLP    | 0.825   | 0.576    | 1.401  | 
| Pale Blue Dot| 0.718  | 0.546   | 1.264    |   
| 多模多多模    | 0.677    | 0.445    | 1.122    | 
| FPM | 0.637   | 0.377   | 1.014   | 
| hit20S    | 0.596  | 0.394  | 0.990    | 
| 躺着屠龙 | 0.614  | 0.360  |0.974  | 
| 新大小分队 | 0.605   | 0.359    | 0.965  | 
| IMUT1506 | 0.573  | 0.347    | 0.921   | 
| new | 0.531   | 0.379   | 0.909   | 
| YXW | 0.529  | 0.333   | 0.861   | 
| 稽查大队 | 0.499 | 0.310  | 0.809   | 
| 清博AI | 0.308   | 0.263    | 0.570    | 
| 小蟹爱喝粥 | 0.422   | 0.143    | 0.566   | 
## 第二阶段第一次结果
 第二阶段本次接收到测试集结果提交11份。以下是本次的结果排名
| **参赛队名**    | **任务一的F1** | **任务2的F1**| **队伍总分** | 
| ----------- | -------- |-------- |-------- |
| TaiNan| 0.854   | 0.604    | 1.458  | 
| TAL_AL_NLP    | 0.750   | 0.519    | 1.269  | 
| Pale Blue Dot| 0.727  | 0.449   | 1.176   |   
| 多模多多模    | 0.696    | 0.453    | 1.149    | 
| hit20S    | 0.644  | 0.424  | 1.068    | 
| 小蟹爱喝粥 | 0.585  | 0.337   | 0.922   | 
| new | 0.488  | 0.404   | 0.893  | 
| IMUT1506 | 0.439  | 0.424    | 0.863  | 
| 一路同行| 0.549   | 0.302   | 0.852| 
| 我们都队| 0.522  | 0.326  | 0.849 | 
| nlper| 0.453   | 0.302   | 0.756 | 
## 第二阶段第二次排名
| **参赛队名**    | **任务一的F1** | **任务2的F1**| **队伍总分** | 
| ----------- | -------- |-------- |-------- |-------- |
| TaiNan| 0.854   | 0.841 |   0.563   | 1.403  | 
| TAL_AL_NLP    | 0.789   | 0.519    | 1.308  |
| 多模多多模    | 0.736    | 0.462    | 1.198    | 
| Pale Blue Dot| 0.717  | 0.413   | 1.130   |  
| hit20S    | 0.667  | 0.424  | 1.090    | 
| new | 0.581  | 0.414   | 0.995  | 
| DLUFLER| 0.575   | 0.419   | 0.993 | 
| 小甜饼 | 0.553   | 0.420  | 0.973 | 
| IMUT1506 | 0.534 | 0.424    | 0.959  | 
| 小蟹爱喝粥 | 0.565  | 0.355   | 0.920   | 
| 一路同行| 0.549   | 0.326   | 0.876| 
| 我们都队| 0.522  | 0.326  | 0.849 | 
| nlper| 0.549  | 0.323   | 0.873 | 
## 比赛获奖情况
| **参赛队名**    |  **参赛单位** | **奖项** |
| ----------- | -------- |-------- |-------- |-------- |
| TaiNan| 0.854   | 北京理工大学 | 一等奖 |
| TAL_AL_NLP    |  好未来AI中台 | 二等奖 |
| 多模多多模    | 大连理工大学 | 二等奖 |
| Pale Blue Dot|   云南大学信息学院 | 三等奖 |
| hit20S    |  哈尔滨工业大学机器智能与翻译研究室 | 三等奖 |
| new |  南方科技大学 | 三等奖 |