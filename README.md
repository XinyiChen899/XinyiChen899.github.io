# Xinyi Chen's Personal Homepage

🌐 **个人主页** — AI 产品经理 / HCI 研究者

## 📍 在线访问
**https://XinyiChen899.github.io/**

## ✏️ 如何编辑内容

这是一个纯 HTML 单页网站，所有内容都在 `index.html` 一个文件中：

1. 克隆仓库到本地：
   ```bash
   git clone git@github.com:XinyiChen899/XinyiChen899.github.io.git
   ```

2. 用任意文本编辑器打开 `index.html`

3. 找到你想修改的部分，直接编辑文字即可：
   - **Hero 区**：姓名、定位标签、简介 → 搜索 `<section class="hero">`
   - **关于我**：个人介绍 + 数据亮点 → 搜索 `id="about"`
   - **项目作品**：添加/修改项目卡片 → 搜索 `id="projects"`
   - **实习经历**：工作经历时间线 → 搜索 `id="experience"`
   - **技能栈**：工具和技能分类 → 搜索 `id="skills"`
   - **教育背景**：学校信息 → 搜索 `id="education"`
   - **荣誉奖项**：获奖列表 → 搜索 `id="awards"`
   - **联系方式**：邮箱/电话/GitHub → 搜索 `id="contact"`

4. 保存后推送更新：
   ```bash
   git add index.html
   git commit -m "更新个人信息"
   git push origin main
   ```

5. GitHub Pages 会自动构建部署，约 1-2 分钟后刷新页面即可看到最新内容。

## 🔧 技术栈
- 纯静态 HTML / CSS / JavaScript（无需服务器或构建工具）
- 响应式设计，支持手机/平板/桌面端
- Google 字体（Inter + Noto Sans SC）
- MathJax 数学公式渲染支持

## 📝 设计说明
- 参考学术风格极简布局，改造为产品经理求职方向
- 单页滚动式（SPA），锚点导航快速跳转
- 渐变色点缀 + 卡片悬停动画 + 滚动渐显效果
- 导航栏毛玻璃效果 + 移动端汉堡菜单

---

© 2026 Xinyi Chen · Built with ❤️
