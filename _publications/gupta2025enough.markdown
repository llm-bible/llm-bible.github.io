---
layout: publication
title: 'Enough Coin Flips Can Make Llms Act Bayesian'
authors: Ritwik Gupta, Rodolfo Corona, Jiaxin Ge, Eric Wang, Dan Klein, Trevor Darrell, David M. Chan
conference: "Arxiv"
year: 2025
bibkey: gupta2025enough
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.04722'}
tags: ['Attention Mechanism', 'Few-Shot', 'Model Architecture', 'Tools', 'Prompting', 'Ethics and Bias']
---
Large language models (LLMs) exhibit the ability to generalize given few-shot
examples in their input prompt, an emergent capability known as in-context
learning (ICL). We investigate whether LLMs utilize ICL to perform structured
reasoning in ways that are consistent with a Bayesian framework or rely on
pattern matching. Using a controlled setting of biased coin flips, we find
that: (1) LLMs often possess biased priors, causing initial divergence in
zero-shot settings, (2) in-context evidence outweighs explicit bias
instructions, (3) LLMs broadly follow Bayesian posterior updates, with
deviations primarily due to miscalibrated priors rather than flawed updates,
and (4) attention magnitude has negligible effect on Bayesian inference. With
sufficient demonstrations of biased coin flips via ICL, LLMs update their
priors in a Bayesian manner.
