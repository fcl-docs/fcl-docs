<div align="center">

# 渲染器

</div>

## 目录
- [渲染器选择](#渲染器选择)
- [渲染器比较](#渲染器比较)

## 渲染器列表

- [holy](https://github.com/FCL-Team/Holy-GL4ES)
- [zink](https://docs.mesa3d.org/drivers/zink.html)
- LTW
- 待补充...

## 渲染器选择

### 1. 性能向选择

- 在1.17以下(包括1.17)版本无脑选择holy，1.17以上版本选择ltw(在有钠等有特殊情况时使用)或者holy。
- 如果觉得还不够，你可以用[Vulkan mod](https://www.mcmod.cn/class/6626.html)(mc百科)来获得最佳帧数。

### 2. 兼容性向选择

- 选择zink，不过你会牺牲一大截帧数。
- 兼容性比较: zink>holy>ltw

## 渲染器比较

|  | holy | zink | LTW |
| --- | --- | --- | --- |
| 兼容性 | 兼容性一般 | 兼容性良好 | 兼容性一般 |
| 性能 | 较好 | 较差 | 较好 |
| 特点 | 默认选择，优化强 | 强兼容，牺牲帧数 | 弥补了holy的部分兼容性，并有新的缺陷，优化强 |


待补充...

如有建议或问题，欢迎提交issue或pr。仓库地址：[https://github.com/ning-g-mo/fcl-docs](https://github.com/ning-g-mo/fcl-docs)