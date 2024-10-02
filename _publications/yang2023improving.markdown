---
layout: publication
title: 'Improving The Reliability Of Large Language Models By Leveraging Uncertainty-aware In-context Learning'
authors: Yang Yuchen, Li Houqiang, Wang Yanfeng, Wang Yu
conference: "Arxiv"
year: 2023
bibkey: yang2023improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.04782"}
tags: ['Applications', 'Attention Mechanism', 'Fine Tuning', 'In Context Learning', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
In recent years, large-scale language models (LLMs) have gained attention for their impressive text generation capabilities. However, these models often face the challenge of hallucination, which undermines their reliability. In this study, we introduce an uncertainty-aware in-context learning framework to empower the model to enhance or reject its output in response to uncertainty. Human-defined methods for estimating uncertainty typically assume that uncertainty is lower when the model's response is correct compared to when it is incorrect. However, setting a precise threshold to distinguish correctness is challenging. Therefore, we introduce uncertainty information as an intermediary variable that implicitly influences the model's behavior. Our innovative uncertainty-aware in-context learning framework involves fine-tuning the LLM using a calibration dataset. Our aim is to improve the model's responses by filtering out answers with high uncertainty while considering the model's knowledge limitations. We evaluate the model's knowledge by examining multiple responses to the same question for the presence of a correct answer. When the model lacks relevant knowledge, the response should indicate that the question cannot be answered. Conversely, when the model has relevant knowledge, the response should provide the correct answer. Extensive experiments confirm the effectiveness of our framework, leading to two key findings. First, the logit output values of the LLM partly reflect inherent uncertainty. Second, our model autonomously recognizes uncertainty, resulting in improved responses.
