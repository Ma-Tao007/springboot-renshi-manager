# springboot-renshi-manager

@[TOC](基于Springboot的人事管理系统)
# 项目简介
基于Springboot框架开发的人事管理系统共分为四个角色：系统管理员、财务专员、人事专员、普通用户
管理员角色包含以下功能： 
管理员拥有所有功能：绩效考核（考核设置）、招聘管理（招聘需求、面试计划）、档案管理（员工档案、合同管理）、工资管理（工资查询）、考勤管理（出勤记录）、培训管理（个人计划、工作日报、转正申请、培训计划）、系统管理（员工管理、部门管理、角色管理、菜单管理、字典管理）

财务专员角色包含以下功能： 
工资管理（工资查询）、考勤管理（出勤记录（上下班打卡））、培训管理（个人计划、工作日报、转正申请）

人事专员角色包含以下功能：招聘管理（招聘需求、面试计划）、档案管理（员工档案）、工资管理（工资查询）、考勤管理（出勤记录）、培训管理（个人计划、工作日报、转正申请）、系统管理（员工管理）

普通用户角色包含以下功能： 
工资查询、考勤管理（出勤记录（上下班打卡））、培训管理（个人计划、工作日报、转正申请）、系统管理（员工查看、部门查看、角色查看）


 # 项目获取
> [源码获取地址](http://www.manoncode.cn/details?id=125)

 
# 开发环境

运行环境：推荐jdk1.8；
开发工具：eclipse以及idea（推荐）、redis；
操作系统：windows 10 8G内存以上（其他windows以及macOS支持，但不推荐）；
浏览器：Firefox(推荐)、Google Chrome(推荐)、Edge;
数据库：MySQL8.0(推荐)及其他版本（支持，但容易异常尤其MySQL5.7（不含）以下版本）；
数据库可视化工具：Navicat Premium 15（推荐）以及其他Navicat版本
是否maven项目：是


 # 项目技术
 
后端：SpringBoot、Mybatis、mysql、redis
前端：html、layui、jquery、ajax、vue

 # 运行截图
 **1.招聘管理-招聘需求**![在这里插入图片描述](https://img-blog.csdnimg.cn/7d357fda9099406a829909b1f1568573.png#pic_center) **财务人员管理页面**
![在这里插入图片描述](https://img-blog.csdnimg.cn/cd364dfe67af4011a0bea9a1023aa884.png#pic_center) **系统管理-字典管理**
![在这里插入图片描述](https://img-blog.csdnimg.cn/e521a830cd2b4777ab8c57b28a66e686.png#pic_center)**系统管理-部门管理**
![在这里插入图片描述](https://img-blog.csdnimg.cn/efe80dd25f06464bb644c4ad8be56db7.png#pic_center)
**系统管理-菜单管理**![在这里插入图片描述](https://img-blog.csdnimg.cn/c2dcdd9ed7c34963bc70bb2e67d898ee.png#pic_center)
**培训管理-工作日报**![在这里插入图片描述](https://img-blog.csdnimg.cn/87d99adee49e4f23bdba22b70c7cf9df.png#pic_center)**工资管理**
![在这里插入图片描述](https://img-blog.csdnimg.cn/ef9d8520805644ebbdeed966a1357c8d.png#pic_center)**绩效审核**
![在这里插入图片描述](https://img-blog.csdnimg.cn/8254e582fe2a43ba8f86014a374843b2.png#pic_center)**培训管理-转正申请**
![在这里插入图片描述](https://img-blog.csdnimg.cn/0dc0a7692fc247acb721251119e419f1.png#pic_center)**考核设置**
![在这里插入图片描述](https://img-blog.csdnimg.cn/8909de088311436eb5a042dd2a294f0d.png#pic_center)**登录页面**
![在这里插入图片描述](https://img-blog.csdnimg.cn/3f71247541e64fac9db5d7b755183b1f.png#pic_center)**项目结构**
![在这里插入图片描述](https://img-blog.csdnimg.cn/884f65d4b1d34009a5238a1bba4d7519.png#pic_center)
**源码下载结构**
![在这里插入图片描述](https://img-blog.csdnimg.cn/129ad5e2f1164ef5a5cd634c20f05dbc.png#pic_center)
**培训管理-个人计划**
![在这里插入图片描述](https://img-blog.csdnimg.cn/0504542e6fa94fafb1499dfab55549db.png#pic_center)**档案管理-合同管理**
![在这里插入图片描述](https://img-blog.csdnimg.cn/1a60979767ed4922883a05a8cec40793.png#pic_center)**普通用户页面**
![在这里插入图片描述](https://img-blog.csdnimg.cn/9bab973e0a6e4f19954aed865b0ec303.png#pic_center)**招聘管理-面试计划**
![在这里插入图片描述](https://img-blog.csdnimg.cn/9111de7d984f4e0496b66ed2220a07aa.png#pic_center)**档案管理-员工档案**
![在这里插入图片描述](https://img-blog.csdnimg.cn/b8728d0769e34810a4cf61a785b2b8f2.png#pic_center)**系统管理-字典管理**
![在这里插入图片描述](https://img-blog.csdnimg.cn/09fd4840a404456c8a7469bdd1519f10.png#pic_center)**系统管理-角色管理**
![在这里插入图片描述](https://img-blog.csdnimg.cn/6579ea9f13144c178138a6d6b285d327.png#pic_center)**考勤管理**
![在这里插入图片描述](https://img-blog.csdnimg.cn/e25540913de04fca9a1bb655868fb404.png#pic_center)
![在这里插入图片描述](https://img-blog.csdnimg.cn/c14de8c4f3d0491f88fad4db355a5936.png#pic_center)
![在这里插入图片描述](https://img-blog.csdnimg.cn/aa8a81f4e524457e8e99d1283a4e4dcc.png#pic_center)
![在这里插入图片描述](https://img-blog.csdnimg.cn/93015c00670f47b1b1da395ab5f2ed0a.png#pic_center)
![在这里插入图片描述](https://img-blog.csdnimg.cn/7713be9048984a3a8785a850b334af94.png#pic_center)
![在这里插入图片描述](https://img-blog.csdnimg.cn/55e781d1146b4600941f5d12528631c4.png#pic_center)

