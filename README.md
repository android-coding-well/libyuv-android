libyuv-android
==============

Build Google libyuv with NDK for Android
# Version
r1580

# Usage
* Step1 切换到mk文件所在目录
* Step2 执行“ndk-build -j8”(前提是已经配置好ndk环境变量)

> 等待一段时间后即可在libs文件夹中看到所需的so。另外，如果想自定义配置可在application.mk中修改
