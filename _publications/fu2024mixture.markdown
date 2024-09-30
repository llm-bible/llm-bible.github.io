---
layout: publication
title: 'Moa: Mixture Of Sparse Attention For Automatic Large Language Model Compression'
authors: Fu Tianyu, Huang Haofeng, Ning Xuefei, Zhang Genghan, Chen Boju, Wu Tianqi, Wang Hongyi, Huang Zixiao, Li Shiyao, Yan Shengen, Dai Guohao, Yang Huazhong, Wang Yu
conference: "Arxiv"
year: 2024
bibkey: fu2024mixture
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14909"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Quantization', 'RAG']
---
Sparse attention can effectively mitigate the significant memory and throughput demands of Large Language Models (LLMs) in long contexts. Existing methods typically employ a uniform sparse attention mask applying the same sparse pattern across different attention heads and input lengths. However this uniform approach fails to capture the diverse attention patterns inherent in LLMs ignoring their distinct accuracy-latency trade-offs. To address this challenge we propose the Mixture of Attention (MoA) which automatically tailors distinct sparse attention configurations to different heads and layers. MoA constructs and navigates a search space of various attention patterns and their scaling rules relative to input sequence lengths. It profiles the model evaluates potential configurations and pinpoints the optimal sparse attention compression plan. MoA adapts to varying input sizes revealing that some attention heads expand their focus to accommodate longer sequences while other heads consistently concentrate on fixed-length local contexts. Experiments show that MoA increases the effective context length by (3.9times) with the same average attention span boosting retrieval accuracy by (1.5-7.1times) over the uniform-attention baseline across Vicuna-7B Vicuna-13B and Llama3-8B models. Moreover MoA narrows the capability gaps between sparse and dense models reducing the maximum relative performance drop from (9-36) to within (5) across two long-context understanding benchmarks. MoA achieves a (1.2-1.4times) GPU memory reduction and boosts decode throughput by 5.5-6.7 times for 7B and 13B dense models on a single GPU with minimal impact on performance.
