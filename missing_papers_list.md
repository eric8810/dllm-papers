# 缺失的推理框架论文列表

## 一、核心推理框架 (必须补充)
1. **vLLM: Easy, Fast, and Cheap LLM Serving with PagedAttention** (NeurIPS 2023)
   - arXiv: 2309.06180
   - 重要性: ⭐⭐⭐⭐⭐
   - 核心: PagedAttention算法，内存管理

2. **SGLang: Efficient Execution of Structured Language Model Programs** (2024)
   - GitHub: https://github.com/sgl-project/sglang
   - 重要性: ⭐⭐⭐⭐⭐
   - 核心: 结构化生成，并行执行

3. **FlashInfer: Efficient and Customizable Attention Engine for LLM Inference Serving** (2024)
   - GitHub: https://github.com/flashinfer-ai/flashinfer
   - 重要性: ⭐⭐⭐⭐
   - 核心: Attention优化引擎

## 二、内存管理与批处理优化
4. **FlexGen: High Throughput Generative Inference of Large Language Models** (ICML 2023)
   - arXiv: 2303.06865
   - 重要性: ⭐⭐⭐⭐
   - 核心: 高吞吐量推理

5. **SpecInfer: Accelerating Generative LLM Serving with Speculative Inference** (2023)
   - arXiv: 2305.09781
   - 重要性: ⭐⭐⭐⭐
   - 核心: 推测推理加速

6. **Medusa: Simple LLM Acceleration Framework with Multiple Decoding Heads** (2024)
   - arXiv: 2401.10774
   - 重要性: ⭐⭐⭐
   - 核心: 多解码头加速

## 三、延迟优化技术
7. **Speculative Decoding for Large Language Models** (2023)
   - arXiv: 2302.01318
   - 重要性: ⭐⭐⭐⭐
   - 核心: 推测解码

8. **Lookahead Decoding: A New Way to Accelerate Large Language Models** (2024)
   - arXiv: 2404.00595
   - 重要性: ⭐⭐⭐
   - 核心: 前瞻解码

9. **EaSe: Efficient and Accurate Speculative Decoding** (2024)
   - arXiv: 2404.00400
   - 重要性: ⭐⭐⭐
   - 核心: 高效推测解码

## 四、分布式推理
10. **Orca: A Distributed Serving System for Transformer-Based Generative Models** (OSDI 2022)
    - 重要性: ⭐⭐⭐⭐
    - 核心: 分布式服务系统

11. **TGI: Text Generation Inference - A Rust, Python and gRPC Server** (HuggingFace)
    - GitHub: https://github.com/huggingface/text-generation-inference
    - 重要性: ⭐⭐⭐⭐
    - 核心: 生产级推理服务

## 五、批处理与调度
12. **Continuous Batching for Efficient LLM Serving** (2024)
    - 重要性: ⭐⭐⭐⭐
    - 核心: 连续批处理

13. **Dynamic Batching for Transformer-based Language Models** (2023)
    - 重要性: ⭐⭐⭐
    - 核心: 动态批处理

## 获取优先级
- **立即获取**: vLLM, SGLang, FlashInfer (核心框架)
- **本周内**: FlexGen, SpecInfer, Speculative Decoding (优化技术)
- **下周**: 其余论文 (补充完善)

## 下载命令示例
```bash
# 创建目录
mkdir -p papers/inference-frameworks

# 下载核心论文
cd papers/inference-frameworks
wget https://arxiv.org/pdf/2309.06180.pdf -O vLLM_PagedAttention.pdf
wget https://arxiv.org/pdf/2303.06865.pdf -O FlexGen_High_Throughput.pdf
wget https://arxiv.org/pdf/2305.09781.pdf -O SpecInfer_Speculative_Inference.pdf
wget https://arxiv.org/pdf/2302.01318.pdf -O Speculative_Decoding.pdf
wget https://arxiv.org/pdf/2401.10774.pdf -O Medusa_Multiple_Decoding_Heads.pdf
wget https://arxiv.org/pdf/2404.00595.pdf -O Lookahead_Decoding.pdf
```