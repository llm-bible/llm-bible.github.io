---
layout: publication
title: Accelerating Attention Through Gradient45;based Learned Runtime Pruning
authors: Li Zheng, Ghodrati Soroush, Yazdanbakhsh Amir, Esmaeilzadeh Hadi, Kang Mingu
conference: "Arxiv"
year: 2022
bibkey: li2022accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2204.03227"}
tags: ['Attention Mechanism', 'BERT', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Pruning', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Self45;attention is a key enabler of state45;of45;art accuracy for various transformer45;based Natural Language Processing models. This attention mechanism calculates a correlation score for each word with respect to the other words in a sentence. Commonly only a small subset of words highly correlates with the word under attention which is only determined at runtime. As such a significant amount of computation is inconsequential due to low attention scores and can potentially be pruned. The main challenge is finding the threshold for the scores below which subsequent computation will be inconsequential. Although such a threshold is discrete this paper formulates its search through a soft differentiable regularizer integrated into the loss function of the training. This formulation piggy backs on the back45;propagation training to analytically co45;optimize the threshold and the weights simultaneously striking a formally optimal balance between accuracy and computation pruning. To best utilize this mathematical innovation we devise a bit45;serial architecture dubbed LeOPArd for transformer language models with bit45;level early termination microarchitectural mechanism. We evaluate our design across 43 back45;end tasks for MemN2N BERT ALBERT GPT45;2 and Vision transformer models. Post45;layout results show that on average LeOPArd yields 1.9x and 3.9x speedup and energy reduction respectively while keeping the average accuracy virtually intact (<0.237; degradation)
