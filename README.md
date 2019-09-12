# Housing-Prices-in-Nashville 
# Nashville 市房价分析

在线预览该 repository 中的 Housing Prices in Nashiville.html 文件，请点击该链接：https://jax0048.github.io/Housing-Prices-in-Nashville/Housing%20Prices%20in%20Nashville.html
本项目为我本人与他人协作共同完成。旨在构建美国 Nashville 市房价的预测模型。项目的研究报告共分为5个部分：介绍（Introduction）、探索分析（Exploratory Analysis）、方法（Methods）、结果（Results）、讨论（Discussion）和结论（Conclusion）。

## 数据及变量
房价信息共9000条数据，来自美国租房网站 Zillow。用于构建模型的自变量总共分为三类：房屋内在属性（Internal Characteristics）、Regional Amenity Access or Public Service（区域公共设施及服务）、空间结构（Spatial Structure）。
- 房屋内在属性（Internal Characteristics）
  - LandUseFullDescription（用地属性）
  - yearbuilt_building（房屋建造年份）
  - effyearbuilt_building（房屋装修年份）
  - Acrage（房屋占地面积）
  - roomsunits_building（房间数量）
  - sf_bsmt_fin（地下室面积）
  - ac_sfyi（是否有中央空调）
  - baths（浴室数量）
  - Fixtures（家具数量）
 - Regional Amenity Access or Public Service（区域公共设施及服务）
  - d_library（最近的图书馆距离）
  - d_Water（最近的供水厂距离）
  - d_Parks（最近的公园距离）
  - d_Police（最近的警察局距离）
  - d_Social（最近的社区服务中心距离）
  - d_RTA（最近的区域交通站距离）
  - d_FireSta（最近的消防站距离）
  - d_Hospital（最近的一员距离）
  - d_Recycle（最近的垃圾回收厂距离）
  - d_MTA（最近的市域交通站距离）
 - 空间结构（Spatial Structure）
  - LocationZip（房屋所属区域邮编）
  - NeighborhoodAssessor（Zillow 公司根据房屋周边环境属性的分组代码）
  - CouncilDistrict（纳税分区）
### 

模型的准确性评判基于最基本的机器学习方法：Training & Test。
