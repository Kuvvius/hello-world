## Eclipse使用入门

### 三、基础使用

写在最前：如果各位同我一样是使用该工具的新手的话，最最开始的一步是最好耐性的准备和不要恐惧全英文，知道慢慢适应的过程中会有些许烦躁是正常的。

#### 1.Help菜单的使用![无标题](C:\Users\13628\Desktop\Eclipse\无标题.png)

- Help Contents：内容十分丰富，但是初级入门还不会要用到
- Search：使用自然语言输入expression即可搜索到语法使用知识等
- Show Contextual Help：上下文帮助
- Show Active Keybindings：现实所有存在的快捷键
- Tip of the Day：里面有动态化的使用tips的展示
- Tips and Tricks：查看现存的tips，点击可以转载到相应的help content
- Report Bug or Enhancement：向开发者报告错误
- Cheat Sheets:备忘录
- Eclipse User Storage：用户存储
-  Perform Setup Tasks
- Check for Updates
- Install New Software
- Eclipse Marketplace
- About Eclipse IDE：
- Contribute：

#### 2.File菜单的使用

![File2](C:\Users\13628\Desktop\Eclipse\File2.png)

- New：新建
  - Maven Project：相门
  - Enterprise Application Project：企业应用工程
  - Dynamic Web Project 

### 3.工程建立

1）在左方的project视图右键，菜单中选择“Project”可以马上建立新的工程

![工程右键](C:\Users\13628\Desktop\Eclipse\工程右键.png)

2）选择第一个Java project， 键入project name![newproject](C:\Users\13628\Desktop\Eclipse\newproject.png)

注意：Location是安装Eclipse的时候自己创建的workspace的路径，而每一个project就是其中的一个文件夹，JDK为配置环境变量的时候的%JAVA_HOME%，显示为1.8以上的版本才是有效的

![1551253128254](C:\Users\13628\Desktop\Eclipse\1551253128254.png)

建立完成后看到了自己的项目“MyFirstProject"和自带的环境的库如上图

3）尝试最简单的代码编写，对准自己新建的源文件夹，右键，选择New>Source Folder

![new source folder](C:\Users\13628\Desktop\Eclipse\new source folder.png)

注意：Source Folder vs Folder，SF中的源文件会自己帮我们编译，Folder中一般防止不需要编译的文件

4）尝试建立一个类 New>Class

![1551253879596](C:\Users\13628\Desktop\Eclipse\1551253879596.png)

- Source Folder：选择放置的源文件夹

- Package：选择防止的包

- Name：类名

- MODIFIERS：该类的修饰符

- Superclass：父类

- Interfaces：接口

- 主函数，构造函数，所继承的抽象方法是否需要出现，如果要的话打勾。

  （这样可以节省编程时间，快速实现函数的集成和接口的使用）

四个全都勾选之后会自动出来如下代码

![1551254248190](C:\Users\13628\Desktop\Eclipse\1551254248190.png)



































