# 业钊下载站文档

> 基于 VitePress 构建的现代化文档站点

## 🚀 快速开始

### 环境要求

- Node.js 18+
- npm 或 yarn

### 安装依赖

```bash
npm install
```

### 开发模式

```bash
npm run dev
```

访问 `http://localhost:25173` 查看文档站点。

### 构建生产版本

```bash
npm run build
```

构建后的文件位于 `docs/.vitepress/dist` 目录。

### 预览生产版本

```bash
npm run preview
```

## 📁 项目结构

```
├── docs/                          # 文档根目录
│   ├── .vitepress/                # VitePress 配置
│   │   ├── config.mts            # 主配置文件
│   │   └── theme/                # 自定义主题
│   │       ├── index.ts          # 主题入口
│   │       └── custom.css        # 自定义样式
│   ├── getting-started/          # 入门指南
│   ├── troubleshooting/          # 问题解答
│   ├── console-commands/         # 控制台指令
│   └── public/                   # 静态资源
├── .github/workflows/            # GitHub Actions
└── package.json                  # 项目配置
```

## 🎨 特性

- ✨ **现代化设计** - 基于 VitePress 的美观界面
- 🔍 **全文搜索** - 内置搜索功能
- 📱 **响应式设计** - 完美适配移动设备
- 🌙 **暗色主题** - 支持明暗主题切换
- ⚡ **快速加载** - Vite 驱动的极速构建
- 🔗 **SEO 友好** - 静态站点生成，搜索引擎优化

## 📝 编写文档

### 添加新页面

1. 在相应目录下创建 `.md` 文件
2. 在 `docs/.vitepress/config.mts` 中添加导航和侧边栏配置
3. 使用标准 Markdown 语法编写内容

### Markdown 增强

VitePress 支持多种 Markdown 增强功能：

```markdown
::: tip 提示
这是一个提示框
:::

::: warning 警告
这是一个警告框
:::

::: danger 危险
这是一个危险提示框
:::
```

### 自定义容器

支持自定义样式的容器和组件。

## 🚀 部署

### 构建生产版本

```bash
npm run build
```

构建后的文件位于 `docs/.vitepress/dist` 目录，可以部署到任何静态网站托管服务

## 🤝 贡献

欢迎贡献内容和改进建议！

1. Fork 项目
2. 创建功能分支
3. 提交更改
4. 推送到分支
5. 创建 Pull Request

## 📄 许可证

MIT License

## 📞 联系方式

- **QQ群**: 538887146
- **主站**: [share.yezau.com](https://share.yezau.com)
