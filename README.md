# 锦绣AI · API 中转站原型

> 高保真静态原型，演示锦绣AI 统一接入多家大模型 API 的中转站产品形态。

## 在线访问

**GitHub Pages**：<https://lamky666.github.io/jinxiuai-prototype/>

- 首页：<https://lamky666.github.io/jinxiuai-prototype/index.html>
- 用户控制台：<https://lamky666.github.io/jinxiuai-prototype/dashboard.html>
- 在线对话（仿 ChatGPT）：<https://lamky666.github.io/jinxiuai-prototype/chat.html>
- 接口文档：<https://lamky666.github.io/jinxiuai-prototype/docs.html>
- 套餐价格：<https://lamky666.github.io/jinxiuai-prototype/prices.html>
- 登录 / 注册：<https://lamky666.github.io/jinxiuai-prototype/login.html>

## 页面清单

| 文件 | 用途 | 关键能力 |
| --- | --- | --- |
| `index.html` | 营销首页 | Hero 段、价格锚点、品牌故事、模型矩阵、CTA |
| `prices.html` | 套餐价格 | 阶梯定价、按量付费、增值服务对比 |
| `docs.html` | 接口文档 | 左侧 15 章节目录 + 右侧正文：API 快速开始 / Codex CLI / Claude Code / WorkBuddy / Cursor / Cline / Continue / ChatGPT 风格 / Raycast / LangChain / Dify / FAQ |
| `about.html` | 关于我们 | 团队愿景、联系方式、加入我们 |
| `login.html` | 登录 | 邮箱+密码、社交登录占位 |
| `register.html` | 注册 | 邮箱注册、邀请码、协议勾选 |
| `chat.html` | 在线对话 | 仿 ChatGPT 网页版：左侧会话历史、模型选择、参数抽屉、对话流 |
| `dashboard.html` | 用户控制台 | 工作台概览（余额/用量/多中转站）、API Key 管理、充值/账单/返佣/文档/个人资料 |

## 技术说明

- **纯静态 HTML + Tailwind CSS（CDN）+ 原生 JS** — 零构建、零依赖、双击 index.html 即可预览
- 所有交互（标签切换、筛选、复制、Tab、Toast）都是原生 JS demo
- 数据为前端硬编码示例值，**不连接任何后端**

## 本地预览

```bash
cd packages/web/public/prototype
python -m http.server 8080
# 浏览器打开 http://127.0.0.1:8080/
```

## 迭代记录

详见项目内 `packages/web/.workbuddy/memory/2026-07-02.md`（按轮次记录每一版需求→实现→验证）。

---

© 2026 锦绣AI · 演示原型

