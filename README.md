# springboot-app

## 系统介绍

- springboot-app 是J2EE基础开发平台，技术栈包括：SpringBoot、MyBatis、SpringSecurityOAuth，swagger，lombok，SpringTask，业务模块包括：用户管理，角色管理、权限管理，字典管理，定时任务。

## 业务功能

- 1.用户管理：用户增删改查与角色关系
- 2.角色管理：角色增删改查与权限关系
- 3.菜单管理：菜单增删改查（树形结构）
- 4.字典管理：字典增删改查
- 5.定时器：定时器执行

## 技术栈

- springBoot 依赖注入，切面  
- mybatis ORM 
- SpringSecurityOAuth 权限会话 
- springTask 定时任务 
- swagger api
- lombok 代码优化

## 部署

- 1.导入数据库脚本springboot-app.sql
- 2.将https://github.com/vmaps3/admin-ui  放入\src\main\resources\ 更改对应include.js
- 3.启动sprtingboot-app位置com.wangsong.Application
- 4.访问/springboot-app/html/login.html

## qq交流群

- 74745979
