---
layout: publication
title: Attend, Memorize And Generate: Towards Faithful Table-to-text Generation In Few Shots
authors: Zhao Wenting, Liu Ye, Wan Yao, Yu Philip S.
conference: "Arxiv"
year: 2022
bibkey: zhao2022memorize
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.00732"}
tags: ['Applications', 'Attention Mechanism', 'Few Shot', 'Fine Tuning', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Few-shot table-to-text generation is a task of composing fluent and faithful sentences to convey table content using limited data. Despite many efforts having been made towards generating impressive fluent sentences by fine-tuning powerful pre-trained language models the faithfulness of generated content still needs to be improved. To this end this paper proposes a novel approach Attend Memorize and Generate (called AMG) inspired by the text generation process of humans. In particular AMG (1) attends over the multi-granularity of context using a novel strategy based on table slot level and traditional token-by-token level attention to exploit both the table structure and natural linguistic information; (2) dynamically memorizes the table slot allocation states; and (3) generates faithful sentences according to both the context and memory allocation states. Comprehensive experiments with human evaluation on three domains (i.e. humans songs and books) of the Wiki dataset show that our model can generate higher qualified texts when compared with several state-of-the-art baselines in both fluency and faithfulness.
