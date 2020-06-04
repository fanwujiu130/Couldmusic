# Unlock-netease-cloud-music

解锁网易云音乐客户端变灰歌曲

## 项目介绍

网易音乐相信不需要我过多的介绍大家也都知道，由于各种限制，相信很多人在听歌的时候也注意到了，很多的音乐呈现灰色的样式，是无法播放的，如下图所示。今天就带大家**把灰色不能听的音乐全部变成可以正常播放的音乐**，而且是**全平台通用**哦！

![3utjKK.png](https://s2.ax1x.com/2020/02/21/3utjKK.png)

## 特性

- 使用 QQ / 虾米 / 百度 / 酷狗 / 酷我 / 咪咕 / JOOX 音源替换变灰歌曲链接 (默认仅启用一、五、六)
- 为请求增加 `X-Real-IP` 参数解锁海外限制，支持指定网易云服务器 IP，支持设置上游 HTTP / HTTPS 代理
- 完整的流量代理功能 (HTTP / HTTPS)，可直接作为系统代理 (同时支持 PAC)

## <span style="color:orangered;font-weight:bold;">Windows端方法一：</span>

1.打开网易云音乐客户端，进入设置页面，设置自定义代理

- 自定义代理 ：填写服务器地址和端口号

- 代理服务器地址：127.0.0.1 （推荐本机搭建，速度快）

- 代理服务器端口：52000

  ![3uthuT.png](https://s2.ax1x.com/2020/02/21/3uthuT.png)

**2.安装node.js**

官方网站：[http://nodejs.cn/download/](http://nodejs.cn/download/)

下载后双击软件安装包打开安装，一直点下一步直到完成即可

![3ut5bF.png](https://s2.ax1x.com/2020/02/21/3ut5bF.png)

3.**下载项目源码**

**[https://github.com/meng-chuan/Unlock-netease-cloud-music/archive/master.zip](https://github.com/meng-chuan/Unlock-netease-cloud-music/archive/master.zip)**

下载后解压到任意文件夹,双击点开Unlock-netease-cloud-music文件夹中名为：网易☁🎵.bat 的文件

![3ut4DU.png](https://s2.ax1x.com/2020/02/21/3ut4DU.png)

注：此窗口不可关闭，可以最小化

以后每次打开网易云先运行网易☁🎵.bat这个文件即可解锁所有灰色歌曲，在这里先恭喜你成功学会了第一种解锁网易云音乐灰色歌曲的方法

# <span style="color:orangered;font-weight:bold;">Windows端方法二：</span>

注意：Windows 7 如无法执行则需升级 Powershell 到 3.0 以上，XP 不支持，**下载地址**：[https://docs.microsoft.com/powershell/scripting/install/installing-powershell](https://docs.microsoft.com/powershell/scripting/install/installing-powershell)

![GGWNse.png](https://s1.ax1x.com/2020/04/02/GGWNse.png)

**第一步，安装代理**

以 `管理员身份` 打开 `Powershell`，Windows 10 快捷入口：`Win + X` - `Windows Powershell(管理员)(A)`

[![GGhBgf.png](https://s1.ax1x.com/2020/04/02/GGhBgf.png)](https://imgchr.com/i/GGhBgf)

复制以下代码，右键粘贴到命令行回车，打开安装菜单。

```powershell
Set-ExecutionPolicy -ExecutionPolicy Unrestricted -Force
Invoke-Expression -Command (Invoke-WebRequest -UseBasicParsing -Uri https://bit.ly/2RYvE3p).Content
```

[![GGI1g0.png](https://s1.ax1x.com/2020/04/02/GGI1g0.png)](https://imgchr.com/i/GGI1g0)

- 随后选择 `1` 即安装。
- 安装完毕后选择 `3` 运行。
- 如需添加开机自启，则执行 `7`。
- 最后输入 `0` 退出。

[![GGTr7D.png](https://s1.ax1x.com/2020/04/02/GGTr7D.png)](https://imgchr.com/i/GGTr7D)

**第二步，设置代理**

打开网易云音乐客户端，进入设置页面，设置自定义代理

- 自定义代理 ：填写服务器地址和端口号

- 代理服务器地址：127.0.0.1 （推荐本机搭建，速度快）

- 代理服务器端口：6666

  ![GGLULq.png](https://s1.ax1x.com/2020/04/02/GGLULq.png)

  如使用一段时间后无法解锁，则需要重新执行命令，选择 `5` 更新。


## <span style="color:orangered;font-weight:bold;">Windows端方法三：</span>

优点：无需下载任何资源，只需几步设置即可，话不多说，直接上干活，我这里以win10为例，其他系统操作类似：

**第一步：鼠标左键点击桌面右下角的通知气泡**

![3utoE4.png](https://s2.ax1x.com/2020/02/21/3utoE4.png)

**第二步：然后鼠标左键点击所有设置**

![3utWvV.png](https://s2.ax1x.com/2020/02/21/3utWvV.png)

**第三步：鼠标左键点击点击进入网络和intrnet**

![3ut759.png](https://s2.ax1x.com/2020/02/21/3ut759.png)

**第四步，脚本地址**：[https://wy.ydlrqx.com/proxy.pac](https://wy.ydlrqx.com/proxy.pac ) 

**操作步骤请直接看下图，都是使用鼠标左键点击**

![3utbCR.png](https://s2.ax1x.com/2020/02/21/3utbCR.png)

**第五步，打开网易云音乐，进入设置，操作步骤见下图，都是使用鼠标左键点击**

![3utq81.png](https://s2.ax1x.com/2020/02/21/3utq81.png)

最终效果如下:

![3utOv6.png](https://s2.ax1x.com/2020/02/21/3utOv6.png)

# <span style="color:orangered;font-weight:bold;">macOS端</span>

由于本人家境贫寒，买不起苹果电脑，又不想用黑苹果，无法截图说明，所以这里直接文字描述

macOS端的使用与以上Windows端第三种方法同理，依次打开系统偏好`设置`＞`网络`＞`高级`＞`代理`，然后填入**地址**：[https://wy.ydlrqx.com/proxy.pac](https://wy.ydlrqx.com/proxy.pac)

# <span style="color:orangered;font-weight:bold;">Linux端</span>

会用Linux的都不应该是小白，所以这里就不截图了，直接上文字描述

Linux端的使用也同样与以上Windows端第三种方法和macOS端方法同理，依次进入系统`设置`＞`网络`＞`网络代理`，然后填入**地址**：[https://wy.ydlrqx.com/proxy.pac](https://wy.ydlrqx.com/proxy.pac)

#  <span style="color:orangered;font-weight:bold;">安卓端</span>

安卓手机型号太多，这里我使用小米6给大家演示，安卓端的使用必须要连接WiFi，否则无法使用，点击WIFi的详情，然后把代理选择为自动配置模式，同PC端一样，粘贴我提供的地址，记得保存！！！**地址**：[https://wy.ydlrqx.com/proxy.pac](https://wy.ydlrqx.com/proxy.pac) 

![3uUX7D.jpg](https://s2.ax1x.com/2020/02/21/3uUX7D.jpg)

接着再次打开网易云音乐大家就可以很清楚的看到如下图所示的效果，左侧是没有设置之前，很多音乐是灰色的无法试听和下载，右侧是设置后的，我们可以随意的试听和下载！

![3uULnK.jpg](https://s2.ax1x.com/2020/02/21/3uULnK.jpg)

# <span style="color:orangered;font-weight:bold;">iOS端</span>

由于本人家境贫寒，买不起iPhone，无法截图说明，所以这里直接文字描述

iOS端的使用也同样必须要连接WiFi，iOS 设备还需安装 CA 证书。首先点击**链接**：[https://raw.githubusercontent.com/nondanee/UnblockNeteaseMusic/master/ca.crt](https://raw.githubusercontent.com/nondanee/UnblockNeteaseMusic/master/ca.crt) 添加证书，随后在 `设置` > `通用` > `关于本机` > `证书信任设置` 下，手动开启证书，具体参考**Apple 官方说明**：[https://support.apple.com/zh-cn/HT204477](https://support.apple.com/zh-cn/HT204477) 。

安装后依次打开无线局域网＞HTTP代理＞配置代理，然后把代理选择为自动配置模式，同Android端一样，粘贴我提供的地址，记得点击右上角的存储！！！**地址**：[https://wy.ydlrqx.com/proxy.pac](https://wy.ydlrqx.com/proxy.pac) 

教程到此结束，喜欢我的作品请帮忙点个⭐，谢谢！！！

## 本教程仅用于学习交流，如有侵权请联系本人删除，禁止他人用于非法用途，转载请注明出处，谢谢！！！

**注：本人GitHub项目地址**：[https://github.com/meng-chuan/Unlock-netease-cloud-music](https://github.com/meng-chuan/Unlock-netease-cloud-music)