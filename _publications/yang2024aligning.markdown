---
layout: publication
title: Aligning Llms Through Multi45;perspective User Preference Ranking45;based Feedback For Programming Question Answering
authors: Yang Hongyu, He Liyang, Hou Min, Shen Shuanghong, Li Rui, Hou Jiahui, Ma Jianhui, Zhao Junda
conference: "Arxiv"
year: 2024
bibkey: yang2024aligning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.00037"}
tags: ['Agentic', 'Applications', 'BERT', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Tools']
---
Code Community Question Answering (CCQA) seeks to tackle programming45;related issues thereby boosting productivity in both software engineering and academic research. Recent advancements in Reinforcement Learning from Human Feedback (RLHF) have transformed the fine45;tuning process of Large Language Models (LLMs) to produce responses that closely mimic human behavior. Leveraging LLMs with RLHF for practical CCQA applications has thus emerged as a promising area of study. Unlike standard code question45;answering tasks CCQA involves multiple possible answers with varying user preferences for each response. Additionally code communities often show a preference for new APIs. These challenges prevent LLMs from generating responses that cater to the diverse preferences of users in CCQA tasks. To address these issues we propose a novel framework called Aligning LLMs through Multi45;perspective User Preference Ranking45;based Feedback for Programming Question Answering (ALMupQA) to create user45;focused responses. Our approach starts with Multi45;perspective Preference Ranking Alignment (MPRA) which synthesizes varied user preferences based on the characteristics of answers from code communities. We then introduce a Retrieval45;augmented In45;context Learning (RIL) module to mitigate the problem of outdated answers by retrieving responses to similar questions from a question bank. Due to the limited availability of high45;quality multi45;answer CCQA datasets we also developed a dataset named StaCCQA from real code communities. Extensive experiments demonstrated the effectiveness of the ALMupQA framework in terms of accuracy and user preference. Compared to the base model ALMupQA showed nearly an 1137; improvement in BLEU with increases of 2037; and 17.537; in BERTScore and CodeBERTScore respectively.
