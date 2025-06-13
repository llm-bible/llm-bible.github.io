---
layout: publication
title: 'Aggregation Of Reasoning: A Hierarchical Framework For Enhancing Answer Selection In Large Language Models'
authors: Zhangyue Yin, Qiushi Sun, Qipeng Guo, Zhiyuan Zeng, Xiaonan Li, Tianxiang Sun, Cheng Chang, Qinyuan Cheng, Ding Wang, Xiaofeng Mou, Xipeng Qiu, Xuanjing Huang
conference: "Arxiv"
year: 2024
bibkey: yin2024aggregation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.12939"}
tags: ['Training Techniques', 'Prompting', 'Tools']
---
Recent advancements in Chain-of-Thought prompting have facilitated
significant breakthroughs for Large Language Models (LLMs) in complex reasoning
tasks. Current research enhances the reasoning performance of LLMs by sampling
multiple reasoning chains and ensembling based on the answer frequency.
However, this approach fails in scenarios where the correct answers are in the
minority. We identify this as a primary factor constraining the reasoning
capabilities of LLMs, a limitation that cannot be resolved solely based on the
predicted answers. To address this shortcoming, we introduce a hierarchical
reasoning aggregation framework AoR (Aggregation of Reasoning), which selects
answers based on the evaluation of reasoning chains. Additionally, AoR
incorporates dynamic sampling, adjusting the number of reasoning chains in
accordance with the complexity of the task. Experimental results on a series of
complex reasoning tasks show that AoR outperforms prominent ensemble methods.
Further analysis reveals that AoR not only adapts various LLMs but also
achieves a superior performance ceiling when compared to current methods.
