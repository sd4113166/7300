# 8.数据库操作

## 教材

- 讲解W3School的SQL教程，[点击此处访问](http://www.w3school.com.cn/sql/index.asp)
- 讲解《Visual C#.NET程序设计教程(第2版)》第11章《C#数据库编程技术》


## 教学

8.1.什么是数据库

- 关系型数据库
    + RDMS（Relational Database Management System），关系型数据库是由多张能互相联接的二维行列表格组成的数据库
    + 常见：Oracle、DB2、PostgreSQL、Microsoft SQL Server、Microsoft Access、MySQL

- 非关系型数据库
    + NoSQL（Not Only SQL），意即“不仅仅是SQL”
    + 常见：MongoDB、CouchDB、Redis、Memcache、HBase、DynamoDB


8.2.使用Microsoft SQL Server数据库

- 创建数据库
- 创建表
- 备份/还原数据库
- SQL语言
    + SQL(Structured Query Language)语言SQL语言是1974年由Boyce和Chamberlin提出的一种介于关系代数与关系演算之间的结构化查询语言，是一个通用的、功能极强的关系型数据库语言
    + SQL基础教程（SELECT、DISTINCT、WHERE、AND & OR、ORDER BY、INSERT、UPDATE、DELETE）
    + SQL高级教程（TOP、LIKE、JOIN、INNER JOIN、LEFT JOIN、RIGHT JOIN等）（注：请先学习完8.3和8.4后，再学习此部分）
    + SQL函数（AVG、COUNT、MIN、MAX、SUM、GROUP BY等）


8.3.使用ADO.NET操作Microsoft SQL Server数据库

- SqlConnection
- SqlCommand（ExecuteNonQuery、ExecuteReader、ExecuteScalar）
- SqlDataReader
- SqlDataAdapter
- DataSet


8.4.DataGridView控件

- DataGridView.DataSource
- DataGridView.DataMember


## 常见问题

- SQL语句中，如果使用user等数据库保留的关键字，需要用中括号[ ]来访问，例如SELECT * FROM [user]

- 主键，外键和索引的区别
    + 定义：
        + 主键：唯一标识一条记录，不能有重复的，不允许为空。
        + 外键：表的外键是另一表的主键, 外键可以有重复的, 可以是空值。
        + 索引：该字段没有重复值，但可以有一个空值

    + 作用：
        + 主键：用来保证数据完整性
        + 外键：用来和其他表建立联系用的
        + 索引：是提高查询排序的速度

    + 数量：
        + 主键：主键只能有一个
        + 外键：一个表可以有多个外键
        + 索引：一个表可以有多个唯一索引


## 作业

- 完成W3School的SQL测验，[点击此处访问](http://www.w3school.com.cn/sql/sql_quiz.asp)
- 完成《Visual C#.NET程序设计教程(第2版)》第11章《C#数据库编程技术》的习题，做“1.选择题”、“2.判断题”，不做“上机实验”