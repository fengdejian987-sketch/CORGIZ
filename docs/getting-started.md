# 开始使用 CORGIZ

本页面将帮助您快速开始使用 CORGIZ 文档平台。

## 前置要求

- Git
- GitHub 账号
- 基本的 Markdown 知识

## 安装步骤

1. **克隆仓库**
   ```bash
   git clone https://github.com/fengdejian987-sketch/CORGIZ.git
   cd CORGIZ
   ```

2. **安装依赖**
   ```bash
   bundle install
   ```

3. **本地构建**
   ```bash
   bundle exec jekyll serve
   ```

4. **访问本地网站**
   打开浏览器访问 `http://localhost:4000/CORGIZ`

## 文件结构

```
CORGIZ/
├── _config.yml           # Jekyll 配置文件
├── index.md              # 主页
├── docs/                 # 文档目录
│   ├── getting-started.md
│   ├── api-reference.md
│   └── faq.md
├── assets/               # 资源目录
├── CONTRIBUTING.md       # 贡献指南
└── LICENSE              # 许可证
```

## 创建新文档

1. 在 `docs/` 目录中创建新的 Markdown 文件
2. 添加 front matter（文件头）：
   ```markdown
   ---
   layout: default
   title: 文档标题
   ---
   ```
3. 编写内容
4. 提交并推送更改

## 支持的功能

- ✅ Markdown 支持
- ✅ 代码高亮
- ✅ 自动生成目录
- ✅ 搜索功能
- ✅ 响应式设计

## 常见问题

**Q: 如何自定义网站样式？**  
A: 编辑 `_config.yml` 文件并选择不同的 Jekyll 主题。

**Q: 如何添加新页面？**  
A: 在根目录或任何子目录中创建 `.md` 或 `.html` 文件。

**Q: 更改后多久会发布？**  
A: GitHub Pages 通常在几分钟内自动构建和发布。

## 获取帮助

- 📖 [Jekyll 文档](https://jekyllrb.com/)
- 🔗 [GitHub Pages 帮助](https://docs.github.com/en/pages)
- 💬 [CORGIZ Issues](https://github.com/fengdejian987-sketch/CORGIZ/issues)
