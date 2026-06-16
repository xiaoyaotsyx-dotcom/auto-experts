
<p align="center">
  <img src="https://placehold.co/600x150/ffffff/5b5fe7?text=Rigi+Expert+Panel&font=Montserrat" width="500">
</p>

<p align="center">
  <strong>3 分钟创建一个 AI 专家。每个专家天生会开浏览器、查数据、填表单。</strong><br>
  Create AI experts that can actually DO things — browse, search, fill forms, post.
</p>

<p align="center">
  <a href="https://github.com/xiaoyaotsyx-dotcom/expert-panel/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-AGPLv3-blue"></a>
  <a href="#"><img src="https://img.shields.io/github/stars/xiaoyaotsyx-dotcom/expert-panel"></a>
</p>

---

## ⚡ 一句话

给 AI 助手配一个人设 + 内置浏览器操控 = **能聊更能干的 AI 专家**。

---

## 🤔 和普通 Prompt 有什么区别

| | 普通 Prompt | Rigi 专家 |
|------|-----------|----------|
| 能聊天 | ✅ | ✅ |
| 有专业人设 | ⚠️ 靠用户自己写 | ✅ 预置人格化专家 |
| 能查数据 | ❌ | ✅ 开浏览器搜索 |
| 能填表单 | ❌ | ✅ CDP 操控 |
| 能发社媒 | ❌ | ✅ 六平台发布 |
| 安全边界 | ❌ | ✅ 每个专家有声明的边界 |

---

## 🧠 预置专家

| 专家 | 能做什么 |
|------|---------|
| 📈 **投研分析** | 三源数据→交叉验证→四份研报 |
| 🔒 **安全审计** | 扒前端源码→扫敏感信息→出报告 |
| 🕵️ **竞品分析** | 逆向AI产品→提取提示词架构 |

---

## 🎨 创建你自己的专家

```bash
cp -r template/ 你的专家名/
# 改 4 个地方：人设 / 能力 / 命令模板 / 示例对话
```

---

## 🚀 Quick Start

```bash
# 加载一个预置专家
"加载 investment-research skill，分析特斯拉"

# 或创建新专家
"按照模板创建一个房产评估专家"
```

---

## 📁 结构

```
expert-panel/
├── template/           ← 创建框架（内嵌 CDP 能力）
├── investment-research/  ← 预置：投研专家
├── security-audit/       ← 预置：安全审计专家
└── competitive-analysis/  ← 预置：竞品分析专家
```

---

## 📄 License

AGPLv3 — 个人免费，商用需授权。
