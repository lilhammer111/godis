# godis
## 项目介绍
godis使用go语言重写redis，采用tcp协议构建了一个集群化的内存型数据存储服务。
## 项目演示
暂无
## 组织架构
```
.
├── aof // 持久化落盘
├── cluster // 集群架构用于转发，广播请求
├── config // 项目配置
├── database // 执行客户端指令
├── datastruct // 数据结构定义
├── go.mod 
├── go.sum
├── interface // 接口定义
├── lib // 工具库
├── main.go // 主入口函数
├── redis.conf // redis配置文件
├── resp // 响应层，负责解析resp协议，定义通用响应，组织接口调用，返回服务端响应
└── tcp // tcp协议层，建立监听
```

## 技术选型
|技术|说明|官网|
|-|-|-|
|go-commons-pool|a generic object pool for golang|https://github.com/jolestar/go-commons-pool|

## 架构图
生产了一半。。。
![yuque_diagram](https://github.com/lilhammer111/godis/assets/113404700/c2c87374-71b1-47fa-9c1d-4d74655bbd4c)


## 环境搭建
紧急搭建中。。。

## 许可证
紧急许可中。。。
