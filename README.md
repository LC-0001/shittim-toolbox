<div align="center">
  <img src="assets/title.svg" alt="Shittim Toolbox · 什亭之匣" height="48">
</div>

一套轻量网页工具集合，单文件 HTML，开箱即用。

> 在线访问：[https://lc-0001.github.io/shittim-toolbox/](https://lc-0001.github.io/shittim-toolbox/)

## 功能
- 网页工具箱，集成多种实用工具
- 液态玻璃拟态界面，支持浅色 / 深色主题切换
- 单文件运行，无需复杂部署
- 全部数据保存在浏览器本地

## 技术栈
纯原生 HTML / CSS / JavaScript 单文件应用，无框架，无需构建步骤。

## 部署
本项目仅依赖静态资源，支持 GitHub Pages、Vercel、Netlify 等任意静态托管平台。

### GitHub Pages 部署步骤
1. Fork 本仓库到自己的账号
2. 进入仓库 Settings → Pages
3. Source 选择 `Deploy from a branch`，分支选择 `main`，目录选择 `/ (root)`，保存
4. 等待 1–2 分钟，访问 `https://<你的用户名>.github.io/shittim-toolbox/`

## 本地开发
本项目为单文件静态页面，无依赖，无需安装任何包。

```bash
git clone https://github.com/LC-0001/shittim-toolbox.git
cd shittim-toolbox
python3 -m http.server 8000
```

访问 `http://localhost:8000`。

## 许可
[![许可: MIT](https://img.shields.io/badge/%E8%AE%B8%E5%8F%AF-MIT-128AFA.svg)](LICENSE)