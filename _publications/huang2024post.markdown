---
layout: publication
title: Antidote Post45;fine45;tuning Safety Alignment For Large Language Models Against Harmful Fine45;tuning
authors: Huang Tiansheng, Bhattacharya Gautam, Joshi Pratik, Kimball Josh, Liu Ling
conference: "Arxiv"
year: 2024
bibkey: huang2024post
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.09600"}
tags: ['Efficiency And Optimization', 'Pruning', 'Reinforcement Learning', 'Responsible AI', 'Security', 'Training Techniques']
---
Safety aligned Large Language Models (LLMs) are vulnerable to harmful fine45;tuning attacks cite123;qi2023fine125;45;45; a few harmful data mixed in the fine45;tuning dataset can break the LLMss safety alignment. Existing mitigation strategies include alignment stage solutions cite123;huang2024vaccine rosati2024representation125; and fine45;tuning stage solutions cite123;huang2024lazymukhoti2023fine125;. However our evaluation shows that both categories of defenses fail textit123;when some specific training hyper45;parameters are chosen125; 45;45; a large learning rate or a large number of training epochs in the fine45;tuning stage can easily invalidate the defense which however is necessary to guarantee finetune performance. To this end we propose Antidote a post45;fine45;tuning stage solution which remains textbf123;textit123;agnostic to the training hyper45;parameters in the fine45;tuning stage125;125;. Antidote relies on the philosophy that by removing the harmful parameters the harmful model can be recovered from the harmful behaviors regardless of how those harmful parameters are formed in the fine45;tuning stage. With this philosophy we introduce a one45;shot pruning stage after harmful fine45;tuning to remove the harmful weights that are responsible for the generation of harmful content. Despite its embarrassing simplicity empirical results show that Antidote can reduce harmful score while maintaining accuracy on downstream tasks.Our project page is at url123;https://huangtiansheng.github.io/Antidote&#95;gh&#95;page/&#125;
