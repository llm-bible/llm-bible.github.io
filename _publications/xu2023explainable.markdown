---
layout: publication
title: INSTRUCTSCORE Explainable Text Generation Evaluation With Finegrained Feedback
authors: Xu Wenda, Wang Danqing, Pan Liangming, Song Zhenqiao, Freitag Markus, Wang William Yang, Li Lei
conference: "Arxiv"
year: 2023
bibkey: xu2023explainable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14282"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Model Architecture']
---
Automatically evaluating the quality of language generation is critical. Although recent learned metrics show high correlation with human judgement these metrics can not explain their verdict or associate the scores with defects in generated text. To address this limitation we present InstructScore an explainable evaluation metric for text generation. By harnessing both explicit human instruction and the implicit knowledge of GPT45;4 we fine45;tune a text evaluation metric based on LLaMA producing both a score for generated text and a human readable diagnostic report. We evaluate InstructScore on a variety of generation tasks including translation captioning data45;to45;text and commonsense generation. Experiments show that our 7B model surpasses all other unsupervised metrics including those based on 175B GPT45;3 and GPT45;4. Surprisingly our InstructScore even without direct supervision from human45;rated data achieves performance levels on par with state45;of45;the45;art metrics like COMET22 which were fine45;tuned on human ratings.
