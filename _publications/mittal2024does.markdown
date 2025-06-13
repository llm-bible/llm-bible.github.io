---
layout: publication
title: 'Does Learning The Right Latent Variables Necessarily Improve In-context Learning?'
authors: Sarthak Mittal, Eric Elmoznino, Leo Gagnon, Sangnie Bhardwaj, Dhanya Sridhar, Guillaume Lajoie
conference: "Arxiv"
year: 2024
bibkey: mittal2024does
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.19162"}
tags: ['Transformer', 'GPT', 'Ethics and Bias', 'Interpretability and Explainability', 'RAG', 'Model Architecture', 'Language Modeling', 'Attention Mechanism', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
Large autoregressive models like Transformers can solve tasks through
in-context learning (ICL) without learning new weights, suggesting avenues for
efficiently solving new tasks. For many tasks, e.g., linear regression, the
data factorizes: examples are independent given a task latent that generates
the data, e.g., linear coefficients. While an optimal predictor leverages this
factorization by inferring task latents, it is unclear if Transformers
implicitly do so or if they instead exploit heuristics and statistical
shortcuts enabled by attention layers. Both scenarios have inspired active
ongoing work. In this paper, we systematically investigate the effect of
explicitly inferring task latents. We minimally modify the Transformer
architecture with a bottleneck designed to prevent shortcuts in favor of more
structured solutions, and then compare performance against standard
Transformers across various ICL tasks. Contrary to intuition and some recent
works, we find little discernible difference between the two; biasing towards
task-relevant latent variables does not lead to better out-of-distribution
performance, in general. Curiously, we find that while the bottleneck
effectively learns to extract latent task variables from context, downstream
processing struggles to utilize them for robust prediction. Our study
highlights the intrinsic limitations of Transformers in achieving structured
ICL solutions that generalize, and shows that while inferring the right latents
aids interpretability, it is not sufficient to alleviate this problem.
