---
layout: publication
title: The Pitfalls Of Next45;token Prediction
authors: Bachmann Gregor, Nagarajan Vaishnavh
conference: "Arxiv"
year: 2024
bibkey: bachmann2024pitfalls
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.06963"}
  - {name: "Code", url: "https://github.com/gregorbachmann/Next&#45;Token&#45;Failures"}
tags: ['Fine Tuning', 'GPT', 'Has Code', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Can a mere next45;token predictor faithfully model human intelligence We crystallize this emerging concern and correct popular misconceptions surrounding it and advocate a simple multi45;token objective. As a starting point we argue that the two often45;conflated phases of next45;token prediction 45;45; autoregressive inference and teacher45;forced training 45;45; must be treated distinctly. The popular criticism that errors can compound during autoregressive inference crucially assumes that teacher45;forcing has learned an accurate next45;token predictor. This assumption sidesteps a more deep45;rooted problem we expose in certain classes of tasks teacher45;forcing can simply fail to learn an accurate next45;token predictor in the first place. We describe a general mechanism of how teacher45;forcing can fail and design a minimal planning task where both the Transformer and the Mamba architecture empirically fail in that manner 45;45; remarkably despite the task being straightforward to learn. Finally we provide preliminary evidence that this failure can be resolved using a simple modification that predicts multiple tokens in advance. We hope this finding can ground future debates and inspire explorations beyond the next45;token prediction paradigm. We make our code available under https://github.com/gregorbachmann/Next&#45;Token&#45;Failures
