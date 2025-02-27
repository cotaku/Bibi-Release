# Bibi-Release
这里是某个B开头的UWP app的appx分发中心，其本体已经由于大人的原因无法继续在微软商店中公开发布了。

(This is the distribution hub for a UWP app whose name starts with a "B". The main app can no longer be publicly released on the Microsoft Store due to reasons beyond my control.)

最低系统版本要求为16299（ARM版为15063）。

# 安装方法

## 从商店安装

https://www.microsoft.com/store/apps/9NJJ5RRCZSV2

## 从appx安装

1、从Releases中下载对应平台的appx。

2、下载Atelier39.cer，打开并安装证书（本地计算机->证书存储->选择“受信任人”("Trusted People")）。

3、运行appx并安装。

4、如果提示缺少系统组件，可在Dependency目录下的寻找对应平台的相关组件手动安装。

# 其他说明

- 由于在本机编译ARM64版的时候.NET Native tool-chain持续出错，在解决之前无法上传appx（可在商店中下载）。

- app的更新均在Releases中发布，也可在此下载历史版本appx。

- 其他相关问题、反馈以及建议都欢迎在Issues中提出（常见使用问题请参考app主页中内置的帮助页面）。

- 本应用允许本地修改及二次分发，但是禁止用于商业用途。

- app中使用的一些组件可能会陆续开源，但是整体工程代码没有开源计划（主要是因为写得太烂了（逃
