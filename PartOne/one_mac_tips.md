## Mac 必备基础操作实用技巧  

可能很多人不太知道苹果官方制作了精美的 [macOS 中文使用手册](https://support.apple.com/zh-cn/guide/mac-help/the-dock-mh35859/mac)，有图有真相，阅读不费力。如果是零基础使用 Mac 可以前往观看，我就不重复造轮子了，尽量写一些不好发现的实用小技巧。   

> 本文很多设置都需要在 `系统偏好设置` 中完成，`系统偏好设置`可以在启动台、Dock 栏、中找到，或者点击屏幕左上角的 "" -> `系统偏好设置`。

<!-- toc -->   


### 快速显示桌面和使用好屏幕触发角  

<HR style="height:1px" />

有时电脑同时打开了多个窗口，而这时我们想快速简洁的回到桌面，去做其他工作，这种场景在实际使用中是非常多见的。要想在被各个软件窗口遮挡的情况回到桌面，最机械的方式，是把每个窗口最小化或者直接关闭。  
windows 系统下，考虑到了这种使用场景，可以使用 `win + D` 的快捷键组合快速显示桌面，或者在任务栏右键然后选回到桌面，还可以通过设置任务栏，让鼠标光标移动到任务栏右下角时显示桌面。  

Mac 系统下同样有类似问题，Mac 也提供了相应的快捷方式。

1. 触摸板手势  
最常见的是使用触摸板手势，在`系统偏好设置` -> `触摸板` -> `更多手势`中可以看到，通过<span style="color:red">拇指和其他三个手指张开</span>的动作，可以显示桌面。更多手势教程可以前往苹果官方的 [在 Mac 上使用多点触控手势](https://support.apple.com/zh-cn/HT204895)观看。  
<img src="http://img.xiaobotalk.cn/mac_tips01.png" width = "60%" />  

2. 配置快捷键  
触摸板不能解决所有场景下的需求，比如很多人用 Mac 外接了显示器和键盘，这是触摸板就用不到了。另外老一点 Mac 触摸板较小，手大一点的人同时用 4 个手指在触摸板上张开、闭合，还不是很方便，这时候我们可以通过配置快捷键来显示桌面；如果你习惯了 windows 下 `win + D` 的方式，在 Mac 下我们可以配置为 `Command + D` 的快捷方式来显示桌面。打开`系统偏好设置` -> `键盘` -> `快捷键`，来配置你自己的快捷键。  
另外我们还可以用 Mac 触发角来实现显示桌面功能。  
<img src="http://img.xiaobotalk.cn/mac_tips02.png" width = "60%" />

3. 使用好 Mac 触发角  
触发角即长方形显示屏的四个角，鼠标移动到每个角都可以触发一些动作，这些动作我们可以自定义，比较推荐的是让其中一个触发角设置为显示桌面，下图是我自己的触发角设置，由于我经常外接显示器，所有有一个角落没有设置。打开 `系统偏好设置` -> `调度中心` -> `触发角`。  
<img src="http://img.xiaobotalk.cn/mac_tips03.png" width = "60%" />

### 触摸板 3 指拖移   

<HR style="height:1px" />

尽管 2015 年之后的 Mac 触摸板支持了 Force Touch ，但是很多人已久习惯用 3 指拖动来移动软件窗口，而 3 指拖动这个设置在触摸板设置里并没有；而是被隐藏在 `系统偏好设置` -> `辅助功能` -> `鼠标与触摸板` -> `触摸板选项` 中。  
<img src="http://img.xiaobotalk.cn/mac_tips04.png" width = "60%" />
> tip: 如果你想找的某个设置选项在系统偏好设置中不好找，可以使用系统偏好设置界面右上角的搜索功能。

### 分屏操作  

<HR style="height:1px" />  

在 OS X El Capitan 或更高版本中，Split View 功能可以在 Mac 屏幕上满屏显示两个应用，无需手动移动窗口并调整其大小。   
<img src="http://img.xiaobotalk.cn/mac_tips08.png" width = "20%" />

操作只需长按窗口左上角的全屏按钮，即可进入，关于 Split View 苹果官网也有相应的教程，具体请前往查看[在 Mac 上使用 Mission Control](https://support.apple.com/zh-cn/HT204100)。

### 键盘键位调整互换   

<HR style="height:1px" />

在 `系统偏好设置` -> `键盘` -> `修饰键` 中，系统给了我们互换键盘键位的能力。   

一个比较实用的做法是互换 `Control` 键和 `Caps lock` 键，原因是 `Control` 键实际使用中比较高频，而 `Caps lock` 键却很少用，经常我们都是使用 `Shift` 来切换大小写，所以建议互换这两个键位；这个灵感也是来自 `HHKB` 键盘键位布局。  
<img src="http://img.xiaobotalk.cn/mac_tips06.png" width = "60%" /> 


### Finder 相关  

<HR style="height:1px" />

<!-- 习惯了 windows 系统中右键新建文件。-->

对于广大程序员，可能都知道 Mac 上的一款知名 Finder 插件 `Go2Shell` ，快速的在终端打开当前文件夹。今天要告诉大家的是，终端打开文件夹其实还有其他快捷途径，就是右键 -> 服务 -> 同意可以实现。  
<img src="http://img.xiaobotalk.cn/mac_tips11.png" width = "60%" />  
如果你安装了 iTerm2，iTerm2 也可以在服务中使用，如果你的右键服务中没有图中所示的选项，可以在 `系统偏好设置` -> `键盘` -> `快捷键` -> `服务` 中勾选。  
<img src="http://img.xiaobotalk.cn/mac_tips077.png" width = "60%" />


### 关闭仪表盘  

<HR style="height:1px" />

很多 Mac 用户表示仪表盘在 Mac 的作用不大，还占了一个空间；不想看见仪表盘，我们可以在 `系统偏好设置` -> `调度中心` -> `仪表盘`，进行关闭。  
<img src="http://img.xiaobotalk.cn/mac_tips09.png" width = "60%" /> 

### Mac 远程协助  

<HR style="height:1px" />

Mac 的屏幕功能可以通过系统自带的 iMessage 实现，不用安装其他软件就能使用。对于远程协助的小白来说甚至不需要操作，通过 iMessage 建立联系即可，之后等待对方发起共享请求 — 接受。  
<img src="http://img.xiaobotalk.cn/mac_tips111.png" width = "60%" />   


### Mac 允许安装不明身份的开发者应用  

<HR style="height:1px" />

有时候安装一些软件时候，Mac 会提示，应用来自不明身份的开发者；
<img src="http://img.xiaobotalk.cn/mac_tips21.png" width = "60%" />


这并不总是代表软件不安全，一个原因是，开发软件的程序员并没有注册成为 Apple 开发者；遇到这种情况，我们可以在 `系统偏好设置` -> `安全性与隐私` -> `通用` 中选择 `仍要打开`。
<img src="http://img.xiaobotalk.cn/mac_tips22.png" width = "60%" /> 


###  Mac 系统快速查看插件 Quick Look Plugs   

<HR style="height:1px" />

Mac 系统一个非常方便的功能就是预览，选中任何一个文件，敲击`空格`便可对文件进行快速查看，不仅如此，开发者们还未这个功能开发了大量的插件；本来要写一下的，搜了下文章，网上已经有很全面的文章了，下边做个友情链接:
[Mac系统14款快速查看插件Quick Look Plugs](https://juejin.im/entry/59f60b1ef265da433562077b) -- 来自掘金。

### 番外篇酷炫屏保  

<HR style="height:1px" />

好多 Mac 用户都喜欢为它设置各种美丽的壁纸，和屏幕保护，Mac 设置壁纸的软件有很多，有些软件还可以设置动态壁纸，读者可以自行 google / baidu 一下，这里就不过多介绍了；下面我为大家推荐几款不错的屏幕保护程序。

1：翻页时钟屏幕 [Fliqlo](https://fliqlo.com/)  
<img src="http://img.xiaobotalk.cn/mac_tips14.png" width = "60%" />

2：极简时钟屏幕 [Padbury Clock](https://www.screensaversplanet.com/screensavers/padbury-clock-1027/)  
<img src="http://img.xiaobotalk.cn/mac_tips13.png" width = "60%" />

3：最美动态屏保 [Aerial](https://github.com/JohnCoates/Aerial/releases)   
Aerial 是托管在 github 上的一款开源 Mac 屏保，以 [github-release](https://github.com/JohnCoates/Aerial/releases) 形式发布，star 超过 1.2W(2018/10 查看)，可见大家对它的喜爱程度；该屏保视频取材自苹果零售店 Apple TV 的专用屏保——全部由苹果亲自制作的航拍影片。里面的每一个航拍都是不可多得的精美作品！快去下载尝试吧。   
<img src="https://cdn.sspai.com/2017/04/30/8a84e0247dbdd928603895baaf58d767.gif?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1" width = "70%" />   


### 最后推荐几个图片(壁纸)网站  

<HR style="height:1px" />

1. [pixabay 惊人的免费图片和视频资源](https://pixabay.com/)
2. [Awesome Wallpapers](https://alpha.wallhaven.cc/)
3. [Instant Logo Search](http://instantlogosearch.com/)


(完)