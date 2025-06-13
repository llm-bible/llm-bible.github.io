---
layout: publication
title: 'On The Expressiveness Of Visual Prompt Experts'
authors: Minh Le, Anh Nguyen, Huy Nguyen, Chau Nguyen, Anh Tran, Nhat Ho
conference: "Arxiv"
year: 2025
bibkey: le2025expressiveness
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.18936'}
tags: ['Attention Mechanism', 'Efficiency and Optimization', 'Model Architecture', 'Tools', 'Prompting']
---
Visual Prompt Tuning (VPT) has proven effective for parameter-efficient adaptation of pre-trained vision models to downstream tasks by inserting task-specific learnable prompt tokens. Despite its empirical success, a comprehensive theoretical understanding of VPT remains an active area of research. Building on the recently established connection between Mixture of Experts (MoE) and prompt-based methods, wherein each attention head can be conceptualized as a composition of multiple MoE models, we reinterpret VPT as the introduction of new prompt experts into these MoE structures. We identify a key limitation in existing VPT frameworks: the restricted functional expressiveness of prompt experts, which remain static and thus limited in their adaptability. To address this, we propose Visual Adaptive Prompt Tuning (VAPT), a novel method that endows prompt experts with enhanced expressiveness while preserving parameter efficiency. Empirical evaluations on VTAB-1K and FGVC demonstrate that VAPT achieves substantial performance improvements, surpassing fully fine-tuned baselines by 7.34% and 1.04%, respectively. Moreover, VAPT consistently outperforms VPT while requiring fewer additional parameters. Furthermore, our theoretical analysis indicates that VAPT achieves optimal sample efficiency. Collectively, these results underscore the theoretical grounding and empirical advantages of our approach.
