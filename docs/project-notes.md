# Personal project notes

Text extracted from my working notes. Embedded course screenshots and images are not included in this text version.

Understand the business and frame the problem

思路：

Data points

把业务问题翻译成数据问题

价格敏感导致用户流失→价格变动是否显著影响用户是否流失→‘是否流失’无法量化：价格变动是否显著影响用户流失概率

确定分析单元和结果变量

自变量：给客户的价格和其他可能发生变化的数据

核心自变量：价格，可能随不同时间/不同客户变化

因变量：客户是否流失

→建模：

→再给定一组新的自变量，得到的是一个新用户流失的概率→’model churn probabilities’

考虑每个特征的数据形式

自己答案中的问题：

Pricing strategy：可以精确到用户层面，且说明时间是at granular time interval

Potential competitors situation：可以暂时不考虑，如用户是否从本公司转向去买其他公司产品的情况。只考虑在本公司这个范围内，用户有没有流失

Exploratory Data Analysis and Data Cleaning

思路：

了解目标变量整体分布

关注其他变量与目标变量的关系，系统性覆盖所有变量

类别特征：堆叠百分比条形图

数值特征：直方图观察分布；箱线图检查异常值和偏态

关注特殊值、缺失值、日期列格式转换等

自己答案中的问题：

自变量和因变量颠倒。如果将churn 0/1作为自变量，堆叠百分比观察的是churn组内部的分布；将不同类别/不同数值范围的其他变量作为自变量，观察的是其他变量各个取值中churn的比例。后者更符合目的。

凭感觉挑选变量描述关系。要始终针对研究问题，关注想研究的是什么自变量和什么因变量的关系

尽可能覆盖与研究目的相符合的所有描述性分析
