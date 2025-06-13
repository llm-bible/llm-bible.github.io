---
layout: publication
title: 'Review-driven Personalized Preference Reasoning With Large Language Models For Recommendation'
authors: Jieyong Kim, Hyunseo Kim, Hyunjin Cho, Seongku Kang, Buru Chang, Jinyoung Yeo, Dongha Lee
conference: "Arxiv"
year: 2024
bibkey: kim2024review
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.06276"}
tags: ['Efficiency and Optimization', 'Tools', 'RAG', 'Distillation', 'Interpretability', 'Interpretability and Explainability']
---
Recent advancements in Large Language Models (LLMs) have demonstrated
exceptional performance across a wide range of tasks, generating significant
interest in their application to recommendation systems. However, existing
methods have not fully capitalized on the potential of LLMs, often constrained
by limited input information or failing to fully utilize their advanced
reasoning capabilities. To address these limitations, we introduce EXP3RT, a
novel LLM-based recommender designed to leverage rich preference information
contained in user and item reviews. EXP3RT is basically fine-tuned through
distillation from a teacher LLM to perform three key tasks in order: EXP3RT
first extracts and encapsulates essential subjective preferences from raw
reviews, aggregates and summarizes them according to specific criteria to
create user and item profiles. It then generates detailed step-by-step
reasoning followed by predicted rating, i.e., reasoning-enhanced rating
prediction, by considering both subjective and objective information from
user/item profiles and item descriptions. This personalized preference
reasoning from EXP3RT enhances rating prediction accuracy and also provides
faithful and reasonable explanations for recommendation. Extensive experiments
show that EXP3RT outperforms existing methods on both rating prediction and
candidate item reranking for top-k recommendation, while significantly
enhancing the explainability of recommendation systems.
