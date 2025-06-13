---
layout: publication
title: 'Memory Assisted LLM For Personalized Recommendation System'
authors: Jiarui Chen
conference: "Arxiv"
year: 2025
bibkey: chen2025memory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.03824"}
tags: ['Fine-Tuning', 'Training Techniques', 'Prompting', 'Pretraining Methods']
---
Large language models (LLMs) have demonstrated significant potential in
solving recommendation tasks. With proven capabilities in understanding user
preferences, LLM personalization has emerged as a critical area for providing
tailored responses to individuals. Current studies explore personalization
through prompt design and fine-tuning, paving the way for further research in
personalized LLMs. However, existing approaches are either costly and
inefficient in capturing diverse user preferences or fail to account for timely
updates to user history. To address these gaps, we propose the Memory-Assisted
Personalized LLM (MAP). Through user interactions, we first create a history
profile for each user, capturing their preferences, such as ratings for
historical items. During recommendation, we extract relevant memory based on
similarity, which is then incorporated into the prompts to enhance personalized
recommendations. In our experiments, we evaluate MAP using a sequential rating
prediction task under two scenarios: single domain, where memory and tasks are
from the same category (e.g., movies), and cross-domain (e.g., memory from
movies and recommendation tasks in books). The results show that MAP
outperforms regular LLM-based recommenders that integrate user history directly
through prompt design. Moreover, as user history grows, MAP's advantage
increases in both scenarios, making it more suitable for addressing successive
personalized user requests.
