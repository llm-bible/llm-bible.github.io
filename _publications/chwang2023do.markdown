---
layout: publication
title: 'Do Androids Know They''re Only Dreaming Of Electric Sheep?'
authors: Sky Ch-wang, Benjamin Van Durme, Jason Eisner, Chris Kedzie
conference: "Arxiv"
year: 2023
bibkey: chwang2023do
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.17249"}
tags: ['Transformer', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
We design probes trained on the internal representations of a transformer
language model to predict its hallucinatory behavior on three grounded
generation tasks. To train the probes, we annotate for span-level hallucination
on both sampled (organic) and manually edited (synthetic) reference outputs.
Our probes are narrowly trained and we find that they are sensitive to their
training domain: they generalize poorly from one task to another or from
synthetic to organic hallucinations. However, on in-domain data, they can
reliably detect hallucinations at many transformer layers, achieving 95% of
their peak performance as early as layer 4. Here, probing proves accurate for
evaluating hallucination, outperforming several contemporary baselines and even
surpassing an expert human annotator in response-level detection F1. Similarly,
on span-level labeling, probes are on par or better than the expert annotator
on two out of three generation tasks. Overall, we find that probing is a
feasible and efficient alternative to language model hallucination evaluation
when model states are available.
