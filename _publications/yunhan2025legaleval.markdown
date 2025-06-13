---
layout: publication
title: 'Legaleval-q: A New Benchmark For The Quality Evaluation Of Llm-generated Legal Text'
authors: Li Yunhan, Wu Gengshen
conference: "Arxiv"
year: 2025
bibkey: yunhan2025legaleval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.24826"}
  - {name: "Code", url: "https://github.com/lyxx3rd/LegalEval-Q"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'Quantization', 'Has Code', 'Applications']
---
As large language models (LLMs) are increasingly used in legal applications, current evaluation benchmarks tend to focus mainly on factual accuracy while largely neglecting important linguistic quality aspects such as clarity, coherence, and terminology. To address this gap, we propose three steps: First, we develop a regression model to evaluate the quality of legal texts based on clarity, coherence, and terminology. Second, we create a specialized set of legal questions. Third, we analyze 49 LLMs using this evaluation framework.
  Our analysis identifies three key findings: First, model quality levels off at 14 billion parameters, with only a marginal improvement of \\(2.7%\\) noted at 72 billion parameters. Second, engineering choices such as quantization and context length have a negligible impact, as indicated by statistical significance thresholds above 0.016. Third, reasoning models consistently outperform base architectures. A significant outcome of our research is the release of a ranking list and Pareto analysis, which highlight the Qwen3 series as the optimal choice for cost-performance tradeoffs. This work not only establishes standardized evaluation protocols for legal LLMs but also uncovers fundamental limitations in current training data refinement approaches. Code and models are available at: https://github.com/lyxx3rd/LegalEval-Q.
