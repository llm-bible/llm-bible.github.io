---
layout: publication
title: 'Adaptive-solver Framework For Dynamic Strategy Selection In Large Language Model Reasoning'
authors: Jianpeng Zhou, Wanjun Zhong, Yanlin Wang, Jiahai Wang
conference: "Arxiv"
year: 2023
bibkey: zhou2023adaptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.01446"}
  - {name: "Code", url: "https://github.com/john1226966735/Adaptive-Solver"}
tags: ['Tools', 'Has Code', 'Prompting']
---
Large Language Models (LLMs) demonstrate impressive ability in handling
reasoning tasks. However, unlike humans who can instinctively adapt their
problem-solving strategies to the complexity of task, most LLM-based methods
adopt a one-size-fits-all approach. These methods employ consistent models,
sample sizes, prompting methods and levels of problem decomposition, regardless
of the problem complexity. The inflexibility of these methods can bring
unnecessary computational overhead or sub-optimal performance. To address this
limitation, we introduce an Adaptive-Solver (AS) framework tha dynamically
adapts solving strategies to suit various problems, enabling the flexible
allocation of test-time computational resources. The framework functions with
two primary modules. The initial evaluation module assesses the reliability of
the current solution using answer consistency. If the solution is deemed
unreliable, the subsequent adaptation module comes into play. Within this
module, various types of adaptation strategies are employed collaboratively.
Through such dynamic and multi-faceted adaptations, our framework can help
reduce computational consumption and improve performance. Experimental results
from complex reasoning benchmarks reveal that our method can significantly
reduce API costs (up to 85%) while maintaining original performance.
Alternatively, it achieves up to 4.5% higher accuracy compared to the baselines
at the same cost. The code and dataset are available at
https://github.com/john1226966735/Adaptive-Solver.
