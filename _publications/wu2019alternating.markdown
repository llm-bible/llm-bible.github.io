---
layout: publication
title: 'Alternating Recurrent Dialog Model With Large-scale Pre-trained Language Models'
authors: Wu Qingyang, Zhang Yichi, Li Yu, Yu Zhou
conference: "Arxiv"
year: 2019
bibkey: wu2019alternating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1910.03756"}
tags: ['Applications', 'BERT', 'Fine Tuning', 'GPT', 'Model Architecture', 'Tools']
---
Existing dialog system models require extensive human annotations and are difficult to generalize to different tasks. The recent success of large pre-trained language models such as BERT and GPT-2 (Devlin et al. 2019; Radford et al. 2019) have suggested the effectiveness of incorporating language priors in down-stream NLP tasks. However how much pre-trained language models can help dialog response generation is still under exploration. In this paper we propose a simple general and effective framework Alternating Roles Dialog Model (ARDM). ARDM models each speaker separately and takes advantage of the large pre-trained language model. It requires no supervision from human annotations such as belief states or dialog acts to achieve effective conversations. ARDM outperforms or is on par with state-of-the-art methods on two popular task-oriented dialog datasets CamRest676 and MultiWOZ. Moreover we can generalize ARDM to more challenging non-collaborative tasks such as persuasion. In persuasion tasks ARDM is capable of generating human-like responses to persuade people to donate to a charity.
