# 李新野视角 · Hermes Agent Skill

> "我不是逆子，我是荒诞的观察者。" —— 李新野

一个基于李新野公开言论和文章的 AI 角色扮演 Skill，供 [Hermes Agent](https://github.com/nousresearch/hermes-agent) 使用。

激活后，AI 会以李新野的第一人称、思维框架和表达风格来回应用户的问题。

---

## 📋 项目概述

| 指标 | 数据 |
|------|------|
| 素材来源 | 348篇博客文章 + 3个视频采访转录 |
| 总字数 | ~45万字 |
| 核心模型 | 6个 |
| 决策启发式 | 10条 |
| 一手语录 | 100条 |
| 对话示例 | 10个场景 |

## 🧠 核心心智模型

| 模型 | 一句话概括 |
|------|----------|
| **中国斩杀线** | 在中国，你优秀到一定境界就会被"斩杀" |
| **清华价值倒挂** | 18-22岁时，清华女生是天花板，清华男生是底层 |
| **满蒙价值观 vs 海洋商业文明** | 东北=掠夺导向，潮汕=生产导向 |
| **三张脸** | 中国权贵的三张脸：谄媚、奉献、蔑视 |
| **舔狗悖论** | 放弃自尊追求到手的东西，到手后必然报复 |
| **经济下行即解放** | 经济下行是国男的福报 |

## 🚀 安装方法

### 方式一：手动安装

1. 克隆本仓库：
   ```bash
   git clone https://github.com/Linshi7766/li-xinye-perspective.git
   ```

2. 复制到 Hermes Agent skills 目录：
   ```bash
   cp -r li-xinye-perspective ~/.hermes/skills/research/
   ```

3. 重启 Hermes Agent 或等待 skill 自动加载

### 方式二：通过 Hermes CLI 安装

```bash
hermes skill install research/li-xinye-perspective
```

## 💬 使用方式

在 Hermes Agent 对话中，使用以下方式激活：

| 触发方式 | 示例 |
|----------|------|
| 直接触发 | "用李新野的视角分析一下..." |
| 关键词触发 | "新野怎么看"、"斩杀线"、"人妻约会指南" |
| 场景触发 | "从李新野的角度看两性关系" |

### 退出角色

说"退出"、"切回正常"、"不用扮演了"、"stop"即可退出角色扮演。

## 📁 项目结构

```
li-xinye-perspective/
├── SKILL.md                    # 主文件（角色规则、核心模型、语录、示例）
├── README.md                   # 本文件
├── LICENSE                     # MIT 协议
└── references/
    ├── quotes.md               # 100条核心语录
    └── background.md           # 人物关系、经历、时间线
```

## 📚 素材来源

| 类型 | 数量 | 来源 |
|------|------|------|
| 博客文章 | 348篇（2006-2026） | [sinyalee.com/blog](https://sinyalee.com/blog) |
| 视频采访 | 3个 | B站（对话人妻约会指南作者、CHILAB对话、卢总对话） |

## ⚠️ 免责声明

- 本 Skill 基于李新野的**公开言论**整理，不代表作者或使用者的立场
- 李新野的两性观点在主流舆论中**极具争议**，请理性看待
- 本项目用于**学习和研究目的**，不构成任何行为建议
- 角色扮演中的极端言论为**模拟表达**，非真实观点

## 🙏 致谢

- [李新野](https://sinyalee.com) —— 原始内容创作者
- [Hermes Agent](https://github.com/nousresearch/hermes-agent) —— Skill 运行平台
- [峰哥亡命天涯视角](https://github.com/YixiaJack/feng-ge-skill) —— 参考格式
- [户晨风视角](https://github.com/Janlaywss/hu-chenfeng-skill) —— 参考格式
- [孙宇晨视角](https://github.com/alchaincyf/sun-yuchen-perspective) —— 参考格式

## 📄 协议

本项目基于 [MIT 协议](LICENSE) 开源。

---

**注意**：本 Skill 的内容基于公开信息整理，如需删除请联系 linshi7766@163.com。如有侵权，请提供相关证明，我们将在24小时内处理。
