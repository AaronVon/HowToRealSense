# 开发环境的搭建
---

![](/res/cover.png)

## 技术简介及要求
--------

![](/res/TechnicalSpecifications.png)

## 材料准备
--------

- RealSense 设备 (这里以 F200 为示例)
- RealSense SDK [下载地址](https://software.intel.com/en-us/intel-realsense-sdk)
- 下载对应设备的 SDK 以及一个通用的 SDK 离线包

## 具体步骤
--------
#### 1. 插入 RealSense 设备
这步为必须，系统需要检测到 RealSense 设备才能安装环境。
#### 2. 安装通用离线 SDK 包
执行 intel_rs_sdk_offline_package_r6_8.0.24.6528.exe

![](/res/intel_rs_sdk_offline_package.PNG)

定制需要的 SDK 组件

![](/res/choose_components.PNG)

#### 3. 安装 F200 单独SDK
![](/res/intel_rs_dcm_f200.PNG)

所有安装完毕之后，在系统环境变量里添加

![](/res/environment_variables.PNG)

ps. 若没有则手动添加

#### 4. 安装完毕
至此所有环境配置完成，可以在 Intel RealSense SDK Information 检查各模块是否正常。

![](/res/SDK_info.PNG)