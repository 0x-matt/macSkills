# Mac 外接磁盘读写 NTFS/exFAT

![](/assets/Xnip2018-10-20_16-26-49.png)

  很多刚接触 Mac 电脑的新人，都会因为 Mac 默认不能写入外接磁盘 \(NTFS格式\) 而苦恼，这个问题或多或少的给你的工作或者生活带来一些困扰；本篇将介绍 Mac 读写外接磁盘的各种方案，不夸张的说，你能在网上搜到的方案这里都有，相信总有一种能适合你。  
“磁盘读写”: 就是从磁盘读取内容和往磁盘里写内容，一般情况 Mac 可以从一个通过 USB 连接的外接磁盘 ( U 盘或者移动硬盘这里统称为外接磁盘)里拷贝文件到 Mac 电脑里。但是反过来却不可以，也就是从 Mac 里拷贝文件到外接磁盘(这个过程叫写入)。因为大部分的磁盘初始格式都是 NTFS ，Mac 默认不支持 NTFS 格式的文件写入。NTFS 是 New Technology File System 的缩写，简单来讲就是一种文件系统。[点我了解 NTFS 维基百科。](https://zh.wikipedia.org/zh-hans/NTFS)  

<hr/>

## 1. 希捷 (Seagate) 移动硬盘官方特供的写入 NTFS 的软件

![](/assets/Xnip2018-10-20_16-35-47.png)  
　　如果你刚好买的是希捷 (Seagate) 的移动硬盘（如上图，图片仅供参考，理论上只要是希捷品牌的硬盘都可以），Mac 写入的问题就很好解决了，希捷官方提供了磁盘读写软件的免费下载，该软件就是大名鼎鼎的 Paragon NTFS for Mac ，没错正常情况下，该软件是收费的，而且不便宜，现在你可以在希捷的官方网站下载到，但是只是针对希捷的硬盘有效。[点我到希捷官网下载终身免费的 Paragon NTFS for Mac。](https://www.seagate.com/cn/zh/support/downloads/item/ntfs-driver-for-mac-os-master-dl/)

软件的安装和使用都很简单，文末会做介绍。

## 2. 新硬盘可以考虑格式化成 exFAT 格式  
如果是新入手的硬盘，或者硬盘里文件不多，可以考虑格式化成 exFAT ，exFAT 格式的硬盘 Windows 和 Mac 都原生支持读写，如果你需要经常在 Mac 和 Windows 直接切换，可以考虑将硬盘格式化为 exFAT 格式。

使用 Mac 系统自带的磁盘工具软件，就可以进行格式化了。

![](/assets/Xnip2018-10-20_17-13-30.png)





