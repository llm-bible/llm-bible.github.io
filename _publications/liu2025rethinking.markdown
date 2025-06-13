---
layout: publication
title: 'Rethinking The Role Of Prompting Strategies In LLM Test-time Scaling: A Perspective Of Probability Theory'
authors: Yexiang Liu, Zekun Li, Zhi Fang, Nan Xu, Ran He, Tieniu Tan
conference: "Arxiv"
year: 2025
bibkey: liu2025rethinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.10981"}
  - {name: "Code", url: "https://github.com/MraDonkey/rethinking_prompting"}
tags: ['Model Architecture', 'Has Code', 'Prompting', 'Applications', 'Attention Mechanism']
---
Recently, scaling test-time compute on Large Language Models (LLM) has garnered wide attention. However, there has been limited investigation of how various reasoning prompting strategies perform as scaling. In this paper, we focus on a standard and realistic scaling setting: majority voting. We systematically conduct experiments on 6 LLMs \\(\times\\) 8 prompting strategies \\(\times\\) 6 benchmarks. Experiment results consistently show that as the sampling time and computational overhead increase, complicated prompting strategies with superior initial performance gradually fall behind simple Chain-of-Thought. We analyze this phenomenon and provide theoretical proofs. Additionally, we propose a probabilistic method to efficiently predict scaling performance and identify the best prompting strategy under large sampling times, eliminating the need for resource-intensive inference processes in practical applications. Furthermore, we introduce two ways derived from our theoretical analysis to significantly improve the scaling performance. We hope that our research can promote to re-examine the role of complicated prompting, unleash the potential of simple prompting strategies, and provide new insights for enhancing test-time scaling performance. Code is available at https://github.com/MraDonkey/rethinking_prompting.
