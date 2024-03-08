<div align="center">
<img src="./docs/images/head-cover.png" alt="icon"/>

<h1 align="center">NextChat (ChatGPT Next Web)</h1>

English / [简体中文](./README_CN.md)

One-Click to get a well-designed cross-platform ChatGPT web UI, with GPT3, GPT4 & Gemini Pro support.

一键免费部署你的跨平台私人 ChatGPT 应用, 支持 GPT3, GPT4 & Gemini Pro 模型。

[![Web][Web-image]][web-url]
[![Windows][Windows-image]][download-url]
[![MacOS][MacOS-image]][download-url]
[![Linux][Linux-image]][download-url]

[Web App](https://app.nextchat.dev/) / [Desktop App](https://github.com/Yidadaa/ChatGPT-Next-Web/releases) / [Discord](https://discord.gg/YCkeafCafC) / [Twitter](https://twitter.com/NextChatDev)

[网页版](https://app.nextchat.dev/) / [客户端](https://github.com/Yidadaa/ChatGPT-Next-Web/releases) / [反馈](https://github.com/Yidadaa/ChatGPT-Next-Web/issues)

[web-url]: https://chatgpt.nextweb.fun
[download-url]: https://github.com/Yidadaa/ChatGPT-Next-Web/releases
[Web-image]: https://img.shields.io/badge/Web-PWA-orange?logo=microsoftedge
[Windows-image]: https://img.shields.io/badge/-Windows-blue?logo=windows
[MacOS-image]: https://img.shields.io/badge/-MacOS-black?logo=apple
[Linux-image]: https://img.shields.io/badge/-Linux-333?logo=ubuntu

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FYidadaa%2FChatGPT-Next-Web&env=OPENAI_API_KEY&env=CODE&env=GOOGLE_API_KEY&project-name=chatgpt-next-web&repository-name=ChatGPT-Next-Web)

[![Deploy on Zeabur](https://zeabur.com/button.svg)](https://zeabur.com/templates/ZBUEFA)

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/Yidadaa/ChatGPT-Next-Web)

![cover](./docs/images/cover.png)

</div>

## Features

- **Deploy for free with one-click** on Vercel in under 1 minute
- Compact client (~5MB) on Linux/Windows/MacOS, [download it now](https://github.com/Yidadaa/ChatGPT-Next-Web/releases)
- Fully compatible with self-deployed LLMs, recommended for use with [RWKV-Runner](https://github.com/josStorer/RWKV-Runner) or [LocalAI](https://github.com/go-skynet/LocalAI)
- Privacy first, all data is stored locally in the browser
- Markdown support: LaTex, mermaid, code highlight, etc.
- Responsive design, dark mode and PWA
- Fast first screen loading speed (~100kb), support streaming response
- New in v2: create, share and debug your chat tools with prompt templates (mask)
- Awesome prompts powered by [awesome-chatgpt-prompts-zh](https://github.com/PlexPt/awesome-chatgpt-prompts-zh) and [awesome-chatgpt-prompts](https://github.com/f/awesome-chatgpt-prompts)
- Automatically compresses chat history to support long conversations while also saving your tokens
- I18n: English, 简体中文, 繁体中文, 日本語, Français, Español, Italiano, Türkçe, Deutsch, Tiếng Việt, Русский, Čeština, 한국어, Indonesia

## Roadmap

- [x] System Prompt: pin a user defined prompt as system prompt [#138](https://github.com/Yidadaa/ChatGPT-Next-Web/issues/138)
- [x] User Prompt: user can edit and save custom prompts to prompt list
- [x] Prompt Template: create a new chat with pre-defined in-context prompts [#993](https://github.com/Yidadaa/ChatGPT-Next-Web/issues/993)
- [x] Share as image, share to ShareGPT [#1741](https://github.com/Yidadaa/ChatGPT-Next-Web/pull/1741)
- [x] Desktop App with tauri
- [x] Self-host Model: Fully compatible with [RWKV-Runner](https://github.com/josStorer/RWKV-Runner), as well as server deployment of [LocalAI](https://github.com/go-skynet/LocalAI): llama/gpt4all/rwkv/vicuna/koala/gpt4all-j/cerebras/falcon/dolly etc.
- [ ] Plugins: support network search, calculator, any other apis etc. [#165](https://github.com/Yidadaa/ChatGPT-Next-Web/issues/165)

## What's New

- 🚀 v2.10.1 support Google Gemini Pro model.
- 🚀 v2.9.11 you can use azure endpoint now.
- 🚀 v2.8 now we have a client that runs across all platforms!
- 🚀 v2.7 let's share conversations as image, or share to ShareGPT!
- 🚀 v2.0 is released, now you can create prompt templates, turn your ideas into reality! Read this: [ChatGPT Prompt Engineering Tips: Zero, One and Few Shot Prompting](https://www.allabtai.com/prompt-engineering-tips-zero-one-and-few-shot-prompting/).

## 主要功能

- 在 1 分钟内使用 Vercel **免费一键部署**
- 提供体积极小（~5MB）的跨平台客户端（Linux/Windows/MacOS）, [下载地址](https://github.com/Yidadaa/ChatGPT-Next-Web/releases)
- 完整的 Markdown 支持：LaTex 公式、Mermaid 流程图、代码高亮等等
- 精心设计的 UI，响应式设计，支持深色模式，支持 PWA
- 极快的首屏加载速度（~100kb），支持流式响应
- 隐私安全，所有数据保存在用户浏览器本地
- 预制角色功能（面具），方便地创建、分享和调试你的个性化对话
- 海量的内置 prompt 列表，来自[中文](https://github.com/PlexPt/awesome-chatgpt-prompts-zh)和[英文](https://github.com/f/awesome-chatgpt-prompts)
- 自动压缩上下文聊天记录，在节省 Token 的同时支持超长对话
- 多国语言支持：English, 简体中文, 繁体中文, 日本語, Español, Italiano, Türkçe, Deutsch, Tiếng Việt, Русский, Čeština, 한국어, Indonesia
- 拥有自己的域名？好上加好，绑定后即可在任何地方**无障碍**快速访问

## 开发计划

- [x] 为每个对话设置系统 Prompt [#138](https://github.com/Yidadaa/ChatGPT-Next-Web/issues/138)
- [x] 允许用户自行编辑内置 Prompt 列表
- [x] 预制角色：使用预制角色快速定制新对话 [#993](https://github.com/Yidadaa/ChatGPT-Next-Web/issues/993)
- [x] 分享为图片，分享到 ShareGPT 链接 [#1741](https://github.com/Yidadaa/ChatGPT-Next-Web/pull/1741)
- [x] 使用 tauri 打包桌面应用
- [x] 支持自部署的大语言模型：开箱即用 [RWKV-Runner](https://github.com/josStorer/RWKV-Runner) ，服务端部署 [LocalAI 项目](https://github.com/go-skynet/LocalAI) llama / gpt4all / rwkv / vicuna / koala / gpt4all-j / cerebras / falcon / dolly 等等，或者使用 [api-for-open-llm](https://github.com/xusenlinzy/api-for-open-llm)
- [ ] 插件机制，支持联网搜索、计算器、调用其他平台 api [#165](https://github.com/Yidadaa/ChatGPT-Next-Web/issues/165)

## 最新动态

- 🚀 v2.0 已经发布，现在你可以使用面具功能快速创建预制对话了！ 了解更多： [ChatGPT 提示词高阶技能：零次、一次和少样本提示](https://github.com/Yidadaa/ChatGPT-Next-Web/issues/138)。
- 💡 想要更方便地随时随地使用本项目？可以试下这款桌面插件：https://github.com/mushan0x0/AI0x0.com
- 🚀 v2.7 现在可以将会话分享为图片了，也可以分享到 ShareGPT 的在线链接。
- 🚀 v2.8 发布了横跨 Linux/Windows/MacOS 的体积极小的客户端。
- 🚀 v2.9.11 现在可以使用自定义 Azure 服务了。

## Get Started

> [简体中文 > 如何开始使用](./README_CN.md#开始使用)

1. Get [OpenAI API Key](https://platform.openai.com/account/api-keys);
2. Click
   [![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FYidadaa%2FChatGPT-Next-Web&env=OPENAI_API_KEY&env=CODE&project-name=chatgpt-next-web&repository-name=ChatGPT-Next-Web), remember that `CODE` is your page password;
3. Enjoy :)

## FAQ

[简体中文 > 常见问题](./docs/faq-cn.md)

[English > FAQ](./docs/faq-en.md)

## Keep Updated

> [简体中文 > 如何保持代码更新](./README_CN.md#保持更新)

If you have deployed your own project with just one click following the steps above, you may encounter the issue of "Updates Available" constantly showing up. This is because Vercel will create a new project for you by default instead of forking this project, resulting in the inability to detect updates correctly.

We recommend that you follow the steps below to re-deploy:

- Delete the original repository;
- Use the fork button in the upper right corner of the page to fork this project;
- Choose and deploy in Vercel again, [please see the detailed tutorial](./docs/vercel-cn.md).

### Enable Automatic Updates

> If you encounter a failure of Upstream Sync execution, please manually sync fork once.

After forking the project, due to the limitations imposed by GitHub, you need to manually enable Workflows and Upstream Sync Action on the Actions page of the forked project. Once enabled, automatic updates will be scheduled every hour:

![Automatic Updates](./docs/images/enable-actions.jpg)

![Enable Automatic Updates](./docs/images/enable-actions-sync.jpg)

### Manually Updating Code

If you want to update instantly, you can check out the [GitHub documentation](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork) to learn how to synchronize a forked project with upstream code.

You can star or watch this project or follow author to get release notifications in time.

## Access Password

> [简体中文 > 如何增加访问密码](./README_CN.md#配置页面访问密码)

This project provides limited access control. Please add an environment variable named `CODE` on the vercel environment variables page. The value should be passwords separated by comma like this:

```
code1,code2,code3
```

After adding or modifying this environment variable, please redeploy the project for the changes to take effect.

## Environment Variables

> [简体中文 > 如何配置 api key、访问密码、接口代理](./README_CN.md#环境变量)

### `CODE` (optional)

Access password, separated by comma.

### `OPENAI_API_KEY` (required)

Your openai api key, join multiple api keys with comma.

### `BASE_URL` (optional)

> Default: `https://api.openai.com`

> Examples: `http://your-openai-proxy.com`

Override openai api request base url.

### `OPENAI_ORG_ID` (optional)

Specify OpenAI organization ID.

### `AZURE_URL` (optional)

> Example: https://{azure-resource-url}/openai/deployments/{deploy-name}

Azure deploy url.

### `AZURE_API_KEY` (optional)

Azure Api Key.

### `AZURE_API_VERSION` (optional)

Azure Api Version, find it at [Azure Documentation](https://learn.microsoft.com/en-us/azure/ai-services/openai/reference#chat-completions).

### `GOOGLE_API_KEY` (optional)

Google Gemini Pro Api Key.

### `GOOGLE_URL` (optional)

Google Gemini Pro Api Url.

### `HIDE_USER_API_KEY` (optional)

> Default: Empty

If you do not want users to input their own API key, set this value to 1.

### `DISABLE_GPT4` (optional)

> Default: Empty

If you do not want users to use GPT-4, set this value to 1.

### `ENABLE_BALANCE_QUERY` (optional)

> Default: Empty

If you do want users to query balance, set this value to 1, or you should set it to 0.

### `DISABLE_FAST_LINK` (optional)

> Default: Empty

If you want to disable parse settings from url, set this to 1.

### `CUSTOM_MODELS` (optional)

> Default: Empty
> Example: `+llama,+claude-2,-gpt-3.5-turbo,gpt-4-1106-preview=gpt-4-turbo` means add `llama, claude-2` to model list, and remove `gpt-3.5-turbo` from list, and display `gpt-4-1106-preview` as `gpt-4-turbo`.

To control custom models, use `+` to add a custom model, use `-` to hide a model, use `name=displayName` to customize model name, separated by comma.

User `-all` to disable all default models, `+all` to enable all default models.

## Requirements

NodeJS >= 18, Docker >= 20

## Development

> [简体中文 > 如何进行二次开发](./README_CN.md#开发)

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/Yidadaa/ChatGPT-Next-Web)

Before starting development, you must create a new `.env.local` file at project root, and place your api key into it:

```
OPENAI_API_KEY=<your api key here>

# if you are not able to access openai service, use this BASE_URL
BASE_URL=https://chatgpt1.nextweb.fun/api/proxy
```

### Local Development

```shell
# 1. install nodejs and yarn first
# 2. config local env vars in `.env.local`
# 3. run
yarn install
yarn dev
```

## Deployment

> [简体中文 > 如何部署到私人服务器](./README_CN.md#部署)

### Docker (Recommended)

```shell
docker pull yidadaa/chatgpt-next-web

docker run -d -p 3000:3000 \
   -e OPENAI_API_KEY=sk-xxxx \
   -e CODE=your-password \
   yidadaa/chatgpt-next-web
```

You can start service behind a proxy:

```shell
docker run -d -p 3000:3000 \
   -e OPENAI_API_KEY=sk-xxxx \
   -e CODE=your-password \
   -e PROXY_URL=http://localhost:7890 \
   yidadaa/chatgpt-next-web
```

If your proxy needs password, use:

```shell
-e PROXY_URL="http://127.0.0.1:7890 user pass"
```

### Shell

```shell
bash <(curl -s https://raw.githubusercontent.com/Yidadaa/ChatGPT-Next-Web/main/scripts/setup.sh)
```

## Synchronizing Chat Records (UpStash)

| [简体中文](./docs/synchronise-chat-logs-cn.md) | [English](./docs/synchronise-chat-logs-en.md) | [Italiano](./docs/synchronise-chat-logs-es.md) | [日本語](./docs/synchronise-chat-logs-ja.md) | [한국어](./docs/synchronise-chat-logs-ko.md)

## Documentation

> Please go to the [docs][./docs] directory for more documentation instructions.

- [Deploy with cloudflare (Deprecated)](./docs/cloudflare-pages-en.md)
- [Frequent Ask Questions](./docs/faq-en.md)
- [How to add a new translation](./docs/translation.md)
- [How to use Vercel (No English)](./docs/vercel-cn.md)
- [User Manual (Only Chinese, WIP)](./docs/user-manual-cn.md)

## Screenshots

![Settings](./docs/images/settings.png)

![More](./docs/images/more.png)

## Translation

If you want to add a new translation, read this [document](./docs/translation.md).

## Donation

[Buy Me a Coffee](https://www.buymeacoffee.com/yidadaa)

## Special Thanks

### Sponsor

> 仅列出捐赠金额 >= 100RMB 的用户。

[@mushan0x0](https://github.com/mushan0x0)
[@ClarenceDan](https://github.com/ClarenceDan)
[@zhangjia](https://github.com/zhangjia)
[@hoochanlon](https://github.com/hoochanlon)
[@relativequantum](https://github.com/relativequantum)
[@desenmeng](https://github.com/desenmeng)
[@webees](https://github.com/webees)
[@chazzhou](https://github.com/chazzhou)
[@hauy](https://github.com/hauy)
[@Corwin006](https://github.com/Corwin006)
[@yankunsong](https://github.com/yankunsong)
[@ypwhs](https://github.com/ypwhs)
[@fxxxchao](https://github.com/fxxxchao)
[@hotic](https://github.com/hotic)
[@WingCH](https://github.com/WingCH)
[@jtung4](https://github.com/jtung4)
[@micozhu](https://github.com/micozhu)
[@jhansion](https://github.com/jhansion)
[@Sha1rholder](https://github.com/Sha1rholder)
[@AnsonHyq](https://github.com/AnsonHyq)
[@synwith](https://github.com/synwith)
[@piksonGit](https://github.com/piksonGit)
[@ouyangzhiping](https://github.com/ouyangzhiping)
[@wenjiavv](https://github.com/wenjiavv)
[@LeXwDeX](https://github.com/LeXwDeX)
[@Licoy](https://github.com/Licoy)
[@shangmin2009](https://github.com/shangmin2009)

### Contributors

<a href="https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ChatGPTNextWeb/ChatGPT-Next-Web" />
</a>

## LICENSE

[MIT](https://opensource.org/license/mit/)


```
ChatGPT-Next-Web-2.10.3
├─ .babelrc
├─ .dockerignore
├─ .eslintignore
├─ .eslintrc.json
├─ .husky
│  └─ pre-commit
├─ .lintstagedrc.json
├─ .prettierrc.js
├─ app
│  ├─ api
│  │  ├─ auth.ts
│  │  ├─ common.ts
│  │  ├─ config
│  │  │  └─ route.ts
│  │  ├─ cors
│  │  │  └─ [...path]
│  │  │     └─ route.ts
│  │  ├─ google
│  │  │  └─ [...path]
│  │  │     └─ route.ts
│  │  └─ openai
│  │     └─ [...path]
│  │        └─ route.ts
│  ├─ azure.ts
│  ├─ client
│  │  ├─ api.ts
│  │  ├─ controller.ts
│  │  └─ platforms
│  │     ├─ google.ts
│  │     └─ openai.ts
│  ├─ command.ts
│  ├─ components
│  │  ├─ auth.module.scss
│  │  ├─ auth.tsx
│  │  ├─ button.module.scss
│  │  ├─ button.tsx
│  │  ├─ chat-list.tsx
│  │  ├─ chat.module.scss
│  │  ├─ chat.tsx
│  │  ├─ emoji.tsx
│  │  ├─ error.tsx
│  │  ├─ exporter.module.scss
│  │  ├─ exporter.tsx
│  │  ├─ home.module.scss
│  │  ├─ home.tsx
│  │  ├─ input-range.module.scss
│  │  ├─ input-range.tsx
│  │  ├─ markdown.tsx
│  │  ├─ mask.module.scss
│  │  ├─ mask.tsx
│  │  ├─ message-selector.module.scss
│  │  ├─ message-selector.tsx
│  │  ├─ model-config.tsx
│  │  ├─ new-chat.module.scss
│  │  ├─ new-chat.tsx
│  │  ├─ settings.module.scss
│  │  ├─ settings.tsx
│  │  ├─ sidebar.tsx
│  │  ├─ ui-lib.module.scss
│  │  └─ ui-lib.tsx
│  ├─ config
│  │  ├─ client.ts
│  │  └─ server.ts
│  ├─ constant.ts
│  ├─ global.d.ts
│  ├─ icons
│  │  ├─ add.svg
│  │  ├─ auto.svg
│  │  ├─ black-bot.svg
│  │  ├─ bot.png
│  │  ├─ bot.svg
│  │  ├─ bottom.svg
│  │  ├─ brain.svg
│  │  ├─ break.svg
│  │  ├─ cancel.svg
│  │  ├─ chat-settings.svg
│  │  ├─ chat.svg
│  │  ├─ chatgpt.png
│  │  ├─ chatgpt.svg
│  │  ├─ clear.svg
│  │  ├─ close.svg
│  │  ├─ cloud-fail.svg
│  │  ├─ cloud-success.svg
│  │  ├─ config.svg
│  │  ├─ confirm.svg
│  │  ├─ connection.svg
│  │  ├─ copy.svg
│  │  ├─ dark.svg
│  │  ├─ delete.svg
│  │  ├─ down.svg
│  │  ├─ download.svg
│  │  ├─ drag.svg
│  │  ├─ edit.svg
│  │  ├─ export.svg
│  │  ├─ eye-off.svg
│  │  ├─ eye.svg
│  │  ├─ github.svg
│  │  ├─ left.svg
│  │  ├─ light.svg
│  │  ├─ lightning.svg
│  │  ├─ mask.svg
│  │  ├─ max.svg
│  │  ├─ menu.svg
│  │  ├─ min.svg
│  │  ├─ pause.svg
│  │  ├─ pin.svg
│  │  ├─ plugin.svg
│  │  ├─ prompt.svg
│  │  ├─ reload.svg
│  │  ├─ rename.svg
│  │  ├─ return.svg
│  │  ├─ robot.svg
│  │  ├─ send-white.svg
│  │  ├─ settings.svg
│  │  ├─ share.svg
│  │  ├─ three-dots.svg
│  │  └─ upload.svg
│  ├─ layout.tsx
│  ├─ locales
│  │  ├─ ar.ts
│  │  ├─ bn.ts
│  │  ├─ cn.ts
│  │  ├─ cs.ts
│  │  ├─ de.ts
│  │  ├─ en.ts
│  │  ├─ es.ts
│  │  ├─ fr.ts
│  │  ├─ id.ts
│  │  ├─ index.ts
│  │  ├─ it.ts
│  │  ├─ jp.ts
│  │  ├─ ko.ts
│  │  ├─ no.ts
│  │  ├─ pt.ts
│  │  ├─ ru.ts
│  │  ├─ sk.ts
│  │  ├─ tr.ts
│  │  ├─ tw.ts
│  │  └─ vi.ts
│  ├─ masks
│  │  ├─ cn.ts
│  │  ├─ en.ts
│  │  ├─ index.ts
│  │  └─ typing.ts
│  ├─ page.tsx
│  ├─ polyfill.ts
│  ├─ store
│  │  ├─ access.ts
│  │  ├─ chat.ts
│  │  ├─ config.ts
│  │  ├─ index.ts
│  │  ├─ mask.ts
│  │  ├─ prompt.ts
│  │  ├─ sync.ts
│  │  └─ update.ts
│  ├─ styles
│  │  ├─ animation.scss
│  │  ├─ globals.scss
│  │  ├─ highlight.scss
│  │  ├─ markdown.scss
│  │  └─ window.scss
│  ├─ typing.ts
│  ├─ utils
│  │  ├─ clone.ts
│  │  ├─ cloud
│  │  │  ├─ index.ts
│  │  │  ├─ upstash.ts
│  │  │  └─ webdav.ts
│  │  ├─ cors.ts
│  │  ├─ format.ts
│  │  ├─ hooks.ts
│  │  ├─ merge.ts
│  │  ├─ model.ts
│  │  ├─ store.ts
│  │  ├─ sync.ts
│  │  └─ token.ts
│  └─ utils.ts
├─ CODE_OF_CONDUCT.md
├─ docker-compose.yml
├─ Dockerfile
├─ docs
│  ├─ cloudflare-pages-cn.md
│  ├─ cloudflare-pages-en.md
│  ├─ cloudflare-pages-es.md
│  ├─ cloudflare-pages-ja.md
│  ├─ cloudflare-pages-ko.md
│  ├─ faq-cn.md
│  ├─ faq-en.md
│  ├─ faq-es.md
│  ├─ faq-ja.md
│  ├─ faq-ko.md
│  ├─ images
│  │  ├─ cover.png
│  │  ├─ enable-actions-sync.jpg
│  │  ├─ enable-actions.jpg
│  │  ├─ head-cover.png
│  │  ├─ icon.svg
│  │  ├─ more.png
│  │  ├─ settings.png
│  │  ├─ upstash-1.png
│  │  ├─ upstash-2.png
│  │  ├─ upstash-3.png
│  │  ├─ upstash-4.png
│  │  ├─ upstash-5.png
│  │  ├─ upstash-6.png
│  │  ├─ upstash-7.png
│  │  └─ vercel
│  │     ├─ vercel-create-1.jpg
│  │     ├─ vercel-create-2.jpg
│  │     ├─ vercel-create-3.jpg
│  │     ├─ vercel-env-edit.jpg
│  │     └─ vercel-redeploy.jpg
│  ├─ synchronise-chat-logs-cn.md
│  ├─ synchronise-chat-logs-en.md
│  ├─ synchronise-chat-logs-es.md
│  ├─ synchronise-chat-logs-ja.md
│  ├─ synchronise-chat-logs-ko.md
│  ├─ translation.md
│  ├─ user-manual-cn.md
│  ├─ vercel-cn.md
│  ├─ vercel-es.md
│  ├─ vercel-ja.md
│  └─ vercel-ko.md
├─ LICENSE
├─ next.config.mjs
├─ package.json
├─ public
│  ├─ android-chrome-192x192.png
│  ├─ android-chrome-512x512.png
│  ├─ apple-touch-icon.png
│  ├─ favicon-16x16.png
│  ├─ favicon-32x32.png
│  ├─ favicon.ico
│  ├─ macos.png
│  ├─ prompts.json
│  ├─ robots.txt
│  ├─ serviceWorker.js
│  ├─ serviceWorkerRegister.js
│  └─ site.webmanifest
├─ README.md
├─ README_CN.md
├─ scripts
│  ├─ delete-deployment-preview.sh
│  ├─ fetch-prompts.mjs
│  ├─ init-proxy.sh
│  ├─ proxychains.template.conf
│  └─ setup.sh
├─ src-tauri
│  ├─ Cargo.lock
│  ├─ Cargo.toml
│  ├─ icons
│  │  ├─ 128x128.png
│  │  ├─ 128x128@2x.png
│  │  ├─ 32x32.png
│  │  ├─ icon.icns
│  │  ├─ icon.ico
│  │  ├─ icon.png
│  │  ├─ Square107x107Logo.png
│  │  ├─ Square142x142Logo.png
│  │  ├─ Square150x150Logo.png
│  │  ├─ Square284x284Logo.png
│  │  ├─ Square30x30Logo.png
│  │  ├─ Square310x310Logo.png
│  │  ├─ Square44x44Logo.png
│  │  ├─ Square71x71Logo.png
│  │  ├─ Square89x89Logo.png
│  │  └─ StoreLogo.png
│  ├─ src
│  │  └─ main.rs
│  └─ tauri.conf.json
├─ tsconfig.json
├─ vercel.json
└─ yarn.lock

```
```
ChatGPT-Next-Web-2.10.3
├─ .babelrc
├─ .dockerignore
├─ .eslintignore
├─ .eslintrc.json
├─ .husky
│  └─ pre-commit
├─ .lintstagedrc.json
├─ .prettierrc.js
├─ app
│  ├─ api
│  │  ├─ auth.ts
│  │  ├─ common.ts
│  │  ├─ config
│  │  │  └─ route.ts
│  │  ├─ cors
│  │  │  └─ [...path]
│  │  │     └─ route.ts
│  │  ├─ google
│  │  │  └─ [...path]
│  │  │     └─ route.ts
│  │  └─ openai
│  │     └─ [...path]
│  │        └─ route.ts
│  ├─ azure.ts
│  ├─ client
│  │  ├─ api.ts
│  │  ├─ controller.ts
│  │  └─ platforms
│  │     ├─ google.ts
│  │     └─ openai.ts
│  ├─ command.ts
│  ├─ components
│  │  ├─ auth.module.scss
│  │  ├─ auth.tsx
│  │  ├─ button.module.scss
│  │  ├─ button.tsx
│  │  ├─ chat-list.tsx
│  │  ├─ chat.module.scss
│  │  ├─ chat.tsx
│  │  ├─ emoji.tsx
│  │  ├─ error.tsx
│  │  ├─ exporter.module.scss
│  │  ├─ exporter.tsx
│  │  ├─ home.module.scss
│  │  ├─ home.tsx
│  │  ├─ input-range.module.scss
│  │  ├─ input-range.tsx
│  │  ├─ markdown.tsx
│  │  ├─ mask.module.scss
│  │  ├─ mask.tsx
│  │  ├─ message-selector.module.scss
│  │  ├─ message-selector.tsx
│  │  ├─ model-config.tsx
│  │  ├─ new-chat.module.scss
│  │  ├─ new-chat.tsx
│  │  ├─ settings.module.scss
│  │  ├─ settings.tsx
│  │  ├─ sidebar.tsx
│  │  ├─ ui-lib.module.scss
│  │  └─ ui-lib.tsx
│  ├─ config
│  │  ├─ client.ts
│  │  └─ server.ts
│  ├─ constant.ts
│  ├─ global.d.ts
│  ├─ icons
│  │  ├─ add.svg
│  │  ├─ auto.svg
│  │  ├─ black-bot.svg
│  │  ├─ bot.png
│  │  ├─ bot.svg
│  │  ├─ bottom.svg
│  │  ├─ brain.svg
│  │  ├─ break.svg
│  │  ├─ cancel.svg
│  │  ├─ chat-settings.svg
│  │  ├─ chat.svg
│  │  ├─ chatgpt.png
│  │  ├─ chatgpt.svg
│  │  ├─ clear.svg
│  │  ├─ close.svg
│  │  ├─ cloud-fail.svg
│  │  ├─ cloud-success.svg
│  │  ├─ config.svg
│  │  ├─ confirm.svg
│  │  ├─ connection.svg
│  │  ├─ copy.svg
│  │  ├─ dark.svg
│  │  ├─ delete.svg
│  │  ├─ down.svg
│  │  ├─ download.svg
│  │  ├─ drag.svg
│  │  ├─ edit.svg
│  │  ├─ export.svg
│  │  ├─ eye-off.svg
│  │  ├─ eye.svg
│  │  ├─ github.svg
│  │  ├─ left.svg
│  │  ├─ light.svg
│  │  ├─ lightning.svg
│  │  ├─ mask.svg
│  │  ├─ max.svg
│  │  ├─ menu.svg
│  │  ├─ min.svg
│  │  ├─ pause.svg
│  │  ├─ pin.svg
│  │  ├─ plugin.svg
│  │  ├─ prompt.svg
│  │  ├─ reload.svg
│  │  ├─ rename.svg
│  │  ├─ return.svg
│  │  ├─ robot.svg
│  │  ├─ send-white.svg
│  │  ├─ settings.svg
│  │  ├─ share.svg
│  │  ├─ three-dots.svg
│  │  └─ upload.svg
│  ├─ layout.tsx
│  ├─ locales
│  │  ├─ ar.ts
│  │  ├─ bn.ts
│  │  ├─ cn.ts
│  │  ├─ cs.ts
│  │  ├─ de.ts
│  │  ├─ en.ts
│  │  ├─ es.ts
│  │  ├─ fr.ts
│  │  ├─ id.ts
│  │  ├─ index.ts
│  │  ├─ it.ts
│  │  ├─ jp.ts
│  │  ├─ ko.ts
│  │  ├─ no.ts
│  │  ├─ pt.ts
│  │  ├─ ru.ts
│  │  ├─ sk.ts
│  │  ├─ tr.ts
│  │  ├─ tw.ts
│  │  └─ vi.ts
│  ├─ masks
│  │  ├─ cn.ts
│  │  ├─ en.ts
│  │  ├─ index.ts
│  │  └─ typing.ts
│  ├─ page.tsx
│  ├─ polyfill.ts
│  ├─ store
│  │  ├─ access.ts
│  │  ├─ chat.ts
│  │  ├─ config.ts
│  │  ├─ index.ts
│  │  ├─ mask.ts
│  │  ├─ prompt.ts
│  │  ├─ sync.ts
│  │  └─ update.ts
│  ├─ styles
│  │  ├─ animation.scss
│  │  ├─ globals.scss
│  │  ├─ highlight.scss
│  │  ├─ markdown.scss
│  │  └─ window.scss
│  ├─ typing.ts
│  ├─ utils
│  │  ├─ clone.ts
│  │  ├─ cloud
│  │  │  ├─ index.ts
│  │  │  ├─ upstash.ts
│  │  │  └─ webdav.ts
│  │  ├─ cors.ts
│  │  ├─ format.ts
│  │  ├─ hooks.ts
│  │  ├─ merge.ts
│  │  ├─ model.ts
│  │  ├─ store.ts
│  │  ├─ sync.ts
│  │  └─ token.ts
│  └─ utils.ts
├─ CODE_OF_CONDUCT.md
├─ docker-compose.yml
├─ Dockerfile
├─ docs
│  ├─ cloudflare-pages-cn.md
│  ├─ cloudflare-pages-en.md
│  ├─ cloudflare-pages-es.md
│  ├─ cloudflare-pages-ja.md
│  ├─ cloudflare-pages-ko.md
│  ├─ faq-cn.md
│  ├─ faq-en.md
│  ├─ faq-es.md
│  ├─ faq-ja.md
│  ├─ faq-ko.md
│  ├─ images
│  │  ├─ cover.png
│  │  ├─ enable-actions-sync.jpg
│  │  ├─ enable-actions.jpg
│  │  ├─ head-cover.png
│  │  ├─ icon.svg
│  │  ├─ more.png
│  │  ├─ settings.png
│  │  ├─ upstash-1.png
│  │  ├─ upstash-2.png
│  │  ├─ upstash-3.png
│  │  ├─ upstash-4.png
│  │  ├─ upstash-5.png
│  │  ├─ upstash-6.png
│  │  ├─ upstash-7.png
│  │  └─ vercel
│  │     ├─ vercel-create-1.jpg
│  │     ├─ vercel-create-2.jpg
│  │     ├─ vercel-create-3.jpg
│  │     ├─ vercel-env-edit.jpg
│  │     └─ vercel-redeploy.jpg
│  ├─ synchronise-chat-logs-cn.md
│  ├─ synchronise-chat-logs-en.md
│  ├─ synchronise-chat-logs-es.md
│  ├─ synchronise-chat-logs-ja.md
│  ├─ synchronise-chat-logs-ko.md
│  ├─ translation.md
│  ├─ user-manual-cn.md
│  ├─ vercel-cn.md
│  ├─ vercel-es.md
│  ├─ vercel-ja.md
│  └─ vercel-ko.md
├─ LICENSE
├─ next.config.mjs
├─ package.json
├─ public
│  ├─ android-chrome-192x192.png
│  ├─ android-chrome-512x512.png
│  ├─ apple-touch-icon.png
│  ├─ favicon-16x16.png
│  ├─ favicon-32x32.png
│  ├─ favicon.ico
│  ├─ macos.png
│  ├─ prompts.json
│  ├─ robots.txt
│  ├─ serviceWorker.js
│  ├─ serviceWorkerRegister.js
│  └─ site.webmanifest
├─ README.md
├─ README_CN.md
├─ scripts
│  ├─ delete-deployment-preview.sh
│  ├─ fetch-prompts.mjs
│  ├─ init-proxy.sh
│  ├─ proxychains.template.conf
│  └─ setup.sh
├─ src-tauri
│  ├─ Cargo.lock
│  ├─ Cargo.toml
│  ├─ icons
│  │  ├─ 128x128.png
│  │  ├─ 128x128@2x.png
│  │  ├─ 32x32.png
│  │  ├─ icon.icns
│  │  ├─ icon.ico
│  │  ├─ icon.png
│  │  ├─ Square107x107Logo.png
│  │  ├─ Square142x142Logo.png
│  │  ├─ Square150x150Logo.png
│  │  ├─ Square284x284Logo.png
│  │  ├─ Square30x30Logo.png
│  │  ├─ Square310x310Logo.png
│  │  ├─ Square44x44Logo.png
│  │  ├─ Square71x71Logo.png
│  │  ├─ Square89x89Logo.png
│  │  └─ StoreLogo.png
│  ├─ src
│  │  └─ main.rs
│  └─ tauri.conf.json
├─ tsconfig.json
├─ vercel.json
└─ yarn.lock

```