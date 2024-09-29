---
layout: publication
title: User-aware Prefix-tuning Is A Good Learner For Personalized Image Captioning
authors: Wang Xuan, Wang Guanhong, Chai Wenhao, Zhou Jiayu, Wang Gaoang
conference: "Arxiv"
year: 2023
bibkey: wang2023user
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.04793"}
tags: ['GPT', 'Merging', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Transformer']
---
Image captioning bridges the gap between vision and language by automatically generating natural language descriptions for images. Traditional image captioning methods often overlook the preferences and characteristics of users. Personalized image captioning solves this problem by incorporating user prior knowledge into the model such as writing styles and preferred vocabularies. Most existing methods emphasize the user context fusion process by memory networks or transformers. However these methods ignore the distinct domains of each dataset. Therefore they need to update the entire caption model parameters when meeting new samples which is time-consuming and calculation-intensive. To address this challenge we propose a novel personalized image captioning framework that leverages user context to consider personality factors. Additionally our framework utilizes the prefix-tuning paradigm to extract knowledge from a frozen large language model reducing the gap between different language domains. Specifically we employ CLIP to extract the visual features of an image and align the semantic space using a query-guided mapping network. By incorporating the transformer layer we merge the visual features with the users contextual prior knowledge to generate informative prefixes. Moreover we employ GPT-2 as the frozen large language model. With a small number of parameters to be trained our model performs efficiently and effectively. Our model outperforms existing baseline models on Instagram and YFCC100M datasets across five evaluation metrics demonstrating its superiority including twofold improvements in metrics such as BLEU-4 and CIDEr.
