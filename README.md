# 我的个人文档站

这是我的个人文档站点，使用 [Docsify](https://docsify.js.org) 构建，托管在 [GitHub Pages](https://pages.github.com) 上。

## 🌐 在线访问

访问地址：https://你的用户名.github.io/你的仓库名

## 📂 项目结构

```
.
├── docs/                   # 网站内容目录
│   ├── index.html          # 站点入口
│   ├── README.md           # 首页内容
│   ├── _coverpage.md       # 封面配置
│   ├── _sidebar.md         # 侧边栏配置
│   ├── _navbar.md          # 顶部导航配置
│   ├── about.md            # 关于页面
│   ├── .nojekyll           # GitHub Pages 配置文件
│   ├── tech/               # 技术文章
│   └── life/               # 生活随笔
├── .github/
│   └── workflows/
│       └── deploy.yml      # GitHub Actions 自动部署配置
├── README.md               # 本文件（项目说明）
└── PROJECT_STRUCTURE.md    # 项目结构详细说明
```

## 🚀 本地开发

```bash
# 安装 docsify-cli
npm install -g docsify-cli

# 启动本地服务器
cd docs
docsify serve .

# 或指定端口
docsify serve . -p 3000
```

访问 http://localhost:3000 预览效果。

## 📝 添加内容

1. 在 `docs/` 目录下创建或编辑 `.md` 文件
2. 在 `docs/_sidebar.md` 中添加导航链接
3. 提交并推送到 GitHub，自动部署

## 🔧 技术栈

- **Docsify** - 轻量级文档站点生成器
- **GitHub Pages** - 静态网站托管
- **GitHub Actions** - 自动部署

## 📄 详细指南

查看 [PROJECT_STRUCTURE.md](./PROJECT_STRUCTURE.md) 了解完整的项目结构和配置说明。

## 📚 参考

- [Docsify 官方文档](https://docsify.js.org)
- [GitHub Pages 文档](https://docs.github.com/pages)
- [Markdown 语法指南](https://www.markdownguide.org)

---

**作者**：你的名字  
**许可证**：MIT
