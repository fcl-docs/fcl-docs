<div align="center">

# Vulkan版本查看

</div>

## 前言

 - 这里将介绍一些查看Vulkan版本的方法
 - 如果有更好的方式可以投搞至1902002294@qq.com(不一定在线)
 - 骁龙查看方式推荐Termux,可以查看是否支持Turnip(Termux的Turnip比较旧,兼容更多的旧设备,可能FCL的新Turnip不能正常使用)
::: warning 警告
软件黑名单(已知虚标/不正确显示Vulkan版本)
- 设备信息by流舟
:::
:::warning 警告
设备黑名单(一定用不了VulkanMod,即使检测出来是Vulkan**1.2/1.3/1.4**)
- 使用天玑的**VIVO**/**IQOO**
- 过于老旧的手机
:::
 
 
## 简单版

1. 使用Device info (HW)
打开“芯片”页,找到“Vulkan”一行,后面的数字即为支持的Vulkan大版本
2. 使用[**VulakanCapsviewer**](https://vulkan.gpuinfo.org/downloads/vulkancapsviewer_3.43_arm.apk)
首页找到“apiVersion”后面的数字即为支持的Vulkan详细版本
##进阶版
使用(Zero/U)Termux
推荐已经有Termux软件/骁龙检查Turnip兼容性
进入后运行以下命令(推荐先换清华源)
- apt install vulkan-tools -y
- apt install mesa-vulkan-icd-freedreno -y(可以在第三个指令后面，但如果这样需要在运行此命令后重复第三个指令)
- apt install vulkan-loader-android -y
- vulkaninfo(/vulkaninfo -j,此指令用于生成json文件,便于发给他人检查)
- Vulkan版本是“**apiVersion**”
- 驱动版本是“**driverVersion**”(用于检查Turnip是否生效,如果Turnip生效一般显示2x.x.x)
- 如果apiVersion≥**1.2**,那么你可以去享受改完了的VulkanMod了
::: warning 警告
如果是搭载**天玑**SOC的**VIVO/IQOO**手机,那么你可以放弃了(也许有个例)
:::
---

## 署名

**编辑作者：** [空心](https://github.com/KongXing0819)  
**QQ：** 1902002294  
**邮箱：** 1902002294@qq.com  
**创建时间：** 2024.12.26  
**修改时间：** 2024.12.26
