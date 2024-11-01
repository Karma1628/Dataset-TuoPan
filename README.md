# Chip Tray Dataset

本数据集公开了用于芯片托盘异常检测的高质量数据，适用于计算机视觉、深度学习等相关领域的研究和应用。

## 数据集结构

数据集包含以下三个文件夹：

1. **Normal**：包含1680张正常芯片托盘样本，用于模型的正常样本训练或评估。
2. **Abnormal**：包含100张具有异常的芯片托盘样本，可用于异常检测的训练和测试。
3. **Mask**：包含与Abnormal文件夹中异常样本对应的标注文件，每个异常样本配有一个JSON标注文件，提供异常位置的详细信息。

## 文件格式

- 图像文件为标准图像格式（`png`）。
- 标注文件采用JSON格式，包含异常区域的坐标信息，方便模型训练和验证中的异常定位。

## 数据集用途

该数据集可用于：
- 异常检测
- 图像分割
- 机器学习与深度学习模型的训练与评估

## 使用方法

将数据集按上述结构加载到您的项目中，使用Normal文件夹中的图像作为无异常样本，Abnormal和Mask文件夹中的数据用于异常样本检测和标注学习。

## 下载链接

数据集可以通过以下链接下载：

- 链接：[https://pan.baidu.com/s/1S3_GPZwUxdU2hjM5yGQyag?pwd=1234](https://pan.baidu.com/s/1S3_GPZwUxdU2hjM5yGQyag?pwd=1234)
- 提取码：`1234`
