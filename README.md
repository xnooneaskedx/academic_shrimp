# 🦐 Academic Shrimp (学术虾) 
> **基于长文本行为学优化的智能文献综述引擎**

## 🌟 项目愿景
[cite_start]拒绝“中间遗失”，重塑学术阅读效率。针对 LLM 在处理长文献时的“U型性能曲线”痛点，提供深度优化的阅读体验 [cite: 4, 9]。

## 🚀 核心技术：DASS 采样算法
本项目首创 **DASS (Dual-Anchor Sparse Sampling)** 采样算法：
* [cite_start]**双向锚点**：自动定位 PDF 前 3 页（Abstract/Intro）与后 2 页（Conclusion/Discussion） [cite: 18, 19, 20]。
* **性能优化**：通过 5-Page Focused Window 策略，在保证综述响应速度的同时，人为避开了模型的“中间遗忘区”。
* **全量回溯**：在细节追问模式下，解除采样限制，调用 Gemini 2.5 Flash 的百万级上下文进行全量文本解析。

## ✨ 核心功能
* [cite_start]**审稿人级综述**：从核心摘要、创新点、方法论及学术洞察四个维度产出报告 [cite: 74, 75]。
* [cite_start]**全量背景追问**：支持针对论文中任何边角数据的精准回溯与探讨 [cite: 82, 84]。
* [cite_start]**出版级导出**：一键生成符合学术规范排版的 Word 综述文件 [cite: 85, 88]。

## 🛠️ 技术栈
* [cite_start]**推理引擎**: Google Gemini 2.5 Flash [cite: 23]
* [cite_start]**前端框架**: Streamlit [cite: 24]
* [cite_start]**文档处理**: LangChain (PyPDFLoader) & Python-Docx [cite: 25]

## 📝 详细说明书
[点击查看完整项目说明书 (WPS)](https://www.kdocs.cn/l/cm1rizMzl3IT)

---
**2026 北纬·龙虾大赛 | 学术龙虾赛道提交材料**
**吴伟彰 | 18810731755@163.com**
