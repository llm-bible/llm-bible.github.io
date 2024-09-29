---
layout: publication
title: Self45;consistency Of Large Language Models Under Ambiguity
authors: Bartsch Henning, Jorgensen Ole, Rosati Domenic, Hoelscher-obermaier Jason, Pfau Jacob
conference: "Arxiv"
year: 2023
bibkey: bartsch2023self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.13439"}
tags: ['Applications', 'Interpretability And Explainability', 'Prompting', 'RAG', 'Security', 'Training Techniques']
---
Large language models (LLMs) that do not give consistent answers across contexts are problematic when used for tasks with expectations of consistency e.g. question45;answering explanations etc. Our work presents an evaluation benchmark for self45;consistency in cases of under45;specification where two or more answers can be correct. We conduct a series of behavioral experiments on the OpenAI model suite using an ambiguous integer sequence completion task. We find that average consistency ranges from 6737; to 8237; far higher than would be predicted if a models consistency was random and increases as model capability improves. Furthermore we show that models tend to maintain self45;consistency across a series of robustness checks including prompting speaker changes and sequence length changes. These results suggest that self45;consistency arises as an emergent capability without specifically training for it. Despite this we find that models are uncalibrated when judging their own consistency with models displaying both over45; and under45;confidence. We also propose a nonparametric test for determining from token output distribution whether a model assigns non45;trivial probability to alternative answers. Using this test we find that despite increases in self45;consistency models usually place significant weight on alternative inconsistent answers. This distribution of probability mass provides evidence that even highly self45;consistent models internally compute multiple possible responses.
