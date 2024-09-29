---
layout: publication
title: Anchored Preference Optimization And Contrastive Revisions: Addressing Underspecification In Alignment
authors: D'oosterlinck Karel, Xu Winnie, Develder Chris, Demeester Thomas, Singh Amanpreet, Potts Christopher, Kiela Douwe, Mehri Shikib
conference: "Arxiv"
year: 2024
bibkey: doosterlinck2024anchored
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.06266"}
  - {name: "Code", url: "https://github.com/ContextualAI/CLAIR_and_APO"}
tags: ['Efficiency And Optimization', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Large Language Models (LLMs) are often aligned using contrastive alignment objectives and preference pair datasets. The interaction between model paired data and objective makes alignment a complicated procedure sometimes producing subpar results. We study this and find that (i) preference data gives a better learning signal when the underlying responses are contrastive and (ii) alignment objectives lead to better performance when they specify more control over the model during training. Based on these insights we introduce Contrastive Learning from AI Revisions (CLAIR) a data-creation method which leads to more contrastive preference pairs and Anchored Preference Optimization (APO) a controllable and more stable alignment objective. We align Llama-3-8B-Instruct using various comparable datasets and alignment objectives and measure MixEval-Hard scores which correlate highly with human judgments. The CLAIR preferences lead to the strongest performance out of all datasets and APO consistently outperforms less controllable objectives. Our best model trained on 32K CLAIR preferences with APO improves Llama-3-8B-Instruct by 7.6537; closing the gap with GPT4-turbo by 4537;. Our code is available at https://github.com/ContextualAI/CLAIR\_and\_APO."
