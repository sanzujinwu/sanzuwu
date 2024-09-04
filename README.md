<br/>
<br/>
<p align = "center">
    <img src="logo.png" width="96">
    <h3 align = "center">三足乌数据中台</h3>
    <p align = "center">一体化、可视化数据开发平台</p>
</p>


## 项目介绍
三足乌数据中台融合数据规划、数据接入、数据开发、数据仓库、数据治理、数据资产、数据服务、数据运维、系统管理等功能模块为一体。打通数据壁垒，解决数据孤岛问题，实现数据的低代码可视化开发，助力政府、企业数字化转型。

## 演示（文末获取账号）
<a href="http://47.92.101.159:8180" target="_blank">演示平台</a>

## 文档
<a href="http://47.92.101.159" target="_blank">中文文档</a>

## 架构图
![](img/0架构图.png)


## 项目截图
### 登陆页
![](img/1登陆.png)
### 首页
![](img/2首页.png)
### 工作台
![](img/3工作台.png)
### 全景图
![](img/4全景图.png)
### 数据源管理
![](img/25-1数据源列表.png)
![](img/25-2数据源.png)
### 数据接入
#### 数据探查
![](img/数据探查.png)
#### 数据同步
![](img/数据同步1.png)
![](img/数据同步2.png)
#### 数据对账
![](img/7数据对账.png)
#### 接入概览
![](img/8接入概览.png)
### 数据开发
#### 离线开发
![](img/9-1数据加工列表.png)
![](img/9-1数据加工工作流.png)
![](img/数据映射.png)
![](img/执行日志.png)
![](img/预览数据.png)
#### 工作流血缘
![](img/工作流血缘.png)
#### 实时开发
![](img/实时处理.png)
#### 脚本开发
![](img/脚本开发.png)
#### 机器学习
![](img/11机器学习.png)
#### 工作流开发
### 数据仓库
#### 数仓规划
![](img/12数仓规划.png)
#### 模型管理
![](img/物理建模.png)
### 数据治理
#### 数据标准
![](img/数据标准.png)
#### 数据质量
##### 质量规则
![](img/质量规则.png)
##### 质量评估
![](img/质量评估.png)
##### 质量报告
![](img/16质量报告历史.png)
![](img/17质量报告详情.png)
#### 元数据
##### 元数据查询
##### 血缘分析
![](img/18血缘分析.png)
![](img/19影响分析.png)
##### 血缘维护
![](img/20血缘维护.png)
#### 数据标签
##### 标签库
![](img/数据标签.png)
#### 数据安全
### 数据资产
#### 资产目录
![](img/23资产目录.png)
### 数据服务
#### 服务管理
![](img/21数据服务.png)
#### 服务概览
![](img/22服务概览.png)
### 数据运维
#### 流程实例
![](img/24-1任务监控.png)
#### 任务实例
![](img/24-2任务监控.png)
### 资源管理
#### 工作流管理
![](img/26数据开发工作流菜单.png)
## 功能一览
- 工作台
    - 任务管理: 待办、已办任务
    - 任务总览: 
- 可视化设计器
    - 设计器: 可视化拖拉组件
- 数据接入
    - 数据探查
        - 数据库探查: 配置可视化探查数据库工作流
        - 表探查: 配置可视化探查表工作流
    - 数据同步
        - DataX数据同步: 配置DataX可视化数据同步工作流
        - SeaTunnel数据同步: 配置SeaTunnel可视化数据同步工作流
        - ChunJun数据同步: 配置ChunJun可视化数据同步工作流
        - FlinkCDC数据同步: 配置FlinkCDC可视化数据同步工作流
    - 数据对账
        - 数据对账: 数据同步完成记录，展示数据同步总条数、错误条数等
    - 接入概览
        - 数据接入概览: 数据接入总体情况图表展示
- 数据开发
    - 离线开发: 配置可视化离线开发工作流，拖拉组件模块，提交任务到调度器
    - 实时开发: 集成Dinky
    - 脚本开发: 支持各类常见数据库SQL开发，BI展示结果，数据血缘关系分析
    - 工作流开发: 构建任务依赖流程图
- 数据治理
    - 数据标准: 本地数据中需要对照标准的数据维护
    - 数据质量
        - 规则配置: 数据质量规则配置
        - 数据校验: 配置数据质量校验工作流
        - 质量报告: 数据质量结果统计分析
- 数据标签
    - 标签管理: 标签分级、标签分类、标签规则定义
    - 标签开发: 配置可视化标签开发工作流，支持规则、统计、挖掘标签在线开发
    - 组合标签: 
    - 标签搜索: 
- 数据资产
    - 资产管理: 
- 数据服务
    - API管理: API定义、测试、授权、监控等
    - 令牌管理: 令牌管理
    - API日志: API接口调用日志
    - 服务概览: API接口统计展示
- 任务监控
    - 任务监控: 集成DolphinScheduler的运维日志
- 任务度器
    - 调度器: 调度器集成DolphinScheduler，并对DolphinScheduler做二次开发
- 资源管理
    - 数据源管理:
    - 算子管理: 
    - 函数管理: 
- 系统管理
    - 用户管理、部门管理、岗位管理、菜单管理、角色管理、参数配置、字典管理、系统监控
- 系统监控: 

## 技术选型
| 前端          | 后端        |  大数据          |
| ------------ | ----------- | --------------- | 
| vue3         | SpringBoot  | Hadoop          | 
| antv/x6      | SpringCloud | Zookeeper       | 
| echarts      | Nacos       | Hive            | 
| pinia        | Sentinel    | Spark           |
| monaco-editor| Seata       | Flink           |  
|              | SaToken     | Kafka           |  
|              | Minio       | Presto          |  
|              | Mysql       | Hbase           |  
|              | Redis       | DolpinScheduler |  
|              |             | ClickHouse      |  
|              |             | Doris           |  
|              |             | DataX           |  
|              |             | SeaTunnel       |  
|              |             | ChunJun         |  

## 特别鸣谢！
- [DolpinScheduler社区](https://www.slidestalk.com/DolphinScheduler/list/meetup/)
- [SeaTunnel社区](https://www.slidestalk.com/SeaTunnel/)
- [Dinky社区](http://www.dlink.top/)

## 关注
获取演示账号需收藏、关注项目。
添加微信【sanzujinwu_cloud】，或关注微信公众号【三足乌】（回复不及时），开启你的数据之旅吧，愿君在数据的道路上越走越远。。。<br>
![](img/wx_300.png)
