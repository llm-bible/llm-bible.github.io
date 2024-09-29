---
layout: publication
title: Finetuned Language Models Are Zero45;shot Learners
authors: Jason Wei, Maarten Bosma, Vincent Y. Zhao, Kelvin Guu, Adams Wei Yu, Brian Lester, Nan Du, Andrew M. Dai, Quoc V. Le
conference: "Arxiv"
year: 2021
bibkey: wei2021finetuned
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2109.01652v5"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods']
---
This paper explores a simple method for improving the zero45;shot learning abilities of language models. We show that instruction tuning 45;45; finetuning language models on a collection of tasks described via instructions 45;45; substantially improves zero45;shot performance on unseen tasks. We take a 137B parameter pretrained language model and instruction45;tune it on over 60 NLP tasks verbalized via natural language instruction templates. We evaluate this instruction45;tuned model which we call FLAN on unseen task types. FLAN substantially improves the performance of its unmodified counterpart and surpasses zero45;shot 175B GPT45;3 on 20 of 25 tasks that we evaluate. FLAN even outperforms few45;shot GPT45;3 by a large margin on ANLI RTE BoolQ AI245;ARC OpenbookQA and StoryCloze. Ablation studies reveal that number of finetuning datasets model scale and natural language instructions are key to the success of instruction tuning.
