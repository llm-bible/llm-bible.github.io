---
layout: publication
title: 'Review-llm: Harnessing Large Language Models For Personalized Review Generation'
authors: Peng Qiyao, Liu Hongtao, Xu Hongyan, Yang Qing, Shao Minglai, Wang Wenjun
conference: "Arxiv"
year: 2024
bibkey: peng2024review
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.07487"}
tags: ['Fine Tuning', 'GPT', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Survey Paper', 'Training Techniques']
---
Product review generation is an important task in recommender systems which could provide explanation and persuasiveness for the recommendation. Recently Large Language Models (LLMs e.g. ChatGPT) have shown superior text modeling and generating ability which could be applied in review generation. However directly applying the LLMs for generating reviews might be troubled by the polite phenomenon of the LLMs and could not generate personalized reviews (e.g. negative reviews). In this paper we propose Review-LLM that customizes LLMs for personalized review generation. Firstly we construct the prompt input by aggregating user historical behaviors which include corresponding item titles and reviews. This enables the LLMs to capture user interest features and review writing style. Secondly we incorporate ratings as indicators of satisfaction into the prompt which could further improve the models understanding of user preferences and the sentiment tendency control of generated reviews. Finally we feed the prompt text into LLMs and use Supervised Fine-Tuning (SFT) to make the model generate personalized reviews for the given user and target item. Experimental results on the real-world dataset show that our fine-tuned model could achieve better review generation performance than existing close-source LLMs.
