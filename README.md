<h1 align="center">Shittim Toolbox</h1>

<p align="center">
  <b>什亭之匣</b>
</p>

<p align="center">
  <a href="https://lc-0001.github.io/shittim-toolbox/">
    <img src="https://img.shields.io/badge/Live-在线访问-128AFA?style=for-the-badge" alt="在线访问">
  </a>
  <a href="LICENSE">
    <img src="https://img.shields.io/badge/许可-MIT-128AFA?style=for-the-badge" alt="许可: MIT">
  </a>
</p>

<p align="center">
  一套轻量网页工具集合，单文件 HTML，开箱即用。
</p>

---

## 功能
- 网页工具箱，集成多种实用工具
- 液态玻璃拟态界面，支持浅色 / 深色主题切换
- 单文件运行，无需复杂部署
- 全部数据保存在浏览器本地

## 技术栈
纯原生 HTML / CSS / JavaScript 单文件应用，无框架，无需构建步骤。

## 如何 Fork 并部署自己的副本
1. 点击仓库右上角的 **Fork** 按钮。
2. 进入你 fork 后的仓库，点击 **Settings** → 左侧栏 **Pages**。
3. Source 选 **Deploy from a branch**，Branch 选 **main**，文件夹选 **/(root)**，点 **Save**。
4. 等待 1–2 分钟，访问 `https://你的用户名.github.io/shittim-toolbox/`。

## 本地开发
本项目是纯静态页面，无需安装任何依赖。

```bash
git clone https://github.com/LC-0001/shittim-toolbox.git
cd shittim-toolbox
python3 -m http.server 8000
```

然后访问 http://localhost:8000 即可。

## 许可

本项目基于 [MIT License](LICENSE) 开源。