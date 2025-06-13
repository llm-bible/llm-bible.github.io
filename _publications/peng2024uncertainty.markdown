---
layout: publication
title: 'Uncertainty-aware Explainable Recommendation With Large Language Models'
authors: Yicui Peng, Hao Chen, Chingsheng Lin, Guo Huang, Jinrong Hu, Hui Guo, Bin Kong, Shu Hu, Xi Wu, Xin Wang
conference: "Arxiv"
year: 2024
bibkey: peng2024uncertainty
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.03366"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'GPT', 'Interpretability', 'Fine-Tuning', 'Interpretability and Explainability', 'Prompting']
---
Providing explanations within the recommendation system would boost user
satisfaction and foster trust, especially by elaborating on the reasons for
selecting recommended items tailored to the user. The predominant approach in
this domain revolves around generating text-based explanations, with a notable
emphasis on applying large language models (LLMs). However, refining LLMs for
explainable recommendations proves impractical due to time constraints and
computing resource limitations. As an alternative, the current approach
involves training the prompt rather than the LLM. In this study, we developed a
model that utilizes the ID vectors of user and item inputs as prompts for
GPT-2. We employed a joint training mechanism within a multi-task learning
framework to optimize both the recommendation task and explanation task. This
strategy enables a more effective exploration of users' interests, improving
recommendation effectiveness and user satisfaction. Through the experiments,
our method achieving 1.59 DIV, 0.57 USR and 0.41 FCR on the Yelp, TripAdvisor
and Amazon dataset respectively, demonstrates superior performance over four
SOTA methods in terms of explainability evaluation metric. In addition, we
identified that the proposed model is able to ensure stable textual quality on
the three public datasets.
