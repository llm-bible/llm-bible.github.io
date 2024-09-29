---
layout: publication
title: Characterizing Learning Curves During Language Model Pre-training Learning Forgetting And Stability
authors: Chang Tyler A., Tu Zhuowen, Bergen Benjamin K.
conference: "Arxiv"
year: 2023
bibkey: chang2023characterizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.15419"}
tags: ['GPT', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
How do language models learn to make predictions during pre-training To study this we extract learning curves from five autoregressive English language model pre-training runs for 1M unseen tokens in context. We observe that the language models generate short repetitive phrases before learning to generate longer and more coherent text. We also find that individual tokens often exhibit sudden increases or decreases in loss that are surprisingly consistent across pre-training runs. To better understand these fluctuations we quantify the final surprisal within-run variability age of acquisition forgettability and cross-run variability of learning curves for individual tokens in context. More frequent tokens reach lower final surprisals exhibit less variability within and across pre-training runs are learned earlier and are less likely to be forgotten during pre-training. Higher n-gram probabilities further accentuate these effects. Independent of the target token shorter and more frequent contexts correlate with marginally more stable and quickly acquired predictions. Based on our results we argue for the existence of sequential learning dependencies between different model capabilities and we characterize language model learning as early n-gram learning before gradual refinement of tail n-gram predictions.
