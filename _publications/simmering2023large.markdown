---
layout: publication
title: Large Language Models For Aspect45;based Sentiment Analysis
authors: Simmering Paul F., Huoviala Paavo
conference: "Arxiv"
year: 2023
bibkey: simmering2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.18025"}
tags: ['GPT', 'Model Architecture', 'Prompting']
---
Large language models (LLMs) offer unprecedented text completion capabilities. As general models they can fulfill a wide range of roles including those of more specialized models. We assess the performance of GPT45;4 and GPT45;3.5 in zero shot few shot and fine45;tuned settings on the aspect45;based sentiment analysis (ABSA) task. Fine45;tuned GPT45;3.5 achieves a state45;of45;the45;art F1 score of 83.8 on the joint aspect term extraction and polarity classification task of the SemEval45;2014 Task 4 improving upon InstructABSA 35;64;scaria95;instructabsa95;2023 by 5.737;. However this comes at the price of 1000 times more model parameters and thus increased inference cost. We discuss the the cost45;performance trade45;offs of different models and analyze the typical errors that they make. Our results also indicate that detailed prompts improve performance in zero45;shot and few45;shot settings but are not necessary for fine45;tuned models. This evidence is relevant for practioners that are faced with the choice of prompt engineering versus fine45;tuning when using LLMs for ABSA.
