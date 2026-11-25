# Codex Credits 个人支持页

纯静态个人支持页。使用 OpenAI 官方赠送流程，不自行收款，不收集登录信息和兑换链接。

## 配置

编辑 index.html 中 CONFIG.recipientEmail，填写明确愿意公开的接收邮箱。留空时提示先私下确认接收方式。请勿公开兑换链接、密码或 Token。

默认站点：https://qishuhua.github.io/codex-donate/ 。修改地址时同步更新 CONFIG.siteUrl 和 qrcode.svg。

## GitHub Pages

打开 https://github.com/qishuhua/codex-donate/settings/pages ，Source 选择 Deploy from a branch，Branch 选择 main 和 /(root)，保存。部署成功后访问默认站点，验证扫码和跳转。

## 本地预览

运行 python -m http.server 8080，访问 http://localhost:8080/ 。

## 官方流程

- https://help.openai.com/en/articles/20001417-gifting-credits-in-chatgpt
- https://chatgpt.com/codex/settings/usage （用量管理页，并非已验证的独立赠送结账链接）

功能分批开放，双方需符合官方资格并使用相同账单币种。购买后私下交付一次性领取链接，接收人在 30 天内兑换；并非扫码自动充值。本站非 OpenAI 官方网站。
