## Visual Studio 2017安装
### 离线下载安装文件

　　登入VS官网下载页面，选择需要的版本点击下载，下载页（[点此进入](https://www.visualstudio.com/zh-hans/downloads/)）。

### 下载完整版离线包

全语言据说100G
```
vs_enterprise.exe --layout d:\vs2017offline
```
简体中文20G
```
vs_enterprise.exe --layout d:\vs2017offline --lang zh-CN
```

.net core开发2G
```
vs_enterprise.exe --layout d:\vs2017offline --lang en-US --add Microsoft.VisualStudio.Workload.NetCoreTools Microsoft.VisualStudio.Workload.NetWeb
```

### 安装证书

在运行安装程序之前，您需要在\ certificates文件夹中安装根证书

### 安装
运行离线根目录下的安装程序，各版本位置如下：
企业版：离线文件存储文件夹\vs_Enterprise.exe

### 更新
当微软提示有版本更新后，到官网下载最新的在线安装执行文件。按上面的安装文件的步骤，但是必须注意，--layout后的下载文件夹路径必须是旧版本离线文件存储的位置（如果你之前下载好没移动过那就是之前的下载路径），执行命令后安装程序会扫描已有文件并下载更新文件和新增文件。

### Key

Visual Studio 2017（VS2017） 企业版Enterprise 注册码：NJVYC-BMHX2-G77MM-4XJMR-6Q8QF

Visual Studio 2017（VS2017） 专业版Professional 激活码key：KBJFW-NXHK6-W4WJM-CRMQB-G3CDH