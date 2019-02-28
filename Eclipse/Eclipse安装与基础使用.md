## Eclipse安装

###一、定位

基于Java的可拓展开发平台，附带了标准的插件集何开发工具JDK

###二、安装

本人安装的是打包起来的压缩文件版本，直接解压缩可使用。（资源放在文末）

1.下载压缩文件

2.解压缩文件到D盘

3.打开D盘文件夹“eclipse”

![1551180132581](C:\Users\13628\AppData\Local\Temp\1551180132581.png)

4.打开eclipse.exe文件

![1551180185869](C:\Users\13628\AppData\Local\Temp\1551180185869.png)

5.如果电脑的路径是正确的那么就已经能够使用了，打开的界面如下

![1551180285886](C:\Users\13628\AppData\Local\Temp\1551180285886.png)

- **极大可能遇到的问题：启动报错，环境变量出现问题**

![报错图](C:\Users\13628\Desktop\报错图.png)

（图源：https://www.cnblogs.com/wkrbky/p/6070175.html）

- **解决方法**

  （1）右键“我的电脑”，点击属性

![1551180593042](C:\Users\13628\AppData\Local\Temp\1551180593042.png)

​	（2）点击“高级系统设置”

![1551180637921](C:\Users\13628\AppData\Local\Temp\1551180637921.png)

​	（3）点击“环境变量”

![1551180755048](C:\Users\13628\AppData\Local\Temp\1551180755048.png)

PS：如果实在找不到，可以在搜索框中输入“编辑系统环境变量”，会弹出如下图，点击即可

![搜索框](C:\Users\13628\Desktop\Eclipse\搜索框.png)

（4）设置环境变量如下：

|  变量名   |                       变量值                       |
| :-------: | :------------------------------------------------: |
| JAVA_HOME |         C:\Program Files\Java\jdk1.8.0_181         |
| CLASSPATH | .;%JAVA_HOME%\lib\dt.jar;%JAVA_HOME%\lib\tools.jar |
|   Path    |       .;%JAVA_HOME%\bin;%JAVA_HOME%\jre\bin        |

**注意：JAVA_HOME为你下载的JDK的根目录，且下载的JDK版本应该为高于1.8及以上**

（JDK下载链接：https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html）

选择自己的电脑型号和jkd-8u***的即可，一般是jdk-8u201-windows-x64.exe

 	