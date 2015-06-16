本插件为hadoop2.x版本使用，编译步骤：
  
1、命令行下进入目录：src/contrib/eclipse-plugin

2、执行编译命令：ant jar -Dversion=2.6.0 -Declipse.home=D:\desktop\eclipse -Dhadoop.home=D:\desktop\hadoop-2.6.0

   其中Declipse.home为ecipse根目录，Dhadoop.home为hadoop根目录

3、等待编译成功，出现如下“BUILD SUCCESSFUL”提示文字，说明编译成功

   编译成功的jar包位于：build/contrib/eclipse-plugin/hadoop-eclipse-plugin-2.6.0.jar


更多参考：http://www.cnblogs.com/hanganglin/p/4581063.html