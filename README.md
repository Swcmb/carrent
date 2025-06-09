# 汽车租赁系统

这是一个基于 Spring Boot 的汽车租赁管理系统，提供完整的汽车租赁业务流程管理功能。

## 技术栈

- 后端框架：Spring Boot 2.1.4
- 数据库：MySQL 8.0
- ORM框架：MyBatis + JPA
- 前端技术：JSP + JSTL
- 支付集成：支付宝 SDK
- 其他功能：
  - 阿里云服务集成
  - 二维码生成
  - MongoDB 支持

## 系统要求

- JDK 1.8
- Maven 3.x
- MySQL 8.0
- MongoDB（可选）

## 快速开始

1. 克隆项目到本地
```bash
git clone [项目地址]
```

2. 配置数据库
- 导入 `数据库/wbar.sql` 到 MySQL 数据库
- 修改 `application.properties` 中的数据库连接信息

3. 编译运行
```bash
mvn clean package
java -jar target/carrent-0.0.1-SNAPSHOT.jar
```

## 主要功能

- 用户管理
- 车辆管理
- 租赁订单管理
- 支付集成
- 数据统计

## 项目结构

```
src/
├── main/
│   ├── java/        # Java 源代码
│   └── resources/   # 配置文件
├── test/            # 测试代码
数据库/              # 数据库脚本
```

## 开发说明

- 使用 MyBatis Generator 生成基础代码
- 遵循 RESTful API 设计规范
- 使用 Lombok 简化代码

## 注意事项

- 首次运行需要配置数据库连接信息
- 支付功能需要配置支付宝相关参数
- 阿里云服务需要配置相应的 AccessKey

## 许可证

[许可证类型]
