---
layout: publication
title: 'Beyond Hard And Soft: Hybrid Context Compression For Balancing Local And Global Information Retention'
authors: Huanxuan Liao, Wen Hu, Yao Xu, Shizhu He, Jun Zhao, Kang Liu
conference: "Arxiv"
year: 2025
bibkey: liao2025beyond
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.15774'}
tags: ['RAG', 'Efficiency and Optimization', 'Training Techniques', 'Pretraining Methods']
---
Large Language Models (LLMs) encounter significant challenges in long-sequence inference due to computational inefficiency and redundant processing, driving interest in context compression techniques. Existing methods often rely on token importance to perform hard local compression or encode context into latent representations for soft global compression. However, the uneven distribution of textual content relevance and the diversity of demands for user instructions mean these approaches frequently lead to the loss of potentially valuable information. To address this, we propose \\(\textbf\{Hy\}\\)brid \\(\textbf\{Co\}\\)ntext \\(\textbf\{Co\}\\)mpression (HyCo\\(_2\\)) for LLMs, which integrates both global and local perspectives to guide context compression while retaining both the essential semantics and critical details for task completion. Specifically, we employ a hybrid adapter to refine global semantics with the global view, based on the observation that different adapters excel at different tasks. Then we incorporate a classification layer that assigns a retention probability to each context token based on the local view, determining whether it should be retained or discarded. To foster a balanced integration of global and local compression, we introduce auxiliary paraphrasing and completion pretraining before instruction tuning. This promotes a synergistic integration that emphasizes instruction-relevant information while preserving essential local details, ultimately balancing local and global information retention in context compression. Experiments show that our HyCo\\(_2\\) method significantly enhances long-text reasoning while reducing token usage. It improves the performance of various LLM series by an average of 13.1% across seven knowledge-intensive QA benchmarks. Moreover, HyCo\\(_2\\) matches the performance of uncompressed methods while reducing token consumption by 88.8%.
