---
layout: publication
title: The Emergence Of Essential Sparsity In Large Pre45;trained Models The Weights That Matter
authors: Ajay Jaiswal, Shiwei Liu, Tianlong Chen, Zhangyang Wang
conference: "Arxiv"
year: 2023
bibkey: jaiswal2023emergence
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2306.03805v2"}
  - {name: "Code", url: "https://github.com/VITA&#45;Group/essential&#95;sparsity&#125;"}
tags: ['BERT', 'Efficiency And Optimization', 'Has Code', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Large pre45;trained transformers are show45;stealer in modern45;day deep learning and it becomes crucial to comprehend the parsimonious patterns that exist within them as they grow in scale. With exploding parameter counts Lottery Ticket Hypothesis (LTH) and its variants have lost their pragmatism in sparsifying them due to high computation and memory bottleneck of repetitive train45;prune45;retrain routine of iterative magnitude pruning (IMP) which worsens with increasing model size. This paper comprehensively studies induced sparse patterns across multiple large pre45;trained vision and language transformers. We propose the existence of 45;45; essential sparsity defined with a sharp dropping point beyond which the performance declines much faster w.r.t the rise of sparsity level when we directly remove weights with the smallest magnitudes in one45;shot without re45;training. We also find essential sparsity to hold valid for NM sparsity patterns as well as on modern45;scale large language models (Vicuna45;7B). We also present an intriguing emerging phenomenon of abrupt sparsification during the pre45;training of BERT i.e. BERT suddenly becomes heavily sparse in pre45;training after certain iterations. Moreover our observations also indicate a counter45;intuitive finding that BERT trained with a larger amount of pre45;training data tends to have a better ability to condense knowledge in comparatively relatively fewer parameters. Lastly we investigate the effect of the pre45;training loss on essential sparsity and discover that self45;supervised learning (SSL) objectives trigger stronger emergent sparsification properties than supervised learning (SL). Our codes are available at url123;https://github.com/VITA&#45;Group/essential&#95;sparsity&#125;.
