# AI_Futurelab
赛题链接: [城市-房产租金预测](https://ai.futurelab.tv/contest_detail/3)

赛题主要是通过房产市场、租赁市场、市场需求以及房屋配置，做出合理的房租预测。
数据集中数据类别包括租赁房源、小区情况、所在版块二手房、新房以及土地等营销情况，结合人口、客户、真实租金等。

评分公式为:

<a href="https://www.codecogs.com/eqnedit.php?latex=\dpi{100}&space;\huge&space;$$&space;score=1-\frac{\sum_{i=1}^m&space;(\hat{y}_i&space;-&space;y_i)&space;^&space;2}{\sum_{i=1}^m&space;(y_i&space;-&space;\bar{y})^2}&space;$$" target="_blank"><img src="https://latex.codecogs.com/png.latex?\dpi{100}&space;\huge&space;$$&space;score=1-\frac{\sum_{i=1}^m&space;(\hat{y}_i&space;-&space;y_i)&space;^&space;2}{\sum_{i=1}^m&space;(y_i&space;-&space;\bar{y})^2}&space;$$" title="\huge $$ score=1-\frac{\sum_{i=1}^m (\hat{y}_i - y_i) ^ 2}{\sum_{i=1}^m (y_i - \bar{y})^2} $$" /></a>
