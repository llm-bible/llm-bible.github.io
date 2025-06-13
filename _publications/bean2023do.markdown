---
layout: publication
title: 'Do Large Language Models Have Shared Weaknesses In Medical Question Answering?'
authors: Andrew M. Bean, Karolina Korgul, Felix Krones, Robert Mccraith, Adam Mahdi
conference: "Arxiv"
year: 2023
bibkey: bean2023do
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.07225"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'Applications']
---
Large language models (LLMs) have made rapid improvement on medical
benchmarks, but their unreliability remains a persistent challenge for safe
real-world uses. To design for the use LLMs as a category, rather than for
specific models, requires developing an understanding of shared strengths and
weaknesses which appear across models. To address this challenge, we benchmark
a range of top LLMs and identify consistent patterns across models. We test
\\(16\\) well-known LLMs on \\(874\\) newly collected questions from Polish medical
licensing exams. For each question, we score each model on the top-1 accuracy
and the distribution of probabilities assigned. We then compare these results
with factors such as question difficulty for humans, question length, and the
scores of the other models. LLM accuracies were positively correlated pairwise
(\\(0.39\\) to \\(0.58\\)). Model performance was also correlated with human
performance (\\(0.09\\) to \\(0.13\\)), but negatively correlated to the difference
between the question-level accuracy of top-scoring and bottom-scoring humans
(\\(-0.09\\) to \\(-0.14\\)). The top output probability and question length were
positive and negative predictors of accuracy respectively (p\\(< 0.05\\)). The top
scoring LLM, GPT-4o Turbo, scored \\(84%\\), with Claude Opus, Gemini 1.5 Pro and
Llama 3/3.1 between \\(74%\\) and \\(79%\\). We found evidence of similarities
between models in which questions they answer correctly, as well as
similarities with human test takers. Larger models typically performed better,
but differences in training, architecture, and data were also highly impactful.
Model accuracy was positively correlated with confidence, but negatively
correlated with question length. We find similar results with older models, and
argue that these patterns are likely to persist across future models using
similar training methods.
