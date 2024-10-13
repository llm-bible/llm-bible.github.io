---
layout: publication
title: 'Aligning Llms Through Multi-perspective User Preference Ranking-based Feedback For Programming Question Answering'
authors: Yang Hongyu, He Liyang, Hou Min, Shen Shuanghong, Li Rui, Hou Jiahui, Ma Jianhui, Zhao Junda
conference: "Arxiv"
year: 2024
bibkey: yang2024aligning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.00037"}
tags: ['Agentic', 'Applications', 'BERT', 'Fine Tuning', 'In Context Learning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Code Community Question Answering (CCQA) seeks to tackle programming-related
issues, thereby boosting productivity in both software engineering and academic
research. Recent advancements in Reinforcement Learning from Human Feedback
(RLHF) have transformed the fine-tuning process of Large Language Models (LLMs)
to produce responses that closely mimic human behavior. Leveraging LLMs with
RLHF for practical CCQA applications has thus emerged as a promising area of
study. Unlike standard code question-answering tasks, CCQA involves multiple
possible answers, with varying user preferences for each response.
Additionally, code communities often show a preference for new APIs. These
challenges prevent LLMs from generating responses that cater to the diverse
preferences of users in CCQA tasks. To address these issues, we propose a novel
framework called Aligning LLMs through Multi-perspective User Preference
Ranking-based Feedback for Programming Question Answering (ALMupQA) to create
user-focused responses. Our approach starts with Multi-perspective Preference
Ranking Alignment (MPRA), which synthesizes varied user preferences based on
the characteristics of answers from code communities. We then introduce a
Retrieval-augmented In-context Learning (RIL) module to mitigate the problem of
outdated answers by retrieving responses to similar questions from a question
bank. Due to the limited availability of high-quality, multi-answer CCQA
datasets, we also developed a dataset named StaCCQA from real code communities.
Extensive experiments demonstrated the effectiveness of the ALMupQA framework
in terms of accuracy and user preference. Compared to the base model, ALMupQA
showed nearly an 11% improvement in BLEU, with increases of 20% and 17.5% in
BERTScore and CodeBERTScore, respectively.
