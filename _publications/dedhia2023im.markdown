---
layout: publication
title: Im45;promptu In45;context Composition From Image Prompts
authors: Dedhia Bhishma, Chang Michael, Snell Jake C., Griffiths Thomas L., Jha Niraj K.
conference: "Arxiv"
year: 2023
bibkey: dedhia2023im
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.17262"}
tags: ['Agentic', 'Attention Mechanism', 'Ethics And Bias', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Tools', 'Transformer']
---
Large language models are few45;shot learners that can solve diverse tasks from a handful of demonstrations. This implicit understanding of tasks suggests that the attention mechanisms over word tokens may play a role in analogical reasoning. In this work we investigate whether analogical reasoning can enable in45;context composition over composable elements of visual stimuli. First we introduce a suite of three benchmarks to test the generalization properties of a visual in45;context learner. We formalize the notion of an analogy45;based in45;context learner and use it to design a meta45;learning framework called Im45;Promptu. Whereas the requisite token granularity for language is well established the appropriate compositional granularity for enabling in45;context generalization in visual stimuli is usually unspecified. To this end we use Im45;Promptu to train multiple agents with different levels of compositionality including vector representations patch representations and object slots. Our experiments reveal tradeoffs between extrapolation abilities and the degree of compositionality with non45;compositional representations extending learned composition rules to unseen domains but performing poorly on combinatorial tasks. Patch45;based representations require patches to contain entire objects for robust extrapolation. At the same time object45;centric tokenizers coupled with a cross45;attention module generate consistent and high45;fidelity solutions with these inductive biases being particularly crucial for compositional generalization. Lastly we demonstrate a use case of Im45;Promptu as an intuitive programming interface for image generation.
