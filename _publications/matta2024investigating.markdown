---
layout: publication
title: 'Investigating Cost-efficiency Of Llm-generated Training Data For Conversational Semantic Frame Analysis'
authors: Shiho Matta, Yin Jou Huang, Fei Cheng, Hirokazu Kiyomaru, Yugo Murawaki
conference: "Arxiv"
year: 2024
bibkey: matta2024investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.06550"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Few-Shot', 'GPT']
---
Recent studies have demonstrated that few-shot learning allows LLMs to
generate training data for supervised models at a low cost. However, the
quality of LLM-generated data may not entirely match that of human-labeled
data. This raises a crucial question: how should one balance the trade-off
between the higher quality but more expensive human data and the lower quality
yet substantially cheaper LLM-generated data? In this paper, we synthesized
training data for conversational semantic frame analysis using GPT-4 and
examined how to allocate budgets optimally to achieve the best performance. Our
experiments, conducted across various budget levels, reveal that optimal
cost-efficiency is achieved by combining both human and LLM-generated data
across a wide range of budget levels. Notably, as the budget decreases, a
higher proportion of LLM-generated data becomes more preferable.
