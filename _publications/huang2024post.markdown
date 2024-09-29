---
layout: publication
title: Antidote Post-fine-tuning Safety Alignment For Large Language Models Against Harmful Fine-tuning
authors: Huang Tiansheng, Bhattacharya Gautam, Joshi Pratik, Kimball Josh, Liu Ling
conference: "Arxiv"
year: 2024
bibkey: huang2024post
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.09600"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'Pruning', 'Reinforcement Learning', 'Responsible AI', 'Security', 'Training Techniques']
---
Safety aligned Large Language Models (LLMs) are vulnerable to harmful fine-tuning attacks (citeqi2023fine)-- a few harmful data mixed in the fine-tuning dataset can break the LLMss safety alignment. Existing mitigation strategies include alignment stage solutions (cite)huang2024vaccine rosati2024representation and fine-tuning stage solutions (cite)huang2024lazymukhoti2023fine. However our evaluation shows that both categories of defenses fail (textit)when some specific training hyper-parameters are chosen -- a large learning rate or a large number of training epochs in the fine-tuning stage can easily invalidate the defense which however is necessary to guarantee finetune performance. To this end we propose Antidote a post-fine-tuning stage solution which remains (textbf)(textit)agnostic to the training hyper-parameters in the fine-tuning stage. Antidote relies on the philosophy that by removing the harmful parameters the harmful model can be recovered from the harmful behaviors regardless of how those harmful parameters are formed in the fine-tuning stage. With this philosophy we introduce a one-shot pruning stage after harmful fine-tuning to remove the harmful weights that are responsible for the generation of harmful content. Despite its embarrassing simplicity empirical results show that Antidote can reduce harmful score while maintaining accuracy on downstream tasks.Our project page is at (url)https://huangtiansheng.github.io/Antidote\_gh\_page/\}
