# VirtualApkDemo
VirtualApk 插件化实现示例

demo运行命令
##### 构建host
```
  gradlew :app:assembleRelease
```
将构建出来的app-release.apk安装到手机

##### 构建插件
```
 gradlew clean assemblePlugin
```
将构建出来的plugin apk push到 /sdcard/目录  

 支持 9.0
 api  不能大于28.0.0  大于会报错

  注意需要添加权限   
 
请参考 https://github.com/didi/VirtualAPK/wiki