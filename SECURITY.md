# Security and privacy

请通过 GitHub Security Advisory 私下报告仓库自身的安全问题，不要在公开 issue 中
粘贴真实凭据、目标数据、未公开漏洞或个人信息。

本仓库只接受可公开复用的框架、模板和合成测试数据。以下内容不得提交：

- `.env`、API key、token、Cookie、私钥、抓包中的认证头；
- 真实目标域名/IP、客户或比赛私有题目数据；
- 用户目录、绝对工作区路径、用户名、邮箱、手机号；
- `samples/`、`cases/`、`exports/`、`reports/` 中的实际任务产物；
- 受第三方许可限制的工具二进制或样本。

提交前运行：

```powershell
python scripts/misc/public_release_check.py
```
