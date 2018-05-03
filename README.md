# 项目简介

这是我在课余时间基于SSH框架和Myeclipse编辑器设计的学生管理系统，希望能够帮助大家。

# 使用技术

Web框架：Struts2

ORM框架：Hibernate4.1

数据库：Mysql5.7

前端展示：Bootstrap，Jsp

# 项目相关

## 1.运行环境和所需工具

编译器：myeclipse

数据库：Mysql5.7

JDK版本：jdk1.8

Tomcat版本：Tomcat8.x

## 2.开始项目

1.在你的Mysql控制面板中，导入运行我提供的 student_manager.sql 文件

2.在 myeclipse 中添加 Hibernate 创建数据库链接，测试是否成功

3.使用 myeclipse 导入项目，进入 src/hibernate.cfg.xml 修改 JDBC 配置文件,选择刚刚创建出来的数据库链接，配置环境变量将 Web-INF/lib 中的包导入

4.配置我们的 Tomcat ，然后把项目添加到 Tomcat 中

5.运行，输入 http://localhost:8080/Student_Manager Tomcat配置其他端口，修改8080便可

 ![](https://github.com/1123GY/Student_Manager/blob/master/Image/首页.jpg)
 
 #数据库设计

 ## 1.数据库设计模型如下

 ![](https://github.com/1123GY/Student_Manager/blob/master/Student_Manager/sql/数据库设计模型.jpg)

 # 模块介绍
 
 ## 1.学生模块
 
学生注册+搜索课程+选修课程+退课+查看课表+查看成绩+修改个人信息

![](https://github.com/1123GY/Student_Manager/blob/master/Image/学生首页.jpg)

 ## 2.教师模块
 
教师注册+查看所教授课程+查看没课学生列表和成绩+给学生打分+修改自己信息

![](https://github.com/1123GY/Student_Manager/blob/master/Image/教师界面.jpg)

 ## 3.管理员模块
 
查看全部课程+添课+查看全部开课+开新课+查看全部学生信息+删除学生+查看全部教师信息+删除教师

![](https://github.com/1123GY/Student_Manager/blob/master/Image/管理员页面.jpg)