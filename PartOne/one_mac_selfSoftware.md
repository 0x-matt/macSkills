## Mac 自带软件使用简介
> Mac 上一些自带的软件，看似简单，却也能解决不少工作中的问题，下面简单简绍几个可能被我们忽视的 Mac 自带软件。  

<!-- toc --> 

### 数码测色仪 <image src="http://img.xiaobotalk.cn/macSkills/selfSoft_12.png" width="6%"/>    

`数码测色仪` 是 Mac 自带用来检测屏幕上某点的 RGB 值，使用非常方便，打开后，鼠标光标指向哪里，就显示哪里的 RGB 颜色值，推荐做设计的人员使用。  

<image src="http://img.xiaobotalk.cn/macSkills/selfSoft_08.png" width="60%"/>

### 图片`预览`软件 <image src="http://img.xiaobotalk.cn/macSkills/selfSoft_14.png" width="6%"/>  
  
不要被这个软件的名字`预览`迷惑了，从名字上看他只能用来预览图片，但实际上用它还可以用来做一些图片处理；

1: 图片基本调整
这是一个比较使用的一个功能，好多网站都对上传的图片大小进行了限制，这时可以使用`预览`软件调整图片的大小，同时还可以做图片翻转。  

<image src="http://img.xiaobotalk.cn/macSkills/selfSoft_09.png" width="60%"/>    

<br/>
<br/>
2: 使用标记工具栏做一些较为高级的修图  

点击软件搜索框旁边的<image src="http://img.xiaobotalk.cn/macSkills/selfSoft_11.png" width="5%"/>图标，可以调出标记工具栏：
<image src="http://img.xiaobotalk.cn/macSkills/selfSoft_10.png" width="50%"/>

  这一栏可以完成图片裁剪，添加文字，修改颜色，刻章，甚至使用套索工具进行轻量级 PS 处理。更多关于预览可参考 Apple 官方给出的文档 [如何在 Mac 上使用“预览”功能编辑图像和标记 PDF](https://support.apple.com/zh-cn/HT201740#editphotos)。

### QuickTime Player  <image src="http://img.xiaobotalk.cn/macSkills/selfSoft_15.png" width="6%"/> 对 Mac/iPhone 录制屏幕



#### Mac 屏幕录制
选择 `文件` -> `新建屏幕录制` ，就开始对整个屏幕进行录制：  
<image src="http://img.xiaobotalk.cn/macSkills/selfSoft_18.png" width="50%"/>

#### iPhone 屏幕录制  

当 iPhone 通过数据线连接到 Mac 时，通过`文件` -> `新建屏幕录制`，然后选择 iPhone，就开始对 iPhone 屏幕的实时录制：  
<image src="http://img.xiaobotalk.cn/macSkills/selfSoft_17.png" width="50%"/>

### 使用`屏幕快照`软件 <image src="http://img.xiaobotalk.cn/macSkills/selfSoft_13.png" width="6%"/> 进行区域录屏

与 QuickTime Player 不一样的是，`屏幕快照` 软件可以选择屏幕区域进行录制，同时还可以显示鼠标轨迹：  

<image src="http://img.xiaobotalk.cn/macSkills/selfSoft_16.png" width="80%"/>  

更多关于`屏幕快照`可参考 Apple 官方给出的文档：[如何在 Mac 上拍摄屏幕快照](https://support.apple.com/zh-cn/HT201361)

### Xcode 附带的文件差异比对软件: FileMerge   <image src="http://img.xiaobotalk.cn/macSkills/selfSoft_07.png" width="6%"/>

如果你安装了 Xcode (开发者的集成开发工具)，会同时附带几个不错的软件，FileMerge 是一款不错比较两个文件差异的工具。但是这个软件无法在启动台或者应用程序中直接找到，通过 spotlight 搜索可以搜索到。

<image src="http://img.xiaobotalk.cn/macSkills/selfSoft_06.png" width="70%"/>  

之所以不能再启动台找到它，是因为 FileMerge 并不在应用程序根目录下，具体目录在:  `Xcode` - `显示包内容` - `Contents` - `Applications`

<image src="http://img.xiaobotalk.cn/macSkills/selfSoft_05.png" width="70%"/>  

### Automator 工作流  
比起 Automator ，我更多使用的是 Alfred ，它们都是工作流软件，只不过 Automator 是苹果自家出的软件，Alfred 是一款三方软件，如果想了解 Alfred 使用和介绍，可以参考我后边的文章：[Mac 第一神软 Alfred](https://www.xiaobotalk.cn/PartTwo/two_Alfred.html)。  

#### 使用 Automator 制作每日邮件日报 

虽然 Automator 功能很强大，但我自己实际使用 Automator 体验下来，发现 Automator 更适合用来处理重复事件；比如你在公司每天要发邮件日报，那么可以通过 Automator 做一个工作流，自动生成当天的邮件格式，因为每天发的日报格式中有很多都是重复的，比如发件人，收件人都一样，因为是日报，所以要包含每天的当天的日期，而`当天日期`可以使用 Automator 变量自动生成。  

第一步，打开 Automator 新建`应用程序`(因为应用程序可以自动运行)；  

<image src="http://img.xiaobotalk.cn/macSkills/selfSoft_21.png" width="70%"/>

第二步，从资源库中选择`邮件` -> `新建邮件信息`，并拖入右边的工作流程中；  
<image src="http://img.xiaobotalk.cn/macSkills/selfSoft_22.png" width="70%"/>

第三步，配置邮件中相关信息(收件人，内容格式等)，然后从变量一栏中选择`日期与时间` -> `今天的日期`，拖入到邮件的主题中，日期的格式可以自定义修改； 
<image src="http://img.xiaobotalk.cn/macSkills/selfSoft_19.png" width="70%"/>

保存应用程序，以后每次双击做好的应用程序，就会自动创建好邮件模板：

<image src="http://img.xiaobotalk.cn/macSkills/selfSoft_20.png" width="70%"/>


#### Automator 教程链接

* [苹果官方教程：自动操作使用手册](https://support.apple.com/zh-cn/guide/automator/welcome/mac)
* [少数派：Automator 简单介绍及入门玩法](https://sspai.com/post/36667)
* [Automator 视频教程-英文版本](http://www.macosxautomation.com/automator/)

(完)
