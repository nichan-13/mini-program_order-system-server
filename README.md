# mini-program_order-system-server
点餐小程序服务端

## 使用说明
- 详见 `环境搭建说明` 文档，文档所用**Wampserver**版本为 `3.1.7` ，可下载最新版**Wampserver**，参照文档进行配置
	- [Wampserver官网](https://www.wampserver.com/)
- 启动**Wampserver**可能会报错 `由于找不到MSVCR110.dll，无法创建执行代码。` ，原因是缺少一个运行库合集
	- 在微软官网下载 [VSU4/vcredist](https://www.microsoft.com/zh-CN/download/details.aspx?id=30679) 安装后重启Wampserver即可解决
