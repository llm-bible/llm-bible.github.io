---
layout: publication
title: 'Lottery Ticket Adaptation: Mitigating Destructive Interference In Llms'
authors: Panda Ashwinee, Isik Berivan, Qi Xiangyu, Koyejo Sanmi, Weissman Tsachy, Mittal Prateek
conference: "Arxiv"
year: 2024
bibkey: panda2024lottery
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.16797"}
  - {name: "Code", url: "https://github.com/kiddyboots216/lottery-ticket-adaptation"}
tags: ['Applications', 'Fine Tuning', 'Has Code', 'Merging', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Existing methods for adapting large language models (LLMs) to new tasks are not suited to multi-task adaptation because they modify all the model weights -- causing destructive interference between tasks. The resulting effects such as catastrophic forgetting of earlier tasks make it challenging to obtain good performance on multiple tasks at the same time. To mitigate this we propose Lottery Ticket Adaptation (LoTA) a sparse adaptation method that identifies and optimizes only a sparse subnetwork of the model. We evaluate LoTA on a wide range of challenging tasks such as instruction following reasoning math and summarization. LoTA obtains better performance than full fine-tuning and low-rank adaptation (LoRA) and maintains good performance even after training on other tasks -- thus avoiding catastrophic forgetting. By extracting and fine-tuning over lottery tickets (or sparse task vectors) LoTA also enables model merging over highly dissimilar tasks. Our code is made publicly available at https://github.com/kiddyboots216/lottery-ticket-adaptation."
