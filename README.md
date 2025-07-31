# Vertu SEO - 关键词驱动的智能博客创作工具

这是一个基于 Next.js 和 Google Generative AI 的智能SEO工具，可以帮助用户通过关键词分析生成高质量的博客内容创意。

## 功能特性

- 🔍 **关键词搜索**: 使用Google搜索API获取相关内容
- 🤖 **AI驱动**: 基于Google Generative AI生成博客创意
- 🎨 **现代UI**: 使用shadcn/ui组件库构建美观界面
- 📱 **响应式设计**: 支持桌面和移动设备
- 🌐 **多语言支持**: 支持多个目标市场和语言

## 技术栈

- **前端框架**: Next.js 14 (App Router)
- **UI组件**: shadcn/ui + Radix UI
- **样式**: Tailwind CSS
- **AI服务**: Google Generative AI
- **语言**: TypeScript

## 安装和运行

### 1. 安装依赖
```bash
npm install
```

### 2. 运行开发服务器
```bash
npm run dev
```

### 3. 访问应用
打开 [http://localhost:3001](http://localhost:3001) 查看应用。
（如果端口3000被占用，Next.js会自动使用3001端口）

## 使用说明

### 第一步：输入关键词
1. 输入您想要分析的关键词
2. 选择目标市场和语言
3. 设置检索参数
4. 点击"生成创意"

### 第二步：查看博客创意
- **左侧**：显示搜索意图分析和Google搜索结果（参考资料）
- **中间**：展示AI生成的8种不同类型的博客创意
- **右侧**：附加功能区域（文本内容、AI知识库）

## 项目结构

```
vertu-seo/
├── app/                    # Next.js App Router
├── components/ui/          # shadcn/ui组件
├── lib/                   # 工具函数和服务
└── ...配置文件
``` 
