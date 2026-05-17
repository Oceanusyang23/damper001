# 协调质量阻尼器（TMD）科普 Web App

> 一个面向大众的协调质量阻尼器（Tuned Mass Damper, TMD）科普单页应用。
> 分辨率 1920 × 1080（16:9），通过底部导航在五大板块间切换。

## 项目简介

协调质量阻尼器是一种通过"以柔克刚"原理来抵抗建筑物振动的被动控制装置。本项目以上海中心大厦"上海慧眼"为代表案例，配合历史、原理、动手实验和未来火星建筑的延展，向公众系统化地介绍 TMD 技术。

## 内容板块

1. **历史起源** — TMD 的发展脉络与里程碑事件
2. **原理分析** — 共振、反相位运动与能量耗散的图解说明
3. **上海中心慧眼** — 全球最重 TMD 之一的工程细节
4. **装置实践** — 用矿泉水瓶 + 配重 DIY 一个简易 TMD 模型
5. **火星移民应用** — 低重力、沙尘暴环境下 TMD 的未来设想

## 技术栈

- 纯 HTML / CSS / JavaScript 单文件实现
- 16:9（1920×1080）固定分辨率版式
- 无需构建工具，直接在浏览器中打开

## 快速开始

```bash
# 克隆仓库
git clone https://github.com/Oceanusyang23/damper001.git
cd damper001

# 直接在浏览器中打开
open index.html      # macOS
# 或 start index.html   # Windows
# 或 xdg-open index.html # Linux
```

## 文件结构

```
.
├── index.html        # 主页面（包含五个板块与底部导航）
├── README.md         # 项目说明
└── 参考图片/         # 上海中心 TMD 参考插图
```

## 分支

- `main`：稳定版本
- `webapp`：当前 Web 应用开发分支

## License

MIT
