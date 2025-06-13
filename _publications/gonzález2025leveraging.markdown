---
layout: publication
title: 'Leveraging The True Depth Of Llms'
authors: Ramón Calvo González, Daniele Paliotta, Matteo Pagliardini, Martin Jaggi, François Fleuret
conference: "Arxiv"
year: 2025
bibkey: gonzález2025leveraging
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.02790'}
tags: ['RAG', 'Efficiency and Optimization', 'Training Techniques', 'Fine-Tuning', 'Pretraining Methods']
---
Large Language Models (LLMs) demonstrate remarkable capabilities at the cost of high compute requirements. Recent studies have demonstrated that intermediate layers in LLMs can be removed or reordered without substantial accuracy loss; however, this insight has not yet been exploited to improve inference efficiency. Leveraging observed layer independence, we propose a novel method that groups consecutive layers into pairs evaluated in parallel, effectively restructuring the computational graph to enhance parallelism. Without requiring retraining or fine-tuning, this approach achieves an inference throughput improvement of 1.05x-1.20x on standard benchmarks, retaining 95%-99% of the original model accuracy. Empirical results demonstrate the practicality of this method in significantly reducing inference cost for large-scale LLM deployment. Additionally, we demonstrate that modest performance degradation can be substantially mitigated through lightweight fine-tuning, further enhancing the method's applicability.
