# FKM 登录与找回密码 Demo

公开交互原型，支持简体中文、繁体中文、English。

- [在线演示](https://mikann-star.github.io/fkm-login-demo/)：顶部短信开关可以切换开放/未开放状态。
- [固定短信开放版](https://mikann-star.github.io/fkm-login-demo/sms-enabled.html)
- [固定短信关闭版](https://mikann-star.github.io/fkm-login-demo/sms-disabled.html)

## 测试

忘记密码输入 demo、email、merchant@example.com 或 13812345678 可测试双绑定账号；email-only 仅绑定邮箱，phone 仅绑定手机号，none 未绑定。

验证码为 123456，新密码示例 Fkm888888!。登录填写任意非空标识和密码，可体验模拟成功及桌台页，点击退出登录可重复测试。

此页面为开发演示，不执行真实鉴权或修改密码，不发送真实短信/邮件，不保存密码。请使用演示数据。

## 发布与更新

GitHub Pages 从 main 分支根目录发布，无需构建。更新 index.html 后自动重新部署。
