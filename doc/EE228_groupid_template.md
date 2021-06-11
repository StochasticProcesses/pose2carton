# Pose2Carton 

EE228 课程大作业，利用3D骨架控制3D卡通人物。



# Maya 环境配置

Tutorial: [maya配置教程-知乎](https://zhuanlan.zhihu.com/p/367649237)<br>

* 申请Autodesk账户和教育版权限，下载maya2020，按引导安装，运行maya2020.
* 添加环境变量：将maya2020\bin的路径添加到环境变量-系统变量-Path中。打开cmd，输入mayapy检查是否添加成功。
* 打开cmd，输入安装pip
>curl https://bootstrap.pypa.io/pip/2.7/get-pip.py -o get-pip.py<br>
>mayapy get-pip.py
* 安装numpy：
>mayapy -m pip install -i https://pypi.anaconda.org/carlkl/simple numpy
* 检查环境：
>import maya<br>
>import maya.standalone<br>
>maya.standalone.initialize(name='python')<br>
>import maya.OpenMaya as om<br>
>import maya.cmds as cmds<br>
>import pymel.core as pm<br>
>import maya.mel as mel<br>
>import numpy as np<br>
>import os<br>
>import glob
* 在脚本目录下运行示例代码
>mayapy fbx_parser.py xxxx.fbx
如果顺利结束运行，并生成所需文件，则配置完成。

# 匹配流程

这里请简单描述你熟悉/使用 匹配代码的流程，可以简述对代码的理解/各个函数作用等。



# 新增脚本说明

如果你写了自己的脚本来处理数据或进行可视化，请在这里进行相关说明(如何使用等)； 如果没有，请忽略该模块。



# 项目结果

这里放置来自你最终匹配结果的截图， 如

![image](../img/pose2carton.png)





# 协议 
本项目在 Apache-2.0 协议下开源

所涉及代码及数据的最终解释权归倪冰冰老师课题组所有

Group xx
