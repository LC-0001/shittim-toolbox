<div align="center">
  <img src="assets/title.svg" alt="Shittim Toolbox · 什亭之匣" height="48">
</div>

一个《蔚蓝档案》风格的网页工具箱。阿罗娜与普拉娜坐镇「什亭之匣」，把常用工具收进一个单文件 HTML 页面，打开浏览器就能用。

> 在线访问：[https://lc-0001.github.io/shittim-toolbox/](https://lc-0001.github.io/shittim-toolbox/)

## 特色
- **蔚蓝档案风格界面**：液态玻璃拟态设计，配合阿罗娜、普拉娜的对话与提示，像在什亭之匣的终端里操作
- **MomoTalk 主题**：一键切换粉色的 MomoTalk 风格，和默认的蓝色主题可以随时切换
- **浅色 / 深色模式**：可手动切换，也可以跟随系统
- **自定义背景**：上传图片作为背景，支持裁剪
- **数据备份与恢复**：设置、对话和主题可以导出为 JSON 文件，换设备时再导入

## 功能
- 网页工具箱，集成多种实用工具
- 单文件运行，无需复杂部署
- 全部数据保存在浏览器本地，不会上传到服务器

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
本项目为单文件静态页面，无依赖，无需安装任何包。如果你想在自己的电脑上修改和预览，需要先安装 [Python 3](https://www.python.org/)，然后在终端中运行：

```bash
git clone https://github.com/LC-0001/shittim-toolbox.git
cd shittim-toolbox
python3 -m http.server 8000
```

运行后，在浏览器中打开 `http://localhost:8000` 即可预览。这个地址只能在你自己的电脑上访问，关闭终端后服务会停止。

## 声明
本项目是《蔚蓝档案》的非官方同人作品，仅供学习交流，与 Nexon / Yostar 无任何关联。《蔚蓝档案》相关的角色名称、设定及素材版权归 Nexon / Yostar 所有，禁止用于商业用途。

## 许可
本项目基于 [MIT License](LICENSE) 开源，第三方组件归属见 [NOTICE.md](NOTICE.md)。