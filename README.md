# 千里之行，始于足下 - 个人技术博客

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-在线-brightgreen)](https://ink-hz.github.io)
[![域名](https://img.shields.io/badge/域名-www.ink--hz.cn-blue)](http://www.ink-hz.cn)

托管在 GitHub Pages 上的个人技术博客，主要涵盖 Linux、算法、编译、工程能力和技术书籍笔记等文章。

## 🌟 应用场景

### 博客内容分类
- **Linux 系统管理**：服务器管理、Shell 脚本、系统优化
- **算法分析**：数据结构、算法实现和复杂度分析
- **编译技术**：编译器设计、代码生成、优化技术
- **工程能力**：软件架构、开发实践、工具使用
- **技术书籍笔记**：技术文献的总结和心得

### 使用场景
- **知识分享**：记录技术解决方案和学习成果
- **参考资料**：快速访问命令、配置和代码片段
- **学习进展**：跟踪复杂技术概念的理解程度
- **社区贡献**：与开发者社区分享经验

## ⚙️ 功能特性

### 核心功能
- **静态站点生成**：性能优化的快速加载页面
- **响应式设计**：适配所有设备类型的移动友好布局
- **图片画廊**：集成 Fancybox 的增强媒体查看
- **搜索功能**：客户端博客内容搜索
- **归档系统**：按年份时间顺序组织文章
- **自定义域名**：在 www.ink-hz.cn 的专业展示

### 交互元素
- **导航**：平滑滚动和直观的菜单系统
- **灯箱**：使用 Fancybox 2.1.5 增强图片查看
- **搜索**：实时内容过滤和发现
- **社交集成**：便捷的分享和互动功能

## 🏗️ 代码结构

### 前端架构
```
/
├── css/
│   └── style.css          # 主样式表
├── js/
│   └── script.js          # 核心 JavaScript 功能
├── fancybox/
│   ├── jquery.fancybox.css
│   ├── jquery.fancybox.js
│   └── fancybox_sprite.png
├── images/                # 博客资源和媒体文件
├── 2020/, 2021/, 2022/    # 按年份生成的博客文章
├── archives/              # 归档页面
├── index.html             # 首页
└── CNAME                  # 自定义域名配置
```

### 技术栈
- **生成器**：Hexo 4.2.0 静态站点生成器
- **前端**：HTML5、CSS3、JavaScript (ES5)
- **库**：jQuery 用于 DOM 操作
- **UI 组件**：Fancybox 用于媒体画廊
- **托管**：GitHub Pages 配合自定义域名

### 数据流
1. **内容创建** → Hexo 处理 markdown 文件
2. **静态生成** → HTML/CSS/JS 编译
3. **部署** → 推送到 GitHub Pages
4. **内容分发** → 通过 CDN 在 www.ink-hz.cn 提供服务

## 🎯 框架设计

### 架构模式
- **静态站点生成器 (SSG)**：预构建 HTML 以获得最佳性能
- **基于组件**：模块化的 CSS 和 JavaScript 组织
- **渐进增强**：无需 JavaScript 即可访问核心内容
- **移动优先**：响应式设计原则

### 设计原则
- **性能**：最少的 JavaScript，优化的资源
- **可访问性**：语义化 HTML，键盘导航
- **SEO 优化**：结构化数据，元标签
- **可维护性**：清晰的关注点分离

### 部署策略
- **单一仓库**：生成的文件在主分支
- **自动部署**：GitHub Pages 自动部署
- **版本控制**：基于 Git 的内容版本管理
- **自定义域名**：通过 CNAME 的 DNS 配置

## 🚀 使用方法

### 浏览博客
访问 [www.ink-hz.cn](http://www.ink-hz.cn) 或 [ink-hz.github.io](https://ink-hz.github.io) 浏览文章。

### 本地开发
```bash
# 克隆仓库
git clone https://github.com/ink-hz/ink-hz.github.io.git
cd ink-hz.github.io

# 本地服务（需要简单的 HTTP 服务器）
python -m http.server 8000
# 或者
npx serve .

# 在浏览器中打开 http://localhost:8000
```

### 内容更新
```bash
# 添加新生成的内容
git add .

# 使用时间戳模式提交
git commit -m "Site updated: $(date '+%Y-%m-%d %H:%M:%S')"

# 部署到 GitHub Pages
git push origin main
```

### 搜索功能
- 使用搜索功能查找特定主题
- 搜索适用于所有已发布的文章
- 结果高亮显示匹配的内容片段

## 📱 特性

### 阅读体验
- **快速加载**：优化的静态文件
- **清晰排版**：可读的字体和间距
- **图片画廊**：点击放大并具有平滑过渡
- **移动响应**：适应所有屏幕尺寸
- **深色/浅色主题**：自动主题检测

### 技术特性
- **SEO 优化**：元标签，结构化数据
- **社交分享**：Open Graph 和 Twitter Cards
- **分析就绪**：易于集成跟踪工具
- **CDN 分发**：快速的全球内容分发

## 🔧 定制化

### 样式
- 修改 `/css/style.css` 进行视觉更改
- 为移动端/平板/桌面定义响应式断点
- 颜色方案和排版易于定制

### 功能
- 扩展 `/js/script.js` 以添加额外功能
- 主脚本文件中的 Fancybox 配置
- 搜索功能可针对不同内容类型进行定制

## 📄 许可证

此博客内容和代码在 MIT 许可证下可用。各个文章的特定许可证请参见相应文章。

---

**作者**：黄政 (Huang Zheng)  
**博客**：[www.ink-hz.cn](http://www.ink-hz.cn)  
**座右铭**：千里之行，始于足下