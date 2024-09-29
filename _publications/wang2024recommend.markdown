---
layout: publication
title: To Recommend or Not Recommendability Identification in Conversations with Pre-trained Language Models
authors: Wang Zhefan, Ma Weizhi, Zhang Min
conference: "Arxiv"
year: 2024
bibkey: wang2024recommend
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.18628"}
tags: ['Applications', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
Most current recommender systems primarily focus on what to recommend assuming users always require personalized recommendations. However with the widely spread of ChatGPT and other chatbots a more crucial problem in the context of conversational systems is how to minimize user disruption when we provide recommendation services for users. While previous research has extensively explored different user intents in dialogue systems fewer efforts are made to investigate whether recommendations should be provided. In this paper we formally define the recommendability identification problem which aims to determine whether recommendations are necessary in a specific scenario. First we propose and define the recommendability identification task which investigates the need for recommendations in the current conversational context. A new dataset is constructed. Subsequently we discuss and evaluate the feasibility of leveraging pre-trained language models (PLMs) for recommendability identification. Finally through comparative experiments we demonstrate that directly employing PLMs with zero-shot results falls short of meeting the task requirements. Besides fine-tuning or utilizing soft prompt techniques yields comparable results to traditional classification methods. Our work is the first to study recommendability before recommendation and provides preliminary ways to make it a fundamental component of the future recommendation system.
