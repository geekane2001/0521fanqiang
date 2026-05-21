# Node.js Argo Web Service

基于 Node.js 的轻量级 Web 应用服务。

## 📋 环境变量配置

| 变量名 | 是否必须 | 默认值 | 说明 |
|--------|----------|--------|------|
| PORT | 否 | 3000 | 服务监听端口 |
| UUID | 否 | 自动生成 | 专属 UUID 标识 |
| ARGO_DOMAIN | 否 | - | 固定隧道域名（留空启用临时通道） |
| ARGO_AUTH | 否 | - | 固定隧道密钥 |
| CFIP | 否 | saas.sin.fan | 优选域名或 IP |
| CFPORT | 否 | 443 | 优选端口 |
| NAME | 否 | - | 节点前缀名称 |
| SUB_PATH | 否 | sub | 订阅路径 |

## 🚀 部署

```bash
npm install
node index.js
```
