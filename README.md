# 数据集:SAR-Ship-Dataset
* Github：https://github.com/CAESAR-Radi/SAR-Ship-Dataset
* 介绍：https://www.cas.cn/syky/201904/t20190428_4690206.shtml?from=timeline

# 数据预处理：
* 已处理成Psacol_VOC 2012 数据集格式

# 模型
* 详见```SAR_Faster-RCNN\README.md```
* 基于Faster-RCNN目标检测模型，以Res Net50为backbone，引入Mix-Pooling优化原有ROI Align，随机选择最大池化或平均池化，增加网络正则性。
* Mix-Pooling部分的修改代码在实验室服务器上因相关原因还在优化

# 结果
* 详见根目录
