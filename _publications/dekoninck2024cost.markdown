---
layout: publication
title: 'Polyrating: A Cost-effective And Bias-aware Rating System For LLM Evaluation'
authors: Jasper Dekoninck, Maximilian Baader, Martin Vechev
conference: "Arxiv"
year: 2024
bibkey: dekoninck2024cost
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.00696"}
tags: ['Ethics and Bias', 'RAG', 'Applications', 'Reinforcement Learning']
---
Rating-based human evaluation has become an essential tool to accurately
evaluate the impressive performance of large language models (LLMs). However,
current rating systems suffer from several important limitations: first, they
fail to account for biases that significantly influence evaluation results,
second, they require large and expensive preference datasets to obtain accurate
ratings, and third, they do not facilitate meaningful comparisons of model
ratings across different tasks. To address these issues, we introduce
Polyrating, an expressive and flexible rating system based on maximum a
posteriori estimation that enables a more nuanced and thorough analysis of
model performance at lower costs. Polyrating can detect and quantify biases
affecting human preferences, ensuring fairer model comparisons. Further,
Polyrating can reduce the cost of human evaluations by up to \\(41%\\) for new
models and up to \\(77%\\) for new tasks by leveraging existing benchmark scores.
Lastly, Polyrating enables direct comparisons of ratings across different
tasks, providing a comprehensive understanding of an LLMs' strengths,
weaknesses, and relative performance across different applications.
