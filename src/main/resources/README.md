# admin-ui

## 系统介绍

- admin-ui 为springboot/dubbo-app/springcloud-app提供后台管理前端页面，技术栈包括：jquery、jqueryeasyui、jquery-cookie业务模块包括：用户管理，角色管理、权限管理，字典管理。

## 流程简介
- 登陆后换取token放入cookie内，每次访问后端携带
- 前端组成菜单，通过后端返回权限码，进行填充数据

## 业务功能

- 1.用户管理：用户增删改查与角色关系
- 2.角色管理：角色增删改查与权限关系
- 3.菜单管理：菜单增删改查（树形结构）
- 4.字典管理：字典增删改查

## 技术栈

- jquery 核心 
- jqueryeasyui 组件
- jquery-cookie cookie操作

## 部署

- 参考相对应后端工程
- springboot为核心单机后端框架 https://github.com/vmaps3/springboot-app
- dubbo为核心分布式后端框架 https://github.com/vmaps3/dubbo-app
- springcloud为核心分布式后端框架 https://github.com/vmaps3/springcloud-app

## qq交流群

- 74745979
