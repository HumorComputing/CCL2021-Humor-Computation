# CCL2021-Humor-Computation

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

