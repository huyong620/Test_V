> [![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https://github.com/huyong620/Test_V)

 4. 回到专案首页，点击上面的链接以部署 V2Ray

### 变量
##| `ID` |`ad806487-2d26-4636-98b6-ab85cc8521f7`|
##| `AID`|`64`|
##
对部署时需设定的变量名称做如下说明。

| 变量 | 默认值 | 说明 |
| :--- | :--- | :--- |
| `ID` | (`2290c4e2-c1df-4993-88a7-4e2a2137fb44`) | VMess 用户主 ID，用于身份验证，为 UUID 格式 |
| `AID` | `128` | 为进一步防止被探测所设额外 ID，即 AlterID，范围为 0 至 65535 |
| `WSPATH` | `/` | WebSocket 所使用的 HTTP 协议路径 |

## 接入 CloudFlare

以下两种方式均可以将应用接入 CloudFlare，从而在一定程度上提升速度。

 1. 为应用绑定域名，并将该域名接入 CloudFlare
 2. 通过 CloudFlare Workers 反向代理

## 注意

 1. **请勿滥用本专案，类似 Heroku 的免费服务少之又少，且用且珍惜**
 2. 若使用域名接入 CloudFlare，请考虑启用 TLS 1.3
 3. AWS 绝大部分 IPv4 地址已被 Twitter 屏蔽
