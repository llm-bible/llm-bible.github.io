---
layout: publication
title: 'Unveiling Reasoning Thresholds In Language Models: Scaling, Fine-tuning, And Interpretability Through Attention Maps'
authors: Yen-che Hsiao, Abhishek Dutta
conference: "Arxiv"
year: 2025
bibkey: hsiao2025unveiling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.15120"}
  - {name: "Code", url: "https://github.com/AnnonymousForPapers/CoT_Reasoning_Test"}
tags: ['Training Techniques', 'Model Architecture', 'In-Context Learning', 'GPT', 'Pretraining Methods', 'Transformer', 'Fine-Tuning', 'Has Code', 'Interpretability and Explainability', 'Prompting', 'Applications', 'Attention Mechanism']
---
This study investigates the in-context learning capabilities of various
decoder-only transformer-based language models with different model sizes and
training data, including GPT2, SmolLM2, OpenELM, TinyLlama, Stable LM, and
Gemma 2. We identify a critical parameter threshold (~1.6 billion), beyond
which reasoning performance improves significantly in tasks such as commonsense
reasoning in multiple-choice question answering and deductive reasoning.
Specifically, models above this threshold achieve better success rates in
chain-of-thought (CoT) prompting for deductive reasoning tasks, especially
those requiring longer reasoning chains, such as proof by contradiction and
disjunction elimination. To address limitations in sub-threshold models, we
demonstrate that fine-tuning with task-specific exemplars substantially
enhances reasoning performance, enabling accurate CoT generation even without
additional exemplars in the prompt for tasks with shorter reasoning chains.
Finally, our analysis of attention maps reveals that models capable of
generating correct CoTs exhibit higher token-level attention scores on
subsequent correct tokens and the correct parts of speech, providing
interpretability insights into reasoning processes. These findings collectively
advance understanding of reasoning capabilities in decoder-only
transformer-based models. The code is available at:
https://github.com/AnnonymousForPapers/CoT_Reasoning_Test.
