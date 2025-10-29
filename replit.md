# Spring Boot 项目

## 概述
这是一个Spring Boot项目，包含一个webhook验证接口。

## 项目结构
- `src/main/java/com/example/demo/` - Java源代码
  - `DemoApplication.java` - 主应用类
  - `controller/NotificationController.java` - 通知控制器
- `src/main/resources/` - 资源文件
  - `application.properties` - 应用配置
- `pom.xml` - Maven依赖配置

## 接口说明
- `GET /notification?validationToken=<token>` - Webhook验证接口，返回传入的token

## 技术栈
- Spring Boot 3.2.0
- Java 17
- Maven
- Lombok

## 最近更改
- 2025-10-29: 初始化项目结构和webhook验证接口
