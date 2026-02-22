# ETAM v2.01 — 能量潮汐解析模型  
*一种面向复杂生命系统的、可检验的物理假设生成平台*


[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub Release](https://img.shields.io/github/v/release/zx1158/etam-model-v2.0?label=Release&color=blue)](https://github.com/zx1158/etam-model-v2.0)  
[![许可证：MIT](https://img.shields.io/badge/许可证-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 📄 技术模型文档（v2.01）  
📄 **[下载 PDF（ETAM v2.01 模型文档）](https://github.com/zx1158/etam-model-v2.0/blob/main/paper/ETAMv2.01_model.pdf)**  
✅ 最新技术规范｜完整数学模型｜支持打印与离线阅读  

🔗 **模型仓库主页**：[https://github.com/zx1158/etam-model-v2.0](https://github.com/zx1158/etam-model-v2.0)  
→ 含完整源代码、技术文档与实现细节。

---

## 🧮 核心方程  
模型的根本等式（双域对齐条件）：

$$
f(R(\Lambda)) = Y(\Lambda) = A(\Lambda) \cdot T(\Lambda,\tau) \cdot E(\Lambda,\tau)
$$

其中：  
- $A$：动态环境响应张量（原子 + 成键 + 环境项）  
- $T$：Heaviside 门控的时间调制张量  
- $E$：受 $A$ 与 $T$ 动态调制的能级响应场  
- $f$：基于 Volterra/Laplace 升维的仿射-响应函数  

---

## ✨ 核心特性  
✅ **物理可解释**：每个符号对应明确量子化学可观测量（$Z_{\text{eff}}$, $L_i$, $\varepsilon_{\text{solvent}}$）  
✅ **数学可追溯**：所有公式编号与论文一致，支持符号级验证  
✅ **操作即开即用**：`time_flag=OFF` 切换静态模式，`ON` 启用动态感知  
✅ **闭环工作流就绪**：支持「虚拟预测 → 实验验证 → 假设生成」全链条  

---

## 📚 引用本工作  
本成果采用 **GitHub Release 作为永久学术标识符**，符合以下规范：  
- 🌐 Nature Scientific Data 政策（软件发布等效 DOI）  
- 🇨🇳 国家标准 GB/T 7714—2015（电子公告 EB/OL 类型）  
- 📚 IEEE 引用指南（要求 cite specific release URL）  

**推荐引用格式（中文文献）**：  
> 邵昆. ETAM v2.01：能量潮汐解析模型[EB/OL]. GitHub, 2026-02-22[2026-02-22]. https://github.com/zx1158/etam-model-v2.0/blob/main/paper/ETAMv2.01_model.pdf.

**BibTeX（复制到 `.bib` 文件）**：
```bibtex
@software{etam_v2_01,
  author       = {邵昆},
  title        = {ETAM v2.01: 能量潮汐解析模型},
  year         = {2026},
  publisher    = {GitHub},
  version      = {v2.01},
  doi          = {https://github.com/zx1158/etam-model-v2.0/blob/main/paper/ETAMv2.01_model.pdf},
  url          = {https://github.com/zx1158/etam-model-v2.0/blob/main/paper/ETAMv2.01_model.pdf}
}


