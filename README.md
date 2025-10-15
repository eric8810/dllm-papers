# Diffusion Language Models (dLLM) 论文合集

[![Papers](https://img.shields.io/badge/Papers-282-blue.svg)](papers/)
[![Categories](https://img.shields.io/badge/Categories-9-green.svg)](#-分类概览)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

[English](#english) | [中文](#中文)

---

## 中文

### 📚 项目简介

本仓库收集整理了 **Diffusion Large Language Models (dLLM)** 相关的学术论文，涵盖基础模型、多模态、推理优化、训练策略等多个方向。目前已收录 **282 篇论文**，并按主题分类整理。

### 🗂️ 分类概览

| 分类 | 论文数量 | 目录 |
|------|---------|------|
| 必读论文 | 6 | [01-Must-Read](papers/01-Must-Read/) |
| 综述论文 | 5 | [02-Surveys](papers/02-Surveys/) |
| 扩散基础 | 7 | [03-Diffusion-Foundation](papers/03-Diffusion-Foundation/) |
| 离散扩散模型 | 71 | [04-Discrete-DLMs](papers/04-Discrete-DLMs/) |
| 连续扩散模型 | 32 | [05-Continuous-DLMs](papers/05-Continuous-DLMs/) |
| 多模态模型 | 13 | [06-Multimodal-DLMs](papers/06-Multimodal-DLMs/) |
| 训练策略 | 23 | [07-Training-Strategies](papers/07-Training-Strategies/) |
| 推理优化 | 56 | [08-Inference-Optimization](papers/08-Inference-Optimization/) |
| 应用领域 | 60 | [09-Applications](papers/09-Applications/) |

### 📋 主要研究方向

#### 1️⃣ 基础模型
- **LLaDA** - Large Language Diffusion Models
- **Dream 7B** - Diffusion Large Language Models
- **SDAR** - Structured Denoising Autoregressive Models

#### 2️⃣ 多模态 dLLM
- **LaViDa** - 多模态理解的大型扩散语言模型
- **Dimple** - 并行解码的离散扩散多模态大语言模型
- **LLaDA-V** - 视觉指令调优的大语言扩散模型
- **MMaDA** - 多模态大型扩散语言模型
- **Lumina-DiMOO** - 全能扩散大语言模型

#### 3️⃣ KV Cache 优化
- dKV-Cache、dLLM-Cache
- Fast-dLLM、Sparse-dLLM
- DPad（后缀丢弃）

#### 4️⃣ 推理采样方法
- 熵界无掩码采样
- SlowFast 采样
- 位置感知校准
- 奖励加权采样
- 并行解码

#### 5️⃣ 可变长度生成
- DreamOn - 代码填充的可变长度画布
- Beyond Fixed - 可变长度去噪
- Any-Order - 任意顺序灵活长度掩码扩散

#### 6️⃣ 强化学习
- **d1** - 基于强化学习的推理扩展
- **wd1** - 加权策略优化
- LLaDA 1.5 - 方差减少的偏好优化
- MDPO - 克服训练推理分歧

#### 7️⃣ 应用领域
- **医学影像** - LLaDA-MedV
- **语音理解** - DIFFA、Whisfusion
- **代码生成** - DiffuCoder、DreamOn
- **安全性研究** - The Devil behind the mask
- **机器人控制** - LLaDA-VLA

#### 8️⃣ 推理框架与系统优化
- vLLM、SGLang、FlashInfer
- FlexGen、SpecInfer
- Medusa、Lookahead Decoding

### 📖 文档索引

- [完整论文列表](paper_list.md) - 按主题分类的中文论文列表
- [缺失论文清单](missing_papers_list.md) - 待补充的推理框架论文
- [详细索引](papers/INDEX.md) - 包含 arXiv 链接和文件路径的完整索引

### 🚀 快速开始

```bash
# 克隆仓库
git clone https://github.com/yourusername/dllm.git
cd dllm

# 浏览论文分类
ls papers/

# 查看完整索引
cat papers/INDEX.md
```

### 📊 统计信息

- 总论文数：**282 篇**
- 最新更新：2025年10月
- 覆盖时间：2021-2025
- 主要来源：arXiv, NeurIPS, ICML, ACL 等

### 🤝 贡献指南

欢迎贡献新的论文或改进现有分类！

1. Fork 本仓库
2. 添加论文到对应分类目录
3. 更新相关索引文件
4. 提交 Pull Request

### 📄 许可证

本项目采用 MIT 许可证。论文版权归原作者所有。

---

## English

### 📚 About

This repository is a curated collection of academic papers on **Diffusion Large Language Models (dLLM)**, covering foundation models, multimodal systems, inference optimization, training strategies, and more. Currently featuring **282 papers** organized by topic.

### 🗂️ Categories Overview

| Category | Count | Directory |
|----------|-------|-----------|
| Must-Read | 6 | [01-Must-Read](papers/01-Must-Read/) |
| Surveys | 5 | [02-Surveys](papers/02-Surveys/) |
| Diffusion Foundation | 7 | [03-Diffusion-Foundation](papers/03-Diffusion-Foundation/) |
| Discrete DLMs | 71 | [04-Discrete-DLMs](papers/04-Discrete-DLMs/) |
| Continuous DLMs | 32 | [05-Continuous-DLMs](papers/05-Continuous-DLMs/) |
| Multimodal DLMs | 13 | [06-Multimodal-DLMs](papers/06-Multimodal-DLMs/) |
| Training Strategies | 23 | [07-Training-Strategies](papers/07-Training-Strategies/) |
| Inference Optimization | 56 | [08-Inference-Optimization](papers/08-Inference-Optimization/) |
| Applications | 60 | [09-Applications](papers/09-Applications/) |

### 🔬 Key Research Areas

- **Foundation Models**: LLaDA, Dream 7B, SDAR
- **Multimodal**: LaViDa, Dimple, MMaDA, Lumina-DiMOO
- **KV Cache**: dKV-Cache, Fast-dLLM, Sparse-dLLM
- **Sampling Methods**: Entropy-bounded, SlowFast, Parallel Decoding
- **Variable Length**: DreamOn, Beyond Fixed, Any-Order
- **Reinforcement Learning**: d1, wd1, MDPO
- **Applications**: Medical imaging, Audio, Code generation, Robotics
- **Inference Systems**: vLLM, SGLang, FlashInfer

### 📖 Documentation

- [Paper List (CN)](paper_list.md) - Categorized Chinese list
- [Missing Papers](missing_papers_list.md) - Papers to be added
- [Full Index](papers/INDEX.md) - Complete index with arXiv links

### 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/yourusername/dllm.git
cd dllm

# Browse paper categories
ls papers/

# View full index
cat papers/INDEX.md
```

### 📊 Statistics

- Total Papers: **282**
- Last Update: October 2025
- Time Span: 2021-2025
- Sources: arXiv, NeurIPS, ICML, ACL, etc.

### 🤝 Contributing

Contributions are welcome! Please feel free to:

1. Fork this repository
2. Add papers to appropriate category directories
3. Update index files
4. Submit a Pull Request

### 📄 License

This project is licensed under the MIT License. Paper copyrights belong to their respective authors.

---

### ⭐ Star History

If you find this collection useful, please consider giving it a star!

### 📬 Contact

For questions or suggestions, please open an issue.

---

**Note**: This is a research paper collection for academic purposes. All papers are publicly available from their respective sources.
