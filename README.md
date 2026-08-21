# Shadowrocket 配置文件

一份开箱即用的 Shadowrocket 规则配置，导入后添加自己的节点或订阅即可使用。

## 当前重点

- 优化 DNS 防泄露
   - 上游 DNS 仅使用 DNSPod / AliDNS 的 DoH
   - 备用 DNS 不再回退系统 DNS
   - 直连域名解析不再强制使用系统 DNS
   - 扩展常见硬编码 DNS 劫持范围
   - 新增 blackmatrix7 `BlockHttpDNS`，拦截 App 内置 HTTPDNS
