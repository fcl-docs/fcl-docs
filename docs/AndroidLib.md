<div align="center">

# VulkanMod Android Lib

</div>

# 前言

 - !!!!!不要打开自动签名!!!!!
 - !!!!!不要打开自动签名!!!!!
 - !!!!!不要打开自动签名!!!!!
 - 接下来将教你如何在VulkanMod中添加VulkanMod Android Lib
 - 如果失败请不要抱怨别人
 - 如果需要帮助可以联系1902002294@qq.com(不一定在线)
 - !!!!!不要打开自动签名!!!!!
 - !!!!!不要打开自动签名!!!!!
 - !!!!!不要打开自动签名!!!!!
 
# 步骤
 1. 准备好VulkanMod本体jar文件(VulkanMod介绍已给出下载地址)和[VulkanMod Android Lib的jar文件](https://www.curseforge.com/minecraft/mc-mods/vulkanmod-android-libs)
 
 2. 用MT管理器(可以使用其他文件管理器,此处仅推荐)在两边分别打开VulkanMod本体和VulkanMod AndroidLib的jar文件,两边都进入META-INF文件夹,然后再进入jars文件夹,将VulkanMod Android Lib那边的5个jar复制到右边(记得关自动签名)
::: tip 提示
如果想要减小文件体积,可以删除所有开头不是“fabric”的文件(先删后加,避免删掉AndroidLib的部分,这样做的话jars文件夹中最后应剩12个文件)
:::

 3. 两个窗口均回到刚打开jar的目录,找到fabric.mod.json  
 
 4.  首先打开VulkanMod AndroidLib的jar文件中的fabric.mod.json,找到“"jars"”,其后面“[]”中是模组加载的jar，将括号中的内容复制
::: tip 提示
不需要复印中括号,“[”下面一行前面的空格可复制(称A情况)也可不复制(称B情况)
:::
 
 5. 然后退出,打开VulkanMod本体的jar文件中的fabric.mod.json,找到“"jars"”,点击其后面的“[”,依据MT管理器的“括号高亮”(就是括号带淡蓝色)找到与"jars"后面的“[”对应的后中括号(为什么不用符号表示,你在一个md文件中写[]中间夹几个字符看看)  
- 在“]”上面一行加上英文的“,”,然后换行
- 如果按第二步“提示”中做了,则应该删除“{}”中包括已删除的文件的那部分(包括“{}”),最后从前中括号到后中括号之间应有36行(不包括中括号所在的那两行)
- A情况下,在换行后按删除,直到光标到这一行最左边,再粘贴
- B情况下,在换行后直接粘贴
- 退出保存即可
::: warning 警告
**不要打开“自动签名”**  
**不要打开“自动签名”**  
**不要打开“自动签名”**  
:::
 
 6. 把成品文件放入mods文件夹测试.  
 测试时,mods文件夹不应该有其他模组,推荐搭配:VulkanMod+modmenu(查看是否加载)及其前置
 
 7. 若测试时,VulkanMod可正常加载且可以进入地图则意味着制作成功.  
 不受理兼容性问题  
 不受理Vulkan低于1.2导致的崩溃
 
---

## 署名

**编辑作者：** [空心](https://github.com/KongXing0819)  
**QQ：** 1902002294  
**邮箱：** 1902002294@qq.com  
**创建时间：** 2024.12.22  
**修改时间：** 2024.12.23  
