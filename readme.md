# 基于SSM的宿舍管理系统

## 1、项目介绍

基于SSM的宿舍管理系统5拥有三种角色，分别为管理员、宿管、学生，具体功能如下：

- 管理员：楼层管理、宿舍管理、员工管理、物品进出登记、来访人员登记、学生管理、系统管理、用户管理

- 宿管：宿舍管理、学生管理、物品进出登记、来访人员登记

- 学生：个人信息查看、密码修改



## 2、项目技术

后端框架：SSM（Spring、SpringMVC、Mybatis）

前端框架：easyui、jsp、css、JavaScript、JQuery

## 3、开发环境

- JAVA版本：JDK1.8，其它版本理论上可以
- IDE类型：IDEA、Eclipse、Myeclipse都可以。推荐IDEA与Eclipse
- tomcat版本：Tomcat 7.x、8.x、9.x、10.x版本均可
- 数据库版本：MySql 5.x
- maven版本：无限制
- 硬件环境：Windows 或者 Mac OS


## 4、功能介绍

### 4.1 登录

![登录](https://www.codeshop.fun/Typora-Images/20220515002955.jpg)

三种用户均可通过登录界面登录至系统，需要输入正确的验证码和选择正确的用户类型

### 4.2 管理员模块

![管理员-楼层管理](https://www.codeshop.fun/Typora-Images/20220515003032.jpg)

![管理员-宿舍管理](https://www.codeshop.fun/Typora-Images/20220515003037.jpg)

![管理员-物品进出管理](https://www.codeshop.fun/Typora-Images/20220515003040.jpg)

![管理员-学生管理](https://www.codeshop.fun/Typora-Images/20220515003041.jpg)

![管理员-用户管理](https://www.codeshop.fun/Typora-Images/20220515003043.jpg)

![管理员-员工管理](https://www.codeshop.fun/Typora-Images/20220515003048.jpg)

- 楼层管理：管理员可以根据楼层号查询楼层信息，还可查看、增加、编辑和停用、启用楼层

- 宿舍管理：管理员可以根据宿舍号、容量、所在楼层查询宿舍信息，还可查看、增加、编辑和停用、启用宿舍

- 员工管理：管理员可以根据员工姓名、所在楼层查询员工，还可查看、增加、编辑和停用、启用宿舍员工

- 物品进出登记：管理员可以根据物品名称查询物品登记信息，还可添加记录、删除和修改记录

- 来访人员登记：管理员可以根据来访人和被访人筛选来访人员登记记录，还可添加和删除记录

- 学生管理：管理员可以根据学号、姓名、班级、宿舍号筛选学生，还可查看、修改、添加、删除学生

- 用户管理：管理员可以根据用户名筛选学生，还可查看、修改、添加、删除用户


### 4.3 宿管模块

![宿管-来访人员管理](https://www.codeshop.fun/Typora-Images/20220515003523.jpg)

![宿管-宿舍管理](https://www.codeshop.fun/Typora-Images/20220515003526.jpg)

![宿管-物品进出登记](https://www.codeshop.fun/Typora-Images/20220515003529.jpg)

![宿管-学生管理](https://www.codeshop.fun/Typora-Images/20220515003531.jpg)

- 宿舍管理：同上

- 学生管理：同上

- 物品进出登记： 宿管可以根据物品名称查询物品登记信息，还可添加记录、删除和修改记录

- 来访人员登记： 宿管可以根据来访人和被访人筛选来访人员登记记录，还可添加和删除记录


### 4.4 学生模块

![学生界面](https://www.codeshop.fun/Typora-Images/20220515003607.jpg)

学生可以查看个人信息、密码修改

## 6、获取方式

关注公众号： **程序员王不二**，回复 “宿舍5 ” ，即可获取完整版的项目代码。

![image-20220509000010316](https://gitee.com/buer_wang/project-drawing-bed/raw/master/Typora-Images/20220509000012.png)


  

