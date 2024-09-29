---
layout: publication
title: Sbora Low45;rank Adaptation With Regional Weight Updates
authors: Po Lai-man, Liu Yuyang, Wu Haoxuan, Zhang Tianqi, Yu Wing-yin, Jiang Zeyu, Li Kun
conference: "Arxiv"
year: 2024
bibkey: po2024low
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.05413"}
  - {name: "Code", url: "https://github.com/cityuhkai/SBoRA"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'RAG']
---
This paper introduces Standard Basis LoRA (SBoRA) a novel parameter45;efficient fine45;tuning approach for Large Language Models that builds upon the pioneering works of Low45;Rank Adaptation (LoRA) and Orthogonal Adaptation. SBoRA further reduces the computational and memory requirements of LoRA while enhancing learning performance. By leveraging orthogonal standard basis vectors to initialize one of the low45;rank matrices either A or B SBoRA enables regional weight updates and memory45;efficient fine45;tuning. This approach gives rise to two variants SBoRA45;FA and SBoRA45;FB where only one of the matrices is updated resulting in a sparse update matrix with a majority of zero rows or columns. Consequently the majority of the fine45;tuned models weights remain unchanged from the pre45;trained weights. This characteristic of SBoRA wherein regional weight updates occur is reminiscent of the modular organization of the human brain which efficiently adapts to new tasks. Our empirical results demonstrate the superiority of SBoRA45;FA over LoRA in various fine45;tuning tasks including commonsense reasoning and arithmetic reasoning. Furthermore we evaluate the effectiveness of QSBoRA on quantized LLaMA models of varying scales highlighting its potential for efficient adaptation to new tasks. Code is available at https://github.com/cityuhkai/SBoRA
