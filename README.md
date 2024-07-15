

## 项目简介
项目描述：以原始YOLO v4为基础提出一种改进轻量级杂草检测模型，将YOLOv4的主干特征提取网络更换为MobileNetV3-Small，结合深度可分离卷积和逆残差结构，引入轻量级的注意力机制，提高了模型的检测效率，使用TensorRT与C++完成模型部署。
- 基于**Tensorrt**加速**改进Yolov4**
- 支持**Windows10**
- 支持**Python/C++**

## 环境说明
- Tensorrt 8.2.1.8
- Cuda 10.2 Cudnn 8.2.1(**特别注意需安装两个cuda10.2补丁**)
- Opencv 3.4.6
- Cmake 3.17.1
- VS 2017
- GTX1650


