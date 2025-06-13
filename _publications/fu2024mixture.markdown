---
layout: publication
title: 'Moa: Mixture Of Sparse Attention For Automatic Large Language Model Compression'
authors: Tianyu Fu, Haofeng Huang, Xuefei Ning, Genghan Zhang, Boju Chen, Tianqi Wu, Hongyi Wang, Zixiao Huang, Shiyao Li, Shengen Yan, Guohao Dai, Huazhong Yang, Yu Wang
conference: "Arxiv"
year: 2024
bibkey: fu2024mixture
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14909"}
  - {name: "Code", url: "https://github.com/thu-nics/MoA"}
tags: ['Efficiency and Optimization', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism', 'Has Code', 'Quantization']
---
Sparse attention can effectively mitigate the significant memory and
throughput demands of Large Language Models (LLMs) in long contexts. Existing
methods typically employ a uniform sparse attention mask, applying the same
sparse pattern across different attention heads and input lengths. However,
this uniform approach fails to capture the diverse attention patterns inherent
in LLMs, ignoring their distinct accuracy-latency trade-offs. To address this
challenge, we propose the Mixture of Attention (MoA), which automatically
tailors distinct sparse attention configurations to different heads and layers.
MoA constructs and navigates a search space of various attention patterns and
their scaling rules relative to input sequence lengths. It profiles the model,
evaluates potential configurations, and pinpoints the optimal sparse attention
compression plan. MoA adapts to varying input sizes, revealing that some
attention heads expand their focus to accommodate longer sequences, while other
heads consistently concentrate on fixed-length local contexts. Experiments show
that MoA increases the effective context length by \\(3.9\times\\) with the same
average attention span, boosting retrieval accuracy by \\(1.5-7.1\times\\) over the
uniform-attention baseline across Vicuna-\{7B,13B\}, and Llama3-\{8B,70B\} models.
Moreover, MoA narrows the capability gaps between sparse and dense models,
reducing the maximum relative performance drop from \\(9%-36%\\) to within \\(5%\\)
across two long-context understanding benchmarks. MoA achieves a
\\(1.2-1.4\times\\) GPU memory reduction, boosting decode throughput by
\\(6.6-8.2\times\\) and \\(1.7-1.9\times\\) compared to FlashAttention2 and vLLM, with
minimal impact on performance. Our code is available at
\url\{https://github.com/thu-nics/MoA\}.
