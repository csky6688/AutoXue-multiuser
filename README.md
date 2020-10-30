# 写在最前
这个项目完全是为了学习python，学习了原AutoXue的项目，项目地址 https://github.com/kessil/AutoXue
因为原作者没有更新，因此拿来作为研究学习之用，请遵守开源许可协议。严禁用于商业用途，禁止使用进行任何盈利活动。对一切非法使用所产生的后果，本人概不负责。
# 使用方法，一定要先读！！
1、安装雷电模拟器，默认设置即可。

2、安装安卓sdk，并配置环境变量。

3、用户名在default.ini里配置，可以配置多用户，也可以单用户。一定要配置！！

4、如果是新的模拟器第一次登录，必须提前登录用一次，把各种提示刷没了，否则app提示操作会导致程序崩溃；

5、解压缩后保持目录结构，系统采用相对目录，exe文件单独拉出来运行不了。

6、2.0版本没有开源，python编译后总是被360误杀，建议添加信任列表，目前看win10自带defender检测没问题。

7、运行xuexi文件夹中的exe。

## 关于开源
项目暂时不开源了，目前来看很多人拿去改完在这里bb炫耀，邀请他一起参与也不提供任何代码，只说自己优化的怎么怎么样；开源的目的是让大家一起参与提高项目质量，目前群内也有无私奉献的人，都一起提高优化，想一起参与项目的群内小范围共享代码；不愿意参与项目的只拿去可执行程序就可以了，这样也可以避免项目无限扩大导致项目被封。


## 免责申明
`AutoXue`为本人`Python`学习交流的开源非营利项目，仅作为`Python`学习交流之用，使用需严格遵守开源许可协议。严禁用于商业用途，禁止使用`AutoXue`进行任何盈利活动。对一切非法使用所产生的后果，本人概不负责。


0. 如果之前添加过环境变量`ADB1.0.40`请确保删除之

1. 安装`JDK`，本文使用JDK1.8
    + 在环境变量中新建`JAVA_HOME`变量，值为JDK安装路径，如`C:\Program Files\Java\jdk1.8.0_05`
    + 新建`CLASSPATH`变量，值为`.;%JAVA_HOME%\lib;%JAVA_HOME%\lib\tools.jar;`
    + `Path`变量中添加：`%JAVA_HOME%\bin和%JAVA_HOME%\jre\bin`
    
2. 安装`SDK`，本文使用SDK r24.4.1
    + 在环境变量中新建`ANDROID_HOME`，值为SDK安装路径，如`C:\Program Files (x86)\Android\android-sdk`
    + 在Path变量中添加项：`%ANDROID_HOME%\platform-tools` 和 `%ANDROID_HOME%\tools`
    + 打开`SDK Manager.exe` 安装对应的工具和包,根据安卓版本进行安装，**Tools**和**Build-tools**别漏
    ![avatar](https://github.com/kessil/AutoXue/raw/dev/image-20200601204634969.png)
    
   
4. 安装一个模拟器，建议选择雷电模拟器最新版本，如用其他模拟器或真机出现问题请自救。

5. 安装`Python`，请至少使用3.7+版本，推荐3.8



