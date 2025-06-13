---
layout: publication
title: 'Qualeval: Qualitative Evaluation For Model Improvement'
authors: Vishvak Murahari, Ameet Deshpande, Peter Clark, Tanmay Rajpurohit, Ashish Sabharwal, Karthik Narasimhan, Ashwin Kalyan
conference: "Arxiv"
year: 2023
bibkey: murahari2023qualitative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.02807"}
tags: ['RAG', 'Training Techniques', 'Reinforcement Learning']
---
Quantitative evaluation metrics have traditionally been pivotal in gauging
the advancements of artificial intelligence systems, including large language
models (LLMs). However, these metrics have inherent limitations. Given the
intricate nature of real-world tasks, a single scalar to quantify and compare
is insufficient to capture the fine-grained nuances of model behavior. Metrics
serve only as a way to compare and benchmark models, and do not yield
actionable diagnostics, thus making the model improvement process challenging.
Model developers find themselves amid extensive manual efforts involving
sifting through vast datasets and attempting hit-or-miss adjustments to
training data or setups. In this work, we address the shortcomings of
quantitative metrics by proposing QualEval, which augments quantitative scalar
metrics with automated qualitative evaluation as a vehicle for model
improvement. QualEval uses a powerful LLM reasoner and our novel flexible
linear programming solver to generate human-readable insights that when
applied, accelerate model improvement. The insights are backed by a
comprehensive dashboard with fine-grained visualizations and
human-interpretable analyses. We corroborate the faithfulness of QualEval by
demonstrating that leveraging its insights, for example, improves the absolute
performance of the Llama 2 model by up to 15% points relative on a challenging
dialogue task (DialogSum) when compared to baselines. QualEval successfully
increases the pace of model development, thus in essence serving as a
data-scientist-in-a-box. Given the focus on critiquing and improving current
evaluation metrics, our method serves as a refreshingly new technique for both
model evaluation and improvement.
