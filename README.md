# GAS -- GenshinArtScanner

[简体中文](./README.md) | [English](./README_en.md)

## Deprecated
> 这个仓库已过时废弃，该项目已永久移至 [daydreaming666/Amenoma](https://github.com/daydreaming666/Amenoma).

扫描背包中的圣遗物，并导出至 json 格式。之后可导入圣遗物分析工具( [莫娜占卜铺](https://www.mona-uranai.com) 、 [MingyuLab](https://genshin.mingyulab.com) 、 [Genshin Optimizer](https://frzyc.github.io/genshin-optimizer ) 进行计算与规划等。

- 已支持 原神2.0 的圣遗物!


## 下载

有多个版本可供下载：

- ArtScannerUI.exe
  带界面的单文件版本，启动时间略长。(推荐)

- ArtScannerUI.zip
  带界面的多文件版本，解压后使用，启动时间较短。缺点是解压后占用空间较大。

- ArtScannerCLI.exe
  使用命令行的单文件版本。

> 使用中文界面时，请确保下载不带有后缀 *_EN* 的版本。不同语言的版本不能通用。

## 用法

1. 双击 ArtScanner.exe 打开程序，等待一会儿代码的解压
2. 将原神调整分辨率为 1600 * 900，打开背包 - 圣遗物
3. 捕获窗口并等待
4. 调整扫描选项
5. 开始扫描
6. 扫描结果存储在运行文件夹 *artifacts.genshinart.json*(莫娜占卜铺 / Genshin Optimizer) / *artifacts.mingyulab.json*(MingyuLab)

> [其他问题](#Q&A)


## 开发环境搭建

> 普通用户请跳过这一节

```cmd
conda env create -f ./ArtScanner/Tools/model_trainer/dev_env.yml
```

## 版权说明

### 开源协议

[APACHE LICENSE, VERSION 2.0](http://www.apache.org/licenses/LICENSE-2.0.html)

### 声明

您下载或使用本软件，视为您知悉并同意以下内容：

- 本软件为离线软件，无需网络环境，不会上传任何信息。
- 本软件需要操控鼠标对自动对背包中的圣遗物进行点击，并对窗口进行截图。
- 本项目仅为个人爱好，与 miHoYo 公司无任何关系
- 本软件为开源软件，不对您因使用本软件而造成的任何损失负责。


## 鸣谢

- [ProblemFactory/GenshinArtScanner](https://github.com/ProblemFactory/GenshinArtScanner)
的项目

- [honeyhunterworld](https://genshin.honeyhunterworld.com/) 的数据支持
- 各位测试与使用者的支持


## Q&A

暂时还没写 QwQ

> 如果遇到问题或任何建议，请提交 issues 或邮件至 [daydreaming@foxmail.com](mailto://daydreaming@foxmail.com)


## 捐赠

感谢支持。

<img src="https://daydreaming.top/wp-content/uploads/2021/08/QQ图片20210822004740.jpg" width="270" height="420" alt="Alipay"/>

<img src="https://daydreaming.top/wp-content/uploads/2021/08/QQ图片20210822004735.png" width="306" height="420" alt="Wechat"/>

[PayPal@daydreaming666](https://www.paypal.me/daydreaming666)
