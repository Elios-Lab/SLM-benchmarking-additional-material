# Supplementary Material: Benchmarking Small Language Models on an Industry-grade, MCU-MPU crossover

This repository serves as supplementary material for the paper **"Benchmarking Small Language Models on an Industry-grade, MCU-MPU crossover"**.

The paper presents an empirical characterization of inference throughput for various Small Language Models (SLMs) on the **STMicroelectronics STM32MP2**, a heterogeneous platform designed for industrial Edge AI applications. 

Below you will find the complete list of all the language models evaluated in our study, along with their size and direct links to their official technical reports, research papers, or repositories.

## Evaluated Models

| Model Family / Framework | Parameters | Reference Title / Description | Link |
| :--- | :--- | :--- | :--- |
| **TinyStories** | 15M - 110M | Inference of LLaMA-style Models in Pure C (Karpathy, 2023) | [GitHub](https://github.com/karpathy/llama2.c) |
| **Gemma 3** | 270M, 1B | Gemma 3 Technical Report (Gemma Team et al., 2025) | [arXiv:2503.19786](https://arxiv.org/abs/2503.19786) |
| **SmolLM2** | 135M, 1.7B | SmolLM2: When Smol Goes Big -- Data-Centric Training (Allal et al., 2025) | [arXiv:2502.02737](https://arxiv.org/abs/2502.02737) |
| **LFM2** | 350M - 2.6B | LFM2 Technical Report (Amini et al., 2025) | [arXiv:2511.23404](https://arxiv.org/abs/2511.23404) |
| **Granite 3.3** | 2B | IBM Granite Models Announcement (IBM Research, 2025) | [IBM Announcement](https://www.ibm.com/new/announcements/ibm-granite-3-3-speech-recognition-refined-reasoning-rag-loras) |
| **Granite 4.0** | 350M, 3B | IBM Granite 4.0 Announcement (IBM Research, 2025) | [IBM Announcement](https://www.ibm.com/new/announcements/ibm-granite-4-0-hyper-efficient-high-performance-hybrid-models) |
| **Qwen** | 500M | Qwen Technical Report (Bai et al., 2023) | [arXiv:2309.16609](https://arxiv.org/abs/2309.16609) |
| **Qwen2** | 1B, 1.5B | Qwen2 Technical Report (Alibaba Cloud, 2024) | [Technical Report](https://cdn.jsdelivr.net/gh/yanfeng98/paper-is-all-you-need/papers/00069-Qwen3_Technical_Report.pdf) |
| **Qwen3** | 2.2B | Qwen3 Technical Report (Yang et al., 2025) | [arXiv:2505.09388](https://arxiv.org/abs/2505.09388) |
| **DeepSeek-R1** | 1.5B | DeepSeek-R1 Technical Report (DeepSeek AI, 2024) | [GitHub](https://github.com/deepseek-ai/DeepSeek-R1) |
| **BitNet** | 2B | BitNet: Scaling 1-bit Transformers (Wang et al., 2023) | [arXiv:2310.11453](https://arxiv.org/abs/2310.11453) |
| **EXAONE Deep** | 2.4B | EXAONE Deep: Reasoning Enhanced Language Models (LG AI, 2025) | [arXiv:2503.12524](https://arxiv.org/abs/2503.12524) |
| **OpenELM** | 3B | OpenELM: An Efficient Language Model Family (Mehta et al., 2024) | [arXiv:2404.14619](https://arxiv.org/abs/2404.14619) |
| **Phi-3** | 3.8B | Introducing Phi-3 (Microsoft Research, 2023) | [Microsoft Blog](https://azure.microsoft.com/en-us/blog/introducing-phi-3-redefining-whats-possible-with-slms/) |
| **Phi-4** | 3.8B | Phi-4 Technical Report (Abdin et al., 2024) | [arXiv:2412.08905](https://arxiv.org/abs/2412.08905) |
