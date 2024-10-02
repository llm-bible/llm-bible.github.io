---
layout: publication
title: 'The Languini Kitchen: Enabling Language Modelling Research At Different Scales Of Compute'
authors: Stanić Aleksandar, Ashley Dylan, Serikov Oleg, Kirsch Louis, Faccio Francesco, Schmidhuber Jürgen, Hofmann Thomas, Schlag Imanol
conference: "Arxiv"
year: 2023
bibkey: stanić2023languini
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.11197"}
tags: ['Efficiency And Optimization', 'GPT', 'Large Scale Training', 'Model Architecture', 'Scaling Laws', 'Training Techniques']
---
'The Languini Kitchen serves as both a research collective and codebase designed to empower researchers with limited computational resources to contribute meaningfully to the field of language modelling. We introduce an experimental protocol that enables model comparisons based on equivalent compute, measured in accelerator hours. The number of tokens on which a model is trained is defined by the model''s throughput and the chosen compute class. Notably, this approach avoids constraints on critical hyperparameters which affect total parameters or floating-point operations. For evaluation, we pre-process an existing large, diverse, and high-quality dataset of books that surpasses existing academic benchmarks in quality, diversity, and document length. On it, we compare methods based on their empirical scaling trends which are estimated through experiments at various levels of compute. This work also provides two baseline models: a feed-forward model derived from the GPT-2 architecture and a recurrent model in the form of a novel LSTM with ten-fold throughput. While the GPT baseline achieves better perplexity throughout all our levels of compute, our LSTM baseline exhibits a predictable and more favourable scaling law. This is due to the improved throughput and the need for fewer training tokens to achieve the same decrease in test perplexity. Extrapolating the scaling laws leads of both models results in an intersection at roughly 50,000 accelerator hours. We hope this work can serve as the foundation for meaningful and reproducible language modelling research.'
