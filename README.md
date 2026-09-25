# Agent Gateway Compare

五款 AI Agent 网关与模型管理工具的简洁对比页：Magpie · CC Switch · CLIProxyAPI · AstrLink · opencodex。

**线上**: https://agent-gateway-compare.versun.me

## 特性
- 单文件静态页，无框架，gzip ~3KB
- 暗/亮主题切换（跟随系统 + 手动 + localStorage 记忆，无 FOUC）
- 一句话定位 / 基础信息 / 能力矩阵 / 订阅借力风险 / 怎么选

## 部署
Cloudflare Workers 静态资产托管：

```sh
npx wrangler deploy
```

`wrangler.jsonc` 的 `assets.directory` 指向 `dist/`（其中仅 `index.html`）。

## License
MIT · Made with ❤️ Versun
