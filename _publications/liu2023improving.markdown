---
layout: publication
title: 'Improving Large Language Model Fine-tuning For Solving Math Problems'
authors: Yixin Liu, Avi Singh, C. Daniel Freeman, John D. Co-reyes, Peter J. Liu
conference: "Arxiv"
year: 2023
bibkey: liu2023improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.10047"}
tags: ['Pretraining Methods', 'Training Techniques', 'Fine-Tuning', 'Few-Shot']
---
Despite their success in many natural language tasks, solving math problems
remains a significant challenge for large language models (LLMs). A large gap
exists between LLMs' pass-at-one and pass-at-N performance in solving math
problems, suggesting LLMs might be close to finding correct solutions,
motivating our exploration of fine-tuning methods to unlock LLMs' performance.
Using the challenging MATH dataset, we investigate three fine-tuning
strategies: (1) solution fine-tuning, where we fine-tune to generate a detailed
solution for a given math problem; (2) solution-cluster re-ranking, where the
LLM is fine-tuned as a solution verifier/evaluator to choose among generated
candidate solution clusters; (3) multi-task sequential fine-tuning, which
integrates both solution generation and evaluation tasks together efficiently
to enhance the LLM performance. With these methods, we present a thorough
empirical study on a series of PaLM 2 models and find: (1) The quality and
style of the step-by-step solutions used for fine-tuning can make a significant
impact on the model performance; (2) While solution re-ranking and majority
voting are both effective for improving the model performance when used
separately, they can also be used together for an even greater performance
boost; (3) Multi-task fine-tuning that sequentially separates the solution
generation and evaluation tasks can offer improved performance compared with
the solution fine-tuning baseline. Guided by these insights, we design a
fine-tuning recipe that yields approximately 58.8% accuracy on the MATH dataset
with fine-tuned PaLM 2-L models, an 11.2% accuracy improvement over the
few-shot performance of pre-trained PaLM 2-L model with majority voting.
