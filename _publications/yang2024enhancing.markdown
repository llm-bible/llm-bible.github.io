---
layout: publication
title: Enhancing And Assessing Instruction-following With Fine-grained Instruction Variants
authors: Yang Jiuding, Guo Weidong, Yang Kaitong, Li Xiangyang, Rao Zhuwei, Xu Yu, Niu Di
conference: "Arxiv"
year: 2024
bibkey: yang2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11301"}
tags: ['Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
The effective alignment of Large Language Models (LLMs) with precise instructions is essential for their application in diverse real-world scenarios. Current methods focus on enhancing the diversity and complexity of training and evaluation samples yet they fall short in accurately assessing LLMs ability to follow similar instruction variants. We introduce an effective data augmentation technique that decomposes complex instructions into simpler sub-components modifies these and reconstructs them into new variants thereby preserves the original instructions context and complexity while introducing variability which is critical for training and evaluating LLMs instruction-following precision. We developed the DeMoRecon dataset using this method to both fine-tune and evaluate LLMs. Our findings show that LLMs fine-tuned with DeMoRecon will gain significant performance boost on both ours and commonly used instructions-following benchmarks.
