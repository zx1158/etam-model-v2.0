# ETAMv2.0 规范 — ATE 基底 · XR 编码 · icR 生成器  
> [English README](README.md)｜[PDF 下载](https://github.com/zx1158/etam-spec/releases/download/v2.0.0/ETAMv2.0_spec.pdf)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.xxxxxxx.svg)](https://doi.org/10.5281/zenodo.xxxxxxx)  
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

---

## 📘 什么是 ETAMv2.0？

**ETAMv2.0**（Energetic–Temporal–Environmental Activity Model v2.0）不是对旧模型的升级，而是一个**建模范式的根本性重构**。它以三个不可约的本体基底（Ontological Basis）为第一性原理：

| 符号 | 全称（中文） | 含义 |
|------|----------------|------|
| **A** | **空间构型活性**（Spatial-Architectural Activity） | 描述轨道占据几何、原子排布约束（如 s/p/d/f 轨道权重） |
| **T** | **时间槽激活**（Temporal-Slot Activation） | 划分离散演化尺度窗口（从飞秒到百万秒） |
| **E** | **能质响应场**（Energo-Material Response Field） | 表征环境耦合效应（电离、亲和、极化、溶剂化） |

- ✅ **XR**：`R = [n_A, n_T, n_E] ∈ ℤ^{N×3}` —— ATE 基底在离散状态空间中的**协同投影坐标**（非特征拼接）。  
- ✅ **icR**：`f(R) = x(R) + i·c(R)` —— **复值生成器**：<br>　• `x(R)` 是协变可观测量（实部，对应物理输出 `Y`）<br>　• `c(R)` 是共变提升势（虚部，驱动 `分子 → 介观 → 宏观` 自洽涌现）。

> 🔑 **核心创新**：ETAMv2.0 将建模语言从“变量映射”升维至“本体坐标系”，其数学结构直接受 Rosen 关系本体论、Connes 非交换几何、Penrose 复平面层级、Wigner 数学可逆性四大思想奠基。

---

## 🛠️ 如何使用本规范？

### ✅ 获取 PDF
- [下载 ETAMv2.0_spec.pdf（v2.0.0）](https://github.com/zx1158/etam-spec/releases/download/v2.0.0/ETAMv2.0_spec.pdf)  


