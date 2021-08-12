# 026ssm高校党员管理系统
026ssm高校党员管理系统

## 项目介绍
高校党员信息管理系统，分为普通用户和管理员两种角色。

普通用户登录后主要功能有：
我的中心:首页、个人资料、修改密码；
党费信息:党费信息查询、党费缴纳；
通知查询：查看通知；
党员成绩信息：党课信息查询
个人操作日志：个人操作日志；
管理员登录后主要功能有:
系统用户管理：首页、管理员账号管理、添加管理kmuu账号、修改密码；
普通用户管理：用户信息查询、用户信息添加；
党员信息管理：正式党员查询、预备党员查询、发展对象查询、入党积极分子查询、入党申请人查询；
党组织管理：党组织查询、党组织添加；
党员党课成绩：党课信息查询、党课添加；
党费信息管理：党费信息管理
党员成绩管理：党员成绩查询、党员成绩添加；
通知信息管理：通知信息查询、通知信息添加；
党员活动管理：活动信息查询、活动信息添加；
操作日志管理：操作日志查询；
数据备份：数据备份；

演示视频：[ **点此查看** ](https://www.bilibili.com/video/av417027900/)

源码获取：[ **点此获取** ](http://www.shuyue.fun/index.php?type=productinfo&id=127)

## 环境需要
1.运行环境：最好是java jdk 1.8，我们在这个平台上运行的。其他版本理论上也可以。
2.IDE环境：IDEA，Eclipse,Myeclipse都可以。推荐IDEA;
3.tomcat环境：Tomcat 7.x,8.x,9.x版本均可
4.硬件环境：windows 7/8/10 1G内存以上；或者 Mac OS；
5.是否Maven项目: 是；查看源码目录中是否包含pom.xml；若包含，则为maven项目，否则为非maven项目
6.数据库：MySql 5.7版本；

## 技术栈
1. 后端：Spring SpringMVC MyBatis
2. 前端：JSP+Bootstrap+JQuery+AmazeUI

## 使用说明
1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；
2. 将项目中jdbc.properties配置文件中的数据库配置改为自己的配置
3. 使用IDEA/Eclipse/MyEclipse导入项目，Eclipse/MyEclipse导入时，若为maven项目请选择maven;
若为maven项目，导入成功后请执行maven clean;maven install命令，配置tomcat，然后运行；
5. 运行项目，输入localhost:8080/xxx 登录
管理员用户：admin  密码：admin
普通用户：688566199812229977 密码：123456

## 运行截图
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/201030_a50d749a_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/201041_0109d936_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/201050_77ba4da6_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/201059_0ab3d753_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/201110_c1c99f49_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/201119_419966c1_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/201130_e125e7e8_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/201139_56baa9b2_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/201150_cd67942b_863230.png "屏幕截图.png")
