---
layout: publication
title: 'Lusifer: Llm-based User Simulated Feedback Environment For Online Recommender Systems'
authors: Danial Ebrat, Eli Paradalis, Luis Rueda
conference: "Arxiv"
year: 2024
bibkey: ebrat2024llm
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.13362'}
tags: ['Agentic', 'Interpretability and Explainability', 'Training Techniques', 'Tools', 'RecSys', 'Reinforcement Learning']
---
Reinforcement learning (RL) recommender systems often rely on static datasets
that fail to capture the fluid, ever changing nature of user preferences in
real-world scenarios. Meanwhile, generative AI techniques have emerged as
powerful tools for creating synthetic data, including user profiles and
behaviors. Recognizing this potential, we introduce Lusifer, an LLM-based
simulation environment designed to generate dynamic, realistic user feedback
for RL-based recommender training. In Lusifer, user profiles are incrementally
updated at each interaction step, with Large Language Models (LLMs) providing
transparent explanations of how and why preferences evolve. We focus on the
MovieLens dataset, extracting only the last 40 interactions for each user, to
emphasize recent behavior. By processing textual metadata (such as movie
overviews and tags) Lusifer creates more context aware user states and
simulates feedback on new items, including those with limited or no prior
ratings. This approach reduces reliance on extensive historical data and
facilitates cold start scenario handling and adaptation to out of distribution
cases. Our experiments compare Lusifer with traditional collaborative filtering
models, revealing that while Lusifer can be comparable in predictive accuracy,
it excels at capturing dynamic user responses and yielding explainable results
at every step. These qualities highlight its potential as a scalable, ethically
sound alternative to live user experiments, supporting iterative and
user-centric evaluations of RL-based recommender strategies. Looking ahead, we
envision Lusifer serving as a foundational tool for exploring generative
AI-driven user simulations, enabling more adaptive and personalized
recommendation pipelines under real world constraints.
