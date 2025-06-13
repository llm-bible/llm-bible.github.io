---
layout: publication
title: 'Sbora: Low-rank Adaptation With Regional Weight Updates'
authors: Lai-man Po, Yuyang Liu, Haoxuan Wu, Tianqi Zhang, Wing-yin Yu, Zhuohan Wang, Zeyu Jiang, Kun Li
conference: "Arxiv"
year: 2024
bibkey: po2024low
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.05413"}
  - {name: "Code", url: "https://github.com/cityuhkai/SBoRA"}
tags: ['Pretraining Methods', 'Training Techniques', 'Fine-Tuning', 'Has Code']
---
This paper introduces Standard Basis LoRA (SBoRA), a novel
parameter-efficient fine-tuning approach for Large Language Models that builds
upon the pioneering works of Low-Rank Adaptation (LoRA) and Orthogonal
Adaptation. SBoRA reduces the number of trainable parameters by half or doubles
the rank with the similar number of trainable parameters as LoRA, while
improving learning performance. By utilizing orthogonal standard basis vectors
to initialize one of the low-rank matrices (either \\(\mathbf\{A\}\\) or
\\(\mathbf\{B\}\\)), SBoRA facilitates regional weight updates and memory-efficient
fine-tuning. This results in two variants, SBoRA-FA and SBoRA-FB, where only
one of the matrices is updated, leading to a sparse update matrix
\\(\mathrm\{\Delta\} \mathbf\{W\}\\) with predominantly zero rows or columns.
Consequently, most of the fine-tuned model's weights
\\((\mathbf\{W\}_0+\mathrm\{\Delta\} \mathbf\{W\})\\) remain unchanged from the
pre-trained weights, akin to the modular organization of the human brain, which
efficiently adapts to new tasks. Our empirical results demonstrate the
superiority of SBoRA-FA over LoRA in various fine-tuning tasks, including
commonsense reasoning and arithmetic reasoning. Furthermore, we evaluate the
effectiveness of QSBoRA on quantized LLaMA models of varying scales,
highlighting its potential for efficient adaptation to new tasks. Code is
available at https://github.com/cityuhkai/SBoRA
