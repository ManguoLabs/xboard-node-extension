# XBoard 免费节点采集与节点扩展

面向 XBoard 免费节点采集、XBoard 节点扩展、XBoard 第三方节点、XBoard Clash 订阅与节点池管理的公开技术说明。

本仓库解释外部节点数据如何进入验证、规范化、去重、健康检查和权限组分配流程，不公开商业产品核心源码。

## 适用场景

- 导入 Clash 或 Mihomo 订阅节点
- 接入远程 API、JSON 或第三方节点源
- 聚合多个订阅并建立节点池
- 按 XBoard 权限组或套餐分配节点
- 自动发现失效、重复或格式异常节点

## 安全与质量

免费节点和第三方节点不天然可信。接入前应验证授权、来源、隐私风险、协议字段和可用性，并设置失效移除与人工禁用机制。

## 文档

- [免费节点采集流程](docs/free-node-collector.md)
- [Clash 订阅导入](docs/clash-import.md)
- [远程 API 节点](docs/api-nodes.md)
- [权限组节点分配](docs/permission-groups.md)
- [常见问题 FAQ](FAQ.md)

## Manguo Labs

产品说明：[XBoard 节点扩展](https://manguolabs.com/xboard-node-extension/)

需要评估节点源或面板接入方式时，可通过 [@ManguoShop_bot](https://t.me/ManguoShop_bot) 咨询。不要在公开 Issue 中提交订阅链接、Token 或私有节点地址。
