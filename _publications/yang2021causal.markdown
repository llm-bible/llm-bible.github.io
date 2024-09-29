---
layout: publication
title: Causal Attention For Vision45;language Tasks
authors: Yang Xu, Zhang Hanwang, Qi Guojun, Cai Jianfei
conference: "Arxiv"
year: 2021
bibkey: yang2021causal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2103.03493"}
  - {name: "Code", url: "https://github.com/yangxuntu/catt&#125;"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
We present a novel attention mechanism Causal Attention (CATT) to remove the ever45;elusive confounding effect in existing attention45;based vision45;language models. This effect causes harmful bias that misleads the attention module to focus on the spurious correlations in training data damaging the model generalization. As the confounder is unobserved in general we use the front45;door adjustment to realize the causal intervention which does not require any knowledge on the confounder. Specifically CATT is implemented as a combination of 1) In45;Sample Attention (IS45;ATT) and 2) Cross45;Sample Attention (CS45;ATT) where the latter forcibly brings other samples into every IS45;ATT mimicking the causal intervention. CATT abides by the Q45;K45;V convention and hence can replace any attention module such as top45;down attention and self45;attention in Transformers. CATT improves various popular attention45;based vision45;language models by considerable margins. In particular we show that CATT has great potential in large45;scale pre45;training e.g. it can promote the lighter LXMERT~cite123;tan2019lxmert125; which uses fewer data and less computational power comparable to the heavier UNITER~cite123;chen2020uniter125;. Code is published in url123;https://github.com/yangxuntu/catt&#125;.
