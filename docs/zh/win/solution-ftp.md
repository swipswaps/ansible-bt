## 如何上传和管理文件

我们知道文件管理主要包括：复制、粘贴、剪切、删除、重命名、压缩、刷新、新建文件、新建目录等操作，宝塔Windows面板支持多种文件管理方式，下面分别描述：

### 方案一：使用在线文件管理

打开宝塔->文件管理界面：

![](http://libs.websoft9.com/Websoft9/DocsPicture/zh/btwin/bt-filemanage-websoft9.png)


可以进行新增、删除、编辑、解压、权限设置、压缩等几乎所有的操作

具体参考《[宝塔官方文档-文件管理](https://www.kancloud.cn/chudong/bt2017/424266)》

### 方案二：远程桌面直接管理

远程桌面，登录到服务器，直接使用 复制/粘贴 的方式实现本地与远程文件的拷贝


### 方案三：使用FTP

当每个网站分属于不同的客户的时候，给每个网站分配对应的FTP是必要的：

* 建立网站
* 设置FTP账号
* 下载FTP客户端，推荐Filezella
* 连接FTP，上传文件

若FTP无法正常连接，请根据以下说明排除错误
1. 安全组的21端口是否打开
2. 是否主动/被动模式都不能连接
3. 宝塔中的防火墙设置禁止了21端口
