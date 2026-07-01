Python入门笔记

一、Python基础介绍

Python是一门解释型、面向对象的高级编程语言，语法简洁易读，广泛应用于数据分析、人工智能、Web开发、自动化运维等场景。
Python拥有丰富的第三方库，生态完善，零基础入门门槛较低。

二、环境搭建

1. 前往Python官网下载对应系统的安装包，安装时勾选Add Python to PATH，完成环境变量配置。

2. 运行校验：打开命令提示符，输入python --version，出现版本号即安装成功。

3. 开发工具：可以使用IDLE、VS Code、PyCharm完成代码编写。

三、基础语法

1. 输出语句

Python使用print()函数完成控制台输出：

print("Hello Python")

2. 变量与数据类型

变量不需要提前声明类型，赋值即可创建：

name = "小明"

age = 18

score = 92.5

is_student = True

基础数据类型：

• 字符串 str：使用单引号/双引号包裹文本

• 整数 int：不带小数的数字

• 浮点数 float：带小数的数字

• 布尔值 bool：只有True和False两个取值

3. 输入函数

input()可以读取用户键盘输入：

username = input("请输入你的名字：")

print("你好，", username)

4. 注释

• 单行注释：#后面跟随注释内容

• 多行注释：三个单引号 ''' 或者三个双引号 """

四、程序结构

1. 分支语句 if

Python依靠缩进划分代码块：

score = 85

if score >= 60:

    print("考试及格")
    
else:

    print("考试不及格")
    
2. 循环语句

for循环

遍历0~9

for i in range(10):

    print(i)
    
while循环

i = 0

while i < 10:

    print(i)
    
    i = i + 1
五、函数基础

函数可以封装重复使用的代码：

def add(a, b):

    return a + b

result = add(3, 5)

print(result)

六、常见学习建议

1. 多动手敲写代码，不要只看代码；

2. 优先掌握基础语法，再去学习第三方库；

3. 完成小型实战项目，例如简易计算器、学生成绩统计，巩固知识点。
