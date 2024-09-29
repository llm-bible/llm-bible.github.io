---
layout: publication
title: Can You Follow Me Testing Situational Understanding In Chatgpt
authors: Yang Chenghao, Ettinger Allyson
conference: "Arxiv"
year: 2023
bibkey: yang2023can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.16135"}
  - {name: "Code", url: "https://github.com/yangalan123/SituationalTesting"}
tags: ['Agentic', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Understanding sentence meanings and updating information states appropriately across time 45;45; what we call situational understanding (SU) 45;45; is a critical ability for human45;like AI agents. SU is essential in particular for chat models such as ChatGPT to enable consistent coherent and effective dialogue between humans and AI. Previous works have identified certain SU limitations in non45;chatbot Large Language models (LLMs) but the extent and causes of these limitations are not well understood and capabilities of current chat45;based models in this domain have not been explored. In this work we tackle these questions proposing a novel synthetic environment for SU testing which allows us to do controlled and systematic testing of SU in chat45;oriented models through assessment of models ability to track and enumerate environment states. Our environment also allows for close analysis of dynamics of model performance to better understand underlying causes for performance patterns. We apply our test to ChatGPT the state45;of45;the45;art chatbot and find that despite the fundamental simplicity of the task the models performance reflects an inability to retain correct environment states across time. Our follow45;up analyses suggest that performance degradation is largely because ChatGPT has non45;persistent in45;context memory (although it can access the full dialogue history) and it is susceptible to hallucinated updates 45;45; including updates that artificially inflate accuracies. Our findings suggest overall that ChatGPT is not currently equipped for robust tracking of situation states and that trust in the impressive dialogue performance of ChatGPT comes with risks. We release the codebase for reproducing our test environment as well as all prompts and API responses from ChatGPT at https://github.com/yangalan123/SituationalTesting.
