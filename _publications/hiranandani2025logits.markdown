---
layout: publication
title: 'Logits Are All We Need To Adapt Closed Models'
authors: Gaurush Hiranandani, Haolun Wu, Subhojyoti Mukherjee, Sanmi Koyejo
conference: "Arxiv"
year: 2025
bibkey: hiranandani2025logits
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.06806"}
tags: ['Tools', 'GPT', 'Pretraining Methods', 'Prompting', 'Applications']
---
Many commercial Large Language Models (LLMs) are often closed-source, limiting developers to prompt tuning for aligning content generation with specific applications. While these models currently do not provide access to token logits, we argue that if such access were available, it would enable more powerful adaptation techniques beyond prompt engineering. In this paper, we propose a token-level probability reweighting framework that, given access to logits and a small amount of task-specific data, can effectively steer black-box LLMs toward application-specific content generation. Our approach views next-token prediction through the lens of supervised classification. We show that aligning black-box LLMs with task-specific data can be formulated as a label noise correction problem, leading to Plugin model -- an autoregressive probability reweighting model that operates solely on logits. We provide theoretical justification for why reweighting logits alone is sufficient for task adaptation. Extensive experiments with multiple datasets, LLMs, and reweighting models demonstrate the effectiveness of our method, advocating for broader access to token logits in closed-source models.
