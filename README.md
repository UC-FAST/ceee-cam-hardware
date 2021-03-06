# ceee-cam-hardware

# 硬件
## 我需要准备什么
* 学硬件是要烧钱的，为了完成这个项目，1000元是可能需要花费的。
* 需要购买的成品组件：
    - 树莓派HQ摄像头模组
    - 一个C或者CS接口的镜头，1/23"以上面积
    - 树莓派Zero 2w
* 必须的工具：电烙铁、热风枪、焊锡、锡浆、镊子等
* 基本的电路板绘制技能
* 一些其他零件：在文件BOM.xlsx内
* 若干电阻以及电容等，参照原理图
_____
## 需要自制的电路板组件
本项目内含四块需要自制的电路板，分别为：
* Z01-2：电源板，负责整个系统的充放电，附带电量指示功能，并提供基本的输入按钮
![电源板](https://github.com/UC-FAST/CEEE-HQ-CAMERA/blob/main/pict/Z01.png "Z01")
* Z02：摄像头转接板及支架，这一部分是作为结构板、不含电路的
![转接板](https://github.com/UC-FAST/CEEE-HQ-CAMERA/blob/main/pict/Z02-1.png "摄像头转接板")
![支架](https://github.com/UC-FAST/CEEE-HQ-CAMERA/blob/main/pict/Z02-2.png "摄像头支架")
* Z03：Lcd显示屏板，附带一个5D开关
![Lcd显示屏板](https://github.com/UC-FAST/CEEE-HQ-CAMERA/blob/main/pict/Z03.png "Lcd显示屏板")


____

## 组装
需要用到若干5mm尼龙柱、10mm尼龙柱、12mm尼龙柱、15mm尼龙柱、M2.5尼龙螺丝以及M2.5尼龙螺母。本项目中所有安装孔都是2.5mm的直径。

### 组装顺序：
|层数|名称|高度（尼龙柱长度，单位mm）|
|-|-|-|
|1|树莓派HQ摄像头模组|
||尼龙柱|5|
|2|摄像头转接板 Z02||
||尼龙柱|5|
|3|摄像头支架 Z02|
||尼龙柱|10|
|4|树莓派Zero 2w，焊接17mm双排针|
||尼龙柱|12或15|
|5|电源板 Z01-2|
||尼龙柱|12|
|6|Lcd显示屏板|
