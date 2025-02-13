<p align="center">
<img src="/SRC/Waifu2x-Extension-QT/icon/icon_main.png" height="150">
</p>

<h2 align="center"> Waifu2x-Extension-GUI </h2>

<h3 align="center"> 使用机器学习放大 图片/视频/GIF </h3>

<p align="center">
<img src="https://img.shields.io/github/v/release/aaronfeng753/waifu2x-extension-gui?label=Latest%20stable%20release&style=flat-square&color=brightgreen">
<img src="https://img.shields.io/badge/Support-Windows%20x64-blue?logo=Windows&style=flat-square">
<img src="https://img.shields.io/github/license/aaronfeng753/waifu2x-extension-gui?style=flat-square&label=License">
</p>

### [📜English README](https://github.com/AaronFeng753/Waifu2x-Extension-GUI/blob/master/README.md)

#### 如果README内的图片无法正常加载,请[点击本链接查看码云内存储的README](https://gitee.com/aaronfeng0711/Waifu2x-Extension-GUI/blob/master/README_CN.md)或者[使用邮电部国家公用电信网提供的国际出入口信道进行国际联网](http://www.cac.gov.cn/1996-02/02/c_126468621.htm)后刷新页面.

# [💾下载最新稳定版本 (Windows x64)](https://github.com/AaronFeng753/Waifu2x-Extension-GUI/releases/latest)
下载最新版本的绿色版安装包, 适用于拥有`Intel/AMD/Nvidia`显卡的`Windows 64位`系统个人电脑.

下载最新版: https://github.com/AaronFeng753/Waifu2x-Extension-GUI/releases/latest

#### [📖点击阅读 使用说明 Wiki](https://github.com/AaronFeng753/Waifu2x-Extension-GUI/wiki/%E4%B8%AD%E6%96%87%E7%9B%AE%E5%BD%95)---[📝点击查看完整更新日志](https://github.com/AaronFeng753/Waifu2x-Extension-GUI/blob/master/Change_log_CN.md)

支持的语言: English, 简体中文, 日本語(機械翻訳), 繁體中文.

[➡点击访问Gitee(码云,中国大陆)的Releases下载页面](https://gitee.com/aaronfeng0711/Waifu2x-Extension-GUI/releases)

# [🌟下载测试版本 (Windows x64)](https://github.com/AaronFeng753/Waifu2x-Extension-GUI/releases)
测试版与稳定版相比拥有更快的更新周期,可以让您提前体验到本软件最新的特性.

⚠请注意,测试版与稳定版相比更不稳定,因为测试版在发布前未经完整测试.

前往Releases页面下载测试版: https://github.com/AaronFeng753/Waifu2x-Extension-GUI/releases

[➡点击访问Gitee(码云,中国大陆)的Releases下载页面](https://gitee.com/aaronfeng0711/Waifu2x-Extension-GUI/releases)

# Waifu2x-Extension-GUI是什么?

### 借助深度卷积神经网络对`图片` & `GIF` & `视频`进行超分辨率放大(即放大与降噪).

### ✨主要特性:
- #### 📺自动化处理多种媒体: 支持处理 图片 的同时,实现了自动化处理 GIF 和 视频.
- #### 😍全图像风格支持: 内置多种算法, 无论是 二次元动漫 还是 您日常拍摄的照片&录像 ,都可以进行清晰化处理.
- #### ✅强大的兼容性: 内置多个引擎, 几乎与所有现代 Windows PC 兼容.
- 📊灵活的多线程设定: 在为每个引擎提供完备的设置项的同时,您也可以自由调整线程数量,充分利用PC的一切性能.
- 🚀🚀🚀多GPU支持: 内置的所有引擎均可支持多显卡,充分利用您的PC的所有性能.
- 🛠众多自定义设置: 您可以通过调整软件内的众多自定义设置实现自动化的工作流.
- 🤖智能设定: 本软件可根据您的PC硬件信息和您要处理文件的信息自动调整部分软件设定.
- 😉易于使用的图形用户界面.
- 📨持续的维护与更新.

```
内置图像处理算法:
Waifu2x / SRMD / RealSR / Anime4K / ACNet

内置图像处理引擎:
Waifu2x-caffe / Waifu2x-converter / Waifu2x-ncnn-vulkan / SRMD-ncnn-vulkan / RealSR-ncnn-vulkan / Anime4KCPP
```

#### ✅已经在 `AMD` RX 550, `NVIDIA` GeForce GTX 1070 和 `Intel` UHD 620 上通过测试.

![mainwindow](/Screenshot/mainwindow_cn.jpg)

![Engine_Settings](/Screenshot/Engine_Settings_CN.jpg)

![Additional_Settings](/Screenshot/Additional_Settings_CN.jpg)

# 示例👀

### **`图片`** : https://github.com/AaronFeng753/Waifu2x-Extension-GUI/tree/master/Samples/image

### **`视频`** : https://github.com/AaronFeng753/Waifu2x-Extension-GUI/tree/master/Samples/video

### **`GIF`** : https://github.com/AaronFeng753/Waifu2x-Extension-GUI/tree/master/Samples/gif

### [➡对比(3D写实)(使用内置的RealSR-NCNN-Vulkan引擎)](https://imgsli.com/MzYzMTQ)
#### 原照片来自Unsplash,由Jonatan Pie拍摄.
![Comparison](/Samples/image/Comparison_3D_Real-life.png)

### [➡对比(2D动漫)(使用内置的Waifu2x-NCNN-Vulkan引擎)](https://imgsli.com/MzYzMTY)
![Comparison](/Samples/image/Comparison.png)

#### 原图 2D动漫图片 480x300 (.jpg 93.2 KB):
![Original Imgae](/Samples/image/Original_[480x300].jpg)

#### 经过8x放大, 3级降噪和压缩后 3840x2400 (.jpg 525 KB):
#### (使用内置的Waifu2x-NCNN-Vulkan引擎)
![Scaled Imgae](/Samples/image/Waifu2x_8x_[3840x2400].jpg)

#### 原图 GIF 500 x 372 (493 KB):
![Original GIF](/Samples/gif/2_original.gif)

#### 经过2x放大,2级降噪和gif优化后 1000 x 744 (3.77 MB):
#### (使用内置的Waifu2x-NCNN-Vulkan引擎)
![Original GIF](/Samples/gif/2_waifu2x_compressed.gif)

### `github不支持在线播放视频, 请点击下方链接查看视频示例:`
### **`视频`** : https://github.com/AaronFeng753/Waifu2x-Extension-GUI/tree/master/Samples/video

# ❤ 捐赠 ❤ (推荐使用 支付宝 或者 微信)
# [PayPal](https://www.paypal.me/aaronfeng753)
### 除了扫码捐赠现金, 您也可以每天打开支付宝首页搜“682796694”领红包并使用, 我也可以获得收入.
![donate_new](/donate_new.jpg)
#### 如果捐赠二维码图片无法正常加载,请[打开此链接查看](https://gitee.com/aaronfeng0711/Waifu2x-Extension-GUI/raw/master/donate_new.jpg)或者[使用邮电部国家公用电信网提供的国际出入口信道进行国际联网](http://www.cac.gov.cn/1996-02/02/c_126468621.htm)后刷新页面.

# [📄许可协议](https://github.com/AaronFeng753/Waifu2x-Extension-GUI/blob/master/LICENSE)

Waifu2x-Extension-GUI遵循[🔗GNU Affero General Public License v3.0](https://www.gnu.org/licenses/agpl-3.0.en.html)许可协议.

<p align="left">
<img src="/.github/AGPLv3_Logo.png" height="120">
</p>

# 隐私政策🙈🙉🙊

我们尊重您的隐私,所以本软件的隐私政策如下:
```
1. 本软件不会向互联网上传任何数据, 所以我们不会收集您的任何信息, 我们甚至没有服务器.

2. 本软件仅在检查更新与更新捐赠页的二维码时会连接互联网, 此时将从Github和码云下载两个.ini文件和两个.jpg文件.
(码云是一个类似Github的网站, 由中华人民共和国政府监管, 您可以在附加设置内启用[禁止连接码云]以禁止本软件从码云下载数据.)

总之, 我们不会收集您的任何信息. 如果您不信任我们, 您可以自行阅读本软件的源代码或者停止使用本软件.
```

# 💝鸣谢💝:
- ❤捐赠者们❤
- Anime4K: https://github.com/bloc97/Anime4K
- Anime4KCPP: https://github.com/TianZerL/Anime4KCPP
- Beautiful Soup: https://www.crummy.com/software/BeautifulSoup/
- FFmpeg: https://ffmpeg.org/
- FFmpeg Builds - gyan.dev: https://www.gyan.dev/ffmpeg/builds/
- FFmpeg Builds - Zeranoe(该网站已停止运营): https://ffmpeg.zeranoe.com/builds/
- Ghostscript: https://www.ghostscript.com/index.html
- Gifsicle: https://www.lcdf.org/gifsicle/
- ImageMagick: http://www.imagemagick.org/
- NCNN: https://github.com/Tencent/ncnn
- NirCmd: https://www.nirsoft.net/utils/nircmd.html
- NSIS: https://nsis.sourceforge.io/
- OpenCV: https://opencv.org/
- Pillow: https://python-pillow.org/
- PyInstaller: https://github.com/pyinstaller/pyinstaller
- Python: https://www.python.org/
- QT: https://www.qt.io/
- RealSR-ncnn-vulkan: https://github.com/nihui/realsr-ncnn-vulkan
- Real-World Super-Resolution: https://github.com/jixiaozhong/RealSR
- SoX: http://sox.sourceforge.net/
- SRMD: https://github.com/cszn/SRMD
- SRMD-ncnn-Vulkan: https://github.com/nihui/srmd-ncnn-vulkan
- Waifu2x: https://github.com/nagadomi/waifu2x
- Waifu2x-caffe: https://github.com/lltcggie/waifu2x-caffe
- Waifu2x-converter: https://github.com/DeadSix27/waifu2x-converter-cpp
- Waifu2x-Extension: https://github.com/AaronFeng753/Waifu2x-Extension
- Waifu2x-ncnn-vulkan: https://github.com/nihui/waifu2x-ncnn-vulkan
- 图标作者: [Freepik](https://www.flaticon.com/authors/freepik) & [Roundicons](https://www.flaticon.com/authors/roundicons) & [Icongeek26](https://www.flaticon.com/authors/Icongeek26) 来自 Flaticon : https://www.flaticon.com/
- 感謝 [@uimee](https://github.com/AaronFeng753/Waifu2x-Extension-GUI/issues/85) 協助進行繁體中文翻譯.
- 感谢 [@Nova-Aurora](https://github.com/Nova-Aurora) 协助修复英文版README中的语法和拼写错误.
- 感谢 [@CAFUCSteven](https://github.com/CAFUCSteven) 协助测试软件.
- 感谢 [@Michael18751](https://github.com/Michael18751) 为提示音添加了淡出效果.
- 感谢 [@CaptainStabs](https://github.com/CaptainStabs) 协助修复多个英语语法错误.
