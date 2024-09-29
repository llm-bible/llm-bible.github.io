---
layout: publication
title: Fine45;tuning Large Language Models To Translate Will A Touch Of Noisy Data In Misaligned Languages Suffice
authors: Zhu Dawei, Chen Pinzhen, Zhang Miaoran, Haddow Barry, Shen Xiaoyu, Klakow Dietrich
conference: "Arxiv"
year: 2024
bibkey: zhu2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.14122"}
tags: ['Applications', 'Ethics And Bias', 'Training Techniques']
---
Traditionally success in multilingual machine translation can be attributed to three key factors in training data large volume diverse translation directions and high quality. In the current practice of fine45;tuning large language models (LLMs) for translation we revisit the importance of all these factors. We find that LLMs display strong translation capability after being fine45;tuned on as few as 32 training instances and that fine45;tuning on a single translation direction effectively enables LLMs to translate in multiple directions. However the choice of direction is critical fine45;tuning LLMs with English on the target side can lead to task misinterpretation which hinders translations into non45;English languages. A similar problem arises when noise is introduced into the target side of parallel data especially when the target language is well45;represented in the LLMs pre45;training. In contrast noise in an under45;represented language has a less pronounced effect. Our findings suggest that attaining successful alignment hinges on teaching the model to maintain a superficial focus thereby avoiding the learning of erroneous biases beyond translation.
