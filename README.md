# Automatic_examination_system_Java
**Java面向对象程序设计大作业——小学生数学考试自动系统 （18华广）**

**小学生数学考试自动系统**

**JAVA + Swing**

*Java面向对象程序设计大作业
之
小学生数学考试自动系统*

## **开发环境与平台测试：**

使用JDK11.0.2，初代开发环境为Eclipse，完成GUI部分开发后迁移至IDEA
Eclipse中采用了WindowBuilder插件进行GUI开发

在windows10与macos环境下测试无异常



## **以下为项目要求：**

1）开始界面上需要填写姓名、专业、和班级信息；  
2）点击开始考试按钮后，自动生成50道数学题，计时开始；  
3）考试计时功能，在界面上显示考试花费时间，90分钟后自动交卷；  
4）交卷功能按钮：点击该按钮提前交卷或90分钟时间后自动交卷，均弹出对话框，并显示统计后的考试得分；  
5）试卷显示部分采用卡式布局管理器（CardLayout），每页显示5道题，共25页，通过“首页”、“上一页”、“下一页”和“尾页”四个按钮控制翻页功能，其他功能部分可自行合理布局；  
6）每道题100以内的整数随机生成，加法和减法也是随机，但3个数的混合运算结果不能为负数；  
7）考试的成绩累加写入“成绩.txt”文件，格式为“姓名  年级  班级  成绩”，如：“张三 **年级 *班 98”。  
8）增加考试平均分按钮，实现对进行过考试的人员平均分统计，即对文件“成绩.txt”进行平均分统计。  

**以上功能全部实现**

## 程序流程图：
位于仓库流程图文件夹下


## 如何运行程序？
入口位于src/ExamSystem/Main.java文件中

## 如何进入管理员界面查看平均分？
管理员登陆账号：  
姓名： 张三     
年级： 教务处     
班级： 123456     

## 寄语
开源此程序是希望广大学弟学妹能找到作为参照的灯塔，而不是复制粘贴后随便改改变量名糊弄过去。
（话说应该也只有华广的学弟学妹才会搜到这题了吧）

这个题目应该是从18级开始自创的，因为当时我也试图在网上搜寻资料，无果XD

所以，大家可以尽情参考我的代码，然后去改进它。
此代码中有许多小细节，本人在写的过程中没有刻意去完善，不保证程序会在某种玄学使用下出现BUG。

代码质量低，还请来围观的大佬嘴下留情。
就这样。

参考资料：
Java实现小学四则运算练习系统（UI）https://www.cnblogs.com/dwxuan/p/8711505.html
