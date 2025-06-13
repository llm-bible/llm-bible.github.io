---
layout: publication
title: 'Transformers Can Navigate Mazes With Multi-step Prediction'
authors: Niklas Nolte, Ouail Kitouni, Adina Williams, Mike Rabbat, Mark Ibrahim
conference: "Arxiv"
year: 2024
bibkey: nolte2024transformers
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.05117"}
  - {name: "Code", url: "https://github.com/facebookresearch/maze_navigation_MLMU"}
tags: ['Transformer', 'Model Architecture', 'Language Modeling', 'Reinforcement Learning', 'Masked Language Model', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
Despite their remarkable success in language modeling, transformers trained
to predict the next token in a sequence struggle with long-term planning. This
limitation is particularly evident in tasks requiring foresight to plan
multiple steps ahead such as maze navigation. The standard next single token
prediction objective, however, offers no explicit mechanism to predict multiple
steps ahead - or revisit the path taken so far. Consequently, in this work we
study whether explicitly predicting multiple steps ahead (and backwards) can
improve transformers' maze navigation. We train parameter-matched transformers
from scratch, under identical settings, to navigate mazes of varying types and
sizes with standard next token prediction and MLM-U, an objective explicitly
predicting multiple steps ahead and backwards. We find that MLM-U considerably
improves transformers' ability to navigate mazes compared to standard next
token prediction across maze types and complexities. We also find MLM-U
training is 4x more sample efficient and converges 2x faster in terms of GPU
training hours relative to next token training. Finally, for more complex mazes
we find MLM-U benefits from scaling to larger transformers. Remarkably, we find
transformers trained with MLM-U outperform larger transformers trained with
next token prediction using additional supervision from A* search traces. We
hope these findings underscore the promise of learning objectives to advance
transformers' capacity for long-term planning. The code can be found at
https://github.com/facebookresearch/maze_navigation_MLMU
