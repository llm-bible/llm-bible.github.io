---
layout: publication
title: 'Every Sample Matters: Leveraging Mixture-of-experts And High-quality Data For Efficient And Accurate Code LLM'
authors: Codefuse, Ling Team, :, Wenting Cai, Yuchen Cao, Chaoyu Chen, Chen Chen, Siba Chen, Qing Cui, Peng Di, Junpeng Fang, Zi Gong, Ting Guo, Zhengyu He, Yang Huang, Cong Li, Jianguo Li, Zheng Li, Shijie Lian, Bingchang Liu, Songshan Luo, Shuo Mao, Min Shen, Jian Wu, Jiaolong Yang, Wenjie Yang, Tong Ye, Hang Yu, Wei Zhang, Zhenduo Zhang, Hailin Zhao, Xunjin Zheng, Jun Zhou
conference: "Arxiv"
year: 2025
bibkey: codefuse2025every
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.17793"}
  - {name: "Code", url: "https://huggingface.co/inclusionAI/Ling-Coder-lite"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Has Code', 'Applications']
---
Recent advancements in code large language models (LLMs) have demonstrated
remarkable capabilities in code generation and understanding. It is still
challenging to build a code LLM with comprehensive performance yet ultimate
efficiency. Many attempts have been released in the open source community to
break the trade-off between performance and efficiency, such as the Qwen Coder
series and the DeepSeek Coder series. This paper introduces yet another attempt
in this area, namely Ling-Coder-Lite. We leverage the efficient
Mixture-of-Experts (MoE) architecture along with a set of high-quality data
curation methods (especially those based on program analytics) to build an
efficient yet powerful code LLM. Ling-Coder-Lite exhibits on-par performance on
12 representative coding benchmarks compared to state-of-the-art models of
similar size, such as Qwen2.5-Coder-7B and DeepSeek-Coder-V2-Lite, while
offering competitive latency and throughput. In practice, we achieve a 50%
reduction in deployment resources compared to the similar-sized dense model
without performance loss. To facilitate further research and development in
this area, we open-source our models as well as a substantial portion of
high-quality data for the annealing and post-training stages. The models and
data can be accessed
at~\url\{https://huggingface.co/inclusionAI/Ling-Coder-lite\}.
