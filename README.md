 java-cangku
Java 课程作业项目仓库

# 阅读程序
## 实验目的
用类描述计算机中CPU的速度和硬盘的容量。
## 实验过程
1、参考JAVA2实验教程一书P110第4道编程题中提供的参考例子及要求。
2、熟知是严重的相关关系及基本定义如：
（1）类：一个模板用来定义以，欸事物的状态和行为。（抽象的复合数据类型）
创建一个类就是一个新的数据类型；类的构成：成员变量（基本类型或数组）和成员方法（用户与对象之间的接口）
（2）关系：抽象和具体的关系，类是创建对象的模板，对象是类的具体实例；类是总称，，对象是个体。
3、了解清相关定义便可以使用eclipse软件进行编程，基本按照建立Package，再在包里新建Class（CPU、pc、Test、Hardisk）的过程便开始编写程序代码。
要求：将Teat作为主类，在main方法中创建一个CPU对象cpu，cpu将自己的speed设置为2200；
      main方法中创建一个HardDisk对象disk，disk将自己的amount设置为200；
      main方法中创建一个PC对象pc；
      pc调用setharddisk方法，调用时实参是disk；
      pc调用show()方法。
      
## 核心方法
1.方法1：构造方法：是类中的一种特殊方法，当程序用类创建对象时需使用它的构造方法。类中的构造方法的名字
必须与它所在的类的名字完全相同，而且没有类型。
2.方法2：创建一个对象包括对象的声明和为对象分配变量两个步骤。
3.方法3：为对象分配变量：使用new运算符和类的构造方法为声明的对象分配变量，即创建对象。
        如果类中没有构造方法，系统会调用默认的构造方法。（默认的构造方法是无参数的，且方法体中没有语句。）
## 实验结果
   硬盘容量：200；
   cpu速度：2200。
##实验感想
  通过本次实验对eclipes软件运用更加熟悉，在编程代码时有了更加清晰的思路，
对构造方法创建对象及分配的运用也更加熟练了。
