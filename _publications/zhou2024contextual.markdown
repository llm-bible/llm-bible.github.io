---
layout: publication
title: Sirius Contextual Sparsity With Correction For Efficient Llms
authors: Zhou Yang, Chen Zhuoming, Xu Zhaozhuo, Lin Victoria, Chen Beidi
conference: "Arxiv"
year: 2024
bibkey: zhou2024contextual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.03856"}
  - {name: "Code", url: "https://github.com/Infini&#45;AI&#45;Lab/Sirius.git"}
tags: ['Applications', 'Efficiency And Optimization', 'Has Code', 'Prompting', 'Training Techniques']
---
With the blossom of large language models (LLMs) inference efficiency becomes increasingly important. Various approximation methods are proposed to reduce the cost at inference time. Contextual Sparsity (CS) is appealing for its training45;free nature and its ability to reach a higher compression ratio seemingly without quality degradation. However after a comprehensive evaluation of contextual sparsity methods on various complex generation tasks we find that although CS succeeds in prompt45;understanding tasks CS significantly degrades the model performance for reasoning deduction and knowledge45;based tasks. Despite the gap in end45;to45;end accuracy we observed that sparse models often share general problem45;solving logic and require only a few token corrections to recover the original model performance. This paper introduces Sirius an efficient correction mechanism which significantly recovers CS models quality on reasoning tasks while maintaining its efficiency gain. Sirius is evaluated on 6 models with 8 difficult generation tasks in reasoning math and coding and shows consistent effectiveness and efficiency. Also we carefully develop a system implementation for Sirius and show that Sirius achieves roughly 2037; reduction in latency for 8B model on45;chip and 3537; reduction for 70B model offloading. We open45;source our implementation of Sirius at https://github.com/Infini&#45;AI&#45;Lab/Sirius.git.
