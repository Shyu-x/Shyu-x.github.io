-----

# Shyu-x 的数字空间 | 个人作品集网站

欢迎来到我的个人作品集网站项目！

[**🔗 在线访问 (Live Demo)**](https://www.google.com/url?sa=E&source=gmail&q=https://shyu-x.github.io/) 
-----

## ✨ 项目特性

  - **🌌 沉浸式 3D 背景**: 基于 `Three.js` 构建的动态粒子星云背景，并能与鼠标进行微妙的交互，营造出深邃的科技感。
  - **🖱️ 交互式光标辉光**: 一个跟随鼠标移动的辉光效果，为用户的每一次浏览都增添了视觉反馈和趣味性。
  - **📜 平滑滚动动画**: 采用 `AOS.js` 库，当用户向下滚动页面时，所有元素都会以优雅、流畅的动画效果进入视野。
  - **💻 动态项目展示**:
      - **模拟终端**: 为 `core-sh` 项目制作了一个高度仿真的终端动画，可以自动“输入”并“执行”命令，生动地演示项目场景。
      - **SVG 架构图**: 为 `nexus-net` 项目制作了动态的 SVG 流程图，直观地展示了 Reactor 模式的事件流转过程。
  - **🎨 现代化设计语言**:
      - 采用暗色主题，搭配高对比度的强调色，符合当代开发者的审美。
      - 使用专业的字体（`Nunito` & `Fira Code`），保证了内容的可读性和美观性。
      - 玻璃拟态 (Glassmorphism) 效果的应用，提升了界面的层次感和质感。
  - **📱 完全响应式**: 无论是在桌面宽屏、平板还是手机上，网站都能自适应并保持完美的显示效果和用户体验。
  - **🚀 极简架构**: 整个网站的所有代码（HTML, CSS, JavaScript）都集成在单一的 `index.html` 文件中，实现了零依赖、易于部署和维护的优点。

-----

## 🚀 技术栈

  - **前端**: HTML5, CSS3, JavaScript (ES6+)
  - **CSS 框架**: [Tailwind CSS](https://tailwindcss.com/) - 用于快速构建响应式布局和组件。
  - **3D 渲染**: [Three.js](https://threejs.org/) - 负责创建和渲染主页的 WebGL 粒子背景。
  - **滚动动画**: [AOS.js](https://michalsnik.github.io/aos/) - 一个轻量级的“滚动动画”库。
  - **图标库**: [Font Awesome](https://fontawesome.com/) - 提供项目中所使用的各类图标。
  - **字体**: [Google Fonts](https://fonts.google.com/) - 引入了 `Nunito` (正文) 和 `Fira Code` (代码/终端) 字体。

-----

## 🔧 如何使用与部署

这个项目最大的优点之一就是部署极其简单。

### 本地运行

1.  克隆或下载此仓库。
2.  直接用浏览器打开 `index.html` 文件即可查看效果。

### 部署到 GitHub Pages (推荐)

1.  创建一个新的 GitHub 仓库，仓库名推荐为 `your-github-username.github.io` (将 `your-github-username` 替换为你的 GitHub 用户名)。
2.  将 `index.html` 文件推送到该仓库的 `main` (或 `master`) 分支。
3.  在仓库的 `Settings > Pages` 中，设置部署源为你的 `main` 分支。
4.  等待几分钟，然后访问 `https://your-github-username.github.io/` 即可看到你的线上个人主页。

-----

## ✍️ 内容定制

你可以轻松地修改 `index.html` 文件来打造完全属于你自己的版本。

1.  **全局信息**:
      - 在 `<title>` 标签中修改网站标题。
      - 在页头 (header) 和页脚 (footer) 区域修改你的名字或 Logo。
2.  **章节内容**:
      - **`#hero`**: 修改你的 Slogan 和主要介绍。
      - **`#about`**: 修改“关于我”部分的个人陈述。
      - **`#skills`**: 在技能列表中增删技术图标（图标来自 Font Awesome）。
      - **`#projects`**: 这是核心区域。你可以修改项目名称、描述、技术标签，甚至可以定制模拟终端 (`terminal-body`) 和 SVG 图中的动画逻辑。
      - **`#contact`**: 在联系方式部分，将 `mailto:` 和 GitHub 链接替换为你自己的地址。
3.  **模拟终端定制**:
      - 在 `<script>` 标签内找到 `commandQueue` 数组。
      - 你可以修改数组中的对象，改变终端自动执行的命令 (`value`)、类型 (`type`) 和每次执行后的延迟时间 (`delay`)。

-----

## 📜 许可

该项目采用 [MIT License](https://opensource.org/licenses/MIT) 许可。欢迎自由使用、修改和分发。

-----

## 🙏 致谢

感谢以下开源项目，它们是构建此网站的基石：

  - [Three.js](https://threejs.org/)
  - [Tailwind CSS](https://tailwindcss.com/)
  - [AOS.js](https://michalsnik.github.io/aos/)
  - [Font Awesome](https://fontawesome.com/)

-----

*由 Shyu-x 设计与构建*
