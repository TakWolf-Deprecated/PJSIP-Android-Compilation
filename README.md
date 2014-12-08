# PJSIP-Android平台编译后的Hello World #

官方示例中Android平台的两个Hello World编译后项目，整个过程坑爹一坨坨。

Android平台官方文档页为：

[http://trac.pjsip.org/repos/wiki/Getting-Started/Android](http://trac.pjsip.org/repos/wiki/Getting-Started/Android)

### 编译环境 ###

- Ubuntu-14.04.1-LTS-i386

- PJSIP-2.3

- ndk-r9d-linux-x86

### 经验和教训 ###

简而言之就是以下几句话：

- 别用Windows编译

- 别用Ubuntu 64位，使用32位，包括ndk

- 别用ndk版本号高于r10，使用r9以下版本

### 详细的说明 ###

参看：[http://blog.takwolf.com/2014/12/03/pjsip-android-compilation](http://blog.takwolf.com/2014/12/03/pjsip-android-compilation)

以上，祝你好运~
