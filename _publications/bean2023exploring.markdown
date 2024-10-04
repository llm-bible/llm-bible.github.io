---
layout: publication
title: 'Exploring The Landscape Of Large Language Models In Medical Question Answering'
authors: Bean Andrew M., Korgul Karolina, Krones Felix, Mccraith Robert, Mahdi Adam
conference: "Arxiv"
year: 2023
bibkey: bean2023exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.07225"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
With the rapid development of new large language models (LLMs), each claiming to surpass previous models, an overall picture of medical LLM research can be elusive. To address this challenge, we benchmark a range of top LLMs and identify consistent patterns which appear across models. We test \\(8\\) well-known LLMs on \\(874\\) newly collected questions from Polish medical licensing exams. For each question, we score each model on the top-1 accuracy and the distribution of probabilities assigned. We then compare with factors including question difficulty for humans, question length, and the scores of the other models. LLM accuracies were positively correlated pairwise (\\(0.29\\) to \\(0.62\\)). Model performance was also correlated with human performance (\\(0.07\\) to \\(0.16\\)), but negatively correlated to the difference between the question-level accuracy of top-scoring and bottom-scoring humans (\\(-0.16\\) to \\(-0.23\\)). The top output probability and question length were positive and negative predictors of accuracy respectively (p \\(< 0.05\\)). The top scoring LLM, GPT-4 Turbo, scored \\(82\%\\), followed by Med42, PaLM 2, Mixtral and GPT-3.5 around \\(63\%\\). We found evidence of similarities between models in which questions they answer correctly, as well as similarities with human test takers. Larger models typically performed better, but differences in training methods were also highly impactful. Model accuracy was positively correlated with confidence, but negatively correlated with question length. We expect that similar training methods will lead these patterns to persist across future models. These patterns can therefore aid medical experts in forming expectations about LLMs as a category to support application research.
