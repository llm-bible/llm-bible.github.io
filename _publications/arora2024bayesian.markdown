---
layout: publication
title: 'Bayesian Scaling Laws For In-context Learning'
authors: Aryaman Arora, Dan Jurafsky, Christopher Potts, Noah D. Goodman
conference: "Arxiv"
year: 2024
bibkey: arora2024bayesian
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.16531"}
tags: ['Fine-Tuning', 'Responsible AI', 'Pre-Training', 'GPT', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Large-Scale Training', 'Training Techniques', 'Scaling Laws', 'Prompting', 'In-Context Learning']
---
In-context learning (ICL) is a powerful technique for getting language models
to perform complex tasks with no training updates. Prior work has established
strong correlations between the number of in-context examples provided and the
accuracy of the model's predictions. In this paper, we seek to explain this
correlation by showing that ICL approximates a Bayesian learner. This
perspective gives rise to a family of novel Bayesian scaling laws for ICL. In
experiments with \mbox\{GPT-2\} models of different sizes, our scaling laws
exceed or match existing scaling laws in accuracy while also offering
interpretable terms for task priors, learning efficiency, and per-example
probabilities. To illustrate the analytic power that such interpretable scaling
laws provide, we report on controlled synthetic dataset experiments designed to
inform real-world studies of safety alignment. In our experimental protocol, we
use SFT to suppress an unwanted existing model capability and then use ICL to
try to bring that capability back (many-shot jailbreaking). We then experiment
on real-world instruction-tuned LLMs using capabilities benchmarks as well as a
new many-shot jailbreaking dataset. In all cases, Bayesian scaling laws
accurately predict the conditions under which ICL will cause the suppressed
behavior to reemerge, which sheds light on the ineffectiveness of post-training
at increasing LLM safety.
