---
layout: publication
title: Improving The Reliability Of Large Language Models By Leveraging Uncertainty45;aware In45;context Learning
authors: Yang Yuchen, Li Houqiang, Wang Yanfeng, Wang Yu
conference: "Arxiv"
year: 2023
bibkey: yang2023improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.04782"}
tags: ['Applications', 'Attention Mechanism', 'Language Modeling', 'Model Architecture', 'RAG', 'Tools']
---
In recent years large45;scale language models (LLMs) have gained attention for their impressive text generation capabilities. However these models often face the challenge of hallucination which undermines their reliability. In this study we introduce an uncertainty45;aware in45;context learning framework to empower the model to enhance or reject its output in response to uncertainty. Human45;defined methods for estimating uncertainty typically assume that uncertainty is lower when the models response is correct compared to when it is incorrect. However setting a precise threshold to distinguish correctness is challenging. Therefore we introduce uncertainty information as an intermediary variable that implicitly influences the models behavior. Our innovative uncertainty45;aware in45;context learning framework involves fine45;tuning the LLM using a calibration dataset. Our aim is to improve the models responses by filtering out answers with high uncertainty while considering the models knowledge limitations. We evaluate the models knowledge by examining multiple responses to the same question for the presence of a correct answer. When the model lacks relevant knowledge the response should indicate that the question cannot be answered. Conversely when the model has relevant knowledge the response should provide the correct answer. Extensive experiments confirm the effectiveness of our framework leading to two key findings. First the logit output values of the LLM partly reflect inherent uncertainty. Second our model autonomously recognizes uncertainty resulting in improved responses.
