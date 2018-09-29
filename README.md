# Customer Relationship Management
> CRM-客户关系管理系统

需求：
1. 不同角色登录进行不同事务的管理
2. 客户信息及时、高效创建与管理
3. 自动化统计报表，绘制客户贡献与构成图
4. 产品信息管理与库存查询
5. 角色和管理员的创建及管理
6. 日志的记录与查看

开发环境：
- JavaSE 1.8
- Tomcat 8.5
- Maven 3.5
- Eclipse

技术：
- Spring
- Springmvc
- Mybatis
- Oracle
- jQuery+Ajax+Jason
- JFreeChart
- PageHelper

功能角色：
- 管理员
- 高管
- 主管
- 经理

功能模块：
- 营销管理模块
- 客户管理模块
- 服务管理模块
- 统计报表模块
- 基础数据模块
- 系统设置模块

项目结构：
```
crm
|
|--common //通用
|     |
|     |--bean //实体类
|     |
|     |--exception //自定义异常
|     |
|     |--util //额外插件
|
|--dao //数据库交互
|
|--service //逻辑处理
|     |
|     |--impl //服务层实现类
|     |
|     |--interfaces //服务层接口
|
|--web //前后端交互
```
