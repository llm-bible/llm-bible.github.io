---
layout: publication
title: 'Minimizing Factual Inconsistency And Hallucination In Large Language Models'
authors: Muneeswaran I, Shreya Saxena, Siva Prasad, M V Sai Prakash, Advaith Shankar, Varun V, Vishal Vaddina, Saisubramaniam Gopalakrishnan
conference: "Arxiv"
year: 2023
bibkey: i2023minimizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.13878"}
tags: ['Fine-Tuning', 'Tools', 'GPT', 'Ethics and Bias', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Interpretability', 'Training Techniques', 'Pretraining Methods']
---
Large Language Models (LLMs) are widely used in critical fields such as
healthcare, education, and finance due to their remarkable proficiency in
various language-related tasks. However, LLMs are prone to generating factually
incorrect responses or "hallucinations," which can lead to a loss of
credibility and trust among users. To address this issue, we propose a
multi-stage framework that generates the rationale first, verifies and refines
incorrect ones, and uses them as supporting references to generate the answer.
The generated rationale enhances the transparency of the answer and our
framework provides insights into how the model arrived at this answer, by using
this rationale and the references to the context. In this paper, we demonstrate
its effectiveness in improving the quality of responses to drug-related
inquiries in the life sciences industry. Our framework improves traditional
Retrieval Augmented Generation (RAG) by enabling OpenAI GPT-3.5-turbo to be
14-25% more faithful and 16-22% more accurate on two datasets. Furthermore,
fine-tuning samples based on our framework improves the accuracy of smaller
open-access LLMs by 33-42% and competes with RAG on commercial models.
