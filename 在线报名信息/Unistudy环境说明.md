# UniStudy 环境说明

## 运行环境
- 作品形态：Electron 桌面端应用
- 开发语言：JavaScript、HTML、CSS
- 运行平台：Windows 10 / Windows 11 优先，macOS 和 Linux 也提供启动脚本

## 开发与运行要求
### 直接运行安装包
如果只是体验作品，推荐直接运行提供的 Windows 安装包。安装完成后即可启动，不需要额外安装 Node.js、npm 或其他开发环境。

### 从源码运行
如果需要从源码查看或复现项目，请先准备以下环境：
- Node.js 20 LTS 或兼容版本
- npm
- Visual Studio Code（可选）

然后在项目根目录执行：

```bash
npm install
npm start
```

如果希望按锁定版本重新安装依赖，也可以使用：

```bash
npm ci
npm start
```

Windows 还可以直接使用 `start.bat` 启动；macOS 使用 `start.command`；Linux 使用 `start.sh`。

## 配置说明
首次启动后，需要在 Settings 中配置模型服务地址、API Key、默认模型以及资料检索相关参数。项目支持通过当前话题绑定 Source 资料，并在本地完成学习记录、笔记和附件管理。

## 运行特性
- 支持本地附件集中管理
- 支持话题级资料绑定与检索增强
- 支持聊天、笔记、复习工具和学习记录的连续使用
- 打包后的安装包可直接运行，源码版适合开发和复现
