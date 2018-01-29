# 7.文件操作

## 教材
讲解《Learning hard C#学习笔记 (图灵原创)》第21章《出师前闯关训练第一关——文件操作》

## 教学

注：需要使用“using System.IO;”引用IO命名空间

7.1.对文件进行增删改查操作

File类和FileInfo类

常用成员：

- AppendText
- Create
- Delete
- Exists
- Open
- OpenRead
- OpenWrite
- ReadAllText
- WriteAllText


7.2.对目录进行增删改查操作

Directory类和DirectoryInfo类

常用成员：

- CreateDirectory
- Delete
- Exists
- GetFiles
- GetParent
- GetCurrentDirectory
- Move


7.3.数据流

Stream类、NetworkStream类、FileStream类、MemoryStream类和GZipStream类

常用成员：

- CanRead
- CanSeek
- CanWrite
- Length
- Position
- BeginRead
- BeginWrite
- Close
- EndRead
- EndWrite
- Flush
- Write


常用读写器

- 文本读写器
    + TextReader类
    + TextWrite类
- 字符串读写器
    + StringReader类
    + StringWriter类
- 二进制读写器
    + BinaryReader类
    + BinaryWriter类
- 流读写器
    + StreamReader类
    + StreamWriter类

7.4.对文件进行异步操作

BeginRead和BeginWrite方法


## 作业
- 复习本章内容，能够闭卷对“文件”和“目录”进行“增删改查”操作
- 自学《Visual C#.NET程序设计教程(第2版)》第12章《文件操作与编程》的“12.3 XML 文档编程”
- 完成《Visual C#.NET程序设计教程(第2版)》第12章《文件操作与编程》的习题，做“1.选择题”、“2.判断题”，不做“上机实验”