# UML逻辑视图-包图详解



**包**是一个**容器**，提供对UML**元素进行分组**的功能，主要表现在：把一个**大的系统**分解为多个**小的系统**，分解是控制软件复杂性的重要手段；结构化方法中，对**功能**进行**分解**；面向对象方法中，讲**相关类放在一起** 



## 包管理类

![1571334147856](C:\Users\JunSIr\AppData\Roaming\Typora\typora-user-images\1571334147856.png)



依次创建，在**Logical View/ Main**中，将包拖入

（显示包中类：右键包--->**select compatment items**--->选择你想要展示的类--->ok）

## 确定包的关系

按照三层模式，关系如下

![1571334605924](C:\Users\JunSIr\AppData\Roaming\Typora\typora-user-images\1571334605924.png)





## 生成Java代码

### 建立类图关系

Logical View/ Main---->**new ClassDiograrm**



建立关系{

![1571335234980](C:\Users\JunSIr\AppData\Roaming\Typora\typora-user-images\1571335234980.png)



}



### 生成框架代码

1. 首先要在**Tools**-->**Java/J2EE**-->**Project Specification**里面的**classpaths**里面加入你要生成的代码的目的路径。

1. 选择**Tools**-->**Java/J2EE**-->**Generate Code**，将目的路径assign给你要生成代码的包/类 