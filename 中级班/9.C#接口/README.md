# 9.C#接口

## 教材

- 讲解《Learning hard C#学习笔记 (图灵原创)》第6章《电脑有USB接口，C#也有接口》


## 教学

9.1.什么是接口

- 接口是对一组方法的声明。并且对这些方法进行统一命名和管理，但是没有提供任何功能实现。也就是说，把一组方法声明在一个接口中，然后继承于该接口的类都需要实现这些方法
- 接口支持多重继承


9.2.接口的使用

- 用interface关键字定义接口
- 接口不能添加任何访问修饰符
- 接口不能包含字段
- 用冒号“:”继承


9.3.隐式接口与显式接口


    //中国人打招呼接口
    interface IChineseGreeting
    {
        void SayHello();
    }

    //美国人打招呼接口
    interface IAmericanGreeting
    {
        void SayHello();
    }

    //显示的接口实现
    void IChineseGreeting.SayHello()
    {
        Console.WriteLine("吃了吗？");
    }

    void IAmericanGreeting.SayHello()
    {
        Console.WriteLine("what's up?");
    }


9.4.接口与抽象类

- 抽象类使用abstract关键字定义，接口使用interface关键字定义，它们都不能进行实例化
- 抽象类中可以包含静态成员，可以包含虚方法、非抽象方法
- 接口中只能定义方法
- 接口支持多继承，抽象类不支持多继承
- 抽象类和继承的类为属于的关系
- 用类来实现接口只是代表类具有接口声明的方法，是“我能做”的意思，例如IComparable和ICloneable等


## 作业

- 完成《Visual C#.NET程序设计教程(第2版)》第5章《面向对象的高级程序设计》的习题，做“1.判断题”、“2.选择题”，不做“上机实验”