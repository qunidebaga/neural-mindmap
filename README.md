# 神经思维导图 MindFlow · Neural Mindmap

基于**神经网络**可视化理念的 **AI 思维导图**工具。在线创建、编辑和智能分析思维导图与脑图，支持模块管理、关联分析、AI 辅助思考，所有数据保存在本地浏览器，无需注册、完全免费。

## 在线体验

👉 https://qunidebaga.github.io/neural-mindmap/

（打开即用，思维导图数据保存在浏览器本地）

## 功能特性

- **神经网络式连线**：思维导图节点以神经网络风格连线呈现，视觉直观
- **AI 智能辅助**：接入 MiniMax API，支持 AI 生成与扩展思维导图内容
- **模块管理**：自由创建、编辑、移动思维导图节点和模块
- **关联分析**：自动分析模块间关联，提供分析记录
- **主题切换**：暗色 / 亮色双主题
- **数据安全**：数据保存在浏览器 localStorage，支持导出 / 导入 JSON 备份
- **桌面版支持**：Electron 打包，可生成 Windows / macOS 桌面应用

## 本地运行（桌面版）

```bash
npm install
npm start        # Electron 桌面版
```

## 文件说明

| 文件 | 说明 |
| --- | --- |
| `index.html` | 单文件 Web 版，完全自包含，可直接静态托管 |
| `main.js` | Electron 主进程 |
| `package.json` | 桌面版构建配置 |

## 技术栈

- 原生 HTML / CSS / JavaScript（零依赖、单文件自包含）
- Electron（桌面版）
- MiniMax API（AI 辅助）

## 许可

仅供学习与个人使用，未经授权请勿用于商业用途。
