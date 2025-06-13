---
layout: publication
title: 'Chemagent: Self-updating Library In Large Language Models Improves Chemical Reasoning'
authors: Xiangru Tang, Tianyu Hu, Muyang Ye, Yanjun Shao, Xunjian Yin, Siru Ouyang, Wangchunshu Zhou, Pan Lu, Zhuosheng Zhang, Yilun Zhao, Arman Cohan, Mark Gerstein
conference: "Arxiv"
year: 2025
bibkey: tang2025self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.06590"}
  - {name: "Code", url: "https://github.com/gersteinlab/chemagent"}
tags: ['Agentic', 'GPT', 'Tools', 'Applications', 'Model Architecture', 'Has Code']
---
Chemical reasoning usually involves complex, multi-step processes that demand
precise calculations, where even minor errors can lead to cascading failures.
Furthermore, large language models (LLMs) encounter difficulties handling
domain-specific formulas, executing reasoning steps accurately, and integrating
code effectively when tackling chemical reasoning tasks. To address these
challenges, we present ChemAgent, a novel framework designed to improve the
performance of LLMs through a dynamic, self-updating library. This library is
developed by decomposing chemical tasks into sub-tasks and compiling these
sub-tasks into a structured collection that can be referenced for future
queries. Then, when presented with a new problem, ChemAgent retrieves and
refines pertinent information from the library, which we call memory,
facilitating effective task decomposition and the generation of solutions. Our
method designs three types of memory and a library-enhanced reasoning
component, enabling LLMs to improve over time through experience. Experimental
results on four chemical reasoning datasets from SciBench demonstrate that
ChemAgent achieves performance gains of up to 46% (GPT-4), significantly
outperforming existing methods. Our findings suggest substantial potential for
future applications, including tasks such as drug discovery and materials
science. Our code can be found at https://github.com/gersteinlab/chemagent
