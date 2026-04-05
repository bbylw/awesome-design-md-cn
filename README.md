<a href="https://github.com/VoltAgent/voltagent">
     <img width="1500" height="801" alt="claude-skills" src="https://github.com/user-attachments/assets/d012a0d2-cec3-4630-ba5e-acc339dbe6cf" />
</a>


<br/>
<br/>

<div align="center">
    <strong>精选的 DESIGN.md 文件合集，灵感来源于开发者专注的网站。</strong>
    <br />
    <sub>汉化自 <a href="https://github.com/VoltAgent/awesome-design-md">VoltAgent/awesome-design-md</a></sub>
    <br />
    <br />

</div>

<div align="center">

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![DESIGN.md Count](https://img.shields.io/badge/DESIGN.md%20count-55-10b981?style=classic)
[![Last Update](https://img.shields.io/github/last-commit/VoltAgent/awesome-design-md?label=Last%20update&style=classic)](https://github.com/VoltAgent/awesome-design-md)
[![Discord](https://img.shields.io/discord/1361559153780195478.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://s.voltagent.dev/discord)

</div>
</div>

# Awesome DESIGN.md

将 DESIGN.md 复制到你的项目中，告诉你的 AI 代理"构建一个看起来像这样的页面"，即可获得完美匹配像素的 UI。


## 什么是 DESIGN.md？

[DESIGN.md](https://stitch.withgoogle.com/docs/design-md/overview/) 是 Google Stitch 引入的新概念。一个纯文本的设计系统文档，AI 代理通过阅读它来生成一致的 UI。

它只是一个 markdown 文件。无需导出 Figma，无需 JSON schema，无需特殊工具。将它放入项目根目录，任何 AI 编码代理或 Google Stitch 都能立即理解你的 UI 应该如何呈现。Markdown 是 LLM 最擅长阅读的格式，因此无需解析或配置。

| 文件 | 谁读取它 | 它定义了什么 |
|------|---------|-----------------|
| `AGENTS.md` | 编码代理 | 如何构建项目 |
| `DESIGN.md` | 设计代理 | 项目的外观和感觉 |

**本仓库提供了可直接使用的 DESIGN.md 文件**，这些文件从真实网站中提取。



## 每个 DESIGN.md 包含什么

每个文件都遵循 [Stitch DESIGN.md 格式](https://stitch.withgoogle.com/docs/design-md/format/) 并包含扩展部分：

| # | 章节 | 它捕获什么 |
|---|---------|-----------------|
| 1 | 视觉主题与氛围 | 情绪、密度、设计哲学 |
| 2 | 调色板与角色 | 语义名称 + 十六进制值 + 功能角色 |
| 3 | 字体规则 | 字体系列、完整层级表 |
| 4 | 组件样式 | 按钮、卡片、输入框、导航及其状态 |
| 5 | 布局原则 | 间距刻度、网格、留白哲学 |
| 6 | 深度与高程 | 阴影系统、表面层级 |
| 7 | 应该与不应该 | 设计护栏和反模式 |
| 8 | 响应式行为 | 断点、触摸目标、折叠策略 |
| 9 | 代理提示指南 | 快速颜色参考、即用型提示 |

每个站点包括：

| 文件 | 用途 |
|------|---------|
| `DESIGN.md` | 设计系统（代理读取的内容） |
| `preview.html` | 视觉目录，展示色板、字体比例、按钮、卡片 |
| `preview-dark.html` | 相同的目录，但使用深色表面 |

### 如何使用


1. 将站点的 `DESIGN.md` 复制到你的项目根目录
2. 告诉你的 AI 代理使用它。


## 请求 DESIGN.md

[使用此模板打开 GitHub issue](https://github.com/VoltAgent/awesome-design-md/issues/new?template=design-md-request.yml) 来请求为网站生成 DESIGN.md。


## 合集

### AI 与机器学习

- [**Claude**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/claude/) - Anthropic 的 AI 助手。温暖的赤陶强调色，干净的编辑布局
- [**Cohere**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/cohere/) - 企业级 AI 平台。充满活力的渐变，数据丰富的仪表板美学
- [**ElevenLabs**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/elevenlabs/) - AI 语音平台。深色电影感 UI，音频波形美学
- [**Minimax**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/minimax/) - AI 模型提供商。大胆的深色界面，带有霓虹强调
- [**Mistral AI**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/mistral.ai/) - 开源 LLM 提供商。法式工程极简主义，紫色调
- [**Ollama**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/ollama/) - 本地运行 LLM。终端优先，单色简约
- [**OpenCode AI**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/opencode.ai/) - AI 编码平台。开发者中心的深色主题
- [**Replicate**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/replicate/) - 通过 API 运行 ML 模型。干净的白色画布，代码优先
- [**RunwayML**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/runwayml/) - AI 视频生成。电影感深色 UI，媒体丰富的布局
- [**Together AI**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/together.ai/) - 开源 AI 基础设施。技术性，蓝图式设计
- [**VoltAgent**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/voltagent/) - AI 代理框架。虚空黑色画布，祖母绿强调，终端原生
- [**xAI**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/x.ai/) - Elon Musk 的 AI 实验室。鲜明单色，未来主义极简主义

### 开发者工具与平台

- [**Cursor**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/cursor/) - AI 优先的代码编辑器。流畅的深色界面，渐变强调色
- [**Expo**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/expo/) - React Native 平台。深色主题，紧凑字间距，以代码为中心
- [**Linear**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/linear.app/) - 面向工程师的项目管理。超极简，精确，紫色强调
- [**Lovable**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/lovable/) - AI 全栈构建器。俏皮的渐变，友好的开发者美学
- [**Mintlify**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/mintlify/) - 文档平台。干净，绿色强调，阅读优化
- [**PostHog**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/posthog/) - 产品分析。俏皮的刺猬品牌，开发者友好的深色 UI
- [**Raycast**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/raycast/) - 生产力启动器。流畅的深色 chrome，充满活力的渐变强调
- [**Resend**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/resend/) - 面向开发者的邮件 API。极简深色主题，等宽字体强调
- [**Sentry**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/sentry/) - 错误监控。深色仪表板，数据密集，粉紫色强调
- [**Supabase**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/supabase/) - 开源 Firebase 替代品。深祖母绿主题，代码优先
- [**Superhuman**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/superhuman/) - 快速邮件客户端。高级深色 UI，键盘优先，紫色光晕
- [**Vercel**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/vercel/) - 前端部署平台。黑白精确，Geist 字体
- [**Warp**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/warp/) - 现代终端。深色 IDE 类界面，基于块的命令 UI
- [**Zapier**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/zapier/) - 自动化平台。温暖的橙色，友好的插图驱动

### 基础设施与云

- [**ClickHouse**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/clickhouse/) - 快速分析数据库。黄色强调，技术文档风格
- [**Composio**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/composio/) - 工具集成平台。现代深色，带有彩色集成图标
- [**HashiCorp**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/hashicorp/) - 基础设施自动化。企业级干净，黑白
- [**MongoDB**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/mongodb/) - 文档数据库。绿叶品牌，开发者文档焦点
- [**Sanity**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/sanity/) - 无头 CMS。红色强调，内容优先的编辑布局
- [**Stripe**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/stripe/) - 支付基础设施。标志性紫色渐变，weight-300 优雅

### 设计与生产力

- [**Airtable**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/airtable/) - 电子表格-数据库混合体。多彩，友好，结构化数据美学
- [**Cal.com**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/cal/) - 开源调度。干净的中性 UI，面向开发的简约性
- [**Clay**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/clay/) - 创意机构。有机形状，柔和渐变，艺术导向布局
- [**Figma**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/figma/) - 协作设计工具。充满活力的多色，有趣而专业
- [**Framer**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/framer/) - 网站构建器。大胆的黑蓝，动效优先，设计前卫
- [**Intercom**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/intercom/) - 客户消息传递。友好的蓝色调色板，对话式 UI 模式
- [**Miro**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/miro/) - 视觉协作。明亮的黄色强调，无限画布美学
- [**Notion**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/notion/) - 一体化工作区。温暖的极简主义，衬线标题，柔和表面
- [**Pinterest**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/pinterest/) - 视觉发现平台。红色强调，砌体网格，图像优先
- [**Webflow**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/webflow/) - 可视化网站构建器。蓝色强调，精致的营销网站美学

### 金融科技与加密货币

- [**Coinbase**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/coinbase/) - 加密货币交易所。干净的蓝色身份，以信任为中心，机构感
- [**Kraken**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/kraken/) - 加密货币交易平台。紫色强调深色 UI，数据密集的仪表板
- [**Revolut**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/revolut/) - 数字银行。流畅的深色界面，渐变卡片，金融科技精度
- [**Wise**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/wise/) - 国际汇款。明亮的绿色强调，友好而清晰

### 企业与消费者

- [**Airbnb**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/airbnb/) - 旅游市场。温暖的珊瑚强调色，摄影驱动，圆角 UI
- [**Apple**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/apple/) - 消费电子产品。高级留白，SF Pro，电影感图像
- [**BMW**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/bmw/) - 豪华汽车。深色高级表面，精密的德国工程美学
- [**IBM**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/ibm/) - 企业技术。Carbon 设计系统，结构化蓝色调色板
- [**NVIDIA**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/nvidia/) - GPU 计算。绿黑能量，技术力量美学
- [**SpaceX**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/spacex/) - 航天技术。鲜明的黑白，全出血图像，未来主义
- [**Spotify**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/spotify/) - 音乐流媒体。深色背景上的活力绿，大胆字体，专辑艺术驱动
- [**Uber**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/uber/) - 移动出行平台。大胆的黑白，紧凑字体，城市能量



## 贡献

请参阅 [CONTRIBUTING.md](https://github.com/VoltAgent/awesome-design-md/blob/main/CONTRIBUTING.md) 获取指南。

- **改进现有文件**：修复错误的颜色、缺失的标记、薄弱的描述
- **报告问题**：如果看起来有什么不对，请告诉我们

在打开 PR 之前，请先 [打开 issue](https://github.com/VoltAgent/awesome-design-md/issues) 讨论你的想法并获取维护者的反馈。


## 许可证

MIT 许可证 - 请参阅 [LICENSE](https://github.com/VoltAgent/awesome-design-md/blob/main/LICENSE)

本仓库是从公共网站中提取的设计系统文档的精选合集。所有 DESIGN.md 文件均按"原样"提供，不提供任何保证。提取的设计标记代表公开可见的 CSS 值。我们不声称拥有任何站点视觉标识的所有权。这些文档的存在是为了帮助 AI 代理生成一致的 UI。