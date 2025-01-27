# AI 春联生成器

![ai_couplets](https://socialify.git.ci/HoshinoSuzumi/ai_couplets/image?custom_description=%E8%BE%93%E5%85%A5%E4%B8%80%E5%8F%A5%E8%AF%9D%E5%B0%B1%E5%8F%AF%E4%BB%A5%E7%94%9F%E6%88%90%E4%B8%80%E5%89%AF%E5%AF%B9%E8%81%94%EF%BC%81%E5%8A%A9%E4%BD%A0%E6%88%90%E4%B8%BA%E5%AF%B9%E5%AF%B9%E8%81%94%E9%AB%98%E6%89%8B&description=1&font=Raleway&forks=1&logo=https%3A%2F%2Fraw.githubusercontent.com%2FHoshinoSuzumi%2Fai_couplets%2Frefs%2Fheads%2Fmain%2Fpublic%2Fandroid-chrome-192x192.png&name=1&pattern=Solid&stargazers=1&theme=Auto)

## 简介 Introduction

只需要输入你想要的主题就可以帮你生成一副春联的东西。**马上成为春联领域高手！**

[立即尝试](https://couplet.bh8.ga/)

## 截图 Screenshot

![screenshot](/public/screenshot.png)

## 部署 Deployment

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FHoshinoSuzumi%2Fai_couplets&env=OPENAI_ENDPOINT,OPENAI_MODEL,OPENAI_API_KEY,MAX_TOKENS&envDescription=OPENAI_API_KEY%20is%20required.&project-name=ai-couplets&repository-name=ai-couplets)

1. 在 [DeepSeek 控制台](https://platform.deepseek.com/api_keys) 创建 API KEY 并保存
2. 点击上方的一键部署按钮，填写项目名
3. 填写环境变量，点击 Deploy 直接部署

### 环境变量 Environments

| 变量名          | 描述                      | 示例值                  |
|-----------------|---------------------------|-------------------------|
| OPENAI_ENDPOINT | OpenAI API 的访问端点     | `https://api.deepseek.com/v1`|
| OPENAI_MODEL    | 使用的 OpenAI 模型名称    | `deepseek-chat`      |
| OPENAI_API_KEY  | OpenAI 的 API 密钥        | `your-api-key`          |
| MAX_TOKENS      | 生成文本的最大 token 数量 | `100`                   |

## 开发 Development

```bash
# 安装依赖
pnpm install
# 启动开发服务器
pnpm dev

# 构建
pnpm build
```

## 赞助 Sponsor

Buy me a coffee~

[![爱发电](https://afdian.moeci.com/11/badge.svg)](https://afdian.com/a/hoshino_suzumi)
[![Support me on Patreon](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Fshieldsio-patreon.vercel.app%2Fapi%3Fusername%3D5ANK41%26type%3Dpledges&style=flat)](https://patreon.com/5ANK41)
