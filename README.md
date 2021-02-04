# Unity-Android-Vuforia-UVCCamera

#### 介绍
<<<<<<< HEAD
unity平台下打包vuforia链接外置摄像头（通过开源的UVCCamera方式）

author chill 
date:2021.2.4

环境设置
Windows 10
Unity 2019.2.11f1  
unity-Vuforia 8.5.9

-----complie----
vuforia-sdk-android-9-6-3
vuforia-driver-sample-uvcdriver-android-9-6-3
vuforia-sample-android-9-6-3

---build tool---
Cmake 3.15.5
Python 3.8.6 （python版本对build有一定影响）
git 2.30  windows
ninja 1.9.0
ndk 13r
android sdk 22
编译完成的文件需要放到Unity中，设置如下
---unity projectsetting---
orientation : landspeace left
ratio mode  :1.86
graphics api :  opgl3
min target api: 24
target api :highest
scripting backend: IL2CPP
target architectures: armv7 arm64

.so文件和jar包位置
Assets/Plugins/Android/libs    (包含三个平台的文件，都保留即可)

UVCManager.cs   调取外部安卓摄像头
参考地址：
https://library.vuforia.com/articles/Solution/uvc-camera-driver.html
https://blog.csdn.net/zhangxiao13627093203/article/details/103834015
https://blog.csdn.net/zhangxiao13627093203/article/details/103937139#comments_14332732

