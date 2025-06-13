---
layout: publication
title: 'Equivpruner: Boosting Efficiency And Quality In Llm-based Search Via Action Pruning'
authors: Jiawei Liu, Qisi Chen, Jianshu Zhang, Quan Liu, Defu Lian
conference: "Arxiv"
year: 2025
bibkey: liu2025boosting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.16312'}
  - {name: "Code", url: 'https://github.com/Lolo1222/EquivPruner'}
tags: ['Has Code', 'Efficiency and Optimization', 'Training Techniques', 'Fine-Tuning', 'Pruning']
---
Large Language Models (LLMs) excel at complex reasoning through search algorithms, yet current strategies often suffer from massive token consumption due to redundant exploration of semantically equivalent steps. Existing semantic similarity methods struggle to accurately identify such equivalence in domain-specific contexts like mathematical reasoning. To address this, we propose EquivPruner, a simple yet effective approach that identifies and prunes semantically equivalent actions during LLM reasoning search. We also introduce MathEquiv, the first dataset we created for mathematical statement equivalence, which enables the training of a lightweight equivalence detector. Extensive experiments across various models and tasks demonstrate that EquivPruner significantly reduces token consumption, improving searching efficiency and often bolstering reasoning accuracy. For instance, when applied to Qwen2.5-Math-7B-Instruct on GSM8K, EquivPruner reduced token consumption by 48.1% while also improving accuracy. Our code is available at https://github.com/Lolo1222/EquivPruner.
