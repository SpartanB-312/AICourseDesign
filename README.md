## 数据来源及说明
数据来自韩国光阳的大宇钢铁有限公司，为制造过程中的电力消耗。数据包括：日期、能耗、滞后功率、导前功率、CO2、滞后系数、导前系数、NSM、工作日和负载状态。  
UCI Machine Learning Repository: Steel Industry Energy Consumption Dataset Data Set  
https://archive.ics.uci.edu/ml/datasets/Steel+Industry+Energy+Consumption+Dataset

## 结论
1.	二氧化碳排放量与能耗线性相关  
2.	随着负载的提高，能耗与电网参数之间的关系趋于非线性  
3.	使用RNN和DNN对时间序列进行预测，在高能耗情况下拟合偏差较大，但总体上优于线性模型  

