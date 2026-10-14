<div align="center">

# 🎬 browser-use-automation

## 会点、会打字、会上传下载：让 AI 真把网页操作一遍
## AI that actually clicks, types, uploads and downloads real pages

📮 **商务合作 / Business：wow.vip@foxmail.com**
🎬 **抖音 / Douyin：[v.douyin.com/07EjIDGVErY](https://v.douyin.com/07EjIDGVErY/)**

</div>

---

## 🇨🇳 中文

让智能体直接操作真实网站：打开与跳转页面、读取可见内容和 UI 状态、点击、输入、选择、上传下载文件、截图、管理标签页、跑通业务流并排查浏览器问题。实现边界很硬——页面控制只用一条路径，即 plane="bu" 的 computer_use_tool 并导入 seed_browser_use，Bash、HTTP 客户端和脚本都不算浏览器控制的替代方案。每个业务步骤都翻译成「先取 ref、观察—操作—再观察」的循环，站点参考文档只提供业务规则，不定义浏览器后端。凡是登录、二次验证、扫码/短信/OTP、验证码或需要用户接管，一律走 interaction.request_action 拉起人工授权，绝不用一句文字请求登录糊过去。也覆盖淘宝/天猫、微博、小红书等站点的业务流程。

### ✨ 能做什么

- 打开/跳转页面、读取可见内容与 UI 状态、截图并管理标签页
- 点击、输入、下拉选择、上传与下载文件，完整跑通一段 Web 流程
- 确定性实现路径：plane="bu" 的 computer_use_tool + seed_browser_use，杜绝混用后端
- 每步业务动作翻译为 ref-first 的「观察—操作—观察」循环
- 登录、扫码/短信/OTP、验证码、身份核验 → 拉起用户接管授权
- 内置淘宝/天猫、微博、小红书等站点的业务规则路由

### 📦 包含的技能

- `browser-use-automation` —— 见 [`browser-use-automation/SKILL.md`](browser-use-automation/SKILL.md)

### 🚀 安装

```bash
git clone https://github.com/yzsp-studio/browser-use-automation.git
cp -r browser-use-automation/* "$DSH_HOME/skills/"
```

> 技能是**纯文本说明**（`SKILL.md` + `references/`），零依赖、零 API key，用你当前 agent 的会话额度。

---

## 🇬🇧 English

Lets an agent drive real websites: open and navigate pages, inspect visible content and UI state, click, type, select, upload and download files, take screenshots, manage tabs, test a web flow and troubleshoot browser behavior. The implementation boundary is strict: page control runs through exactly one path, a computer_use_tool cell with plane="bu" importing seed_browser_use, so Bash, HTTP clients and shell scripts are never alternate browser backends. Every business step is translated into a ref-first observe-act-observe loop, and site references only supply business rules, never a browser backend. Whenever login, reauthentication, QR/SMS/OTP, CAPTCHA, identity verification or user takeover is needed, it calls interaction.request_action to hand off for authorization instead of sending a text-only login request. Site workflows such as Taobao/Tmall, Weibo and Xiaohongshu are covered.

### ✨ What it does

- Opens and navigates pages, reads visible content and UI state, screenshots and manages tabs
- Clicks, types, selects, uploads and downloads files to complete a full web flow
- One deterministic control path: computer_use_tool with plane="bu" plus seed_browser_use
- Translates each business step into a ref-first observe-act-observe loop
- Login, QR/SMS/OTP, CAPTCHA and identity checks trigger a real handoff for user authorization
- Routes business rules for sites including Taobao/Tmall, Weibo and Xiaohongshu

### 📦 Skills included

- `browser-use-automation` — [`browser-use-automation/SKILL.md`](browser-use-automation/SKILL.md)

### 🚀 Install

```bash
git clone https://github.com/yzsp-studio/browser-use-automation.git
cp -r browser-use-automation/* "$DSH_HOME/skills/"
```

> Skills are **plain-text instructions** (`SKILL.md` + `references/`). Zero dependencies, no API keys — they run on your agent's existing session quota.

---

## 📮 联系 / Contact

| | |
|---|---|
| 🎬 **抖音 / Douyin** | [https://v.douyin.com/07EjIDGVErY/](https://v.douyin.com/07EjIDGVErY/) |
| 📮 **商务合作 / Business** | **wow.vip@foxmail.com** |
| 🐙 **GitHub** | [https://github.com/yzsp-ai](https://github.com/yzsp-ai) |
| 💖 **打赏 / Support** | [afdian.com/a/yzsp-ai](https://afdian.com/a/yzsp-ai) |

## 📄 License

[MIT](LICENSE) · © 2026 [yzsp-ai](https://github.com/yzsp-ai)
