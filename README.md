# M3U8-Downloader
M3U8-Downloader是基于Electron框架开发的一款可以下载、播放HLS视频流的APP，功能特点如下：

| 功能 | 支持 |
| :-- | --: |
| HLS协议点播源 | ✓ |
| 自定义Http协议头下载 | ✓ |
| 自定义KEY和IV解密 | ✓ |
| 本地M3U8文件下载 | ✓ |
| HLS协议直播源 | ✓ |
| 标准 AES-128-CBC加密 | ✓ |
| 标准 AES-196-CBC加密 | ✓ |
| 标准 AES-256-CBC加密 | ✓ |
| 非标准 AES-*-CBC加密 | ㄨ(可定制) |


<div align="center">
	<br>
	<img width="739" src="https://github.com/HeiSir2014/M3U8-Downloader/blob/master/resource/HLSDownloadShow-3-1.gif?raw=true" alt="M3U8-Downloader">
	<br>
</div>
<div align="center">
	<br>
	<img width="739" src="https://github.com/HeiSir2014/M3U8-Downloader/blob/master/resource/HLSDownloadShow-3-2.gif?raw=true" alt="M3U8-Downloader">
	<br>
</div>

<div align="center">
	<br>
	<img width="739" src="https://github.com/HeiSir2014/M3U8-Downloader/blob/master/resource/HLSDownloadShow-4.gif?raw=true" alt="M3U8-Downloader">
	<br>
</div>

# 流程原理图

---

<div align="center">
	<br>
	<img width="1024" src="https://github.com/HeiSir2014/M3U8-Downloader/raw/master/resource/flowchart.png" alt="M3U8-Downloader">
	<br>
</div>

---

# 官网
[M3U8-Downloader 官网](https://tools.heisir.cn/HLSDownload)

QQ交流群：341972319

[点我加QQ交流群](https://jq.qq.com/?_wv=1027&k=nhFrZBS0)

# 获取M3U8视频地址

在chrome浏览器打开视频网页，按下F12,页签点击到Network页面，在Filter框里输入"m3u8",然后按F5刷新页面，如果网页里的视频使用的是HLS源，就可以在这里捕获到视频流地址，然后选中右键 Copy -> Copy Link Address.
提供m3u8源地址，下载并无损转码Mp4文件

[自定义头添加-视频教程](https://player.bilibili.com/player.html?aid=498666070&bvid=BV1QK411n7VJ&cid=206827525&page=1)

# 下载可执行包

目前仅编译了Windows 和 Mac 版本。

## [推荐] 蓝奏下载
## [Windows 安装包](https://tools.heisir.cn/HLSDownload/download.html?platform=win)  |  [Windows 绿色版](https://tools.heisir.cn/HLSDownload/download.html?platform=win-zip)  |  [下载 MacOS 版](https://tools.heisir.cn/HLSDownload/download.html?platform=mac)

## [备份] coding.net 下载
## [Windows 安装包](https://heisir-01.coding.net/api/share/download/f0ce6bff-62f7-4ac4-884b-14624ce5384c)  |  [Windows 绿色版](https://heisir-01.coding.net/api/share/download/ae0d3071-188e-4eee-873f-3a200ca7004c)  |  [MacOS 安装包](https://heisir-01.coding.net/api/share/download/684b56a8-5462-4c8f-9a72-3cf99545b916)

# 运行源码
### NodeJS开发环境搭建

安装NodeJs最新版，[NodeJs Download](http://nodejs.cn/download/)

### Clone 代码

在任意文件夹下新建一个文件夹存放代码，并执行以下命令
```
cd newdir

git clone https://github.com/HeiSir2014/M3U8-Downloader.git .
```
### Yarn 环境安装

```
npm install yarn -g
```

### Package 依赖安装

```
yarn
```
### 运行M3U8-Downloader

```
yarn start
```
### 打包发布

```
//windows 平台打包
yarn pack-win

//mac 平台打包
yarn pack-mac

```

### Enjoy it

### 赞赏

[赞赏链接](https://tools.heisir.cn/HLSDownload/2019/07/08/02/)
