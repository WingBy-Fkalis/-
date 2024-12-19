**Author：fkalis**

# 安卓测试环境部署

## adb使用

[【ADB】adb命令的安装和使用（超级详细，命令大全）-CSDN博客](https://blog.csdn.net/weixin_55018452/article/details/121992202)

## 解BL锁

[给小米/红米手机root（工具基本都是官方的）——magisk篇_小米专用root工具官方-CSDN博客](https://blog.csdn.net/weixin_73636162/article/details/134043402)

[《XP、面具框架玩机》小米手机玩机教程--菜鸟小回_面具magisk和xp框架-CSDN博客](https://blog.csdn.net/qq_39231769/article/details/96366590)

### 基础需要

#### 一台电脑

#### 手机需要插入电话卡（用于绑定）

### 基本的流程

#### <font style="color:rgb(51, 51, 51);">申请解锁：</font>[<font style="color:#3b3b3b;">//www.miui.com/unlock</font>](https://www.miui.com/unlock)

> **现在貌似不用申请了，我不知道是不是我之前申请过（忘记了），但是我做的时候是没有申请的，直接进行下载即可**

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733490403428-aec0b42e-f5a4-4b46-ba1a-036da0f62004.png)

[https://www.miui.com/unlock/download.html](https://www.miui.com/unlock/download.html)

> **下载解锁工具**

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733490480218-c0678c1c-b76b-4732-952a-06693d7a3ec6.png)

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733491226445-aa08f259-4196-4bd8-b1bb-f349237e9596.png)

#### 打开手机的开发者选项

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733490593078-2a834a21-3cf3-4eb7-aaed-9d2845f40624.png)

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733490616759-e815db6f-4ef4-4895-9a0c-c7a04011b467.png)



#### 额外开启一些手机配置（个人测试踩坑，最好进行配置）

[小米解锁bl连接不上解决方法(适用MIUI手机)_哔哩哔哩_bilibili](https://www.bilibili.com/video/av444624869/?vd_source=fa4b364c33e77d1b4d4f003ae6727a44)

##### 首先需要来到开发者选项中

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733490695729-69c4db91-b06e-405c-ab42-63cfbcc984aa.png)

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733490695729-69c4db91-b06e-405c-ab42-63cfbcc984aa.png)

##### 开启OEM解锁

> **这个图片这里是黑的是以为已经解了BL锁了，在此之前是可以进行开关的，需要进行打开！！**

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733490738734-7383cfae-1306-4c8b-aa75-2d0cd4378ab8.png)

##### 下面三个usb有关的全部开启！！

> **注意：全部开启，图片中的usb调试忘记勾选了**

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733490835801-1bb24d6e-2c51-44a4-93d5-07556bd7da7e.png)

##### 修改USB的默认传输方式为MTP！！

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733490882375-c516350f-aa2a-4c5d-a238-510d3ec1d095.png)

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733490899509-7e39c6db-747f-4109-b904-0e911507936c.png)

#### 进行账户绑定

##### 需要插入电话卡，登录小米账户，点击绑定账户，进行绑定！![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733491131397-a069bc0e-a531-4971-9f11-aa7e407294e8.png)

#### 打开步骤一下载的工具

##### <font style="color:rgb(77, 77, 77);">打开文件夹，找到其中唯一的exe文件将其双击打开</font>

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733491211304-a3bc67f2-2c37-456f-96e3-1d219dac4f17.png)

##### <font style="color:rgb(77, 77, 77);">打开登录手机上的小米账号</font>

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733491211304-f71c892d-c440-47a7-b6a0-0e28f91e320b.png)

##### <font style="color:rgb(77, 77, 77);">登录后进入到了主页面小米解锁工具</font>

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733491211516-5597c9f6-61b4-41f7-b7e9-9f39d9a8819c.png)<font style="color:rgb(77, 77, 77);">  
</font>![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733491211617-59f4a796-2545-4149-aaf3-2d341ad11557.png)

#### <font style="color:rgb(77, 77, 77);">手机fast boot模式</font>

##### <font style="color:rgb(77, 77, 77);">关机</font>

##### <font style="color:rgb(77, 77, 77);">开机时长按 电源键 和 音量- </font>

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733491725872-67a973df-d673-4403-a3e0-cf2ef9669ef7.png)



#### 安装驱动

##### 点击右上角的设置

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733491834658-56c4cdc9-403d-4640-babc-c61270ee7a08.png)

##### 点击驱动检测

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733491877023-6a2b6f28-e538-40ef-b061-91c74ef025eb.png)

##### 重新插拔手机

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733491912824-d2bf698e-3caa-4cec-b66f-2d0097e16436.png)

##### 驱动安装成功即可




#### 成功刷机（如果顺利的话）

##### 点击解锁

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733492011270-20bbe126-7294-40f3-8723-3f0f6750aeef.png)  
![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733492011074-8ef444e8-35ea-4eb0-ad8b-a294636c2bdc.png)  
![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733492010744-99bfdeba-c9da-482e-9a4f-cfaa974a6707.png)

##### 等待解锁完成

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733492011038-8f4ebda7-b118-4a6d-9eff-ae38beb6085a.png)  
![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733492010749-9bf37a3e-e133-48b4-a5d1-28d67898b52c.png)











### 坑点1：一直无法检测到手机，无论怎么插都是下面这个图片

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733487868348-303d679c-9894-4237-848d-ac0a7885c330.png)

#### 解决方式：

> **<font style="color:rgb(51, 51, 51);">右键 → 我的电脑  → 管理   →设备管理器 →  找到未识别的或者已经识别到的安卓设备   →右键  → 禁用  → 然后再启用 → 重启电脑 → 重新打开软件 → 重新插入手机即可</font>**

[小米6解锁BL显示未连接手机解决办法以及各种小技巧汇总...-手机中国论坛](https://bbs.cnmo.com/thread-16403360-1-1.html)

##### 搜索设备管理器

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733492191944-2bc37f1f-c4d2-4e8c-af7d-256ea7c27e3a.png)



##### 禁用设备

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733492798698-ee9360fd-5f9a-4600-9188-bfc0dad57749.png)

##### 再用同样的方式进行启用设备

> **禁用后自然会变成启用**

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733492798698-ee9360fd-5f9a-4600-9188-bfc0dad57749.png)

##### 重启电脑即可连接上（必须要重启！！）

> **图片源自网上，没有来得及进行截图保存**

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733487995866-ce96ab57-d3db-4f61-b371-2209cf8f8cfd.png)

### 坑点2：检测手机后，一直卡在百分之50，然后提示失败

#### 解决方法

[小米刷机解锁BL卡50问题解决过程分享 - 哔哩哔哩](https://www.bilibili.com/opus/927889003848400919)

##### <font style="color:rgb(24, 25, 28);">使用老版本的BL解锁软件 : 推荐V5.5版本（个人测试使用的也是老版本的）</font>

历史版本的全部BL解锁软件

[MiUnlock 解锁工具下载合集 – MIUI历史版本](https://miuiver.com/miunlock/)

##### <font style="color:rgb(24, 25, 28);">切换数据接口：切换为usb2.0的接口</font>

我测试的时候，上面的那个不行，切换为下面的就可以

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733493082758-7c114c91-fd74-4927-ba80-3068f49fbc54.png)



![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1732953220540-6dc38494-94c3-4901-8379-68de49094999.png)

##### 修改注册表，能识别接口

将其保存为bat，并且以管理员的方式运行

```python
@echo off
reg add "HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\usbflags\18D1D00D0100" /v "osvc" /t REG_BINARY /d "0000" /f
reg add "HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\usbflags\18D1D00D0100" /v "SkipContainerIdQuery" /t REG_BINARY /d "01000000" /f
reg add "HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\usbflags\18D1D00D0100" /v "SkipBOSDescriptorQuery" /t REG_BINARY /d "01000000" /f  

pause

```

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733493165943-0d947bf0-ec60-4562-b337-d995e2b15886.png)

##### <font style="color:rgb(24, 25, 28);">重启手机和电脑，再次进入FASTBOOK模式（一定要重启！）</font>

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1732953220540-6dc38494-94c3-4901-8379-68de49094999.png)





## 刷 magisk 面具 ROOT（修补boot）

> **基本流程：**
>
> 1. **找到系统文件**
> 2. **解压压缩包获取到boot.img（解压获取到payload.bin，修复为boot.img）**
> 3. **安装面具**
> 4. **通过面具修复boot.img 获取到新的img**
> 5. **安装驱动**
> 6. **使用adb将修复后的img传到电脑**
> 7. **通过adb+fastboot刷入img，成功获取到root权限**

[「刷机教程」小米手机解锁后通过修补BOOT获取ROOT](https://mp.weixin.qq.com/s/J612mXXYc5RhAkwHYyhzfQ)

[小米红米全系root刷面具magisk教程（超详细）](https://mp.weixin.qq.com/s/GL52ESDE5l_CgFQ_pAPkzA)

[Magisk安装教程](https://magiskcn.com/)

[Magisk安装教程](https://magiskcn.com/)



### <font style="color:rgb(33, 33, 33);">找到当前版本所对应的系统（两种方法：1. 通过手机下载(推荐)，2. 通过官网寻找）</font>

#### 方法1：<font style="color:rgb(33, 33, 33);">通过手机下载(推荐）</font>

**来到系统页面**

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733494889025-942128a3-bab2-472e-9131-2f949533c21a.jpeg)



**点击下载最新完整包**

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733494854410-4dd4b5a9-f533-4d6f-9e63-4cf1864b57d9.jpeg)

**点击浏览器，来到下载就可以看到下载中的安装包**

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733495249418-54704cb7-7f93-45d2-bc8a-b5bb7b4e2b01.jpeg)

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733495280390-fb5aa176-cdb5-4823-9846-09d0fb409890.jpeg)

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733495339546-6ebde2d0-2cf9-48ae-b316-835a8c9024e2.jpeg)



#### 方法2：通过官网寻找

**手机中查看系统版本**

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733494889025-942128a3-bab2-472e-9131-2f949533c21a.jpeg)

**官网系统包寻找**

[**https://xiaomirom.com/series/**](https://xiaomirom.com/series/)![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733495434110-f5802af4-9f69-4eda-b8c1-5ad2c38c9d7e.png)

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733495445841-f3865080-f668-4446-9ad2-bc748246c014.png)





### 解压下载到的系统压缩包获取到boot.img

#### 通过adb将下载的zip上传到电脑

[通过adb pull和adb push 手机与电脑之间传输文件-CSDN博客](https://blog.csdn.net/Goals1989/article/details/120183562)

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733495716788-6ed954a7-d1ab-4f58-972f-c972503d2447.png)





> **注意：二和三，选择其中一个做就行，看解压出来的有没有boot.img，如果有直接用里面的boot.img就可以！！**

#### 解压压缩包还原boot.img

1. <font style="color:rgb(33, 33, 33);">解压卡刷包中的playloade.bin，将它放在桌面上</font>

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733494800693-5942297e-8c7c-4c88-8f04-0595a515c892.jpeg)

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733494800767-acf75536-469f-4246-993a-cf86b75e99cc.jpeg)

2. <font style="color:rgb(33, 33, 33);">下载FastbootEnhance，并解压放在桌面上</font>

[GitHub - libxzr/FastbootEnhance: A user-friendly Fastboot ToolBox & Payload Dumper for Windows](https://github.com/libxzr/FastbootEnhance)

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733494800713-3cb938ed-1dd3-4fa8-a3d7-586d8c20c790.jpeg)

<font style="color:rgb(33, 33, 33);">3. 打开FastbootEnhance文件夹，并运行主程序</font>

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733494801184-fa145066-59f4-41d6-8b80-f88a2328372f.jpeg)

4. <font style="color:rgb(33, 33, 33);">将功能切换到Playload.bin解包</font>

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733494801195-deb72cb5-8875-42e4-948a-b596a54e538f.jpeg)

5. <font style="color:rgb(33, 33, 33);">将之前解压得到的playload.bin拖入程序窗口</font>

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733494801335-f8e9c9c2-4cfe-4908-832b-eea5bed04149.jpeg)

6. <font style="color:rgb(33, 33, 33);">等待读取文件信息，随后将功能切换至分区信息</font>

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733494801344-05d6071c-4f0c-4d9d-b367-07e830fc890a.jpeg)

7. <font style="color:rgb(33, 33, 33);">选择boot分区，导出boot.img</font>

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733494801618-ce13491b-5a0f-499c-b5d8-03b02fdfd05a.jpeg)

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733494801915-438b7fee-44a7-46cf-b0d9-d41a22b7d1cc.jpeg)

8. <font style="color:rgb(33, 33, 33);">等待操作完成，此时桌面会出现boot.img</font>

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733494801897-45e2c77d-a992-428c-b334-5bc946b68410.jpeg)

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733494802183-61c53df6-8b19-4f6e-bdb0-cf42fb2811c9.jpeg)



#### 解压压缩包直接可以获取到boot.img

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733496161100-168c3ef4-af5a-40bc-9aa1-18e212383481.png)



### 通过获取到的boot.img和面具生成新的img

#### 用adb push 将获取到的boot.img发送到手机（略，跟上面一样的）


#### 手机直接下载apk 安装面具magisk

[https://github.com/topjohnwu/Magisk/releases/tag/v28.0](https://github.com/topjohnwu/Magisk/releases/tag/v28.0)

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733496373428-bc1f7c1a-c297-4a30-81a9-1cbbc14ff760.png)

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733494802294-a7045252-8607-4670-8967-57ac177b3d4b.jpeg)



#### 利用面具修复boot.img，生成新的img

1. 打开面具

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733496608070-a4de4fed-9aba-4f7a-a3d6-e1100876b491.jpeg)

2. 点击安装

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733496651097-017aea19-3bb8-4f36-a921-91a8824e5045.jpeg)

 ![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733496681026-1e457c32-6189-4afc-8f22-83647f55d0df.jpeg)

3. 勾选使用img进行修补

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733496740403-981519d2-a00e-41b8-a8d4-fa70f850dcfe.png)



4. 选择刚刚传给手机的boot.img文件

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733496797980-959b8584-d415-4373-9260-6466629432ac.jpeg)



5. 等待生成新的img文件

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733494803251-d10886ac-957c-4146-90c0-fc235831ffc2.jpeg)



#### 使用adb将新的img传到电脑上

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733496904199-c08fc72c-e508-458d-9eb1-30d5464491ff.png)

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733496919059-890c298b-39ea-4e08-a2f9-26891c2c3e2b.png)



### 安装驱动

> **这一步一定要做，否则后面使用adb可能会有问题，比如使用adb reset fastboot的时候会不断重启**

[IDT Tools吾爱版.rar](https://www.yuque.com/attachments/yuque/0/2024/rar/35288468/1733497255300-53798db2-801c-44ec-aa44-e09c01e9a358.rar)

[https://www.52pojie.cn/thread-1737197-1-1.html](https://www.52pojie.cn/thread-1737197-1-1.html)

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733497081109-56e50d75-dc38-4c13-b98a-4374c776a556.png)

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733494804128-145a7a95-5a8e-49a7-b7b4-11f4913d6571.jpeg)

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733494804102-c7358c4e-15c1-473d-87f4-e38711a5255c.jpeg)

<font style="color:rgb(189, 189, 189);"></font>

2. <font style="color:rgb(33, 33, 33);">打开电脑的设备管理器，此时可以在列表中看到设备连接。应该是以下两种情况之一</font>

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733494804402-4f9f59c3-e4b8-4b0e-82a2-86feb90286af.jpeg)

<font style="color:rgb(189, 189, 189);">bootloader</font>

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733494804394-54ff99e6-37b9-4a0a-a6ac-bc7e12191b6b.jpeg)

<font style="color:rgb(189, 189, 189);">adb</font>

<font style="color:rgb(33, 33, 33);"></font>

### <font style="color:rgb(33, 33, 33);">使用 fastboot flash boot 将img刷入系统</font>

1. 使用数据线连接设备
2. <font style="color:rgb(33, 33, 33);">fastboot flash boot xxx.img</font>

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733494804675-6eb87c0e-62e6-40f1-bf7d-1d82aad01a4c.jpeg)

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733494805138-f16589c2-9e9a-41bb-935e-cde7ef2fddae.jpeg)

3. <font style="color:rgb(33, 33, 33);">按下回车键执行命令</font>

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733494804735-8c8fe60b-3646-45e6-82d1-0e886f162cfe.jpeg)

<font style="color:rgb(33, 33, 33);"></font>

### <font style="color:rgb(33, 33, 33);">重启设备，打开Magisk，出现版本信息或是模块变亮就算成功</font>

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733494804990-3a2d6555-5d69-465d-b887-671ffd48a87d.jpeg)



## 下载MT管理器


## 刷入Lxposed框架

[https://lsposed.cn/221](https://lsposed.cn/221)

[https://github.com/LSPosed/LSPosed](https://github.com/LSPosed/LSPosed)



## 刷入Kali Net

> **目前网上的教程都太复杂了，实际上很简单，原创教程**

### 电脑打开官方连接

[Kali NetHunter App Store - Android App Repository for Penetraton Testing and Forensics](https://store.nethunter.com)

手机扫码下载软件

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733498474173-8d155946-c06e-49b9-80a7-dd9754766353.png)

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733498547314-12125bb4-601b-4e63-a3c7-16fbb9231f5c.jpeg)



### 访问官网下载软件

下载这四个软件

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733498681872-e19f0d70-8909-49d2-a7bd-90aae796c066.jpeg)



### 去官网下载移动安装包

[Get Kali | Kali Linux](https://www.kali.org/get-kali/#kali-mobile)

1. 根据个人的系统来

![](https://cdn.nlark.com/yuque/0/2024/png/35288468/1733498734763-f7d61ed1-1d9e-44b0-83d0-b3ab8621ab27.png)

2. 查看压缩包可以看见里面有个kalis的压缩包

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733498943875-a117c824-77ca-4784-82bc-e8f3a877ee68.jpeg)

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733498967325-d9b5dd97-7831-4c8e-81d7-41fbfcbe3675.jpeg)

3. 将其解压出来

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733499003364-9cdfd43d-e7db-4c8c-8c63-f8ebaab206ac.jpeg)







### 打开下载好的NET Hunter

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733499074318-ca33d025-be98-4378-b462-45d95f3c6280.jpeg)

 ![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733499094345-f4eae1f7-80df-438b-8d8c-68dda20d841c.jpeg)



### 来到Chroot Manager

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733499111518-7ec56cb0-603d-478c-94b7-1478bf1e3202.jpeg)



### 点击install进行安装

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733499167636-2879bf59-d834-42df-8c0b-db1571a783e9.jpeg)

### 选择刚刚从压缩包解压出来的kalis压缩包

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733499252799-11c84af9-d1b9-414a-9f3e-0486821580b1.jpeg)



### 等待安装

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733499184804-1cc0f10f-2c12-44a6-885e-d927935d292b.jpeg)



### 完成后点击start开启kali

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733499355681-9aa872d3-450b-4a11-b1be-07b944d92abe.jpeg)

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733499513806-03996cc0-6bbc-4cb2-8b1a-4cb109e71f76.jpeg)



### 启动终端

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733499391569-6b023119-7b65-4499-9eac-e4f3473e3d2d.jpeg)

### 成功连接控制台

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733499416518-5d728542-34d4-402d-98c7-594dbe21adc3.jpeg)



### 安装kalis的工具，包库

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733499665405-863c8e60-3a65-4251-9098-077ffe6240a3.jpeg)

![](https://cdn.nlark.com/yuque/0/2024/jpeg/35288468/1733499689817-b4bb0a72-4232-42b5-b18f-aa884b9fe00b.jpeg)



### 开启vnc远程控制

[VNC开启后仅能本机访问_vnc用127.0.0.1-CSDN博客](https://blog.csdn.net/jiaofug/article/details/88955831)

```shell
vncserver :1 localhost no
```
