# 简单的示例
---
这里给出了一些使用 RealSense SDK Browser 测试所执行的一些示例。

![](/res/realsense_sdk_browser.png)
 
## 3D Scan
----
从 RealSense SDK Browser 打开 3D Scan 模块，如图所示

![](/res/3d_scan.PNG)

- 可选择扫描的物体类型 (其识别模式会有相应更改)
- 可选择执行扫描的设备 (这里就是 F200)
- 以及设备的分辨率、帧率 (会一定程度上影响对扫描物体的识别率)

##### 3D 建模的一个杯子

![](/res/3d_cup.png)

##### 3D 建模数据的处理
扫描完成之后系统会生成一个 `.obj` 和一个 `.html` 文件。

- `.obj` 即为3D 建模数据，可以使用 [OpenCV](http://opencv.org) 对其进行分析处理
- `.html` 可以直接在浏览器中预览生成的 3D 模型

## 附录
---
系统自带模块的源码可以在 `C:\Program Files (x86)\Intel\RSSDK\sample\` 中找到。

![](/res/source_code.PNG)