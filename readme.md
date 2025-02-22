# Checkin

GitHub Actions 实现 [GLaDOS][glados] 自动签到

## 使用说明

1. Fork 这个仓库

1. 登录 [GLaDOS][glados] 获取 Cookie

1. 添加 koa:sess=***; koa:sess.sig=**** 到 Secret `GLADOS`

1. 启用 Actions, 每天北京时间 00:10 自动签到

1.  [PushPlus][pushplus], 添加 Token 到 Secret `NOTIFY`

[glados]: https://github.com/glados-network/GLaDOS
[pushplus]: https://www.pushplus.plus/
