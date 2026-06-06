# YanXu AI Portfolio

个人 AI 作品集展示网站，部署于 Vercel。

## 技术栈

- 纯静态 HTML + CSS（无框架依赖）
- [Vanta.js](https://www.vantajs.com/) — Birds 飞鸟动态背景
- Three.js — Vanta 的渲染依赖
- Google Fonts：Orbitron（标题）+ Noto Sans SC（正文）

## 特性

- 动态飞鸟背景（青色 + 紫色渐变）
- 霓虹渐变故障 Glitch 标题动画
- 游戏卡片悬停发光抬升效果
- 响应式布局（手机 / 平板 / 桌面）

## 如何添加头像

将你的头像图片命名为 `avatar.jpg` 放到项目根目录，没有时显示默认占位符。

## 部署到 Vercel

```bash
# 安装 Vercel CLI（如未安装）
npm i -g vercel

# 在项目目录下执行
vercel
```

也可直接在 Vercel 控制台连接 GitHub 仓库一键部署。

## 本地预览

```bash
# 任意 HTTP 服务器均可，例如：
npx serve .
# 或
python -m http.server 3000
```

> 注意：直接双击 index.html 打开，Vanta.js 因跨域限制可能无法加载，建议用本地服务器预览。
