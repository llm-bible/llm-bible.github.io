---
layout: publication
title: "Mitigating Catastrophic Forgetting In Language Transfer Via Model Merging"
authors: Alexandrov Anton, Raychev Veselin, Müller Mark Niklas, Zhang Ce, Vechev Martin, Toutanova Kristina
conference: "Arxiv"
year: 2024
bibkey: alexandrov2024mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.08699"}
tags: ['Merging', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
As open-weight large language models (LLMs) achieve ever more impressive performances across a wide range of tasks in English practitioners aim to adapt these models to different languages. However such language adaptation is often accompanied by catastrophic forgetting of the base models capabilities severely limiting the usefulness of the resulting model. We address this issue by proposing Branch-and-Merge (BaM) a new adaptation method based on iteratively merging multiple models fine-tuned on a subset of the available training data. BaM is based on the insight that this yields lower magnitude but higher quality weight changes reducing forgetting of the source domain while maintaining learning on the target domain. We demonstrate in an extensive empirical study on Bulgarian and German that BaM can significantly reduce forgetting while matching or even improving target domain performance compared to both standard continued pretraining and instruction finetuning across different model architectures.
