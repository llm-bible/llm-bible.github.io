---
layout: publication
title: Learning Neural Templates For Recommender Dialogue System
authors: Liang Zujie, Hu Huang, Xu Can, Miao Jian, He Yingying, Chen Yining, Geng Xiubo, Liang Fan, Jiang Daxin
conference: "Arxiv"
year: 2021
bibkey: liang2021learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.12302"}
  - {name: "Code", url: "https://github.com/jokieleung/NTRD"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
Though recent end-to-end neural models have shown promising progress on Conversational Recommender System (CRS) two key challenges still remain. First the recommended items cannot be always incorporated into the generated replies precisely and appropriately. Second only the items mentioned in the training corpus have a chance to be recommended in the conversation. To tackle these challenges we introduce a novel framework called NTRD for recommender dialogue system that decouples the dialogue generation from the item recommendation. NTRD has two key components i.e. response template generator and item selector. The former adopts an encoder-decoder model to generate a response template with slot locations tied to target items while the latter fills in slot locations with the proper items using a sufficient attention mechanism. Our approach combines the strengths of both classical slot filling approaches (that are generally controllable) and modern neural NLG approaches (that are generally more natural and accurate). Extensive experiments on the benchmark ReDial show our NTRD significantly outperforms the previous state-of-the-art methods. Besides our approach has the unique advantage to produce novel items that do not appear in the training set of dialogue corpus. The code is available at urlhttps://github.com/jokieleung/NTRD}.
