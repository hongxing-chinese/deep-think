## 🌟 简介

Deep Think 是一个基于大型语言模型（LLM）的深度思考工具，它能够帮助你解决复杂问题、进行深入分析和研究。该项目具有以下特点：

- 支持多种 AI 模型提供商（Google、OpenAI、Anthropic 等）
- 提供两种深度思考模式：
  - **Deep Think**: 严谨推理与多轮验证模式
  - **Ultra Think**: 多角度并行探索模式
- 支持实时流式响应和渐进式展示
- 内置联网搜索功能，减少模型幻觉
- 支持知识库管理，可以上传和管理本地资源
- 完整的历史记录管理
- 支持多语言界面（中文、英文、西班牙语等）
- 响应式设计，支持移动端使用
- 支持 PWA 应用安装

参考： https://github.com/u14app/deep-research / https://github.com/lyang36/IMO25 实现

拥有 deep-research 的全部功能，工作流采用 IMO 25 魔改版，优化了对通用任务的适应性

## 🛠️ 功能特性

### 🔍 深度研究模式

Deep Think 提供强大的深度研究功能：

1. **研究主题定义** - 明确你要研究的问题
2. **问题提问** - 系统会根据主题提出相关问题
3. **信息收集** - 自动联网搜索相关信息
4. **研究报告生成** - 整理信息并生成详细报告

### 💭 深度思考模式

提供两种不同的深度思考模式：

- **Deep Think 模式**：采用迭代改进和验证的方法，逐步完善解决方案
- **Ultra Think 模式**：并行多个智能体从不同角度探索问题，然后综合结果

### 📚 知识库管理

- 上传和管理本地文件（PDF、TXT、DOC等）
- 浏览器本地存储，保护隐私
- 在研究过程中引用知识库内容

### ⚙️ 模型支持

支持多种主流 AI 模型提供商：

- Google Gemini
- OpenAI GPT
- Anthropic Claude
- DeepSeek
- XAI Grok
- Mistral
- Azure OpenAI
- OpenRouter
- Ollama
- 以及其他兼容 OpenAI 接口的模型

### 🔍 搜索提供商

支持多种网络搜索服务：

- 模型内置搜索
- Tavily
- FireCrawl
- Exa
- Bocha
- SearXNG

## 📖 使用指南

### 基本使用流程

1. 设置 AI 模型和相关参数
2. 输入你想研究或思考的问题
3. 选择合适的思考模式（Deep Think 或 Ultra Think）
4. 等待系统完成分析和处理
5. 查看生成的结果和报告

### 高级功能

- **历史记录管理**：保存和加载之前的研究结果
- **知识库集成**：上传本地文件作为额外知识源
- **自定义提示词**：在研究过程中添加自己的想法和要求
- **多语言支持**：界面和输出支持多种语言

## 🧩 技术架构

- **前端框架**：Next.js 15
- **UI 组件库**：Tailwind CSS + shadcn/ui
- **状态管理**：Zustand
- **国际化**：i18next
- **构建工具**：TypeScript + ESLint
- **部署方式**：支持 Vercel、Cloudflare Pages 等平台

## 📄 许可证

本项目采用 MIT 许可证，详情请见 [LICENSE](./LICENSE) 文件。