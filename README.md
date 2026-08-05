# UX Design Guide — UI/UX 设计师方案产出指南

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.0.0-green.svg)](SKILL.md)

一个面向 AI 编程助手的 **UI/UX 设计师 Skill**，将设计领域方法论转化为可执行工作流。自动识别 5 类设计场景（0→1 新产品设计 / 功能迭代 / 微调 / 设计系统升级 / 概念探索），按对应清单产出交互流程、设计规范、组件库方案、无障碍方案等完整交付物。

## 适用场景

| 场景 | 示例 | 产出量 |
|------|------|:---:|
| 0→1 新产品设计 | 全新 App 设计系统搭建 | 10-12类 |
| 中大型功能迭代 | CRM 新增看板模块 | 6-8类 |
| 小优化/微调 | 登录页体验优化 | 2-3类 |
| 设计系统大版本升级 | Design Token V2.0 | 8-10类 |
| 概念探索/预研 | 新业务方向 Mood Board | 3-4类 |

## 触发热词

UI设计、UX设计、交互设计、界面设计、设计系统、设计规范、原型、线框图、高保真、设计走查、用户体验、信息架构、Design Token

---

## 安装

本 Skill 遵循 **Open Agent Skills 标准**（SKILL.md 格式），兼容以下工具：

### WorkBuddy / CodeBuddy

**方式一：克隆到 skills 目录**
```bash
git clone https://github.com/genapohub/ux-design-guide.git ~/.workbuddy/skills/ux-design-guide
```

### Trae

**ZIP 导入**
```bash
# 先下载并打包
git clone https://github.com/genapohub/ux-design-guide.git
zip -r ux-design-guide.zip ux-design-guide/
```
然后在 Trae → **设置** → **Rules & Skills** → **创建** → 上传 `ux-design-guide.zip`。

### Codex

```bash
# 克隆到 skills 目录
git clone https://github.com/genapohub/ux-design-guide.git ~/.codex/skills/ux-design-guide

# 或使用 cc switch (推荐)
git clone https://github.com/genapohub/ux-design-guide.git ~/.cc-switch/skills/ux-design-guide
```

重启 CC Switch客户端/Codex客户端 后自动发现。也可以在对话中输入 `$ux-design-guide` 手动调用。

### Cursor
```bash
# 克隆到 skills 目录
git clone https://github.com/genapohub/ux-design-guide.git ~/.cursor/skills-cursor/ux-design-guide
```

重启 Cursor客户端 后自动发现。也可以在对话中输入 `$ux-design-guide` 手动调用。

---

## 使用

安装后无需额外配置，对话中自然描述需求即可触发：

```
帮我设计一个宠物托运小程序的首页 UI
这个看板模块的交互流程怎么设计
我们的设计系统 Token 需要升级到 V2
帮我出个登录页的交互方案
```

## 许可

[MIT](LICENSE) © zhangmengbo
